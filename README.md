My Selenium Grid learning on mac :


https://www.codementor.io/@olawalealadeusi896/setting-up-selenium-grid-to-run-your-tests-in-parallel-on-multiple-browsers-kl6vqi83a


Clone this repo and open in intelliJ idea

Download jar from https://selenium.dev/downloads/ and go to respective directory on the pc and run below 2 commands on 2 terminal windows to start the hub and node

java -jar selenium-server-standalone-3.141.59.jar -role hub

java -jar selenium-server-standalone-3.141.59.jar -role node -hub https://localhost:4444/grid/register

Then run below 2 commands by placing the respective binaries in the respective paths

java -Dwebdriver.chrome.driver="/Users/Downloads/chromedriver"

java -Dwebdriver.gecko.driver="/Users/Downloads/geckodriver"

Note : Every command above has to be ran separately and leave the terminal window open after command  execution


To Run : Right click on google.xml and run


See report :

TestNG Report Generation in Selenium WebDriver
1. The TestNG will generate the default report.
2. When you execute testng.xml file, and refresh the project. You will get test-output folder in that folder.
3. Right click on the emailable-report.html and select the option. Open with the web browser.





￼
Check on Use default reporters option which will create test-output folder in your root folder with all reports.


https://www.techbeamers.com/selenium-grid-webdriver-code-example-java/






https://github.com/Gridlastic/java-code-example

