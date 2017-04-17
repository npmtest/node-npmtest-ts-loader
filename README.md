# test coverage for  [ts-loader (v2.0.3)](https://github.com/TypeStrong/ts-loader)  [![npm package](https://img.shields.io/npm/v/npmtest-ts-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ts-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ts-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-ts-loader)
#### TypeScript loader for webpack

[![NPM](https://nodei.co/npm/ts-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ts-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ts-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ts-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ts-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ts-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ts-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ts-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ts-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ts-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ts-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ts-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ts-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ts-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-ts-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ts-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ts-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ts-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ts-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ts-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ts-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ts-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ts-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Brantly",
        "url": "http://www.jbrantly.com/"
    },
    "bugs": {
        "url": "https://github.com/TypeStrong/ts-loader/issues"
    },
    "dependencies": {
        "colors": "^1.0.3",
        "enhanced-resolve": "^3.0.0",
        "loader-utils": "^1.0.2",
        "semver": "^5.0.1"
    },
    "description": "TypeScript loader for webpack",
    "devDependencies": {
        "babel": "^6.0.0",
        "babel-core": "^6.0.0",
        "babel-loader": "^6.0.0",
        "babel-polyfill": "^6.16.0",
        "babel-preset-es2015": "^6.0.0",
        "babel-preset-es2016": "^6.16.0",
        "babel-preset-react": "^6.0.0",
        "escape-string-regexp": "^1.0.3",
        "fs-extra": "^2.0.0",
        "glob": "^7.1.1",
        "html-webpack-plugin": "^2.17.0",
        "jasmine-core": "^2.5.2",
        "karma": "^1.3.0",
        "karma-jasmine": "^1.0.0",
        "karma-mocha-reporter": "^2.0.0",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-sourcemap-loader": "^0.3.6",
        "karma-webpack": "^2.0.1",
        "mkdirp": "^0.5.1",
        "mocha": "^3.1.0",
        "phantomjs-prebuilt": "^2.1.2",
        "rimraf": "^2.4.2",
        "typescript": "^2.2.1",
        "typings": "^2.0.0",
        "webpack": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "89b8c87598f048df065766e07e1538f0eaeb1165",
        "tarball": "https://registry.npmjs.org/ts-loader/-/ts-loader-2.0.3.tgz"
    },
    "engines": {
        "node": ">=4.3.0 <5.0.0 || >=5.10"
    },
    "gitHead": "6c733272a02bfc9cc99aad8e91a1ab9be5a2be61",
    "homepage": "https://github.com/TypeStrong/ts-loader",
    "keywords": [
        "ts-loader",
        "typescript-loader",
        "webpack",
        "loader",
        "typescript",
        "ts"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "blakeembrey"
        },
        {
            "name": "jbrantly"
        },
        {
            "name": "johnnyreilly"
        }
    ],
    "name": "ts-loader",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/TypeStrong/ts-loader.git"
    },
    "scripts": {
        "build": "tsc --version && tsc --project \"./src\"",
        "comparison-tests": "npm link ./test/comparison-tests/testLib && node test/comparison-tests/run-tests.js",
        "comparison-tests-generate": "node test/comparison-tests/stub-new-version.js",
        "execution-tests": "node test/execution-tests/run-tests.js",
        "test": "node test/run-tests.js"
    },
    "version": "2.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
