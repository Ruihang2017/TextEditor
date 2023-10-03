![GitHub](https://img.shields.io/badge/license-mit-blue)

# TextEditor

## Deployed link (Heroku):

https://floating-shelf-28407-4440061b92a7.herokuapp.com/

## Table of Contents

- [Project Description](#Project-Description)
- [User Stories](#User-Stories)
- [Usage](#Installation-and-Usage)
- [Screenshots](#Screenshots)
- [Deployment Links](#Deployment-Links)

## Project Description

A single-page PWA Web text editor allows user to create notes or code snippets with or without an internet connection. It can be reliably retrieved for later use.

## Features

- **WHEN** the user opens the application in their editor
- **THEN** they should see a client-server folder structure
- **WHEN** the user runs `npm run start` from the root directory
- **THEN** they find that the application starts up the backend and serves the client
- **WHEN** the user runs the text editor application from the terminal
- **THEN** they find that their JavaScript files have been bundled using webpack
- **WHEN** the user runs their webpack plugins
- **THEN** they find that they have a generated HTML file, service worker, and a manifest file
- **WHEN** the user uses next-gen JavaScript in the application
- **THEN** they find that the text editor still functions in the browser without errors
- **WHEN** the user opens the text editor
- **THEN** they find that IndexedDB has immediately created a database storage
- **WHEN** the user enters content and subsequently clicks off of the DOM window
- **THEN** they find that the content in the text editor has been saved with IndexedDB
- **WHEN** the user reopens the text editor after closing it
- **THEN** they find that the content in the text editor has been retrieved from their IndexedDB
- **WHEN** the user clicks on the Install button
- **THEN** they download their web application as an icon on their desktop
- **WHEN** the user loads the web application
- **THEN** they should have a registered service worker using workbox
- **WHEN** the user registers a service worker
- **THEN** they should have their static assets pre-cached upon loading, along with subsequent pages and static assets
- **WHEN** the user deploys to Heroku
- **THEN** they should have proper build scripts for a webpack application

## Technologies Used

- PWA
- Webpack
- Babel
- Workbox
- IndexDB
- Manifest
