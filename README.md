# api documentation for  [koa-compose (v3.2.1)](https://github.com/koajs/compose#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-koa-compose.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-koa-compose) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-koa-compose.svg)](https://travis-ci.org/npmdoc/node-npmdoc-koa-compose)
#### compose Koa middleware

[![NPM](https://nodei.co/npm/koa-compose.png?downloads=true)](https://www.npmjs.com/package/koa-compose)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-compose/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-koa-compose_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-compose/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-koa-compose/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-koa-compose/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/koajs/compose/issues"
    },
    "dependencies": {
        "any-promise": "^1.1.0"
    },
    "description": "compose Koa middleware",
    "devDependencies": {
        "co": "^4.6.0",
        "istanbul": "^0.4.2",
        "matcha": "^0.7.0",
        "mocha": "^3.1.2",
        "should": "^2.0.0",
        "standard": "^8.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a85ccb40b7d986d8e5a345b3a1ace8eabcf54de7",
        "tarball": "https://registry.npmjs.org/koa-compose/-/koa-compose-3.2.1.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "9fd370a88ab552f001f2af80e06afced123a4954",
    "homepage": "https://github.com/koajs/compose#readme",
    "keywords": [
        "koa",
        "middleware",
        "compose"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "aheckmann",
            "email": "aaron.heckmann+github@gmail.com"
        },
        {
            "name": "coderhaoxin",
            "email": "coderhaoxin@outlook.com"
        },
        {
            "name": "dead_horse",
            "email": "dead_horse@qq.com"
        },
        {
            "name": "eivifj",
            "email": "eivind.fjeldstad@gmail.com"
        },
        {
            "name": "fengmk2",
            "email": "fengmk2@gmail.com"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "juliangruber",
            "email": "julian@juliangruber.com"
        },
        {
            "name": "stephenmathieson",
            "email": "me@stephenmathieson.com"
        },
        {
            "name": "tejasmanohar",
            "email": "me@tejas.io"
        },
        {
            "name": "tjholowaychuk",
            "email": "tj@vision-media.ca"
        }
    ],
    "name": "koa-compose",
    "optionalDependencies": {},
    "publishConfig": {
        "tag": "next"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/koajs/compose.git"
    },
    "scripts": {
        "bench": "matcha bench/bench.js",
        "lint": "standard index.js test/*.js",
        "test": "mocha --require should --reporter spec",
        "test-cov": "node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --require should",
        "test-travis": "node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- --require should"
    },
    "version": "3.2.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module koa-compose](#apidoc.module.koa-compose)



# <a name="apidoc.module.koa-compose"></a>[module koa-compose](#apidoc.module.koa-compose)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
