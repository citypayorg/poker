# WebClient
<<<<<<< HEAD
=======

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.3.
npm i @angular/cli@7.1.3
-- D:\pokerSrc\poker\web-client>node -v
-- v14.15.1
-- Node 14는	4.14+   --> https://www.npmjs.com/package/node-sass
npm i node-sass@4.14.0

>>>>>>> f42d50fc1d0c017939ec54fa106c95bfc5b6f1ee
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
-----------------------------
▦▦▦    WebClient
-----------------------------
cd D:\pokerSrc\poker\web-client
-----------------------------
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.3.
npm i @angular/cli@7.1.3
-- D:\pokerSrc\poker\web-client>node -v
-- v14.15.1
-- Node 14는	4.14+   --> https://www.npmjs.com/package/node-sass
npm i node-sass@4.14.0

-------------------
D:\pokerSrc\poker\web-client\src\app\services\other\url.service.ts
--> url change
D:\pokerSrc\poker\game-service\bin\main\application.properties
D:\pokerSrc\poker\game-service\bin\test\application.properties
D:\pokerSrc\poker\game-service\src\main\resources\application.properties
D:\pokerSrc\poker\game-service\src\test\resources\application.properties
D:\pokerSrc\poker\user-service\bin\test\application.properties
D:\pokerSrc\poker\user-service\src\test\resources\application.properties

postgresql 및 관련 url 변경
D:\pokerSrc\poker\mobile-client\app\src\main\java\be\kdg\mobile_client\shared\UrlService.java
관련 ip 변경
----------------------------------------------------------
ng serve --host 0.0.0.0 --disableHostCheck true
----------------------------------------------------------
http://localhost:4200/
-----------------------------
▦▦▦    game-service
-----------------------------
cd D:\pokerSrc\poker\game-service
d:
gradlew.bat
-----------------------------
▦▦▦    user-service
-----------------------------
cd D:\pokerSrc\poker\user-service
d:
gradlew.bat
-----------------------------

----------------------------- posgres sql -----------------------------
CREATE USER poker PASSWORD 'pokerpoker' SUPERUSER;
CREATE DATABASE pokerDB OWNER poker;
----------------------------------------------------------
