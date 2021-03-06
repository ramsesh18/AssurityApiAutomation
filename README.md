# RamaseshanThirumalai

## Welcome to Assurity Api Automation

The API project has been developed using JAVA RestAssured combined with Maven and TestNG framework.

To Import this project to an IDE say Eclipse

1. Goto File --> Import and choose GIT --> Projects from GIT
2. Choose Clone URI
3. In the URI, enter <https://github.com/ramsesh18/AssurityApiAutomation> and click Master branch (if asked for)
4. Follow the dialog box by clicking next and then choosing the desired workspace and the project will be imported to your workspace

To run this project and correct the errors, please make sure you have the following 

1. Java JDK 1.8 :-) - (Small tip if you dont have java installed: when you add JAVA_HOME as environmental variable, make sure you DON'T
include "/bin" in JAVA_HOME, however you can add %JAVA_HOME%/bin in the classpath).
2. Eclipse Java EE IDE for Web Developers or Netbeans or any IDE installed in your computer.
3. Maven (3.3.x) installed and an entry has been added in the environment variable. To verify please open command prompt (As administrator)
and run this mvn --version. If you see the version, then it has been installed properly. 
4. The pom.xml has all the required jars and those jars will be pulled from maven central repository (ofcourse you need an Internet connection :-))
5. To execute the project say in Eclispe using TestNG, you need to install the TestNg plug-in. Please go to eclipse-marketplace or IDE market place to 
   to search for TESTNG plugin or Please refer: https://www.ecanarys.com/Blogs/ArticleID/169/How-to-Install-TestNG-framework-Step-by-Step-installation-process
6. The testng.xml contains listener class and test class.
7. The rest assured libraries can be accessed from maven central repository and you could verify the same in pom.xml
 
 To Summarize - you should now have TestNG downloaded from Marketplace, maven 3.x, Java 1.8, JDK1.8 in JAVA_HOME.

There are 2 ways to run this project
1. Maven commands using command line
	1. "mvn install" will install all the libraries
	2. "mvn test" will run the test
2. Right-click on "AssurityApiTest" in Eclipse IDE (or any IDE you use) and Run-as "TestNG Test"

There are 2 ways to view the report
1. SUREFIRE REPORTS (maven execution)
		Go to your project in your local computer and navigate to the following to view HTML surefire reports. This report is viewable only if the 
		tests are executed using MAVEN command in command line.
		
		<\ApiAutomation\target\surefire-reports\html\index.html>
		
2. TESTNG REPORTS (RUN-AS TestNg Test execution) 
		Go to your project in your local computer and navigate to the following to view testng report. This report is viewable only if the 
		tests are executed in say Eclipse by right-click on the Test class and choosing run as "TestNg Test"
		
		<\ApiAutomation\test-outputemailable-report.html>

 
