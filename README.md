CASE WORKER TASK MANAGEMENT SYSTEM (CWMS)
CwmsApp
This project was generated using Angular CLI version 19.2.9.

Development server
To start a local development server, run:

ng serve
Once the server is running, open your browser and navigate to http://localhost:4200/. The application will automatically reload whenever you modify any of the source files.

Code scaffolding
Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

ng generate component component-name
For a complete list of available schematics (such as components, directives, or pipes), run:

ng generate --help
Building
To build the project run:

ng build
This will compile your project and store the build artifacts in the dist/ directory. By default, the production build optimizes your application for performance and speed.

Running unit tests
To execute unit tests with the Karma test runner, use the following command:

ng test
Running end-to-end tests
For end-to-end (e2e) testing, run:

ng e2e
Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

Additional Resources
For more information on using the Angular CLI, including detailed command references, visit the Angular CLI Overview and Command Reference page.

- Notes
The app is fully responsive using Angular Material.
Ensure the backend application and Docker container for mySQL is running before using frontend features.
Description:
The app is able to

Create a task with the following properties:
Title (Mandatory and max 10 characters)
Description (Mandatory and max 100 characters)
Status (Mandatory and can have value ACTIVE or INACTIVE or IN COMPLETE)
Due date/time (Mandatory and Date and Time cannot be in past)
Retrieve a task by ID
Retrieve all tasks
Update the status of a task
Delete a task
Author: MFS
