# npmdoc-args

#### basic api documentation for  [args (v2.6.0)](https://github.com/leo/args#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-args.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-args) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-args.svg)](https://travis-ci.org/npmdoc/node-npmdoc-args)

#### Minimal toolkit for building CLIs

[![NPM](https://nodei.co/npm/args.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/args)

- [https://npmdoc.github.io/node-npmdoc-args/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-args/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-args/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-args/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-args/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-args/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "leo"
    },
    "bugs": {
        "url": "https://github.com/leo/args/issues"
    },
    "dependencies": {
        "camelcase": "4.1.0",
        "chalk": "1.1.3",
        "minimist": "1.2.0",
        "pkginfo": "0.4.0",
        "string-similarity": "1.1.0"
    },
    "description": "Minimal toolkit for building CLIs",
    "devDependencies": {
        "ava": "0.19.1",
        "eslint-config-prettier": "1.6.0",
        "execa": "0.6.3",
        "husky": "0.13.3",
        "lint-staged": "3.4.0",
        "prettier": "0.22.0",
        "xo": "0.18.1"
    },
    "directories": {},
    "dist": {
        "shasum": "5f2b310a4831f1181a7bf0d92f81aed32b538eb4",
        "tarball": "https://registry.npmjs.org/args/-/args-2.6.0.tgz"
    },
    "engines": {
        "node": ">= 6.6.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "438ce937fca38e032af0781860f6c53b11728cdb",
    "homepage": "https://github.com/leo/args#readme",
    "keywords": [
        "cli",
        "command",
        "arguments",
        "util",
        "bin",
        "commander",
        "minimist"
    ],
    "license": "MIT",
    "lint-staged": {
        "*.js": [
            "npm run lint",
            "prettier --single-quote --write",
            "git add"
        ]
    },
    "maintainers": [
        {
            "name": "leo"
        }
    ],
    "name": "args",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/leo/args.git"
    },
    "scripts": {
        "lint": "xo",
        "precommit": "lint-staged",
        "test": "npm run lint && ava"
    },
    "version": "2.6.0",
    "xo": {
        "extends": "prettier"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
