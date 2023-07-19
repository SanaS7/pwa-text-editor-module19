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
* [References](#references)
* [License](#license)

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
*Below is the screenshot of the client server folder structure.  The folder structure have been set up or given in this structure.*

![alt text](/assets/images/TE07.png)


2.
``````
    WHEN I run `npm run start` from the root directory
    THEN I find that my application should start up the backend and serve the client
    WHEN I run the text editor application from my terminal
    THEN I find that my JavaScript files have been bundled using webpack
    WHEN I run my webpack plugins
    THEN I find that I have a generated HTML file, service worker, and a manifest file
``````
*Below is the screenshot of the running at npm run start and npm run build* 

![alt text](/assets/images/TE02.png)

*Below is the screenshot of the generated HTML, service worker and a manifest file*

![alt text](/assets/images/TE08.png)

3.
``````
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
``````
*Below is the screenshot of the text editor "Just Another Text Editor (J.A.T.E)"*

![alt text](/assets/images/TE03.png)

4.
``````
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
``````
*Below is the  screenshot of content in the text editor has been retrieved from the IndexedDB"*

![alt text](/assets/images/TE05.png)

5.
``````
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
``````
*Below is the screenshot of icon on the desktop"*

![alt text](/assets/images/TE04.png)

6.
``````
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
``````
*Below is the screenshot of the static assets pre cached upon loading with subsequent pages and static assets"*

![alt text](/assets/images/TE09.png)

![alt text](/assets/images/TE10.png)

7.

 ````````
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application 
````````
![alt text](/assets/images/TE11.png)


## References

*   The Unit Ahead : Progressive Web Applications (PWA)
*   Module 19 Mini-Project: Deploy Contact Directory App on Heroku with Script
*   Request-Response : The Full-Stack Blog : Heroku Deployment Guide
 
