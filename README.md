# npmtest-jison

#### basic test coverage for  [jison (v0.4.17)](http://jison.org)  [![npm package](https://img.shields.io/npm/v/npmtest-jison.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jison) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jison.svg)](https://travis-ci.org/npmtest/node-npmtest-jison)

#### A parser generator with Bison's API

[![NPM](https://nodei.co/npm/jison.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jison)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jison/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jison/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jison/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jison/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jison/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jison/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jison/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jison/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jison/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jison/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jison/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jison/build/test-report.html](https://npmtest.github.io/node-npmtest-jison/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jison/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jison/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jison/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jison/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jison/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jison/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jison/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jison/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Zach Carter <zach@carter.name> (http://zaa.ch)",
    "name": "jison",
    "description": "A parser generator with Bison's API",
    "version": "0.4.17",
    "license": "MIT",
    "keywords": [
        "jison",
        "bison",
        "yacc",
        "parser",
        "generator",
        "lexer",
        "flex",
        "tokenizer",
        "compiler"
    ],
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/zaach/jison.git"
    },
    "bugs": {
        "url": "http://github.com/zaach/jison/issues"
    },
    "main": "lib/jison",
    "bin": "lib/cli.js",
    "engines": {
        "node": ">=0.4"
    },
    "dependencies": {
        "JSONSelect": "0.4.0",
        "esprima": "1.1.x",
        "escodegen": "1.3.x",
        "jison-lex": "0.3.x",
        "ebnf-parser": "0.1.10",
        "lex-parser": "~0.1.3",
        "nomnom": "1.5.2",
        "cjson": "0.3.0"
    },
    "devDependencies": {
        "test": "0.6.x",
        "jison": "0.4.x",
        "uglify-js": "~2.4.0",
        "browserify": "2.x.x"
    },
    "scripts": {
        "test": "node tests/all-tests.js"
    },
    "homepage": "http://jison.org"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
