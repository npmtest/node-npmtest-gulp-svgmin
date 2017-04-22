# npmtest-gulp-svgmin

#### basic test coverage for  [gulp-svgmin (v1.2.3)](https://github.com/ben-eb/gulp-svgmin)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-svgmin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-svgmin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-svgmin.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-svgmin)

#### Minify SVG files with gulp.

[![NPM](https://nodei.co/npm/gulp-svgmin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-svgmin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-svgmin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-svgmin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-svgmin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-svgmin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-svgmin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-svgmin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-svgmin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-svgmin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-svgmin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-svgmin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-svgmin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-svgmin/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-svgmin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-svgmin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-svgmin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-svgmin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-svgmin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-svgmin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-svgmin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-svgmin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-svgmin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Briggs",
        "url": "http://beneb.info"
    },
    "ava": {
        "require": "babel-register"
    },
    "bugs": {
        "url": "https://github.com/ben-eb/gulp-svgmin/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.4",
        "svgo": "^0.7.0"
    },
    "description": "Minify SVG files with gulp.",
    "devDependencies": {
        "ava": "^0.16.0",
        "babel-cli": "^6.5.1",
        "babel-core": "^6.5.2",
        "babel-plugin-add-module-exports": "^0.2.0",
        "babel-preset-es2015": "^6.5.0",
        "babel-preset-es2015-loose": "^7.0.0",
        "babel-preset-stage-0": "^6.5.0",
        "babel-register": "^6.9.0",
        "chai": "~3.5.0",
        "coveralls": "^2.11.6",
        "del-cli": "^0.2.0",
        "eslint": "^3.0.0",
        "eslint-config-cssnano": "^3.0.0",
        "eslint-plugin-babel": "^3.3.0",
        "eslint-plugin-import": "^1.10.2",
        "nyc": "^8.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "88947b132e15b2de43d1dbccb30455319c5e50b5",
        "tarball": "https://registry.npmjs.org/gulp-svgmin/-/gulp-svgmin-1.2.3.tgz"
    },
    "eslintConfig": {
        "extends": "cssnano"
    },
    "files": [
        "LICENSE-MIT",
        "dist"
    ],
    "gitHead": "d0386b8a268328e44f4dd121216351675bb58f70",
    "homepage": "https://github.com/ben-eb/gulp-svgmin",
    "keywords": [
        "gulpplugin",
        "minify",
        "svg",
        "svgo"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "beneb"
        }
    ],
    "name": "gulp-svgmin",
    "nyc": {
        "exclude": [
            "node_modules",
            "**/__tests__"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ben-eb/gulp-svgmin.git"
    },
    "scripts": {
        "prepublish": "del-cli dist && BABEL_ENV=publish babel src --out-dir dist --ignore /__tests__/",
        "pretest": "eslint src",
        "test": "nyc ava src/__tests__",
        "test-012": "nyc ava src/__tests__"
    },
    "version": "1.2.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
