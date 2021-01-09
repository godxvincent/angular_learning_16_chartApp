# ChartApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.3.

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


## What I learnt.

1. Instalaciones necesarias
2. Configuraciones
3. Gráfico de Barras
4. Gráfico de Donas
5. Gráfico de Radar




## **This project was created by godxvincent.**

![Godxvincent](DFFOO_Vincent_Valentine.png)

## ** Extra installations **
* npm install jquery 
* npm install popper.js --save 
* npm install bootstrap  
* npm install animate.css --save  https://animate.style/  ==> animate__animated animate__bounce
* npm install sweetalert2  https://sweetalert2.github.io/#download
* npm install swiper https://swiperjs.com/
* npm install --save ng2-charts

## ** Links de interés  ** 

* quicktype

https://quicktype.io/

* ng-starrating

https://www.npmjs.com/package/ng-starrating

* Eventos del dom disponibles

https://www.w3schools.com/jsref/dom_obj_event.asp

* chart.js

https://valor-software.com/ng2-charts/

## How to remove sensitve data

git filter-branch --force --index-filter "git rm --cached --ignore-unmatch src/app/services/movies.service.ts" --prune-empty --tag-name-filter cat -- --all