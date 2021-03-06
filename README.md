# npmdoc-react-tabs

#### basic api documentation for  [react-tabs (v0.8.3)](https://github.com/reactjs/react-tabs)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-tabs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-tabs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-tabs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-tabs)

#### React tabs component

[![NPM](https://nodei.co/npm/react-tabs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-tabs)

- [https://npmdoc.github.io/node-npmdoc-react-tabs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-tabs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-tabs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-tabs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-tabs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-tabs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt Zabriskie"
    },
    "bugs": {
        "url": "https://github.com/reactjs/react-tabs/issues"
    },
    "dependencies": {
        "classnames": "^2.2.0",
        "create-react-class": "^15.5.2",
        "js-stylesheet": "^0.0.1",
        "prop-types": "^15.5.8"
    },
    "description": "React tabs component",
    "devDependencies": {
        "babel-cli": "^6.9.0",
        "babel-core": "^6.9.1",
        "babel-eslint": "^7.0.0",
        "babel-jest": "^16.0.0",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-1": "^6.5.0",
        "cross-env": "^3.0.0",
        "enzyme": "^2.3.0",
        "eslint": "^2.11.1",
        "eslint-config-airbnb": "^9.0.1",
        "eslint-plugin-import": "^1.8.0",
        "eslint-plugin-jsx-a11y": "^1.2.2",
        "eslint-plugin-react": "^5.1.1",
        "jest-cli": "^16.0.0",
        "react": "^15.0.0",
        "react-addons-test-utils": "^15.0.0",
        "react-dom": "^15.0.0",
        "react-modal": "^1.3.0",
        "react-test-renderer": "^15.5.4",
        "rimraf": "^2.5.2",
        "webpack": "^1.13.1",
        "webpack-dev-server": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "40bdc14c725c4dbf4befdfddf1153a93af92a894",
        "tarball": "https://registry.npmjs.org/react-tabs/-/react-tabs-0.8.3.tgz"
    },
    "files": [
        "dist",
        "lib"
    ],
    "gitHead": "8d6744b369fa81e5f47bd84e82b079e837288fd4",
    "homepage": "https://github.com/reactjs/react-tabs",
    "jest": {
        "testPathDirs": [
            "src"
        ]
    },
    "keywords": [
        "react",
        "tabs",
        "a11y",
        "react-component"
    ],
    "license": "MIT",
    "main": "lib/main.js",
    "maintainers": [
        {
            "name": "danez"
        },
        {
            "name": "mzabriskie"
        }
    ],
    "name": "react-tabs",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.7 || ^15.0.0",
        "react-dom": "^0.14.7 || ^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reactjs/react-tabs.git"
    },
    "scripts": {
        "build": "npm run clean && npm run build:commonjs",
        "build:commonjs": "babel src/ --out-dir lib/ --ignore __tests__,__mocks__",
        "build:umd": "webpack --devtool source-map --config webpack.build.js",
        "build:umd:min": "cross-env MINIFY=1 webpack --devtool source-map --config webpack.build.js",
        "bundle": "mkdir -p dist && npm run build:umd && npm run build:umd:min",
        "clean": "rimraf lib",
        "lint": "eslint src",
        "prepublish": "npm run build",
        "preversion": "npm run lint && npm test && npm run build && npm run bundle && git add dist/ && git commit -m 'Publish: build bower distribution'",
        "start": "webpack-dev-server --inline --content-base examples/",
        "test": "jest"
    },
    "version": "0.8.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
