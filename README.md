# Plivo API Test Suite

Test Automation framework for Plivo REST APIs. 


### Tools and Frameworks used

This suite uses the following tools and framework:
1. REST Assured
2. Maven
3. TestNG
4. Log4j
5. ExtentReport-3

### Setting up the Framework

This project has been developed on EclipseIDE. Clone the repository to checkout the code to your local machine.
The pre-requisites for setting up of the framework are:
1. JDK installed on the local machine. (version: 1.8.0_171)
2. Maven(version: 3.6.0). Steps for setting up Maven on local can be found here: https://maven.apache.org/install.html

After checking out the code, import it as existing maven project to any IDE.

## Running the tests

After the project has been imported successfully, the test cases can be run in the following ways:
1. From terminal: cd <project directory> and then execute command "mvn clean test".
2. From IDE: Right-click on the project and select Run As -> Maven Build.. -> Enter Goals as "clean test".

## Test Reports
After the execution of the TestSuite, ExtentReport is generated under the TestReport folder.
A sample test report generated can be found here:  /plivoAPITest/TestReport/PlivoAPITestReport.html
