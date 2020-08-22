#  🏆 React Native Starter Architecture 🏆 
[![React Native](https://img.shields.io/badge/React%20Native-v0.63.0-green.svg)](https://facebook.github.io/react-native/)
[![React Navigation V5](https://img.shields.io/badge/React%20Navigation-v5.7-blue.svg)](https://reactnavigation.org/)

This project aims to act as a template for React Native. This project configured with redux, redux saga and redux persist. 
Uses the latest version of react-navigation (v5.7)

## Scalability Factor

This Architecture is well fitted for small and medium scale apps. For building large scale application check out the Advance version of the template.

[React Native Advance Architecture](https://github.com/Toolbone/RNAdvanceArcht)


## Libraries
- [Typescript](https://www.typescriptlang.org/) support.
- [React Hooks](https://reactjs.org/docs/hooks-intro.html)
- [React Navigation](https://reactnavigation.org/) with [Authentication flow](https://reactnavigation.org/docs/auth-flow) baked in & theming support.
- [React Native Gesture Handler](https://github.com/kmagiera/react-native-gesture-handler)
- [React Native Paper](https://callstack.github.io/react-native-paper/)- with theming support 
- [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)
- [Redux](http://redux.js.org/) with [hooks](https://react-redux.js.org/api/hooks) support
- [Redux Saga](https://redux-saga.js.org/)
- [Redux Persist](https://github.com/rt2zz/redux-persist/)
- [Jest](https://facebook.github.io/jest/)
- [Eslint](http://eslint.org/) ([Airbnb config](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb))


## Prerequisites

- [Node](https://nodejs.org) v10 (it is recommended to install it via [NVM](https://github.com/creationix/nvm))
- [Yarn](https://yarnpkg.com/)
- A development machine set up for React Native by following [these instructions](https://facebook.github.io/react-native/docs/getting-started.html)

## Getting Started

1. Clone this repo, `git clone https://github.com/Toolbone/RNStarterArcht.git <your project name>`
2. Go to project's root directory, `cd <your project name>`
3. Remove `.git` folder, `rm -rf .git`
4. Use [React Native Rename](https://github.com/junedomingo/react-native-rename) to update project name `$ npx react-native-rename <newName>`
5. Run `yarn` or `npm install` to install dependencies

6. Start the packager with `npm start`
7. Connect a mobile device to your development machine
8. Run the test application:

- On Android:
  - Run `react-native run-android` or Use Android Studio (Recommended)
- On iOS:
  - Open `ios/YourReactProject.xcworkspace` in Xcode
  - Hit `Run` after selecting the desired device

9. All set!!!, you are ready to go!


