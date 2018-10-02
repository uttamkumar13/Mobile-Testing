Pre-requisites:
******************
apk file taken for automation: android-sample-app.apk
Tool used for automation: 
- JDK
- Eclipse
- Selenium with Java
- Appium SDK Studio
- Appium Server
- Selenium Jar files
- Java Client

Mobile Device used for testing:
*********************************
Device Name: Motorola E3 POWER
OS type: Android
Version: 6.0.0, API 23


Stack Requirements:
**********************
1) Download and install JDK and set the environment variables
2) Download and install any version of eclipse
3) Download and install Android SDK Manager. Set the environment variables for Android SDK
Note: While installing make sure to install the Android version that is under test (e.g-Android 6.0, API 23 and select only starting 3 options and rest all options should be unchecked)
4) Download and install "appium-desktop-setup-1.7.0"
5) Download the required Selenium jar files 
6) Download the Java client (java-client.exe) and import in Eclipse
7) Make sure to enable the Developer options mode in the mobile device

Steps to Execute:
*********************
1) Download the project from github and import it in Eclipse
2) Make sure that the "android-sample-app.apk" file is available and installed in the mobile device
3) Connect the android mobile device with the laptop. Open the command promt and type> adb devices. Result should display the connected mobile device
4) Start the Appium Server
5) Run the downloaded Selenium script from Eclipse


Notes:
********
1) I have written the script while testing the  android-sample-app.apk in mobile directly. We can test the same app in Simulator as well. For that, we need to have a simulator and we just need to change the device name as Simulator name (instead of mobile name) in the desired capability.
2) If the connected mobile device is not detecting in computer, install the pdanet software which will help to detect the connected device
3) I have not used any framework to automate this scenario as this is very small script. If you want, I can put the same script in a Framework (having Maven and TestNG) and can send you the updated script in an hour.
4) The Scenario that is tested in this script is written in the form of test case in the excel sheet (Automation_Testcase.xlsx) which is also uploaded in the github.
