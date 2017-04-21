# npmdoc-nodemcu-tool

#### api documentation for  [nodemcu-tool (v2.0.4)](https://github.com/AndiDittrich/NodeMCU-Tool)  [![npm package](https://img.shields.io/npm/v/npmdoc-nodemcu-tool.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nodemcu-tool) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nodemcu-tool.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nodemcu-tool)

#### Command line tool to upload and manage files on your NodeMCU / ESP8266 Module.

[![NPM](https://nodei.co/npm/nodemcu-tool.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nodemcu-tool)

- [https://npmdoc.github.io/node-npmdoc-nodemcu-tool/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nodemcu-tool/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nodemcu-tool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nodemcu-tool/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nodemcu-tool/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nodemcu-tool/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nodemcu-tool",
    "version": "2.0.4",
    "description": "Command line tool to upload and manage files on your NodeMCU / ESP8266 Module.",
    "keywords": [
        "cli",
        "lua",
        "terminal",
        "nodemcu",
        "esp8266",
        "wifi",
        "serial",
        "upload",
        "embedded"
    ],
    "homepage": "https://github.com/AndiDittrich/NodeMCU-Tool",
    "bugs": "https://github.com/AndiDittrich/NodeMCU-Tool/issues",
    "repository": "AndiDittrich/NodeMCU-Tool",
    "files": [
        "bin",
        "lib",
        "helloworld.lua",
        "CHANGED.md",
        "LICENSE.md",
        "README.md"
    ],
    "main": "./lib/NodeMCU-Tool.js",
    "bin": {
        "nodemcu-tool": "bin/nodemcu-tool.js"
    },
    "preferGlobal": true,
    "author": "Andi Dittrich (http://andidittrich.de)",
    "license": "MIT",
    "dependencies": {
        "cli-progress": "^1.2.0",
        "colors": "^1.1.2",
        "commander": "^2.9.0",
        "logging-facility": "^1.1.0",
        "prompt": "^0.2.14",
        "serialport": "^4.0.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
