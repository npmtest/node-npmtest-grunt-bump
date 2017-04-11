# test coverage for  [grunt-bump (v0.8.0)](https://github.com/vojtajina/grunt-bump)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-bump.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-bump) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-bump.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-bump)
#### Bump package version

[![NPM](https://nodei.co/npm/grunt-bump.png?downloads=true)](https://www.npmjs.com/package/grunt-bump)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-bump/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-bump/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-bump/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-bump/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-bump/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-bump/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-bump/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-bump/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-grunt-bump/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-bump/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-grunt-bump%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-bump/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-bump/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-grunt-bump%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-bump/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-bump/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-bump/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vojta Jína",
        "email": "vojta.jina@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/vojtajina/grunt-bump/issues"
    },
    "contributors": [
        {
            "name": "Vojta Jina",
            "email": "vojta.jina@gmail.com"
        },
        {
            "name": "Mathias Paumgarten",
            "email": "paumgarten@soapcreative.com"
        },
        {
            "name": "Elfrey Shira",
            "email": "elfrey.shira@opower.com"
        },
        {
            "name": "adam j. sontag",
            "email": "ajpiano@ajpiano.com"
        },
        {
            "name": "Jonas Rabbe",
            "email": "jonas.rabbe@gmail.com"
        },
        {
            "name": "travis4all",
            "email": "travis4all@diamon.dz"
        },
        {
            "name": "Jarrett Drouillard",
            "email": "jarrett@thestyl.us"
        },
        {
            "name": "Jason Diamond",
            "email": "jason@diamond.name"
        },
        {
            "name": "Joe Mills",
            "email": "mills.joe@gmail.com"
        },
        {
            "name": "Mathias Paumgarten",
            "email": "mail@mathias-paumgarten.com"
        },
        {
            "name": "Mayhem",
            "email": "stepien.nicolas@gmail.com"
        },
        {
            "name": "Michael Hellein",
            "email": "themichaek@gmail.com"
        },
        {
            "name": "Mike Schechter",
            "email": "mschechter@2u.com"
        },
        {
            "name": "Mário Gonçalves",
            "email": "mario.mc.goncalves@gmail.com"
        },
        {
            "name": "Nikolay Vasilchuk",
            "email": "Anonym.tsk@gmail.com"
        },
        {
            "name": "Nils Winkler",
            "email": "nils.winkler@sungard.com"
        },
        {
            "name": "RobinQu",
            "email": "robinqu@gmail.com"
        },
        {
            "name": "Scott Davis",
            "email": "stdavis@utah.gov"
        },
        {
            "name": "Snugug",
            "email": "snugug@gmail.com"
        },
        {
            "name": "Swen Wenzel",
            "email": "swenzel@uos.de"
        },
        {
            "name": "Tunghsiao Liu",
            "email": "t@sparanoid.com"
        },
        {
            "name": "Vishwanath",
            "email": "vishwanath@tinyowl.co.in"
        },
        {
            "name": "angleman",
            "email": "angleman@users.noreply.github.com"
        },
        {
            "name": "cattail",
            "email": "zhongchiyu@gmail.com"
        },
        {
            "name": "Adam Biggs",
            "email": "adam.biggs@lightmaker.com"
        },
        {
            "name": "ylesaout",
            "email": "ylesaout@gmail.com"
        },
        {
            "name": "Arnold Daniels",
            "email": "arnold@jasny.net"
        },
        {
            "name": "Braden Kelley",
            "email": "redbmk@gmail.com"
        },
        {
            "name": "Christopher Van",
            "email": "cvan@mozilla.com"
        },
        {
            "name": "Christopher Van",
            "email": "cvan@users.noreply.github.com"
        },
        {
            "name": "Freddy Knuth",
            "email": "freddy.knuth@rackspace.com"
        },
        {
            "name": "Gavin",
            "email": "gavin@kodekoan.com"
        }
    ],
    "dependencies": {
        "semver": "^5.1.0"
    },
    "description": "Bump package version",
    "devDependencies": {
        "grunt": "^1.0.1",
        "grunt-auto-release": "^0.0.6",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-nodeunit": "^1.0.0",
        "grunt-conventional-changelog": "^1.2.0",
        "grunt-npm": "^0.0.2",
        "load-grunt-tasks": "^3.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d3ffe0cf3cf0b38e09607b78538f42a531eafe55",
        "tarball": "https://registry.npmjs.org/grunt-bump/-/grunt-bump-0.8.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "54ed28e9a6574db213d609ef3ad58ca2437b71d4",
    "homepage": "https://github.com/vojtajina/grunt-bump",
    "keywords": [
        "gruntplugin"
    ],
    "license": "MIT",
    "main": "tasks/bump.js",
    "maintainers": [
        {
            "name": "vojtajina",
            "email": "vojta.jina@gmail.com"
        },
        {
            "name": "eddiemonge",
            "email": "eddie+npm@eddiemonge.com"
        }
    ],
    "name": "grunt-bump",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=1.0.1"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/vojtajina/grunt-bump.git"
    },
    "scripts": {
        "release-major": "grunt release:major",
        "release-minor": "grunt release:minor",
        "release-patch": "grunt release:patch",
        "test": "grunt nodeunit"
    },
    "version": "0.8.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
