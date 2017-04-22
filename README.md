# npmtest-angular2-text-mask

#### basic test coverage for  [angular2-text-mask (v8.0.0)](https://github.com/text-mask/text-mask/tree/master/angular2/#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-angular2-text-mask.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angular2-text-mask) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angular2-text-mask.svg)](https://travis-ci.org/npmtest/node-npmtest-angular2-text-mask)

#### Angular 2 directive for input text masking

[![NPM](https://nodei.co/npm/angular2-text-mask.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angular2-text-mask)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angular2-text-mask/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-text-mask/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-text-mask/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angular2-text-mask/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angular2-text-mask/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angular2-text-mask/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angular2-text-mask/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-angular2-text-mask/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-angular2-text-mask/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular2-text-mask/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-angular2-text-mask/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-angular2-text-mask/build/test-report.html](https://npmtest.github.io/node-npmtest-angular2-text-mask/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-angular2-text-mask/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angular2-text-mask/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-angular2-text-mask/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-angular2-text-mask/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular2-text-mask/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular2-text-mask/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angular2-text-mask/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angular2-text-mask/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "angular2-text-mask",
    "version": "8.0.0",
    "description": "Angular 2 directive for input text masking",
    "main": "dist/angular2TextMask.js",
    "typings": "./dist/angular2TextMask.d.ts",
    "author": "M.K. Safi <msafi@msafi.com>",
    "license": "Unlicense",
    "bugs": {
        "url": "https://github.com/text-mask/text-mask/issues"
    },
    "scripts": {
        "start": "tsc -p example/tsconfig.json && concurrently \"tsc -w -p example/tsconfig.json\" lite-server ",
        "build": "./node_modules/.bin/ngc -p tsconfig.json && rm -rf aot",
        "test": "# ADD TESTS",
        "loud-lint": "node_modules/.bin/tslint -c tslint.json src/*.ts test/**/*.ts example/**/*.ts",
        "lint": "node_modules/.bin/tslint -c tslint.json src/*.ts test/**/*.ts example/**/*.ts || true",
        "ci": "npm run test && npm run loud-lint"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/text-mask/text-mask.git"
    },
    "homepage": "https://github.com/text-mask/text-mask/tree/master/angular2/#readme",
    "keywords": [
        "angular2",
        "ng2",
        "angular2 component",
        "angular2 directive",
        "text mask",
        "input mask",
        "string mask",
        "input formatting",
        "text formatting",
        "string formatting"
    ],
    "devDependencies": {
        "@angular/common": "^2.1.2",
        "@angular/compiler": "^2.1.2",
        "@angular/compiler-cli": "^2.1.2",
        "@angular/core": "^2.1.2",
        "@angular/forms": "^2.1.2",
        "@angular/http": "^2.1.2",
        "@angular/platform-browser": "^2.1.2",
        "@angular/platform-browser-dynamic": "^2.1.2",
        "@angular/platform-server": "^2.1.2",
        "@types/core-js": "^0.9.34",
        "@types/node": "^6.0.45",
        "awesome-typescript-loader": "^1.0.0",
        "concurrently": "^3.0.0",
        "core-js": "^2.4.1",
        "lite-server": "^2.2.2",
        "reflect-metadata": "^0.1.8",
        "rxjs": "^5.0.1",
        "systemjs": "0.19.39",
        "ts-node": "~1.2.0",
        "tslint": "^3.13.0",
        "typescript": "^2.0.6",
        "zone.js": "^0.7.2"
    },
    "dependencies": {
        "text-mask-core": "^5.0.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
