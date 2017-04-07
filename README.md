# api documentation for  [args (v2.4.1)](https://github.com/leo/args#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-args.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-args) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-args.svg)](https://travis-ci.org/npmdoc/node-npmdoc-args)
#### Minimal toolkit for building CLIs

[![NPM](https://nodei.co/npm/args.png?downloads=true)](https://www.npmjs.com/package/args)

[![apidoc](https://npmdoc.github.io/node-npmdoc-args/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-args%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-args/build/apidoc.html)

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
        "camelcase": "4.0.0",
        "chalk": "1.1.3",
        "minimist": "1.2.0",
        "pkginfo": "0.4.0"
    },
    "description": "Minimal toolkit for building CLIs",
    "devDependencies": {
        "ava": "0.18.2",
        "eslint-config-prettier": "1.5.0",
        "execa": "0.6.0",
        "husky": "0.13.3",
        "lint-staged": "3.4.0",
        "prettier": "0.22.0",
        "xo": "0.17.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e409e5d73eaf1185b7b29acb3cc41e3b650dea77",
        "tarball": "https://registry.npmjs.org/args/-/args-2.4.1.tgz"
    },
    "engines": {
        "node": ">= 6.6.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "7f23720aed673fd7103585d91faf000ba79bf19f",
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
            "name": "leo",
            "email": "mindrun@icloud.com"
        }
    ],
    "name": "args",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/leo/args.git"
    },
    "scripts": {
        "lint": "xo",
        "precommit": "lint-staged",
        "test": "npm run lint && ava"
    },
    "version": "2.4.1",
    "xo": {
        "extends": "prettier"
    }
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module args](#apidoc.module.args)
1.  object <span class="apidocSignatureSpan">args.</span>config
1.  object <span class="apidocSignatureSpan">args.</span>details
1.  object <span class="apidocSignatureSpan">args.</span>printMainColor
1.  object <span class="apidocSignatureSpan">args.</span>printSubColor

#### [module args.printMainColor](#apidoc.module.args.printMainColor)
1.  boolean <span class="apidocSignatureSpan">args.printMainColor.</span>enabled
1.  boolean <span class="apidocSignatureSpan">args.printMainColor.</span>supportsColor
1.  [function <span class="apidocSignatureSpan">args.printMainColor.</span>hasColor ()](#apidoc.element.args.printMainColor.hasColor)
1.  [function <span class="apidocSignatureSpan">args.printMainColor.</span>stripColor (str)](#apidoc.element.args.printMainColor.stripColor)
1.  object <span class="apidocSignatureSpan">args.printMainColor.</span>styles



# <a name="apidoc.module.args"></a>[module args](#apidoc.module.args)



# <a name="apidoc.module.args.printMainColor"></a>[module args.printMainColor](#apidoc.module.args.printMainColor)

#### <a name="apidoc.element.args.printMainColor.hasColor"></a>[function <span class="apidocSignatureSpan">args.printMainColor.</span>hasColor ()](#apidoc.element.args.printMainColor.hasColor)
- description and source-code
```javascript
hasColor = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.args.printMainColor.stripColor"></a>[function <span class="apidocSignatureSpan">args.printMainColor.</span>stripColor (str)](#apidoc.element.args.printMainColor.stripColor)
- description and source-code
```javascript
stripColor = function (str) {
	return typeof str === 'string' ? str.replace(ansiRegex, '') : str;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
