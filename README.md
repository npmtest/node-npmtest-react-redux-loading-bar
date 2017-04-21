# npmtest-react-redux-loading-bar

#### basic test coverage for  [react-redux-loading-bar (v2.8.1)](https://github.com/mironov/react-redux-loading-bar)  [![npm package](https://img.shields.io/npm/v/npmtest-react-redux-loading-bar.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-redux-loading-bar) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-redux-loading-bar.svg)](https://travis-ci.org/npmtest/node-npmtest-react-redux-loading-bar)

#### Simple Loading Bar for Redux and React

[![NPM](https://nodei.co/npm/react-redux-loading-bar.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-redux-loading-bar)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-redux-loading-bar/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-redux-loading-bar/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/test-report.html](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-redux-loading-bar/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-redux-loading-bar/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-redux-loading-bar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-redux-loading-bar/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-redux-loading-bar/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-redux-loading-bar",
    "version": "2.8.1",
    "description": "Simple Loading Bar for Redux and React",
    "main": "build/index.js",
    "typings": "index.d.ts",
    "scripts": {
        "build": "'npm bin'/babel src -d build",
        "build:watch": "npm run build -- --watch",
        "lint": "'npm bin'/eslint src/ spec/",
        "test": "'npm bin'/mocha --compilers js:babel-core/register spec/",
        "test:watch": "npm run test -- --watch",
        "test:coverage": "'npm bin'/istanbul cover -x 'spec/**' 'npm bin'/_mocha -- -u exports --compilers js:babel-register spec/",
        "test:coveralls": "npm run test:coverage && node ./node_modules/coveralls/bin/coveralls.js < coverage/lcov.info",
        "pkgfiles": "pkgfiles"
    },
    "repository": {
        "type": "git",
        "url": "mironov/react-redux-loading-bar"
    },
    "keywords": [
        "react",
        "redux",
        "loading",
        "loading-bar",
        "progress",
        "progress-bar",
        "react-component"
    ],
    "author": "Anton Mironov (ant.mironov@gmail.com)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/mironov/react-redux-loading-bar/issues"
    },
    "homepage": "https://github.com/mironov/react-redux-loading-bar",
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0",
        "react-redux": "^3.0.0 || ^4.0.0 || ^5.0.0",
        "redux": "^3.0.0"
    },
    "devDependencies": {
        "@types/react": "^0.14.55",
        "babel-cli": "^6.7.7",
        "babel-core": "^6.7.7",
        "babel-eslint": "^7.1.1",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-2": "^6.5.0",
        "coveralls": "^2.11.9",
        "enzyme": "^2.2.0",
        "eslint": "^3.11.1",
        "eslint-config-airbnb": "^8.0.0",
        "eslint-plugin-import": "^1.6.1",
        "eslint-plugin-jsx-a11y": "^2.2.3",
        "eslint-plugin-react": "^5.0.1",
        "expect": "^1.18.0",
        "expect-jsx": "^2.5.1",
        "istanbul": "^1.0.0-alpha.2",
        "jsdom": "^9.11.0",
        "lolex": "^1.4.0",
        "mocha": "^3.2.0",
        "pkgfiles": "^2.3.0",
        "react": "^15.4.1",
        "react-addons-test-utils": "^15.4.1",
        "react-dom": "^15.4.1",
        "react-redux": "^4.4.5",
        "redux": "^3.5.2"
    },
    "dependencies": {
        "prop-types": "^15.5.6"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
