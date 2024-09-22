# AWScodeBuild
AWS Code Build test project

This AWS CodeBuild process sets up a Java 17 (Amazon Corretto) environment and installs Maven 3.9.8 to build the project. It modifies the database connection details in the application.properties file and compiles the project using Maven. After packaging the output, the build artifacts are stored in the target/vprofile-v2 directory for deployment.
