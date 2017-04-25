# npmtest-run-parallel

#### basic test coverage for  [run-parallel (v1.1.6)](https://github.com/feross/run-parallel)  [![npm package](https://img.shields.io/npm/v/npmtest-run-parallel.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-run-parallel) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-run-parallel.svg)](https://travis-ci.org/npmtest/node-npmtest-run-parallel)

#### Run an array of functions in parallel

[![NPM](https://nodei.co/npm/run-parallel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/run-parallel)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-run-parallel/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-run-parallel/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-run-parallel/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-run-parallel/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-run-parallel/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-run-parallel/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-run-parallel/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-run-parallel/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-run-parallel/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-run-parallel/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-run-parallel/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-run-parallel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-run-parallel/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-run-parallel/build/test-report.html](https://npmtest.github.io/node-npmtest-run-parallel/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-run-parallel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-run-parallel/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-run-parallel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-run-parallel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-run-parallel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-run-parallel/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-run-parallel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-run-parallel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Feross Aboukhadijeh",
        "url": "http://feross.org/"
    },
    "bugs": {
        "url": "https://github.com/feross/run-parallel/issues"
    },
    "dependencies": {},
    "description": "Run an array of functions in parallel",
    "devDependencies": {
        "standard": "^6.0.5",
        "tape": "^4.0.0",
        "zuul": "^3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "29003c9a2163e01e2d2dfc90575f2c6c1d61a039",
        "tarball": "https://registry.npmjs.org/run-parallel/-/run-parallel-1.1.6.tgz"
    },
    "gitHead": "f9ee5e836569ec13712889a208a0a730069e22af",
    "homepage": "https://github.com/feross/run-parallel",
    "keywords": [
        "parallel",
        "async",
        "function",
        "callback",
        "asynchronous",
        "run",
        "array",
        "run parallel"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "feross"
        }
    ],
    "name": "run-parallel",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/feross/run-parallel.git"
    },
    "scripts": {
        "test": "standard && npm run test-node && npm run test-browser",
        "test-browser": "zuul -- test/*.js",
        "test-browser-local": "zuul --local -- test/*.js",
        "test-node": "tape test/*.js"
    },
    "version": "1.1.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
