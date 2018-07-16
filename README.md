# React (Web + Native) Property Listing App

## Tech
- [Redux](https://redux.js.org/docs/introduction/)
- [React Native Router Flux](https://github.com/aksonov/react-native-router-flux) for native mobile
- [Native Base](https://nativebase.io/) for native mobile
- [Expo](https://expo.io/)
- [Airbnb's JS Linting](https://github.com/airbnb/javascript) guidelines

## Setup

#### 1. Install

_*It's recommended that you install [React Native Debugger](https://github.com/jhen0409/react-native-debugger/releases) and open before `npm start`._

```bash
# Install dependencies
npm install
```

#### 2.1. Run the _React Native_ App

```bash
# Start the React Native packager
npm start
```

Instructions are shown in the terminal. You can select to open it in:

- An emulator (either iOS or Android)
- Your mobile device with the [Expo app](https://expo.io/). It will reload if you save edits to your files and you will see build errors and logs in the terminal.

#### 2.2. Run the _Web_ App

```bash
# Starts are local live-reload server at:
# http://localhost:3001
npm run web
```

Via webpack, starts a localhost server on port 3001 [http://localhost:3001](http://localhost:3001).

- Save code and it auto refreshes
- Install [Redux DevTools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en) into Chrome to see the state of Redux
