# EXOSPHERE

A client for making things happen in the cloud. Currently targeting OpenStack.


## Scaffold and Electron

To run this Electron app you will need to install Electron. You will also need elm, npm, and node.

Convenience commands to do this:

```bash
npm install
```

To compile and run the app:

```bash
npm run elm
npm run start
```

To watch for changes to `*.elm` files, auto-compile when they change, and hot-reloading of the app:

```bash
npm run watch
```

Based on the instructions found here:

<https://medium.com/@ezekeal/building-an-electron-app-with-elm-part-1-boilerplate-3416a730731f>

-------

Building a packages

Install the electron packager
https://www.npmjs.com/package/electron-packager

```bash
# for use in npm scripts 
npm install electron-packager --save-dev
 
# for use from cli 
npm install electron-packager -g
```

Run the packager like this and you will build a package for the OS you are running the command on.

```bash
electron-packager .
```