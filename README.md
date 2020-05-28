This project is simplest form of Electron + React + Electron Builder

In the project directory, you can run:

### `npm install`

Installs all the dependencies <br />

### `npm start`

Launches react in browser at http://localhost:3000<br />
This is similar to `react-scripts start`

### `npm run dev`

Runs React and waits for it to load using wait-on package.<br />
Further it starts Electron app with http://localhost:3000

Any changes done in react reflects automatically (almost instantly) in electron and browser both.

### `npm run electron-build`
### `npm run electron-dist`

**Note: This command should run one after the other**

This creates react build using `react-scripts build` and further creates distribution in dist folder.