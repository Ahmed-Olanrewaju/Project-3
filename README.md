# Project-3
Documentation for project-3

# SIMPLE TO-DO APPLICATION ON MERN WEB STACK

MERN Web stack consists of following components:
MongoDB: A document-based, No-SQL database used to store application data in a form of documents.
ExpressJS: A server side Web Application framework for Node.js.
ReactJS: A frontend framework developed by Facebook. It is based on JavaScript, used to build User Interface (UI) components.
Node.js: A JavaScript runtime environment. It is used to run JavaScript on a machine rather than in a browser.

[Web Application Frameworks](https://en.wikipedia.org/wiki/Web_framework)

[Practice basic JavaScript syntax just for fun](https://www.w3schools.com/js/js_intro.asp)

`sudo apt update`

![sudo apt update](./Images/sudo-apt-update.png)

`Upgrade-ubuntu-sudo-apt-upgrade`

![Upgrade-ubuntu-sudo-apt-upgrade](./Images/Upgrade-ubuntu-sudo-apt-upgrade.png)

location of Node.js software from Ubuntu repositories

![`location of Node.js software from Ubuntu repositories`](./Images/location-of-Node.js-software-from-Ubuntu-repositories..png)

Install Node.js on the server

![`Install Node.js on the server`](./Images/Install-Node.js-on-the-server.png)

Run the command below to verify that the Todo directory is created with ls command

![`Verify the node installation with the command below`](./Images/Verify-the-node-installation-with-the-command-below.png)

Application Code Setup
Create a new directory for your To-Do project:

![`Create a new directory for your To-Do project:`](./Images/Create-a-new-directory-for-your-To-Do-project.png)

Next, you will use the command npm init to initialise your project, so that a new file named package.json will be created.

![`information about your application and the dependencies that it needs to run npm init`](./Images/information-about%20your-application-and-the-dependencies-that-it-needs-to-run-npm-init.png)

# INSTALL EXPRESSJS

Express helps to define routes of your application based on HTTP methods and URLs.

![`npm install express`](./Images/npm-install-express.png)

![`touch index.js`](./Images/touch-index-js.png)

![`Run ls to confirm that index.js file is successfully created`](./Images/Run-ls.png)

![`npm install dotenv`](./Images/npm-install-dotenv.png)

![`index.js`](./Images/index-js.png)

![`node index.js`](./Images/node-index-js.png)

![`server-running-on-port5000`](./Images/server-running-on-port-5000.png)

![`Welcome to Express`](./Images/Welcome-to-Express.png)

![`mkdir routes cd routes`](./Images/mkdir-routes-cd%20routes.png)

![`touch api.js`](./Images/touch-api-js.png)

![vim api.js](./Images/Routes.png)

![`Routes`](image.jpg)

# MODELS

Install mongoose

Now comes the interesting part, since the app is going to make use of Mongodb which is a NoSQL database, we need to create a model.

A model is at the heart of JavaScript based applications, and it is what makes it interactive.

![`npm install mongoose`](./Images/npm-install-mongoose.png)


![`Create a new folder models`](./Images/Creating-a-new-folder-models.png)

![`Open the file created with vim todo.js`](./Images/Open-the-file-created-with-vim-todo-js.png)

![`In Routes directory, open api.js with vim api.js`](./Images/In-Routes-directory-open-api-js-with-vim-api-js.png)

![`new code`](./Images/new-code.png)

![`touch .env`](./Images/touch-env.png)

![`vi-env`](./Images/vi-env.png)

![`delete existing content in the file, and update it`](./Images/delete-existing-content-in-the-file-and-update-it.png)

![`Server running on port 5000 Database connected successfully`](./Images/node-index-js-Database-connected-successfully.png)

![`action working on project 3`](./Images/Action-working-on-project-3.png)

![`GET-request-on-API`](./Images/GET-request-on-API%20.png)

# STEP 2 – FRONTEND CREATION

it is time to create a user interface for a Web client (browser) to interact with the application via API. To start out with the frontend of the To-do app, we will use the create-react-app command to scaffold our app.

![`FRONTEND CREATION`](./Images/FRONTEND-CREATION.png)

![`npm install concurrently --save-dev`](./Images/npm-install-concurrently-save-dev.png)

![`npm install nodemon --save-dev`](./Images/npm-install-nodemon%20-save-dev.png)

![`In Todo folder open the package.json file. Change the highlighted part of the below screenshot and replace with the code below`](./Images/In%20Todo%20folder%20open-the-package-json-file-Change-the-highlighted-part-of-the-below-screenshot-and-replace-with-the-code-below.png)

![`vi package.json`](./Images/vi-package-json.png)

![`localhost:5000/api/todos`](./Images/localhost-5000-api-todos.png)

![`app-open-and-running-on-localhost-3000`](./Images/app-open-and-running-on-localhost-3000.png)

![`mkdir components`](./Images/mkdir-components.png)

![`touch-Input-js-ListTodo-js-Todo-js`](./Images/touch-Input-js-ListTodo-js-Todo-js.png)

![`vi Input.js`](./Images/vi-Input-js.png)

![`npm install axios`](./Images/npm-install-axios.png)

![`in the ListTodo.js copy and paste the following code`](./Images/in-the-ListTodo-js-copy-and-paste-the-following-code.png)

![`Then in your Todo.js file you write the following code`](./Images/Then-in-your-Todo-js-file-you-write-the-following-code.png)

![`vi App.js`](./Images/vi-App-js.png)

![`vi App.css`](./Images/vi-App-css.png)

![`npm run dev`](./Images/npm-run-dev.png)

![`My Todo`](./Images/MY-TO-DO.png)

