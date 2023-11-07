# Text Editor

## Description

I want to build a text editor that someone can access via website and/or download to use.

### User Story

AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

### Acceptance Criteria

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

## Installation

Download the files from the repo and be sure to install the following:

- MongoDB
- Express
- Mongoose

Once installed, start your server and test in Insomnia.

## Usage

This is an app local on your device that you may trigger within terminal and see the functionality in Insomnia

Link to video: [Social API](https://drive.google.com/file/d/1vfQCZrYs9eiavhVVP4kIXE90ziFXViFy/view)

Screenshot of App: 

![Social API](/social-app.png "Social API")

## Credits

* Worked through the documentaiton from class activities

* Received assistance from AskBCS Quinton

## License

None
