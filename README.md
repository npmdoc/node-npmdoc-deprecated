# npmdoc-deprecated

#### api documentation for  [deprecated (v0.0.1)](http://github.com/wearefractal/deprecated)  [![npm package](https://img.shields.io/npm/v/npmdoc-deprecated.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-deprecated) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-deprecated.svg)](https://travis-ci.org/npmdoc/node-npmdoc-deprecated)

#### Tool for deprecating things

[![NPM](https://nodei.co/npm/deprecated.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/deprecated)

- [https://npmdoc.github.io/node-npmdoc-deprecated/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-deprecated/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-deprecated/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-deprecated/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-deprecated/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-deprecated/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "deprecated",
    "description": "Tool for deprecating things",
    "version": "0.0.1",
    "homepage": "http://github.com/wearefractal/deprecated",
    "repository": "git://github.com/wearefractal/deprecated.git",
    "author": "Fractal <contact@wearefractal.com> (http://wearefractal.com/)",
    "main": "./index.js",
    "dependencies": {},
    "devDependencies": {
        "mocha": "~1.17.0",
        "should": "~3.1.0",
        "mocha-lcov-reporter": "~0.0.1",
        "coveralls": "~2.6.1",
        "istanbul": "~0.2.3",
        "rimraf": "~2.2.5",
        "jshint": "~2.4.1"
    },
    "scripts": {
        "test": "mocha --reporter spec && jshint",
        "coveralls": "istanbul cover _mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | coveralls && rm -rf ./coverage"
    },
    "engines": {
        "node": ">= 0.9"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/wearefractal/deprecated/raw/master/LICENSE"
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
