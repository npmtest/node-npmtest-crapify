# npmtest-crapify

#### test coverage for  [crapify (v1.2.0)](https://github.com/bcoe/crapify)  [![npm package](https://img.shields.io/npm/v/npmtest-crapify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-crapify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-crapify.svg)](https://travis-ci.org/npmtest/node-npmtest-crapify)

#### a proxy for simulating slow, spotty, HTTP connections

[![NPM](https://nodei.co/npm/crapify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/crapify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-crapify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-crapify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-crapify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-crapify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-crapify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-crapify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-crapify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-crapify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-crapify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-crapify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-crapify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-crapify/build/test-report.html](https://npmtest.github.io/node-npmtest-crapify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-crapify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-crapify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-crapify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-crapify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-crapify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-crapify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-crapify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-crapify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Coe"
    },
    "bin": {
        "crapify": "./bin/crapify.js"
    },
    "dependencies": {
        "chalk": "^0.5.1",
        "lodash": "^2.4.1",
        "monkey-proxy": "^1.2.0",
        "throttle": "^1.0.3",
        "yargs": "^1.3.3"
    },
    "description": "a proxy for simulating slow, spotty, HTTP connections",
    "devDependencies": {
        "async": "^0.9.0",
        "code": "^1.2.1",
        "lab": "^5.1.1",
        "nock": "^0.53.0",
        "request": "^2.51.0"
    },
    "directories": {},
    "dist": {
        "shasum": "92f1e884920a508900f6374b5c3a661a896b8cbb",
        "tarball": "https://registry.npmjs.org/crapify/-/crapify-1.2.0.tgz"
    },
    "git": {
        "url": "git://github.com/bcoe/crapify.git"
    },
    "gitHead": "cd5917c7d58770419fa351770ae5b454e30facd8",
    "homepage": "https://github.com/bcoe/crapify",
    "keywords": [
        "proxy",
        "slow",
        "connection-limit"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bcoe"
        }
    ],
    "name": "crapify",
    "optionalDependencies": {},
    "preferGlobal": true,
    "scripts": {
        "test": "lab -v -c --timeout 5000"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
