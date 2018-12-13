# Basic HTML5 boilerplate with Parcel Bundler

##Description
Use this as a starting point to complete the Bootstrap activity. It scaffolds out a simple web app with parcel support to bundle up our assets. The activity instructions will teach you how to install Bootstrap into it as well.

##Prerequisites

- You must have Node installed. visit https://byui-cit.github.io/advcss/lesson01/l01-software.html and skip to the Node section for instructions
- Yarn must be installed. After installing Node run `npm install yarn -g`

## Setup

- `yarn install` (If you get an error about node here then run `yarn install --ignore-engines`)
- `yarn start` starts up a local server and updates on any JS or CSS/SCSS changes.
- `yarn build` to build final files when you are ready to turn in.

## Add package

- `yarn add [package] --dev` or `yarn add [package]`
- `yarn upgrade` - when needed, updates all dependencies to their latest version based on the version range specified in the `package.json` file

## Using Boilerplate

- Import the javascript dependencies into `assets/js/scripts.js`
  - `import shipController from 'ships.js'`;
