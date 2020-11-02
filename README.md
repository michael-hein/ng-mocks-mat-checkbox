# Instructions

To reproduce the issue, run `ng test`.

You should receive the following error:
```bash
TypeError:: Cannot read property 'subscribe' of undefined
            at http://localhost:9876/_karma_webpack_/node_modules/@angular/cdk/__ivy_ngcc__/fesm2015/observers.js:151:58
            at ZoneDelegate.invoke (http://localhost:9876/_karma_webpack_/node_modules/zone.js/dist/zone-evergreen.js:364:1)
            at ProxyZoneSpec.push.QpwO.ProxyZoneSpec.onInvoke (http://localhost:9876/_karma_webpack_/node_modules/zone.js/dist/zone-testing.js:292:1)
            at ZoneDelegate.invoke (http://localhost:9876/_karma_webpack_/node_modules/zone.js/dist/zone-evergreen.js:363:1)
            at Zone.run (http://localhost:9876/_karma_webpack_/node_modules/zone.js/dist/zone-evergreen.js:123:1)
            at NgZone.runOutsideAngular (http://localhost:9876/_karma_webpack_/node_modules/@angular/core/__ivy_ngcc__/fesm2015/core.js:27422:1)
            at CdkObserveContent._subscribe (http://localhost:9876/_karma_webpack_/node_modules/@angular/cdk/__ivy_ngcc__/fesm2015/observers.js:149:1)
            at CdkObserveContent.ngAfterContentInit (http://localhost:9876/_karma_webpack_/node_modules/@angular/cdk/__ivy_ngcc__/fesm2015/observers.js:136:1)
            at callHook (http://localhost:9876/_karma_webpack_/node_modules/@angular/core/__ivy_ngcc__/fesm2015/core.js:3281:1)
            at callHooks (http://localhost:9876/_karma_webpack_/node_modules/@angular/core/__ivy_ngcc__/fesm2015/core.js:3251:1)
```

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
