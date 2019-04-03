# MusicMarket

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.5.

## FireBase Credentials

Must have a Google account.

Before serving the project, go to https://firebase.google.com/. You will the option to "Add project". Select it.

Click on the "Add FireBase to your web app" option (icon is </>).

Add the following code to src/app/api-keys.ts and fill in the fields with your corresponding FireBase information:

```bash

export const masterFirebaseConfig = {
    apiKey: "xxxx",
    authDomain: "xxxx.firebaseapp.com",
    databaseURL: "https://xxxx.firebaseio.com",
    storageBucket: "xxxx.appspot.com",
    messagingSenderId: "xxxx"
  };

```

Add /src/app/api-keys.ts to .gitignore file for FireBase information security. 


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
