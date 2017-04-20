# npmdoc-yo

#### api documentation for  [yo (v1.8.5)](http://yeoman.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-yo.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-yo) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-yo.svg)](https://travis-ci.org/npmdoc/node-npmdoc-yo)

#### CLI tool for running Yeoman generators

[![NPM](https://nodei.co/npm/yo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/yo)

- [https://npmdoc.github.io/node-npmdoc-yo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-yo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-yo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-yo/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-yo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-yo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yeoman"
    },
    "bin": {
        "yo": "lib/cli.js",
        "yo-complete": "lib/completion/index.js"
    },
    "bugs": {
        "url": "https://github.com/yeoman/yo/issues"
    },
    "dependencies": {
        "async": "^1.0.0",
        "chalk": "^1.0.0",
        "cli-list": "^0.1.1",
        "configstore": "^1.0.0",
        "cross-spawn": "^3.0.1",
        "figures": "^1.3.5",
        "fullname": "^2.0.0",
        "got": "^5.0.0",
        "humanize-string": "^1.0.0",
        "inquirer": "^0.11.0",
        "insight": "^0.7.0",
        "lodash": "^3.2.0",
        "meow": "^3.0.0",
        "npm-keyword": "^4.1.0",
        "opn": "^3.0.2",
        "package-json": "^2.1.0",
        "parse-help": "^0.1.1",
        "read-pkg-up": "^1.0.1",
        "repeating": "^2.0.0",
        "root-check": "^1.0.0",
        "sort-on": "^1.0.0",
        "string-length": "^1.0.0",
        "tabtab": "^1.3.0",
        "titleize": "^1.0.0",
        "update-notifier": "^0.6.0",
        "user-home": "^2.0.0",
        "yeoman-character": "^1.0.0",
        "yeoman-doctor": "^2.0.0",
        "yeoman-environment": "^1.6.1",
        "yosay": "^1.0.0"
    },
    "description": "CLI tool for running Yeoman generators",
    "devDependencies": {
        "gulp": "^3.6.0",
        "gulp-coveralls": "^0.1.0",
        "gulp-eslint": "^2.0.0",
        "gulp-exclude-gitignore": "^1.0.0",
        "gulp-istanbul": "^0.10.4",
        "gulp-mocha": "^2.0.0",
        "gulp-nsp": "^2.1.0",
        "gulp-plumber": "^1.0.0",
        "mocha": "^2.1.0",
        "mockery": "^1.4.0",
        "nock": "^8.0.0",
        "nsp": "^2.2.0",
        "proxyquire": "^1.0.1",
        "registry-url": "^3.0.0",
        "sinon": "^1.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "776ab9ec79a7882f8d4f7a9e10214fdab050d928",
        "tarball": "https://registry.npmjs.org/yo/-/yo-1.8.5.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "files": [
        "lib"
    ],
    "gitHead": "3be725bd6376ead2c593741da2d374082f673b05",
    "homepage": "http://yeoman.io",
    "keywords": [
        "cli-app",
        "cli",
        "front-end",
        "development",
        "dev",
        "build",
        "web",
        "tool",
        "scaffold",
        "stack",
        "yeoman",
        "generator",
        "generate",
        "app",
        "boilerplate"
    ],
    "license": "BSD-2-Clause",
    "main": "lib",
    "maintainers": [
        {
            "name": "sindresorhus"
        },
        {
            "name": "paulirish"
        },
        {
            "name": "addyosmani"
        },
        {
            "name": "eddiemonge"
        },
        {
            "name": "passy"
        },
        {
            "name": "sboudrias"
        },
        {
            "name": "arthurvr"
        }
    ],
    "name": "yo",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yeoman/yo.git"
    },
    "scripts": {
        "postinstall": "yodoctor",
        "postupdate": "yodoctor",
        "prepublish": "gulp prepublish",
        "test": "gulp"
    },
    "tabtab": {
        "yo": [
            "-f",
            "--force",
            "--version",
            "--no-color",
            "--no-insight",
            "--insight",
            "--generators"
        ]
    },
    "version": "1.8.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
