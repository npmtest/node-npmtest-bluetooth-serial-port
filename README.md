# npmtest-bluetooth-serial-port

#### basic test coverage for  [bluetooth-serial-port (v2.1.2)](https://github.com/eelcocramer/node-bluetooth-serial-port)  [![npm package](https://img.shields.io/npm/v/npmtest-bluetooth-serial-port.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bluetooth-serial-port) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bluetooth-serial-port.svg)](https://travis-ci.org/npmtest/node-npmtest-bluetooth-serial-port)

#### Bluetooth serial port communication for Node.js

[![NPM](https://nodei.co/npm/bluetooth-serial-port.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bluetooth-serial-port)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bluetooth-serial-port/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bluetooth-serial-port/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/test-report.html](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bluetooth-serial-port/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bluetooth-serial-port/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bluetooth-serial-port/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bluetooth-serial-port/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bluetooth-serial-port/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "bluetooth-serial-port",
    "version": "2.1.2",
    "description": "Bluetooth serial port communication for Node.js",
    "author": "Eelco Cramer <eelco@hailendal.org>",
    "keywords": [
        "bluetooth",
        "serial port",
        "rfcomm",
        "linux",
        "os x",
        "windows"
    ],
    "homepage": "https://github.com/eelcocramer/node-bluetooth-serial-port",
    "bugs": "https://github.com/eelcocramer/node-bluetooth-serial-port/issues",
    "repository": {
        "type": "git",
        "url": "https://github.com/eelcocramer/node-bluetooth-serial-port"
    },
    "directories": {
        "lib": "./lib"
    },
    "main": "./lib/bluetooth-serial-port.js",
    "os": [
        "darwin",
        "linux",
        "win32"
    ],
    "dependencies": {
        "bindings": "1.2.x",
        "nan": "latest"
    },
    "engines": {
        "node": ">= 0.8.x",
        "npm": ">= 1.1.x"
    },
    "scripts": {
        "install": "node-gyp configure build",
        "install-debug": "node-gyp configure build --debug"
    },
    "license": "BSD-2-Clause",
    "contributors": [
        "Eric Smekens",
        "Juho Vepsäläinen",
        "Elmar Langholz",
        "Donald Ness",
        "Joost Verdoorn",
        "Max Metral",
        "Thomas Wickham",
        "Adrián Estrada",
        "Juan Gomez",
        "Eric Lundby",
        "Kevin Clarens"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
