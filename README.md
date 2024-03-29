# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). <br>

## Available Scripts <br><br>

In the project directory, you can run: <br><br>

### `npm start` <br><br>

Runs the app in the development mode.\  <br>
Open [http://localhost:3000](http://localhost:3000) to view it in your browser. <br><br>

The page will reload when you make changes.\ <br>
You may also see any lint errors in the console. <br><br>

### `npm test` <br><br>

Launches the test runner in the interactive watch mode.\    <br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information. <br><br>

### `npm run build` <br><br>

Builds the app for production to the `build` folder.\   <br>
It correctly bundles React in production mode and optimizes the build for the best performance. <br><br>

The build is minified and the filenames include the hashes.\    <br><br>
Your app is ready to be deployed!   <br><br>

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.   <br><br>

### `npm run eject` <br><br>

**Note: this is a one-way operation. Once you `eject`, you can't go back!** <br><br>

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project. <br><br>

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.  <br><br>

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it. <br><br>

## Learn More   <br><br>

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).   <br><br>

To learn React, check out the [React documentation](https://reactjs.org/).  <br><br>

### Code Splitting  <br><br>

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting) <br><br>

### Analyzing the Bundle Size   <br><br>

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)   <br><br>

### Making a Progressive Web App    <br><br>

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app) <br><br>

### Advanced Configuration  <br><br>

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration) <br><br>

### Deployment  <br><br>

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment) <br><br>

### `npm run build` fails to minify <br><br>

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify) <br><br>

#   Git hub deployment  <br><br>

> npm install --save-dev gh-pages   <br><br>

package.json add followings:-   <br><br>

1. add below in the top level   <br>
   "homepage": "https://username.github.io/repo-name",  <br>

2. Add the following scripts to the scripts section of your package.json:   <br>
   "scripts": { <br>
   "predeploy": "npm run build",    <br>
   "deploy": "gh-pages -d build",   <br>
   "start": "react-scripts start",  <br>
   "build": "react-scripts build",  <br>
   "test": "react-scripts test",    <br>
   "eject": "react-scripts eject"   <br>
   }    <br>    <br>

3. npm run deploy   <br><br>

4. Configure GitHub Repository: <br>
   Go to your GitHub repository settings and ensure that the GitHub Pages source is set to the gh-pages branch  <br>

5. Access Your Deployed App: <br>
   After a few moments, your React app should be accessible at the specified GitHub Pages URL (https://username.github.io/repo-name).   <br><br>

After making changes in the project <br>

> npm run build <br>
> npm run deploy    <br>
