# `react-scripts-ts-static` [![npm version](https://badge.fury.io/js/react-scripts-ts-static.svg)](https://badge.fury.io/js/react-scripts-ts-static) [![Build Status](https://travis-ci.org/wmonk/create-react-app-typescript-static.svg?branch=master)](https://travis-ci.org/wmonk/create-react-app-typescript-static)

Create React apps (with Typescript) with no build configuration.

 * [Getting Started](#tldr) – How to create a new app.
 * [User Guide](https://github.com/wmonk/create-react-app-typescript/blob/master/packages/react-scripts/template/README.md) – How to develop apps bootstrapped with react scripts ts.

This repo is fork from official create-react-app TypeScript implementation: https://github.com/wmonk/create-react-app-typescript.

The only deference is that file names are made static (no hashes included) for production builds. It may be useful if you are going to publish your app using Visual Studio or other tool which require static file names. See https://github.com/facebook/create-react-app/issues/3855.

## Getting Started

```sh
npm install -g create-react-app

create-react-app my-app --scripts-version=react-scripts-ts-static
cd my-app/
npm start
```
