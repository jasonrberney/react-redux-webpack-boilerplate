# React Redux Webpack boilerplate using ES6

This template was modified from Kliment Petrov's repository here: [https://github.com/KleoPetroff/react-webpack-boilerplate](https://github.com/KleoPetroff/react-webpack-boilerplate). It is meant to be used for my future projects. I have modified the template to include necessary components for my projects. 

The boilderplate includes: 

- [x] React 16.3.1
- [x] ECMAScript 6 and JSX support
- [x] React Router v4
- [x] Component testing using [Enzyme](https://github.com/airbnb/enzyme) and [Jest](https://facebook.github.io/jest)
- [x] Code Coverage
- [x] Latest Webpack (v.3.11.0) and Webpack Dev Server (v.2.9.5) with Scope Hoisting enabled
- [x] Hot Module Replacement using [react-hot-loader](https://github.com/gaearon/react-hot-loader)
- [x] ES6 linting with continuous linting on file change
- [x] SASS support
- [x] Separate CSS stylesheets generation
- [x] Automatic HTML generation
- [x] Production Config
- [x] Custom Babel Preset with Decorators, Class Properties, Rest/Spread operator support
- [x] Export Separate Vendor Files
- [x] Redux

## Starting the dev server

Make sure you have the latest Stable or LTS version of Node.js installed.

1. `git clone https://github.com/KleoPetroff/react-webpack-boilerplate.git`
2. Run `npm install` or `yarn install`
3. Start the dev server using `npm start`
3. Open [http://localhost:8080](http://localhost:8080)

## Available Commands

- `yarn start` - start the dev server
- `yarn clean` - delete the dist folder
- `npm run production` - create a production ready build in `dist` folder
- `npm run lint` - execute an eslint check
- `npm test` - run all tests
- `npm run test:watch` - run all tests in watch mode
- `npm run coverage` - generate code coverage report in the `coverage` folder

## Code Coverage

The project is using the Jest Code Coverage tool. The reports are generated by running `npm run coverage`. All configurations are located in `package.json`, inside the `jest` object.

The coverage report consists of an HTML reporter, which can be viewed in the browser and some helper coverage files like the coverage json and xml file.

## Production code

Run `npm run production`. The production-ready code will be located under `dist` folder.

## Authors

- Kliment Petrov
- Jason Berney