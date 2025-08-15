# Hello Java Maven - Task 8

## Objective
Learn how to use Jenkins to build a simple Java application using Maven — the first step into CI/CD.

## Tools Required
- Jenkins (Docker or local installation)
- Java JDK 8 or 11
- Maven
- Git (optional)

## Project Structure

hello-java-maven-task8/
├── pom.xml
└── src
└── main
└── java
└── HelloWorld.java


### File Descriptions
- **HelloWorld.java**: Simple Java program that prints:
Hello, Jenkins + Maven

- **pom.xml**: Maven configuration for compiling and packaging the Java application.

## Steps Completed
1. Created a basic Java HelloWorld application.
2. Added `pom.xml` for Maven build configuration.
3. Built the project locally using Maven:
```bash`
mvn clean package

Set up Jenkins (via Docker or local installation):

Added Maven in Global Tool Configuration.

Created a Freestyle project.

Selected Invoke top-level Maven targets in the Build section.

Set Goal: clean package.

Verified successful build in Jenkins console output.

How to Run Locally

Navigate to the project folder:

cd hello-java-maven-task8


Build using Maven:

mvn clean package


Run the program:

java -cp target/hello-java-maven-task8-1.0-SNAPSHOT.jar HelloWorld


Expected output:

Hello, Jenkins + Maven

##AUTHOR##
#-#GOUTHAM BABU#-#
