# Minesweeper

Minesweeper game is played by connecting to the websocket `wss://hometask.eg1236.com/game1/` and sending specific commands to it.

## Tech Stack

- React (Functional Components)
- TypeScript
- Material UI (CSS-in-JS)
- Redux, Redux-Saga, Redux Toolkit

## Source Code

- [Organised using feature-first approach](https://gist.github.com/arnausd23/137bab46215d69023729a1b30fb3ec9b)
- Covered with tests. Any coverage you see fit
- [Redux-Saga event channel is used to communicate with websocket](https://redux-saga.js.org/docs/advanced/Channels/)

## Demo

[Demo](https://webmas0124.github.io/minesweeper-websocket/)

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000/minesweeper-websocket](http://localhost:3000/minesweeper-websocket) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
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
