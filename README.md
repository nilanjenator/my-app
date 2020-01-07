# my-app
This is a sample java code for creating ci ct pipelines.

There is an App.java file which takes any string as input and reverses that string. maven is used for compiling, testing the code. 

# Steps to Build: 
mvn compile

# Steps to run unit tests: 
mvn test

# Steps to execute the Java Code:
cd my-app/target/classes
java com.mycompany.app.App
  Enter string to reverse:
  abcd
  Reversed string is:
  dcba

# The Requirement:
# Req 1: 
Create a pipeline as a code which will do the following tasks:
 Checkout Repo -> Compile Code -> Run Unit Tests -> Publish reports in CI Orchestrator (like Jenkins/Gitlab CI etc) -> If all tests are passed then Archive the code.

# Req 2:
Create a pipeline as a code which will do the following tasks:
 Checkout Repo -> Compile Code -> Run Unit Tests -> Run Code coverage Tests -> Publish reports in CI Orchestrator (like Jenkins/Gitlab CI etc) -> If all tests are passed and Code Coverage is more than 90% then Archive the code.

 There is a sample placeholder file AppTest.java for unit tests, however you can ignore it and create new ones of your own if required. 
