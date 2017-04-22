# npmtest-mdns

#### basic test coverage for  [mdns (v2.3.3)](http://agnat.github.com/node_mdns)  [![npm package](https://img.shields.io/npm/v/npmtest-mdns.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mdns) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mdns.svg)](https://travis-ci.org/npmtest/node-npmtest-mdns)

#### multicast DNS service discovery

[![NPM](https://nodei.co/npm/mdns.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mdns)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mdns/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mdns/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mdns/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mdns/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mdns/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mdns/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mdns/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mdns/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mdns/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mdns/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mdns/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mdns/build/test-report.html](https://npmtest.github.io/node-npmtest-mdns/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mdns/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mdns/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mdns/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mdns/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mdns/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mdns/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mdns/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mdns/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mdns",
    "version": "2.3.3",
    "description": "multicast DNS service discovery",
    "main": "./lib/mdns.js",
    "scripts": {
        "test": "node utils/testrun"
    },
    "keywords": [
        "zeroconf",
        "bonjour",
        "dns_sd",
        "mDNSResponder"
    ],
    "devDependencies": {
        "ejs": "*",
        "less": "*",
        "mkdirp": "*",
        "nopt": "*",
        "slide": "*",
        "glob": "*",
        "ncp": "*",
        "minimatch": "*",
        "proxyquire": "^1.7.3"
    },
    "repository": {
        "type": "git",
        "url": "http://github.com/agnat/node_mdns.git"
    },
    "homepage": "http://agnat.github.com/node_mdns",
    "bugs": {
        "url": "http://github.com/agnat/node_mdns/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/agnat/node_mdns/raw/master/LICENSE"
        }
    ],
    "author": {
        "name": "David Siegel",
        "github": "agnat"
    },
    "contributors": [
        {
            "name": "Orlando Vazquez",
            "url": "http://or.lan.do/",
            "github": "orlandov"
        },
        {
            "name": "Ryan Dahl",
            "url": "http://four.livejournal.com/",
            "github": "ry"
        },
        {
            "name": "Dominic Tarr",
            "url": "http://twitter.com/dominictarr",
            "github": "dominictarr"
        },
        {
            "name": "Emil Stenqvist",
            "github": "emilisto"
        },
        {
            "name": "Toby Ealden",
            "github": "TobyEalden"
        },
        {
            "name": "Cong Liu",
            "github": "ghostoy"
        },
        {
            "name": "Tian Zhang",
            "github": "KhaosT"
        }
    ],
    "dependencies": {
        "bindings": "~1.2.1",
        "nan": "~2.3.0"
    },
    "gypfile": true,
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
