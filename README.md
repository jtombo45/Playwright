# Install Playwright
To follow the tutorial ensure Node.js and Visual Studio Code and Playwright are downloaded.

## Install Node.js
Node.js is a cross-platform, open-source JavaScript runtime environment that can run on Windows, Linux, Unix, macOS, and more. 
Node.js runs on the V8 JavaScript engine, and executes JavaScript code outside a web browser. 
Node.js lets developers use JavaScript to write command line tools and for server-side scripting. <br>
[https://nodejs.org/en](https://nodejs.org/en)

## Install Visual Studio Code:
Visual Studio Code, also commonly referred to as VS Code, is an integrated development environment developed by Microsoft for Windows, Linux, macOS and web browsers.<br>
[https://code.visualstudio.com/](https://code.visualstudio.com/)

## Install Playwright
Playwright is an open-source automation library for browser testing and web scraping developed by Microsoft and launched on 31 January 2020, which has since become popular among programmers and web developers. 
Playwright provides the ability to automate browser tasks in Chromium, Firefox and WebKit with a single API. <br>
[https://playwright.dev/](https://playwright.dev/) - installation and documentation <br>
[https://github.com/microsoft/playwright](https://github.com/microsoft/playwright) - github repository

Navigate to your project folder and run the following command:
```
npm init playwright@latest
```
Select JavaScript when prompted for language, test folder for the location of end-to-end tests, and say no to GitHuib Action workflow.
Choose true for Install Playwright browser.

## Run Test
Navigate to the project root folder and enter the following command:
```
npx playwright test --headed
```
