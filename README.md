# npmtest-how2

#### test coverage for  [how2 (v1.5.0)](https://github.com/santinic/how2)  [![npm package](https://img.shields.io/npm/v/npmtest-how2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-how2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-how2.svg)](https://travis-ci.org/npmtest/node-npmtest-how2)

#### Uses Google and Stackoverflow to find how to do things on a Unix commmand line

[![NPM](https://nodei.co/npm/how2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/how2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-how2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-how2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-how2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-how2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-how2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-how2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-how2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-how2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-how2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-how2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-how2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-how2/build/test-report.html](https://npmtest.github.io/node-npmtest-how2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-how2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-how2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-how2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-how2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-how2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-how2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-how2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-how2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Claudio Santini",
        "url": "https://www.linkedin.com/in/santinic"
    },
    "bin": {
        "how2": "./bin/how2"
    },
    "bugs": {
        "url": "https://github.com/santinic/how2/issues"
    },
    "dependencies": {
        "blessed": "^0.1.81",
        "colors": "^1.1.2",
        "devnull": "0.0.12",
        "ent": "^2.2.0",
        "google": "^1.4.0",
        "keypress": "^0.2.1",
        "lodash": "^4.3.0",
        "marked": "0.3.5",
        "marked-terminal": "^1.6.1",
        "nconf": "^0.8.4",
        "npm-latest": "^1.0.1",
        "openurl": "^1.1.1",
        "request": "^2.69.0",
        "semver": "5.1.0",
        "simple-spinner": "0.0.5",
        "yargs": "^4.1.0"
    },
    "description": "Uses Google and Stackoverflow to find how to do things on a Unix commmand line",
    "devDependencies": {
        "chai": "^3.5.0",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "bb885707e732dd6b5e622a159584fc1b89acdcd4",
        "tarball": "https://registry.npmjs.org/how2/-/how2-1.5.0.tgz"
    },
    "gitHead": "88d9e1d697794f3d27ff834de702572c60c27686",
    "homepage": "https://github.com/santinic/how2",
    "keywords": [
        "how2",
        "howto",
        "man",
        "google",
        "stackoverflow",
        "stack overflow",
        "stackexchange",
        "stack exchange"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "santinic"
        }
    ],
    "name": "how2",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/santinic/how2.git"
    },
    "scripts": {
        "start": "./bin/how2 concatenate two files",
        "test": "mocha test"
    },
    "tags": [
        "how2",
        "howto",
        "man",
        "google",
        "stackoverflow",
        "stack overflow",
        "stackexchange",
        "stack exchange"
    ],
    "version": "1.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
