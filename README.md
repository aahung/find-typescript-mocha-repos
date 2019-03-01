# Find Repos in TypeScript Tested using Mocha

The list was updated at 01:56:05 03/01/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [Microsoft/vscode](https://github.com/Microsoft/vscode) | 70017 | `mocha` | 
| [ReactiveX/rxjs](https://github.com/ReactiveX/rxjs) | 17245 | `cross-env TS_NODE_PROJECT=spec/tsconfig.json mocha --opts spec/support/default.opts "spec/**/*-spec.ts"` | 
| [nestjs/nest](https://github.com/nestjs/nest) | 13061 | `nyc --require ts-node/register mocha packages/**/*.spec.ts --reporter spec --require 'node_modules/reflect-metadata/Reflect.js'` | 
| [typeorm/typeorm](https://github.com/typeorm/typeorm) | 11401 | `rimraf ./build && tsc && mocha --file ./build/compiled/test/utils/test-setup.js --bail --recursive --timeout 60000 ./build/compiled/test` | 
| [googleapis/google-api-nodejs-client](https://github.com/googleapis/google-api-nodejs-client) | 7225 | `nyc mocha build/test` | 
| [nexe/nexe](https://github.com/nexe/nexe) | 6574 | `mocha` | 
| [xtermjs/xterm.js](https://github.com/xtermjs/xterm.js) | 5747 | `npm run mocha` | 
| [davidkpiano/xstate](https://github.com/davidkpiano/xstate) | 4965 | `npm run build:cjs && mocha --require ts-node/register test/**.ts test/**/*.test.ts` | 
| [palantir/tslint](https://github.com/palantir/tslint) | 4776 | `npm-run-all test:pre -p test:mocha test:rules` | 
| [Microsoft/azuredatastudio](https://github.com/Microsoft/azuredatastudio) | 4760 | `mocha` | 
| [rrweb-io/rrweb](https://github.com/rrweb-io/rrweb) | 4022 | `npm run bundle:browser && cross-env TS_NODE_CACHE=false TS_NODE_FILES=true mocha -r ts-node/register test/**/*.test.ts` | 
| [williamngan/pts](https://github.com/williamngan/pts) | 3441 | `mocha --opts mocha.opts` | 
| [thx/rap2-delos](https://github.com/thx/rap2-delos) | 3219 | `cross-env NODE_ENV=development cross-env TEST_MODE=true nyc mocha --exit` | 
| [vuejs/vue-class-component](https://github.com/vuejs/vue-class-component) | 3039 | `npm run build && webpack --config test/webpack.config.js && mocha test/test.build.js` | 
| [michaelgrosner/tribeca](https://github.com/michaelgrosner/tribeca) | 2919 | `mocha` | 
| [retejs/rete](https://github.com/retejs/rete) | 2918 | `BABEL_ENV=test mocha -r ts-node/register test/**.ts` | 
| [electron-userland/electron-forge](https://github.com/electron-userland/electron-forge) | 2654 | `cross-env TS_NODE_FILES=true yarn run mocha './tools/test-globber.ts'` | 
| [decaffeinate/decaffeinate](https://github.com/decaffeinate/decaffeinate) | 2457 | `mocha 'test/**/*.ts'` | 
| [compodoc/compodoc](https://github.com/compodoc/compodoc) | 2336 | `mocha-parallel-tests test && node test/dist/cli/cli-revert-root-folder.js` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 2258 | `npm run tsc && npm run mocha` | 
| [s-panferov/awesome-typescript-loader](https://github.com/s-panferov/awesome-typescript-loader) | 1954 | `rimraf .test && mocha --trace-warnings --timeout 30000 --exit dist/__test__` | 
| [mgechev/codelyzer](https://github.com/mgechev/codelyzer) | 1934 | `rimraf dist && tsc && ncp test/fixtures dist/test/fixtures && mocha dist/test --recursive` | 
| [yortus/asyncawait](https://github.com/yortus/asyncawait) | 1811 | `mocha` | 
| [staltz/xstream](https://github.com/staltz/xstream) | 1792 | `npm run lint && npm run test-types && npm run mocha && npm run doctest` | 
| [colyseus/colyseus](https://github.com/colyseus/colyseus) | 1558 | `mocha --require ts-node/register test/**Test.ts --exit` | 
| [strongloop/loopback-next](https://github.com/strongloop/loopback-next) | 1503 | `node packages/build/bin/run-nyc npm run mocha --scripts-prepend-node-path` | 
| [vscode-icons/vscode-icons](https://github.com/vscode-icons/vscode-icons) | 1491 | `nyc -x '' mocha` | 
| [Microsoft/vscode-chrome-debug](https://github.com/Microsoft/vscode-chrome-debug) | 1486 | `mocha --exit --timeout 20000 -s 2000 -u tdd --colors "./out/test/*.test.js"` | 
| [shanalikhan/code-settings-sync](https://github.com/shanalikhan/code-settings-sync) | 1443 | `npm run tslint-check && tsc -p ./ && mocha --recursive "./out/test/**/*.js"` | 
| [sveltejs/sapper](https://github.com/sveltejs/sapper) | 1355 | `mocha --opts mocha.opts` | 
| [google/clasp](https://github.com/google/clasp) | 1323 | `nyc --cache false mocha --timeout 100000 -- 'tests/**/*.js'` | 
| [cherow/cherow](https://github.com/cherow/cherow) | 1301 | `cross-env TS_NODE_PROJECT="test/tsconfig.json" mocha "test/**/*.ts" -c -R progress -r ts-node/register -r source-map-support/register --recursive --globals expect` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1259 | `TS_NODE_PROJECT=tsconfig.test.json mocha **/*.test.ts` | 
| [funkia/list](https://github.com/funkia/list) | 1257 | `nyc mocha --timeout 10000 --recursive test/*.ts` | 
| [Polymer/polymer-bundler](https://github.com/Polymer/polymer-bundler) | 1228 | `tsc && tslint -c tslint.json src/*.ts src/**/*.ts && mocha` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 1168 | `rm -Rf .ts-node && TS_NODE_CACHE_DIRECTORY=.ts-node mocha -r ts-node/register src/**/*.test.ts ./test/*.ts -R spec` | 
| [firebase/geofire-js](https://github.com/firebase/geofire-js) | 1123 | `nyc --reporter=html --reporter=text mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 1106 | `tsc -p ./ && mocha` | 
| [itchio/itch](https://github.com/itchio/itch) | 1030 | `cross-env TS_NODE_PROJECT=tsconfig.test.json mocha -r ts-node/register -r tsconfig-paths/register ./src/**/*.spec.ts` | 
| [mgechev/ngrev](https://github.com/mgechev/ngrev) | 974 | `electron-mocha app/specs.js.autogenerated --renderer --require source-map-support/register` | 
| [Microsoft/dts-gen](https://github.com/Microsoft/dts-gen) | 957 | `mocha bin/tests/test.js` | 
| [WuTheFWasThat/vimflowy](https://github.com/WuTheFWasThat/vimflowy) | 955 | `mocha --opts test/mocha.opts` | 
| [stryker-mutator/stryker](https://github.com/stryker-mutator/stryker) | 875 | `npm run mocha` | 
| [NativeScript/nativescript-cli](https://github.com/NativeScript/nativescript-cli) | 808 | `istanbul cover ./node_modules/mocha/bin/_mocha` | 
| [simonbengtsson/jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) | 792 | `mocha --require ts-node/register` | 
| [netgusto/nodebook](https://github.com/netgusto/nodebook) | 784 | `mocha test/backend` | 
| [davidkpiano/flipping](https://github.com/davidkpiano/flipping) | 781 | `NODE_ENV=test && mocha -r ts-node/register test/**.test.ts` | 
| [coinbase/gdax-tt](https://github.com/coinbase/gdax-tt) | 742 | `yarn run lint && yarn run test:mocha` | 
| [iotaledger/iota.js](https://github.com/iotaledger/iota.js) | 736 | `mocha` | 
| [ClusterWS/ClusterWS](https://github.com/ClusterWS/ClusterWS) | 733 | `mocha -r ts-node/register ./tests/specs/*.spec.ts --exit` | 
| [rubyide/vscode-ruby](https://github.com/rubyide/vscode-ruby) | 726 | `node ./node_modules/mocha/bin/mocha --recursive ./out/*.test.js` | 
| [angular/dgeni](https://github.com/angular/dgeni) | 717 | `mocha --require ts-node/register -R spec src/**/*.spec.ts` | 
| [alexjlockwood/avocado](https://github.com/alexjlockwood/avocado) | 696 | `./node_modules/.bin/mocha --require ts-node/register ./test/**/*.spec.ts` | 
| [mrmlnc/fast-glob](https://github.com/mrmlnc/fast-glob) | 658 | `mocha "out/**/*.spec.js" -s 0` | 
| [veonim/veonim](https://github.com/veonim/veonim) | 657 | `mocha test/unit` | 
| [laoqiren/mlhelper](https://github.com/laoqiren/mlhelper) | 646 | `mocha --recursive` | 
| [opentracing/opentracing-javascript](https://github.com/opentracing/opentracing-javascript) | 639 | `mocha lib/test/unittest.js --check-leaks --color` | 
| [YousefED/typescript-json-schema](https://github.com/YousefED/typescript-json-schema) | 619 | `npm run build && mocha -t 5000 --require source-map-support/register test` | 
| [jaysoo/todomvc-redux-react-typescript](https://github.com/jaysoo/todomvc-redux-react-typescript) | 611 | `tsc && mocha --require test-setup --recursive ./dist/**/__spec__/**/*-spec.js` | 
| [googleapis/google-auth-library-nodejs](https://github.com/googleapis/google-auth-library-nodejs) | 604 | `nyc mocha build/test` | 
| [RxJS-CN/RxJS-Docs-CN](https://github.com/RxJS-CN/RxJS-Docs-CN) | 604 | `npm-run-all clean_spec build_spec test_mocha clean_spec` | 
| [data-forge/data-forge-ts](https://github.com/data-forge/data-forge-ts) | 602 | `nyc mocha --opts ./src/test/mocha.opts` | 
| [szokodiakos/typegoose](https://github.com/szokodiakos/typegoose) | 600 | `npm run lint && nyc npm run mocha` | 
| [JustClear/blurify](https://github.com/JustClear/blurify) | 597 | `mocha test/index.js` | 
| [hacksparrow/node-easyimage](https://github.com/hacksparrow/node-easyimage) | 594 | `npm run lint && npm run mocha` | 
| [dsherret/ts-morph](https://github.com/dsherret/ts-morph) | 592 | `cross-env TS_NODE_COMPILER="ttypescript" TS_NODE_TRANSPILE_ONLY="true" mocha --opts mocha.opts --grep @performance --invert` | 
| [andrerpena/react-mde](https://github.com/andrerpena/react-mde) | 590 | `mocha --timeout 15000 -r ts-node/register ./test/*Spec.ts` | 
| [pgilad/leasot](https://github.com/pgilad/leasot) | 588 | `mocha --require ts-node/register -R spec './tests/*.ts'` | 
| [bbc/sqs-consumer](https://github.com/bbc/sqs-consumer) | 587 | `mocha` | 
| [emilioastarita/lyricfier](https://github.com/emilioastarita/lyricfier) | 563 | `mocha` | 
| [brannondorsey/chattervox](https://github.com/brannondorsey/chattervox) | 559 | `mocha test` | 
| [mateogianolio/vectorious](https://github.com/mateogianolio/vectorious) | 552 | `nyc mocha -r ts-node/register ./src/*.spec.ts` | 
| [whitecolor/yalc](https://github.com/whitecolor/yalc) | 537 | `tsc && mocha test && yarn lint` | 
| [SierraSoftworks/Iridium](https://github.com/SierraSoftworks/Iridium) | 537 | `mocha --opts test/mocha.opts dist/test` | 
| [rill-js/rill](https://github.com/rill-js/rill) | 531 | `nyc --extension=.ts --include=src/**/*.ts --reporter=lcov --reporter=text-summary npm run mocha` | 
| [lukeautry/tsoa](https://github.com/lukeautry/tsoa) | 524 | `cross-env NODE_ENV=tsoa_test mocha **/*.spec.ts --exit --compilers ts:ts-node/register` | 
| [championswimmer/vuex-persist](https://github.com/championswimmer/vuex-persist) | 513 | `cd test && mocha -r ts-node/register *.ts` | 
| [benjamn/ast-types](https://github.com/benjamn/ast-types) | 506 | `npm run gen && npm run build && npm run mocha` | 
| [steelsojka/lodash-decorators](https://github.com/steelsojka/lodash-decorators) | 506 | `mocha --opts mocha.opts` | 
| [sourcegraph/javascript-typescript-langserver](https://github.com/sourcegraph/javascript-typescript-langserver) | 504 | `mocha --require source-map-support/register --timeout 7000 --slow 2000 lib/test/**/*.js` | 
| [firebase/firebase-functions](https://github.com/firebase/firebase-functions) | 500 | `npm run mocha` | 
| [electron/electron-rebuild](https://github.com/electron/electron-rebuild) | 497 | `npm run lint && npm run mocha` | 
| [Rich-Harris/devalue](https://github.com/Rich-Harris/devalue) | 492 | `mocha --opts mocha.opts` | 
| [Cookie-AutoDelete/Cookie-AutoDelete](https://github.com/Cookie-AutoDelete/Cookie-AutoDelete) | 491 | `./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- -R spec ./test/*` | 
| [pact-foundation/pact-js](https://github.com/pact-foundation/pact-js) | 476 | `nyc --check-coverage --reporter=html --reporter=text-summary mocha` | 
| [43081j/rar.js](https://github.com/43081j/rar.js) | 461 | `npm run build && mocha` | 
| [szwacz/fs-jetpack](https://github.com/szwacz/fs-jetpack) | 452 | `mocha -r ts-node/register "spec/**/*.spec.ts"` | 
| [incrediblesound/story-graph](https://github.com/incrediblesound/story-graph) | 445 | `_mocha --` | 
| [vvakame/typescript-formatter](https://github.com/vvakame/typescript-formatter) | 439 | `npm run build && mocha --reporter spec --timeout 20000 --require intelli-espower-loader` | 
| [line/line-bot-sdk-nodejs](https://github.com/line/line-bot-sdk-nodejs) | 423 | `API_BASE_URL=http://localhost:1234/ TEST_PORT=1234 TS_NODE_CACHE=0 nyc mocha` | 
| [felixfbecker/vscode-php-debug](https://github.com/felixfbecker/vscode-php-debug) | 407 | `mocha out/test --timeout 20000 --slow 1000 --retries 4` | 
| [surf-build/surf](https://github.com/surf-build/surf) | 396 | `mocha --compilers ts:ts-node/register ./test/*.ts` | 
| [amplify-education/serverless-domain-manager](https://github.com/amplify-education/serverless-domain-manager) | 385 | `tsc --project . && nyc mocha -r ts-node/register test/unit-tests/index.test.ts && nyc report --reporter=text-summary` | 
| [Asana/typed-react](https://github.com/Asana/typed-react) | 383 | `istanbul cover _mocha -- --reporter ${MOCHA_REPORTER-nyan} --slow 10 --ui tdd --recursive build/**/*_test.js` | 
| [R-js/libRmath.js](https://github.com/R-js/libRmath.js) | 382 | `cross-env-shell NODE_ENV=test TS_NODE_DISABLE_WARNINGS=true nyc mocha` | 
| [Microsoft/node-pty](https://github.com/Microsoft/node-pty) | 370 | `cross-env NODE_ENV=test mocha -R spec --exit lib/*.test.js` | 
| [Polymer/prpl-server](https://github.com/Polymer/prpl-server) | 365 | `npm run build && mocha` | 
| [cartant/rxjs-spy](https://github.com/cartant/rxjs-spy) | 364 | `yarn run lint && yarn run test:build && yarn run test:karma && yarn run test:mocha` | 
| [itsFrank/vue-typescript](https://github.com/itsFrank/vue-typescript) | 361 | `mocha` | 
| [arangodb/arangojs](https://github.com/arangodb/arangojs) | 355 | `mocha --growl --reporter spec --require source-map-support/register --timeout 10000 lib/async/test` | 
| [apollographql/persistgraphql](https://github.com/apollographql/persistgraphql) | 354 | `mocha --reporter spec --full-trace lib/test/tests.js` | 
| [ngParty/ng-metadata](https://github.com/ngParty/ng-metadata) | 351 | `mocha ./test/index.ts --require ts-node/register --colors --watch-extensions ts` | 
| [codemirror/codemirror.next](https://github.com/codemirror/codemirror.next) | 350 | `mocha -r ts-node/register/transpile-only doc/test/test-*.ts state/test/test-*.ts history/test/test-*.ts rangeset/test/test-rangeset.ts keymap/test/test-*.ts legacy-modes/test/test-*.ts extension/test/test-*.ts view/test/test-heightmap.ts` | 
| [biesbjerg/ngx-translate-extract](https://github.com/biesbjerg/ngx-translate-extract) | 340 | `mocha -r ts-node/register tests/**/*.spec.ts` | 
| [Canner/apollo-link-firebase](https://github.com/Canner/apollo-link-firebase) | 339 | `TS_NODE_COMPILER_OPTIONS='{"module":"commonjs"}' mocha --timeout 10000 --compilers ts:ts-node/register --recursive --exit "test/**/*.spec.ts"` | 
| [dividab/tsconfig-paths](https://github.com/dividab/tsconfig-paths) | 331 | `mocha` | 
| [GoogleChrome/chrome-launcher](https://github.com/GoogleChrome/chrome-launcher) | 322 | `mocha --require ts-node/register --reporter=dot test/**/*-test.ts --timeout=10000` | 
| [zlq4863947/triangular-arbitrage](https://github.com/zlq4863947/triangular-arbitrage) | 322 | `cross-env NODE_ENV=test mocha dist/**/*.test.js --timeout 5000 --require intelli-espower-loader` | 
| [SweetIQ/schemats](https://github.com/SweetIQ/schemats) | 316 | `npm run lint && npm run build && npm run dependency-check && mocha` | 
| [alexcambose/motus](https://github.com/alexcambose/motus) | 301 | `cross-env mocha -r ts-node/register 'test/**/*.spec.ts'` | 
| [Kononnable/typeorm-model-generator](https://github.com/Kononnable/typeorm-model-generator) | 300 | `istanbul cover ./node_modules/mocha/bin/_mocha dist/test/**/*.test.js  -- -R spec --bail` | 
| [cbowdon/TsMonad](https://github.com/cbowdon/TsMonad) | 297 | `mocha lib/test` | 
| [mgechev/aspect.js](https://github.com/mgechev/aspect.js) | 296 | `tsc && mocha -R nyan ./dist/test/**/*.spec.js` | 
| [FinNLP/en-inflectors](https://github.com/FinNLP/en-inflectors) | 292 | `mocha` | 
| [spiffcode/ghedit](https://github.com/spiffcode/ghedit) | 281 | `mocha` | 
| [dolanmiu/docx](https://github.com/dolanmiu/docx) | 281 | `mocha-webpack "src/**/*.ts"` | 
| [cdonohue/polychrome](https://github.com/cdonohue/polychrome) | 279 | `mocha --compilers js:babel-register test/**/*.js` | 
| [nwtgck/piping-server](https://github.com/nwtgck/piping-server) | 279 | `mocha --require ts-node/register --timeout 10000 test/**/*.ts` | 
| [worr/node-imdb-api](https://github.com/worr/node-imdb-api) | 275 | `nyc --require ts-node/register --reporter=lcov node_modules/mocha/bin/mocha test/*.ts` | 
| [albburtsev/bem-cn](https://github.com/albburtsev/bem-cn) | 270 | `mocha src/**/*.spec.ts` | 
| [championswimmer/vuex-module-decorators](https://github.com/championswimmer/vuex-module-decorators) | 269 | `cd test && mocha -r ts-node/register *.ts` | 
| [rubenspgcavalcante/webpack-chrome-extension-reloader](https://github.com/rubenspgcavalcante/webpack-chrome-extension-reloader) | 269 | `NODE_ENV=test webpack && mocha dist/tests.js` | 
| [FormidableLabs/inspectpack](https://github.com/FormidableLabs/inspectpack) | 267 | `mocha "test/**/*.spec.ts"` | 
| [juanfranblanco/vscode-solidity](https://github.com/juanfranblanco/vscode-solidity) | 266 | `nyc --require ts-node/register --require source-map-support/register mocha test/**/*.spec.ts` | 
| [RisingStack/node-typescript-starter](https://github.com/RisingStack/node-typescript-starter) | 265 | `tsc && mocha dist/**/*.spec.js` | 
| [slothking-online/diagram](https://github.com/slothking-online/diagram) | 265 | `mocha -r ts-node/register src/**/*.spec.ts` | 
| [ReactiveX/rxjs-tslint](https://github.com/ReactiveX/rxjs-tslint) | 259 | `rimraf dist && tsc && mocha -R nyan dist/test --recursive` | 
| [nefe/pont](https://github.com/nefe/pont) | 253 | `mocha --timeout 15000 -r ts-node/register test/**/test.ts` | 
| [AmirTugi/tea-school](https://github.com/AmirTugi/tea-school) | 252 | `npx ts-mocha ./src/tests/**.ts` | 
| [frankwallis/plugin-typescript](https://github.com/frankwallis/plugin-typescript) | 252 | `mocha --require ./test/environment --timeout 10000 ./test/*.ts` | 
| [SpoonX/wetland](https://github.com/SpoonX/wetland) | 251 | `mocha dist/test/helper dist/test/unit/{*.spec.js,**/*.spec.js} --timeout 15000` | 
| [kubernetes-client/javascript](https://github.com/kubernetes-client/javascript) | 248 | `nyc mocha` | 
| [cyclejs/react-native](https://github.com/cyclejs/react-native) | 246 | `TS_NODE_PROJECT=test/tsconfig.json mocha test/*.ts --require @huston007/react-native-mock/mock.js --require ts-node/register --recursive` | 
| [styleguidist/react-docgen-typescript](https://github.com/styleguidist/react-docgen-typescript) | 240 | `tsc && mocha --timeout 10000 ./lib/**/__tests__/**.js` | 
| [liangzeng/cqrs](https://github.com/liangzeng/cqrs) | 239 | `tsc && mocha` | 
| [googleapis/nodejs-storage](https://github.com/googleapis/nodejs-storage) | 239 | `nyc mocha build/test` | 
| [renke/import-sort](https://github.com/renke/import-sort) | 232 | `mocha --require ts-node/register --recursive "packages/*/test/**/*.ts"` | 
| [Odi-ts/odi](https://github.com/Odi-ts/odi) | 232 | `nyc mocha test/**/*.test.ts --exit` | 
| [duniter/duniter](https://github.com/duniter/duniter) | 226 | `nyc --reporter html mocha` | 
| [thiagobustamante/typescript-rest](https://github.com/thiagobustamante/typescript-rest) | 223 | `cross-env NODE_ENV=test mocha --exit` | 
| [harttle/liquidjs](https://github.com/harttle/liquidjs) | 221 | `npm run build && mocha 'test/**/*.ts'` | 
| [Microsoft/vscode-cordova](https://github.com/Microsoft/vscode-cordova) | 219 | `node ./node_modules/mocha/bin/mocha --recursive -u bdd ./out/test/debugger` | 
| [cartant/rxjs-tslint-rules](https://github.com/cartant/rxjs-tslint-rules) | 218 | `yarn run lint && yarn run test:build && yarn run test:mocha && yarn run test:tslint-v5 && yarn run test:tslint-v6 && yarn run test:tslint-v6-compat` | 
| [fabiandev/ts-runtime](https://github.com/fabiandev/ts-runtime) | 211 | `NODE_ENV=test TS_NODE_CACHE=false ./node_modules/mocha/bin/_mocha` | 
| [jedmao/eclint](https://github.com/jedmao/eclint) | 210 | `nyc npm run mocha -- --reporter lcov --reporter spec` | 
| [stardustjs/stardust-core](https://github.com/stardustjs/stardust-core) | 209 | `mocha test` | 
| [HerringtonDarkholme/av-ts](https://github.com/HerringtonDarkholme/av-ts) | 206 | `mocha dist/test.js` | 
| [Zarel/Pokemon-Showdown-Client](https://github.com/Zarel/Pokemon-Showdown-Client) | 206 | `eslint --config=.eslintrc.js --cache --cache-file=eslint-cache/base js/ data/ && eslint --config=build-tools/.eslintrc.js --cache --cache-file=eslint-cache/build build-tools/update build-tools/build-indexes && tslint --project . && tsc && node build && mocha` | 
| [R-js/blasjs](https://github.com/R-js/blasjs) | 202 | `cross-env-shell NODE_ENV=test TS_NODE_DISABLE_WARNINGS=true nyc mocha` | 
| [zekelevu/typeframework](https://github.com/zekelevu/typeframework) | 200 | `mocha -R spec test/integration` | 
| [microsoftgraph/msgraph-sdk-javascript](https://github.com/microsoftgraph/msgraph-sdk-javascript) | 198 | `mocha lib/spec/core` | 
| [Polymer/polyserve](https://github.com/Polymer/polyserve) | 197 | `npm run build && mocha && tslint "src/**/*.ts"` | 
| [oclif/cli-ux](https://github.com/oclif/cli-ux) | 197 | `mocha --forbid-only "test/**/*.test.ts"` | 
| [funkia/hareactive](https://github.com/funkia/hareactive) | 196 | `nyc mocha --recursive test/**/*.ts` | 
| [JumpFm/jumpfm](https://github.com/JumpFm/jumpfm) | 192 | `mocha js` | 
| [emmanueltouzery/prelude-ts](https://github.com/emmanueltouzery/prelude-ts) | 187 | `rm tests/apidoc-*; tsc && node ./dist/tests/Comments.js && tsc && ./node_modules/mocha/bin/mocha --throw-deprecation --timeout 60000 ./dist/tests/*.js` | 
| [pnp/office365-cli](https://github.com/pnp/office365-cli) | 186 | `nyc -r=lcov -r=text mocha "dist/**/*.spec.js"` | 
| [codeaholicguy/wowcup](https://github.com/codeaholicguy/wowcup) | 185 | `nyc mocha --forbid-only "test/**/*.test.ts"` | 
| [ohjames/rxjs-websockets](https://github.com/ohjames/rxjs-websockets) | 180 | `npm run build && npm run mocha` | 
| [nodejs/llhttp](https://github.com/nodejs/llhttp) | 175 | `npm run mocha && npm run lint` | 
| [felixfbecker/iterare](https://github.com/felixfbecker/iterare) | 174 | `mocha -r source-map-support/register lib/**/*.test.js` | 
| [drew-y/cliffy](https://github.com/drew-y/cliffy) | 173 | `tsc && cd dist && mocha` | 
| [brentlintner/synt](https://github.com/brentlintner/synt) | 172 | `globstar -- _mocha "test/spec/**/*.coffee"` | 
| [staltz/html-looks-like](https://github.com/staltz/html-looks-like) | 172 | `npm run lint && npm run mocha` | 
| [Chinachu/Mirakurun](https://github.com/Chinachu/Mirakurun) | 171 | `mocha --exit test/*.spec.js` | 
| [nestjs/cqrs](https://github.com/nestjs/cqrs) | 169 | `tsc && mocha` | 
| [PeterDing/chord](https://github.com/PeterDing/chord) | 169 | `mocha --delay` | 
| [googleapis/nodejs-translate](https://github.com/googleapis/nodejs-translate) | 165 | `nyc mocha build/test` | 
| [Polymer/polymer-analyzer](https://github.com/Polymer/polymer-analyzer) | 165 | `npm run clean && npm run build && npm run lint && mocha` | 
| [nestjs/typeorm](https://github.com/nestjs/typeorm) | 164 | `rimraf ./build && tsc && mocha --file ./build/compiled/test/utils/test-setup.js --bail --recursive --timeout 60000 ./build/compiled/test` | 
| [Microsoft/typescript-tslint-plugin](https://github.com/Microsoft/typescript-tslint-plugin) | 163 | `mocha ./out/**/*.test.js --slow 2000 --timeout 10000` | 
| [Microsoft/vscode-node-debug](https://github.com/Microsoft/vscode-node-debug) | 162 | `gulp compile && mocha --timeout 10000 -u tdd ./out/tests/` | 
| [p-society/typeracer-cli](https://github.com/p-society/typeracer-cli) | 161 | `mocha --no-deprecation --timeout 10000 --require ts-node/register **/*.spec.ts` | 
| [geofirestore/geofirestore-js](https://github.com/geofirestore/geofirestore-js) | 160 | `nyc --reporter=html --reporter=text mocha` | 
| [Microsoft/vscode-vsce](https://github.com/Microsoft/vscode-vsce) | 159 | `gulp compile && mocha` | 
| [Talento90/typescript-node](https://github.com/Talento90/typescript-node) | 159 | `npm run build && mocha --exit --recursive dist/test/unit` | 
| [woutervh-/typescript-is](https://github.com/woutervh-/typescript-is) | 157 | `npm run lint && npm run build && ttsc --project tsconfig-test.json && mocha` | 
| [Half-Shot/matrix-appservice-discord](https://github.com/Half-Shot/matrix-appservice-discord) | 157 | `npm run-script build && mocha --opts test/mocha.opts build/test/config.js build/test` | 
| [nozer/quill-delta-to-html](https://github.com/nozer/quill-delta-to-html) | 157 | `./node_modules/nyc/bin/nyc.js ./node_modules/mocha/bin/mocha --compilers ts:ts-node/register -b "./test/**/*.ts"  ` | 
| [danvk/localturk](https://github.com/danvk/localturk) | 155 | `mocha --require ts-node/register test/**/*.ts` | 
| [nomiclabs/buidler](https://github.com/nomiclabs/buidler) | 155 | `nyc mocha` | 
| [Commit451/skyhook](https://github.com/Commit451/skyhook) | 155 | `mocha -r ts-node/register test/*.ts` | 
| [jgranstrom/zipson](https://github.com/jgranstrom/zipson) | 152 | `mocha --require ts-node/register --watch-extensions ts 'test/**/*.ts'` | 
| [cartant/rxjs-marbles](https://github.com/cartant/rxjs-marbles) | 151 | `yarn run lint && yarn run test:build && cross-env FAILING=0 yarn run test:ava && cross-env FAILING=0 yarn run test:jasmine && cross-env FAILING=0 yarn run test:jasmine-angular && cross-env FAILING=0 yarn run test:jest && cross-env FAILING=0 yarn run test:mocha && cross-env FAILING=0 yarn run test:tape` | 
| [chenhaozhi/Cpage.js](https://github.com/chenhaozhi/Cpage.js) | 151 | `mocha -r ./node_modules/ts-node/register test/**/*_spec.ts --reporter mochawesome` | 
| [ConquestArrow/dtsmake](https://github.com/ConquestArrow/dtsmake) | 149 | `mocha --compilers ts:ts-node/register test/*.ts` | 
| [atomist/sdm](https://github.com/atomist/sdm) | 148 | `mocha --require espower-typescript/guess "test/**/*.test.ts"` | 
| [martysweet/cfn-lint](https://github.com/martysweet/cfn-lint) | 145 | `mocha lib/test` | 
| [calidion/vig](https://github.com/calidion/vig) | 144 | `npm run build && nyc --reporter=text --reporter=html --reporter=lcov mocha --bail --compilers ts:ts-node/register --recursive 'test/**/*.test.ts'` | 
| [TrustWallet/trust-ray](https://github.com/TrustWallet/trust-ray) | 140 | `cross-env NODE_ENV=test mocha --recursive --require ts-node/register 'test/**/*.test.ts' --exit` | 
| [featurist/hyperdom](https://github.com/featurist/hyperdom) | 140 | `./node_modules/.bin/tsc && npm run karma && npm run mocha && eslint . && npm run tslint` | 
| [vrimar/construct-ui](https://github.com/vrimar/construct-ui) | 139 | `cross-env TS_NODE_PROJECT=test/tsconfig.json mocha` | 
| [arfedulov/semantic-ui-calendar-react](https://github.com/arfedulov/semantic-ui-calendar-react) | 139 | `npx cross-env TS_NODE_COMPILER_OPTIONS="{""allowJs"":true}" npx mocha -r ts-node/register ./test/setup.js ./test/**/*.{js,jsx,ts,tsx}` | 
| [Microsoft/monaco-languages](https://github.com/Microsoft/monaco-languages) | 139 | `mocha` | 
| [implydata/plyql](https://github.com/implydata/plyql) | 139 | `mocha` | 
| [DotJoshJohnson/vscode-xml](https://github.com/DotJoshJohnson/vscode-xml) | 138 | `npm run compile && mocha ./out/test/**/*.js` | 
| [Enterprise-JS/vscode-ts-node-debugging](https://github.com/Enterprise-JS/vscode-ts-node-debugging) | 138 | `npm run mocha --recursive ./src/**/__tests__/*` | 
| [rhysd/neovim-component](https://github.com/rhysd/neovim-component) | 137 | `mocha test/unit/ --exit` | 
| [Soluto/graphql-to-mongodb](https://github.com/Soluto/graphql-to-mongodb) | 137 | `ts-mocha tests/**/*.spec.ts` | 
| [bradymholt/cRonstrue](https://github.com/bradymholt/cRonstrue) | 136 | `npx mocha --reporter spec --compilers ts:ts-node/register` | 
| [Azure/azure-functions-pack](https://github.com/Azure/azure-functions-pack) | 136 | `npm run build && mocha --compilers ts:ts-node/register --recursive test/**/*-spec.ts` | 
| [rangle/typed-immutable-record](https://github.com/rangle/typed-immutable-record) | 134 | `npm run typings  && npm run lint && nyc npm run mocha` | 
| [AzureAD/azure-activedirectory-library-for-nodejs](https://github.com/AzureAD/azure-activedirectory-library-for-nodejs) | 133 | `npm run tsc && mocha -R spec --ui tdd test` | 
| [rtfeldman/node-elm-compiler](https://github.com/rtfeldman/node-elm-compiler) | 133 | `rm -rf test/fixtures/elm-stuff && mocha test/**/*.ts --require ts-node/register --watch-extensions ts` | 
| [colyseus/colyseus.js](https://github.com/colyseus/colyseus.js) | 133 | `mocha test/*.ts --require ts-node/register` | 
| [grantila/fetch-h2](https://github.com/grantila/fetch-h2) | 131 | `npm run lint && node_modules/.bin/nyc --require source-map-support/register npm run mocha` | 
| [szdc/tiktok-api](https://github.com/szdc/tiktok-api) | 131 | `TS_NODE_PROJECT=test/tsconfig.json mocha` | 
| [tunnelvisionlabs/antlr4ts](https://github.com/tunnelvisionlabs/antlr4ts) | 131 | `mocha` | 
| [Urigo/angular-meteor-base](https://github.com/Urigo/angular-meteor-base) | 131 | `TEST_BROWSER_DRIVER=puppeteer meteor test --driver-package=ardatan:mocha --raw-logs` | 
| [Microsoft/vscode-ios-web-debug](https://github.com/Microsoft/vscode-ios-web-debug) | 130 | `node ./node_modules/mocha/bin/mocha --recursive -u tdd ./out/test/` | 
| [tomastrajan/ngx-model](https://github.com/tomastrajan/ngx-model) | 130 | `npm run clean && tslint *.ts && npm run format:ci && mocha ./lib/model.test.ts --require ts-node/register` | 
| [ajafff/tsutils](https://github.com/ajafff/tsutils) | 129 | `mocha test/*Tests.js && tslint --test 'test/rules/**/tslint.json'` | 
| [mjhea0/typescript-node-api](https://github.com/mjhea0/typescript-node-api) | 129 | `mocha --reporter spec --compilers ts:ts-node/register 'test/**/*.test.ts'` | 
| [redhat-developer/yaml-language-server](https://github.com/redhat-developer/yaml-language-server) | 128 | `mocha --require ts-node/register --ui tdd ./test/*.test.ts` | 
| [matthew-matvei/freeman](https://github.com/matthew-matvei/freeman) | 127 | `xvfb-maybe electron-mocha --renderer __tests__` | 
| [functionalone/serverless-iam-roles-per-function](https://github.com/functionalone/serverless-iam-roles-per-function) | 127 | `nyc mocha --require ts-node/register --require source-map-support/register  ./src/test/**/*.test.ts` | 
| [arusanov/avatar-generator](https://github.com/arusanov/avatar-generator) | 126 | `mocha -r ts-node/register src/**/*.spec.ts` | 
| [arusanov/avatar-generator](https://github.com/arusanov/avatar-generator) | 126 | `mocha -r ts-node/register src/**/*.spec.ts` | 
| [TreeGateway/tree-gateway](https://github.com/TreeGateway/tree-gateway) | 125 | `cross-env NODE_ENV=test mocha --exit` | 
| [interledgerjs/ilp](https://github.com/interledgerjs/ilp) | 125 | `istanbul test -- _mocha` | 
| [prh/prh](https://github.com/prh/prh) | 125 | `npm run build && mocha --reporter spec --require intelli-espower-loader` | 
| [Goyoo/node-k8s-client](https://github.com/Goyoo/node-k8s-client) | 125 | `mocha test` | 
| [googlearchive/polylint](https://github.com/googlearchive/polylint) | 125 | `bower install && node_modules/.bin/jshint test && node_modules/.bin/mocha test/test.js` | 
| [Glavin001/graphql-sequelize-crud](https://github.com/Glavin001/graphql-sequelize-crud) | 125 | `mocha --require source-map-support/register dist/test` | 
| [tfoxy/chrome-promise](https://github.com/tfoxy/chrome-promise) | 125 | `mocha --timeout 10000` | 
| [tanepiper/node-bitly](https://github.com/tanepiper/node-bitly) | 124 | `VCR_MODE=cache mocha -r ts-node/register --reporter list src/*.spec.ts` | 
| [paulcbetts/spawn-rx](https://github.com/paulcbetts/spawn-rx) | 122 | `mocha --compilers ts:ts-node/register ./test/*` | 
| [Microsoft/TypeScript-TmLanguage](https://github.com/Microsoft/TypeScript-TmLanguage) | 121 | `mocha --full-trace tests/test.js  --reporter mocha-multi-reporters` | 
| [pocesar/node-stratum](https://github.com/pocesar/node-stratum) | 121 | `node ./node_modules/typescript/bin/tsc -p tests.json && mocha test` | 
| [JoshGlazebrook/socks](https://github.com/JoshGlazebrook/socks) | 121 | `NODE_ENV=test mocha --recursive --compilers ts:ts-node/register test/**/*.ts` | 
| [englercj/tsd-jsdoc](https://github.com/englercj/tsd-jsdoc) | 120 | `mocha --ui tdd -r ts-node/register test/specs/**.ts` | 
| [moodysalem/react-tournament-bracket](https://github.com/moodysalem/react-tournament-bracket) | 119 | `mocha --require ts-node/register src/**/*.test.tsx` | 
| [Esri/react-arcgis](https://github.com/Esri/react-arcgis) | 118 | `nyc mocha` | 
| [tycho01/typical](https://github.com/tycho01/typical) | 118 | `tsc | tee tsc.log && mocha lib/**/*.test.js 2>&1 | sed 's/[0-9]\+)/×/g' | tee errors.log` | 
| [jvilk/MakeTypes](https://github.com/jvilk/MakeTypes) | 116 | `npm-run-all --serial prepublish generate:test build:test mocha` | 
| [rohitpaulk/todoist-tribute](https://github.com/rohitpaulk/todoist-tribute) | 115 | `mocha --require ts-node/register app/javascript/packs/tests/**/*.ts` | 
| [IBM/Decentralized-Energy-Composer](https://github.com/IBM/Decentralized-Energy-Composer) | 114 | `mocha --recursive -t 4000` | 
| [mgechev/ngresizable](https://github.com/mgechev/ngresizable) | 110 | `mocha --require ts-node/register test/**/*.spec.ts --recursive` | 
| [horiuchi/dtsgenerator](https://github.com/horiuchi/dtsgenerator) | 109 | `istanbul cover _mocha test/*.js test/**/*.js` | 
| [structured-log/structured-log](https://github.com/structured-log/structured-log) | 109 | `mocha --compilers ts:ts-node/register -r src/polyfills/objectAssign.js test/**/*.spec.ts` | 
| [googleapis/nodejs-pubsub](https://github.com/googleapis/nodejs-pubsub) | 109 | `nyc mocha build/test` | 
| [toolness/p5.js-widget](https://github.com/toolness/p5.js-widget) | 109 | `webpack && mocha-phantomjs test/index.html` | 
| [palantir/typesettable](https://github.com/palantir/typesettable) | 108 | `npm-run-all build test:mocha test:coverage lint` | 
| [mysticatea/vue-eslint-parser](https://github.com/mysticatea/vue-eslint-parser) | 108 | `nyc npm run _mocha` | 
| [nodejs/llparse](https://github.com/nodejs/llparse) | 108 | `npm run mocha && npm run lint` | 
| [Urigo/meteor-rxjs](https://github.com/Urigo/meteor-rxjs) | 108 | `cd tests && meteor test --driver-package practicalmeteor:mocha` | 
| [kimamula/ts-transformer-keys](https://github.com/kimamula/ts-transformer-keys) | 107 | `tsc && node ./test/compileMain.js && mocha ./test/main.js` | 
| [bpatrik/pigallery2](https://github.com/bpatrik/pigallery2) | 107 | `ng test && mocha --recursive test/backend/unit && mocha --recursive test/backend/integration  && mocha --recursive test/common/unit ` | 
| [materiahq/materia-server](https://github.com/materiahq/materia-server) | 107 | `mocha -R spec dist/test/**/*.js` | 
| [atlassian/nucleus](https://github.com/atlassian/nucleus) | 106 | `mocha --compilers ts:ts-node/register src/__spec__/rest.ts src/**/__spec__/*_spec.ts src/**/**/__spec__/*_spec.ts` | 
| [inversify/inversify-express-example](https://github.com/inversify/inversify-express-example) | 106 | `nyc --clean --all --require ts-node/register --require reflect-metadata/Reflect --extension .ts -- mocha --exit --timeout 5000` | 
| [rjmacarthy/express-typescript-starter](https://github.com/rjmacarthy/express-typescript-starter) | 105 | `mocha -r ts-node/register -w ./spec/**/*.spec.ts` | 
| [philcockfield/storybook-host](https://github.com/philcockfield/storybook-host) | 105 | `./node_modules/mocha/bin/mocha --require ts-node/register --watch-extensions ts,tsx 'src/**/*.test.ts{,x}'` | 
| [gcanti/prop-types-ts](https://github.com/gcanti/prop-types-ts) | 104 | `npm run lint && npm run prettier && npm run mocha` | 
| [palantir/react-layered-chart](https://github.com/palantir/react-layered-chart) | 104 | `mocha 'test/**/*.ts' && tslint --project tsconfig.json` | 
| [wildbit/postmark.js](https://github.com/wildbit/postmark.js) | 104 | `node_modules/mocha/bin/mocha --timeout 10000 --retries 1 -r ts-node/register test/**/*test.ts` | 
| [balassy/aws-lambda-typescript](https://github.com/balassy/aws-lambda-typescript) | 103 | `nyc mocha --config ./test/.mocharc.yml` | 
| [secret-tech/backend-ico-dashboard](https://github.com/secret-tech/backend-ico-dashboard) | 103 | `nyc mocha ./src/**/*.spec.ts --require test/prepare.ts` | 
| [cartant/ts-action](https://github.com/cartant/ts-action) | 103 | `yarn run lint && yarn run test:build && mocha ./build/**/*-spec.js` | 
| [Kode/KodeStudio](https://github.com/Kode/KodeStudio) | 102 | `mocha` | 
| [thomasboyt/manygolf](https://github.com/thomasboyt/manygolf) | 102 | `webpack --config webpack/test.js && mocha --no-colors build/test/test.bundle.js` | 
| [metaes/metaes](https://github.com/metaes/metaes) | 101 | `tsc; mocha --recursive lib/ test/runner` | 
| [jf3096/json-typescript-mapper](https://github.com/jf3096/json-typescript-mapper) | 101 | `mocha ./spec/*.js` | 
| [AkashaProject/ipfs-connector](https://github.com/AkashaProject/ipfs-connector) | 99 | `./node_modules/istanbul/lib/cli.js cover ./node_modules/.bin/_mocha  ./tests.js` | 
| [argoproj/argo-ci](https://github.com/argoproj/argo-ci) | 99 | `TS_NODE_PROJECT=./src/tests/tsconfig.json mocha --require ts-node/register ./src/tests/**/*spec.ts` | 
| [giantmachines/redux-websocket](https://github.com/giantmachines/redux-websocket) | 98 | `mocha --compilers js:babel-core/register` | 
| [motorcyclejs/motorcyclejs](https://github.com/motorcyclejs/motorcyclejs) | 98 | `northbrook tslint && northbrook mocha && northbrook karma` | 
| [sudheerj/generator-jhipster-primeng](https://github.com/sudheerj/generator-jhipster-primeng) | 98 | `mocha test/* --timeout 500000` | 
| [ynab/ynab-sdk-js](https://github.com/ynab/ynab-sdk-js) | 97 | `TS_NODE_PROJECT=./test/tsconfig.json npx mocha --reporter spec --require ts-node/register/type-check 'test/**/*.ts'` | 
| [redhat-developer/vscode-yaml](https://github.com/redhat-developer/vscode-yaml) | 97 | `mocha --ui tdd out/test/extension.test.js` | 
| [InCar/ali-mns](https://github.com/InCar/ali-mns) | 96 | `node node_modules/mocha/bin/mocha` | 
| [nucleojs/nucleo](https://github.com/nucleojs/nucleo) | 95 | `mocha -r ts-node/register` | 
| [levjj/esverify](https://github.com/levjj/esverify) | 95 | `TS_NODE_TRANSPILE_ONLY=true mocha -r ts-node/register tests/*.ts` | 
| [aurelia/vscode-extension](https://github.com/aurelia/vscode-extension) | 94 | `mocha ./dist/test --recursive` | 
| [any-json/any-json](https://github.com/any-json/any-json) | 94 | `npm run build && cp -Rf test/fixtures out/test/ && mocha --ui tdd out/test/` | 
| [vladotesanovic/typescript-mongoose-express](https://github.com/vladotesanovic/typescript-mongoose-express) | 93 | `mocha` | 
| [googleapis/nodejs-bigquery](https://github.com/googleapis/nodejs-bigquery) | 92 | `nyc mocha build/test` | 
| [ENikS/LINQ](https://github.com/ENikS/LINQ) | 92 | `mocha test/ --recursive` | 
| [wbhob/nest-middlewares](https://github.com/wbhob/nest-middlewares) | 91 | `nyc --require ts-node/register mocha packages/**/*.spec.ts --reporter spec` | 
| [Azure/azure-cosmos-js](https://github.com/Azure/azure-cosmos-js) | 90 | `mocha -r ./src/test/common/setup.ts ./lib/src/test/ --recursive --timeout 100000 -i -g .*ignore.js` | 
| [sunzongzheng/musicApi](https://github.com/sunzongzheng/musicApi) | 90 | `mocha -t 30000 --require @babel/register 'test/*.test.js' --exit` | 
| [KarlPurk/redux-decorators](https://github.com/KarlPurk/redux-decorators) | 89 | `webpack --env=test > /dev/null && mocha dist/redux-decorators.spec.js` | 
| [carlansley/swagger2-koa](https://github.com/carlansley/swagger2-koa) | 89 | `npm run build && _mocha $(find build -name '*.spec.js') && npm run lint` | 
| [Cody2333/koa-swagger-decorator](https://github.com/Cody2333/koa-swagger-decorator) | 87 | `./node_modules/mocha/bin/mocha -r babel-core/register test/**/*.js --bail -t 2000000` | 
| [koltyakov/sp-rest-proxy](https://github.com/koltyakov/sp-rest-proxy) | 86 | `ts-node ./test/init && mocha --opts test/mocha.opts || ECHO.` | 
| [gcanti/elm-ts](https://github.com/gcanti/elm-ts) | 85 | `npm run lint && npm run mocha` | 
| [shlomiassaf/ngc-webpack](https://github.com/shlomiassaf/ngc-webpack) | 84 | `npm run build-test && ./node_modules/.bin/mocha dist/test/*.spec.js --recursive` | 
| [ui-jar/ui-jar](https://github.com/ui-jar/ui-jar) | 84 | `tsc && mocha "dist/test/**/*.js" ` | 
| [olosegres/jsona](https://github.com/olosegres/jsona) | 84 | `npm run test-compile && env NODE_ENV=test ts-mocha ./**/*.test.ts` | 
| [MariusAlch/json-to-ts](https://github.com/MariusAlch/json-to-ts) | 84 | `npm run build && mocha ./test/js-integration/index.js && mocha ./build/test` | 
| [rh389/dynamodb-geo.js](https://github.com/rh389/dynamodb-geo.js) | 84 | `mocha --require ts-node/register test/**/*.ts` | 
| [googleapis/nodejs-datastore](https://github.com/googleapis/nodejs-datastore) | 84 | `nyc mocha build/test` | 
| [roblox-ts/roblox-ts](https://github.com/roblox-ts/roblox-ts) | 83 | `npm run build && npx nyc --reporter=html mocha --timeout 0 --recursive out/test.js && lua tests/spec.lua` | 
| [yakovlevga/brickyeditor](https://github.com/yakovlevga/brickyeditor) | 82 | `mocha --compilers js:babel-core/register --recursive` | 
| [timocov/dts-bundle-generator](https://github.com/timocov/dts-bundle-generator) | 81 | `mocha --timeout 10000 --slow 2500 tests/unittests/**/*.spec.js tests/functional-test-cases.js` | 
| [flagello/Essence](https://github.com/flagello/Essence) | 81 | `mocha` | 
| [metadevpro/openapi3-ts](https://github.com/metadevpro/openapi3-ts) | 81 | `mocha --recursive --compilers ts:ts-node/register --require source-map-support/register "src/**/*.spec.ts"` | 
| [neon-bindings/neon-cli](https://github.com/neon-bindings/neon-cli) | 81 | `npm run transpile && mocha dist/neon-cli-test/acceptance` | 
| [teambition/ReactiveDB](https://github.com/teambition/ReactiveDB) | 79 | `npm run lint && NODE_ENV=test tman --mocha spec-js/test/run.js` | 
| [ninoseki/mitaka](https://github.com/ninoseki/mitaka) | 79 | `nyc mocha -r ts-node/register "src/**/*.spec.ts"` | 
| [adrien2p/nestjs-graphql](https://github.com/adrien2p/nestjs-graphql) | 78 | `mocha -r ts-node/register src/**/tests/*.ts` | 
| [Microsoft/vscode-mock-debug](https://github.com/Microsoft/vscode-mock-debug) | 78 | `mocha -u tdd ./out/tests/` | 
| [rpgeeganage/async-ray](https://github.com/rpgeeganage/async-ray) | 78 | `nyc mocha` | 
| [CityOfZion/neo-js](https://github.com/CityOfZion/neo-js) | 78 | `mocha --reporter spec` | 
| [bespoken/virtual-alexa](https://github.com/bespoken/virtual-alexa) | 77 | `nyc mocha --require ts-node/register test/**/*Test.ts` | 
| [troch/path-parser](https://github.com/troch/path-parser) | 77 | `mocha -r ts-node/register 'test/main.js'` | 
| [teamdomy/domy](https://github.com/teamdomy/domy) | 77 | `mocha --reporter spec --require ts-node/register 'tests/**/*.spec.ts'` | 
| [Microsoft/vscode-chrome-debug-core](https://github.com/Microsoft/vscode-chrome-debug-core) | 77 | `mocha --exit --recursive -u tdd ./out/test/` | 
| [wavesplatform/waves-api](https://github.com/wavesplatform/waves-api) | 76 | `npm run build && ./node_modules/.bin/tsc -p ./test/tsconfig.json && ./node_modules/.bin/mocha $(find ./tmp-node/test -name '*.spec.js')` | 
| [balena-io/balena-supervisor](https://github.com/balena-io/balena-supervisor) | 76 | `npm run lint && npm run test:build && JUNIT_REPORT_PATH=report.xml istanbul cover _mocha && npm run coverage` | 
| [codius/codiusd](https://github.com/codius/codiusd) | 76 | `npm run lint && nyc mocha` | 
| [AndrewPoyntz/time-ago-pipe](https://github.com/AndrewPoyntz/time-ago-pipe) | 76 | `mocha --reporter spec --require ts-node/register test/**/*.spec.ts` | 
| [funkia/jabz](https://github.com/funkia/jabz) | 75 | `nyc mocha --recursive test/**/*.ts` | 
| [suksant/sequelize-typescript-examples](https://github.com/suksant/sequelize-typescript-examples) | 75 | `gulp compile && mocha 'build/*/test/**/*.js'` | 
| [hbenl/vscode-firefox-debug](https://github.com/hbenl/vscode-firefox-debug) | 75 | `TS_NODE_FILES=true mocha --opts src/test/mocha.opts "src/test/test*.ts"` | 
| [puzzle-js/puzzle-js](https://github.com/puzzle-js/puzzle-js) | 74 | `nyc --check-coverage --lines=85 cross-env NODE_ENV=production mocha -r ts-node/register  --recursive 'test/**/*.spec.ts'` | 
| [alex-okrushko/backoff-rxjs](https://github.com/alex-okrushko/backoff-rxjs) | 74 | `yarn run lint && yarn run test:build && yarn run test:mocha` | 
| [pact-foundation/pact-node](https://github.com/pact-foundation/pact-node) | 74 | `cross-env LOGLEVEL=debug PACT_DO_NOT_TRACK=true mocha -r ts-node/register -R mocha-unfunk-reporter -t 15000 -s 5000 -b --check-leaks --exit "{src,test,bin,standalone}/**/*.spec.ts"` | 
| [Microsoft/vscode-css-languageservice](https://github.com/Microsoft/vscode-css-languageservice) | 73 | `npm run compile && mocha && npm run lint` | 
| [mrmlnc/vscode-scss](https://github.com/mrmlnc/vscode-scss) | 73 | `mocha out/**/*.spec.js` | 
| [Microsoft/NoSQLProvider](https://github.com/Microsoft/NoSQLProvider) | 73 | `mocha dist/tests/NoSqlProviderTests.js --timeout 5000` | 
| [theGlenn/apollo-prophecy](https://github.com/theGlenn/apollo-prophecy) | 72 | `rm -rf coverage && nyc mocha --opts mocha.opts` | 
| [DavidDuwaer/Coloquent](https://github.com/DavidDuwaer/Coloquent) | 72 | `npm run build && mocha -r ts-node/register tests/**/*.test.ts` | 
| [hawx1993/judge](https://github.com/hawx1993/judge) | 71 | `mocha --compilers ts:ts-node/register test/test.ts` | 
| [cartant/rxjs-etc](https://github.com/cartant/rxjs-etc) | 71 | `yarn run lint && yarn run test:build && yarn run test:karma && yarn run test:mocha` | 
| [felixfbecker/sequelize-decorators](https://github.com/felixfbecker/sequelize-decorators) | 71 | `mocha dist/test` | 
| [googleapis/node-gtoken](https://github.com/googleapis/node-gtoken) | 70 | `nyc mocha build/test` | 
| [AlexGalays/immupdate](https://github.com/AlexGalays/immupdate) | 70 | `mocha test/test.js && node test/testCompilationErrors.js` | 
| [indiejames/vscode-clojure-debug](https://github.com/indiejames/vscode-clojure-debug) | 69 | `node ./node_modules/mocha/bin/mocha -u tdd ./out/tests/` | 
| [deerawan/vscode-dash](https://github.com/deerawan/vscode-dash) | 69 | `./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- -R spec --ui tdd ./out/test/extension.test.js` | 
| [DhyanaChina/koa2-typescript-guide](https://github.com/DhyanaChina/koa2-typescript-guide) | 68 | `mocha` | 
| [Cellule/dndGenerator](https://github.com/Cellule/dndGenerator) | 68 | `mocha -r ./mocha-setup src/**/*.spec.ts` | 
| [mceachen/exiftool-vendored.js](https://github.com/mceachen/exiftool-vendored.js) | 68 | `nyc mocha` | 
| [Team-CHAD/DevDecks](https://github.com/Team-CHAD/DevDecks) | 68 | `cross-env NODE_ENV=test NODE_PATH=./app BABEL_DISABLE_CACHE=1 mocha --retries 2 --compilers ts:ts-node/register --recursive --require ignore-styles ./test/setup.ts test/**/*.spec.ts test/**/*.spec.tsx` | 
| [lukeautry/ts-app](https://github.com/lukeautry/ts-app) | 68 | `cross-env TS_NODE_PROJECT=./api/tsconfig.json mocha -t 15000 -r ts-node/register "./api/**/*.spec.ts"` | 
| [firebase/firebase-functions-test](https://github.com/firebase/firebase-functions-test) | 68 | `mocha .tmp/spec/index.spec.js` | 
| [KoteiIto/node-athena](https://github.com/KoteiIto/node-athena) | 67 | `rm -rf coverage && istanbul cover _mocha -- -R spec build/test/*.js` | 
| [dupski/json-to-graphql-query](https://github.com/dupski/json-to-graphql-query) | 67 | `mocha -r ts-node/register --recursive "./src/**/__tests__/*"` | 
| [jinhduong/linq-fns](https://github.com/jinhduong/linq-fns) | 67 | `mocha -r ts-node/register test/*.ts` | 
| [interledgerjs/ilp-connector](https://github.com/interledgerjs/ilp-connector) | 67 | `nyc mocha` | 
| [Polymer/polymer-editor-service](https://github.com/Polymer/polymer-editor-service) | 67 | `npm run clean && npm run build && mocha && npm run lint` | 
| [Alfresco/alfresco-js-api](https://github.com/Alfresco/alfresco-js-api) | 66 | `mocha --full-trace -r ts-node/register test/*.spec.ts test/**/*.spec.ts` | 
| [mattlewis92/generator-angular-library](https://github.com/mattlewis92/generator-angular-library) | 66 | `NODE_ENV=test mocha --timeout 300000` | 
| [getsentry/sentry-electron](https://github.com/getsentry/sentry-electron) | 66 | `cross-env TS_NODE_PROJECT=tsconfig.json xvfb-maybe electron-mocha --require ts-node/register/transpile-only --timeout 3000 ./test/unit/**/*.ts` | 
| [Microsoft/vscode-node-debug2](https://github.com/Microsoft/vscode-node-debug2) | 65 | `mocha --timeout 20000 -s 2000 -u tdd --colors --reporter node_modules/vscode-chrome-debug-core-testsupport/out/loggingReporter.js ./out/test/` | 
| [JustinBeckwith/retry-axios](https://github.com/JustinBeckwith/retry-axios) | 65 | `nyc mocha build/test --timeout 5000 --require source-map-support/register` | 
| [mysticatea/regexpp](https://github.com/mysticatea/regexpp) | 65 | `nyc _mocha "test/*.ts" --reporter dot --timeout 10000` | 
| [apollographql/graphql-document-collector](https://github.com/apollographql/graphql-document-collector) | 65 | `mocha 'lib/**/__tests__/*.js'` | 
| [TonyRobotics/RoboWare-Studio](https://github.com/TonyRobotics/RoboWare-Studio) | 64 | `mocha` | 
| [19majkel94/class-transformer-validator](https://github.com/19majkel94/class-transformer-validator) | 64 | `mocha build/tests/index.js` | 
| [wikiwi/reassemble](https://github.com/wikiwi/reassemble) | 64 | `cross-env TS_NODE_COMPILER_OPTIONS='{"module":"commonjs"}' mocha --opts mocha.opts` | 
| [duffman/tspath](https://github.com/duffman/tspath) | 64 | `mocha -r ts-node/register test/**.*/test.ts` | 
| [tinganho/node-accept-language](https://github.com/tinganho/node-accept-language) | 64 | `node node_modules/mocha/bin/mocha Build/Tests/Test.js` | 
| [mshanemc/shane-sfdx-plugins](https://github.com/mshanemc/shane-sfdx-plugins) | 63 | `mocha --forbid-only "test/**/*.test.ts"` | 
| [pdupavillon/express-recaptcha](https://github.com/pdupavillon/express-recaptcha) | 63 | `mocha --compilers ts:ts-node/register test/**/*.spec.ts` | 
| [NativeScript/nativescript-vscode-extension](https://github.com/NativeScript/nativescript-vscode-extension) | 63 | `mocha --opts ./src/tests/config/mocha.opts` | 
| [isc30/linq-collections](https://github.com/isc30/linq-collections) | 63 | `nyc mocha ./build/test/TestSuite.js --slow 0` | 
| [SqrTT/prophet](https://github.com/SqrTT/prophet) | 63 | `node ./node_modules/mocha/bin/mocha -u tdd ./out/tests/` | 
| [JustClear/colority](https://github.com/JustClear/colority) | 62 | `mocha test/index.js` | 
| [nhabuiduc/react-filter-box](https://github.com/nhabuiduc/react-filter-box) | 62 | `node --max-old-space-size=16000 ./node_modules/.bin/mocha-webpack --require ignore-styles -r jsdom-global/register --webpack-config webpack.test.config.js --watch "./test/**/*.ts"` | 
| [HerringtonDarkholme/kilimanjaro](https://github.com/HerringtonDarkholme/kilimanjaro) | 62 | `mocha dist/test/*.js` | 
| [matthiasferch/tsm](https://github.com/matthiasferch/tsm) | 61 | `mocha -r ts-node/register test/**/*.spec.ts` | 
| [rcjsuen/dockerfile-language-server-nodejs](https://github.com/rcjsuen/dockerfile-language-server-nodejs) | 61 | `mocha out/test` | 
| [zenclabs/codetree](https://github.com/zenclabs/codetree) | 61 | `mocha -r ts-node/register src/**/*.spec.ts` | 
| [w11k/ngx-componentdestroyed](https://github.com/w11k/ngx-componentdestroyed) | 60 | `mocha --opts spec/mocha.opts src/**/*test.ts` | 
| [AlCalzone/node-tradfri-client](https://github.com/AlCalzone/node-tradfri-client) | 60 | `node_modules/.bin/mocha --watch` | 
| [waitingsong/node-win32-api](https://github.com/waitingsong/node-win32-api) | 60 | `mocha --opts test/mocha.opts` | 
| [wix/rawss](https://github.com/wix/rawss) | 60 | `mocha` | 
| [wearetheledger/fabric-node-chaincode-utils](https://github.com/wearetheledger/fabric-node-chaincode-utils) | 60 | `mocha -r ts-node/register test/**/*.spec.ts --reporter spec` | 
| [nicojs/node-install-local](https://github.com/nicojs/node-install-local) | 59 | `mocha --timeout 30000 test/**/*.js` | 
| [ktsn/vuetype](https://github.com/ktsn/vuetype) | 59 | `rimraf test/fixtures/*.d.ts && mocha --require espower-typescript/guess test/specs/**/*.ts` | 
| [dalenguyen/firestore-backup-restore](https://github.com/dalenguyen/firestore-backup-restore) | 59 | `mocha --timeout 99999999 --exit -r ts-node/register test/**/*.spec.ts` | 
| [mstssk/sw2dts](https://github.com/mstssk/sw2dts) | 58 | `mocha test/*.js` | 
| [longlho/ts-transform-css-modules](https://github.com/longlho/ts-transform-css-modules) | 58 | `rm -rf test/fixture/*.js && mocha --require ts-node/register --recursive  test/**/*.test.ts` | 
| [angular-extensions/model](https://github.com/angular-extensions/model) | 58 | `npm run lint && npm run format:test && nyc mocha {lib,schematics}/**/*.test.ts --require ts-node/register --require source-map-support/register` | 
| [jsonapi-suite/jsorm](https://github.com/jsonapi-suite/jsorm) | 58 | `NODE_ENV=test mocha --opts test/mocha.opts` | 
| [thiagobustamante/typescript-rest-swagger](https://github.com/thiagobustamante/typescript-rest-swagger) | 57 | `cross-env NODE_ENV=test mocha` | 
| [Microsoft/node-jsonc-parser](https://github.com/Microsoft/node-jsonc-parser) | 57 | `npm run compile && mocha` | 
| [yagajs/leaflet-ng2](https://github.com/yagajs/leaflet-ng2) | 57 | `npm run lint && npm run transpile && istanbul cover _mocha -- -- test/*.js` | 
| [mike-lischke/antlr4-c3](https://github.com/mike-lischke/antlr4-c3) | 57 | `tsc --version && tsc && mocha out/test` | 
| [PeculiarVentures/xadesjs](https://github.com/PeculiarVentures/xadesjs) | 57 | `mocha` | 
| [breakstring/xunfeisdk](https://github.com/breakstring/xunfeisdk) | 57 | `tsc && mocha -R nyan -t 15000 -r ts-node/register "./test/**/*.ts"` | 
| [darkoverlordofdata/entitas-ts](https://github.com/darkoverlordofdata/entitas-ts) | 57 | `NODE_ENV=test mocha --compilers coffee:coffee-script --require test/test_helper.js --recursive` | 
| [KennethanCeyer/browser-detect](https://github.com/KennethanCeyer/browser-detect) | 57 | `nyc mocha` | 
| [mono/TsToCSharp](https://github.com/mono/TsToCSharp) | 57 | `npm run lint && mocha  ./dist/TsToCSharpTests.js` | 
| [balmbees/dynamo-types](https://github.com/balmbees/dynamo-types) | 57 | `AWS_REGION=us-east-1 AWS_ACCESS_KEY_ID=mock AWS_SECRET_ACCESS_KEY=mock DYNAMO_TYPES_ENDPOINT=http://127.0.0.1:8000 mocha -t 20000 dst/**/__test__/**/*.js` | 
| [Unibeautify/vscode](https://github.com/Unibeautify/vscode) | 56 | `mocha` | 
| [roginvs/space-rangers-quest](https://github.com/roginvs/space-rangers-quest) | 56 | `nyc --reporter=html --reporter=text mocha --bail built-node/test` | 
| [jeswin/basho](https://github.com/jeswin/basho) | 55 | `./build.sh && mocha dist/test/test.js` | 
| [hg-pyun/iterize](https://github.com/hg-pyun/iterize) | 55 | `mocha --recursive ./test/*.ts --require ts-node/register` | 
| [hazelcast/hazelcast-nodejs-client](https://github.com/hazelcast/hazelcast-nodejs-client) | 55 | `mocha --recursive --reporter-options mochaFile=report.xml --reporter mocha-junit-reporter` | 
| [jupyter-attic/services](https://github.com/jupyter-attic/services) | 55 | `mocha --retries 3 test/build/**/*.spec.js --foo bar --terminalsAvailable True` | 
| [realm/realm-graphql](https://github.com/realm/realm-graphql) | 54 | `mocha --opts config/mocha.opts` | 
| [Anonyfox/vuex-store-module-example](https://github.com/Anonyfox/vuex-store-module-example) | 54 | `rm -rf dist && tsc -p . && npm run lint && mocha dist/test` | 
| [akoenig/gulp-svg2png](https://github.com/akoenig/gulp-svg2png) | 54 | `npm run build && npm run mocha` | 
| [asakusuma/swae](https://github.com/asakusuma/swae) | 54 | `yarn build && rm -rf test/dist && yarn run lint && yarn run build-test && mocha test/dist/test/**/*.spec.js --timeout 15000` | 
| [weaveworks/promjs](https://github.com/weaveworks/promjs) | 54 | `mocha --recursive "test/**/*-test.ts"` | 
| [rauschma/stringio](https://github.com/rauschma/stringio) | 53 | `mocha --ui qunit` | 
| [yesmeck/waque](https://github.com/yesmeck/waque) | 53 | `nyc mocha --forbid-only "test/**/*.test.ts"` | 
| [vechain/thorify](https://github.com/vechain/thorify) | 53 | `NODE_ENV=test mocha --require ts-node/register --timeout 20000 --recursive  --exclude './test/browser/*.ts' './**/*.test.ts'` | 
| [RobotlegsJS/RobotlegsJS](https://github.com/RobotlegsJS/RobotlegsJS) | 53 | `nyc mocha` | 
| [rpgeeganage/ifto](https://github.com/rpgeeganage/ifto) | 53 | `nyc mocha` | 
| [ryanatkn/ear-sharpener](https://github.com/ryanatkn/ear-sharpener) | 53 | `NODE_ENV=test mocha --require ts-node/register --require ignore-styles --require src/test src/**/*/test.{ts,tsx}` | 
| [realm/realm-studio](https://github.com/realm/realm-studio) | 53 | `mocha-webpack --opts=configs/mocha-webpack.opts` | 
| [KennethanCeyer/formulize](https://github.com/KennethanCeyer/formulize) | 53 | `nyc mocha --opts test/mocha.opts` | 
| [hcnode/koa-cola](https://github.com/hcnode/koa-cola) | 52 | `NODE_ENV=test nyc mocha` | 
| [infinum/mobx-jsonapi-store](https://github.com/infinum/mobx-jsonapi-store) | 52 | `NODE_ENV=test nyc mocha` | 
| [Microsoft/vscode-json-languageservice](https://github.com/Microsoft/vscode-json-languageservice) | 52 | `npm run compile && mocha && npm run lint` | 
| [WasabiFan/ev3dev-lang-js](https://github.com/WasabiFan/ev3dev-lang-js) | 52 | `grunt tsc && ./node_modules/mocha/bin/mocha` | 
| [AkashaProject/geth-connector](https://github.com/AkashaProject/geth-connector) | 52 | `./node_modules/istanbul/lib/cli.js cover ./node_modules/.bin/_mocha  ./tests/index.js` | 
| [chanlito/simple-todos](https://github.com/chanlito/simple-todos) | 52 | `cross-env NODE_ENV=test nyc mocha --require test/index.ts --opts test/mocha.opts` | 
| [bougarfaoui/back](https://github.com/bougarfaoui/back) | 52 | `mocha` | 
| [VoxaAI/voxa](https://github.com/VoxaAI/voxa) | 52 | `mocha test/*.spec.* test/**/*.spec.*` | 
| [cartant/rxjs-observe](https://github.com/cartant/rxjs-observe) | 52 | `yarn run lint && yarn run test:build && yarn run test:karma && yarn run test:mocha` | 
| [Lusito/forget-me-not](https://github.com/Lusito/forget-me-not) | 52 | `cross-env TS_NODE_FILES=true nyc mocha test/**/*.ts` | 
| [Fundflow/apollo-redux-form](https://github.com/Fundflow/apollo-redux-form) | 51 | `mocha --reporter spec --full-trace lib/test/tests.js` | 
| [ethereumjs/ethereumjs-blockstream](https://github.com/ethereumjs/ethereumjs-blockstream) | 51 | `mocha --require ts-node/register tests/**/*.ts` | 
| [mrmlnc/emitty](https://github.com/mrmlnc/emitty) | 51 | `mocha out/test/{,**/}*.spec.js -s 0` | 
| [camesine/Typescript-restful-starter](https://github.com/camesine/Typescript-restful-starter) | 51 | `cross-env NODE_ENV=test mocha test/**/*.ts` | 
| [aykutkardas/Json-Function](https://github.com/aykutkardas/Json-Function) | 51 | `cross-env TS_NODE_COMPILER_OPTIONS='{ "module": "commonjs" }' mocha -r ts-node/register -r ignore-styles -r jsdom-global/register test/**/*.spec.ts` | 
| [JBlaak/Express-Torch](https://github.com/JBlaak/Express-Torch) | 51 | `yarn lint && yarn mocha` | 
| [DhyanaChina/todo-live](https://github.com/DhyanaChina/todo-live) | 51 | `mocha` | 
| [argoproj/argo-ui](https://github.com/argoproj/argo-ui) | 50 | `mocha --require ts-node/register ./src/app/**/*.spec.ts` | 
| [HdrHistogram/HdrHistogramJS](https://github.com/HdrHistogram/HdrHistogramJS) | 50 | `mocha --opts mocha.opts --watch` | 
| [sjohnsonaz/cascade](https://github.com/sjohnsonaz/cascade) | 50 | `tsc && node src/mocha/NodeRunner.js` | 
| [tusharmath/rwc](https://github.com/tusharmath/rwc) | 50 | `tsc && mocha -r src/TestSetup.js` | 
| [desertkun/hiera-editor](https://github.com/desertkun/hiera-editor) | 50 | `mocha --timeout 15000 dist/tests/**/*.js` | 
| [jackrobertscott/graphql-api-demo](https://github.com/jackrobertscott/graphql-api-demo) | 50 | `NODE_ENV=test mocha --require=ts-node/register --recursive --exit 'src/**/*.spec.ts'` | 
| [argoproj/argo-ui](https://github.com/argoproj/argo-ui) | 50 | `mocha --require ts-node/register ./src/app/**/*.spec.ts` | 
| [HdrHistogram/HdrHistogramJS](https://github.com/HdrHistogram/HdrHistogramJS) | 50 | `mocha --opts mocha.opts --watch` | 
| [sjohnsonaz/cascade](https://github.com/sjohnsonaz/cascade) | 50 | `tsc && node src/mocha/NodeRunner.js` | 
| [tusharmath/rwc](https://github.com/tusharmath/rwc) | 50 | `tsc && mocha -r src/TestSetup.js` | 
| [desertkun/hiera-editor](https://github.com/desertkun/hiera-editor) | 50 | `mocha --timeout 15000 dist/tests/**/*.js` | 
| [jackrobertscott/graphql-api-demo](https://github.com/jackrobertscott/graphql-api-demo) | 50 | `NODE_ENV=test mocha --require=ts-node/register --recursive --exit 'src/**/*.spec.ts'` | 
| [marcinnajder/powerseq](https://github.com/marcinnajder/powerseq) | 50 | `mocha ./dist/cjs_es6/test -R spec --recursive --timeout 30000` | 
| [stevenxie/express-starter](https://github.com/stevenxie/express-starter) | 50 | `NODE_ENV=test; npm run build; mocha -Sb --exit tests/*.test.js` | 
| [Grademark/grademark](https://github.com/Grademark/grademark) | 50 | `nyc mocha --opts ./src/test/mocha.opts` | 
| [strongloop/loopback4-example-shopping](https://github.com/strongloop/loopback4-example-shopping) | 49 | `lb-mocha --allow-console-logs "dist/test"` | 
| [evansolomon/nodejs-kinesis-client-library](https://github.com/evansolomon/nodejs-kinesis-client-library) | 49 | `npm run lint && mocha` | 
| [seansfkelley/synology-download-manager](https://github.com/seansfkelley/synology-download-manager) | 49 | `TS_NODE_PROJECT=test/tsconfig-test.json mocha --require ts-node/register 'test/**/*.{ts,tsx}'` | 
| [SomeKittens/gustav](https://github.com/SomeKittens/gustav) | 49 | `mocha dist/test` | 
| [tjson/tjson-js](https://github.com/tjson/tjson-js) | 49 | `mocha --compilers ts:ts-node/register --recursive` | 
| [voodooattack/serialism](https://github.com/voodooattack/serialism) | 49 | `nyc mocha --expose-gc --ui mocha-typescript test/test_**.ts` | 
| [soywiz/atpl.js](https://github.com/soywiz/atpl.js) | 49 | `tsc && ./node_modules/.bin/mocha --ui exports --globals name ` | 
| [teppeis/closure-ts](https://github.com/teppeis/closure-ts) | 49 | `npm-run-all --aggregate-output -p lint:ts build -p lint:js mocha` | 
| [adumont/tplink-cloud-api](https://github.com/adumont/tplink-cloud-api) | 48 | `mocha -r ts-node/register -p tsconfig.json lib/**/*.spec.ts` | 
| [mj1618/serverless-offline-sns](https://github.com/mj1618/serverless-offline-sns) | 48 | `nyc ts-mocha "test/**/*.ts" -p src/` | 
| [xmlking/koa-router-decorators](https://github.com/xmlking/koa-router-decorators) | 48 | `mocha .tmp/test/**/*.spec.js` | 
| [BeTomorrow/ReImproveJS](https://github.com/BeTomorrow/ReImproveJS) | 48 | `mocha --reporter spec --compilers ts:ts-node/register 'test/*.spec.ts' --timeout 120000` | 
| [AEB-labs/cruddl](https://github.com/AEB-labs/cruddl) | 48 | `tsc --noEmit --skipLibCheck && mocha --opts ./spec/mocha.opts` | 
| [SPGoding/spu](https://github.com/SPGoding/spu) | 48 | `mocha --require espower-typescript/guess "./src/test/**/*.ts"` | 
| [Microsoft/vscode-html-languageservice](https://github.com/Microsoft/vscode-html-languageservice) | 47 | `npm run compile && mocha && npm run lint` | 
| [NativeScript/nativescript-dev-appium](https://github.com/NativeScript/nativescript-dev-appium) | 47 | `mocha --timeout 999999` | 
| [danrevah/typeserializer](https://github.com/danrevah/typeserializer) | 47 | `NODE_ENV=test mocha -r ts-node/register src/*.spec.ts src/**/*.spec.ts` | 
| [rgraphql/soyuz](https://github.com/rgraphql/soyuz) | 47 | `npm run lint && npm run mocha` | 
| [ryu1kn/vscode-partial-diff](https://github.com/ryu1kn/vscode-partial-diff) | 46 | `mocha --opts cli-test-mocha.opts` | 
| [shlomiassaf/ng-router-loader](https://github.com/shlomiassaf/ng-router-loader) | 46 | `npm run compile_integration && npm run build && ./node_modules/.bin/mocha dist/test spec --recursive` | 
| [sketchglass/respass](https://github.com/sketchglass/respass) | 46 | `NODE_ENV=test mocha lib/test` | 
| [RobinBuschmann/react.di](https://github.com/RobinBuschmann/react.di) | 46 | `mocha` | 
| [ProjectOpenSea/opensea-js](https://github.com/ProjectOpenSea/opensea-js) | 45 | `./node_modules/.bin/mocha test/*.ts --require ts-node/register --timeout 15000` | 
| [brunolm/ts-react-redux-startup](https://github.com/brunolm/ts-react-redux-startup) | 45 | `npm run lint && mocha dist/spec` | 
| [mrmlnc/vscode-csscomb](https://github.com/mrmlnc/vscode-csscomb) | 45 | `mocha out/{,**/}*.spec.js -s 0` | 
| [soraping/koa-ts](https://github.com/soraping/koa-ts) | 45 | `mocha --recursive` | 
| [googleapis/nodejs-spanner](https://github.com/googleapis/nodejs-spanner) | 45 | `nyc mocha build/test` | 
| [rsamec/react-binding](https://github.com/rsamec/react-binding) | 45 | `mocha -R spec ./test` | 
| [rhysd/fixjson](https://github.com/rhysd/fixjson) | 45 | `mocha test` | 
| [ethereum-ts/evm-ts](https://github.com/ethereum-ts/evm-ts) | 44 | `yarn lint && yarn test:mocha` | 
| [sourcegraph/browser-extensions](https://github.com/sourcegraph/browser-extensions) | 44 | `mocha --require ts-node/register --watch --watch-extensions ts './src/**/*.test.ts?(x)'` | 
| [pokemongo-dev-contrib/pokemongo-json-pokedex](https://github.com/pokemongo-dev-contrib/pokemongo-json-pokedex) | 44 | `mocha --recursive --compilers ts:ts-node/register,ts:tsconfig-paths/register test/*.ts test/**/*.ts` | 
| [zaaack/inker](https://github.com/zaaack/inker) | 44 | `electron-mocha --renderer -r ./tools/register "src/test/**.test.ts"` | 
| [dhruvrajvanshi/ts-failable](https://github.com/dhruvrajvanshi/ts-failable) | 44 | `mocha --compilers ts:ts-node/register './test/**/*[tj]s'` | 
| [thundernet8/GithubProfile](https://github.com/thundernet8/GithubProfile) | 44 | `ts-mocha -p ./ test/**/*.spec.ts` | 
| [dirk/hummingbird](https://github.com/dirk/hummingbird) | 43 | `node_modules/.bin/mocha` | 
| [crescware/walts](https://github.com/crescware/walts) | 43 | `npm run build && mocha --require intelli-espower-loader --reporter dot ./test/test.js` | 
| [sebawita/nativescript-angular-cli](https://github.com/sebawita/nativescript-angular-cli) | 43 | `istanbul cover node_modules/mocha/bin/_mocha -- --recursive --reporter spec-xunit-file --require test/test-bootstrap.js --timeout 1000 test/` | 
| [ikr/react-star-rating-input](https://github.com/ikr/react-star-rating-input) | 43 | `mocha -r ts-node/register -r tests/helpers/enzyme -b tests/*.spec.*` | 
| [vilic/thenfail](https://github.com/vilic/thenfail) | 43 | `mocha && npm run aplus` | 
| [Pushwoosh/web-push-notifications](https://github.com/Pushwoosh/web-push-notifications) | 43 | `mocha` | 
| [sourcegraph/sourcegraph-extension-api](https://github.com/sourcegraph/sourcegraph-extension-api) | 43 | `TS_NODE_COMPILER_OPTIONS='{"module":"commonjs"}' mocha --require ts-node/register --require source-map-support/register --opts mocha.opts` | 
| [zswang/icity](https://github.com/zswang/icity) | 43 | `istanbul cover --hook-run-in-context node_modules/mocha/bin/_mocha -- -R spec` | 
| [huang6349/ts-dva](https://github.com/huang6349/ts-dva) | 43 | `atool-test-mocha ./src/**/*-test.js` | 
| [fuse-box/angular2-example](https://github.com/fuse-box/angular2-example) | 43 | `cross-env TS_NODE_PROJECT=./src/tsconfig.mocha.json mocha --opts ./test/mocha.travis.opts` | 
| [Jiasm/typescript-example](https://github.com/Jiasm/typescript-example) | 42 | `mocha -r ts-node/register test/**/*.spec.ts` | 
| [pubkey/solidity-cli](https://github.com/pubkey/solidity-cli) | 42 | `mocha --bail --exit ./dist/test/index.test.js  ./dist/test/integration.test.js` | 
| [olivierlsc/swagger-express-ts](https://github.com/olivierlsc/swagger-express-ts) | 42 | `echo "Testing..." && npm run build && nyc mocha` | 
| [eclipse/sprotty](https://github.com/eclipse/sprotty) | 42 | `jenkins-mocha --opts ./configs/mocha.opts "./src/**/*.spec.?(ts|tsx)"` | 
| [ft-interactive/koa2-typescript-boilerplate](https://github.com/ft-interactive/koa2-typescript-boilerplate) | 42 | `tsc && mocha build/test` | 
| [NEEOInc/neeo-sdk](https://github.com/NEEOInc/neeo-sdk) | 42 | `TS_NODE_PROJECT=./test/tsconfig.json nyc mocha ./test/**/*.ts --opts ./test/mocha.opts` | 
| [aleris/zxing-typescript](https://github.com/aleris/zxing-typescript) | 41 | `mocha --compilers js:babel-core/register "build-node/test/core/**/*.js" --timeout 30000 --colors` | 
| [ivarvh/movielistr-backend-ts-ioc](https://github.com/ivarvh/movielistr-backend-ts-ioc) | 41 | `mocha -r ts-node/register test/**/*.spec.ts` | 
| [stephenmartindale/kgs-leben](https://github.com/stephenmartindale/kgs-leben) | 41 | `gulp build:tests && mocha --timeout 1000 .build/tests.js` | 
| [ShyykoSerhiy/spotilocal](https://github.com/ShyykoSerhiy/spotilocal) | 41 | `./node_modules/typescript/bin/tsc && mocha "dist/test/**/*.js"` | 
| [bitjourney/ci-npm-update](https://github.com/bitjourney/ci-npm-update) | 41 | `TS_NODE_PROJECT=test/tsconfig.json mocha --opts test/support/default.opts test/**/*.test.ts` | 
| [gcanti/hyper-ts](https://github.com/gcanti/hyper-ts) | 41 | `npm run prettier && npm run lint && npm run typings-checker && npm run mocha` | 
| [RobinCK/typeorm-fixtures](https://github.com/RobinCK/typeorm-fixtures) | 41 | `nyc mocha` | 
| [ngParty/ts-helpers](https://github.com/ngParty/ts-helpers) | 41 | `mocha index.test.js` | 
| [just-animate/just-curves](https://github.com/just-animate/just-curves) | 41 | `node_modules/.bin/mocha --require ts-node/register --reporter spec ./tests/**/**.ts` | 
| [Quramy/graphql-decorator](https://github.com/Quramy/graphql-decorator) | 41 | `npm run build && npm run lint && mocha lib/**/*.spec.js` | 
| [microsoftgraph/msgraph-typescript-typings](https://github.com/microsoftgraph/msgraph-typescript-typings) | 41 | `tsc && mocha spec/` | 
| [FontoXML/fontoxpath](https://github.com/FontoXML/fontoxpath) | 41 | `ts-mocha --require test/testhook.js "test/specs/**/*.ts"` | 
| [JoshGlazebrook/smart-buffer](https://github.com/JoshGlazebrook/smart-buffer) | 40 | `NODE_ENV=test mocha --recursive --compilers ts:ts-node/register test/**/*.ts` | 
| [prismicio/prismic-javascript](https://github.com/prismicio/prismic-javascript) | 40 | `mocha` | 
| [AOEpeople/puppeteer-fetchbot](https://github.com/AOEpeople/puppeteer-fetchbot) | 40 | `npm run build && NODE_ENV=testing ./node_modules/.bin/mocha ./dist/lib/**/*.spec.js` | 
| [shogogg/ts-option](https://github.com/shogogg/ts-option) | 40 | `mocha --reporter spec --compilers ts:espower-typescript/guess` | 
| [unbounce/iidy](https://github.com/unbounce/iidy) | 40 | `mocha lib/tests/_init.js lib/tests/**/*js` | 
| [sinnerschrader/aem-react-js](https://github.com/sinnerschrader/aem-react-js) | 40 | `npm run build && npm run lint &&  nyc mocha --compilers ts:espower-typescript/guess test/*.js ` | 
| [realm/realm-graphql-service](https://github.com/realm/realm-graphql-service) | 39 | `mocha --opts ./mocha.opts` | 
| [OmniSharp/omnisharp-node-client](https://github.com/OmniSharp/omnisharp-node-client) | 39 | `tsc && npm run lint && mocha` | 
| [scopsy/node-typescript-starter](https://github.com/scopsy/node-typescript-starter) | 39 | `tsc && mocha dist/**/*.spec.js` | 
| [zalando-incubator/authmosphere](https://github.com/zalando-incubator/authmosphere) | 39 | `npm run build && mocha lib/test lib/integration-test --recursive` | 
| [josephg/statecraft](https://github.com/josephg/statecraft) | 39 | `mocha -r ts-node/register test/*.ts` | 
| [functionalone/aws-least-privilege](https://github.com/functionalone/aws-least-privilege) | 39 | `nyc mocha --require ts-node/register --require source-map-support/register  ./src/test/**/*.test.ts` | 
| [azu/localstorage-ponyfill](https://github.com/azu/localstorage-ponyfill) | 39 | `mocha "test/**/*.ts"` | 
| [jaystack/odata-v4-server](https://github.com/jaystack/odata-v4-server) | 39 | `nyc mocha --reporter mochawesome --reporter-options reportDir=report,reportName=odata-v4-server,reportTitle="OData V4 Server" src/test/**/*.spec.ts` | 
| [indutny/bitcode](https://github.com/indutny/bitcode) | 39 | `npm run mocha && npm run lint` | 
| [aurelia/bundler](https://github.com/aurelia/bundler) | 39 | `mocha --reporter spec --compilers ts:ts-node/register test/**/*.spec.ts` | 
| [aiden/autobot](https://github.com/aiden/autobot) | 39 | `mocha --harmony --require source-map-support/register dist/test --recursive` | 
| [bromne/typescript-optional](https://github.com/bromne/typescript-optional) | 39 | `nyc mocha src/*` | 
| [snaptopixel/vuex-ts-decorators](https://github.com/snaptopixel/vuex-ts-decorators) | 38 | `mocha -r source-map-support/register -r ts-node/register -r es6-promise/auto test/**/*.ts` | 
| [konvajs/ng2-konva](https://github.com/konvajs/ng2-konva) | 38 | `mocha --require ts-node/register test/**/*.spec.ts --recursive` | 
| [ngerakines/express-typescript-sequelize](https://github.com/ngerakines/express-typescript-sequelize) | 38 | `istanbul cover node_modules/mocha/bin/_mocha -x *.spec.js -- --reporter spec` | 
| [home-assistant/home-assistant-js-websocket](https://github.com/home-assistant/home-assistant-js-websocket) | 38 | `mocha test/*.spec.ts` | 
| [RocketChat/Rocket.Chat.js.SDK](https://github.com/RocketChat/Rocket.Chat.js.SDK) | 38 | `nyc mocha './src/lib/**/*.spec.ts'` | 
| [usm4n/cycle-hn](https://github.com/usm4n/cycle-hn) | 38 | `cross-env NODE_ENV=test nyc mocha-webpack --timeout=100000 --colors --webpack-config configs/webpack.config.test.js test/**/*.test.*` | 
| [Webtomizer/typeorm-loader](https://github.com/Webtomizer/typeorm-loader) | 37 | `npm run build && [ -d tests ] && NODE_ENV=test mocha $NODE_DEBUG_OPTION -r ts-node/register -r tslib tests/test_**.ts` | 
| [nickpisacane/mips](https://github.com/nickpisacane/mips) | 37 | `__TS_PROJECT_PATH__=./test ts-mocha test/**/*.test.ts` | 