# Bellingcat Discord Server Entity Network Visualisation

This project generates an [interactive visualisation](https://bellingcat.github.io/4-year-anniversary-network/) in messages from the Bellingcat Discord Server.

This visualisation was developed by Bellingcat based on an excellent [Sigma.js demo](https://github.com/jacomyal/sigma.js/tree/main/demo), and uses [react-sigma-v2](https://github.com/sim51/react-sigma-v2) to interface sigma.js with React.

You can view the live visualisation [here](https://bellingcat.github.io/4-year-anniversary-network/). With GitHub pages configured, after making changes to the `main` branch, you need to run the command `npm run deploy` for the latest changes to be reflected in the live visualisation.

## NPM Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:5000](http://localhost:5000) to view it in the browser.

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
