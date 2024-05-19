# Read Me First
Hello, world! This is a simple Spring Boot web API that converts values between 

# Steps to run the application:

1. Make sure you have Java installed. On Windows, Mac, or Linux, type this into the command line:
        java -version
2. If you don't have Java installed:
    - Windows does not provide a built-in command-line utility to download Java directly. However, you can download Java manually from the official Oracle website (https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) and install it using the installer.
    - On Mac, you can install Java using Homebrew by running the following command:
        brew install openjdk
    - On Linux, you can install Java using the package manager. For example, on Ubuntu, you can run the following command:
        sudo apt-get install openjdk-11-jdk
3. Make sure you have Maven installed. On Windows, Mac, or Linux, type this into the command line:
        mvn -version
4. If you don't have Maven installed:
    - Windows does not provide a built-in command-line utility to download Maven directly. However, you can download Maven manually from the official Apache Maven website (https://maven.apache.org/download.cgi) and install it using the installer.
    - On Mac, you can install Maven using Homebrew by running the following command:
        brew install maven
    - On Linux, you can install Maven using the package manager. For example, on Ubuntu, you can run the following command:
        sudo apt-get install maven
5. Next, change directory to the project root directory
6. To build the project, type:
        mvn clean install
7. To run the project, type:
        mvn spring-boot:run
8. To test the project, open a web browser and navigate to:
    http://localhost:8800/api/convert/weight?value=100&fromUnit=pounds&toUnit=kilograms











# Reference Documentation (mostly auto-generated by Spring Initializr)

* This project uses the package name 'com.example.conversion'

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.2.5/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.2.5/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#web)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)

