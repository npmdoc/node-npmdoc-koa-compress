# npmdoc-koa-compress

#### api documentation for  koa-compress (v2.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-koa-compress.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-koa-compress) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-koa-compress.svg)](https://travis-ci.org/npmdoc/node-npmdoc-koa-compress)

#### Compress middleware for koa

[![NPM](https://nodei.co/npm/koa-compress.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-compress)

- [https://npmdoc.github.io/node-npmdoc-koa-compress/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-compress/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-compress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-compress/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-koa-compress/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-koa-compress/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "koa-compress",
    "description": "Compress middleware for koa",
    "version": "2.0.0",
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com",
        "twitter": "https://twitter.com/jongleberry"
    },
    "license": "MIT",
    "repository": "koajs/compress",
    "dependencies": {
        "bytes": "^2.3.0",
        "compressible": "^2.0.0",
        "koa-is-json": "^1.0.0",
        "statuses": "^1.0.0"
    },
    "devDependencies": {
        "istanbul": "^0.4.2",
        "koa": "^2.0.0-alpha.3",
        "mocha": "^2.4.1",
        "should": "^3.0.0",
        "supertest": "^1.0.0"
    },
    "scripts": {
        "test": "NODE_ENV=test mocha --require should --reporter spec",
        "test-cov": "NODE_ENV=test node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --require should",
        "test-travis": "NODE_ENV=test node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- --require should"
    },
    "files": [
        "index.js",
        "LICENSE",
        "HISTORY.md"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
