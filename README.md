# npmtest-victory

#### basic test coverage for  [victory (v0.18.4)](https://github.com/formidablelabs/victory)  [![npm package](https://img.shields.io/npm/v/npmtest-victory.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-victory) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-victory.svg)](https://travis-ci.org/npmtest/node-npmtest-victory)

#### Data viz for React

[![NPM](https://nodei.co/npm/victory.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/victory)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-victory/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-victory/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-victory/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-victory/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-victory/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-victory/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-victory/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-victory/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-victory/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-victory/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-victory/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-victory/build/test-report.html](https://npmtest.github.io/node-npmtest-victory/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-victory/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-victory/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-victory/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-victory/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-victory/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-victory/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-victory/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-victory/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "victory",
    "version": "0.18.4",
    "description": "Data viz for React",
    "keywords": [
        "data visualization",
        "React",
        "d3",
        "charting"
    ],
    "main": "lib/index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/formidablelabs/victory.git"
    },
    "engines": {
        "npm": ">=2.0.0"
    },
    "author": "Formidable",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/formidablelabs/victory/issues"
    },
    "homepage": "https://github.com/formidablelabs/victory",
    "scripts": {
        "postinstall": "cd lib || builder run npm:postinstall || (echo 'POSTINSTALL FAILED: If using npm v2, please upgrade to npm v3. See bug https://github.com/FormidableLabs/builder/issues/35' && exit 1)",
        "preversion": "builder run npm:preversion",
        "postversion": "builder run npm:postversion",
        "postpublish": "builder run npm:postpublish",
        "start": "builder run dev",
        "test": "builder run check",
        "version": "builder run npm:version"
    },
    "dependencies": {
        "victory-chart": "^18.2.0",
        "victory-core": "^14.1.0",
        "victory-pie": "^10.3.0"
    },
    "devDependencies": {
        "builder-victory-component-dev": "^3.1.0",
        "chai": "^3.2.0",
        "lodash": "^4.12.0",
        "mocha": "^2.3.3",
        "react": "^15.1.0",
        "react-addons-test-utils": "^15.1.0",
        "react-dom": "^15.1.0",
        "sinon": "^1.17.2",
        "sinon-chai": "^2.8.0",
        "builder": "^3.1.0",
        "builder-victory-component": "^3.1.0"
    },
    "publishr": {
        "dependencies": [
            "^builder"
        ],
        "files": {
            ".npmignore": ".npmignore.publishr"
        }
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
