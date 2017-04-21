# npmtest-yargs-parser

#### basic test coverage for  yargs-parser (v5.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-yargs-parser.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-yargs-parser) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-yargs-parser.svg)](https://travis-ci.org/npmtest/node-npmtest-yargs-parser)

#### the mighty option parser used by yargs

[![NPM](https://nodei.co/npm/yargs-parser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yargs-parser)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-yargs-parser/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-yargs-parser/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-yargs-parser/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-yargs-parser/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-yargs-parser/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-yargs-parser/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-yargs-parser/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-yargs-parser/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-yargs-parser/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-yargs-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-yargs-parser/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-yargs-parser/build/test-report.html](https://npmtest.github.io/node-npmtest-yargs-parser/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-yargs-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-yargs-parser/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-yargs-parser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yargs-parser/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-yargs-parser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-yargs-parser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "yargs-parser",
    "version": "5.0.0",
    "description": "the mighty option parser used by yargs",
    "main": "index.js",
    "scripts": {
        "pretest": "standard",
        "test": "nyc mocha test/*.js",
        "coverage": "nyc report --reporter=text-lcov | coveralls",
        "release": "standard-version"
    },
    "repository": {
        "url": "git@github.com:yargs/yargs-parser.git"
    },
    "keywords": [
        "argument",
        "parser",
        "yargs",
        "command",
        "cli",
        "parsing",
        "option",
        "args",
        "argument"
    ],
    "author": "Ben Coe <ben@npmjs.com>",
    "license": "ISC",
    "devDependencies": {
        "chai": "^3.5.0",
        "coveralls": "^2.11.12",
        "mocha": "^3.0.1",
        "nyc": "^10.0.0",
        "standard": "^8.0.0",
        "standard-version": "^4.0.0"
    },
    "dependencies": {
        "camelcase": "^3.0.0"
    },
    "files": [
        "lib",
        "index.js"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
