# Finansys

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.2.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


## Dependencias Finansys
ng new finansys

npm install bootstrap jquery --save
npm install angular-imask --save
npm install currency-formatter --save
npm install moment --save
npm install toastr --save
npm install primeng --save
npm install primeicons --save
npm install chart.js --save
npm install angular-in-memory-web-api --save

## Componentes Categoria Finansys
ng g m pages/categories --routing
ng g c pages/categories/category-list
ng g c pages/categories/category-form
ng g s pages/categories/shared/category

## Componentes Entries Finansys
ng g m pages/entries --routing


## Reestruturando Finansys
ng g m core
ng g m shared
ng g c shared/components/bread-crumb
ng g c shared/components/page-header
ng g c shared/components/form-field-error --inline-template
ng g c shared/components/server-error-messages
ng g c core/components/navebar

## Componentes Report Finansys
ng g m pages/reports --routing
ng g c pages/reports/reports


