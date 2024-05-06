# symphony
Automate saucedemo.com using playwright javascript, verify items are sorted A - Z , change sorting  to Name Z to A , implement assertions and provide clear instructions on the Read Me file. 

Playwright UI Automation Steps.

Open command line terminal on Mac
Install Homebrew (optional): With Homebrew you can easily do other installations with ease.
Check installations present on brew :  [copy on terminal] brew list
Install nodejs using Homebrew : [copy on terminal] brew install node
Step above installs nodejs and npm..  
Verify if node is installed : [copy on terminal] node -v
Verify if npm is installed : [copy on terminal] npm -v

Go to the directory you want to use and create a folder (Or manually create a folder on Desktop to drag and drop on VScode or import)
Go to location where you want to create folder and type cmd.exe. Then Enter or [copy on terminal] cd /Applications/Android_folder/
[copy on terminal] mkdir symphony
Navigate into the directory : cd /Applications/Android_folder/symphony
Initialize a new nodejs project : [copy on terminal] npm init -y
Install Playwright as a dependency: [copy on terminal] npm install playwright --save-dev

Create a new Javascript file, saucedemo-test.js in directory : [copy on terminal] touch saucedemo-test.js

Use homebrew to install visual-studio-code
 [copy on terminal]: brew install visual-studio-code
Open file in visual studio code: [copy on terminal] code saucedemo-test.js
Write code and use Automatically save option from file dropdown..........

STEP 2 (Most Preferred)
     
11. Manually open a folder, name symphony on Desktop (or preffered location)

Open installed VSCode.
import symphony folder or drag and drop on openned vscode 
From extension in VSC, install code runner, Playwright Test for VSCode.
Go to view, command palette search for playwright install click, then check all boxes, choosing javascript, install
Package.json, Playwright config present on dashboard.
create a file, saucedemo_test.spec.js as a file in the symphony folder under test.
familiarize self with terminal commands
- npx playwright test - to run all test
- npx playwright test --ui : watch mode
- npx playwright codegen - to open playwright inspector, this records steps on the website. 
- npx playwright test saucedemo_test.spec.js - for running specific file.
- npx playwright test saucedemo_test.spec.js --project chromium - for specific browser, here chromium
- npx playwright test saucedemo_test.spec.js --headed - for headed visual ui test
- npx playwright test saucedemo_test.spec.js --project firefox --headed --debug : this is used to debug as it traces breakpoint in ui mode 
