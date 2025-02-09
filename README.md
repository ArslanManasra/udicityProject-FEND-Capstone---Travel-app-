Project Introduction
This project is focused on building a web application that helps users plan their trips based on predicted weather forecasts for their travel destinations.

Project Goals
This project provides an opportunity to gain experience in:

Setting up a server environment
Configuring Webpack
Styling with Sass
Using Webpack Loaders and Plugins
Targeting the DOM and working with objects
Creating page layouts and designs
Implementing Service Workers for offline functionality
Using APIs and making requests to external URLs
Working with unit testing
Languages and Tools
Node.js & Express.js: For backend development
JavaScript: For frontend development
Webpack: For build optimization
Service Workers: For offline support
Jest: For unit testing
Project Rubric
To check the project specifications and evaluation criteria, refer to the provided documentation.

Additional Features
This project includes some extra features, such as:

Fetching an image of the country from the Pixabay API if no results are found for the entered location (useful for obscure places).
Allowing users to remove trips.
Getting Started
Follow these steps to run the project locally:

Clone the GitHub repository and install dependencies

bash
Copy
Edit
git clone https://github.com/ArslanManasra/udicityProject-FEND-Capstone---Travel-app-
cd FEND-Capstone-travel-app
npm install
Start the local server

bash
Copy
Edit
npm run build-prod
npm start
Once started, the app will be available in the browser at localhost:8081.

Running in Development Mode
After completing the steps above, open a new terminal window and start the Webpack Dev Server:

bash
Copy
Edit
npm run build-dev
The development version of the app will run on localhost:8080, and any code changes will automatically update in the browser.

Unit Testing
This project includes unit tests using Jest. To run the tests, use the following command:

bash
Copy
Edit
npm run test
