## Guide To Gathering The Skills Neccessary To Be A Professional Full-Stack Javascript Developer(WIP)

"This guide is for beginner developer(year 1) that are on the Full-Stack developer track and want to understand all the neccessary skills needed to **become a professional**. I will document the most important pieces to evolving as a developer and how to begin implementing them. **NOTE: THIS GUIDE IS FOR BEGINNERS. MY GOALS ARE TO TAKE OVERCOMPLICATED IDEAS AND DUMB THEM DOWN. USING SIMPLIFICATION TO BUILD INITIAL UNDERSTANDINGS**. Look through the folders section for a playground for each, as well as individual readme's for quick start."

> #### _Found it useful? Want more updates?_ [**Show your support by giving a :star:**](https://github.com/piotrwitek/react-redux-typescript-patterns/stargazers) 

### Goals
- Be able to understand what it takes to implement a Full-Stack Javascript application on a professional level.

### Complementary Projects
- Todos Application implementing React/Redux, GraphQL/Apollo, TypeScript, Jest/Enzyme, TravisCI/Heroku [Todos](https://github.com/jakedykstra)

### Playground Project
[![Todos](https://app.codeship.com/projects/11eb8c10-d117-0135-6c51-26e28af241d2/status?branch=master)](https://app.codeship.com/projects/262359)

## Contributing Guide
If you're planning to contribute please make sure to read the contributing guide: [CONTRIBUTING.md](/CONTRIBUTING.md)

---

## Table of Contents
- [Type Definitions & Complementary Libraries](#type-definitions--complementary-libraries)
- [React Types Cheatsheet](#react-types-cheatsheet) 🌟 __NEW__
- [Component Typing Patterns](#component-typing-patterns)
  - [Stateless Components - SFC](#stateless-components---sfc)
  - [Stateful Components - Class](#stateful-components---class) 📝 __UPDATED__
  - [Generic Components](#generic-components)
  - [Render Props](#render-props) 🌟 __NEW__
  - [Higher-Order Components](#higher-order-components) 📝 __UPDATED__
  - [Redux Connected Components](#redux-connected-components)
- [Redux](#redux)
  - [Action Creators](#action-creators) 📝 __UPDATED__
  - [Reducers](#reducers) 📝 __UPDATED__
    - [State with Type-level Immutability](#state-with-type-level-immutability)
    - [Typing reducer](#typing-reducer)
    - [Testing reducer](#testing-reducer)
  - [Store Configuration](#store-configuration) 📝 __UPDATED__
  - [Async Flow](#async-flow) 📝 __UPDATED__
  - [Selectors](#selectors)
  - [Typing connect](#typing-connect) 🌟 __NEW__
- [Tools](#tools)
  - [TSLint](#tslint)
  - [Jest](#jest)
  - [Enzyme](#enzyme)
  - [Living Style Guide](#living-style-guide) 🌟 __NEW__
  - [Common Npm Scripts](#common-npm-scripts)
- [Recipes](#recipes)
  - [tsconfig.json](#tsconfigjson)
  - [Vendor Types Augmentation](#vendor-types-augmentation)
  - [Default and Named Module Exports](#default-and-named-module-exports)
- [FAQ](#faq)
- [Tutorials](#tutorials)
- [Contributors](#contributors)

---

## Where to Start
It's easy to say harder to do. My advice, start with the basics. Learn JavaScript/CSS/HTML front and back and begin work on projects.

## What it takes (This is what I'm reviewing. It's a specific stack I've chosen to use. For rationale please refer here.
- Clean Code
  - Implement strong naming and follow design patterns
- Front-End
  - Understand the Basics to move forward - HTML5, CSS3, JavaScript
  - Know how to implement SPA (Single Page Application) - React, ReactRouter
    - With React you can build better, more responsive applications on the front-end.
    - You need to route your page within react
  - Use state management - Redux
    - With React, unless you want to link every component together to pass data, you'll need a store to pull, update, and add data.
  - Send AJAX requests - GraphQL/ApolloClient
    - There will be data needed from our database. Use GraphQL to get the exact data you need. Apollo helps us use GraphQL on the front-end
  - Use Static Type - TypeScript
  - Implement a precompiler for styling - SCSS
  - Unit Test - Jest with Enzyme
  - Handle 0Auth - NPM Packages (react-facebook-login/react-google-login)
  - Use a linter - TSLint
- Back-End
  - Know Node
  - Know your database. Choose SQL - MySQL/Sequelize
  - Pick a framework - Express
  - Handle API's - GraphQL
  - Authorization - PassportJS
  - Have a checker - TravisCI
- Deployment
  - Contain your application - Docker

## Tutorials
> Curated list of relevant in-depth tutorials

## Contributors

Thanks goes to these wonderful people 

#### ReadMe Structure motivated by Piotr Witek <piotrek.witek@gmail.com> (http://piotrwitek.github.io). Thanks!

---

MIT License

Copyright (c) 2019 Jacob Dykstra (http://www.github.com/jakedykstra)
