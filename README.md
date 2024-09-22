# PWA-Text-Editor

## Description
This application is a text editor web application that runs in the browser. It's a single-page application that meets the PWA criteria and features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.
Key features of this text editor include:

* Client-Server Folder Structure: The application is organized with a client-server folder structure, ensuring clear separation of concerns and easier maintenance.
* Webpack Bundling: JavaScript files are bundled using webpack, optimizing the application for performance.
* Service Worker and Workbox: The application uses a registered service worker using Workbox, allowing for offline functionality and faster load times.
* IndexedDB Storage: Content entered in the text editor is saved in IndexedDB, providing persistent local storage.
* Installation Capability: Users can install the web application on their desktop, making it easily accessible.
* JavaScript Syntax Highlighting: The text editor includes JavaScript syntax highlighting, enhancing the coding experience.
* Automatic Saving: Content in the text editor is automatically saved when the DOM window is unfocused.

## Usage 
To use this text editor application, follow these steps:

* Clone the Repository
git clone https://github.com/digitalscribe53/PWA-Text-Editor.git
cd PWA-Text-Editor

* Install Dependencies
npm install

* Run the Application Locally
npm run start:dev
This will start the backend and serve the client, running the text editor on your local machine.
Open in Browser
Open your preferred web browser and visit http://localhost:3000
Use the Text Editor

Type or paste your content into the text editor.
The content will automatically be saved when you click off the DOM window.
To test offline functionality, open the Application tab in Chrome DevTools and switch to offline mode.

* Install as PWA

Click the "Install" button in the application's header.
Follow the prompts to install the application on your desktop.

## Deployed URL 
[Click](https://pwa-text-editor-enhq.onrender.com/)
