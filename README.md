# npmdoc-raspi-io

#### basic api documentation for  [raspi-io (v7.3.1)](https://github.com/nebrius/raspi-io)  [![npm package](https://img.shields.io/npm/v/npmdoc-raspi-io.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-raspi-io) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-raspi-io.svg)](https://travis-ci.org/npmdoc/node-npmdoc-raspi-io)

#### A Firmata-compatible Raspberry Pi I/O API

[![NPM](https://nodei.co/npm/raspi-io.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/raspi-io)

- [https://npmdoc.github.io/node-npmdoc-raspi-io/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-raspi-io/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-raspi-io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-raspi-io/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-raspi-io/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-raspi-io/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "raspi-io",
    "version": "7.3.1",
    "description": "A Firmata-compatible Raspberry Pi I/O API",
    "main": "dist/index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/nebrius/raspi-io.git"
    },
    "homepage": "https://github.com/nebrius/raspi-io",
    "keywords": [
        "raspberrypi",
        "nodebots",
        "robots"
    ],
    "dependencies": {
        "raspi": "^3.0.0",
        "raspi-board": "^4.0.0",
        "raspi-gpio": "^3.0.0",
        "raspi-i2c": "^5.0.2",
        "raspi-led": "^1.4.0",
        "raspi-pwm": "^3.1.0",
        "raspi-serial": "^3.0.3",
        "raspi-soft-pwm": "^2.0.1",
        "raspi-io-core": "1.1.1"
    },
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-preset-es2015": "^6.6.0",
        "eslint": "^2.4.0"
    },
    "scripts": {
        "test": "node ./test/bootstrap.js",
        "prebuild": "eslint src/**/*.js",
        "build": "babel src/index.js --presets es2015 --out-file dist/index.js --source-maps"
    },
    "author": "Bryan Hughes <bryan@nebri.us>",
    "contributors": [
        {
            "name": "Bryan Hughes"
        },
        {
            "name": "Brian Cooke"
        }
    ],
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/nebrius/raspi-io/issues"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
