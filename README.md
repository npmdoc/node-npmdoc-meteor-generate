# npmdoc-meteor-generate

#### api documentation for  meteor-generate (v0.12.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-meteor-generate.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-meteor-generate) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-meteor-generate.svg)](https://travis-ci.org/npmdoc/node-npmdoc-meteor-generate)

#### Generate Meteor scaffolding on demand

[![NPM](https://nodei.co/npm/meteor-generate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/meteor-generate)

- [https://npmdoc.github.io/node-npmdoc-meteor-generate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-meteor-generate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-meteor-generate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-meteor-generate/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-meteor-generate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-meteor-generate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "meteor-generate",
    "version": "0.12.2",
    "description": "Generate Meteor scaffolding on demand",
    "keywords": [
        "meteor",
        "scaffold"
    ],
    "author": "Adam Brodzinski",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/AdamBrodzinski/meteor-generate.git"
    },
    "bin": {
        "mgen": "./bin/mgen"
    },
    "dependencies": {
        "coffee-script": "*",
        "commander": "*",
        "change-case": "*",
        "fs-extra": "0.13.0",
        "pluralize": "*"
    },
    "devDependencies": {
        "mocha": "*",
        "chai": "*"
    },
    "scripts": {
        "test": "make test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
