# npmtest-entities

#### test coverage for  [entities (v1.1.1)](https://github.com/fb55/node-entities)  [![npm package](https://img.shields.io/npm/v/npmtest-entities.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-entities) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-entities.svg)](https://travis-ci.org/npmtest/node-npmtest-entities)

#### Encode & decode XML/HTML entities with ease

[![NPM](https://nodei.co/npm/entities.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/entities)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-entities/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-entities/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-entities/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-entities/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-entities/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-entities/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-entities/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-entities/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-entities/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-entities/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-entities/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-entities/build/test-report.html](https://npmtest.github.io/node-npmtest-entities/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-entities/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-entities/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-entities/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-entities/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-entities/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-entities/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-entities/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-entities/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Felix Boehm"
    },
    "bugs": {
        "url": "https://github.com/fb55/node-entities/issues"
    },
    "dependencies": {},
    "description": "Encode & decode XML/HTML entities with ease",
    "devDependencies": {
        "coveralls": "*",
        "istanbul": "*",
        "jshint": "2",
        "mocha": "1",
        "mocha-lcov-reporter": "*"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "6e5c2d0a5621b5dadaecef80b90edfb5cd7772f0",
        "tarball": "https://registry.npmjs.org/entities/-/entities-1.1.1.tgz"
    },
    "homepage": "https://github.com/fb55/node-entities",
    "jshintConfig": {
        "eqeqeq": true,
        "freeze": true,
        "latedef": "nofunc",
        "noarg": true,
        "nonbsp": true,
        "quotmark": "double",
        "undef": true,
        "unused": true,
        "trailing": true,
        "eqnull": true,
        "proto": true,
        "smarttabs": true,
        "node": true,
        "globals": {
            "describe": true,
            "it": true
        }
    },
    "keywords": [
        "html",
        "xml",
        "entity",
        "encoding"
    ],
    "license": "BSD-like",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "feedic"
        }
    ],
    "name": "entities",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/fb55/node-entities.git"
    },
    "scripts": {
        "coveralls": "npm run lint && npm run lcov && (cat coverage/lcov.info | coveralls || exit 0)",
        "lcov": "istanbul cover _mocha --report lcovonly -- -R spec",
        "lint": "jshint index.js lib/*.js test/*.js",
        "test": "mocha && npm run lint"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
