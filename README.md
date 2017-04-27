# npmtest-redux-undo

#### basic test coverage for  [redux-undo (v0.6.1)](https://github.com/omnidan/redux-undo)  [![npm package](https://img.shields.io/npm/v/npmtest-redux-undo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redux-undo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redux-undo.svg)](https://travis-ci.org/npmtest/node-npmtest-redux-undo)

#### simple undo/redo functionality for redux state containers

[![NPM](https://nodei.co/npm/redux-undo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-undo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redux-undo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-undo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redux-undo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redux-undo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redux-undo/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-redux-undo/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-redux-undo/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redux-undo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redux-undo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-redux-undo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-redux-undo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-undo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-redux-undo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-redux-undo/build/test-report.html](https://npmtest.github.io/node-npmtest-redux-undo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-redux-undo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redux-undo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-redux-undo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-undo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-undo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-undo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redux-undo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redux-undo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Bugl",
        "url": "https://github.com/omnidan"
    },
    "bugs": {
        "url": "https://github.com/omnidan/redux-undo/issues"
    },
    "dependencies": {
        "redux": "^3.0.2"
    },
    "description": "simple undo/redo functionality for redux state containers",
    "devDependencies": {
        "babel": "^6.3.26",
        "babel-cli": "^6.4.5",
        "babel-core": "^6.4.5",
        "babel-eslint": "^4.1.6",
        "babel-plugin-transform-object-rest-spread": "^6.3.13",
        "babel-preset-es2015": "^6.3.13",
        "chai": "^3.4.1",
        "eslint": "^1.6",
        "eslint-config-standard": "^4.4.0",
        "eslint-plugin-react": "^3.5.1",
        "eslint-plugin-standard": "^1.3.1",
        "expect": "^1.12.0",
        "isparta": "^3.1.0",
        "mocha": "^2.3.3",
        "rimraf": "^2.4.3"
    },
    "directories": {},
    "dist": {
        "shasum": "ff407749b8f468bead636e413819e92c0982eeca",
        "tarball": "https://registry.npmjs.org/redux-undo/-/redux-undo-0.6.1.tgz"
    },
    "gitHead": "510d17a2f13584fb6344c8db556268f34dca7caa",
    "homepage": "https://github.com/omnidan/redux-undo",
    "keywords": [
        "redux",
        "undo",
        "redo",
        "flux",
        "time travel"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "omnidan"
        }
    ],
    "name": "redux-undo",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/omnidan/redux-undo.git"
    },
    "scripts": {
        "build": "babel src --out-dir lib",
        "clean": "rimraf lib",
        "lint": "eslint src test",
        "prepublish": "npm run lint && npm run test && npm run clean && npm run build",
        "test": "NODE_ENV=test mocha --compilers js:babel-core/register --recursive",
        "test:cov": "babel-node ./node_modules/.bin/isparta cover ./node_modules/.bin/_mocha -- --recursive",
        "test:watch": "NODE_ENV=test mocha --compilers js:babel-core/register --recursive --watch"
    },
    "version": "0.6.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
