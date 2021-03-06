# npmdoc-gulp-combine-mq

#### api documentation for  [gulp-combine-mq (v0.4.0)](https://github.com/buildingblocks/gulp-combine-mq)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-combine-mq.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-combine-mq) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-combine-mq.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-combine-mq)

#### Gulp plugin for node-combine-mq

[![NPM](https://nodei.co/npm/gulp-combine-mq.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-combine-mq)

- [https://npmdoc.github.io/node-npmdoc-gulp-combine-mq/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-combine-mq/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-combine-mq/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-combine-mq/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-combine-mq/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-combine-mq/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Building Blocks Ltd"
    },
    "bugs": {
        "url": "https://github.com/buildingblocks/gulp-combine-mq/issues"
    },
    "contributors": [],
    "dependencies": {
        "combine-mq": "^0.7.0",
        "graceful-fs": "^3.0.4",
        "gulp-util": "~2.2.0",
        "map-stream": "^0.1.0",
        "path": "^0.4.9",
        "temp-write": "^1.1.0",
        "through2": "*"
    },
    "description": "Gulp plugin for node-combine-mq",
    "devDependencies": {
        "coveralls": "*",
        "event-stream": "*",
        "gulp": "^3.8.8",
        "istanbul": "*",
        "mocha": "*",
        "mocha-lcov-reporter": "*",
        "should": "~2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "abf48848efe2d5d711ca969c8e923151fbe3bed5",
        "tarball": "https://registry.npmjs.org/gulp-combine-mq/-/gulp-combine-mq-0.4.0.tgz"
    },
    "engines": {
        "node": ">=0.8.0",
        "npm": ">=1.2.10"
    },
    "gitHead": "c1a982242f11136c13f6ee130626654626e13457",
    "homepage": "https://github.com/buildingblocks/gulp-combine-mq",
    "keywords": [
        "gulpplugin",
        "combine",
        "media queries",
        "combine media queries",
        "CSS",
        "Less",
        "Sass"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://building-blocks.mit-license.org"
        }
    ],
    "maintainers": [
        {
            "name": "spacedawwwg"
        },
        {
            "name": "furzeface"
        }
    ],
    "name": "gulp-combine-mq",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/buildingblocks/gulp-combine-mq.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "istanbul test _mocha --report html -- test/*.js --reporter spec"
    },
    "version": "0.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
