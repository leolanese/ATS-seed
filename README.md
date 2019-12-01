# This is an ATS-seed app, created from scratch using CLI & npm

■ Setup a default seed project or use CLI:

- Install nodeJS & npm (or simply verify you already have it):
```javascript
  node -v
  npm -v
```  
- Install the Angular CLI globally:
```javascript
  npm install -g @angular/cli
  ng -v
```
- Create a workspace and initial application:
```javascript
  ng new test-app
```
- Serve the application:
```javascript
  cd test-app
  ng serve --port 4500 --open
```
- Install Angular Material & Schematics:
```javascript
  npm install --save @angular/material @angular/cdk @angular/animations
  ng add @angular/material
  ng generate @angular/material:material-nav --name container
```

**EXTRAS**
- Include Prettier (this can be handle by the pipeline later on):
```javascript
  npm install --save-dev --save-exact prettier
```
- Include a Service with a Component already declared:
```javascript
  cd test-app/src/app
  mkdir service
  ng g s service
```  
- Include a reference to empty side defined boxes
- Include modular bootstrap 4
```javascript
  npm install bootstrap --save
  open angular.json
  "styles": [
    "src/styles.css",
    "node_modules/bootstrap/dist/css/bootstrap.min.css"
  ],
```
  LINK:
  https://getbootstrap.com/docs/4.0/components/alerts/
- Include fontawesome:
```javascript  
<div style="text-align:center">
  <fa-icon [icon]="faCoffee"></fa-icon>
</div>
```
  LINK:
  https://fontawesome.com/how-to-use/on-the-web/using-with/angular

---
# TestApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.3.

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

--

#### { 'Leo Lanese',
####   'Building Inspiring Responsive Reactive Solutions',
####   'London, UK' }

##### Portfolio<br>
<a href="http://www.leolanese.com" target="_blank">http://www.leolanese.com</a>

##### Twitter:<br>
<a href="http://twitter.com/LeoLaneseltd" target="_blank">twitter.com/LeoLaneseltd</a>

##### Questions / Suggestion / Recommendation ?<br>
<a href="mail:to">developer@leolanese.com</a>

#### GitHub bash profile:<br>
<a href="http://github.com/leolanese/bash_profile" target="_blank">github.com/leolanese/bash_profile</a>

##### DEV.to:<br>
<a href="http://www.dev.to/leolanese" target="_blank">www.dev.to/leolanese</a>

##### Blog:<br/>
<a href="http://www.leolanese.com/blog" target="_blank">leolanese.com/blog</a>

