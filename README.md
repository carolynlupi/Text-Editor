# PWA-Text-Editor

Week-19 Challenge (Progressive Web Applications)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

## Table of Contents

- [Description](#description)

- [Live-URL](#live-url)

- [Technologies-Used](#technologies-used)

- [Installation](#installation)

- [Features](#features)

- [Usage-Information](#usage-information)

- [License](#license)

- [Questions](#questions)

## Description

This application serves as a practical demonstration and an opportunity for skill enhancement in the realm of progressive web applications (PWAs). Its primary aim is to provide a deeper insight into the inner workings of the React JavaScript library. Four main concepts are central to this application. First, it involves configuring the webpack.config.js file, incorporating essential Workbox plugins for service worker and manifest files, and implementing CSS and Babel loaders to ensure compatibility with older devices running on legacy code (e.g., ES5). Second, asset caching is employed within the src-sw.js file, enabling offline functionality. Third, the application involves configuring the database, facilitating the addition, updating, and retrieval of data from IndexedDB. Fourth, it incorporates event handlers for the install button, enabling users to install the application into their personal app stack for offline use.

While this application relies on a boilerplate code structure, its development has significantly enhanced understanding of libraries and frameworks like React, Angular, and Vue. While there are no immediate plans for further development, this application can serve as a valuable benchmark and boilerplate codebase for the creation of future progressive web applications.

## Live URL

https://glacial-fortress-44365-dc26fbaae169.herokuapp.com/

## Technologies Used

This application is powered by Webpack (HTML-Webpack-Plugin, Babel, and CSS Loader), Node.js (v16.19.1), Express.js (v.14.17.1), and JavaScript. Nodemon (v2.0.4) and Concurrently (v5.2.0) were utilized as a devDependencies allowing the server to refresh when edits were made to application, and allowing both the front end and back end to be ran on a single command (npm run start:dev).

![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)
![Babel](https://img.shields.io/badge/Babel-F9DC3e?style=for-the-badge&logo=babel&logoColor=black)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)

## Installation

Users can view and utilize the application through the use of the browser by visiting the deployed application at (https://glacial-fortress-44365-dc26fbaae169.herokuapp.com)

Viewing the application in the browser will also give users the ability to download the application allowing it to be used offline.


## Features

Once the application is opened, the IndexedDB will persist any notes added to the site. There is no need to save any information as the application automatically updates the IndexedDB -> the only thing required for this feature to occur is that the user click out of the window. When returning to the site, they will find all of their notes and other information persisted to the page.

## Usage Information

Usage of this application is very intuitive, just visit the live URL ((https://glacial-fortress-44365-dc26fbaae169.herokuapp.com)) and start adding notes right away! Users will also notice an install button in the nav bar allowing for the application to be downloaded and used offline. Saving of notes occurs automatically through the IndexedDB; the only thing required is for the user to click out of the window and notes will be persisted whether using the application online or offline.

## License

NOTICE: This application is covered under the MIT License

## Questions

Have additional questions? Click the links below to reach me through my GitHub account or Email address.

[Link to Github]((https://github.com/carolynlupi))

