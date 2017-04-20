# npmdoc-uglifyify

#### api documentation for  uglifyify (v3.0.4)  [![npm package](https://img.shields.io/npm/v/npmdoc-uglifyify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-uglifyify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-uglifyify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-uglifyify)

#### A browserify transform which minifies your code using UglifyJS2

[![NPM](https://nodei.co/npm/uglifyify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/uglifyify)

- [https://npmdoc.github.io/node-npmdoc-uglifyify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-uglifyify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-uglifyify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-uglifyify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-uglifyify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-uglifyify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "uglifyify",
    "version": "3.0.4",
    "description": "A browserify transform which minifies your code using UglifyJS2",
    "main": "index.js",
    "dependencies": {
        "convert-source-map": "~1.1.0",
        "extend": "^1.2.1",
        "minimatch": "^3.0.2",
        "through": "~2.3.4",
        "uglify-js": "2.x.x"
    },
    "devDependencies": {
        "bl": "^0.9.3",
        "browserify": "^8.1.1",
        "from2": "^1.3.0",
        "tap-spec": "^2.1.2",
        "tape": "^3.2.0",
        "wrap-stream": "^2.0.0"
    },
    "scripts": {
        "test": "node test | tap-spec"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/hughsk/uglifyify.git"
    },
    "keywords": [
        "uglify",
        "minify",
        "compress",
        "compile",
        "browserify",
        "transform",
        "stream"
    ],
    "author": "Hugh Kennedy <hughskennedy@gmail.com> (http://hughskennedy.com/)",
    "license": "MIT",
    "readmeFilename": "README.md"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
