# npmdoc-screenshot-stream

#### basic api documentation for  [screenshot-stream (v4.1.0)](https://github.com/kevva/screenshot-stream#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-screenshot-stream.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-screenshot-stream) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-screenshot-stream.svg)](https://travis-ci.org/npmdoc/node-npmdoc-screenshot-stream)

#### Capture screenshot of a website and return it as a stream

[![NPM](https://nodei.co/npm/screenshot-stream.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/screenshot-stream)

- [https://npmdoc.github.io/node-npmdoc-screenshot-stream/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-screenshot-stream/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-screenshot-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-screenshot-stream/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-screenshot-stream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-screenshot-stream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kevin Mårtensson",
        "url": "github.com/kevva"
    },
    "bugs": {
        "url": "https://github.com/kevva/screenshot-stream/issues"
    },
    "dependencies": {
        "base64-stream": "^0.1.2",
        "byline": "^4.2.1",
        "object-assign": "^4.0.1",
        "parse-cookie-phantomjs": "^1.0.0",
        "phantom-bridge": "^2.0.0"
    },
    "description": "Capture screenshot of a website and return it as a stream",
    "devDependencies": {
        "ava": "*",
        "cookie": "^0.2.3",
        "get-port": "^2.1.0",
        "get-stream": "^1.1.0",
        "image-size": "^0.4.0",
        "is-jpg": "^1.0.0",
        "is-png": "^1.0.0",
        "pify": "^2.3.0",
        "png-js": "^0.1.1",
        "rfpify": "^1.0.0",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "cd876a206a57c3b1d452a40a3b68420f45e7c5c9",
        "tarball": "https://registry.npmjs.org/screenshot-stream/-/screenshot-stream-4.1.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "index.js",
        "stream.js"
    ],
    "gitHead": "dfc8efc3291e728aa4bff23217e2368a5ae6860b",
    "homepage": "https://github.com/kevva/screenshot-stream#readme",
    "keywords": [
        "image",
        "page",
        "phantom",
        "phantomjs",
        "resolution",
        "screen",
        "screenshot",
        "size",
        "stream",
        "url"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "kevva"
        },
        {
            "name": "samverschueren"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "screenshot-stream",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kevva/screenshot-stream.git"
    },
    "scripts": {
        "test": "xo && ava"
    },
    "version": "4.1.0",
    "xo": {
        "esnext": true,
        "overrides": [
            {
                "files": "stream.js",
                "esnext": false,
                "rules": {
                    "import/no-extraneous-dependencies": 0,
                    "import/no-unresolved": 0
                }
            }
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
