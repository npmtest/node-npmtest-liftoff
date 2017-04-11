# test coverage for  [liftoff (v2.3.0)](https://github.com/js-cli/js-liftoff)  [![npm package](https://img.shields.io/npm/v/npmtest-liftoff.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-liftoff) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-liftoff.svg)](https://travis-ci.org/npmtest/node-npmtest-liftoff)
#### Launch your command line tool with ease.

[![NPM](https://nodei.co/npm/liftoff.png?downloads=true)](https://www.npmjs.com/package/liftoff)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-liftoff/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-liftoff/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-liftoff/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-liftoff/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-liftoff/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-liftoff/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-liftoff/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-liftoff/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-liftoff/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-liftoff/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-liftoff%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-liftoff/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-liftoff/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-liftoff%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-liftoff/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-liftoff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-liftoff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tyler Kellen",
        "url": "http://goingslowly.com/"
    },
    "bugs": {
        "url": "https://github.com/js-cli/js-liftoff/issues"
    },
    "dependencies": {
        "extend": "^3.0.0",
        "findup-sync": "^0.4.2",
        "fined": "^1.0.1",
        "flagged-respawn": "^0.3.2",
        "lodash.isplainobject": "^4.0.4",
        "lodash.isstring": "^4.0.1",
        "lodash.mapvalues": "^4.4.0",
        "rechoir": "^0.6.2",
        "resolve": "^1.1.7"
    },
    "description": "Launch your command line tool with ease.",
    "devDependencies": {
        "chai": "^3.5.0",
        "coffee-script": "^1.10.0",
        "istanbul": "^0.4.3",
        "jscs": "^2.11.0",
        "jshint": "^2.9.2",
        "mocha": "^2.4.5",
        "sinon": "~1.17.4"
    },
    "directories": {},
    "dist": {
        "shasum": "a98f2ff67183d8ba7cfaca10548bd7ff0550b385",
        "tarball": "https://registry.npmjs.org/liftoff/-/liftoff-2.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "gitHead": "be40ec3a3fa5854b4ab496a97f3d5877bf747b0b",
    "homepage": "https://github.com/js-cli/js-liftoff",
    "keywords": [
        "command line"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonschlinkert",
            "email": "github@sellside.com"
        },
        {
            "name": "phated",
            "email": "blaine.bublitz@gmail.com"
        },
        {
            "name": "tkellen",
            "email": "tyler@sleekcode.net"
        },
        {
            "name": "tusbar",
            "email": "bertrand.marron@gmail.com"
        }
    ],
    "name": "liftoff",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/js-cli/js-liftoff.git"
    },
    "scripts": {
        "test": "jshint lib index.js && jscs lib index.js && mocha -t 5000 -b -R spec test/index"
    },
    "version": "2.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
