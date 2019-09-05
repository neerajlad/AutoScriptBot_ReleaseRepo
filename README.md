# AutoScriptBot

How about hearing that AutoScriptBot will help you to setup and run your automation scripts without writing a single line of code and gives your step by step execution status LIVE. Isn’t it cool. Yes! You heard is correct. This is a AutoScriptBot is codeless automation setup. 

## Features: 

	- Support Web(Chrome, Firefox) and Android
	- Parallel execution of Android App 
	- Live step by step execution status
	- Nice Dashboard for executed suites and current suite status
	- No more waiting for whole scripts completion
	- Ignore element in case element is sometime display and sometime not display
	- Skip the steps if you want

## Prerequisite:

### Java 1.7 and above setup

* Website Test using Selenium:
	
	- Download [ChromeWebDriver](https://chromedriver.chromium.org/downloads).
	- Download [Geckodriver](https://github.com/mozilla/geckodriver/releases) 

* Android Test using Appium on Real Device/Simulator

	- CLI Appium Server setup (Port number starts from 4723 and goes on)
	- ADB Setup and ADB must be running 
	- Android studio
 
* Tested on Operating System:

	- Mac OS
	
 
## Supported Platform:

### Web Browsers:

	- Chrome : Default installed version (No parallel)
	- Firefox 

### Android devices:

	- Real Device
	- Emulator 

## Installation of Servers:

	- MySql Server
	- Tomcat Server

## Supported Actions:

### Web:

	- Click - Click on WebElement
	- SendKey - SendKey into textbox
	- Clear - Clear the text field
	- VerifyText - Compare WebElement actual value with Expected Value
	- VerifyIsDisplayed - Check WebElement is displayed or not
	- VerifyIsEnabled - Check WebElement is Enabled or not
	- VerifyIsClickable - Check WebElement is Clickable or not
	- WaitUntilVisible - Wait until WebElement is visible 
	- WaitUntilClickable - Wait until WebElement is clickable
	- WaitUntilInvisible - Wait until WebElement is Invisible
	- Wait - Wait for given given time duration in seconds. Enter value in Miliseconds 
	- SelectDropDownByValue - Select a value from the dropdown by Value displayed in the dropdown
	- GoTo - Navigate to URL passed during execution. ( Web Application under test URL can be setup from Setting page)
	- GoBack - Go back to the previous page 
	- SwitchToNewWindow - Switch to New window 
	- SwitchToMainWindow - Switch to default window or main window
	- AcceptAlert - Accept the Alert
	- ScrollUp - Page Scroll up. Default height 100px  
	- ScrollDown - Page Scroll down. Default height 100px 
	- SwitchToIframeByIndex - switch to iframe by passed index
	- SwitchToIframeByNameOrId - switch to iframe by passed name or id
	- SwitchToIframeDefaultContent - switch back to default content
	- SwitchToIframeByWebElementXpath - Switch to the Iframe by passing xpath webElement
	- Hover - Hover on given WebElement	


### Android Supported Actions:


	- Click - Click on WebElement
	- SendKey - SendKey into textbox
	- Clear - Clear the text field
	- DisplayGetText - Read Android Element text value
	- VerifyText - Compare Android Element actual value with Expected Value
	- VerifyIsDisplayed - Check Android Element is displayed or not
	- VerifyIsEnabled - Check Android Element is Enabled or not
	- VerifyIsClickable - Check Android Element is Clickable or not
	- DisplayGetAttributeValue - Read Passed attribute Android Element Value
	- WaitUntilVisible - Wait until Android Element is visible 
	- WaitUntilClickable - Wait until Android Element is clickable
	- WaitUntilInvisible - Wait until Android Element is Invisible
	- Wait - Wait for given given time duration in seconds. Enter value in Miliseconds 
	- SwitchToView - Switch to passed view 
	- SwipeUp - Bring Android element from Up to bottom. Default is 1 swipe. Enter number > 1 for more swipe
	- SwipeDown - Bring Android element from bottom to up. Default is 1 swipe. Enter number > 1 for more swipe
	- SwipeToLeft - Bring Android element from Left to Right. Default is 1 swipe. Enter number > 1 for more swipe
	- SwipeToRight - Bring Android element from Right to Left. Default is 1 swipe. Enter number > 1 for more swipe
	- LongPress - Long press on Android Element


## Setup:
	- Execute given db script into mySQl Server
	- Download war file
	- Place the war file into Tomcat webApps folder and start tomcat server
	- Change your mysql server details at this location :: tomcat server folder >> webApps >> AutoScriptBot >> WEB-INF >> Classes >> database.properties    
	- Restart Tomcat 

## Versions info
		
	Selenium: 
		<dependency>
			<groupId>org.seleniumhq.selenium</groupId>
			<artifactId>selenium-java</artifactId>
			<version>3.14.0</version>
		</dependency>
	Appium:
		<dependency>
			<groupId>io.appium</groupId>
			<artifactId>java-client</artifactId>
			<version>6.1.0</version>
		</dependency>

## Not Supported NOW
 
	- Parallel browser execution
	- Other browsers except Chrome and Firefox - Will be supported later
	- ChromeOptions and Firefox options
	- iOS app Automation
	- No Screenshot 
	- No log tracking integrated in the AutoScriptBot
	 

## Access the URL : 

__http://localhost:portNo/AutoScriptBot/Login.xhtml__

Or 

__http://hosted_IPAddress:portNo/AutoScriptBot/Login.xhtml__ 



__Note:__ 

	- ADB Server daemon is  running for android app
	- Phone should have permission to install AUT app from USB unknown source 
	- Chrome/Firefox browser should support Selenium lib
	- Appium installation should be proper 


DEMO Video : __https://youtu.be/OdgvuuFsVzo__  



