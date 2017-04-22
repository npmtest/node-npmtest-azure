# npmtest-azure

#### basic test coverage for  [azure (v2.0.0-preview)](http://github.com/azure/azure-sdk-for-node)  [![npm package](https://img.shields.io/npm/v/npmtest-azure.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-azure) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-azure.svg)](https://travis-ci.org/npmtest/node-npmtest-azure)

#### Microsoft Azure Client Library for node

[![NPM](https://nodei.co/npm/azure.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/azure)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-azure/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-azure/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-azure/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-azure/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-azure/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-azure/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-azure/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-azure/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-azure/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-azure/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-azure/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-azure/build/test-report.html](https://npmtest.github.io/node-npmtest-azure/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-azure/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-azure/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-azure/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-azure/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-azure/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-azure/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-azure/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-azure/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Microsoft Corporation"
    },
    "bugs": {
        "url": "http://github.com/Azure/azure-sdk-for-node/issues"
    },
    "contributors": [
        {
            "name": "Block, Glenn"
        },
        {
            "name": "Cowlishaw, Mark"
        },
        {
            "name": "Dejardin, Louis"
        },
        {
            "name": "Georgiev, Yavor"
        },
        {
            "name": "Janczuk, Tomasz"
        },
        {
            "name": "Rodrigues, Andre"
        },
        {
            "name": "Tavares, Chris"
        },
        {
            "name": "Zavery, Amar"
        },
        {
            "name": "Wang, Yugang"
        },
        {
            "name": "Mkrtchyan, Hovsep"
        },
        {
            "name": "Lu, Jianghao"
        },
        {
            "name": "Krishnan, Balaji"
        }
    ],
    "dependencies": {
        "azure-arm-advisor": "1.0.0-preview",
        "azure-arm-analysisservices": "2.0.0-preview",
        "azure-arm-authorization": "4.0.0-preview",
        "azure-arm-automation": "1.0.0-preview",
        "azure-arm-batch": "1.0.0-preview",
        "azure-arm-billing": "1.0.0-preview",
        "azure-arm-cdn": "2.0.0-preview",
        "azure-arm-cognitiveservices": "1.0.0-preview",
        "azure-arm-commerce": "1.0.0-preview",
        "azure-arm-compute": "1.0.0-preview",
        "azure-arm-containerregistry": "1.0.0-preview",
        "azure-arm-customerinsights": "1.0.0-preview",
        "azure-arm-datalake-analytics": "2.0.0-preview",
        "azure-arm-datalake-store": "2.0.0-preview",
        "azure-arm-devtestlabs": "1.0.0-preview",
        "azure-arm-dns": "1.0.0-preview",
        "azure-arm-documentdb": "1.0.0-preview",
        "azure-arm-eventhub": "1.0.0-preview",
        "azure-arm-hdinsight": "0.2.1",
        "azure-arm-hdinsight-jobs": "0.1.1",
        "azure-arm-insights": "1.0.0-preview",
        "azure-arm-intune": "1.0.0-preview",
        "azure-arm-iothub": "1.0.0-preview",
        "azure-arm-keyvault": "1.0.0-preview",
        "azure-arm-logic": "1.0.0-preview",
        "azure-arm-machinelearning": "1.0.0-preview",
        "azure-arm-mediaservices": "1.0.0-preview",
        "azure-arm-network": "1.0.0-preview",
        "azure-arm-notificationhubs": "1.0.0-preview",
        "azure-arm-operationalinsights": "1.0.0-preview",
        "azure-arm-powerbiembedded": "1.0.0-preview",
        "azure-arm-recoveryservices": "1.0.0-preview",
        "azure-arm-recoveryservicesbackup": "1.0.0-preview",
        "azure-arm-rediscache": "1.0.0-preview",
        "azure-arm-relay": "1.0.0-preview",
        "azure-arm-resource": "2.0.0-preview",
        "azure-arm-sb": "1.0.0-preview",
        "azure-arm-scheduler": "1.0.0-preview",
        "azure-arm-search": "1.0.0-preview",
        "azure-arm-servermanagement": "1.0.0-preview",
        "azure-arm-servicefabric": "1.0.0-preview",
        "azure-arm-servicemap": "1.0.0-preview",
        "azure-arm-sql": "1.0.0-preview",
        "azure-arm-storage": "1.0.0-preview",
        "azure-arm-storageimportexport": "1.0.0-preview",
        "azure-arm-trafficmanager": "1.0.0-preview",
        "azure-arm-website": "1.0.0-preview",
        "azure-asm-compute": "0.17.1",
        "azure-asm-hdinsight": "0.10.3",
        "azure-asm-mgmt": "0.10.2",
        "azure-asm-network": "0.13.1",
        "azure-asm-sb": "0.10.2",
        "azure-asm-scheduler": "0.10.2",
        "azure-asm-sql": "0.10.2",
        "azure-asm-storage": "0.12.1",
        "azure-asm-store": "0.10.2",
        "azure-asm-subscription": "0.10.2",
        "azure-asm-trafficmanager": "0.10.4",
        "azure-asm-website": "0.10.5",
        "azure-batch": "1.0.0-preview",
        "azure-common": "0.9.18",
        "azure-gallery": "2.0.0-pre.20",
        "azure-graph": "2.0.0-preview",
        "azure-insights": "1.0.0-preview",
        "azure-keyvault": "2.0.0-preview",
        "azure-monitoring": "0.10.5",
        "azure-sb": "0.10.4",
        "azure-scheduler": "0.10.3",
        "azure-servicefabric": "1.0.0-preview",
        "azure-storage": "1.3.0",
        "mime": "~1.2.4",
        "moment": "^2.18.1",
        "ms-rest": "^2.0.0",
        "ms-rest-azure": "^2.0.1",
        "request": "^2.81.0",
        "underscore": "1.4.x",
        "uuid": "^3.0.1"
    },
    "description": "Microsoft Azure Client Library for node",
    "devDependencies": {
        "adal-node": "^0.1.22",
        "async": "^1.5.0",
        "azure-storage-legacy": "0.9.14",
        "colors": "1.1.2",
        "glob": "^7.1.1",
        "grunt": "~0.4",
        "grunt-contrib-connect": "^0.10.1",
        "grunt-contrib-symlink": "^0.3.0",
        "grunt-devserver": "~0.6",
        "grunt-gh-pages": "1.1.0",
        "grunt-jsdoc": "~0.6",
        "gulp": "^3.9.0",
        "gulp-exec": "2.1.2",
        "jshint": "2.9.4",
        "minami": "git://github.com/devigned/minami.git#master",
        "mocha": "^3.2.0",
        "moment": "^2.14.1",
        "nock": "0.16",
        "node-forge": "0.6.30",
        "promise": "^7.1.1",
        "random-js": "1.0.4",
        "should": "^8.3.1",
        "sinon": "^2.1.0",
        "xmlbuilder": "0.4.3",
        "yargs": "3.29.0"
    },
    "directories": {},
    "dist": {
        "shasum": "550ac8a15b65e7e25287c21dfda9f1cfd7a7e756",
        "tarball": "https://registry.npmjs.org/azure/-/azure-2.0.0-preview.tgz"
    },
    "gitHead": "1d79303183fb8d72f268cc384c04f4b8e125d130",
    "homepage": "http://github.com/azure/azure-sdk-for-node",
    "keywords": [
        "node",
        "azure"
    ],
    "license": "(MIT OR Apache-2.0)",
    "main": "./lib/azure.js",
    "maintainers": [
        {
            "name": "windowsazure"
        }
    ],
    "name": "azure",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/azure/azure-sdk-for-node.git"
    },
    "scripts": {
        "ci": "node scripts/unit.js testlist.txt",
        "coverage": "node scripts/unit.js testlist.txt -coverage > coverage.html",
        "jshint": "jshint lib --reporter=jslint",
        "setup": "node scripts/setup.js",
        "test": "npm -s run-script jshint && npm -s run-script unit-arm && npm -s run-script unit && npm -s run-script unit-msrest && npm -s run-script unit-msrestazure",
        "unit": "node scripts/unit.js testlist.txt",
        "unit-arm": "node scripts/unit-arm.js testlistarm.txt",
        "unit-msrest": "cd runtime/ms-rest && npm test",
        "unit-msrestazure": "cd runtime/ms-rest-azure && npm test"
    },
    "tags": [
        "azure",
        "sdk"
    ],
    "version": "2.0.0-preview",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
