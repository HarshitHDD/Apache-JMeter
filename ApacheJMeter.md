# Apache-JMeter
Notes on Apache JMeter.

# **Introduction**: -
JMeter is used to perform performance testing, functional testing, and load testing of web applications.
The Apache JMeter™ application is open-source software, a 100% pure Java application designed to load test functional behaviour and measure performance. It was originally designed for testing Web Applications but has since expanded to other test functions.
Apache JMeter may be used to test performance both on static and dynamic resources, Web dynamic applications.
It can be used to simulate a heavy load on a server, group of servers, network or object to test its strength or to analyse overall performance under different load types.
# Apache JMeter features include: -
-	Ability to load and performance test many different applications/server/protocol types:
-	Web - HTTP, HTTPS (Java, NodeJS, PHP, ASP.NET, …)
-	SOAP / REST Webservices
-	FTP
-	Database via JDBC
-	LDAP
-	Message-oriented middleware (MOM) via JMS
-	Mail - SMTP(S), POP3(S) and IMAP(S)
-	Native commands or shell scripts
-	TCP
-	Java Objects  
-	Full featured Test IDE that allows fast Test Plan recording (from Browsers or native applications), building and debugging.
-	A complete and ready to present dynamic HTML report.
-	Easy Continuous Integration through 3rd party Open-Source libraries for Maven, Gradle and Jenkins.

# Download And Requirements: -
To download JMeter Visit: https://jmeter.apache.org/, under download section download the latest stable release you want or any you want.
To make JMeter works, it requires JAVA (8+ version), so you need to have Java installed in your system, Because JMeter uses only standard Java APIs.
Although you can use a JRE (Java Runtime Environment), it is better to install a JDK as for recording of HTTPS, JMeter needs utility from JDK.

## GUI(Graphical User Interface) Mode: -
To start JMeter GUI open the “jmeter.bat” file present in bin folder of JMeter.
Where All GUI based performance testing is performed also to make test cases(.jmx), reports and many more.
In GUI mode load testing is not recommended because it can consume a lot of CPU and memory unlike CLI mode.
The GUI console is excellent for running a small load and developing and/or debugging your script.

![JMeter's GUI Window!](https://static.wixstatic.com/media/955d13_0e66ee2f34c242cfa25f1e3607705a9c~mv2.png "JMeter")

## CLI (Command Line Interface) Mode: -
CLI mode is best to run heavy load testing
To use CLI mode, open your terminal, navigate to “jmeter.bat” file folder.
Following command are used to work in CLI mode: -
### ~ jmeter -n -t {path to test case} -l {path to log file} -e -o {path to folder for report}
- “n” = to run in cli mode, 
- “t” = test file, 
- ‘l’ = log file of test result.
- ‘e’ = to generate report dashboard after test
- ‘o’= output folder (exist or empty) to save HTML report.
