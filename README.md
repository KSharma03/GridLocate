# GridLocate
Grid Locate Automation

Currently, it is designed for only Chrome and Firefox browsers. For Safari, changes are to be made.

Pre-requisite:
1. Download chromedriver.exe
2. Place it in some folder, the path of which you have to give in GridLocateMainClass class in System.setProperty("webdriver.chrome.driver", "C:\\Users\\kapil.2.sharma\\Desktop\\My Idhar Udhar Ka Work\\Selenium Scratch\\chromedriver.exe");
3. For firefox, set the system property by giving the path of your firefox.exe file in in GridLocateMainClass class in System.setProperty("webdriver.firefox.bin", "C:\\Users\\kapil.2.sharma\\AppData\\Local\\Mozilla Firefox\\firefox.exe");
4. You need to add all selenium jars to your project which are in folder "selenium-2.48.2" as well as "selenium-2.48.2\libs" folders
5. Right now only single device is getting added though I have mentioned the loop, but if you want to add multiple devices in one go, all the device IDs and their Device Pins have to be fetched from user, the code for which needs to be implemented in Swing.
6. You need to provide your G+ email ID and password in GridLocateMainClass class in gridLocateSignInWithGoogle() method in order to login into GridLocate.

Automation Scenario:
Scenaro I: Add new device to Gridlocate.com: As you will execute, Swing Frame will come in front of you, where you have to make your browser choice. This will sign you up with your provided email ID and password. Another Swing Frame will appear which will ask you for Adding Device or Viewing Device History. Depending on your choice, the outcome will come. 
