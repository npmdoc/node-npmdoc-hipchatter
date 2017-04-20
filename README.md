# npmdoc-hipchatter

#### api documentation for  hipchatter (v1.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-hipchatter.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hipchatter) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hipchatter.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hipchatter)

#### Wrapper for the HipChat API (v2)

[![NPM](https://nodei.co/npm/hipchatter.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hipchatter)

- [https://npmdoc.github.io/node-npmdoc-hipchatter/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hipchatter/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hipchatter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hipchatter/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hipchatter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hipchatter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hipchatter",
    "description": "Wrapper for the HipChat API (v2)",
    "version": "1.0.0",
    "author": "Charlton Roberts <charltonroberts@gmail.com> (http://charlton.io)",
    "license": "GPL-2.0",
    "contributors": [
        "Macklin Underdown <macklinu@gmail.com> (http://mackli.nu)"
    ],
    "keywords": [
        "hipchat",
        "hip",
        "chat",
        "hip",
        "atlassian",
        "hipchatter",
        "api"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/charltoons/hipchatter.git"
    },
    "main": "hipchatter.js",
    "dependencies": {
        "async": "~0.2.9",
        "needle": "^1.0.0"
    },
    "engines": {
        "node": "*"
    },
    "devDependencies": {
        "mocha": "~1.14.0",
        "chai": "~1.8.1",
        "colors": "~0.6.2",
        "grunt": "~0.4.1",
        "grunt-execute": "~0.1.5"
    },
    "scripts": {
        "test": "mocha -t 6000 -R spec"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
