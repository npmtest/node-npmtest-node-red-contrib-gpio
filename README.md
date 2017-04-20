# npmtest-node-red-contrib-gpio

#### basic test coverage for  [node-red-contrib-gpio (v0.9.2)](https://github.com/monteslu/node-red-contrib-gpio)  [![npm package](https://img.shields.io/npm/v/npmtest-node-red-contrib-gpio.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-red-contrib-gpio) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-red-contrib-gpio.svg)](https://travis-ci.org/npmtest/node-npmtest-node-red-contrib-gpio)

#### A set of node-red nodes for using johnny-five and IO plugins

[![NPM](https://nodei.co/npm/node-red-contrib-gpio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-red-contrib-gpio)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-red-contrib-gpio/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-red-contrib-gpio/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/test-report.html](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-red-contrib-gpio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-red-contrib-gpio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-red-contrib-gpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-red-contrib-gpio/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-red-contrib-gpio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Luis Montes"
    },
    "bugs": {
        "url": "https://github.com/monteslu/node-red-contrib-gpio/issues"
    },
    "dependencies": {
        "firmata": "^0.15.0",
        "johnny-five": "^0.10.6",
        "lodash": "^4.11.1",
        "meshblu": "^2.2.5",
        "mqtt": "^2.1.1",
        "mqtt-serial": "^0.6.0",
        "serialport": "^4.0.7",
        "skynet-serial": "^1.3.0",
        "udp-serial": "^0.2.0"
    },
    "description": "A set of node-red nodes for using johnny-five and IO plugins",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "c3dff6d179bddf8abf37c505d30cb566d4e85074",
        "tarball": "https://registry.npmjs.org/node-red-contrib-gpio/-/node-red-contrib-gpio-0.9.2.tgz"
    },
    "gitHead": "5ef116285c3a397bc86230b1750af35437c6b754",
    "homepage": "https://github.com/monteslu/node-red-contrib-gpio",
    "keywords": [
        "gpio",
        "io",
        "firmata",
        "node-red",
        "johnny-five",
        "mqtt",
        "raspberry pi",
        "arduino",
        "galileo",
        "edison",
        "beaglebone"
    ],
    "license": "MIT",
    "main": "gpio.js",
    "maintainers": [
        {
            "name": "monteslu"
        }
    ],
    "name": "node-red-contrib-gpio",
    "node-red": {
        "nodes": {
            "gpio": "gpio.js"
        }
    },
    "optionalDependencies": {
        "mqtt": "^2.1.1"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/monteslu/node-red-contrib-gpio.git"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "0.9.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
