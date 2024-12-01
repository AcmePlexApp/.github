# Backend Setup Instructions
- Using git, clone "backend" repository at https://github.com/AcmePlexApp/backend
- Install MySQL server.
- Using SQLWorkbench or other means, Create a localhost MYSQL database schema called "ACME", with user "root" and no password.
- Confirm MySQL server is running
- In eclipse, install "Spring Boot 4" plugin.
- In eclipse, "open project from folder contents" and navigate to this folder "ACME".  Will open up  the project in Eclipse.
- RUN project as a Java application.  Should start up a server on localhost:8080.
- To confirm back end server is running Open http://localhost:8080/auth/create in a browser - If it is running you should get a 403 Authorization Error in your browser.

# Front End Setup Instructions
- Clone "acmeplex" repository using https://github.com/AcmePlexApp/acmeplex
- Install node.js
- Open a terminal inside the "acmeplex" folder and run the command "npm install".  Confirm that all required packages are installed.
- Run the command "npm run dev".  This should show the front end server opening at http://localhost:5173/
- Open the server address in a browser window.  You should now be able to interact with the application.
