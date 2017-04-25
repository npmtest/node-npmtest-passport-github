# npmtest-passport-github

#### basic test coverage for  [passport-github (v1.1.0)](https://github.com/jaredhanson/passport-github#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-passport-github.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-passport-github) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-passport-github.svg)](https://travis-ci.org/npmtest/node-npmtest-passport-github)

#### GitHub authentication strategy for Passport.

[![NPM](https://nodei.co/npm/passport-github.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-github)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-passport-github/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-github/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-passport-github/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-passport-github/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-passport-github/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-passport-github/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-passport-github/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-passport-github/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-passport-github/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-passport-github/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-passport-github/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-github/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-passport-github/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-passport-github/build/test-report.html](https://npmtest.github.io/node-npmtest-passport-github/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-passport-github/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-passport-github/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-passport-github/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-github/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-github/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-github/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-passport-github/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-passport-github/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jared Hanson",
        "url": "http://www.jaredhanson.net/"
    },
    "bugs": {
        "url": "http://github.com/jaredhanson/passport-github/issues"
    },
    "dependencies": {
        "passport-oauth2": "1.x.x"
    },
    "description": "GitHub authentication strategy for Passport.",
    "devDependencies": {
        "chai": "2.x.x",
        "chai-passport-strategy": "1.x.x",
        "make-node": "0.3.x",
        "mocha": "1.x.x",
        "proxyquire": "1.4.x"
    },
    "directories": {},
    "dist": {
        "shasum": "8ce1e3fcd61ad7578eb1df595839e4aea12355d4",
        "tarball": "https://registry.npmjs.org/passport-github/-/passport-github-1.1.0.tgz"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "gitHead": "c10321591d0521a2235613830562c2e8e2195c16",
    "homepage": "https://github.com/jaredhanson/passport-github#readme",
    "keywords": [
        "passport",
        "github",
        "auth",
        "authn",
        "authentication",
        "identity"
    ],
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://opensource.org/licenses/MIT"
        }
    ],
    "main": "./lib",
    "maintainers": [
        {
            "name": "jaredhanson"
        }
    ],
    "name": "passport-github",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/jaredhanson/passport-github.git"
    },
    "scripts": {
        "test": "mocha --require test/bootstrap/node test/*.test.js"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
