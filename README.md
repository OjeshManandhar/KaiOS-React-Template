# KaiOS-React-Template

A starter template for KaiOS app using ReactJS

### To use

- Clone the repo
- run **yarn** or **yarn install** to install the required _node_modules_
- Update the app details in _./public/manifest.webapp_, _./public/index.html_ and __name__ in  _./package.json_ if necessary.
  - **version**, **type** and **categories** are necessary in _./public/manifest.webapp_ to run [**KaiAds**](https://www.kaiads.com/publishers/sdk.html)
  - Currently **KaiAds _version 3_ SDK** file is present in the _./public_ folder and this file provides the function _getKaiAds()_
  - Use the function **getKaiAds()** as **window.getKaiAds()**
- The starting point is the _./src/index.js_ file as normal React app made using [**create-react-app**](https://www.npmjs.com/package/create-react-app)
- After running **yarn build**, a _./build_ folder will be created in the root directory, then send the contents of the _./build_ folder to the device by [WebIDE](https://developer.kaiostech.com/getting-started/build-your-first-package-app/test-your-apps#webide) or load the contents of the _./build_ folder by [Simulator](https://developer.kaiostech.com/getting-started/build-your-first-package-app/test-your-apps#simulator).

---

# Contents from **create-react-app**

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
