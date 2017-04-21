# npmtest-denodeify

#### basic test coverage for  [denodeify (v1.2.1)](https://github.com/matthew-andrews/denodeify)  [![npm package](https://img.shields.io/npm/v/npmtest-denodeify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-denodeify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-denodeify.svg)](https://travis-ci.org/npmtest/node-npmtest-denodeify)

#### Tool to turn functions with Node-style callback APIs into functions that return Promises

[![NPM](https://nodei.co/npm/denodeify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/denodeify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-denodeify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-denodeify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-denodeify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-denodeify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-denodeify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-denodeify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-denodeify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-denodeify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-denodeify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-denodeify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-denodeify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-denodeify/build/test-report.html](https://npmtest.github.io/node-npmtest-denodeify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-denodeify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-denodeify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-denodeify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-denodeify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-denodeify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-denodeify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-denodeify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-denodeify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "denodeify",
    "version": "1.2.1",
    "description": "Tool to turn functions with Node-style callback APIs into functions that return Promises",
    "main": "index.js",
    "directories": {
        "test": "test"
    },
    "scripts": {
        "files": "find . -name '*.js' ! -path './node_modules/*'",
        "jshint": "./node_modules/.bin/jshint 'npm run -s files'",
        "lintspaces": "./node_modules/.bin/lintspaces -i js-comments -e .editorconfig 'npm run -s files'",
        "test": "./node_modules/.bin/mocha test/*test.js && npm run jshint && npm run lintspaces"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/matthew-andrews/denodeify.git"
    },
    "author": "Matt Andrews",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/matthew-andrews/denodeify/issues"
    },
    "homepage": "https://github.com/matthew-andrews/denodeify",
    "devDependencies": {
        "es6-promise": "^1.0.0",
        "es6-shim": "^0.18.0",
        "jshint": "^2.5.5",
        "lie": "^2.7.7",
        "lintspaces-cli": "0.0.4",
        "mocha": "^1.21.4",
        "native-promise-only": "^0.7.6-a"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
