# npmtest-react-a11y

#### basic test coverage for  [react-a11y (v0.3.3)](https://github.com/reactjs/react-a11y/blob/latest/README.md)  [![npm package](https://img.shields.io/npm/v/npmtest-react-a11y.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-a11y) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-a11y.svg)](https://travis-ci.org/npmtest/node-npmtest-react-a11y)

#### Warns about potential accessibility issues with your React elements.

[![NPM](https://nodei.co/npm/react-a11y.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-a11y)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-a11y/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-a11y/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-a11y/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-a11y/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-a11y/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-a11y/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-a11y/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-a11y/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-a11y/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-a11y/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-a11y/build/test-report.html](https://npmtest.github.io/node-npmtest-react-a11y/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-a11y/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-a11y/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-a11y/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-a11y/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-a11y/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-a11y/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Ryan Florence",
        "Todd Kloots",
        "Angus Croll"
    ],
    "bugs": {
        "url": "https://github.com/reactjs/react-a11y/issues"
    },
    "dependencies": {
        "object.assign": "^4.0.3"
    },
    "description": "Warns about potential accessibility issues with your React elements.",
    "devDependencies": {
        "babel": "^5.2.17",
        "babel-core": "^5.2.17",
        "babel-loader": "^5.0.0",
        "jsx-loader": "^0.12.2",
        "jsxhint": "^0.8.1",
        "karma": "^0.13.3",
        "karma-chrome-launcher": "^0.1.7",
        "karma-cli": "0.0.4",
        "karma-firefox-launcher": "^0.1.3",
        "karma-mocha": "^0.1.10",
        "karma-sourcemap-loader": "^0.3.2",
        "karma-webpack": "^1.7.0",
        "mocha": "^2.0.1",
        "react": "^0.12 || ^0.13 || ^0.14",
        "react-dom": "^0.14.7",
        "rf-release": "0.4.0",
        "webpack": "^1.4.13"
    },
    "directories": {},
    "dist": {
        "shasum": "310edd466b81371d76cd1dc9a5d90758dbac3840",
        "tarball": "https://registry.npmjs.org/react-a11y/-/react-a11y-0.3.3.tgz"
    },
    "gitHead": "64fe62cfd03f9bbd044560034f859c35296b9fed",
    "homepage": "https://github.com/reactjs/react-a11y/blob/latest/README.md",
    "keywords": [
        "accessibility",
        "react",
        "a11y"
    ],
    "license": "MIT",
    "main": "./dist/index.js",
    "maintainers": [
        {
            "name": "angus-c"
        },
        {
            "name": "ryanflorence"
        },
        {
            "name": "toddkloots"
        },
        {
            "name": "wyattdanger"
        }
    ],
    "name": "react-a11y",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reactjs/react-a11y.git"
    },
    "scripts": {
        "prepublish": "babel lib --out-dir dist",
        "release": "release",
        "test": "jsxhint . && karma start --single-run",
        "watch-tests": "npm test -- --watch"
    },
    "tags": [
        "accessibility",
        "react",
        "a11y"
    ],
    "version": "0.3.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
