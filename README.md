# npmtest-progress-stream

#### basic test coverage for  progress-stream (v2.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-progress-stream.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-progress-stream) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-progress-stream.svg)](https://travis-ci.org/npmtest/node-npmtest-progress-stream)

#### Read the progress of a stream

[![NPM](https://nodei.co/npm/progress-stream.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/progress-stream)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-progress-stream/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-progress-stream/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-progress-stream/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-progress-stream/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-progress-stream/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-progress-stream/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-progress-stream/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-progress-stream/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-progress-stream/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-progress-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-progress-stream/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-progress-stream/build/test-report.html](https://npmtest.github.io/node-npmtest-progress-stream/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-progress-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-progress-stream/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-progress-stream/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-progress-stream/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-progress-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-progress-stream/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-progress-stream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-progress-stream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "progress-stream",
    "version": "2.0.0",
    "description": "Read the progress of a stream",
    "repository": {
        "type": "git",
        "url": "git@github.com:freeall/progress-stream.git"
    },
    "keywords": [
        "stream",
        "progress",
        "percentage",
        "percent",
        "download",
        "upload",
        "file",
        "streaming",
        "request",
        "http"
    ],
    "main": "index.js",
    "dependencies": {
        "speedometer": "~1.0.0",
        "through2": "~2.0.3"
    },
    "devDependencies": {
        "request": "~2.29.0",
        "single-line-log": "~1.0.0",
        "numeral": "~1.5.2"
    },
    "scripts": {
        "test": "node test/http.js && node test/request.js"
    },
    "author": "freeall <freeall@gmail.com>",
    "license": "BSD-2-Clause"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
