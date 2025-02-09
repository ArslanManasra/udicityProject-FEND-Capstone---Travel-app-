Project Intro


Building a web app that allows users to to plan their trips based on predicted weather forecasts for the location they are travelling to.

The goal of this project is to get practice with:

Setting up a server environment
Setting up Webpack
Sass styles
Webpack Loaders and Plugins
Targeting the DOM, working with objects
Creating layouts and page design
Service workers
Using APIs and creating requests to external urls
Working with Testing units
Language and tools for this project:

Node & Express: For server side development
js: For client side development
Webpack: Build tool
Service workers: Offline functionality
Jest: Testing unit
Project rubric:

Check out the specifications here.

Project Extension
Some extra features were included in this project:

Pull in an image for the country from Pixabay API when the entered location brings up no results (good for obscure localities).
Allow the user to remove the trip.
Getting Started
Follow the steps below to get the project running.

Clone this Github repository and use NPM to install all the dependencies listed in the package.json file:

$ git clone https://github.com/ArslanManasra/udicityProject-FEND-Capstone---Travel-app-
$ cd FEND-Capstone-travel-app
$ npm install
Then, start the local server:

$ npm run build-prod
$ npm start
The app will be running in your browser on localhost:8081

Runnning the development mode
After completing the steps above, open a second terminal and start the webpack dev server:

$ npm run build-dev

The development version of the app will be running in your browser on localhost:8080
(the page will automatically update in the browser after any code change)

Testing Unit
This project has a Testing Unit to check if the main functions are working correctly. Testing is done with Jest.

To run tests you can use the following NPM command:

$ npm run test

The test results will be displayed on the terminal.
