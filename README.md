# Auto_WebCrawler.exe
It is a code that can be crawled on Google and Naver, and can be executed directly as a code, and can be converted into an executable file and used.


## Demo
<p align="center"><img src="./Demo.gif" width="90%" height="90%" title="70px" alt="memoryblock"></p>

## Getting Started
* Check your chrome version and download the correct chromedriver for your version<br>
* Check your chrome version link --> chrome://settings/help <br>
* Other chromedriver download link --> https://chromedriver.chromium.org/downloads<br>
* The chromedriver included in the repo is **87.0.4280.88**<br>
* If you download another chromedriver, replace it with the repo's chromedriver.<br>


**Download git and install module**
```Shell
git clone https://github.com/cjf8899/WebCrawler_exe.git

cd WebCrawler_exe

pip install pyinstaller

pyinstaller --onefile main.py

cd dist

cp -r ../chromedriver .
```

the structures would like

```
~/WebCrawler_exe/
    -- chromedriver
      --chromedriver.exe
    --dist
      --main.exe
      --chromedriver
        --chromedriver.exe
    --collect_links.py
    --keywords.txt
    --LICENSE
    --main.py
    --requirements.txt
    ...
```

**Enter the main.exe file and run it!**


## Development Environment

* Windows 10
* Python
* Visual Studio Code

## Referenced. Thank you all
code : https://github.com/YoongiKim/AutoCrawler
