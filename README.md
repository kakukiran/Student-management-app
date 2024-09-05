# Student Management Application

## Project Description
This project is a simple and beginner-friendly **Student Management Application**, developed using **Spring Boot** for the backend, **React (with Vite)** for the frontend, and an **H2 in-memory database**.  
It is designed as an introductory project and might contain some minor bugs. It offers hands-on experience in working with modern web development frameworks, though it has certain limitations.

## Pre-requisites
Before running this project, ensure that your system meets the following requirements:
1. **Java**, **Maven**, and **Node.js** should be installed on your system.
2. IDEs should be properly configured:
    - For the backend, **IntelliJ IDEA** is recommended (any IDE supporting Spring Boot can be used).
    - For the frontend, **Visual Studio Code (VS Code)** is preferred, but can also be used for both the frontend and backend.
3. An unzipping tool such as **WinRAR** or **7-Zip** should be installed.

## How to Execute the Project

To set up and run the project, follow these steps:

1. Ensure that all pre-requisites are met.
2. Download the project ZIP file or clone the repository from source control.
3. Extract the ZIP file using **WinRAR** or **7-Zip**.
4. Open the project files as described below:

### Frontend (React with Vite)
1. Open the **frontend** folder in your IDE (preferably **VS Code**).
2. Run the following command to install the necessary project dependencies:
   ```bash
   npm i
3. Strat the development server using:
   ```bash
   npm run dev
 4.The frontend should now open automatically in your default web browser. If not, navigate to the URL displayed in the 
 terminal.

## Backend (Spring Boot with H2 Database)
1.Open the backend folder in IntelliJ IDEA (or any other suitable IDE).

2.Ensure all required dependencies in the pom.xml file match your system configuration. Modify the versions if necessary and apply Maven changes.

3. Navigate to the following directory:
   ```bash
   StudentManagementBackend/src/main/java/com/StudentManagement

 4.Open the file StudentManagementBackendAppApplication.java.

 5.Run the Spring Boot application by clicking the Run button (typically a green triangle).

 6.If any errors occur, debug and resolve them based on the error messages provided.

 7.Once both the frontend and backend are running, refresh the frontend page in your browser to start using the Student 
 Management Application.

## Known Issues
-There is a bug in the "Edit Student Details" functionality. The issue is related to updating student information in the database, which may not work as expected. Debugging will be required to resolve this issue.
