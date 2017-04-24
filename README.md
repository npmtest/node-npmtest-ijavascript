# npmtest-ijavascript

#### basic test coverage for  [ijavascript (v5.0.19)](https://n-riesco.github.io/ijavascript)  [![npm package](https://img.shields.io/npm/v/npmtest-ijavascript.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ijavascript) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ijavascript.svg)](https://travis-ci.org/npmtest/node-npmtest-ijavascript)

#### IJavascript is a Javascript kernel for the Jupyter notebook

[![NPM](https://nodei.co/npm/ijavascript.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ijavascript)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ijavascript/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ijavascript/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ijavascript/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ijavascript/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ijavascript/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ijavascript/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ijavascript/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ijavascript/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ijavascript/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ijavascript/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ijavascript/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ijavascript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ijavascript/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ijavascript/build/test-report.html](https://npmtest.github.io/node-npmtest-ijavascript/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ijavascript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ijavascript/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ijavascript/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ijavascript/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ijavascript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ijavascript/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ijavascript/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ijavascript/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "url": "http://www.nicolasriesco.net/"
    },
    "bin": {
        "ijs": "bin/ijavascript.js",
        "ijsconsole": "bin/ijsconsole.js",
        "ijsinstall": "bin/ijsinstall.js",
        "ijskernel": "lib/kernel.js",
        "ijsnotebook": "bin/ijsnotebook.js"
    },
    "bugs": {
        "url": "https://github.com/n-riesco/ijavascript/issues"
    },
    "contributors": [
        {
            "name": "Benjamin Abel"
        },
        {
            "name": "Kevin Kwok"
        },
        {
            "name": "Mandar Vaze"
        },
        {
            "name": "Matt Torok"
        },
        {
            "name": "Min RK"
        },
        {
            "name": "Nicolas Riesco"
        },
        {
            "name": "Will Whitney"
        }
    ],
    "dependencies": {
        "jp-kernel": "0.1.x"
    },
    "description": "IJavascript is a Javascript kernel for the Jupyter notebook",
    "devDependencies": {
        "debug": "latest",
        "jsdoc": "latest",
        "jshint": "latest",
        "mocha": "3",
        "uuid": "^3.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "3bd3b4674bebe3c6aff240f84d4fd8e0bb38c8e0",
        "tarball": "https://registry.npmjs.org/ijavascript/-/ijavascript-5.0.19.tgz"
    },
    "gitHead": "608a6319ba6b9ec3bb1042491756595fbf149a49",
    "homepage": "https://n-riesco.github.io/ijavascript",
    "keywords": [
        "javascript",
        "kernel",
        "ipython",
        "jupyter"
    ],
    "license": "BSD-3-Clause",
    "maintainers": [
        {
            "name": "n-riesco"
        }
    ],
    "name": "ijavascript",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/n-riesco/ijavascript.git"
    },
    "scripts": {
        "doc": "python scripts/doc-build.py",
        "doc:publish": "node scripts/doc-publish.js gh-pages https://github.com/n-riesco/ijavascript",
        "lint": "jshint bin lib",
        "test": "npm run lint && npm run test:ijskernel",
        "test:ijskernel": "mocha test/ijskernel.js"
    },
    "version": "5.0.19"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
