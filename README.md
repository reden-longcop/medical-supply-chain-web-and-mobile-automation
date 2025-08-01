# medical-supply-chain-test-automation
medical-supply-chain test automation for web and mobile testing in test environment.

## 🚀 Getting Started
### Prerequisites
Download python: 
```bash
https://www.python.org/downloads/
```
Verify the installation:
``` bash
python --version
```
Verify pip installed:
``` bash
pip --version
```
Install node: 
```bash
https://nodejs.org/en
```
Verify installation:
```bash
node --version
npm --version
```
Install Appium:
```bash
npm install -g appium
```
Verify installation:
```bash
appium --version
```
Download Appium Inspector: 
```bash
https://github.com/appium/appium-inspector/releases
```
<br>

### Setting Up the Project
Clone this repository:
``` bash
git clone https://github.com/reden-longcop/medical-supply-chain-test-automation.git
```
Activate Virtual Environment:
```bash
source kadena-app-env/bin/activate
```
Install test requirements:
```bash
pip install -r requirements.txt
```

<br>

### Run the Robot Test Automation
By default, you can run:
```bash
robot -d reports test-scenarios/
```
You can also run the automation with tags:
```bash
robot -d reports -i Sample test-scenarios/
```
You can also change the browser, by default it is set to Edge browser:
```bash
robot -d reports -v BROWSER:Chrome
```

<br>

### References
For robot syntax and documentaions:<br>
<a href="https://robotframework.org/">Robotframework official web page</a><br>
<a href="https://robotframework.org/?tab=builtin#resources">Robotframework builtin libraries</a><br>
<a href="https://robotframework.org/SeleniumLibrary/SeleniumLibrary.html">SeleniumLibrary</a><br>
<a href="https://serhatbolsu.github.io/robotframework-appiumlibrary/AppiumLibrary.html#library-documentation-top">AppiumLibrary</a>
