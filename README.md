# Find Repos in TypeScript Tested using Mocha

The list was updated at 01:56:14 01/22/19 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [Microsoft/vscode](https://github.com/Microsoft/vscode) | 67738 | `mocha` | 
| [ReactiveX/rxjs](https://github.com/ReactiveX/rxjs) | 16739 | `cross-env TS_NODE_PROJECT=spec/tsconfig.json mocha --opts spec/support/default.opts "spec/**/*-spec.ts"` | 
| [nestjs/nest](https://github.com/nestjs/nest) | 11864 | `nyc --require ts-node/register mocha packages/**/*.spec.ts --reporter spec --require 'node_modules/reflect-metadata/Reflect.js'` | 
| [typeorm/typeorm](https://github.com/typeorm/typeorm) | 10507 | `rimraf ./build && tsc && mocha --file ./build/compiled/test/utils/test-setup.js --bail --recursive --timeout 60000 ./build/compiled/test` | 
| [googleapis/google-api-nodejs-client](https://github.com/googleapis/google-api-nodejs-client) | 7079 | `nyc mocha build/test` | 
| [nexe/nexe](https://github.com/nexe/nexe) | 6337 | `mocha` | 
| [xtermjs/xterm.js](https://github.com/xtermjs/xterm.js) | 5546 | `npm run mocha` | 
| [Microsoft/azuredatastudio](https://github.com/Microsoft/azuredatastudio) | 4667 | `mocha` | 
| [palantir/tslint](https://github.com/palantir/tslint) | 4590 | `npm-run-all test:pre -p test:mocha test:rules` | 
| [davidkpiano/xstate](https://github.com/davidkpiano/xstate) | 4351 | `npm run build:cjs && mocha --require ts-node/register test/**.ts test/**/*.test.ts` | 
| [rrweb-io/rrweb](https://github.com/rrweb-io/rrweb) | 3454 | `npm run bundle:browser && cross-env TS_NODE_CACHE=false TS_NODE_FILES=true mocha -r ts-node/register test/**/*.test.ts` | 
| [williamngan/pts](https://github.com/williamngan/pts) | 3413 | `mocha --opts mocha.opts` | 
| [thx/rap2-delos](https://github.com/thx/rap2-delos) | 2983 | `cross-env NODE_ENV=development cross-env TEST_MODE=true nyc mocha --exit` | 
| [vuejs/vue-class-component](https://github.com/vuejs/vue-class-component) | 2882 | `npm run build && webpack --config test/webpack.config.js && mocha test/test.build.js` | 
| [michaelgrosner/tribeca](https://github.com/michaelgrosner/tribeca) | 2869 | `mocha` | 
| [electron-userland/electron-forge](https://github.com/electron-userland/electron-forge) | 2511 | `cross-env TS_NODE_FILES=true yarn run mocha './tools/test-globber.ts' --opts mocha.opts` | 
| [decaffeinate/decaffeinate](https://github.com/decaffeinate/decaffeinate) | 2440 | `mocha 'test/**/*.ts'` | 
| [compodoc/compodoc](https://github.com/compodoc/compodoc) | 2263 | `mocha-parallel-tests test && node test/dist/cli/cli-revert-root-folder.js` | 
| [benjamn/recast](https://github.com/benjamn/recast) | 2188 | `npm run tsc && npm run mocha` | 
| [s-panferov/awesome-typescript-loader](https://github.com/s-panferov/awesome-typescript-loader) | 1908 | `rimraf .test && mocha --trace-warnings --timeout 30000 --exit dist/__test__` | 
| [mgechev/codelyzer](https://github.com/mgechev/codelyzer) | 1894 | `rimraf dist && tsc && ncp test/fixtures dist/test/fixtures && mocha dist/test --recursive` | 
| [yortus/asyncawait](https://github.com/yortus/asyncawait) | 1809 | `mocha` | 
| [staltz/xstream](https://github.com/staltz/xstream) | 1773 | `npm run lint && npm run test-types && npm run mocha && npm run doctest` | 
| [Microsoft/vscode-chrome-debug](https://github.com/Microsoft/vscode-chrome-debug) | 1452 | `mocha --exit --timeout 20000 -s 2000 -u tdd --colors "./out/test/*.test.js"` | 
| [colyseus/colyseus](https://github.com/colyseus/colyseus) | 1425 | `mocha --require ts-node/register test/**Test.ts --exit` | 
| [vscode-icons/vscode-icons](https://github.com/vscode-icons/vscode-icons) | 1422 | `nyc -x '' mocha` | 
| [strongloop/loopback-next](https://github.com/strongloop/loopback-next) | 1355 | `node packages/build/bin/run-nyc npm run mocha --scripts-prepend-node-path` | 
| [shanalikhan/code-settings-sync](https://github.com/shanalikhan/code-settings-sync) | 1314 | `npm run tslint-check && tsc -p ./ && mocha --recursive "./out/test/**/*.js"` | 
| [sveltejs/sapper](https://github.com/sveltejs/sapper) | 1285 | `mocha --opts mocha.opts` | 
| [cherow/cherow](https://github.com/cherow/cherow) | 1249 | `cross-env TS_NODE_PROJECT="test/tsconfig.json" mocha "test/**/*.ts" -c -R progress -r ts-node/register -r source-map-support/register --recursive --globals expect` | 
| [Polymer/polymer-bundler](https://github.com/Polymer/polymer-bundler) | 1233 | `tsc && tslint -c tslint.json src/*.ts src/**/*.ts && mocha` | 
| [funkia/list](https://github.com/funkia/list) | 1229 | `nyc mocha --timeout 10000 --recursive test/*.ts` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1215 | `TS_NODE_PROJECT=tsconfig.test.json mocha **/*.test.ts` | 
| [google/clasp](https://github.com/google/clasp) | 1199 | `nyc --cache false mocha --timeout 100000 -- tests/*.js` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 1134 | `rm -Rf .ts-node && TS_NODE_CACHE_DIRECTORY=.ts-node mocha -r ts-node/register src/**/*.test.ts ./test/*.ts -R spec` | 
| [firebase/geofire-js](https://github.com/firebase/geofire-js) | 1104 | `nyc --reporter=html --reporter=text mocha` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 1070 | `tsc -p ./ && mocha` | 
| [itchio/itch](https://github.com/itchio/itch) | 1007 | `cross-env TS_NODE_PROJECT=tsconfig.test.json mocha -r ts-node/register -r tsconfig-paths/register ./src/**/*.spec.ts` | 
| [WuTheFWasThat/vimflowy](https://github.com/WuTheFWasThat/vimflowy) | 943 | `mocha --opts test/mocha.opts` | 
| [mgechev/ngrev](https://github.com/mgechev/ngrev) | 927 | `electron-mocha app/specs.js.autogenerated --renderer --require source-map-support/register` | 
| [Microsoft/dts-gen](https://github.com/Microsoft/dts-gen) | 901 | `mocha bin/tests/test.js` | 
| [netgusto/nodebook](https://github.com/netgusto/nodebook) | 772 | `mocha test/backend` | 
| [simonbengtsson/jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) | 764 | `mocha --require ts-node/register` | 
| [coinbase/gdax-tt](https://github.com/coinbase/gdax-tt) | 736 | `yarn run lint && yarn run test:mocha` | 
| [iotaledger/iota.js](https://github.com/iotaledger/iota.js) | 727 | `mocha` | 
| [ClusterWS/ClusterWS](https://github.com/ClusterWS/ClusterWS) | 714 | `mocha -r ts-node/register ./tests/specs/*.spec.ts --exit` | 
| [angular/dgeni](https://github.com/angular/dgeni) | 712 | `mocha --require ts-node/register -R spec src/**/*.spec.ts` | 
| [davidkpiano/flipping](https://github.com/davidkpiano/flipping) | 708 | `NODE_ENV=test && mocha -r ts-node/register test/**.test.ts` | 
| [rubyide/vscode-ruby](https://github.com/rubyide/vscode-ruby) | 696 | `node ./node_modules/mocha/bin/mocha --recursive ./out/*.test.js` | 
| [alexjlockwood/avocado](https://github.com/alexjlockwood/avocado) | 671 | `./node_modules/.bin/mocha --require ts-node/register ./test/**/*.spec.ts` | 
| [laoqiren/mlhelper](https://github.com/laoqiren/mlhelper) | 647 | `mocha --recursive` | 
| [mrmlnc/fast-glob](https://github.com/mrmlnc/fast-glob) | 625 | `mocha "out/**/*.spec.js" -s 0` | 
| [opentracing/opentracing-javascript](https://github.com/opentracing/opentracing-javascript) | 610 | `mocha lib/test/unittest.js --check-leaks --color` | 
| [jaysoo/todomvc-redux-react-typescript](https://github.com/jaysoo/todomvc-redux-react-typescript) | 609 | `tsc && mocha --require test-setup --recursive ./dist/**/__spec__/**/*-spec.js` | 
| [JustClear/blurify](https://github.com/JustClear/blurify) | 597 | `mocha test/index.js` | 
| [hacksparrow/node-easyimage](https://github.com/hacksparrow/node-easyimage) | 593 | `npm run lint && npm run mocha` | 
| [veonim/veonim](https://github.com/veonim/veonim) | 590 | `mocha test/unit` | 
| [data-forge/data-forge-ts](https://github.com/data-forge/data-forge-ts) | 585 | `nyc mocha --opts ./src/test/mocha.opts` | 
| [RxJS-CN/RxJS-Docs-CN](https://github.com/RxJS-CN/RxJS-Docs-CN) | 579 | `npm-run-all clean_spec build_spec test_mocha clean_spec` | 
| [googleapis/google-auth-library-nodejs](https://github.com/googleapis/google-auth-library-nodejs) | 576 | `nyc mocha build/test` | 
| [pgilad/leasot](https://github.com/pgilad/leasot) | 574 | `mocha --require ts-node/register -R spec './tests/*.ts'` | 
| [YousefED/typescript-json-schema](https://github.com/YousefED/typescript-json-schema) | 571 | `npm run build && mocha -t 5000 --require source-map-support/register test` | 
| [andrerpena/react-mde](https://github.com/andrerpena/react-mde) | 562 | `mocha --timeout 15000 -r ts-node/register ./test/*Spec.ts` | 
| [brannondorsey/chattervox](https://github.com/brannondorsey/chattervox) | 559 | `mocha test` | 
| [emilioastarita/lyricfier](https://github.com/emilioastarita/lyricfier) | 556 | `mocha` | 
| [SierraSoftworks/Iridium](https://github.com/SierraSoftworks/Iridium) | 539 | `mocha --opts test/mocha.opts dist/test` | 
| [dsherret/ts-simple-ast](https://github.com/dsherret/ts-simple-ast) | 531 | `cross-env TS_NODE_COMPILER="ttypescript" TS_NODE_TRANSPILE_ONLY="true" mocha --opts mocha.opts --grep @performance --invert` | 
| [rill-js/rill](https://github.com/rill-js/rill) | 528 | `nyc --extension=.ts --include=src/**/*.ts --reporter=lcov --reporter=text-summary npm run mocha` | 
| [benjamn/ast-types](https://github.com/benjamn/ast-types) | 497 | `npm run gen && npm run tsc && npm run mocha` | 
| [lukeautry/tsoa](https://github.com/lukeautry/tsoa) | 490 | `cross-env NODE_ENV=tsoa_test mocha **/*.spec.ts --exit --compilers ts:ts-node/register` | 
| [Rich-Harris/devalue](https://github.com/Rich-Harris/devalue) | 488 | `mocha --opts mocha.opts` | 
| [steelsojka/lodash-decorators](https://github.com/steelsojka/lodash-decorators) | 485 | `mocha --opts mocha.opts` | 
| [electron/electron-rebuild](https://github.com/electron/electron-rebuild) | 475 | `mocha --compilers ts:ts-node/register ./test/*.ts` | 
| [sourcegraph/javascript-typescript-langserver](https://github.com/sourcegraph/javascript-typescript-langserver) | 473 | `mocha --require source-map-support/register --timeout 7000 --slow 2000 lib/test/**/*.js` | 
| [championswimmer/vuex-persist](https://github.com/championswimmer/vuex-persist) | 468 | `cd test && mocha -r ts-node/register *.ts` | 
| [firebase/firebase-functions](https://github.com/firebase/firebase-functions) | 465 | `npm run mocha` | 
| [whitecolor/yalc](https://github.com/whitecolor/yalc) | 464 | `tsc && mocha test && yarn lint` | 
| [Cookie-AutoDelete/Cookie-AutoDelete](https://github.com/Cookie-AutoDelete/Cookie-AutoDelete) | 462 | `./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- -R spec ./test/*` | 
| [43081j/rar.js](https://github.com/43081j/rar.js) | 462 | `npm run build && mocha` | 
| [pact-foundation/pact-js](https://github.com/pact-foundation/pact-js) | 453 | `nyc --check-coverage --reporter=html --reporter=text-summary mocha` | 
| [szwacz/fs-jetpack](https://github.com/szwacz/fs-jetpack) | 448 | `mocha -r ts-node/register "spec/**/*.spec.ts"` | 
| [incrediblesound/story-graph](https://github.com/incrediblesound/story-graph) | 444 | `_mocha --` | 
| [vvakame/typescript-formatter](https://github.com/vvakame/typescript-formatter) | 426 | `npm run build && mocha --reporter spec --timeout 20000 --require intelli-espower-loader` | 
| [line/line-bot-sdk-nodejs](https://github.com/line/line-bot-sdk-nodejs) | 409 | `API_BASE_URL=http://localhost:1234/ TEST_PORT=1234 TS_NODE_CACHE=0 nyc mocha` | 
| [felixfbecker/vscode-php-debug](https://github.com/felixfbecker/vscode-php-debug) | 401 | `mocha out/test --timeout 20000 --slow 1000 --retries 4` | 
| [surf-build/surf](https://github.com/surf-build/surf) | 392 | `mocha --compilers ts:ts-node/register ./test/*.ts` | 
| [Asana/typed-react](https://github.com/Asana/typed-react) | 383 | `istanbul cover _mocha -- --reporter ${MOCHA_REPORTER-nyan} --slow 10 --ui tdd --recursive build/**/*_test.js` | 
| [R-js/libRmath.js](https://github.com/R-js/libRmath.js) | 380 | `cross-env-shell NODE_ENV=test TS_NODE_DISABLE_WARNINGS=true nyc mocha` | 
| [itsFrank/vue-typescript](https://github.com/itsFrank/vue-typescript) | 361 | `mocha` | 
| [Polymer/prpl-server](https://github.com/Polymer/prpl-server) | 358 | `npm run build && mocha` | 
| [ngParty/ng-metadata](https://github.com/ngParty/ng-metadata) | 350 | `mocha ./test/index.ts --require ts-node/register --colors --watch-extensions ts` | 
| [arangodb/arangojs](https://github.com/arangodb/arangojs) | 344 | `mocha --growl --reporter spec --require source-map-support/register --timeout 10000 lib/async/test` | 
| [apollographql/persistgraphql](https://github.com/apollographql/persistgraphql) | 343 | `mocha --reporter spec --full-trace lib/test/tests.js` | 
| [Microsoft/node-pty](https://github.com/Microsoft/node-pty) | 340 | `cross-env NODE_ENV=test mocha -R spec --exit lib/*.test.js` | 
| [cartant/rxjs-spy](https://github.com/cartant/rxjs-spy) | 330 | `yarn run lint && yarn run test:build && yarn run test:karma && yarn run test:mocha` | 
| [biesbjerg/ngx-translate-extract](https://github.com/biesbjerg/ngx-translate-extract) | 325 | `mocha -r ts-node/register tests/**/*.spec.ts` | 
| [Canner/apollo-link-firebase](https://github.com/Canner/apollo-link-firebase) | 317 | `TS_NODE_COMPILER_OPTIONS='{"module":"commonjs"}' mocha --timeout 10000 --compilers ts:ts-node/register --recursive --exit "test/**/*.spec.ts"` | 
| [zlq4863947/triangular-arbitrage](https://github.com/zlq4863947/triangular-arbitrage) | 312 | `cross-env NODE_ENV=test mocha dist/**/*.test.js --timeout 5000 --require intelli-espower-loader` | 
| [codemirror/codemirror.next](https://github.com/codemirror/codemirror.next) | 312 | `mocha -r ts-node/register/transpile-only doc/test/test-*.ts state/test/test-*.ts history/test/test-*.ts rangeset/test/test-rangeset.ts keymap/test/test-*.ts legacy-modes/test/test-*.ts extension/test/test-*.ts view/test/test-heightmap.ts` | 
| [GoogleChrome/chrome-launcher](https://github.com/GoogleChrome/chrome-launcher) | 305 | `mocha --require ts-node/register --reporter=dot test/**/*-test.ts --timeout=10000` | 
| [dividab/tsconfig-paths](https://github.com/dividab/tsconfig-paths) | 305 | `mocha` | 
| [alexcambose/motus](https://github.com/alexcambose/motus) | 299 | `cross-env mocha -r ts-node/register 'test/**/*.spec.ts'` | 
| [SweetIQ/schemats](https://github.com/SweetIQ/schemats) | 294 | `npm run lint && npm run build && npm run dependency-check && mocha` | 
| [FinNLP/en-inflectors](https://github.com/FinNLP/en-inflectors) | 291 | `mocha` | 
| [mgechev/aspect.js](https://github.com/mgechev/aspect.js) | 290 | `tsc && mocha -R nyan ./dist/test/**/*.spec.js` | 
| [cbowdon/TsMonad](https://github.com/cbowdon/TsMonad) | 289 | `mocha lib/test` | 
| [cdonohue/polychrome](https://github.com/cdonohue/polychrome) | 280 | `mocha --compilers js:babel-register test/**/*.js` | 
| [spiffcode/ghedit](https://github.com/spiffcode/ghedit) | 277 | `mocha` | 
| [worr/node-imdb-api](https://github.com/worr/node-imdb-api) | 270 | `nyc --require ts-node/register --reporter=lcov node_modules/mocha/bin/mocha test/*.ts` | 
| [albburtsev/bem-cn](https://github.com/albburtsev/bem-cn) | 265 | `mocha src/**/*.spec.ts` | 
| [Kononnable/typeorm-model-generator](https://github.com/Kononnable/typeorm-model-generator) | 257 | `istanbul cover ./node_modules/mocha/bin/_mocha dist/test/**/*.test.js  -- -R spec` | 
| [FormidableLabs/inspectpack](https://github.com/FormidableLabs/inspectpack) | 255 | `mocha "test/**/*.spec.ts"` | 
| [frankwallis/plugin-typescript](https://github.com/frankwallis/plugin-typescript) | 251 | `mocha --require ./test/environment --timeout 10000 ./test/*.ts` | 
| [RisingStack/node-typescript-starter](https://github.com/RisingStack/node-typescript-starter) | 249 | `tsc && mocha dist/**/*.spec.js` | 
| [rubenspgcavalcante/webpack-chrome-extension-reloader](https://github.com/rubenspgcavalcante/webpack-chrome-extension-reloader) | 248 | `NODE_ENV=test webpack && mocha dist/tests.js` | 
| [ReactiveX/rxjs-tslint](https://github.com/ReactiveX/rxjs-tslint) | 248 | `rimraf dist && tsc && mocha -R nyan dist/test --recursive` | 
| [AmirTugi/tea-school](https://github.com/AmirTugi/tea-school) | 246 | `npx ts-mocha ./src/tests/**.ts` | 
| [cyclejs/react-native](https://github.com/cyclejs/react-native) | 245 | `TS_NODE_PROJECT=test/tsconfig.json mocha test/*.ts --require @huston007/react-native-mock/mock.js --require ts-node/register --recursive` | 
| [dolanmiu/docx](https://github.com/dolanmiu/docx) | 244 | `mocha-webpack "src/**/*.ts"` | 
| [SpoonX/wetland](https://github.com/SpoonX/wetland) | 237 | `mocha dist/test/helper dist/test/unit/{*.spec.js,**/*.spec.js} --timeout 15000` | 
| [liangzeng/cqrs](https://github.com/liangzeng/cqrs) | 236 | `tsc && mocha` | 
| [styleguidist/react-docgen-typescript](https://github.com/styleguidist/react-docgen-typescript) | 229 | `tsc && mocha --timeout 10000 ./lib/**/__tests__/**.js` | 
| [duniter/duniter](https://github.com/duniter/duniter) | 226 | `nyc --reporter html mocha` | 
| [renke/import-sort](https://github.com/renke/import-sort) | 225 | `mocha --require ts-node/register --recursive "packages/*/test/**/*.ts"` | 
| [championswimmer/vuex-module-decorators](https://github.com/championswimmer/vuex-module-decorators) | 217 | `cd test && mocha -r ts-node/register *.ts` | 
| [googleapis/nodejs-storage](https://github.com/googleapis/nodejs-storage) | 216 | `nyc mocha build/test` | 
| [Microsoft/vscode-cordova](https://github.com/Microsoft/vscode-cordova) | 215 | `node ./node_modules/mocha/bin/mocha --recursive -u bdd ./out/test/debugger` | 
| [stardustjs/stardust-core](https://github.com/stardustjs/stardust-core) | 211 | `mocha test` | 
| [cartant/rxjs-tslint-rules](https://github.com/cartant/rxjs-tslint-rules) | 210 | `yarn run lint && yarn run test:build && yarn run test:mocha && yarn run test:tslint-v5 && yarn run test:tslint-v6 && yarn run test:tslint-v6-compat` | 
| [thiagobustamante/typescript-rest](https://github.com/thiagobustamante/typescript-rest) | 208 | `cross-env NODE_ENV=test mocha --exit` | 
| [HerringtonDarkholme/av-ts](https://github.com/HerringtonDarkholme/av-ts) | 207 | `mocha dist/test.js` | 
| [jedmao/eclint](https://github.com/jedmao/eclint) | 205 | `nyc npm run mocha -- --reporter lcov --reporter spec` | 
| [R-js/blasjs](https://github.com/R-js/blasjs) | 203 | `cross-env-shell NODE_ENV=test TS_NODE_DISABLE_WARNINGS=true nyc mocha` | 
| [kubernetes-client/javascript](https://github.com/kubernetes-client/javascript) | 202 | `nyc mocha` | 
| [Zarel/Pokemon-Showdown-Client](https://github.com/Zarel/Pokemon-Showdown-Client) | 201 | `eslint --config=.eslintrc.js --cache --cache-file=eslint-cache/base js/ data/ && eslint --config=build-tools/.eslintrc.js --cache --cache-file=eslint-cache/build build-tools/update build-tools/build-indexes && tslint --project . && tsc && node build && mocha` | 
| [zekelevu/typeframework](https://github.com/zekelevu/typeframework) | 200 | `mocha -R spec test/integration` | 
| [fabiandev/ts-runtime](https://github.com/fabiandev/ts-runtime) | 199 | `NODE_ENV=test TS_NODE_CACHE=false ./node_modules/mocha/bin/_mocha` | 
| [bmewburn/intelephense](https://github.com/bmewburn/intelephense) | 199 | `mocha -r ts-node/register test/*.ts` | 
| [Polymer/polyserve](https://github.com/Polymer/polyserve) | 197 | `npm run build && mocha && tslint "src/**/*.ts"` | 
| [microsoftgraph/msgraph-sdk-javascript](https://github.com/microsoftgraph/msgraph-sdk-javascript) | 190 | `mocha lib/spec/core` | 
| [JumpFm/jumpfm](https://github.com/JumpFm/jumpfm) | 189 | `mocha js` | 
| [oclif/cli-ux](https://github.com/oclif/cli-ux) | 189 | `mocha --forbid-only "test/**/*.test.ts"` | 
| [funkia/hareactive](https://github.com/funkia/hareactive) | 186 | `nyc mocha --recursive test/**/*.ts` | 
| [codeaholicguy/wowcup](https://github.com/codeaholicguy/wowcup) | 185 | `nyc mocha --forbid-only "test/**/*.test.ts"` | 
| [felixfbecker/iterare](https://github.com/felixfbecker/iterare) | 173 | `mocha -r source-map-support/register lib/**/*.test.js` | 
| [emmanueltouzery/prelude-ts](https://github.com/emmanueltouzery/prelude-ts) | 173 | `rm tests/apidoc-*; tsc && node ./dist/tests/Comments.js && tsc && ./node_modules/mocha/bin/mocha --throw-deprecation --timeout 60000 ./dist/tests/*.js` | 
| [staltz/html-looks-like](https://github.com/staltz/html-looks-like) | 173 | `npm run lint && npm run mocha` | 
| [brentlintner/synt](https://github.com/brentlintner/synt) | 172 | `globstar -- _mocha "test/spec/**/*.coffee"` | 
| [drew-y/cliffy](https://github.com/drew-y/cliffy) | 169 | `tsc && cd dist && mocha` | 
| [Chinachu/Mirakurun](https://github.com/Chinachu/Mirakurun) | 167 | `mocha --exit test/*.spec.js` | 
| [Polymer/polymer-analyzer](https://github.com/Polymer/polymer-analyzer) | 166 | `npm run clean && npm run build && npm run lint && mocha` | 
| [Microsoft/vscode-node-debug](https://github.com/Microsoft/vscode-node-debug) | 161 | `gulp compile && mocha --timeout 10000 -u tdd ./out/tests/` | 
| [nodejs/llhttp](https://github.com/nodejs/llhttp) | 162 | `npm run mocha && npm run lint` | 
| [Microsoft/vscode-node-debug](https://github.com/Microsoft/vscode-node-debug) | 161 | `gulp compile && mocha --timeout 10000 -u tdd ./out/tests/` | 
| [PeterDing/chord](https://github.com/PeterDing/chord) | 157 | `./node_modules/mocha/bin/mocha --delay` | 
| [googleapis/nodejs-translate](https://github.com/googleapis/nodejs-translate) | 157 | `nyc mocha build/test` | 
| [p-society/typeracer-cli](https://github.com/p-society/typeracer-cli) | 155 | `mocha --no-deprecation --timeout 10000 --require ts-node/register **/*.spec.ts` | 
| [Talento90/typescript-node](https://github.com/Talento90/typescript-node) | 155 | `npm run build && mocha --exit --recursive dist/test/unit` | 
| [Odi-ts/odi](https://github.com/Odi-ts/odi) | 155 | `nyc mocha test/**/*.test.ts --exit` | 
| [danvk/localturk](https://github.com/danvk/localturk) | 153 | `mocha --require ts-node/register test/**/*.ts` | 
| [chenhaozhi/Cpage.js](https://github.com/chenhaozhi/Cpage.js) | 152 | `mocha -r ./node_modules/ts-node/register test/**/*_spec.ts --reporter mochawesome` | 
| [nozer/quill-delta-to-html](https://github.com/nozer/quill-delta-to-html) | 151 | `./node_modules/nyc/bin/nyc.js ./node_modules/mocha/bin/mocha --compilers ts:ts-node/register -b "./test/**/*.ts"  ` | 
| [nestjs/cqrs](https://github.com/nestjs/cqrs) | 149 | `tsc && mocha` | 
| [Commit451/skyhook](https://github.com/Commit451/skyhook) | 149 | `mocha -r ts-node/register test/*.ts` | 
| [Microsoft/vscode-vsce](https://github.com/Microsoft/vscode-vsce) | 148 | `gulp compile && mocha` | 
| [jgranstrom/zipson](https://github.com/jgranstrom/zipson) | 147 | `mocha --require ts-node/register --watch-extensions ts 'test/**/*.ts'` | 
| [calidion/vig](https://github.com/calidion/vig) | 144 | `npm run build && nyc --reporter=text --reporter=html --reporter=lcov mocha --bail --compilers ts:ts-node/register --recursive 'test/**/*.test.ts'` | 
| [ConquestArrow/dtsmake](https://github.com/ConquestArrow/dtsmake) | 143 | `mocha --compilers ts:ts-node/register test/*.ts` | 
| [martysweet/cfn-lint](https://github.com/martysweet/cfn-lint) | 142 | `mocha lib/test` | 
| [cartant/rxjs-marbles](https://github.com/cartant/rxjs-marbles) | 139 | `yarn run lint && yarn run test:build && cross-env FAILING=0 yarn run test:ava && cross-env FAILING=0 yarn run test:jasmine && cross-env FAILING=0 yarn run test:jasmine-angular && cross-env FAILING=0 yarn run test:jest && cross-env FAILING=0 yarn run test:mocha && cross-env FAILING=0 yarn run test:tape` | 
| [geofirestore/geofirestore-js](https://github.com/geofirestore/geofirestore-js) | 139 | `nyc --reporter=html --reporter=text mocha` | 
| [Microsoft/typescript-tslint-plugin](https://github.com/Microsoft/typescript-tslint-plugin) | 138 | `mocha ./out/**/*.test.js --slow 2000 --timeout 10000` | 
| [Half-Shot/matrix-appservice-discord](https://github.com/Half-Shot/matrix-appservice-discord) | 138 | `npm run-script build && mocha --opts test/mocha.opts build/test/config.js build/test` | 
| [Azure/azure-functions-pack](https://github.com/Azure/azure-functions-pack) | 136 | `npm run build && mocha --compilers ts:ts-node/register --recursive test/**/*-spec.ts` | 
| [implydata/plyql](https://github.com/implydata/plyql) | 136 | `mocha` | 
| [DotJoshJohnson/vscode-xml](https://github.com/DotJoshJohnson/vscode-xml) | 135 | `npm run compile && mocha ./out/test/**/*.js` | 
| [Microsoft/monaco-languages](https://github.com/Microsoft/monaco-languages) | 134 | `mocha` | 
| [rangle/typed-immutable-record](https://github.com/rangle/typed-immutable-record) | 133 | `npm run typings  && npm run lint && nyc npm run mocha` | 
| [rhysd/neovim-component](https://github.com/rhysd/neovim-component) | 133 | `mocha test/unit/ --exit` | 
| [nestjs/typeorm](https://github.com/nestjs/typeorm) | 133 | `rimraf ./build && tsc && mocha --file ./build/compiled/test/utils/test-setup.js --bail --recursive --timeout 60000 ./build/compiled/test` | 
| [TrustWallet/trust-ray](https://github.com/TrustWallet/trust-ray) | 133 | `cross-env NODE_ENV=test mocha --recursive --require ts-node/register 'test/**/*.test.ts' --exit` | 
| [atomist/sdm](https://github.com/atomist/sdm) | 132 | `mocha --require espower-typescript/guess "test/**/*.test.ts"` | 
| [vrimar/construct-ui](https://github.com/vrimar/construct-ui) | 131 | `cross-env TS_NODE_PROJECT=test/tsconfig.json mocha` | 
| [Soluto/graphql-to-mongodb](https://github.com/Soluto/graphql-to-mongodb) | 131 | `ts-mocha tests/**/*.spec.ts` | 
| [Urigo/angular-meteor-base](https://github.com/Urigo/angular-meteor-base) | 130 | `TEST_BROWSER_DRIVER=puppeteer meteor test --driver-package=ardatan:mocha --raw-logs` | 
| [Enterprise-JS/vscode-ts-node-debugging](https://github.com/Enterprise-JS/vscode-ts-node-debugging) | 130 | `npm run mocha --recursive ./src/**/__tests__/*` | 
| [rtfeldman/node-elm-compiler](https://github.com/rtfeldman/node-elm-compiler) | 130 | `rm -rf test/fixtures/elm-stuff && mocha test/**/*.ts --require ts-node/register --watch-extensions ts` | 
| [Microsoft/vscode-ios-web-debug](https://github.com/Microsoft/vscode-ios-web-debug) | 129 | `node ./node_modules/mocha/bin/mocha --recursive -u tdd ./out/test/` | 
| [tomastrajan/ngx-model](https://github.com/tomastrajan/ngx-model) | 129 | `npm run clean && tslint *.ts && npm run format:ci && mocha ./lib/model.test.ts --require ts-node/register` | 
| [AzureAD/azure-activedirectory-library-for-nodejs](https://github.com/AzureAD/azure-activedirectory-library-for-nodejs) | 128 | `npm run tsc && mocha -R spec --ui tdd test` | 
| [arusanov/avatar-generator](https://github.com/arusanov/avatar-generator) | 127 | `mocha -r ts-node/register src/**/*.spec.ts` | 
| [mjhea0/typescript-node-api](https://github.com/mjhea0/typescript-node-api) | 127 | `mocha --reporter spec --compilers ts:ts-node/register 'test/**/*.test.ts'` | 
| [arfedulov/semantic-ui-calendar-react](https://github.com/arfedulov/semantic-ui-calendar-react) | 125 | `npx cross-env TS_NODE_COMPILER_OPTIONS="{""allowJs"":true}" npx mocha -r ts-node/register ./test/setup.js ./test/**/*.{js,jsx,ts,tsx}` | 
| [googlearchive/polylint](https://github.com/googlearchive/polylint) | 125 | `bower install && node_modules/.bin/jshint test && node_modules/.bin/mocha test/test.js` | 
| [Glavin001/graphql-sequelize-crud](https://github.com/Glavin001/graphql-sequelize-crud) | 125 | `mocha --require source-map-support/register dist/test` | 
| [tanepiper/node-bitly](https://github.com/tanepiper/node-bitly) | 124 | `VCR_MODE=cache mocha -r ts-node/register --reporter list src/*.spec.ts` | 
| [interledgerjs/ilp](https://github.com/interledgerjs/ilp) | 124 | `istanbul test -- _mocha` | 
| [prh/prh](https://github.com/prh/prh) | 124 | `npm run build && mocha --reporter spec --require intelli-espower-loader` | 
| [bradymholt/cRonstrue](https://github.com/bradymholt/cRonstrue) | 123 | `npx mocha --reporter spec --compilers ts:ts-node/register` | 
| [Goyoo/node-k8s-client](https://github.com/Goyoo/node-k8s-client) | 123 | `mocha test` | 
| [tfoxy/chrome-promise](https://github.com/tfoxy/chrome-promise) | 123 | `mocha --timeout 10000` | 
| [paulcbetts/spawn-rx](https://github.com/paulcbetts/spawn-rx) | 122 | `mocha --compilers ts:ts-node/register ./test/*` | 
| [colyseus/colyseus.js](https://github.com/colyseus/colyseus.js) | 122 | `mocha test/*.ts --require ts-node/register` | 
| [ajafff/tsutils](https://github.com/ajafff/tsutils) | 121 | `mocha test/*Tests.js && tslint --test 'test/rules/**/tslint.json'` | 
| [dsherret/ts-nameof](https://github.com/dsherret/ts-nameof) | 121 | `yarn run --silent copy-test-files && nyc --reporter=lcov mocha --opts mocha.opts` | 
| [nomiclabs/buidler](https://github.com/nomiclabs/buidler) | 119 | `nyc mocha` | 
| [pocesar/node-stratum](https://github.com/pocesar/node-stratum) | 119 | `node ./node_modules/typescript/bin/tsc -p tests.json && mocha test` | 
| [tunnelvisionlabs/antlr4ts](https://github.com/tunnelvisionlabs/antlr4ts) | 118 | `mocha` | 
| [matthew-matvei/freeman](https://github.com/matthew-matvei/freeman) | 116 | `xvfb-maybe electron-mocha --renderer __tests__` | 
| [TreeGateway/tree-gateway](https://github.com/TreeGateway/tree-gateway) | 116 | `cross-env NODE_ENV=test mocha --exit` | 
| [redhat-developer/yaml-language-server](https://github.com/redhat-developer/yaml-language-server) | 115 | `mocha --require ts-node/register --ui tdd ./test/*.test.ts` | 
| [moodysalem/react-tournament-bracket](https://github.com/moodysalem/react-tournament-bracket) | 114 | `mocha --require ts-node/register src/**/*.test.tsx` | 
| [functionalone/serverless-iam-roles-per-function](https://github.com/functionalone/serverless-iam-roles-per-function) | 113 | `nyc mocha --require ts-node/register --require source-map-support/register  ./src/test/**/*.test.ts` | 
| [grantila/fetch-h2](https://github.com/grantila/fetch-h2) | 113 | `npm run lint && node_modules/.bin/nyc --require source-map-support/register npm run mocha` | 
| [Microsoft/TypeScript-TmLanguage](https://github.com/Microsoft/TypeScript-TmLanguage) | 112 | `mocha --full-trace tests/test.js  --reporter mocha-multi-reporters` | 
| [tycho01/typical](https://github.com/tycho01/typical) | 112 | `tsc | tee tsc.log && mocha lib/**/*.test.js 2>&1 | sed 's/[0-9]\+)/×/g' | tee errors.log` | 
| [JoshGlazebrook/socks](https://github.com/JoshGlazebrook/socks) | 111 | `NODE_ENV=test mocha --recursive --compilers ts:ts-node/register test/**/*.ts` | 
| [mgechev/ngresizable](https://github.com/mgechev/ngresizable) | 109 | `mocha --require ts-node/register test/**/*.spec.ts --recursive` | 
| [englercj/tsd-jsdoc](https://github.com/englercj/tsd-jsdoc) | 108 | `mocha --ui tdd -r ts-node/register test/specs/**.ts` | 
| [palantir/typesettable](https://github.com/palantir/typesettable) | 108 | `npm-run-all build test:mocha test:coverage lint` | 
| [IBM/Decentralized-Energy-Composer](https://github.com/IBM/Decentralized-Energy-Composer) | 108 | `mocha --recursive -t 4000` | 
| [Esri/react-arcgis](https://github.com/Esri/react-arcgis) | 108 | `nyc mocha` | 
| [toolness/p5.js-widget](https://github.com/toolness/p5.js-widget) | 108 | `webpack && mocha-phantomjs test/index.html` | 
| [rohitpaulk/todoist-tribute](https://github.com/rohitpaulk/todoist-tribute) | 107 | `mocha --require ts-node/register app/javascript/packs/tests/**/*.ts` | 
| [materiahq/materia-server](https://github.com/materiahq/materia-server) | 107 | `mocha -R spec dist/test/**/*.js` | 
| [Urigo/meteor-rxjs](https://github.com/Urigo/meteor-rxjs) | 107 | `cd tests && meteor test --driver-package practicalmeteor:mocha` | 
| [horiuchi/dtsgenerator](https://github.com/horiuchi/dtsgenerator) | 105 | `istanbul cover _mocha test/*.js test/**/*.js` | 
| [rjmacarthy/express-typescript-starter](https://github.com/rjmacarthy/express-typescript-starter) | 104 | `mocha -r ts-node/register -w ./spec/**/*.spec.ts` | 
| [structured-log/structured-log](https://github.com/structured-log/structured-log) | 104 | `mocha --compilers ts:ts-node/register -r src/polyfills/objectAssign.js test/**/*.spec.ts` | 
| [szdc/tiktok-api](https://github.com/szdc/tiktok-api) | 104 | `TS_NODE_PROJECT=test/tsconfig.json mocha` | 
| [palantir/react-layered-chart](https://github.com/palantir/react-layered-chart) | 104 | `mocha 'test/**/*.ts' && tslint --project tsconfig.json` | 
| [philcockfield/storybook-host](https://github.com/philcockfield/storybook-host) | 103 | `./node_modules/mocha/bin/mocha --require ts-node/register --watch-extensions ts,tsx 'src/**/*.test.ts{,x}'` | 
| [secret-tech/backend-ico-dashboard](https://github.com/secret-tech/backend-ico-dashboard) | 102 | `nyc mocha ./src/**/*.spec.ts --require test/prepare.ts` | 
| [jvilk/MakeTypes](https://github.com/jvilk/MakeTypes) | 101 | `npm-run-all --serial prepublish generate:test build:test mocha` | 
| [mysticatea/vue-eslint-parser](https://github.com/mysticatea/vue-eslint-parser) | 101 | `nyc npm run _mocha` | 
| [atlassian/nucleus](https://github.com/atlassian/nucleus) | 101 | `mocha --compilers ts:ts-node/register src/__spec__/rest.ts src/**/__spec__/*_spec.ts src/**/**/__spec__/*_spec.ts` | 
| [nodejs/llparse](https://github.com/nodejs/llparse) | 101 | `npm run mocha && npm run lint` | 
| [thomasboyt/manygolf](https://github.com/thomasboyt/manygolf) | 101 | `webpack --config webpack/test.js && mocha --no-colors build/test/test.bundle.js` | 
| [wildbit/postmark.js](https://github.com/wildbit/postmark.js) | 101 | `node_modules/mocha/bin/mocha --timeout 10000 --retries 1 -r ts-node/register test/**/*test.ts` | 
| [inversify/inversify-express-example](https://github.com/inversify/inversify-express-example) | 101 | `nyc --clean --all --require ts-node/register --require reflect-metadata/Reflect --extension .ts -- mocha --exit --timeout 5000` | 
| [Kode/KodeStudio](https://github.com/Kode/KodeStudio) | 100 | `mocha` | 
| [metaes/metaes](https://github.com/metaes/metaes) | 99 | `tsc; mocha --recursive lib/ test/runner` | 
| [cartant/ts-action](https://github.com/cartant/ts-action) | 98 | `yarn run lint && yarn run test:build && mocha ./build/**/*-spec.js` | 
| [gcanti/prop-types-ts](https://github.com/gcanti/prop-types-ts) | 97 | `npm run lint && npm run prettier && npm run mocha` | 
| [jf3096/json-typescript-mapper](https://github.com/jf3096/json-typescript-mapper) | 97 | `mocha ./spec/*.js` | 
| [motorcyclejs/motorcyclejs](https://github.com/motorcyclejs/motorcyclejs) | 97 | `northbrook tslint && northbrook mocha && northbrook karma` | 
| [googleapis/nodejs-pubsub](https://github.com/googleapis/nodejs-pubsub) | 97 | `nyc mocha build/test` | 
| [sudheerj/generator-jhipster-primeng](https://github.com/sudheerj/generator-jhipster-primeng) | 97 | `mocha test/* --timeout 500000` | 
| [nucleojs/nucleo](https://github.com/nucleojs/nucleo) | 95 | `mocha -r ts-node/register` | 
| [AkashaProject/ipfs-connector](https://github.com/AkashaProject/ipfs-connector) | 94 | `./node_modules/istanbul/lib/cli.js cover ./node_modules/.bin/_mocha  ./tests.js` | 
| [InCar/ali-mns](https://github.com/InCar/ali-mns) | 94 | `node node_modules/mocha/bin/mocha` | 
| [aurelia/vscode-extension](https://github.com/aurelia/vscode-extension) | 93 | `mocha ./dist/test --recursive` | 
| [ynab/ynab-sdk-js](https://github.com/ynab/ynab-sdk-js) | 93 | `TS_NODE_PROJECT=./test/tsconfig.json npx mocha --reporter spec --require ts-node/register/type-check 'test/**/*.ts'` | 
| [any-json/any-json](https://github.com/any-json/any-json) | 93 | `npm run build && cp -Rf test/fixtures out/test/ && mocha --ui tdd out/test/` | 
| [kimamula/ts-transformer-keys](https://github.com/kimamula/ts-transformer-keys) | 92 | `tsc && node ./test/compileMain.js && mocha ./test/main.js` | 
| [ENikS/LINQ](https://github.com/ENikS/LINQ) | 91 | `mocha test/ --recursive` | 
| [vladotesanovic/typescript-mongoose-express](https://github.com/vladotesanovic/typescript-mongoose-express) | 91 | `mocha` | 
| [levjj/esverify](https://github.com/levjj/esverify) | 91 | `TS_NODE_TRANSPILE_ONLY=true mocha -r ts-node/register tests/*.ts` | 
| [bpatrik/pigallery2](https://github.com/bpatrik/pigallery2) | 90 | `ng test && mocha --recursive test/backend/unit && mocha --recursive test/backend/integration  && mocha --recursive test/common/unit ` | 
| [KarlPurk/redux-decorators](https://github.com/KarlPurk/redux-decorators) | 88 | `webpack --env=test > /dev/null && mocha dist/redux-decorators.spec.js` | 
| [argoproj/argo-ci](https://github.com/argoproj/argo-ci) | 87 | `TS_NODE_PROJECT=./src/tests/tsconfig.json mocha --require ts-node/register ./src/tests/**/*spec.ts` | 
| [carlansley/swagger2-koa](https://github.com/carlansley/swagger2-koa) | 87 | `npm run build && _mocha $(find build -name '*.spec.js') && npm run lint` | 
| [wbhob/nest-middlewares](https://github.com/wbhob/nest-middlewares) | 85 | `nyc --require ts-node/register mocha packages/**/*.spec.ts --reporter spec` | 
| [shlomiassaf/ngc-webpack](https://github.com/shlomiassaf/ngc-webpack) | 83 | `npm run build-test && ./node_modules/.bin/mocha dist/test/*.spec.js --recursive` | 
| [olosegres/jsona](https://github.com/olosegres/jsona) | 83 | `npm run test-compile && env NODE_ENV=test ts-mocha ./**/*.test.ts` | 
| [Cody2333/koa-swagger-decorator](https://github.com/Cody2333/koa-swagger-decorator) | 83 | `./node_modules/mocha/bin/mocha -r babel-core/register test/**/*.js --bail -t 2000000` | 
| [koltyakov/sp-rest-proxy](https://github.com/koltyakov/sp-rest-proxy) | 83 | `ts-node ./test/init && mocha --opts test/mocha.opts || ECHO.` | 
| [redhat-developer/vscode-yaml](https://github.com/redhat-developer/vscode-yaml) | 83 | `mocha --ui tdd out/test/extension.test.js` | 
| [rh389/dynamodb-geo.js](https://github.com/rh389/dynamodb-geo.js) | 82 | `mocha --require ts-node/register test/**/*.ts` | 
| [Azure/azure-cosmos-js](https://github.com/Azure/azure-cosmos-js) | 81 | `mocha -r ./src/test/common/setup.ts ./lib/src/test/ --recursive --timeout 100000 -i -g .*ignore.js` | 
| [flagello/Essence](https://github.com/flagello/Essence) | 81 | `mocha` | 
| [neon-bindings/neon-cli](https://github.com/neon-bindings/neon-cli) | 81 | `npm run transpile && mocha dist/neon-cli-test/acceptance` | 
| [balassy/aws-lambda-typescript](https://github.com/balassy/aws-lambda-typescript) | 80 | `nyc mocha` | 
| [rpgeeganage/async-ray](https://github.com/rpgeeganage/async-ray) | 79 | `nyc mocha` | 
| [googleapis/nodejs-bigquery](https://github.com/googleapis/nodejs-bigquery) | 79 | `nyc mocha build/test` | 
| [teambition/ReactiveDB](https://github.com/teambition/ReactiveDB) | 78 | `npm run lint && NODE_ENV=test tman --mocha spec-js/test/run.js` | 
| [wavesplatform/waves-api](https://github.com/wavesplatform/waves-api) | 78 | `npm run build && ./node_modules/.bin/tsc -p ./test/tsconfig.json && ./node_modules/.bin/mocha $(find ./tmp-node/test -name '*.spec.js')` | 
| [ui-jar/ui-jar](https://github.com/ui-jar/ui-jar) | 78 | `tsc && mocha "dist/test/**/*.js" ` | 
| [yakovlevga/brickyeditor](https://github.com/yakovlevga/brickyeditor) | 78 | `mocha --compilers js:babel-core/register --recursive` | 
| [gcanti/elm-ts](https://github.com/gcanti/elm-ts) | 78 | `npm run lint && npm run mocha` | 
| [CityOfZion/neo-js](https://github.com/CityOfZion/neo-js) | 78 | `mocha --reporter spec` | 
| [MariusAlch/json-to-ts](https://github.com/MariusAlch/json-to-ts) | 77 | `npm run build && mocha ./test/js-integration/index.js && mocha ./build/test` | 
| [Microsoft/vscode-chrome-debug-core](https://github.com/Microsoft/vscode-chrome-debug-core) | 77 | `mocha --exit --recursive -u tdd ./out/test/` | 
| [adrien2p/nestjs-graphql](https://github.com/adrien2p/nestjs-graphql) | 76 | `mocha -r ts-node/register src/**/tests/*.ts` | 
| [codius/codiusd](https://github.com/codius/codiusd) | 76 | `npm run lint && nyc mocha` | 
| [funkia/jabz](https://github.com/funkia/jabz) | 75 | `nyc mocha --recursive test/**/*.ts` | 
| [suksant/sequelize-typescript-examples](https://github.com/suksant/sequelize-typescript-examples) | 75 | `gulp compile && mocha 'build/*/test/**/*.js'` | 
| [AndrewPoyntz/time-ago-pipe](https://github.com/AndrewPoyntz/time-ago-pipe) | 75 | `mocha --reporter spec --require ts-node/register test/**/*.spec.ts` | 
| [timocov/dts-bundle-generator](https://github.com/timocov/dts-bundle-generator) | 74 | `mocha --timeout 10000 --slow 2500 tests/unittests/**/*.spec.js tests/functional-test-cases.js` | 
| [metadevpro/openapi3-ts](https://github.com/metadevpro/openapi3-ts) | 74 | `mocha --recursive --compilers ts:ts-node/register --require source-map-support/register "src/**/*.spec.ts"` | 
| [troch/path-parser](https://github.com/troch/path-parser) | 74 | `mocha -r ts-node/register 'test/main.js'` | 
| [bespoken/virtual-alexa](https://github.com/bespoken/virtual-alexa) | 73 | `nyc mocha lib/**/*Test.js` | 
| [mrmlnc/vscode-scss](https://github.com/mrmlnc/vscode-scss) | 73 | `mocha out/**/*.spec.js` | 
| [balena-io/balena-supervisor](https://github.com/balena-io/balena-supervisor) | 73 | `npm run lint && npm run test:build && JUNIT_REPORT_PATH=report.xml istanbul cover _mocha && npm run coverage` | 
| [hbenl/vscode-firefox-debug](https://github.com/hbenl/vscode-firefox-debug) | 73 | `TS_NODE_FILES=true mocha --opts src/test/mocha.opts "src/test/test*.ts"` | 
| [googleapis/nodejs-datastore](https://github.com/googleapis/nodejs-datastore) | 73 | `nyc mocha build/test` | 
| [Microsoft/vscode-mock-debug](https://github.com/Microsoft/vscode-mock-debug) | 72 | `mocha -u tdd ./out/tests/` | 
| [Microsoft/NoSQLProvider](https://github.com/Microsoft/NoSQLProvider) | 72 | `mocha dist/tests/NoSqlProviderTests.js --timeout 5000` | 
| [hawx1993/judge](https://github.com/hawx1993/judge) | 71 | `mocha --compilers ts:ts-node/register test/test.ts` | 
| [felixfbecker/sequelize-decorators](https://github.com/felixfbecker/sequelize-decorators) | 71 | `mocha dist/test` | 
| [roblox-ts/roblox-ts](https://github.com/roblox-ts/roblox-ts) | 71 | `nyc --reporter=html mocha --timeout 0 --require ts-node/register --require source-map-support/register --recursive src/test.ts && lua tests/spec.lua` | 
| [theGlenn/apollo-prophecy](https://github.com/theGlenn/apollo-prophecy) | 70 | `rm -rf coverage && nyc mocha --opts mocha.opts` | 
| [DavidDuwaer/Coloquent](https://github.com/DavidDuwaer/Coloquent) | 69 | `npm run build && mocha -r ts-node/register tests/**/*.test.ts` | 
| [firebase/firebase-functions-test](https://github.com/firebase/firebase-functions-test) | 69 | `mocha .tmp/spec/index.spec.js` | 
| [Microsoft/vscode-css-languageservice](https://github.com/Microsoft/vscode-css-languageservice) | 69 | `npm run compile && mocha && npm run lint` | 
| [indiejames/vscode-clojure-debug](https://github.com/indiejames/vscode-clojure-debug) | 69 | `node ./node_modules/mocha/bin/mocha -u tdd ./out/tests/` | 
| [AlexGalays/immupdate](https://github.com/AlexGalays/immupdate) | 69 | `mocha test/test.js && node test/testCompilationErrors.js` | 
| [puzzle-js/puzzle-js](https://github.com/puzzle-js/puzzle-js) | 68 | `nyc --check-coverage --lines=85 cross-env NODE_ENV=production mocha -r ts-node/register  --recursive 'test/**/*.spec.ts'` | 
| [Team-CHAD/DevDecks](https://github.com/Team-CHAD/DevDecks) | 68 | `cross-env NODE_ENV=test NODE_PATH=./app BABEL_DISABLE_CACHE=1 mocha --retries 2 --compilers ts:ts-node/register --recursive --require ignore-styles ./test/setup.ts test/**/*.spec.ts test/**/*.spec.tsx` | 
| [PeculiarVentures/graphene](https://github.com/PeculiarVentures/graphene) | 68 | `mocha` | 
| [jinhduong/linq-fns](https://github.com/jinhduong/linq-fns) | 67 | `mocha -r ts-node/register test/*.ts` | 
| [pact-foundation/pact-node](https://github.com/pact-foundation/pact-node) | 67 | `cross-env LOGLEVEL=debug PACT_DO_NOT_TRACK=true mocha -r ts-node/register -R mocha-unfunk-reporter -t 15000 -s 5000 -b --check-leaks --exit "{src,test,bin,standalone}/**/*.spec.ts"` | 
| [Polymer/polymer-editor-service](https://github.com/Polymer/polymer-editor-service) | 67 | `npm run clean && npm run build && mocha && npm run lint` | 
| [alex-okrushko/backoff-rxjs](https://github.com/alex-okrushko/backoff-rxjs) | 66 | `mocha --opts spec/mocha.opts spec/**/*-spec.ts` | 
| [cartant/rxjs-etc](https://github.com/cartant/rxjs-etc) | 66 | `yarn run lint && yarn run test:build && yarn run test:karma && yarn run test:mocha` | 
| [mattlewis92/generator-angular-library](https://github.com/mattlewis92/generator-angular-library) | 66 | `NODE_ENV=test mocha --timeout 300000` | 
| [KoteiIto/node-athena](https://github.com/KoteiIto/node-athena) | 64 | `rm -rf coverage && istanbul cover _mocha -- -R spec build/test/*.js` | 
| [wikiwi/reassemble](https://github.com/wikiwi/reassemble) | 64 | `cross-env TS_NODE_COMPILER_OPTIONS='{"module":"commonjs"}' mocha --opts mocha.opts` | 
| [tinganho/node-accept-language](https://github.com/tinganho/node-accept-language) | 64 | `node node_modules/mocha/bin/mocha Build/Tests/Test.js` | 
| [deerawan/vscode-dash](https://github.com/deerawan/vscode-dash) | 64 | `./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- -R spec --ui tdd ./out/test/extension.test.js` | 
| [interledgerjs/ilp-connector](https://github.com/interledgerjs/ilp-connector) | 64 | `nyc mocha` | 
| [getsentry/sentry-electron](https://github.com/getsentry/sentry-electron) | 64 | `cross-env TS_NODE_PROJECT=tsconfig.json xvfb-maybe electron-mocha --require ts-node/register/transpile-only --timeout 3000 ./test/unit/**/*.ts` | 
| [googleapis/node-gtoken](https://github.com/googleapis/node-gtoken) | 63 | `nyc mocha build/test` | 
| [teamdomy/domy](https://github.com/teamdomy/domy) | 63 | `mocha --reporter spec --require ts-node/register 'tests/**/*.spec.ts'` | 
| [Microsoft/vscode-node-debug2](https://github.com/Microsoft/vscode-node-debug2) | 62 | `mocha --timeout 20000 -s 2000 -u tdd --colors --reporter node_modules/vscode-chrome-debug-core-testsupport/out/loggingReporter.js ./out/test/` | 
| [pdupavillon/express-recaptcha](https://github.com/pdupavillon/express-recaptcha) | 62 | `mocha --compilers ts:ts-node/register test/**/*.spec.ts` | 
| [JustClear/colority](https://github.com/JustClear/colority) | 62 | `mocha test/index.js` | 
| [mceachen/exiftool-vendored.js](https://github.com/mceachen/exiftool-vendored.js) | 62 | `nyc mocha --opts .mocha.opts` | 
| [isc30/linq-collections](https://github.com/isc30/linq-collections) | 62 | `nyc mocha ./build/test/TestSuite.js --slow 0` | 
| [apollographql/graphql-document-collector](https://github.com/apollographql/graphql-document-collector) | 62 | `mocha 'lib/**/__tests__/*.js'` | 
| [HerringtonDarkholme/kilimanjaro](https://github.com/HerringtonDarkholme/kilimanjaro) | 62 | `mocha dist/test/*.js` | 
| [19majkel94/class-transformer-validator](https://github.com/19majkel94/class-transformer-validator) | 61 | `mocha build/tests/index.js` | 
| [zenclabs/codetree](https://github.com/zenclabs/codetree) | 61 | `mocha -r ts-node/register src/**/*.spec.ts` | 
| [matthiasferch/tsm](https://github.com/matthiasferch/tsm) | 60 | `mocha -r ts-node/register test/**/*.spec.ts` | 
| [DhyanaChina/koa2-typescript-guide](https://github.com/DhyanaChina/koa2-typescript-guide) | 60 | `mocha` | 
| [wix/rawss](https://github.com/wix/rawss) | 60 | `mocha` | 
| [NativeScript/nativescript-vscode-extension](https://github.com/NativeScript/nativescript-vscode-extension) | 60 | `mocha --opts ./src/tests/config/mocha.opts` | 
| [SqrTT/prophet](https://github.com/SqrTT/prophet) | 60 | `node ./node_modules/mocha/bin/mocha -u tdd ./out/tests/` | 
| [ktsn/vuetype](https://github.com/ktsn/vuetype) | 59 | `rimraf test/fixtures/*.d.ts && mocha --require espower-typescript/guess test/specs/**/*.ts` | 
| [TonyRobotics/RoboWare-Studio](https://github.com/TonyRobotics/RoboWare-Studio) | 58 | `mocha` | 
| [nicojs/node-install-local](https://github.com/nicojs/node-install-local) | 58 | `mocha --timeout 30000 test/**/*.js` | 
| [mono/TsToCSharp](https://github.com/mono/TsToCSharp) | 58 | `npm run lint && mocha  ./dist/TsToCSharpTests.js` | 
| [yagajs/leaflet-ng2](https://github.com/yagajs/leaflet-ng2) | 57 | `npm run lint && npm run transpile && istanbul cover _mocha -- -- test/*.js` | 
| [longlho/ts-transform-css-modules](https://github.com/longlho/ts-transform-css-modules) | 57 | `rm -rf test/fixture/*.js && mocha --require ts-node/register --recursive  test/**/*.test.ts` | 
| [breakstring/xunfeisdk](https://github.com/breakstring/xunfeisdk) | 57 | `tsc && mocha -R nyan -t 15000 -r ts-node/register "./test/**/*.ts"` | 
| [duffman/tspath](https://github.com/duffman/tspath) | 57 | `mocha -r ts-node/register test/**.*/test.ts` | 
| [mshanemc/shane-sfdx-plugins](https://github.com/mshanemc/shane-sfdx-plugins) | 56 | `mocha --forbid-only "test/**/*.test.ts"` | 
| [AlCalzone/node-tradfri-client](https://github.com/AlCalzone/node-tradfri-client) | 56 | `node_modules/.bin/mocha --watch` | 
| [darkoverlordofdata/entitas-ts](https://github.com/darkoverlordofdata/entitas-ts) | 56 | `NODE_ENV=test mocha --compilers coffee:coffee-script --require test/test_helper.js --recursive` | 
| [ninoseki/mitaka](https://github.com/ninoseki/mitaka) | 56 | `nyc mocha -r ts-node/register "src/**/*.spec.ts"` | 
| [Microsoft/node-jsonc-parser](https://github.com/Microsoft/node-jsonc-parser) | 55 | `npm run compile && mocha` | 
| [jeswin/basho](https://github.com/jeswin/basho) | 55 | `./build.sh && mocha dist/test/test.js` | 
| [PeculiarVentures/xadesjs](https://github.com/PeculiarVentures/xadesjs) | 55 | `mocha` | 
| [lukeautry/ts-app](https://github.com/lukeautry/ts-app) | 55 | `cross-env TS_NODE_PROJECT=./api/tsconfig.json mocha -t 15000 -r ts-node/register "./api/**/*.spec.ts"` | 
| [nhabuiduc/react-filter-box](https://github.com/nhabuiduc/react-filter-box) | 55 | `node --max-old-space-size=16000 ./node_modules/.bin/mocha-webpack --require ignore-styles -r jsdom-global/register --webpack-config webpack.test.config.js --watch "./test/**/*.ts"` | 
| [jsonapi-suite/jsorm](https://github.com/jsonapi-suite/jsorm) | 55 | `NODE_ENV=test mocha --opts test/mocha.opts` | 
| [w11k/ngx-componentdestroyed](https://github.com/w11k/ngx-componentdestroyed) | 54 | `mocha --opts spec/mocha.opts src/**/*test.ts` | 
| [woutervh-/typescript-is](https://github.com/woutervh-/typescript-is) | 54 | `npm run lint && npm run build && ttsc --project tsconfig-test.json && mocha` | 
| [JBlaak/Express-Torch](https://github.com/JBlaak/Express-Torch) | 51 | `yarn lint && yarn mocha` | 
| [DhyanaChina/todo-live](https://github.com/DhyanaChina/todo-live) | 51 | `mocha` | 
| [wearetheledger/fabric-node-chaincode-utils](https://github.com/wearetheledger/fabric-node-chaincode-utils) | 51 | `mocha -r ts-node/register test/**/*.spec.ts --reporter spec` | 
| [realm/realm-graphql](https://github.com/realm/realm-graphql) | 50 | `mocha --opts config/mocha.opts` | 
| [Unibeautify/vscode](https://github.com/Unibeautify/vscode) | 50 | `mocha` | 
| [sjohnsonaz/cascade](https://github.com/sjohnsonaz/cascade) | 50 | `tsc && node src/mocha/NodeRunner.js` | 
| [voodooattack/serialism](https://github.com/voodooattack/serialism) | 50 | `nyc mocha --expose-gc --ui mocha-typescript test/test_**.ts` | 
| [tusharmath/rwc](https://github.com/tusharmath/rwc) | 50 | `tsc && mocha -r src/TestSetup.js` | 
| [VoxaAI/voxa](https://github.com/VoxaAI/voxa) | 50 | `mocha test/*.spec.* test/**/*.spec.*` | 
| [stevenxie/express-starter](https://github.com/stevenxie/express-starter) | 50 | `NODE_ENV=test; npm run build; mocha -Sb --exit tests/*.test.js` | 
| [evansolomon/nodejs-kinesis-client-library](https://github.com/evansolomon/nodejs-kinesis-client-library) | 49 | `npm run lint && mocha` | 
| [Microsoft/vscode-json-languageservice](https://github.com/Microsoft/vscode-json-languageservice) | 49 | `npm run compile && mocha && npm run lint` | 
| [roginvs/space-rangers-quest](https://github.com/roginvs/space-rangers-quest) | 49 | `nyc --reporter=html --reporter=text mocha --bail built-node/test` | 
| [soywiz/atpl.js](https://github.com/soywiz/atpl.js) | 49 | `tsc && ./node_modules/.bin/mocha --ui exports --globals name ` | 
| [teppeis/closure-ts](https://github.com/teppeis/closure-ts) | 49 | `npm-run-all --aggregate-output -p lint:ts build -p lint:js mocha` | 
| [HdrHistogram/HdrHistogramJS](https://github.com/HdrHistogram/HdrHistogramJS) | 48 | `mocha --opts mocha.opts --watch` | 
| [RobotlegsJS/RobotlegsJS](https://github.com/RobotlegsJS/RobotlegsJS) | 52 | `nyc mocha` | 
| [mstssk/sw2dts](https://github.com/mstssk/sw2dts) | 51 | `mocha test/*.js` | 
| [Anonyfox/vuex-store-module-example](https://github.com/Anonyfox/vuex-store-module-example) | 51 | `rm -rf dist && tsc -p . && npm run lint && mocha dist/test` | 
| [hcnode/koa-cola](https://github.com/hcnode/koa-cola) | 51 | `NODE_ENV=test nyc mocha` | 
| [mrmlnc/emitty](https://github.com/mrmlnc/emitty) | 51 | `mocha out/test/{,**/}*.spec.js -s 0` | 
| [rcjsuen/dockerfile-language-server-nodejs](https://github.com/rcjsuen/dockerfile-language-server-nodejs) | 51 | `mocha out/test` | 
| [JBlaak/Express-Torch](https://github.com/JBlaak/Express-Torch) | 51 | `yarn lint && yarn mocha` | 
| [DhyanaChina/todo-live](https://github.com/DhyanaChina/todo-live) | 51 | `mocha` | 
| [wearetheledger/fabric-node-chaincode-utils](https://github.com/wearetheledger/fabric-node-chaincode-utils) | 51 | `mocha -r ts-node/register test/**/*.spec.ts --reporter spec` | 
| [realm/realm-graphql](https://github.com/realm/realm-graphql) | 50 | `mocha --opts config/mocha.opts` | 
| [thiagobustamante/typescript-rest-swagger](https://github.com/thiagobustamante/typescript-rest-swagger) | 50 | `cross-env NODE_ENV=test mocha` | 
| [Unibeautify/vscode](https://github.com/Unibeautify/vscode) | 50 | `mocha` | 
| [sjohnsonaz/cascade](https://github.com/sjohnsonaz/cascade) | 50 | `tsc && node src/mocha/NodeRunner.js` | 
| [AEB-labs/cruddl](https://github.com/AEB-labs/cruddl) | 47 | `tsc --noEmit --skipLibCheck && mocha --opts ./spec/mocha.opts` | 
| [cartant/rxjs-observe](https://github.com/cartant/rxjs-observe) | 47 | `yarn run lint && yarn run test:build && yarn run test:karma && yarn run test:mocha` | 
| [shlomiassaf/ng-router-loader](https://github.com/shlomiassaf/ng-router-loader) | 46 | `npm run compile_integration && npm run build && ./node_modules/.bin/mocha dist/test spec --recursive` | 
| [sketchglass/respass](https://github.com/sketchglass/respass) | 46 | `NODE_ENV=test mocha lib/test` | 
| [NativeScript/nativescript-dev-appium](https://github.com/NativeScript/nativescript-dev-appium) | 46 | `mocha --timeout 999999` | 
| [mj1618/serverless-offline-sns](https://github.com/mj1618/serverless-offline-sns) | 46 | `nyc ts-mocha "test/**/*.ts" -p src/` | 
| [aykutkardas/Json-Function](https://github.com/aykutkardas/Json-Function) | 46 | `cross-env TS_NODE_COMPILER_OPTIONS='{ "module": "commonjs" }' mocha -r ts-node/register -r ignore-styles -r jsdom-global/register test/**/*.spec.ts` | 
| [Lusito/forget-me-not](https://github.com/Lusito/forget-me-not) | 46 | `nyc mocha --require source-map-support/register --require ts-node/register test/**/*.ts` | 
| [ethereumjs/ethereumjs-blockstream](https://github.com/ethereumjs/ethereumjs-blockstream) | 48 | `mocha --require ts-node/register tests/**/*.ts` | 
| [asakusuma/swae](https://github.com/asakusuma/swae) | 48 | `yarn build && rm -rf test/dist && yarn run lint && yarn run build-test && mocha test/dist/test/**/*.spec.js --timeout 15000` | 
| [camesine/Typescript-restful-starter](https://github.com/camesine/Typescript-restful-starter) | 48 | `cross-env NODE_ENV=test mocha test/**/*.ts` | 
| [chanlito/simple-todos](https://github.com/chanlito/simple-todos) | 48 | `cross-env NODE_ENV=test nyc mocha --require test/index.ts --opts test/mocha.opts` | 
| [xmlking/koa-router-decorators](https://github.com/xmlking/koa-router-decorators) | 48 | `mocha .tmp/test/**/*.spec.js` | 
| [marcinnajder/powerseq](https://github.com/marcinnajder/powerseq) | 48 | `mocha ./dist/cjs_es6/test -R spec --recursive --timeout 30000` | 
| [realm/realm-studio](https://github.com/realm/realm-studio) | 48 | `mocha-webpack --opts=configs/mocha-webpack.opts` | 
| [KennethanCeyer/formulize](https://github.com/KennethanCeyer/formulize) | 48 | `nyc mocha --opts test/mocha.opts` | 
| [argoproj/argo-ui](https://github.com/argoproj/argo-ui) | 47 | `mocha --require ts-node/register ./src/app/**/*.spec.ts` | 
| [JustinBeckwith/retry-axios](https://github.com/JustinBeckwith/retry-axios) | 47 | `nyc mocha build/test --timeout 5000 --require source-map-support/register` | 
| [AEB-labs/cruddl](https://github.com/AEB-labs/cruddl) | 47 | `tsc --noEmit --skipLibCheck && mocha --opts ./spec/mocha.opts` | 
| [cartant/rxjs-observe](https://github.com/cartant/rxjs-observe) | 47 | `yarn run lint && yarn run test:build && yarn run test:karma && yarn run test:mocha` | 
| [rgraphql/soyuz](https://github.com/rgraphql/soyuz) | 47 | `npm run lint && npm run mocha` | 
| [SPGoding/spu](https://github.com/SPGoding/spu) | 47 | `mocha --require espower-typescript/guess "./src/test/**/*.ts"` | 
| [shlomiassaf/ng-router-loader](https://github.com/shlomiassaf/ng-router-loader) | 46 | `npm run compile_integration && npm run build && ./node_modules/.bin/mocha dist/test spec --recursive` | 
| [sketchglass/respass](https://github.com/sketchglass/respass) | 46 | `NODE_ENV=test mocha lib/test` | 
| [NativeScript/nativescript-dev-appium](https://github.com/NativeScript/nativescript-dev-appium) | 46 | `mocha --timeout 999999` | 
| [mj1618/serverless-offline-sns](https://github.com/mj1618/serverless-offline-sns) | 46 | `nyc ts-mocha "test/**/*.ts" -p src/` | 
| [aykutkardas/Json-Function](https://github.com/aykutkardas/Json-Function) | 46 | `cross-env TS_NODE_COMPILER_OPTIONS='{ "module": "commonjs" }' mocha -r ts-node/register -r ignore-styles -r jsdom-global/register test/**/*.spec.ts` | 
| [Lusito/forget-me-not](https://github.com/Lusito/forget-me-not) | 46 | `nyc mocha --require source-map-support/register --require ts-node/register test/**/*.ts` | 
| [sourcegraph/browser-extensions](https://github.com/sourcegraph/browser-extensions) | 45 | `mocha --require ts-node/register --watch --watch-extensions ts './src/**/*.test.ts?(x)'` | 
| [sourcegraph/browser-extensions](https://github.com/sourcegraph/browser-extensions) | 45 | `mocha --require ts-node/register --watch --watch-extensions ts './src/**/*.test.ts?(x)'` | 
| [rsamec/react-binding](https://github.com/rsamec/react-binding) | 45 | `mocha -R spec ./test` | 
| [rhysd/fixjson](https://github.com/rhysd/fixjson) | 45 | `mocha test` | 
| [adumont/tplink-cloud-api](https://github.com/adumont/tplink-cloud-api) | 44 | `mocha -r ts-node/register -p tsconfig.json lib/**/*.spec.ts` | 
| [brunolm/ts-react-redux-startup](https://github.com/brunolm/ts-react-redux-startup) | 44 | `npm run lint && mocha dist/spec` | 
| [RobinBuschmann/react.di](https://github.com/RobinBuschmann/react.di) | 44 | `mocha` | 
| [ashleydavis/grademark](https://github.com/ashleydavis/grademark) | 44 | `nyc mocha --opts ./src/test/mocha.opts` | 
| [ryu1kn/vscode-partial-diff](https://github.com/ryu1kn/vscode-partial-diff) | 43 | `mocha --opts cli-test-mocha.opts` | 
| [dirk/hummingbird](https://github.com/dirk/hummingbird) | 43 | `node_modules/.bin/mocha` | 
| [crescware/walts](https://github.com/crescware/walts) | 43 | `npm run build && mocha --require intelli-espower-loader --reporter dot ./test/test.js` | 
| [sebawita/nativescript-angular-cli](https://github.com/sebawita/nativescript-angular-cli) | 43 | `istanbul cover node_modules/mocha/bin/_mocha -- --recursive --reporter spec-xunit-file --require test/test-bootstrap.js --timeout 1000 test/` | 
| [mrmlnc/vscode-csscomb](https://github.com/mrmlnc/vscode-csscomb) | 43 | `mocha out/{,**/}*.spec.js -s 0` | 
| [soraping/koa-ts](https://github.com/soraping/koa-ts) | 43 | `mocha --recursive` | 
| [seansfkelley/synology-download-manager](https://github.com/seansfkelley/synology-download-manager) | 43 | `TS_NODE_PROJECT=test/tsconfig-test.json mocha --require ts-node/register 'test/**/*.{ts,tsx}'` | 
| [ethereum-ts/evm-ts](https://github.com/ethereum-ts/evm-ts) | 43 | `yarn lint && yarn test:mocha` | 
| [googleapis/nodejs-spanner](https://github.com/googleapis/nodejs-spanner) | 43 | `nyc mocha build/test` | 
| [pubkey/solidity-cli](https://github.com/pubkey/solidity-cli) | 43 | `mocha --bail --exit ./dist/test/index.test.js  ./dist/test/integration.test.js` | 
| [sourcegraph/sourcegraph-extension-api](https://github.com/sourcegraph/sourcegraph-extension-api) | 43 | `TS_NODE_COMPILER_OPTIONS='{"module":"commonjs"}' mocha --require ts-node/register --require source-map-support/register --opts mocha.opts` | 
| [zswang/icity](https://github.com/zswang/icity) | 43 | `istanbul cover --hook-run-in-context node_modules/mocha/bin/_mocha -- -R spec` | 
| [fuse-box/angular2-example](https://github.com/fuse-box/angular2-example) | 43 | `cross-env TS_NODE_PROJECT=./src/tsconfig.mocha.json mocha --opts ./test/mocha.travis.opts` | 
| [Pushwoosh/web-push-notifications](https://github.com/Pushwoosh/web-push-notifications) | 42 | `mocha` | 
| [zaaack/inker](https://github.com/zaaack/inker) | 42 | `electron-mocha --renderer -r ./tools/register "src/test/**.test.ts"` | 
| [danrevah/typeserializer](https://github.com/danrevah/typeserializer) | 42 | `NODE_ENV=test mocha -r ts-node/register src/*.spec.ts src/**/*.spec.ts` | 
| [thundernet8/GithubProfile](https://github.com/thundernet8/GithubProfile) | 42 | `ts-mocha -p ./ test/**/*.spec.ts` | 
| [ivarvh/movielistr-backend-ts-ioc](https://github.com/ivarvh/movielistr-backend-ts-ioc) | 41 | `mocha -r ts-node/register test/**/*.spec.ts` | 
| [Jiasm/typescript-example](https://github.com/Jiasm/typescript-example) | 41 | `mocha -r ts-node/register test/**/*.spec.ts` | 
| [vilic/thenfail](https://github.com/vilic/thenfail) | 41 | `mocha && npm run aplus` | 
| [ShyykoSerhiy/spotilocal](https://github.com/ShyykoSerhiy/spotilocal) | 41 | `./node_modules/typescript/bin/tsc && mocha "dist/test/**/*.js"` | 
| [bitjourney/ci-npm-update](https://github.com/bitjourney/ci-npm-update) | 41 | `TS_NODE_PROJECT=test/tsconfig.json mocha --opts test/support/default.opts test/**/*.test.ts` | 
| [olivierlsc/swagger-express-ts](https://github.com/olivierlsc/swagger-express-ts) | 41 | `echo "Testing..." && npm run build && nyc mocha` | 
| [Quramy/graphql-decorator](https://github.com/Quramy/graphql-decorator) | 41 | `npm run build && npm run lint && mocha lib/**/*.spec.js` | 
| [vilic/thenfail](https://github.com/vilic/thenfail) | 41 | `mocha && npm run aplus` | 
| [ShyykoSerhiy/spotilocal](https://github.com/ShyykoSerhiy/spotilocal) | 41 | `./node_modules/typescript/bin/tsc && mocha "dist/test/**/*.js"` | 
| [bitjourney/ci-npm-update](https://github.com/bitjourney/ci-npm-update) | 41 | `TS_NODE_PROJECT=test/tsconfig.json mocha --opts test/support/default.opts test/**/*.test.ts` | 
| [olivierlsc/swagger-express-ts](https://github.com/olivierlsc/swagger-express-ts) | 41 | `echo "Testing..." && npm run build && nyc mocha` | 
| [ft-interactive/koa2-typescript-boilerplate](https://github.com/ft-interactive/koa2-typescript-boilerplate) | 41 | `tsc && mocha build/test` | 
| [ngParty/ts-helpers](https://github.com/ngParty/ts-helpers) | 41 | `mocha index.test.js` | 
| [Quramy/graphql-decorator](https://github.com/Quramy/graphql-decorator) | 41 | `npm run build && npm run lint && mocha lib/**/*.spec.js` | 
| [aleris/zxing-typescript](https://github.com/aleris/zxing-typescript) | 40 | `mocha --compilers js:babel-core/register "build-node/test/core/**/*.js" --timeout 30000 --colors` | 
| [AOEpeople/puppeteer-fetchbot](https://github.com/AOEpeople/puppeteer-fetchbot) | 40 | `npm run build && NODE_ENV=testing ./node_modules/.bin/mocha ./dist/lib/**/*.spec.js` | 
| [stephenmartindale/kgs-leben](https://github.com/stephenmartindale/kgs-leben) | 40 | `gulp build:tests && mocha --timeout 1000 .build/tests.js` | 
| [just-animate/just-curves](https://github.com/just-animate/just-curves) | 40 | `node_modules/.bin/mocha --require ts-node/register --reporter spec ./tests/**/**.ts` | 
| [webix-hub/webix-jet](https://github.com/webix-hub/webix-jet) | 40 | `webpack && phantomjs node_modules/mocha-phantomjs-core/mocha-phantomjs-core.js tests/index.html spec` | 
| [FontoXML/fontoxpath](https://github.com/FontoXML/fontoxpath) | 40 | `ts-mocha --require test/testhook.js "test/specs/**/*.ts"` | 
| [OmniSharp/omnisharp-node-client](https://github.com/OmniSharp/omnisharp-node-client) | 39 | `tsc && npm run lint && mocha` | 
| [realm/realm-graphql-service](https://github.com/realm/realm-graphql-service) | 39 | `mocha --opts ./mocha.opts` | 
| [azu/localstorage-ponyfill](https://github.com/azu/localstorage-ponyfill) | 39 | `mocha "test/**/*.ts"` | 
| [gcanti/hyper-ts](https://github.com/gcanti/hyper-ts) | 39 | `npm run prettier && npm run lint && npm run typings-checker && npm run mocha` | 
| [huang6349/ts-dva](https://github.com/huang6349/ts-dva) | 39 | `atool-test-mocha ./src/**/*-test.js` | 
| [jackrobertscott/graphql-api-demo](https://github.com/jackrobertscott/graphql-api-demo) | 39 | `NODE_ENV=test mocha --require=ts-node/register --recursive --exit 'src/**/*.spec.ts'` | 
| [dhruvrajvanshi/ts-failable](https://github.com/dhruvrajvanshi/ts-failable) | 39 | `mocha --compilers ts:ts-node/register './test/**/*[tj]s'` | 
| [indutny/bitcode](https://github.com/indutny/bitcode) | 39 | `npm run mocha && npm run lint` | 
| [sinnerschrader/aem-react-js](https://github.com/sinnerschrader/aem-react-js) | 39 | `npm run build && npm run lint &&  nyc mocha --compilers ts:espower-typescript/guess test/*.js ` | 
| [aurelia/bundler](https://github.com/aurelia/bundler) | 39 | `mocha --reporter spec --compilers ts:ts-node/register test/**/*.spec.ts` | 
| [aiden/autobot](https://github.com/aiden/autobot) | 39 | `mocha --harmony --require source-map-support/register dist/test --recursive` | 
| [scopsy/node-typescript-starter](https://github.com/scopsy/node-typescript-starter) | 38 | `tsc && mocha dist/**/*.spec.js` | 
| [ngerakines/express-typescript-sequelize](https://github.com/ngerakines/express-typescript-sequelize) | 38 | `istanbul cover node_modules/mocha/bin/_mocha -x *.spec.js -- --reporter spec` | 
| [pokemongo-dev-contrib/pokemongo-json-pokedex](https://github.com/pokemongo-dev-contrib/pokemongo-json-pokedex) | 38 | `mocha --recursive --compilers ts:ts-node/register,ts:tsconfig-paths/register test/*.ts test/**/*.ts` | 
| [shogogg/ts-option](https://github.com/shogogg/ts-option) | 38 | `mocha --reporter spec --compilers ts:espower-typescript/guess` | 
| [functionalone/aws-least-privilege](https://github.com/functionalone/aws-least-privilege) | 38 | `nyc mocha --require ts-node/register --require source-map-support/register  ./src/test/**/*.test.ts` | 
| [ProjectOpenSea/opensea-js](https://github.com/ProjectOpenSea/opensea-js) | 37 | `./node_modules/.bin/mocha test/*.ts --require ts-node/register --timeout 15000` | 
| [JoshGlazebrook/smart-buffer](https://github.com/JoshGlazebrook/smart-buffer) | 37 | `NODE_ENV=test mocha --recursive --compilers ts:ts-node/register test/**/*.ts` | 
| [prismicio/prismic-javascript](https://github.com/prismicio/prismic-javascript) | 37 | `mocha` | 
| [zalando-incubator/authmosphere](https://github.com/zalando-incubator/authmosphere) | 37 | `npm run build && mocha lib/test lib/integration-test --recursive` | 
| [BeTomorrow/ReImproveJS](https://github.com/BeTomorrow/ReImproveJS) | 37 | `mocha --reporter spec --compilers ts:ts-node/register 'test/*.spec.ts' --timeout 120000` | 
| [unbounce/iidy](https://github.com/unbounce/iidy) | 37 | `mocha lib/tests/_init.js lib/tests/**/*js` | 
| [jaystack/odata-v4-server](https://github.com/jaystack/odata-v4-server) | 37 | `nyc mocha --reporter mochawesome --reporter-options reportDir=report,reportName=odata-v4-server,reportTitle="OData V4 Server" src/test/**/*.spec.ts` | 
| [microsoftgraph/msgraph-typescript-typings](https://github.com/microsoftgraph/msgraph-typescript-typings) | 37 | `tsc && mocha spec/` | 
| [snaptopixel/vuex-ts-decorators](https://github.com/snaptopixel/vuex-ts-decorators) | 36 | `mocha -r source-map-support/register -r ts-node/register -r es6-promise/auto test/**/*.ts` | 
| [Polymer/polymer-linter](https://github.com/Polymer/polymer-linter) | 36 | `npm run build && mocha && npm run lint` | 
| [acrazing/mobx-sync](https://github.com/acrazing/mobx-sync) | 36 | `mocha --require ts-node/register --slow 1000 ./src/**/*.spec.ts` | 
| [home-assistant/home-assistant-js-websocket](https://github.com/home-assistant/home-assistant-js-websocket) | 36 | `mocha test/*.spec.ts` | 
| [usm4n/cycle-hn](https://github.com/usm4n/cycle-hn) | 36 | `cross-env NODE_ENV=test nyc mocha-webpack --timeout=100000 --colors --webpack-config configs/webpack.config.test.js test/**/*.test.*` | 
| [paralin/grpc-bus](https://github.com/paralin/grpc-bus) | 36 | `npm run lint && npm run mocha` | 
| [Jason3S/rx-stream](https://github.com/Jason3S/rx-stream) | 36 | `mocha --recursive "dist/**/*.test.js"` | 
| [infinum/mobx-collection-store](https://github.com/infinum/mobx-collection-store) | 36 | `NODE_ENV=test nyc mocha` | 
| [fyndme/messenger-bot-tester](https://github.com/fyndme/messenger-bot-tester) | 35 | `mocha ./test-build` | 
| [nickpisacane/mips](https://github.com/nickpisacane/mips) | 35 | `__TS_PROJECT_PATH__=./test ts-mocha test/**/*.test.ts` | 
| [tsframework/ts-framework](https://github.com/tsframework/ts-framework) | 35 | `mocha build-test --recursive` | 
| [agea/CmisJS](https://github.com/agea/CmisJS) | 35 | `tsc && mocha dist/**/*.spec.js` | 
| [utopian-io/api.utopian.io](https://github.com/utopian-io/api.utopian.io) | 35 | `cross-env NODE_ENV=test npx mocha --ui bdd --reporter spec --colors --recursive -r ts-node/register tests/index.ts` | 
| [tuzhanai/captcha](https://github.com/tuzhanai/captcha) | 35 | `mocha -b --require ts-node/register --require source-map-support/register --recursive --exit src/test.ts` | 
| [bpowers/sd.js](https://github.com/bpowers/sd.js) | 35 | `tsc -p .tsconfig.test.json && mocha` | 
| [ste-vg/pop.svg](https://github.com/ste-vg/pop.svg) | 35 | `nyc mocha --require ./mocha.config.js -r ts-node/register 'src/**/*.spec.ts'  --exit --recursive --timeout 10000` | 
| [Rich-Harris/port-authority](https://github.com/Rich-Harris/port-authority) | 35 | `mocha --opts mocha.opts` | 
| [masvis/angular4-hal](https://github.com/masvis/angular4-hal) | 35 | `mocha -r ts-node/register --config=test/test-config.json test/*.test.ts` | 
| [secret-tech/backend-token-wallets](https://github.com/secret-tech/backend-token-wallets) | 35 | `mocha -r ts-node/register -r test/prepare.ts src/**/*.spec.ts` | 
| [mrmlnc/vscode-stylefmt](https://github.com/mrmlnc/vscode-stylefmt) | 34 | `mocha out/**/*.spec.js -s 0` | 
| [Webtomizer/typeorm-loader](https://github.com/Webtomizer/typeorm-loader) | 34 | `npm run build && [ -d tests ] && NODE_ENV=test mocha $NODE_DEBUG_OPTION -r ts-node/register -r tslib tests/test_**.ts` | 
| [josephg/statecraft](https://github.com/josephg/statecraft) | 34 | `mocha -r ts-node/register test/*.ts` | 
| [larshp/abaplint](https://github.com/larshp/abaplint) | 34 | `mocha --recursive --reporter progress build/test` | 
| [leizongmin/leizm-web](https://github.com/leizongmin/leizm-web) | 34 | `npm run format && mocha --require ts-node/register --exit "src/test/**/*.ts"` | 
| [Draccoz/twc](https://github.com/Draccoz/twc) | 34 | `npm run lint && mocha --require ts-node/register --ui bdd tests/tests.spec.ts` | 
| [davetemplin/web-request](https://github.com/davetemplin/web-request) | 34 | `mocha` | 
| [mulesoft-labs/yaml-ast-parser](https://github.com/mulesoft-labs/yaml-ast-parser) | 34 | `npm run build && mocha --ui tdd dist/test` | 
| [forthright/vile](https://github.com/forthright/vile) | 34 | `globstar -- _mocha "test/spec/**/*.coffee"` | 
| [supergraphql/supergraph](https://github.com/supergraphql/supergraph) | 34 | `nyc mocha ./dist/**/*.spec.js` | 
| [lebinh/cloudflare-workers](https://github.com/lebinh/cloudflare-workers) | 33 | `mocha -r ts-node/register 'tests/**/*_test.ts'` | 
| [Azure/oav](https://github.com/Azure/oav) | 33 | `npm run tsc && npm run tslint && nyc mocha ./dist/test/**/*.js -t 10000 --reporter mocha-junit-reporter --reporter spec` | 
| [mixi-inc/css-semdiff](https://github.com/mixi-inc/css-semdiff) | 33 | `mocha --opts mocha.opts './dist/**/*.test.js'` | 
| [yesmeck/waque](https://github.com/yesmeck/waque) | 33 | `nyc mocha --forbid-only "test/**/*.test.ts"` | 
| [strongloop/loopback4-example-shopping](https://github.com/strongloop/loopback4-example-shopping) | 33 | `lb-mocha --allow-console-logs "dist/test"` | 