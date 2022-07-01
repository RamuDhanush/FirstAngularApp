# AngularProjectDemo

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.3.

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


## How to source code move to GitHub:

1. ng serve
2. git init
3. git add ./
4. git config user.name ""
5. git config user.email ""
6. git commit -m "first commit"
7. git branch -M main
8. git remote add origin https://github.com/RamuDhanush/FirstAngularApp.git
9. git push -u origin main


## Deploy the application in GitHub:

1. ng build --output-path docs --base-href /repository-name/
2. Once the build completes, we will find a new folder named docs and inside this folder found -> HTML file, a few JS files, and a few other files. This is the output of the build.
3. git add ./
4. git commit -m "Included docs folder and build files"
5. git branch -M main
6. git push -u origin main
7. Go to corresponding GitHub repository, switch to the Settings tab
8. Under "Code and automation", find "Pages" to configure the GitHub Pages in left side menus
9. Fill the Source section
10. Set main as the branch, choose /docs in the second dropdown, and click Save.
11. We have successfully hosted our Angular app in GitHub Pages
12. After a few minutes, reload the page. You will find that the message is changed from “Your site is ready to be published at…” to “Your site is published at…”
13. Browse the https://username.github.io/repositoryname


