# npmtest-plex-api

#### basic test coverage for  [plex-api (v5.1.0)](https://github.com/phillipj/node-plex-api#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-plex-api.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-plex-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-plex-api.svg)](https://travis-ci.org/npmtest/node-npmtest-plex-api)

#### Simple wrapper for querying against HTTP API on the Plex Media Server

[![NPM](https://nodei.co/npm/plex-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/plex-api)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-plex-api/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-plex-api/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-plex-api/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-plex-api/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-plex-api/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-plex-api/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-plex-api/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-plex-api/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-plex-api/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-plex-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-plex-api/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-plex-api/build/test-report.html](https://npmtest.github.io/node-npmtest-plex-api/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-plex-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-plex-api/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-plex-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-plex-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-plex-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-plex-api/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-plex-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-plex-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Phillip Johnsen"
    },
    "bugs": {
        "url": "https://github.com/phillipj/node-plex-api/issues"
    },
    "dependencies": {
        "plex-api-credentials": "^3.0.0",
        "plex-api-headers": "1.1.0",
        "request": "2.79.0",
        "uuid": "2.0.2",
        "xml2js": "0.4.16"
    },
    "description": "Simple wrapper for querying against HTTP API on the Plex Media Server",
    "devDependencies": {
        "expect.js": "^0.3.1",
        "mocha": "^2.5.0",
        "nock": "^8.0.0",
        "prettier": "1.1.0",
        "proxyquire": "^1.7.3",
        "sinon": "^1.17.2"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "a4c63314dc989ec9a4bf9f37ebb4547894e20f25",
        "tarball": "https://registry.npmjs.org/plex-api/-/plex-api-5.1.0.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "files": [
        "lib"
    ],
    "gitHead": "ac4236ccf51e1455ac18feb83b4f1641910d5eb3",
    "homepage": "https://github.com/phillipj/node-plex-api#readme",
    "keywords": [
        "plex",
        "api"
    ],
    "license": "MIT",
    "main": "lib/api.js",
    "maintainers": [
        {
            "name": "flipp"
        }
    ],
    "name": "plex-api",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/phillipj/node-plex-api.git"
    },
    "scripts": {
        "format": "npm run format:exec -- --write",
        "format:exec": "prettier --single-quote --print-width=120 --tab-width=4 '{lib,test}/**/*.js'",
        "test": "npm run test:lint && npm run test:unit",
        "test:lint": "npm run format:exec -- --list-different",
        "test:unit": "mocha test/*-test.js",
        "test:watch": "npm run test:unit -- -w"
    },
    "version": "5.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
