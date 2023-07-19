# Text_Editors-PWA-
## Description 

The application is a web-based text editor that allows users to create and store notes or code snippets, with or without an internet connection. It ensures reliable retrieval of the saved content for future use. The integration of service workers and the Cache API enables the application to function seamlessly even when there is no active internet connection. This allows users to access previously visited pages even when the application is offline.

You can find the source code of the application on GitHub at the following repository 
URL:[ GitHub Repository](https://github.com/SanaS7/Text_Editors-PWA-/tree/main).

🚀 The application has been deployed to Heroku, and you can access it using the following URL:
Deployed Application on Heroku

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)

## Installation
To set up the text editor, you need to install Node.js and several npm packages.

Node Package Manager (npm) is a software manager and installer that allows you to install and manage the required modules for the Node.js project. It intelligently handles dependency conflicts and generates a package.json file that contains project details.

This application utilizes the following npm packages:

*cexpress.js: npm install express
* Webpack: npm install --save-dev webpack
* webpack-dev-server: npm install webpack-dev-server --save-dev
* WebpackPwaManifest: npm install --save-dev webpack-pwa-manifest
* Babel: npm install babel
* CSS-loader: npm install --save-dev css-loader
* Concurrently: npm install concurrently --save
* IndexedDB: npm install idb

All the required modules are listed in the package.json file. To install them, open the command line interface or integrated terminal, navigate to the project directory, and run the command "npm install". This will install all the necessary dependencies for the application


## Usage

1.
``````    
GIVEN a text editor web application, 
WHEN I open my application in my editor
THEN I should see a client server folder structure
``````



2.
``````
    WHEN I run `npm run start` from the root directory
    THEN I find that my application should start up the backend and serve the client
    WHEN I run the text editor application from my terminal
    THEN I find that my JavaScript files have been bundled using webpack
    WHEN I run my webpack plugins
    THEN I find that I have a generated HTML file, service worker, and a manifest file
``````

