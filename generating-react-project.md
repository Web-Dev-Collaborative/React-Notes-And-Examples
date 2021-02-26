# Generating React Project

![](.gitbook/assets/image%20%2812%29.png)

![](.gitbook/assets/image%20%2817%29.png)



![](.gitbook/assets/image%20%2810%29.png)

![](.gitbook/assets/image%20%2818%29.png)

![](.gitbook/assets/image%20%288%29.png)

Babel is a way to write ES2015 or 2016 javascript and convert it to ES5 so that it can run on any browser.



## Getting Started with Create React App <a id="getting-started-with-create-react-app"></a>

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts <a id="available-scripts"></a>

In the project directory, you can run:

#### `npm start` <a id="npm-start"></a>

Runs the app in the development mode.  
Open [http://localhost:3000](http://localhost:3000/) to view it in the browser.

The page will reload if you make edits.  
You will also see any lint errors in the console.

#### `npm test` <a id="npm-test"></a>

Launches the test runner in the interactive watch mode.  
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build` <a id="npm-run-build"></a>

Builds the app for production to the `build` folder.  
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.  
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

#### `npm run eject` <a id="npm-run-eject"></a>

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies \(webpack, Babel, ESLint, etc\) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

### Learn More <a id="learn-more"></a>

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

#### Code Splitting <a id="code-splitting"></a>

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

#### Analyzing the Bundle Size <a id="analyzing-the-bundle-size"></a>

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

#### Making a Progressive Web App <a id="making-a-progressive-web-app"></a>

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

#### Advanced Configuration <a id="advanced-configuration"></a>

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

#### Deployment <a id="deployment"></a>

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

#### `npm run build` fails to minify <a id="npm-run-build-fails-to-minify"></a>

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting\#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)



![](.gitbook/assets/image%20%2813%29.png)



![](.gitbook/assets/image%20%2816%29.png)





![](.gitbook/assets/image%20%2811%29.png)

![](.gitbook/assets/image%20%289%29.png)





```text
tree
.
├── README.md
├── package-lock.json
├── package.json
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    ├── reportWebVitals.js
    └── setupTests.js

2 directories, 17 files
```





![](.gitbook/assets/image%20%2819%29.png)





```javascript
//! 1.)     import the react and reactDOM libraries
import React from 'react';
import ReactDOM from 'react-dom';
//==> React uses a bundler package called webpack
//===> the coe we write in index.js is not automatically available throughout the project
//=====> The same is true of any js file and that is why we need to import them.







//! 2.)     Create React Component











//! 3.)       Take the react component and render it on the screen







```



![](.gitbook/assets/image%20%2815%29.png)



```javascript
//! 1.)     import the react and reactDOM libraries
import React from 'react';
import ReactDOM from 'react-dom';
//==> React uses a bundler package called webpack
//===> the coe we write in index.js is not automatically available throughout the project
//=====> The same is true of any js file and that is why we need to import them.







//! 2.)     Create React Component











//! 3.)       Take the react component and render it on the screen






```





```javascript
//! 1.)     import the react and reactDOM libraries
import <<<React>>> from 'react';
import ReactDOM from 'react-dom';
// The name of the react import is a matter of choice
// we could also write :
import MyReact from 'react'; //and it would work all the same.
```











