# React Events State Exercise

1a. Create a function component called Exercise

1b. Add the export line at the bottom of the file

1c. Inside the Exercise function component, use the RETURN keyword with parentheses to have the Exercise function component return a button element and set the text inside of it to "CLICK HERE"

1d. Open the App.js file and add the necessary import line at the top of the file that allows the Exercise component to be used in the App.js file. Also, use the Exercise component in the return for the App component.

1e. Use the "onClick" React event listener on the button and set the value for the "onClick" React event listener to a function that alerts the user with the following message when the button is clicked…
"Congrats! You have clicked the button."
(HINT: Remember to use brackets {})

2a. Add the necessary import line at the top of the Exercise.js file that allows for the useState function to be used in this file/component

2b. Create another button element below the "CLICK HERE" button in the Exercise function component set the text inside of it to "STATE"

2c. Above the return keyword in the Exercise function component, use the "useState" function with the number 1 passed in as an argument. Also, use destructuring to set the values of the array that are returned from the useState function to the following const variable names…<br>
First name: "num"<br>
Second name: "setNum"<br>
(NOTE: Remember that the useState function returns an array of two items. First is the value that was passed into the useState function and the second is a function.)<br>

2d. Below useState function, create a function called addNum that adds one to the value of the num variable and sets that as the new state value for the num variable by using the setNum function inside of the addNum function

2e. Use the "onClick" React event listener on the "STATE" button and set the value for the "onClick" React event listener to the addNum function (HINT: Remember to use brackets {})

2f. Below the "STATE" button, create another h1 with the num variable set as the content/text inside the h1 (HINT: Remember to use brackets {}) (NOTE: If is done correctly, then in Chrome the value of the h1 should start at 1 and go up by 1 every time the "STATE" button is clicked)

<hr>

Bonus<br>

3a. Import the useState function at the top of the file

3b. Create a function component called Bonus.

3c. Add the export line at the bottom of the file

3d. Inside the Bonus function component create a const variable called "letters" with the following array set as the value ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'];

3e. Inside the Bonus function component use the return keyword to have it return an h1 and a button (Set the text for the button to "NEXT LETTER")

3f. Using State as well as an onClick Event, have the letter A display in the h1 when the page loads and change to the next letter in the alphabet each time the button is pressed.

3g. Open the App.js file and create the Bonus import below the Exercise import at the top of the file

3h. Inside the return for the App component, pass in the Bonus component below the Exercise component so it will render to the browser

<hr>

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
