# npmtest-compression

#### basic test coverage for  [compression (v1.6.2)](https://github.com/expressjs/compression#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-compression.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-compression) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-compression.svg)](https://travis-ci.org/npmtest/node-npmtest-compression)

#### Node.js compression middleware

[![NPM](https://nodei.co/npm/compression.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/compression)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-compression/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-compression/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-compression/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-compression/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-compression/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-compression/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-compression/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-compression/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-compression/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-compression/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-compression/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-compression/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-compression/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-compression/build/test-report.html](https://npmtest.github.io/node-npmtest-compression/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-compression/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-compression/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-compression/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-compression/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-compression/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-compression/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-compression/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-compression/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/expressjs/compression/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {
        "accepts": "~1.3.3",
        "bytes": "2.3.0",
        "compressible": "~2.0.8",
        "debug": "~2.2.0",
        "on-headers": "~1.0.1",
        "vary": "~1.1.0"
    },
    "description": "Node.js compression middleware",
    "devDependencies": {
        "eslint": "2.9.0",
        "eslint-config-standard": "5.3.1",
        "eslint-plugin-promise": "1.1.0",
        "eslint-plugin-standard": "1.3.2",
        "istanbul": "0.4.3",
        "mocha": "2.4.5",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "cceb121ecc9d09c52d7ad0c3350ea93ddd402bc3",
        "tarball": "https://registry.npmjs.org/compression/-/compression-1.6.2.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "b9c63ced82b9f719cd5d9fd250c8432b00752d89",
    "homepage": "https://github.com/expressjs/compression#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "compression",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/compression.git"
    },
    "scripts": {
        "lint": "eslint **/*.js",
        "test": "mocha --check-leaks --reporter spec --bail",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --check-leaks --reporter dot",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --check-leaks --reporter spec"
    },
    "version": "1.6.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
