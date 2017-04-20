# npmtest-sendgrid

#### basic test coverage for  [sendgrid (v5.0.0)](https://sendgrid.com)  [![npm package](https://img.shields.io/npm/v/npmtest-sendgrid.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sendgrid) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sendgrid.svg)](https://travis-ci.org/npmtest/node-npmtest-sendgrid)

#### Official SendGrid NodeJS library.

[![NPM](https://nodei.co/npm/sendgrid.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sendgrid)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sendgrid/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sendgrid/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sendgrid/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sendgrid/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sendgrid/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sendgrid/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sendgrid/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sendgrid/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sendgrid/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sendgrid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sendgrid/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sendgrid/build/test-report.html](https://npmtest.github.io/node-npmtest-sendgrid/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sendgrid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sendgrid/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sendgrid/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sendgrid/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sendgrid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sendgrid/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sendgrid/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sendgrid/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "SendGrid <dx@sendgrid.com> (sendgrid.com)",
    "contributors": [
        "Kyle Partridge <kyle.partridge@sendgrid.com>",
        "David Tomberlin <david.tomberlin@sendgrid.com>",
        "Swift <swift@sendgrid.com>",
        "Brandon West <brandon.west@sendgrid.com>",
        "Scott Motte <scott.motte@sendgrid.com>",
        "Robert Acosta <robert.acosta@sendgrid.com>",
        "Elmer Thomas <elmer.thomas@sendgrid.com>",
        "Adam Buczynski <me@adambuczynski.com>"
    ],
    "name": "sendgrid",
    "description": "Official SendGrid NodeJS library.",
    "version": "5.0.0",
    "homepage": "https://sendgrid.com",
    "repository": {
        "type": "git",
        "url": "git://github.com/sendgrid/sendgrid-nodejs.git"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "dependencies": {
        "async.ensureasync": "^0.5.2",
        "async.queue": "^0.5.2",
        "bottleneck": "^1.12.0",
        "debug": "^2.2.0",
        "lodash.chunk": "^4.2.0",
        "mailparser": "^0.6.1",
        "sendgrid-rest": "^2.3.0"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "eslint": "^3.1.0",
        "mocha": "^2.4.5",
        "mocha-sinon": "^1.1.5",
        "sinon": "^1.17.5",
        "sinon-chai": "^2.8.0",
        "typescript": "^2.0.0"
    },
    "scripts": {
        "lint": "eslint . --fix",
        "test": "mocha",
        "test:typescript": "tsc"
    },
    "typings": "index.d.ts",
    "tags": [
        "http",
        "rest",
        "api"
    ],
    "license": "MIT",
    "optionalDependencies": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
