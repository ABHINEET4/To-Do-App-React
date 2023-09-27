# To-Do-App-React

Hosted Website Link :- https://gorgeous-daffodil-34ba0a.netlify.app/

App Functionality :-
The Offline TODO App is designed to provide a simple and efficient way to manage your to-do list. 
It includes the following key features:-

Add TODOs: You can add new TODO items by typing them into the input bar and pressing the return key.

List of TODOs: All added TODOs are displayed as cards, with the most recently added items appearing at the top of the list.

Mark as Complete: Clicking on a TODO card will mark it as complete and move it to the bottom of the list. Completed TODOs are visually differentiated with a strikethrough.

Reset Button: There is a reset button in the top-right corner of the app that allows you to clear all TODOs and return to the initial state.

Offline Functionality: The app is designed to work offline, ensuring that hitting the refresh button or performing a hard refresh in the browser will not affect the app's state.

Project Files:-
src/Components/Form.js
Importing necessary React components and libraries.
Defining functions to retrieve and store TODOs in local storage.
Implementing state hooks for managing TODOs, input value, edit mode, and ID.
Handling form submission, editing, deletion, and checkbox toggling.
Using useEffect to save TODOs to local storage and keep the data persistent.

src/App.js
Importing the Form component.
Rendering the main app structure, including the header and the Form component.

src/index.css
CSS styles for the entire application, including the layout, input form, TODO cards, and buttons.

src/index.js
Importing necessary React components and rendering the App component in the root HTML element.

src/reportWebVitals.js
A script to measure the performance of the app, collecting data on various performance metrics like CLS, FID, FCP, LCP, and TTFB.

src/setupTests.js
Configuration for testing with Jest, including custom matchers for asserting on DOM nodes.

Usage :-
Clone the repository to your local machine.
Run npm install to install the required dependencies.
Run npm start to start the development server.
Open the app in your web browser at http://localhost:3000.


Screenshots :-

![image](https://github.com/ABHINEET4/To-Do-App-React/assets/108821830/c9c2b16b-c6e8-4117-beb3-c53caa5dd469)

![image](https://github.com/ABHINEET4/To-Do-App-React/assets/108821830/e9c2d7f8-98a4-4d9e-955c-1073781676ed)





