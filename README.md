# npmtest-webpagetest

#### basic test coverage for  [webpagetest (v0.3.4)](http://github.com/marcelduran/webpagetest-api)  [![npm package](https://img.shields.io/npm/v/npmtest-webpagetest.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webpagetest) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webpagetest.svg)](https://travis-ci.org/npmtest/node-npmtest-webpagetest)

#### WebPageTest API wrapper for NodeJS

[![NPM](https://nodei.co/npm/webpagetest.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webpagetest)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webpagetest/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpagetest/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webpagetest/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webpagetest/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webpagetest/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webpagetest/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webpagetest/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webpagetest/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webpagetest/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpagetest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webpagetest/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webpagetest/build/test-report.html](https://npmtest.github.io/node-npmtest-webpagetest/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webpagetest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webpagetest/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webpagetest/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webpagetest/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpagetest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpagetest/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webpagetest/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webpagetest/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marcel Duran",
        "url": "http://github.com/marcelduran"
    },
    "bin": {
        "webpagetest": "bin/webpagetest"
    },
    "bugs": {
        "url": "http://github.com/marcelduran/webpagetest-api/issues"
    },
    "dependencies": {
        "commander": "^2.7.1",
        "csv": "^0.4.1",
        "entities": "^1.1.1",
        "mocha": "^2.2.4",
        "xml2js": "^0.4.6"
    },
    "description": "WebPageTest API wrapper for NodeJS",
    "devDependencies": {
        "nock": "~1.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "af0d74c5d44bbc0456601d02e0a4bcd4785b1182",
        "tarball": "https://registry.npmjs.org/webpagetest/-/webpagetest-0.3.4.tgz"
    },
    "engines": {
        "node": ">=0.10.1"
    },
    "gitHead": "55dff8e5c690e4e6e1e5ed5c6a1312340eb280d2",
    "homepage": "http://github.com/marcelduran/webpagetest-api",
    "keywords": [
        "webpagetest",
        "api",
        "performance",
        "test",
        "browser"
    ],
    "license": "MIT",
    "main": "lib/webpagetest.js",
    "maintainers": [
        {
            "name": "marcelduran"
        }
    ],
    "name": "webpagetest",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/marcelduran/webpagetest-api.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha -R spec test/*-test.js"
    },
    "version": "0.3.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
