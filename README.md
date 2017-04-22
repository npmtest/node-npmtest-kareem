# npmtest-kareem

#### basic test coverage for  [kareem (v1.4.0)](https://github.com/vkarpov15/kareem#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-kareem.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-kareem) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-kareem.svg)](https://travis-ci.org/npmtest/node-npmtest-kareem)

#### Next-generation take on pre/post function hooks

[![NPM](https://nodei.co/npm/kareem.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/kareem)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-kareem/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-kareem/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-kareem/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-kareem/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-kareem/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-kareem/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-kareem/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-kareem/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-kareem/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-kareem/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-kareem/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-kareem/build/test-report.html](https://npmtest.github.io/node-npmtest-kareem/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-kareem/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-kareem/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-kareem/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-kareem/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kareem/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kareem/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-kareem/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-kareem/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Valeri Karpov"
    },
    "bugs": {
        "url": "https://github.com/vkarpov15/kareem/issues"
    },
    "dependencies": {},
    "description": "Next-generation take on pre/post function hooks",
    "devDependencies": {
        "acquit": "0.4.1",
        "gulp": "3.8.10",
        "gulp-jscs": "1.4.0",
        "gulp-mocha": "2.0.0",
        "istanbul": "0.4.5",
        "jscs": "1.9.0",
        "mocha": "3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "640285bc0174f10d4bf2127bb30e861bc0372c1c",
        "tarball": "https://registry.npmjs.org/kareem/-/kareem-1.4.0.tgz"
    },
    "gitHead": "101c5f58597c6799289b943114179d1a12288215",
    "homepage": "https://github.com/vkarpov15/kareem#readme",
    "jscsConfig": {
        "preset": "airbnb",
        "requireMultipleVarDecl": null,
        "disallowMultipleVarDecl": true
    },
    "license": "Apache 2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "vkarpov15"
        }
    ],
    "name": "kareem",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/vkarpov15/kareem.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha ./test/*",
        "test-travis": "./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- -R spec ./test/*"
    },
    "version": "1.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
