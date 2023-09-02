## Learning Example To-Do App Documentation

## 1. Introduction.
　This is an example of a To-Do web application created in Java for use in training newcomers,  
This repository contains documentation and source code for the To-Do Web application in Java.
　
## 2. Features
　The ToDo application to be created should have the following features and requirements.
- Basic functionality: Adding ToDo items
    - Adding To-Do items
    - Deleting To-Do items
    - Edit To-Do items
    - Toggle Completed/Uncompleted for To-Do items
- User Related: User Registration
    - User registration function
    - Login/Logout function
    - Password reset function
- Database connection
    - Persistent storage of ToDo items (e.g. MySQL, PostgreSQL, etc.)
    - Data access using Spring Data JPA
- Filtering and sorting
    - Show only completed/uncompleted items
    - Sorting by Due Date, Created Date, Updated Date, etc.
- UI/UX: Responsive design
    - Responsive design
    - Error message display
    - Pop-up to confirm action
- Security: Spring Security
    - Deployment of Spring Security
    - CSRF Countermeasures
    - SQL Injection Countermeasures
    - Password hashing
- REST API: REST API for CRUD operations on ToDo items
    - API endpoint for CRUD operations on ToDo items
    - Response in JSON format
- Error handling: catch exceptions and display appropriate error messages
    - Catch exceptions and display appropriate error messages
- Extensibility
    - Add tags and categories to ToDo items
    - User profile customization
- Testing: Unit testing (using JUnit)
    - Unit testing (using JUnit)
    - Integration testing
- Deployment and Execution
    - Execution and deployment of the application on the Jetty server
- Settings and Configuration:
    - Use external configuration files to manage database connection information and other settings

## 3. Environment
　This web application is ,
- Java 17(LTS)
- MariaDB 10.11.5
- SpringFramework
- Gradle
- Container (Docker or Podman *Docker compatible Podman is used)
- Vue.js
- Jetty Web Server  
  Create and run the above configuration.

## 4. Contents
　This document is managed in the following folder structure.

RootFolder  
├─ Apps ... Source folder in Java format  
├─ Container ... Working folder for container  
├─ Specification ... Specification document  
├─ DesignDocuments ... Design documents  
├─ DevEnvGuide ... Environment building guide  
└─ Q&A_Guide ... Q&A when you have a problem

## 5. Disclaimer
　The authors and authors of this content are not responsible for any  
damage caused by the content of this repository.

## 6. Copyright
　All files related to this repository are copyrighted by their creators.  
Redistribution, modification, etc. is permitted within the scope of the MTT Licence.

## 7. Thanks
　To the developers of all technologies and pioneers who have published   
information on their blogs and other sources.
