# React Native-Expo Starter Kit

This project serves as a boilerplate for a managed workflow [Expo](https://expo.io) application.

This is an opinionated starter kit for [React Native](https://facebook.github.io/react-native/)-[Expo](https://expo.io) projects to help kick start mobile applications development.

## Why use this starter kit?

It's an awesome fact that [Expo](https://expo.io) is making it very simple to develop native mobile applications using JavaScript. However, I believe that the architectural aspect of development should also be considered; this is most especially helpful when working with project teams.

This starter kit provides a simple project architecture that worked for my applications and I'm hoping that this will also work for your needs.

## Quick Start

To get you started on your development journey, follow the instructions below.

1. Clone the repository:

   `git clone https://github.com/arjayosma/react-native-simple-starter-kit.git`

2. Install all project dependencies

   `npm install`

3. Start coding
4. Run the application

   `expo start`

## Features

### Simple

This starter kit offers a very simple way of creating a managed workflow [Expo](https://expo.io) application. A bare and simplistic application-ready scaffolding is at your disposal to make your development life easier.

### Higher Modularity

Having a higher modularity in your mobile applications can help you identify which functionalities should go where. It's highly recommended to package your modules by feature to limit your scope during development.

## Structure

I consider the file structure below as the most suitable structure for most of my projects because of the features mentioned above.

- `assets`
  - `fonts`
  - `images`
- `routes`
- `src`
  - `components`
  - `config`
  - `modules`
  - `styles`
  - `utils`

## Dependencies

These are the project dependencies that I believe are going to be useful during development of any application.

You may add or remove existing dependencies as per your need. Listed below are the items without the default `expo`, `react`, and `react-native` dependencies.

1. [Axios](https://www.npmjs.com/package/axios) (`axios`)
   - A Promise based HTTP client.
   - This can be used for calling REST services for your application.
2. [NativeBase](https://nativebase.io/) (`native-base`)
   - A cross-platform UI components library for React Native.
   - This library simplifies the creation of UI components and screens.
3. [PropTypes](https://reactjs.org/docs/typechecking-with-proptypes.html) (`prop-types`)
   - Run typechecking on the props of your React Native components.
   - It provides a range of validators to help check the values being passed around.
4. [React Native Extended Stylesheet](https://github.com/vitalets/react-native-extended-stylesheet) (`react-native-extended-stylesheet`)
   - Abstracts styles from the different components and elements.
   - This library is a drop-in replacement for the built-in `StylSheet` class of React Native.
5. [React Navigation](https://reactnavigation.org/) (`react-navigateion`)
   - An extensible navigation solution for routing your screens from one to another.
   - It's an easy-to-use library for your routing needs.

## License

This project is licensed under the MIT license, Copyright (c) 2019 Arjay Osma. For more information see [LICENSE](https://github.com/arjayosma/react-native-simple-starter-kit/blob/master/LICENSE)