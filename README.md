# Introduction

This repo contains an Angular implementation of a simple receipt management website, as described by the following assignment.


# Assignment

Create a receipt management website that will be hosted locally on the user's machine for now.  Therefore, no backend is needed at this time.

The user should be able to:
- Add pictures from his machine to the site
- Provide the following information about the receipt:
  - Business name
  - Location (city and state)
  - Date of purchase
- Browse all receipts he has added
- View and edit each receipt he has added
- Delete any of the added receipts

The website does not have to support user authentication or login.


# Solution


## Assumptions

- No localization or internationalization
- Date is in the user's current time zone.   No timezone support for receipt date



## Style

This repo uses the Angular [style guide](https://angular.io/guide/styleguide#style-guide).

# License

Contents of this repo are licensed under the Apache License, Version 2.0.  Please see the `./LICENSE` file for details.


# Usage

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.3.

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
