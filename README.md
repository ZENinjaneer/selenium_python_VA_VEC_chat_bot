# selenium_python_VA_VEC_chat_bot
Use this to automate getting connected to Virginia's unemployment agents so you don't have to manually do it all day

Things you'll need:
* [Python 2.7, 3.4+](https://www.python.org/downloads/)
* Driver for browser ([Chrome](https://sites.google.com/a/chromium.org/chromedriver/downloads), [Firefox](https://github.com/mozilla/geckodriver/releases)) You'll need to get a driver that matches your browser's version. You can find your browsers version in Chrome by going to the three dot menu in the upper right -> help -> About Google Chrome
* Selenium package ([pypi](https://pypi.org/project/selenium/), [conda](https://anaconda.org/conda-forge/selenium))

Just edit the chat.py script with your personal info and this and run it. This script will engage with the Virginia Unemployment Chat bot and repeatedly fill out the requisite information for you. It also mutes the chat audio and will play a Zelda "Du nu nu nahhhhhh!" once it has landed you in a queue with an Agent.

To run the script you just need to install python, put the appropriate version of Chrome driver in the same directory as the script, install the Selenium webDriver package into python (there are instructions on conda/pypi on how to do this) and then run the script with `python -m chat.py`

I know this isn't super user friendly at the moment and I've been working on porting it to java so it's easier to run, but for now I hope this helps people and can free them up from being tethered to the phone or computer all day. If there is enough interest I can do more work to make it a little easier - if there are any other programmers out there, feel free to reach out, branch, whatever with the code.

Other useful links:
[Selenium homepage](https://www.selenium.dev/)
[Selenium Docs](https://www.selenium.dev/documentation/en/getting_started_with_webdriver/browsers/)
Selenium IDE add-on ([Chrome](https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd), [FireFox](https://addons.mozilla.org/en-GB/firefox/addon/selenium-ide/))
[YouTube Tutorial I started with](https://youtu.be/5FUdrBq-WFo)
