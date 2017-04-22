# npmdoc-iphone-inline-video

#### api documentation for  [iphone-inline-video (v2.0.2)](https://github.com/bfred-it/iphone-inline-video#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-iphone-inline-video.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-iphone-inline-video) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-iphone-inline-video.svg)](https://travis-ci.org/npmdoc/node-npmdoc-iphone-inline-video)

#### Make videos playable inline on the iPhone (prevents automatic fullscreen)

[![NPM](https://nodei.co/npm/iphone-inline-video.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/iphone-inline-video)

- [https://npmdoc.github.io/node-npmdoc-iphone-inline-video/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-iphone-inline-video/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-iphone-inline-video/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-iphone-inline-video/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-iphone-inline-video/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-iphone-inline-video/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Federico Brigante",
        "url": "bfred.it"
    },
    "bugs": {
        "url": "https://github.com/bfred-it/iphone-inline-video/issues"
    },
    "dependencies": {
        "intervalometer": "^1.0.0",
        "poor-mans-symbol": "^1.0.1"
    },
    "description": "Make videos playable inline on the iPhone (prevents automatic fullscreen)",
    "devDependencies": {
        "bfred-npm-bundler": "^8.0.3",
        "browser-sync": "^2.18.7",
        "npm-run-all": "^4.0.1",
        "onchange": "^3.2.1",
        "xo": "^0.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "7e721df07c891b40b60899c5c34a4f542d332f11",
        "tarball": "https://registry.npmjs.org/iphone-inline-video/-/iphone-inline-video-2.0.2.tgz"
    },
    "files": [
        "dist"
    ],
    "gitHead": "6a2137ad8e269905d63cd94e640f8459a389ed5a",
    "homepage": "https://github.com/bfred-it/iphone-inline-video#readme",
    "jsnext:main": "dist/iphone-inline-video.es-modules.js",
    "keywords": [
        "browser",
        "iphone",
        "ios",
        "play",
        "video",
        "inline",
        "fullscreen",
        "full screen",
        "ipod",
        "autoplay",
        "multiple",
        "audio",
        "sound",
        "canvas",
        "gif"
    ],
    "license": "MIT",
    "main": "dist/iphone-inline-video.common-js.js",
    "maintainers": [
        {
            "name": "bfred-it"
        }
    ],
    "module": "dist/iphone-inline-video.es-modules.js",
    "name": "iphone-inline-video",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bfred-it/iphone-inline-video.git"
    },
    "scripts": {
        "build": "npm-run-all --silent jsfix build:*",
        "build:js": "bfred-npm-bundler iphone-inline-video enableInlineVideo",
        "jsfix": "xo --fix",
        "prepublish": "npm run build",
        "test": "npm run build",
        "version": "npm run build; git add dist",
        "watch": "npm-run-all --parallel --silent watch:*",
        "watch:build": "onchange 'index.js' 'lib/*' -i -- npm run build",
        "watch:server": "browser-sync start --startPath demo --no-ghost-mode --reload-delay 300 --no-open --server --files 'dist/*.browser.js,demo/**'"
    },
    "version": "2.0.2",
    "xo": {
        "ignores": [
            "demo/**"
        ],
        "env": [
            "browser"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
