# Overview
This is the repository to reproduce the issue when some cordova camera plugin are not merged into the resulting AndroidManifest.xml

# Prerequisities

* [Node.js](http://nodejs.org/) - install node version 18.15.0 (see the installation instructions on the site) or issue `nvm install` (if nvm is used) which will install the required node version
* (if using nvm) Switch to node 18.15.0 by issuing `nvm use 18.15.0` (you may want to make this default node version)
* [npm](https://www.npmjs.com/) - install the latest npm version 9.6.x (for example, 9.6.4 by issuing commands `npm install -g npm@9.6.4`)
* [Ionic CLI](http://ionicframework.com/docs/cli/install.html) - install the latest stable ionic cli version 7.0.x (for example, 7.0.1 by issuing commands `npm install -g @ionic/cli@7.0.1`)
* Install Capacitor Required Dependencies for Android Development (see https://capacitor.ionicframework.com/docs/getting-started/dependencies/)

# Instructions
## Initial setup
1. clone the source code repository
2. change to project repository directory (the directory where you cloned the repo)
3. execute the command `npm install`
4. to build and run the app execute the command `ionic capacitor build android` to open projects in Android Studio, then build and run from there
