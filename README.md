# DashboardAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

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

## Husky

When doing javascript development it is common to have linting and test tasks in your package.json file.
It is easy to forget to run these common tasks before pushing code and this can result in a broken build (if using continues integration) or the next developer will see the issues when pulling down the latest code.
A way to work around this problem is to use git hooks that will allow you to hook into the git workflow to run tasks. Git hooks are not easy to share across a development team as git hooks are located in the .git/hooks folder.
Luckily a npm package called [Husky](https://github.com/typicode/husky) can help solve this issue. Husky describes itself as “Git hooks made easy”. After using it I must agree that it does indeed do just that!
Husky provide "precommit" and "prepush" in script package.json where we can run command before commiting or pushing.

## CommitLint

[Commitlint](https://github.com/marionebl/commitlint) is template for our commit message subject(scope): message... description.
