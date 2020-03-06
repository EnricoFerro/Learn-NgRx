# Learn NgRx

This is a small tutorial that describe how to use NgRx using the [Deck of Cards API](https://deckofcardsapi.com/)

## Introduction

The reactive state is a good form of managment of data inside programming. 
NgRx introduce this framework, popular in React with the logic React+Flux in Angular.

## Prerequisites for this project

Prerequisites for this is to know:

* [Angular](https://angular.io)
* [RxJs](https://rxjs.dev/)

It better to have some knowledge of state theory

## Getting Started

Create the project:
```
ng new learn-ngrx
```

## Install the dependencies

```
npm i --save @ngrx/store @ngrx/effects @ngrx/store-devtools @ngrx/schematics 
```

* Run the following at the root of the project to change the CLI to use the NgRx Schematics.

```
ng config cli.defaultCollection @ngrx/schematics
```



## Reference

* [NgRx](https://ngrx.io/)
* [Angular: NGRX a clean and clear introduction
](https://levelup.gitconnected.com/angular-ngrx-a-clean-and-clear-introduction-4ed61c89c1fc)
* [How to Start Flying with Angular and NgRx](https://medium.com/angular-in-depth/how-to-start-flying-with-angular-and-ngrx-b18e84d444aa)
* [Chrome Extension Redux DevTools
](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en)
