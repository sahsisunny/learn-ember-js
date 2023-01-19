# Day 2 Orientation

## Check Version of the Ember CLI

- `ember --version`

Output:

```bash
ember-cli: 4.9.2
node: 16.13.0
os: win32 x64
```

## Day 2 Overview

Today i have to create a new Ember application named `super-rentals`.

- `ember new super-rentals --lang en`

**--lang** is used to set the language of the application. Following are the available languages:

- en, en-us, en-gb, etc.

## Starting and Stopping the Development Server

When we create a new Ember application, it comes with a development server. We can start the development server by running the following command:

- `ember serve` or `ember s` or `ember server`

We can stop the development server by pressing `Ctrl + C` in the terminal.

## Editing Files and Live Reload

When we start the development server, it will watch for changes in the files. If any changes are made to the files, it will automatically reload the browser.

# For reduce the time for creating a new project, we can skip the installation of the default packages.

- `ember new super-rentals --skip-npm --skip-bower`

After that, we can install the required packages.

- `npm install`
- `yarn install`
- `pnpm install`- faster than npm and yarn

## For add assets like images, fonts, etc. we can use the `public` folder.

- `public` folder is used to store the assets. It will be copied to the `dist` folder. So, we can access the assets from the `dist` folder.
