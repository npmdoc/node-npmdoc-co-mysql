# npmdoc-co-mysql

#### basic api documentation for  [co-mysql (v1.0.0)](https://github.com/coderhaoxin/co-mysql)  [![npm package](https://img.shields.io/npm/v/npmdoc-co-mysql.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-co-mysql) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-co-mysql.svg)](https://travis-ci.org/npmdoc/node-npmdoc-co-mysql)

#### a mysql wrapper for co or koa

[![NPM](https://nodei.co/npm/co-mysql.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/co-mysql)

- [https://npmdoc.github.io/node-npmdoc-co-mysql/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-co-mysql/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-co-mysql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-co-mysql/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-co-mysql/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-co-mysql/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "haoxin"
    },
    "bugs": {
        "url": "https://github.com/coderhaoxin/co-mysql/issues"
    },
    "dependencies": {},
    "description": "a mysql wrapper for co or koa",
    "devDependencies": {
        "co": "*",
        "istanbul-harmony": "*",
        "mocha": "*",
        "mysql": "*"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "9f42a485d301ac5a996e376507ba6f17d377c4a1",
        "tarball": "https://registry.npmjs.org/co-mysql/-/co-mysql-1.0.0.tgz"
    },
    "engines": {
        "node": "> 0.11.13"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "a20896d5a037c9bb0c638f7c9ed47a849f428a15",
    "homepage": "https://github.com/coderhaoxin/co-mysql",
    "keywords": [
        "generator",
        "promise",
        "yield",
        "mysql",
        "koa",
        "co"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "coderhaoxin"
        },
        {
            "name": "zhaoda"
        }
    ],
    "name": "co-mysql",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/coderhaoxin/co-mysql.git"
    },
    "scripts": {
        "test": "mocha --harmony -R spec -t 5000 test/*.js",
        "test-cov": "node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- -R dot -t 5000 test/*.js",
        "test-travis": "node --harmony node_modules/.bin/istanbul cover node_modules/.bin/_mocha --report lcovonly -- -R dot -t 5000 test/*.js"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
