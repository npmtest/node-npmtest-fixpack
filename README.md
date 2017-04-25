# npmtest-fixpack

#### basic test coverage for  [fixpack (v2.3.1)](https://github.com/henrikjoreteg/fixpack)  [![npm package](https://img.shields.io/npm/v/npmtest-fixpack.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fixpack) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fixpack.svg)](https://travis-ci.org/npmtest/node-npmtest-fixpack)

#### cli tool that cleans up package.json files.

[![NPM](https://nodei.co/npm/fixpack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fixpack)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fixpack/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fixpack/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fixpack/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fixpack/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fixpack/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-fixpack/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-fixpack/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fixpack/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fixpack/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fixpack/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fixpack/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fixpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fixpack/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fixpack/build/test-report.html](https://npmtest.github.io/node-npmtest-fixpack/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fixpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fixpack/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fixpack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fixpack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fixpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fixpack/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fixpack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fixpack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Henrik Joreteg"
    },
    "bin": {
        "fixpack": "./bin/fixpack"
    },
    "bugs": {
        "url": "https://github.com/henrikjoreteg/fixpack/issues"
    },
    "dependencies": {
        "alce": "1.0.0",
        "colors": "*",
        "extend-object": "^1.0.0",
        "rc": "^0.6.0"
    },
    "description": "cli tool that cleans up package.json files.",
    "devDependencies": {
        "standard": "^3.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "53f03d88aab7d5123259282f0088a9a3b19836c2",
        "tarball": "https://registry.npmjs.org/fixpack/-/fixpack-2.3.1.tgz"
    },
    "gitHead": "f6a089ee5edc5ce1b898b5b04b482e5ea8570b83",
    "homepage": "https://github.com/henrikjoreteg/fixpack",
    "keywords": [
        "cleanup",
        "package"
    ],
    "license": "MIT",
    "main": "fixpack.js",
    "maintainers": [
        {
            "name": "henrikjoreteg"
        },
        {
            "name": "slang"
        }
    ],
    "name": "fixpack",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/henrikjoreteg/fixpack.git"
    },
    "scripts": {
        "test": "standard && standard bin/fixpack"
    },
    "version": "2.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
