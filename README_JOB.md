# Job_applicationform
The Job Application Management System allows applicants to submit their applications via a user-friendly form built with HTML, CSS, and JavaScript.
The backend is developed using Spring Boot, which handles form submissions and stores the data in MongoDB. Duplicate entries are prevented by checking phone numbers before submitting. 
The API is tested using Postman to ensure proper functionality. This solution streamlines the application process, provides seamless data handling, and improves efficiency for both applicants and HR teams.
jobform1 [boot]
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.example.demo
│   │   │       ├── controller
│   │   │       │   └── JobApplicationController.java
│   │   │       ├── model
│   │   │       │   └── JobApplication.java
│   │   │       ├── repository
│   │   │       │   └── JobApplicationRepository.java
│   │   │       └── service
│   │   │           └── JobApplicationService.java
│   │   ├── resources
│   │       ├── static
│   │       ├── templates
│   │       └── application.properties
│   ├── test
│       └── java
│           └── com.example.demo
├── JRE System Library [JavaSE-17]
├── Maven Dependencies
├── target
│   ├── generated-sources
│   │   └── annotations
│   ├── generated-test-sources
│       └── test-annotations
├── HELP.md
