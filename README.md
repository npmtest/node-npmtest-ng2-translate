# npmtest-ng2-translate

#### test coverage for  [ng2-translate (v5.0.0)](https://github.com/ocombe/ng2-translate)  [![npm package](https://img.shields.io/npm/v/npmtest-ng2-translate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ng2-translate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ng2-translate.svg)](https://travis-ci.org/npmtest/node-npmtest-ng2-translate)

#### An implementation of angular translate for Angular 2

[![NPM](https://nodei.co/npm/ng2-translate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ng2-translate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ng2-translate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng2-translate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ng2-translate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ng2-translate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ng2-translate/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ng2-translate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ng2-translate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ng2-translate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ng2-translate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ng2-translate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ng2-translate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ng2-translate/build/test-report.html](https://npmtest.github.io/node-npmtest-ng2-translate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ng2-translate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ng2-translate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ng2-translate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ng2-translate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ng2-translate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ng2-translate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ng2-translate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ng2-translate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Olivier Combe"
    },
    "bugs": {
        "url": "https://github.com/ocombe/ng2-translate/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {},
    "description": "An implementation of angular translate for Angular 2",
    "devDependencies": {
        "@angular/common": "2.3.1",
        "@angular/compiler": "2.3.1",
        "@angular/compiler-cli": "2.3.1",
        "@angular/core": "2.3.1",
        "@angular/http": "2.3.1",
        "@angular/platform-browser": "2.3.1",
        "@angular/platform-browser-dynamic": "2.3.1",
        "@angular/platform-server": "2.3.1",
        "@types/hammerjs": "2.0.33",
        "@types/jasmine": "2.5.38",
        "@types/node": "6.0.52",
        "awesome-typescript-loader": "3.0.0-beta.17",
        "codelyzer": "2.0.0-beta.3",
        "commitizen": "2.9.2",
        "core-js": "2.4.1",
        "cz-conventional-changelog": "1.2.0",
        "istanbul-instrumenter-loader": "0.2.0",
        "jasmine-core": "2.5.2",
        "karma": "1.3.0",
        "karma-chrome-launcher": "2.0.0",
        "karma-coverage": "1.1.1",
        "karma-jasmine": "1.0.2",
        "karma-mocha-reporter": "^2.1.0",
        "karma-remap-coverage": "0.1.2",
        "karma-sourcemap-loader": "0.3.7",
        "karma-webpack": "1.8.0",
        "loader-utils": "0.2.16",
        "reflect-metadata": "0.1.8",
        "rxjs": "5.0.0-rc.4",
        "semantic-release": "6.3.2",
        "source-map-loader": "0.1.5",
        "ts-helpers": "1.1.2",
        "tslint": "4.0.2",
        "tslint-loader": "3.3.0",
        "typescript": "2.0.10",
        "webpack": "2.1.0-beta.27",
        "zone.js": "0.7.2"
    },
    "directories": {},
    "dist": {
        "shasum": "0adbb510eb5007a2d6ded5f5d26888c14760aca5",
        "tarball": "https://registry.npmjs.org/ng2-translate/-/ng2-translate-5.0.0.tgz"
    },
    "gitHead": "38ab093d8c53620e734b01a2ec41df3bb355ea66",
    "homepage": "https://github.com/ocombe/ng2-translate",
    "keywords": [
        "angular",
        "angular2",
        "translate",
        "i18n"
    ],
    "license": "MIT",
    "main": "bundles/ng2-translate.umd.js",
    "maintainers": [
        {
            "name": "ocombe"
        }
    ],
    "module": "index.js",
    "name": "ng2-translate",
    "optionalDependencies": {},
    "peerDependencies": {
        "@angular/core": "^2.0.0",
        "@angular/http": "^2.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ocombe/ng2-translate.git"
    },
    "scripts": {
        "build": "webpack && cp bundles/ng2-translate.umd.js bundles/index.js",
        "commit": "npm run prepublish && npm test && git-cz",
        "prepublish": "ngc && npm run build",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "test": "karma start",
        "test-watch": "karma start --singleRun=false --autoWatch=true"
    },
    "typings": "index.d.ts",
    "version": "5.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
