# Backoffice Taxi4fun

Modulo del front del proyecto https://github.com/taxy4fun en angular 5. Actualizado a 5.0 y material 5.rc0

El proyecto está preparado para desplegar en heroku mediante npm scripts (heroku-postbuild).

Tiene también dockerfile para generar las imágenes y desplegar. El docker arranca un express en el puerto indicado por variable de entorno env.PORT

[![Dependencies](https://david-dm.org/francisco-navarro/front-taxi4fun/status.svg)](https://david-dm.org/francisco-navarro/front-taxi4fun/)


### Branches CI

**master**



[![CircleCI](https://circleci.com/gh/francisco-navarro/front-taxi4fun.svg?style=shield)](https://circleci.com/gh/francisco-navarro/front-taxi4fun)
[![Maintainability](https://api.codeclimate.com/v1/badges/f56bac70c9d6c5888bec/maintainability)](https://codeclimate.com/github/francisco-navarro/front-taxi4fun/maintainability)
[![Test Coverage](https://codeclimate.com/github/francisco-navarro/front-taxi4fun/badges/coverage.svg)](https://codeclimate.com/github/francisco-navarro/front-taxi4fun/coverage)


Despliegue de prueba en : https://backoffice-4yf-develop.herokuapp.com/


## Development server

`npm run api` para levantar el api mock con dyson

`npm run develop` para arrancar servidor en `http://localhost:4200/`

## Build

`ng build` construir en `dist/`

## Running tests

Tests unitarios

`ng test`

Tests e2e con selenium y protractor

`ng e2e`


## Para desplegar en producción se ejecuta
El paso previo ejecuta `ng build --aot -prod` 
El despliegue ejecuta `node server.js` que arranca un node.
