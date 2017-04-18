# npmdoc-barbeque

#### api documentation for  [barbeque (v0.2.4)](https://github.com/pilwon/barbeque)  [![npm package](https://img.shields.io/npm/v/npmdoc-barbeque.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-barbeque) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-barbeque.svg)](https://travis-ci.org/npmdoc/node-npmdoc-barbeque)

#### Redis-based task queue library for Node.js, inspired by Celery and Kue.

[![NPM](https://nodei.co/npm/barbeque.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/barbeque)

- [https://npmdoc.github.io/node-npmdoc-barbeque/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-barbeque/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-barbeque/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-barbeque/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-barbeque/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-barbeque/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pilwon Huh"
    },
    "bin": {
        "barbeque": "./bin/bbq",
        "bbq": "./bin/bbq"
    },
    "bugs": {
        "url": "https://github.com/pilwon/barbeque/issues"
    },
    "dependencies": {
        "async": "0.2.9",
        "browserify-middleware": "1.19.0",
        "colors": "0.6.2",
        "express": "3.4.4",
        "hbs": "2.4.0",
        "less-middleware": "0.1.14",
        "lodash": "2.2.1",
        "moment": "2.4.0",
        "redis": "0.9.0",
        "socket.io": "0.9.16",
        "uuid": "1.4.1"
    },
    "description": "Redis-based task queue library for Node.js, inspired by Celery and Kue.",
    "devDependencies": {
        "grunt": "0.4.1",
        "grunt-contrib-jshint": "0.7.1",
        "grunt-contrib-watch": "0.4.3",
        "matchdep": "0.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3aaefd3c1b24ec7d8a3ceddca7a92034a5ef3ad9",
        "tarball": "https://registry.npmjs.org/barbeque/-/barbeque-0.2.4.tgz"
    },
    "homepage": "https://github.com/pilwon/barbeque",
    "keywords": [
        "barbeque",
        "barbecue",
        "bbq",
        "task",
        "job",
        "queue",
        "kue",
        "schedule",
        "delay",
        "worker",
        "redis",
        "db",
        "pubsub"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "pilwon"
        }
    ],
    "name": "barbeque",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/pilwon/barbeque.git"
    },
    "scripts": {
        "prepublish": "npm prune"
    },
    "version": "0.2.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
