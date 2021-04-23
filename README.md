# MyFirstApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.9.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
# my-first-app
# my-first-app

# add the bootstap
To add the bootstap module local to the project and not globall
npm install --save bootstrap@3

# git sstrict mode
All the code will only work if you are NOT using "strict mode". Strict mode forces you to write more verbose code in some places (especially when it comes to class properties). If you enabled it by accident, you can also disable it by setting 'strict: false' in your tsconfig.json file.

# How to use
Run "npm install" inside this project folder to install all dependencies.
Make sure you use the latest version of the CLI (upgrade guide below)
Run "ng serve" to see the app in action (try "npm start" in case "ng serve" fails).

# How to upgrade the CLI
Run the below commands - only use "sudo" on Mac/ Linux.

sudo npm uninstall -g angular-cli @angular/cli
npm cache clean --force
sudo npm install -g @angular/cli

# creating a component from cli
$ ng generate component servers
or
$ ng g c server
