# npmdoc-gcr

#### api documentation for  [gcr (v3.0.0)](https://github.com/evanlucas/gcr)  [![npm package](https://img.shields.io/npm/v/npmdoc-gcr.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gcr) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gcr.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gcr)

#### A node gitlab-ci-runner

[![NPM](https://nodei.co/npm/gcr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gcr)

- [https://npmdoc.github.io/node-npmdoc-gcr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gcr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gcr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gcr/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gcr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gcr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Evan Lucas"
    },
    "bin": {
        "gcr": "./bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/evanlucas/gcr/issues"
    },
    "dependencies": {
        "argsplit": "~1.0.2",
        "help": "~2.0.0",
        "inquirer": "~0.4.1",
        "mkdirp": "~0.3.5",
        "nconf": "~0.6.9",
        "nopt": "~2.2.0",
        "npmlog": "~0.0.6",
        "os-homedir": "~1.0.0",
        "request": "~2.53.0",
        "rimraf": "~2.2.6",
        "slide": "~1.1.5",
        "url-join": "0.0.1",
        "which": "~1.0.5"
    },
    "description": "A node gitlab-ci-runner",
    "devDependencies": {
        "istanbul": "~0.3.5",
        "mocha": "~2.1.0",
        "should": "~4.6.5",
        "sinon": "~1.12.2"
    },
    "directories": {},
    "dist": {
        "shasum": "9a44d5e258dadc1d614be50acc92af18787b6035",
        "tarball": "https://registry.npmjs.org/gcr/-/gcr-3.0.0.tgz"
    },
    "gitHead": "76636754208d235ef26c893ace891503666f8f20",
    "homepage": "https://github.com/evanlucas/gcr",
    "keywords": [
        "gitlab",
        "ci",
        "runner"
    ],
    "license": "MIT",
    "main": "./lib/gcr.js",
    "maintainers": [
        {
            "name": "evanlucas"
        }
    ],
    "name": "gcr",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/evanlucas/gcr.git"
    },
    "scripts": {
        "cover": "NODE_ENV=test istanbul cover _mocha -- -R spec",
        "test": "mocha -R spec"
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
