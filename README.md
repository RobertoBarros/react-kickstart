# react-kickstart
**just another react + webpack boilerplate**

[![Build Status](https://travis-ci.org/vesparny/react-kickstart.svg)](https://travis-ci.org/vesparny/react-kickstart)
[![Test Coverage](https://img.shields.io/codeclimate/coverage/github/vesparny/react-kickstart.svg)](https://codeclimate.com/github/vesparny/react-kickstart)
[![Dependency status](https://david-dm.org/vesparny/react-kickstart/status.svg)](https://david-dm.org/vesparny/react-kickstart "Dependency status")
[![Dev dependency status](https://david-dm.org/vesparny/react-kickstart/dev-status.svg)](https://david-dm.org/vesparny/react-kickstart#info=devDependencies "Dev dependency status")


## Minimal
It contains just the necessary to get started with React, I decided not to include flux libraries or other complicated stuff like server-rendering in here.

This projects aims to be a starting point for your React projects, and a way to learn it for newcomers.

See a [working demo](http://vesparny.github.io/react-kickstart/)

## Features
* webpack + hot-module-replacement ([babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform) + [react-transform-hmr](https://github.com/gaearon/react-transform-hmr))
* [css-modules](https://github.com/css-modules/css-modules/) + [stylus](https://learnboost.github.io/stylus/) + [PostCSS](https://github.com/postcss/postcss)
* basic routing setup with react-router (you most likely need routing in your app)
* [babeljs](https://babeljs.io/)
* unit tests ([mocha](http://mochajs.org/) + [chai](http://chaijs.com/)) examples with both [shallow-rendering](https://facebook.github.io/react/docs/test-utils.html#shallow-rendering) and [jsdom](https://github.com/tmpvar/jsdom)
* code coverage generation using [istanbul](https://gotwarlost.github.io/istanbul/)
* eslint and jscs configuration

## Usage

**Clone this repository**
```
git clone https://github.com/vesparny/react-kickstart.git
```

**Install**
```
npm install
```

**Start the application in dev mode with hot-module-replacement**
```
npm start
```

**Run tests**
```
npm test
```

**Build for production**
```
npm run build
```

**Run production version**
```
npm run build:start
```

**Run jscs and eslint**
```
npm run jscs
npm run eslint
```

**Generate code coverage report**
```
npm run test:cov
```

## Contributing

PR and issues reporting are always welcome :)

## License

See LICENSE file

## Changelog

See CHANGELOG.md file
