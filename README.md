# npmtest-strict-rate-limiter

#### basic test coverage for  [strict-rate-limiter (v0.2.0)](https://github.com/getc/strict-rate-limiter)  [![npm package](https://img.shields.io/npm/v/npmtest-strict-rate-limiter.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-strict-rate-limiter) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-strict-rate-limiter.svg)](https://travis-ci.org/npmtest/node-npmtest-strict-rate-limiter)

#### Rate limiter backed by redis with strict concurrency rules for scalable applications

[![NPM](https://nodei.co/npm/strict-rate-limiter.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/strict-rate-limiter)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-strict-rate-limiter/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-strict-rate-limiter/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-strict-rate-limiter/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-strict-rate-limiter/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/test-report.html](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-strict-rate-limiter/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-strict-rate-limiter/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-strict-rate-limiter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-strict-rate-limiter/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-strict-rate-limiter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Regeci"
    },
    "bugs": {
        "url": "https://github.com/ovx/strict-rate-limiter/issues"
    },
    "dependencies": {
        "q": "^1.0.1"
    },
    "description": "Rate limiter backed by redis with strict concurrency rules for scalable applications",
    "devDependencies": {
        "ioredis": "^1.15.1",
        "jasmine-node": "^1.14.5",
        "jshint": "^2.5.10"
    },
    "directories": {},
    "dist": {
        "shasum": "afdaf06c0c3212b4d4f0efa41c0fac62033b9618",
        "tarball": "https://registry.npmjs.org/strict-rate-limiter/-/strict-rate-limiter-0.2.0.tgz"
    },
    "gitHead": "84b0a4fc394b4d0c0f788e0a3ff46e69282dd8e3",
    "homepage": "https://github.com/getc/strict-rate-limiter",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "getc"
        }
    ],
    "name": "strict-rate-limiter",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ovx/strict-rate-limiter.git"
    },
    "scripts": {
        "test": "jshint && jasmine-node spec --verbose --captureExceptions --forceexit"
    },
    "version": "0.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
