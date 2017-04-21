# npmtest-generator-webapp-php

#### basic test coverage for  [generator-webapp-php (v0.3.0)](https://github.com/amercier/generator-webapp-php)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-webapp-php.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-webapp-php) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-webapp-php.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-webapp-php)

#### Scaffold out a front-end web app with a PHP back-end

[![NPM](https://nodei.co/npm/generator-webapp-php.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-webapp-php)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-webapp-php/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-webapp-php/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-webapp-php/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-webapp-php/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-webapp-php/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-webapp-php/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-webapp-php/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-webapp-php/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-webapp-php/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-webapp-php/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-webapp-php/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-webapp-php/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-webapp-php/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-webapp-php/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-webapp-php/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-webapp-php/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-webapp-php/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-webapp-php/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-webapp-php/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-webapp-php/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-webapp-php/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "generator-webapp-php",
    "version": "0.3.0",
    "description": "Scaffold out a front-end web app with a PHP back-end",
    "keywords": [
        "yeoman-generator",
        "web",
        "app",
        "front-end",
        "h5bp",
        "modernizr",
        "php"
    ],
    "homepage": "https://github.com/amercier/generator-webapp-php",
    "bugs": "https://github.com/amercier/generator-webapp-php/issues",
    "author": "Alexandre Mercier",
    "main": "app/index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/amercier/generator-webapp-php.git"
    },
    "scripts": {
        "test": "mocha --reporter spec"
    },
    "dependencies": {
        "yeoman-generator": "~0.14.0",
        "cheerio": "~0.12.1"
    },
    "peerDependencies": {
        "yo": ">=1.0.0-rc.1.1",
        "generator-mocha": "~0.1.1"
    },
    "devDependencies": {
        "mocha": "~1.12.0"
    },
    "engines": {
        "node": ">=0.8.0",
        "npm": ">=1.2.10"
    },
    "licenses": [
        {
            "type": "MIT"
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
