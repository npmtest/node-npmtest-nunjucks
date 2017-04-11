# test coverage for  [nunjucks (v3.0.0)](https://github.com/mozilla/nunjucks#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-nunjucks.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nunjucks) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nunjucks.svg)](https://travis-ci.org/npmtest/node-npmtest-nunjucks)
#### A powerful templating engine with inheritance, asynchronous control, and more (jinja2 inspired)

[![NPM](https://nodei.co/npm/nunjucks.png?downloads=true)](https://www.npmjs.com/package/nunjucks)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nunjucks/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nunjucks/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nunjucks/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nunjucks/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nunjucks/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nunjucks/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nunjucks/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nunjucks/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-nunjucks/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-nunjucks/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-nunjucks%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nunjucks/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nunjucks/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-nunjucks%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nunjucks/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nunjucks/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nunjucks/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Long",
        "email": "longster@gmail.com"
    },
    "bin": {
        "nunjucks-precompile": "./bin/precompile"
    },
    "browser": "./browser/nunjucks.js",
    "bugs": {
        "url": "https://github.com/mozilla/nunjucks/issues"
    },
    "dependencies": {
        "a-sync-waterfall": "^1.0.0",
        "asap": "^2.0.3",
        "chokidar": "^1.6.0",
        "yargs": "^3.32.0"
    },
    "description": "A powerful templating engine with inheritance, asynchronous control, and more (jinja2 inspired)",
    "devDependencies": {
        "expect.js": "*",
        "express": "4.x",
        "istanbul": "0.3.x",
        "jshint": "2.8.x",
        "mocha": "*",
        "node-libs-browser": "^0.4.3",
        "supertest": "*",
        "uglify-js": "*",
        "webpack": "^1.8.11"
    },
    "directories": {},
    "dist": {
        "shasum": "0a2a8fd2942a3ba04f5ba6684e4f7f7ceaca8305",
        "tarball": "https://registry.npmjs.org/nunjucks/-/nunjucks-3.0.0.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "737e4e005cd2a62f1d9e7cd4552b76b21d368930",
    "homepage": "https://github.com/mozilla/nunjucks#readme",
    "keywords": [
        "template",
        "templating"
    ],
    "license": "BSD-2-Clause",
    "main": "index",
    "maintainers": [
        {
            "name": "carljm",
            "email": "carl@oddbird.net"
        },
        {
            "name": "jlongster",
            "email": "longster@gmail.com"
        },
        {
            "name": "samypesse",
            "email": "samypesse@gmail.com"
        },
        {
            "name": "vecmezoni",
            "email": "alexander.inozemtsev@gmail.com"
        }
    ],
    "name": "nunjucks",
    "optionalDependencies": {
        "chokidar": "^1.6.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mozilla/nunjucks.git"
    },
    "scripts": {
        "browserfiles": "./bin/bundle",
        "lint": "jshint .",
        "test": "jshint . && istanbul cover ./node_modules/mocha/bin/_mocha -- -R dot tests"
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
