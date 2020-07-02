# Project features #

-- Development tools
- SpringBoot with JDK 8
- VS Code and Eclipse framework
- Node JS with NPM

-- Source code:
- Clone repository from https://github.com/ralbareda/build_app_spring_and_react.git

# Dev build #

-- Build project:
> Download source from repository to your favourite workspace:
  Build project should be completed automatically

-- Start Spring Boot in localhost;8080
> Run class ReactAndSpringDataRestApplication
> Verify REST return JSON file at: http://localhost:8080/api/contacts 

-- Build React project
> Move to /client folder and run: npm install
  
-- Start React Server in localhost:3000
> Execute command from /client folder: npm start

# Production build #

-- Build project:
> Execute: mvn clean install
  .jar file should be generated in your /target path
  
> Run .jar generated from /target path:
  Example: C:\dev\crm\target>java -jar crm-0.0.1-SNAPSHOT.jar
  
