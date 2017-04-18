# npmtest-cesium

#### test coverage for  [cesium (v1.32.1)](http://cesiumjs.org)  [![npm package](https://img.shields.io/npm/v/npmtest-cesium.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cesium) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cesium.svg)](https://travis-ci.org/npmtest/node-npmtest-cesium)

#### Cesium is a JavaScript library for creating 3D globes and 2D maps in a web browser without a plugin.

[![NPM](https://nodei.co/npm/cesium.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cesium)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cesium/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cesium/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cesium/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cesium/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cesium/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cesium/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cesium/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cesium/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cesium/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cesium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cesium/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cesium/build/test-report.html](https://npmtest.github.io/node-npmtest-cesium/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cesium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cesium/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cesium/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cesium/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cesium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cesium/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cesium/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cesium/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Analytical Graphics, Inc.",
        "url": "http://www.agi.com"
    },
    "bugs": {
        "url": "https://github.com/AnalyticalGraphicsInc/cesium/issues"
    },
    "contributors": [
        {
            "name": "Cesium community",
            "url": "https://github.com/AnalyticalGraphicsInc/cesium/blob/master/CONTRIBUTORS.md"
        }
    ],
    "dependencies": {
        "requirejs": "^2.3.2"
    },
    "description": "Cesium is a JavaScript library for creating 3D globes and 2D maps in a web browser without a plugin.",
    "devDependencies": {
        "almond": "^0.3.3",
        "aws-sdk": "^2.18.0",
        "bluebird": "^3.4.6",
        "compressible": "^2.0.9",
        "compression": "^1.6.2",
        "electron": "^1.6.1",
        "event-stream": "^3.3.4",
        "express": "^4.15.0",
        "globby": "^6.1.0",
        "glsl-strip-comments": "^1.0.0",
        "gulp": "^3.9.1",
        "gulp-insert": "^0.5.0",
        "gulp-jshint": "^2.0.4",
        "gulp-rename": "^1.2.2",
        "gulp-replace": "^0.5.4",
        "gulp-tap": "^0.1.3",
        "gulp-zip": "^4.0.0",
        "jasmine-core": "^2.5.2",
        "jsdoc": "^3.4.3",
        "jshint": "^2.9.4",
        "jshint-stylish": "^2.2.1",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-detect-browsers": "^2.2.3",
        "karma-edge-launcher": "^0.2.0",
        "karma-electron": "^5.1.1",
        "karma-firefox-launcher": "^1.0.0",
        "karma-ie-launcher": "^1.0.0",
        "karma-jasmine": "^1.1.0",
        "karma-requirejs": "^1.1.0",
        "karma-safari-launcher": "^1.0.0",
        "karma-spec-reporter": "^0.0.30",
        "mime": "^1.3.4",
        "mkdirp": "^0.5.1",
        "request": "^2.79.0",
        "rimraf": "^2.6.1",
        "yargs": "^7.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "e6abbef3591142a89f7570e1b9f6f9ec78b464bd",
        "tarball": "https://registry.npmjs.org/cesium/-/cesium-1.32.1.tgz"
    },
    "gitHead": "d83607d392a2e92f841f0967eae766735d58ab76",
    "homepage": "http://cesiumjs.org",
    "keywords": [
        "3D",
        "webgl",
        "geospatial",
        "map",
        "globe"
    ],
    "license": "Apache-2.0",
    "maintainers": [
        {
            "name": "analyticalgraphics"
        },
        {
            "name": "bagnell"
        },
        {
            "name": "hpinkos"
        },
        {
            "name": "lilleyse"
        },
        {
            "name": "mramato"
        },
        {
            "name": "pjcozzi"
        },
        {
            "name": "tfili"
        }
    ],
    "name": "cesium",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/AnalyticalGraphicsInc/cesium.git"
    },
    "scripts": {
        "build": "gulp build",
        "build-watch": "gulp build-watch",
        "buildApps": "gulp buildApps",
        "clean": "gulp clean",
        "cloc": "gulp cloc",
        "combine": "gulp combine",
        "combineRelease": "gulp combineRelease",
        "deploy-s3": "gulp deploy-s3",
        "deploy-set-version": "gulp deploy-set-version",
        "deploy-status": "gulp deploy-status",
        "generateDocumentation": "gulp generateDocumentation",
        "generateStubs": "gulp generateStubs",
        "instrumentForCoverage": "gulp instrumentForCoverage",
        "jsHint": "gulp jsHint",
        "jsHint-watch": "gulp jsHint-watch",
        "makeZipFile": "gulp makeZipFile",
        "minify": "gulp minify",
        "minifyRelease": "gulp minifyRelease",
        "release": "gulp release",
        "requirejs": "gulp requirejs",
        "sortRequires": "gulp sortRequires",
        "start": "node server.js",
        "startPublic": "node server.js --public",
        "test": "gulp test",
        "test-all": "gulp test --all",
        "test-non-webgl": "gulp test --exclude WebGL",
        "test-release": "gulp test --release",
        "test-webgl": "gulp test --include WebGL",
        "test-webgl-stub": "gulp test --webglStub",
        "test-webgl-validation": "gulp test --webglValidation"
    },
    "version": "1.32.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
