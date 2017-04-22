# npmtest-gulp-chug

#### basic test coverage for  [gulp-chug (v0.5.1)](https://github.com/robatron/gulp-chug#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-chug.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-chug) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-chug.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-chug)

#### Run external gulpfiles as part of a gulp task inside another gulpfile

[![NPM](https://nodei.co/npm/gulp-chug.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-chug)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-chug/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-chug/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-chug/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-chug/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-chug/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-chug/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-chug/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-chug/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-chug/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-chug/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-chug/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-chug/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-chug/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-chug/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-chug/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-chug/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-chug/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-chug/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-chug/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-chug/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-chug/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rob McGuire-Dale"
    },
    "bugs": {
        "url": "https://github.com/robatron/gulp-chug/issues"
    },
    "contributors": [
        {
            "name": "Derek Peterson"
        },
        {
            "name": "Harry Wolff"
        },
        {
            "name": "Evgenus"
        },
        {
            "name": "Mike O'Brien"
        },
        {
            "name": "Phillip Green II"
        }
    ],
    "dependencies": {
        "gulp-util": "^3.0.7",
        "lodash": "^4.0.0",
        "resolve": "^1.1.6",
        "through2": "^2.0.0"
    },
    "description": "Run external gulpfiles as part of a gulp task inside another gulpfile",
    "devDependencies": {
        "gulp": "^3.9.0",
        "gulp-istanbul": "^0.10.3",
        "gulp-mocha": "^2.2.0",
        "gulp-replace": "^0.5.4",
        "gulp-util": "^3.0.7",
        "mocha": "^2.3.4",
        "proxyquire": "^1.7.3",
        "should": "^8.1.1",
        "sinon": "^1.17.2"
    },
    "directories": {},
    "dist": {
        "shasum": "b1918881b2bb52fd47e3cb2371587fca4c45e5c6",
        "tarball": "https://registry.npmjs.org/gulp-chug/-/gulp-chug-0.5.1.tgz"
    },
    "gitHead": "1aac66255ba2d6133fddad68d7e317301bcd06ab",
    "homepage": "https://github.com/robatron/gulp-chug#readme",
    "keywords": [
        "gulpplugin",
        "hub",
        "nest",
        "inception",
        "cascade",
        "domino",
        "grunt-hub",
        "gulp-hub"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "robatron"
        }
    ],
    "name": "gulp-chug",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/robatron/gulp-chug.git"
    },
    "scripts": {
        "publish-patch": "npm version patch && git push origin master --tags && npm publish",
        "test": "gulp --gulpfile test/gulp-chug-integrate.js && gulp test"
    },
    "version": "0.5.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
