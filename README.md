```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Management App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
        h1, h3 {
            color: #333;
        }
        ul, ol {
            margin-left: 20px;
        }
    </style>
</head>
<body>

    <h1><b>Student Management Application</b></h1>

    <p>
        <h3><b>&#8226; Project Description:</b></h3>
        This project is a simple and beginner-friendly Student Management Application, developed using Spring Boot for the backend, React (with Vite) for the frontend, and an H2 in-memory database. 
        While the project is functional, it is designed as an introductory exercise and might contain some minor bugs. It offers hands-on experience in working with modern web development frameworks, albeit with some limitations.
    </p>
    
    <p>
        <h3><b>&#8226; Pre-requisites:</b></h3>
        Before running this project, ensure that your system meets the following requirements:
        <ol>
            <li>Java, Maven, and Node.js should be installed on your system.</li>
            <li>Integrated Development Environments (IDEs) must be configured. 
                <ul>
                    <li>For the backend, IntelliJ IDEA is recommended. However, any IDE supporting Spring Boot can be used.</li>
                    <li>For the frontend, Visual Studio Code (VS Code) is preferred, although it can also be used for the backend.</li>
                </ul>
            </li>
            <li>Install an unzipping tool like WinRAR or 7-Zip to extract the project files.</li>
        </ol>
    </p>
    
    <p>
        <h3><b>&#8226; Steps to Execute the Project:</b></h3>
        Follow these instructions to set up and run the project:
        <ol>
            <li>Ensure that all pre-requisites are met.</li>
            <li>Download the project ZIP file or clone the repository from the source control.</li>
            <li>Extract the ZIP file using a tool like WinRAR or 7-Zip.</li>
            <li>Open the extracted project files:
                <ul>
                    <li><b>Frontend (React with Vite):</b>
                        <ol>
                            <li>Open the frontend folder in your IDE (preferably VS Code).</li>
                            <li>Run the command <b>npm i</b> in the terminal to install all necessary project dependencies.</li>
                            <li>Once the installation is complete, run <b>npm run dev</b> to start the frontend development server.</li>
                            <li>The frontend application should now open automatically in your default web browser. If not, navigate to the URL displayed in the terminal output.</li>
                        </ol>
                    </li>
                    <li><b>Backend (Spring Boot with H2 Database):</b>
                        <ol>
                            <li>Open the backend folder in IntelliJ IDEA or any other suitable IDE.</li>
                            <li>Ensure that all required dependencies in the <b>pom.xml</b> file match your system configuration. Modify versions if necessary and apply Maven changes.</li>
                            <li>Navigate to the directory: <b>StudentManagementBackend/src/main/java/com/StudentManagement</b>.</li>
                            <li>Open the file <b>StudentManagementBackendAppApplication.java</b>.</li>
                            <li>Click the <b>Run</b> button (typically represented by a green triangle) to start the backend server.</li>
                            <li>If any errors occur during this process, debug and resolve them based on the error messages provided.</li>
                        </ol>
                    </li>
                </ul>
            </li>
            <li>Once both the frontend and backend are running, refresh the browser page to load the frontend and start using the Student Management Application.</li>
        </ol>
    </p>

    <p>
        <h3><b>&#8226; Known Issues:</b></h3>
        There is currently a bug in the "Edit Student Details" functionality. The issue pertains to updating the student information in the database, which may not work as expected. Debugging and resolution will be required for full functionality.
    </p>

</body>
</html>
```
