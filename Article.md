# WEB APPLICATION IN NODEJS AND EXPRESS USING EXPRESS GENERATOR, SEQUELIZE, SEQUELIZE-CLI, ASSOCIATIONS AND MIGRATIONS
# INTRODUCTION
*This article uses Express Js for handling Hypertext Transfer Protocol(HTTP) requests and MYSQL for storing data. Node Js is a platform used for building server side application using Javascript.Express is a flexible Node Js web application framework and provides a set of robust features for web and mobile applications.Developers do not need to build everything from scratch. Our first focus is ExpressJs which is one of the most used packages by developers build web APIs. Lastly, we focus on sequelize which is used to simplify the communication between NodeJs and MYSQL.*
### REQUIREMENTS
* Basic Javascript Knowledge
* Install Node.Js
* Install NPM
* Install Express 
* Install MYSQL Server
* Install XAMPP 
* Sequelize 
* Visual Studio(VS) Code or any other editor
### PART 1: 
**CREATING PROJECT USING EXPRESS GENERATOR**
**STEP 1**
* Open command prompt. 
### Command Prompt
![alt text](/public/images/commandline.png)
**STEP 2**
* Create a folder for the node project in the location of your choice. Navigate to the folder, and then type
* Make directory to the name of the folder
*mkdir fileName*
*cd fileName*
*code . to take you to the code editor*
### 
![alt text](/public/images/cd.png)
**STEP 3**
* We run *npx express-generator* inorder to generate the express server
* We can install express globally for our projects
*npm install -g express-generator*
###
! [alt text](/public/images/express.png)
*The project is created with series of directories as javascripts, stylesheets, routes, views and with files as package.json, app.js and few other files. This also specifies the next step to be executed (the command to install the dependencies)*
**STEP 4**
* Install Dependencies
*npm install*
###
! [alt text](/public/images/step3.png)
*Lets view the package.json file that is created. All the dependencies needed for the project is added here automatically.*
! [alt text](/public/images/dep.png)
*A directory with the name node_modules is created in the project folder and all the dependencies are added automatically in node_modules directory. The project setup is ready.*
*We open the app.js and see what is embedded in it . All the dependencies are invoked by the use of require method.*
### app.js screenshot
! [alt text](/public/images/app.js.png)
* The use of modules in app.js:
* body-parser – A middleware for handling Raw, Text, JSON and URL encoded form data(especially POST data).
* Cookie-Parser – To parse Cookie header and populate req.cookies with an object keyed by the cookie names.
* Jade-A template engine . It combines data and the template to produce HTML.! [alt text](/public/images/app.js.png)
* express – A web application framework that provides a set of features for web and mobile applications
* morgan – A HTTP request logger middleware for node.js
* Now, let’s run our application. Go to the command line
* Run the server with *npm start*
* The server gets started and listens to port 3002. Open the browser and load http://localhost:3002.You will get the output as shown below.
### 
! [alt text](/public/images/index.png)
! [alt text](/public/images/run.png)


### PART 2:
**SEQUELIZE**

 