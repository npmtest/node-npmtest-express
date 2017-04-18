# npmtest-express

#### test coverage for  [express (v4.15.2)](http://expressjs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-express.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express.svg)](https://travis-ci.org/npmtest/node-npmtest-express)

#### Fast, unopinionated, minimalist web framework

[![NPM](https://nodei.co/npm/express.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express/build/test-report.html](https://npmtest.github.io/node-npmtest-express/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk"
    },
    "bugs": {
        "url": "https://github.com/expressjs/express/issues"
    },
    "contributors": [
        {
            "name": "Aaron Heckmann"
        },
        {
            "name": "Ciaran Jessup"
        },
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Guillermo Rauch"
        },
        {
            "name": "Jonathan Ong"
        },
        {
            "name": "Roman Shtylman"
        },
        {
            "name": "Young Jae Sim"
        }
    ],
    "dependencies": {
        "accepts": "~1.3.3",
        "array-flatten": "1.1.1",
        "content-disposition": "0.5.2",
        "content-type": "~1.0.2",
        "cookie": "0.3.1",
        "cookie-signature": "1.0.6",
        "debug": "2.6.1",
        "depd": "~1.1.0",
        "encodeurl": "~1.0.1",
        "escape-html": "~1.0.3",
        "etag": "~1.8.0",
        "finalhandler": "~1.0.0",
        "fresh": "0.5.0",
        "merge-descriptors": "1.0.1",
        "methods": "~1.1.2",
        "on-finished": "~2.3.0",
        "parseurl": "~1.3.1",
        "path-to-regexp": "0.1.7",
        "proxy-addr": "~1.1.3",
        "qs": "6.4.0",
        "range-parser": "~1.2.0",
        "send": "0.15.1",
        "serve-static": "1.12.1",
        "setprototypeof": "1.0.3",
        "statuses": "~1.3.1",
        "type-is": "~1.6.14",
        "utils-merge": "1.0.0",
        "vary": "~1.1.0"
    },
    "description": "Fast, unopinionated, minimalist web framework",
    "devDependencies": {
        "after": "0.8.2",
        "body-parser": "1.17.1",
        "connect-redis": "~2.4.1",
        "cookie-parser": "~1.4.3",
        "cookie-session": "~1.2.0",
        "ejs": "2.5.6",
        "express-session": "1.15.1",
        "istanbul": "0.4.5",
        "jade": "~1.11.0",
        "marked": "0.3.6",
        "method-override": "2.3.7",
        "mocha": "3.2.0",
        "morgan": "1.8.1",
        "multiparty": "4.1.3",
        "pbkdf2-password": "1.2.1",
        "should": "11.2.0",
        "supertest": "1.2.0",
        "vhost": "~3.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "af107fc148504457f2dca9a6f2571d7129b97b35",
        "tarball": "https://registry.npmjs.org/express/-/express-4.15.2.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "LICENSE",
        "History.md",
        "Readme.md",
        "index.js",
        "lib/"
    ],
    "gitHead": "d43b074f0b3b56a91f240e62798c932ba104b79a",
    "homepage": "http://expressjs.com/",
    "keywords": [
        "express",
        "framework",
        "sinatra",
        "web",
        "rest",
        "restful",
        "router",
        "app",
        "api"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "hacksparrow"
        },
        {
            "name": "jasnell"
        },
        {
            "name": "mikeal"
        }
    ],
    "name": "express",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/express.git"
    },
    "scripts": {
        "test": "mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --require test/support/env --reporter spec --check-leaks test/ test/acceptance/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --require test/support/env --reporter dot --check-leaks test/ test/acceptance/",
        "test-tap": "mocha --require test/support/env --reporter tap --check-leaks test/ test/acceptance/"
    },
    "version": "4.15.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
