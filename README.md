# AppWithoutNgrx

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 19.2.7. In this boiler plate, ngrx structure is not added.

Make sure that you are using a supported version of node.js before using this application. Angular v19 supports node.js versions: ^18.19.1 || ^20.11.1 || ^22.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

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

## app.routes.ts

the app.routes.ts file is typically used to define the routes for your application.
export const AppRoutes = {
welcome: 'welcome',
};

## app.component.ts

The app.component.ts file is the main component of an Angular application. It is responsible for defining the behavior and properties of the root component of the application.

## app.config.ts

The app.config.ts file in an angular application is used to configure the app to Angular Router.

## Use Angular Modules When: 

Building large-scale, enterprise-level applications.
Managing complex dependencies.
(Modules help encapsulate and manage related services, components, and pipes)
Using lazy-loaded feature modules.

## Use Standalone Components When: 

Developing small, focused applications or micro-frontends.
(Standalone components are ideal for apps with minimal setup or when using a micro-frontend architecture where individual parts are independently developed and deployed.)
Creating isolated components for libraries or testing.
(When building component libraries or writing unit tests, standalone components reduce boilerplate and improve isolation by removing the dependency on a module.)



