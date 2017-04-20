# npmtest-tar-fs

#### basic test coverage for  [tar-fs (v1.15.2)](https://github.com/mafintosh/tar-fs)  [![npm package](https://img.shields.io/npm/v/npmtest-tar-fs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tar-fs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tar-fs.svg)](https://travis-ci.org/npmtest/node-npmtest-tar-fs)

#### filesystem bindings for tar-stream

[![NPM](https://nodei.co/npm/tar-fs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tar-fs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tar-fs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tar-fs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tar-fs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tar-fs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tar-fs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tar-fs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tar-fs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tar-fs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tar-fs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tar-fs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tar-fs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tar-fs/build/test-report.html](https://npmtest.github.io/node-npmtest-tar-fs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tar-fs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tar-fs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tar-fs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tar-fs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tar-fs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tar-fs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tar-fs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tar-fs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "tar-fs",
    "version": "1.15.2",
    "description": "filesystem bindings for tar-stream",
    "dependencies": {
        "chownr": "^1.0.1",
        "mkdirp": "^0.5.1",
        "pump": "^1.0.0",
        "tar-stream": "^1.1.2"
    },
    "keywords": [
        "tar",
        "fs",
        "file",
        "tarball",
        "directory",
        "stream"
    ],
    "devDependencies": {
        "rimraf": "^2.2.8",
        "standard": "^4.5.4",
        "tape": "^3.0.0"
    },
    "scripts": {
        "test": "standard && tape test/index.js"
    },
    "bugs": {
        "url": "https://github.com/mafintosh/tar-fs/issues"
    },
    "homepage": "https://github.com/mafintosh/tar-fs",
    "main": "index.js",
    "directories": {
        "test": "test"
    },
    "author": "Mathias Buus",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/mafintosh/tar-fs.git"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
