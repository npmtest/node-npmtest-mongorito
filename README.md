# npmtest-mongorito

#### basic test coverage for  [mongorito (v2.2.0)](https://github.com/vdemedes/mongorito#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mongorito.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mongorito) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mongorito.svg)](https://travis-ci.org/npmtest/node-npmtest-mongorito)

#### ES6 generator-based MongoDB ODM. It rocks.

[![NPM](https://nodei.co/npm/mongorito.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mongorito)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mongorito/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongorito/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mongorito/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mongorito/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mongorito/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-mongorito/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-mongorito/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mongorito/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mongorito/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mongorito/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mongorito/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mongorito/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mongorito/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mongorito/build/test-report.html](https://npmtest.github.io/node-npmtest-mongorito/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mongorito/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mongorito/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mongorito/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mongorito/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongorito/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongorito/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mongorito/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mongorito/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vadim Demedes"
    },
    "bugs": {
        "url": "https://github.com/vdemedes/mongorito/issues"
    },
    "dependencies": {
        "bluebird": "^3.3.1",
        "class-extend": "^0.1.2",
        "clone": "^1.0.2",
        "co": "^4.6.0",
        "get-value": "^2.0.3",
        "is-generator-fn": "^1.0.0",
        "is_js": "^0.7.4",
        "lodash.result": "^4.2.0",
        "mongodb": "^2.0.48",
        "object-assign": "^4.0.1",
        "pluralize": "^1.2.1",
        "set-value": "^0.2.0"
    },
    "description": "ES6 generator-based MongoDB ODM. It rocks.",
    "devDependencies": {
        "ava": "^0.12.0",
        "chance": "^0.8.0",
        "coveralls": "^2.11.4",
        "eslint-config-vdemedes": "^1.0.2",
        "nyc": "^5.0.0",
        "xo": "^0.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "5025c8febbd41f3b5c0903b7f52c16a9911b5df4",
        "tarball": "https://registry.npmjs.org/mongorito/-/mongorito-2.2.0.tgz"
    },
    "files": [
        "index.js",
        "util",
        "lib"
    ],
    "gitHead": "ce0d331eddde8162ca8281c9e70add27b31f7d87",
    "homepage": "https://github.com/vdemedes/mongorito#readme",
    "keywords": [
        "mongo",
        "mongodb",
        "co-mongo",
        "co-mongodb",
        "orm",
        "odm",
        "es6"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "vdemedes"
        }
    ],
    "name": "mongorito",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vdemedes/mongorito.git"
    },
    "scripts": {
        "coveralls": "nyc report --reporter=text-lcov | coveralls",
        "test": "xo && nyc ava --serial"
    },
    "version": "2.2.0",
    "xo": {
        "extends": "vdemedes",
        "esnext": true,
        "env": [
            "node",
            "mocha"
        ],
        "ignore": [
            "examples/*.js"
        ],
        "rules": {
            "prefer-arrow-callback": 0,
            "prefer-spread": 0,
            "no-use-extend-native/no-use-extend-native": 0
        }
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
