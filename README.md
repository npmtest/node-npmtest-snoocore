# npmtest-snoocore

#### basic test coverage for  snoocore (v3.3.1)  [![npm package](https://img.shields.io/npm/v/npmtest-snoocore.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-snoocore) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-snoocore.svg)](https://travis-ci.org/npmtest/node-npmtest-snoocore)

#### A minimal and complete JavaScript driver for the Reddit API.

[![NPM](https://nodei.co/npm/snoocore.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/snoocore)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-snoocore/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-snoocore/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-snoocore/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-snoocore/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-snoocore/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-snoocore/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-snoocore/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-snoocore/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-snoocore/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-snoocore/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-snoocore/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-snoocore/build/test-report.html](https://npmtest.github.io/node-npmtest-snoocore/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-snoocore/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-snoocore/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-snoocore/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-snoocore/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-snoocore/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-snoocore/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-snoocore/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-snoocore/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "snoocore",
    "version": "3.3.1",
    "description": "A minimal and complete JavaScript driver for the Reddit API.",
    "main": "build/src/Snoocore.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/trevorsenior/snoocore.git"
    },
    "author": "Trevor Senior <trevor@tsenior.com> (http://tsenior.com/)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/trevorsenior/snoocore/issues"
    },
    "dependencies": {
        "he": "^0.5.0",
        "when": "^3.6.3"
    },
    "devDependencies": {
        "babel": "^5.1.11",
        "browserify": "^6.3.3",
        "chai": "^1.10.0",
        "chai-as-promised": "^4.1.1",
        "coveralls": "^2.11.2",
        "gulp": "^3.8.11",
        "gulp-babel": "^5.1.0",
        "gulp-sourcemaps": "^1.5.1",
        "gulp-uglify": "^1.2.0",
        "gulp-util": "^3.0.4",
        "istanbul": "^0.3.13",
        "karma": "^0.12.28",
        "karma-chrome-launcher": "^0.1.8",
        "karma-env": "^0.1.0",
        "karma-firefox-launcher": "^0.1.3",
        "karma-mocha": "^0.1.9",
        "karma-mocha-reporter": "^1.0.2",
        "karma-phantomjs-launcher": "^0.1.4",
        "karma-safari-launcher": "^0.1.1",
        "mocha": "^2.1.0",
        "phantom": "^0.7.2",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {
        "test": "test"
    },
    "keywords": [
        "reddit",
        "api",
        "snoocore",
        "wrapper",
        "client"
    ],
    "scripts": {
        "test": "./node_modules/.bin/gulp mocha",
        "karma": "./node_modules/.bin/gulp karma"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
