# PWA Text Editor Application

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Screenshots](#screenshots)
* [Heroku](#heroku)
* [GitHub](#github)

<br/>

# Description
The task of this challenge required us to build a progressive web application (PWA) text editor that runs in the browser. This application is also able to function offline. The challenge implements methods for getting and storing data to an IndexedDB database. The application is then deployed into Heroku to run the application.

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

# Installation
To run the application, please install necessary npm modules through the command line by inputing `npm install`. Once modules have been installed, run `npm run start` on the web browser or it can be ran through Heroku

# Screenshots
Text Editor Application<br>
![Text Editor Application](/images/text-editor-app.JPG)
Text Editor Install Request<br>
![Text Editor Install Request](/images/text-editor-install.JPG)
Text Editor Installed<br>
![Text Editor Installed](/images/text-editor-installed.JPG)
Text Editor with Text<br>
![Text Editor with Text](/images/text-editor-with-text.JPG)
Manifest<br>
![Manifest](/images/manifest.JPG)
Service Workers<br>
![Service Workers](/images/service-workers.JPG)
Storage<br>
![Storage](/images/storage.JPG)
IndexedDB<br>
![IndexedDB](/images/indexedDB.JPG)

# Heroku
[Deployed on Heroku](https://serene-dusk-03109.herokuapp.com/)

# GitHub
[GitHub Repo](https://github.com/ehliao/text-editor-application)
<br/>
[My GitHub Username](https://github.com/ehliao)


