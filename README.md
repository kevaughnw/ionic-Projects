# ScoreBook
Webbabox Project

## Run the app
Make sure you have [nodejs](https://nodejs.org/en/) installed.

Install typecript
```bash
$ npm install -g typescript
```

Install Ionic CLI
```bash
$ npm install -g ionic
```

Install Cordova
```bash
$ npm install -g cordova
```

cd into the github folder run npm or yarn install
```bash
$ npm install or yarn install
```

add the platform that will be used
```bash
$ cordova platform add android or cordova platform add ios
```

You may need to restore the state of the ionic project, especially if you plan on using cordova.
```bash
ionic cordova prepare android or ionic cordova prepare ios
```

Build the app
```bash
$ npm run build or yarn run build
```

Run on android mobile
```bash
$ ionic cordova run android
```

Serve the app
```bash
$ ionic serve
```

Head to `http://localhost:8100` in your browser and you'll see the app running
