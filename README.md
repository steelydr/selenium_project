**What is Selenium?**

Selenium is a portable framework and a popular tool for web app testing. It is compatible with multiple programming languages such as Python, C#, and Java. You can use those languages to perform various tasks with Selenium, such as creating a test script. Still, most users prefer to use Java with this framework because it’s more user-friendly than the rest. 

Selenium is not a single software application. It is a suite of various tools that you can use to perform different sorts of testing.


Selenium has the following tools in its suite:

1.Selenium IDE (Integrated Development Environment)

2.Selenium WebDriver

3.Selenium Client API

4.Selenium Remote Control (Deprecated)

5.Selenium Grid


To get started with the Selenium project you must have Java Eclipse, Chromedriver/Firefox driver use whatever browser you are comfortable with.I prefer Chromedriver.

Useful link to install Chromedriver on your Windows 10/Linux/Mac https://www.youtube.com/watch?v=dz59GsdvUF8

Link to get started with Selenium  https://www.youtube.com/watch?v=BcjlvX39W7o

Copy and paste your selenium dependency into your POM.xml file from the maven repository website (https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java) here you can get the latest versions of your selenium 

The latest version of selenium v 4.11.0 while doing my project work


**What is Selenium IDE?**

Selenium IDE (Integrated Development Environment) is primarily a record/run tool that a test case developer uses to develop Selenium Test cases. Selenium IDE is an easy-to-use tool from the Selenium Test Suite and can even be used by someone new to developing automated test cases for their web applications. One does not require any special setup to get started with Selenium IDE. You just need to add the extension of your specific browser. Selenium IDE provides you with a GUI (Graphical User Interface) for easily recording your interactions with the website.


Selenium IDE allows a user or a test case developer to create the test cases and test suites and edit it later as per their requirements. The development environment also provides the capability of converting test cases to different programming languages, which makes it easier for the user and does not mandate the need for knowing a specific programming language.
 
* Add an selenium IDE extension to your chrome
  
 ![Screenshot (843)](https://github.com/steelydr/selenium_project/assets/65842272/fa6c5d5c-ffa7-466d-87aa-f203c017d5af)



After entering the base URL for the project, the recording begins, and all the interactions with the website are recorded and categorized into three main categories as shown in the above Screenshot:

* Command
* Target
* Value

Features of Selenium IDE
There are several features provided in the IDE under the toolbar, using which one can control the execution of test cases:

* Speed Control – Helps control the speed of test cases
* Run All – Allows execution of the entire Test Suite
* Run – Runs the currently selected test
* Pause/Resume – Allows a user to pause and resume a particular test case
* Step – Helps step into each specific command in the test script
* Rollup – Helps group all the Selenese Commands together and make them execute as a single operation

Limitations of Selenium IDE
* Not suitable for testing extensive data
* Connections with the database can not be tested
* Cannot handle the dynamic part of web-based applications
* Does not support capturing of screenshots on test failures
* No feature available for generating result reports
