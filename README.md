# npmdoc-eslint-loader

#### api documentation for  [eslint-loader (v1.7.1)](https://github.com/MoOx/eslint-loader#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-eslint-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eslint-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eslint-loader.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eslint-loader)

#### eslint loader (for webpack)

[![NPM](https://nodei.co/npm/eslint-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-loader)

- [https://npmdoc.github.io/node-npmdoc-eslint-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-loader/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eslint-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eslint-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Maxime Thirouin"
    },
    "ava": {
        "files": [
            "test/*.js"
        ],
        "verbose": true
    },
    "bugs": {
        "url": "https://github.com/MoOx/eslint-loader/issues"
    },
    "dependencies": {
        "find-cache-dir": "^0.1.1",
        "loader-fs-cache": "^1.0.0",
        "loader-utils": "^1.0.2",
        "object-assign": "^4.0.1",
        "object-hash": "^1.1.4",
        "rimraf": "^2.6.1"
    },
    "description": "eslint loader (for webpack)",
    "devDependencies": {
        "ava": "^0.17.0",
        "eslint": "^3.0.0",
        "eslint-friendly-formatter": "^2.0.4",
        "npmpub": "^3.0.1",
        "webpack": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "50b158dd6272dcefb97e984254837f81a5802ce0",
        "tarball": "https://registry.npmjs.org/eslint-loader/-/eslint-loader-1.7.1.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "56ad1d8fa13fd8215d58cc2341524b3ac044b4bd",
    "homepage": "https://github.com/MoOx/eslint-loader#readme",
    "keywords": [
        "lint",
        "linter",
        "eslint",
        "loader",
        "webpack"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "moox"
        }
    ],
    "name": "eslint-loader",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": ">=1.6.0 <4.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MoOx/eslint-loader.git"
    },
    "scripts": {
        "ava": "ava",
        "lint": "eslint .",
        "release": "npmpub",
        "test": "npm run lint && npm run ava"
    },
    "version": "1.7.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
