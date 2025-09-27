# Project_Progress_Tracker_For_College

## Overview

Project Progress Tracker is a web application that allows students to regularly update their project progress by submitting detailed updates and screenshots. Teachers can securely view these updates and provide constructive feedback. The application fosters effective communication and transparency between students and faculty during the project lifecycle.

## Features

- Student login and secure submission of progress updates with screenshots.  
- Teacher role to view student submissions and provide feedback.  
- Role-based access control to ensure secure and appropriate data visibility.  
- User-friendly JSP-based interface for both students and teachers.  
- Uses MySQL database to store user data, progress entries, and feedback.

## Technologies Used

- **Backend:** Spring MVC  
- **Frontend:** JSP  
- **Database:** MySQL  
- **Build Tool:** Apache Maven 
- **Server:** Apache Tomcat (or similar servlet container)

## Prerequisites

- Java JDK 8 or above  
- Apache Tomcat 8+  
- MySQL Database Server  
- Maven (if using for build and dependency management)

## Installation & Setup

1. **Clone the repository**  
   ```bash
   https://github.com/akashmaskejava2024/Project_Progress_Tracker_For_College.git
   cd Project_Progress_Tracker_For_College
   ```

2. **Configure Database**  
   - Create a MySQL database and update database connection details in `src/main/webapp/WEB-INF/spring-servlet.xml` (or your config location).

3. **Build and Deploy**  
   - Build the project using Maven:  
     ```bash
     mvn clean package
     ```
   - Deploy the generated WAR file to your Apache Tomcat server.

4. **Access the Web App**  
   - Open a browser and navigate to:  
     `http://localhost:8080/project-progress-tracker`  

## Usage

- Students can register/login and upload progress updates with screenshots.  
- Teachers log in to view updates and provide feedback.  
- Both roles have intuitive navigation designed via JSP pages.

## Project Structure

```
/src/main/java       - Java source codes (controllers, services, DAOs)  
/src/main/webapp/WEB-INF/jsp   - JSP frontend pages and web resources  
/src/main/webapp/WEB-INF  - Configuration files (database, properties)  
```


