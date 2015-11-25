# GridLocate
Grid Locate Automation

Currently, it is designed for only Chrome and Firefox browsers on Windows and Chrome and Safari browsers on MAC.

Pre-requisite:
1. Download chromedriver.exe. For Windows visit:- ( http://www.seleniumhq.org/download/). For MAC visit:- http://chromedriver.storage.googleapis.com/index.html?path=2.20/
2. Place it in some folder, the path of which you have to give in GridLocateMainClass class in command "System.setProperty("webdriver.chrome.driver", "C:\\Users\\kapil.2.sharma\\Desktop\\My Idhar Udhar Ka Work\\Selenium Scratch\\chromedriver.exe");" for Windows and for MAC as "System.setProperty("webdriver.chrome.driver", "/Users/caaminf/Desktop/Automation/Selenium/chromedriver");"
3. For firefox, set the system property by giving the path of your firefox.exe file in in GridLocateMainClass class in System.setProperty("webdriver.firefox.bin", "C:\\Users\\kapil.2.sharma\\AppData\\Local\\Mozilla Firefox\\firefox.exe"); This is configured for Windows only currently.
4. For Safari on MAC Download latest Selenium Safari extension from http://selenium-release.storage.googleapis.com/index.html. Download "SafariDriver.safariextz" file. Double-click on the “SafariDriver.safariextz” file and click on Install. Click on “Safari” > “Preferences” > “Extensions” > You will find Selenium extension -> Select “Enable Webdriver”
5. You need to add all selenium jars to your project which are in folder "selenium-2.48.2" as well as "selenium-2.48.2\libs" folders. You can download selenium jars from : http://www.seleniumhq.org/download/
6. Right now only single device is getting added though I have written the while loop, but if you want to add multiple devices in one go, all the device IDs and their Device Pins have to be fetched from user, the code for which needs to be implemented in Swing.
7. You need to provide your G+ email ID and password in GridLocateMainClass class in gridLocateSignInWithGoogle() method in order to login into GridLocate.

Automation Scenario: Add new device to Gridlocate.com: As you will execute, Swing Frame will come in front of you, where you have to make your browser choice. This will sign you up with your provided email ID and password. Another Swing Frame will appear which will ask you for Adding Device or Viewing Device History. Depending on your choice, the outcome will come. 
