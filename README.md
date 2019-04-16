# angular-connect-app

Complete angular app with Docker multi stage build to connect to OpenAPI providers like Google or ORCID

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.8., uses SCSS and deploy on nginx Docker.

## Build

```shell
docker build -t angular-connect-app .
```

## Run

```shell
docker run -it angular-connect-app
```

## Development server

```shell
npm install
ng serve
```

Navigate to [http://localhost:4200/](http://localhost:4200/). The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
