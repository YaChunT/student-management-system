# Student Management System

Built with modern technologies, this system offers a comprehensive set of features for efficiently managing student data and facilitating administrative tasks.

<div align="center">
  <img width="1024" alt="Screenshot 2024-04-11 at 6 22 23 PM" src="https://github.com/YaChunT/student_management_system/assets/162515094/4a277f09-5605-4b53-aa4f-3f3c01e4e6d3">
</div>



## Table of Contents
- [About](#about)
- [Architecture Diagram](#architecture-diagram-%EF%B8%8F)
- [User Interface](#user-interface-)
- [Getting Started](#getting-started%EF%B8%8F)



<br> <!-- Line break -->
<br> <!-- Line break -->
## About📌  
This Student Management System is designed to streamline the process of managing student data and administrative tasks. Here are the key details:

<br> <!-- Line break -->
<br> <!-- Line break -->
## Architecture Diagram 🏗️

<div align="center">
  <img width="1024" alt="Screenshot 2024-03-27 at 11 55 14 PM" src="https://github.com/YaChunT/student_management_system/assets/162515094/d8a7dd63-da8c-4d71-9693-0112be5e0511">
</div>

<br> <!-- Line break -->

This web application architecture is designed around user management and security, encompassing several key components:
<br> <!-- Line break -->

- **User Registration**: New users can create accounts within the system through this process.
- **Roles**: Upon registration, users are assigned roles such as 'admin' or 'user', dictating their access levels within the application.
- **Spring Security**: Leveraging a robust authentication and access-control framework for Java applications, Spring Security effectively manages the security aspects of the application.
- **Session Timeout**: Sessions expire after 15 minutes, requiring users to re-authenticate for continued access.
- **Java Mail Sender**: Integrated to facilitate email communications from the application, including functionalities such as email verification during registration.
- <br> <!-- Line break -->

This architecture follows a standard pattern for user management and security in web applications, ensuring that only authenticated and authorized users can access designated features or sections.

<br> <!-- Line break -->
<br> <!-- Line break -->
## User Interface 📊 
- **Sign-in page for web application**
<div align="center">
<img width="1506" alt="Screenshot 2024-03-28 at 12 17 49 AM" src="https://github.com/YaChunT/student_management_system/assets/162515094/8edefba6-8586-4f4a-9039-5e42b29a35ee">
</div>

<br> <!-- Line break -->
<br> <!-- Line break -->
## Getting Started🏃‍♂️

Follow these steps to get the project up and running on your local machine.

### - Prerequisites

- Docker installed on your system

### - Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/YaChunT/student_management_system.git
    ```

2. Navigate into the project directory:

    ```bash
    cd student_management_system
    ```

3. Build the Docker image:

    ```bash
    docker build -t student_management_system .
    ```

4. Run the Docker container:

    ```bash
    docker run -p 8080:8080 student_management_system
    ```

5. Access the application:

    Open http://localhost:8080 in your web browser.
