# npmdoc-nearley

#### api documentation for  [nearley (v2.8.0)](https://github.com/hardmath123/nearley#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-nearley.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nearley) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nearley.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nearley)

#### Simple, fast, powerful parser toolkit for JavaScript.

[![NPM](https://nodei.co/npm/nearley.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nearley)

- [https://npmdoc.github.io/node-npmdoc-nearley/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nearley/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nearley/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nearley/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nearley/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nearley/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hardmath123"
    },
    "bin": {
        "nearleyc": "bin/nearleyc.js",
        "nearley-test": "bin/nearley-test.js",
        "nearley-unparse": "bin/nearley-unparse.js",
        "nearley-railroad": "bin/nearley-railroad.js"
    },
    "bugs": {
        "url": "https://github.com/hardmath123/nearley/issues"
    },
    "contributors": "https://github.com/Hardmath123/nearley/graphs/contributors",
    "dependencies": {
        "nomnom": "~1.6.2",
        "railroad-diagrams": "^1.0.0",
        "randexp": "^0.4.2"
    },
    "description": "Simple, fast, powerful parser toolkit for JavaScript.",
    "devDependencies": {
        "benchmark": "^2.1.3",
        "chai": "^3.4.1",
        "coffee-script": "^1.10.0",
        "microtime": "^2.1.2",
        "mocha": "^2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "7f88b503e3b373503f5c7e5b3b52bf134c86145b",
        "tarball": "https://registry.npmjs.org/nearley/-/nearley-2.8.0.tgz"
    },
    "gitHead": "cbd2a7bfe7319ac3a1818ec07b56a2991306197d",
    "homepage": "https://github.com/hardmath123/nearley#readme",
    "keywords": [
        "parser",
        "parse",
        "generator",
        "compiler",
        "compile",
        "grammar",
        "language"
    ],
    "license": "MIT",
    "main": "lib/nearley.js",
    "maintainers": [
        {
            "name": "hardmath123"
        }
    ],
    "name": "nearley",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hardmath123/nearley.git"
    },
    "scripts": {
        "benchmark": "node test/benchmark.js",
        "bootstrap": "node bin/nearleyc.js lib/nearley-language-bootstrapped.ne >lib/nearley-language-bootstrapped.js.new && mv lib/nearley-language-bootstrapped.js.new lib/nearley-language-bootstrapped.js",
        "test": "mocha test/launch.js"
    },
    "version": "2.8.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
