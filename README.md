# Angular Endpoint Test

This project is a test of making REST APIs with the Angular 17 update, with a project originally done in Angular Univeral now re-implemented and modernized as Angular SSR here. There are limitations and difficulties with using an Express server that runs Angular SSR to simulatenously implement REST API routes that are accessible to your Angular components.

The major resources I used to create this were https://medium.com/@aayyash/replacing-angular-universal-with-ssr-version-f257dfae305f and https://dev.to/jdgamble555/angular-universal-rest-api-endpoints-23fj

It was originally just an updated version of the latter link, working with Angular SSR instead of Angular Universal, that I build in the course of working on my Autocode project, so feel free to ignore any of the form elements and form logic. 

One major workaround used here, in order to get the api/me endpoint to run on your local machine, is that you must run "ng build", then run node dist/angular-endpoint-test/server/server.mjs. It may be possible to also do it with "ng serve", but not as currently configured, and not with any documented configuration.

## Edited Default Docs Follow

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.1.1.

## Development server

Run `ng serve` for a dev server but note that API endpoints won't work properly as currently configured. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
