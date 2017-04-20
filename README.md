# npmdoc-koa-compose

#### api documentation for  koa-compose (v4.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-koa-compose.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-koa-compose) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-koa-compose.svg)](https://travis-ci.org/npmdoc/node-npmdoc-koa-compose)

#### compose Koa middleware

[![NPM](https://nodei.co/npm/koa-compose.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-compose)

- [https://npmdoc.github.io/node-npmdoc-koa-compose/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-compose/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-compose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-compose/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-koa-compose/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-koa-compose/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "koa-compose",
    "description": "compose Koa middleware",
    "repository": "koajs/compose",
    "version": "4.0.0",
    "keywords": [
        "koa",
        "middleware",
        "compose"
    ],
    "files": [
        "index.js"
    ],
    "dependencies": {},
    "devDependencies": {
        "istanbul": "^0.4.2",
        "matcha": "^0.7.0",
        "mocha": "^3.1.2",
        "should": "^2.0.0",
        "standard": "^9.0.1"
    },
    "scripts": {
        "bench": "matcha bench/bench.js",
        "lint": "standard index.js test/*.js",
        "test": "mocha --require should --reporter spec",
        "test-cov": "node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --require should",
        "test-travis": "node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- --require should"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
