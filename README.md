# npmdoc-standard

#### basic api documentation for  [standard (v10.0.2)](https://standardjs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-standard.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-standard) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-standard.svg)](https://travis-ci.org/npmdoc/node-npmdoc-standard)

#### JavaScript Standard Style

[![NPM](https://nodei.co/npm/standard.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/standard)

- [https://npmdoc.github.io/node-npmdoc-standard/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-standard/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-standard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-standard/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-standard/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-standard/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Feross Aboukhadijeh",
        "url": "http://feross.org/"
    },
    "bin": {
        "standard": "./bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/feross/standard/issues"
    },
    "dependencies": {
        "eslint": "~3.19.0",
        "eslint-config-standard": "10.2.1",
        "eslint-config-standard-jsx": "4.0.1",
        "eslint-plugin-import": "~2.2.0",
        "eslint-plugin-node": "~4.2.2",
        "eslint-plugin-promise": "~3.5.0",
        "eslint-plugin-react": "~6.10.0",
        "eslint-plugin-standard": "~3.0.1",
        "standard-engine": "~7.0.0"
    },
    "description": "JavaScript Standard Style",
    "devDependencies": {
        "babel-eslint": "^7.0.0",
        "cross-spawn": "^5.0.1",
        "eslint-index": "^1.3.0",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.1",
        "run-parallel-limit": "^1.0.3",
        "standard-packages": "^3.1.9",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "974c1c53cc865b075a4b576e78441e1695daaf7b",
        "tarball": "https://registry.npmjs.org/standard/-/standard-10.0.2.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "8b43d45da875f7324b340da42773baaef69a74fc",
    "homepage": "https://standardjs.com",
    "keywords": [
        "JavaScript Standard Style",
        "check",
        "checker",
        "code",
        "code checker",
        "code linter",
        "code standards",
        "code style",
        "enforce",
        "eslint",
        "hint",
        "jscs",
        "jshint",
        "lint",
        "policy",
        "quality",
        "simple",
        "standard",
        "standard style",
        "style",
        "style checker",
        "style linter",
        "verify"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bret"
        },
        {
            "name": "dcousens"
        },
        {
            "name": "dcposch"
        },
        {
            "name": "feross"
        },
        {
            "name": "flet"
        },
        {
            "name": "jb55"
        },
        {
            "name": "jprichardson"
        },
        {
            "name": "linusu"
        },
        {
            "name": "mafintosh"
        },
        {
            "name": "maxogden"
        },
        {
            "name": "othiym23"
        },
        {
            "name": "reggi"
        },
        {
            "name": "rstacruz"
        },
        {
            "name": "timoxley"
        },
        {
            "name": "watson"
        },
        {
            "name": "xjamundx"
        },
        {
            "name": "yoshuawuyts"
        }
    ],
    "name": "standard",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/feross/standard.git"
    },
    "scripts": {
        "show-rules": "eslint-index eslintrc.json",
        "show-rules-disabled": "eslint-index eslintrc.json --status omitted off",
        "show-summary": "eslint-index eslintrc.json --format table",
        "test": "./bin/cmd.js --verbose && tape test/*.js",
        "test-disabled": "npm test -- --disabled",
        "test-offline": "npm test -- --offline",
        "test-offline-quick": "npm test -- --offline --quick",
        "test-quick": "npm test -- --quick",
        "update-authors": "./bin/update-authors.sh"
    },
    "version": "10.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
