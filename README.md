# MyProjects
This project automates the website :""https://www.xe.com/currencyconverter/"
The website is a Currency Converter.
In order to execute the project, the steps to be followed are:
	*Extract the project
	*Download the chromedriver.exe and use the location in System.setProperty present in testSetup method.
	*Right click to the project name(testngMaven) in Project Explorer.
	*Click Run As
	*Click Run Configurations
	*Under TestNG on the left hand side of the pop-up window, select testngMaven_testng.xml
	*Make sure Suite is selected with value as the path to testng.xml(Example:C:\Users\ASUS\eclipse-workspace\testngMaven\testng.xml)
	*Click Run
	*Once all the tests have run, output will be shown in the Console window below the IDE.
	*View the report
		*Go to test-output folder under the project in Project Explorer
		*Under junitreports
		*click TEST-testngMaven.TestNGCurrencyConverter.xml
	
The testng.xml file has 5 cases.
