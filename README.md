# Registration_Form_-_Fullstack

<h3>Overview</h3>
Welcome to "Registration Form - Fullstack" project!

You can see the project's code here:
- Backend (Java module runs on port 8080): https://github.com/AndyDeveloperIsCoding/Registration_Form_-_Java
- Frontend (React module runs on port 3000): https://github.com/AndyDeveloperIsCoding/name_and_sectors_react

The project requires a Postgres database available on Your machine (port 5432) with the following settings:
- Database name: testdb
- Username: testuser
- User password: password

<h3>Stack</h3>
The application stack is React, Java/Spring, REST API, Liquibase, Postgres, Hibernate, JUnit. Jest and Docker parts are started, but not finalized.

<h3>Functionality</h3>
The application enables a user to register his name and the business sectors they are currently involved in. It validates, that the name and at least one business sector is provided, the user agreement to terms are checked. When the validations are passed, the data is saved to the database and the submission form is cleared in the browser. If a user wants to register their data twice, a notification will appear that the data for the provided user is already present and the data of a non-existent user should be provided.
The frontend application communicates to the backend in two occasions: for fetching the list of possible business sectors and for saving the user data.    

<br><br>
Looking forward to hearing Your feedback and the suggestions for the app improvement!
