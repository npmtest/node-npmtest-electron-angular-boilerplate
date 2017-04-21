# npmtest-electron-angular-boilerplate

#### basic test coverage for  [electron-angular-boilerplate (v1.5.0)](https://github.com/Stephn-R/Electron-Boilerplate)  [![npm package](https://img.shields.io/npm/v/npmtest-electron-angular-boilerplate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron-angular-boilerplate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron-angular-boilerplate.svg)](https://travis-ci.org/npmtest/node-npmtest-electron-angular-boilerplate)

#### A basic electron app using AngularJS and Skeleton CSS with ES6 support

[![NPM](https://nodei.co/npm/electron-angular-boilerplate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-angular-boilerplate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron-angular-boilerplate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron-angular-boilerplate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/test-report.html](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electron-angular-boilerplate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-angular-boilerplate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-angular-boilerplate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-angular-boilerplate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electron-angular-boilerplate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "electron-angular-boilerplate",
    "version": "1.5.0",
    "description": "A basic electron app using AngularJS and Skeleton CSS with ES6 support",
    "engines": {
        "node": "<0.12"
    },
    "main": "main.js",
    "scripts": {
        "start": "electron .",
        "postinstall": "bower install && jspm install",
        "debug": "node-inspector && electron --debug=5858 && ",
        "test": "jest --verbose && karma start",
        "test-angularjs": "karma start --auto-watch"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Stephn-R/Electron-Boilerplate.git"
    },
    "keywords": [
        "electron",
        "angular",
        "boilerplate",
        "desktop",
        "applications",
        "web"
    ],
    "author": "steprodriguez10@gmail.com",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Stephn-R/Electron-Boilerplate/issues"
    },
    "homepage": "https://github.com/Stephn-R/Electron-Boilerplate",
    "devDependencies": {
        "babel": "^5.6.14",
        "babel-jest": "^5.3.0",
        "del": "^1.2.0",
        "electron-packager": "^4.1.3",
        "gulp": "^3.9.0",
        "gulp-autoprefixer": "^2.3.1",
        "gulp-clean": "^0.3.1",
        "gulp-istanbul": "^0.10.0",
        "gulp-load-plugins": "^1.0.0-rc.1",
        "gulp-notify": "^2.2.0",
        "gulp-plumber": "^1.0.1",
        "gulp-rename": "^1.2.2",
        "gulp-sass": "^2.0.1",
        "gulp-sourcemaps": "^1.5.2",
        "gulp-util": "^3.0.5",
        "jest-cli": "^0.4.15",
        "karma": "^0.12.37",
        "karma-coverage": "^0.4.2",
        "karma-jasmine": "^0.3.6",
        "karma-mocha-reporter": "^1.0.2",
        "karma-phantomjs-launcher": "^0.2.0",
        "lodash": "^3.9.3",
        "phantomjs": "^1.9.17",
        "wiredep": "^2.2.2"
    },
    "dependencies": {
        "jquery": "^2.1.4"
    },
    "jspm": {
        "directories": {},
        "dependencies": {},
        "devDependencies": {
            "babel": "npm:babel-core@^5.1.13",
            "babel-runtime": "npm:babel-runtime@^5.1.13",
            "core-js": "npm:core-js@^0.9.4"
        }
    },
    "jest": {
        "collectCoverage": true,
        "scriptPreprocessor": "<rootDir>/node_modules/babel-jest",
        "testPathIgnorePatterns": [
            "__tests__/app/",
            "/node_modules/"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
