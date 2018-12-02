# Find Repos in TypeScript Tested using Mocha

The list was updated at 01:55:07 12/02/18 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [Microsoft/vscode](https://github.com/Microsoft/vscode) | 64897 | `mocha` | 
| [ReactiveX/rxjs](https://github.com/ReactiveX/rxjs) | 16011 | `cross-env TS_NODE_PROJECT=spec/tsconfig.json mocha --opts spec/support/default.opts "spec/**/*-spec.ts"` | 
| [nestjs/nest](https://github.com/nestjs/nest) | 10487 | `nyc --require ts-node/register mocha packages/**/*.spec.ts --reporter spec --require 'node_modules/reflect-metadata/Reflect.js'` | 
| [typeorm/typeorm](https://github.com/typeorm/typeorm) | 9422 | `rimraf ./build && tsc && mocha --file ./build/compiled/test/utils/test-setup.js --bail --recursive --timeout 30000  ./build/compiled/test` | 
| [sveltejs/svelte](https://github.com/sveltejs/svelte) | 8569 | `mocha --opts mocha.opts` | 
| [googleapis/google-api-nodejs-client](https://github.com/googleapis/google-api-nodejs-client) | 6946 | `nyc mocha build/test` | 
| [nexe/nexe](https://github.com/nexe/nexe) | 6080 | `mocha` | 
| [xtermjs/xterm.js](https://github.com/xtermjs/xterm.js) | 5210 | `npm run mocha` | 
| [Microsoft/azuredatastudio](https://github.com/Microsoft/azuredatastudio) | 4546 | `mocha` | 
| [palantir/tslint](https://github.com/palantir/tslint) | 4280 | `npm-run-all test:pre -p test:mocha test:rules` | 
| [davidkpiano/xstate](https://github.com/davidkpiano/xstate) | 3733 | `npm run build:cjs && mocha --require ts-node/register test/**.ts test/**/*.test.ts` | 
| [williamngan/pts](https://github.com/williamngan/pts) | 3365 | `mocha --opts mocha.opts` | 
| [michaelgrosner/tribeca](https://github.com/michaelgrosner/tribeca) | 2812 | `mocha` | 
| [vuejs/vue-class-component](https://github.com/vuejs/vue-class-component) | 2666 | `npm run build && webpack --config test/webpack.config.js && mocha test/test.build.js` | 
| [thx/rap2-delos](https://github.com/thx/rap2-delos) | 2592 | `cross-env NODE_ENV=development cross-env TEST_MODE=true nyc mocha --exit` | 
| [decaffeinate/decaffeinate](https://github.com/decaffeinate/decaffeinate) | 2426 | `mocha 'test/**/*.ts'` | 
| [electron-userland/electron-forge](https://github.com/electron-userland/electron-forge) | 2372 | `cross-env TS_NODE_FILES=true yarn run mocha './tools/test-globber.ts' --opts mocha.opts` | 
| [compodoc/compodoc](https://github.com/compodoc/compodoc) | 2162 | `mocha-parallel-tests test && node test/dist/cli/cli-revert-root-folder.js` | 
| [mgechev/codelyzer](https://github.com/mgechev/codelyzer) | 1852 | `rimraf dist && tsc && ncp test/fixtures dist/test/fixtures && mocha dist/test --recursive` | 
| [s-panferov/awesome-typescript-loader](https://github.com/s-panferov/awesome-typescript-loader) | 1840 | `rimraf .test && mocha --trace-warnings --timeout 30000 --exit dist/__test__` | 
| [yortus/asyncawait](https://github.com/yortus/asyncawait) | 1792 | `mocha` | 
| [staltz/xstream](https://github.com/staltz/xstream) | 1728 | `npm run lint && npm run test-types && npm run mocha && npm run doctest` | 
| [burtonator/polar-bookshelf](https://github.com/burtonator/polar-bookshelf) | 1649 | `find web/js -name '*Test.js' | xargs mocha-parallel-tests --timeout 20000 --max-parallel=1 --exit` | 
| [Microsoft/vscode-chrome-debug](https://github.com/Microsoft/vscode-chrome-debug) | 1396 | `mocha --exit --timeout 20000 -s 2000 -u tdd --colors "./out/test/*.test.js"` | 
| [vscode-icons/vscode-icons](https://github.com/vscode-icons/vscode-icons) | 1351 | `nyc -x '' mocha` | 
| [gamestdio/colyseus](https://github.com/gamestdio/colyseus) | 1327 | `mocha --require ts-node/register test/**Test.ts --exit` | 
| [Polymer/polymer-bundler](https://github.com/Polymer/polymer-bundler) | 1233 | `tsc && tslint -c tslint.json src/*.ts src/**/*.ts && mocha` | 
| [funkia/list](https://github.com/funkia/list) | 1211 | `nyc mocha --timeout 10000 --recursive test/*.ts` | 
| [strongloop/loopback-next](https://github.com/strongloop/loopback-next) | 1198 | `node packages/build/bin/run-nyc npm run mocha --scripts-prepend-node-path` | 
| [sveltejs/sapper](https://github.com/sveltejs/sapper) | 1193 | `mocha --opts mocha.opts` | 
| [jakubroztocil/rrule](https://github.com/jakubroztocil/rrule) | 1177 | `TS_NODE_PROJECT=tsconfig.test.json mocha **/*.test.ts` | 
| [shanalikhan/code-settings-sync](https://github.com/shanalikhan/code-settings-sync) | 1146 | `npm run vscode:prepublish && node ./node_modules/bin/mocha --recursive` | 
| [Keyang/node-csvtojson](https://github.com/Keyang/node-csvtojson) | 1103 | `rm -Rf .ts-node && TS_NODE_CACHE_DIRECTORY=.ts-node mocha -r ts-node/register src/**/*.test.ts ./test/*.ts -R spec` | 
| [firebase/geofire-js](https://github.com/firebase/geofire-js) | 1090 | `nyc --reporter=html --reporter=text mocha` | 
| [google/clasp](https://github.com/google/clasp) | 1048 | `nyc --cache false mocha --timeout 100000 -- tests/*.js` | 
| [extrabacon/python-shell](https://github.com/extrabacon/python-shell) | 1033 | `tsc -p ./ && mocha` | 
| [itchio/itch](https://github.com/itchio/itch) | 953 | `cross-env TS_NODE_PROJECT=tsconfig.test.json mocha -r ts-node/register -r tsconfig-paths/register ./src/**/*.spec.ts` | 
| [WuTheFWasThat/vimflowy](https://github.com/WuTheFWasThat/vimflowy) | 926 | `mocha --opts test/mocha.opts` | 
| [mgechev/ngrev](https://github.com/mgechev/ngrev) | 889 | `electron-mocha app/specs.js.autogenerated --renderer --require source-map-support/register` | 
| [Microsoft/dts-gen](https://github.com/Microsoft/dts-gen) | 849 | `mocha bin/tests/test.js` | 
| [netgusto/nodebook](https://github.com/netgusto/nodebook) | 764 | `mocha test/backend` | 
| [coinbase/gdax-tt](https://github.com/coinbase/gdax-tt) | 731 | `yarn run lint && yarn run test:mocha` | 
| [simonbengtsson/jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) | 718 | `mocha --compilers ts:ts-node/register test/*.js || true` | 
| [angular/dgeni](https://github.com/angular/dgeni) | 711 | `mocha --require ts-node/register -R spec src/**/*.spec.ts` | 
| [iotaledger/iota.js](https://github.com/iotaledger/iota.js) | 701 | `mocha` | 
| [ClusterWS/ClusterWS](https://github.com/ClusterWS/ClusterWS) | 689 | `mocha -r ts-node/register ./tests/specs/*.spec.ts --exit` | 
| [davidkpiano/flipping](https://github.com/davidkpiano/flipping) | 656 | `NODE_ENV=test && mocha -r ts-node/register test/**.test.ts` | 
| [rubyide/vscode-ruby](https://github.com/rubyide/vscode-ruby) | 653 | `node ./node_modules/mocha/bin/mocha --recursive ./out/*.test.js` | 
| [alexjlockwood/avocado](https://github.com/alexjlockwood/avocado) | 648 | `./node_modules/.bin/mocha --require ts-node/register ./test/**/*.spec.ts` | 
| [laoqiren/mlhelper](https://github.com/laoqiren/mlhelper) | 647 | `mocha --recursive` | 
| [jaysoo/todomvc-redux-react-typescript](https://github.com/jaysoo/todomvc-redux-react-typescript) | 607 | `tsc && mocha --require test-setup --recursive ./dist/**/__spec__/**/*-spec.js` | 
| [mrmlnc/fast-glob](https://github.com/mrmlnc/fast-glob) | 594 | `mocha "out/**/*.spec.js" -s 0` | 
| [hacksparrow/node-easyimage](https://github.com/hacksparrow/node-easyimage) | 588 | `npm run lint && npm run mocha` | 
| [opentracing/opentracing-javascript](https://github.com/opentracing/opentracing-javascript) | 575 | `mocha lib/test/unittest.js --check-leaks --color` | 
| [RxJS-CN/RxJS-Docs-CN](https://github.com/RxJS-CN/RxJS-Docs-CN) | 554 | `npm-run-all clean_spec build_spec test_mocha clean_spec` | 
| [emilioastarita/lyricfier](https://github.com/emilioastarita/lyricfier) | 551 | `mocha` | 
| [brannondorsey/chattervox](https://github.com/brannondorsey/chattervox) | 544 | `mocha test` | 
| [SierraSoftworks/Iridium](https://github.com/SierraSoftworks/Iridium) | 536 | `mocha --opts test/mocha.opts dist/test` | 
| [andrerpena/react-mde](https://github.com/andrerpena/react-mde) | 532 | `mocha --timeout 15000 -r ts-node/register ./test/*Spec.ts` | 
| [rill-js/rill](https://github.com/rill-js/rill) | 526 | `nyc --extension=.ts --include=src/**/*.ts --reporter=lcov --reporter=text-summary npm run mocha` | 
| [data-forge/data-forge-ts](https://github.com/data-forge/data-forge-ts) | 524 | `nyc mocha --opts ./src/test/mocha.opts` | 
| [pgilad/leasot](https://github.com/pgilad/leasot) | 522 | `mocha --require ts-node/register -R spec './tests/*.ts'` | 
| [YousefED/typescript-json-schema](https://github.com/YousefED/typescript-json-schema) | 515 | `npm run build && mocha -t 5000 --require source-map-support/register test` | 
| [Rich-Harris/devalue](https://github.com/Rich-Harris/devalue) | 479 | `mocha --opts mocha.opts` | 
| [electron/electron-rebuild](https://github.com/electron/electron-rebuild) | 463 | `mocha --compilers ts:ts-node/register ./test/*.ts` | 
| [43081j/rar.js](https://github.com/43081j/rar.js) | 462 | `npm run build && mocha` | 
| [dsherret/ts-simple-ast](https://github.com/dsherret/ts-simple-ast) | 457 | `cross-env TS_NODE_COMPILER="ttypescript" TS_NODE_TRANSPILE_ONLY="true" mocha --opts mocha.opts --grep @performance --invert` | 
| [steelsojka/lodash-decorators](https://github.com/steelsojka/lodash-decorators) | 456 | `mocha --opts mocha.opts` | 
| [lukeautry/tsoa](https://github.com/lukeautry/tsoa) | 450 | `cross-env NODE_ENV=test mocha **/*.spec.ts --compilers ts:ts-node/register` | 
| [incrediblesound/story-graph](https://github.com/incrediblesound/story-graph) | 444 | `_mocha --` | 
| [firebase/firebase-functions](https://github.com/firebase/firebase-functions) | 444 | `npm run mocha` | 
| [sourcegraph/javascript-typescript-langserver](https://github.com/sourcegraph/javascript-typescript-langserver) | 440 | `mocha --require source-map-support/register --timeout 7000 --slow 2000 lib/test/**/*.js` | 
| [szwacz/fs-jetpack](https://github.com/szwacz/fs-jetpack) | 435 | `mocha -r ts-node/register "spec/**/*.spec.ts"` | 
| [Romakita/ts-express-decorators](https://github.com/Romakita/ts-express-decorators) | 427 | `npm run clean && npm run tsc && npm run tslint && cross-env NODE_ENV=test nyc --reporter=html --reporter=text _mocha --recursive` | 
| [pact-foundation/pact-js](https://github.com/pact-foundation/pact-js) | 426 | `nyc --check-coverage --reporter=html --reporter=text-summary mocha` | 
| [vvakame/typescript-formatter](https://github.com/vvakame/typescript-formatter) | 415 | `npm run build && mocha --reporter spec --timeout 20000 --require intelli-espower-loader` | 
| [championswimmer/vuex-persist](https://github.com/championswimmer/vuex-persist) | 402 | `cd test && mocha -r ts-node/register *.ts` | 
| [felixfbecker/vscode-php-debug](https://github.com/felixfbecker/vscode-php-debug) | 392 | `mocha out/test --timeout 20000 --slow 1000 --retries 4` | 
| [line/line-bot-sdk-nodejs](https://github.com/line/line-bot-sdk-nodejs) | 391 | `API_BASE_URL=http://localhost:1234/ TEST_PORT=1234 TS_NODE_CACHE=0 nyc mocha` | 
| [surf-build/surf](https://github.com/surf-build/surf) | 390 | `mocha --compilers ts:ts-node/register ./test/*.ts` | 
| [Asana/typed-react](https://github.com/Asana/typed-react) | 384 | `istanbul cover _mocha -- --reporter ${MOCHA_REPORTER-nyan} --slow 10 --ui tdd --recursive build/**/*_test.js` | 
| [R-js/libRmath.js](https://github.com/R-js/libRmath.js) | 372 | `cross-env-shell NODE_ENV=test TS_NODE_DISABLE_WARNINGS=true nyc mocha` | 
| [itsFrank/vue-typescript](https://github.com/itsFrank/vue-typescript) | 359 | `mocha` | 
| [ngParty/ng-metadata](https://github.com/ngParty/ng-metadata) | 346 | `mocha ./test/index.ts --require ts-node/register --colors --watch-extensions ts` | 
| [Polymer/prpl-server](https://github.com/Polymer/prpl-server) | 346 | `npm run build && mocha` | 
| [apollographql/persistgraphql](https://github.com/apollographql/persistgraphql) | 331 | `mocha --reporter spec --full-trace lib/test/tests.js` | 
| [arangodb/arangojs](https://github.com/arangodb/arangojs) | 331 | `mocha --growl --reporter spec --require source-map-support/register --timeout 10000 lib/async/test` | 
| [cartant/rxjs-spy](https://github.com/cartant/rxjs-spy) | 313 | `yarn run lint && yarn run test:build && yarn run test:karma && yarn run test:mocha` | 
| [whitecolor/yalc](https://github.com/whitecolor/yalc) | 306 | `tsc && mocha test && yarn lint` | 
| [biesbjerg/ngx-translate-extract](https://github.com/biesbjerg/ngx-translate-extract) | 306 | `mocha -r ts-node/register tests/**/*.spec.ts` | 
| [Microsoft/node-pty](https://github.com/Microsoft/node-pty) | 304 | `cross-env NODE_ENV=test mocha -R spec --exit lib/*.test.js` | 
| [zlq4863947/triangular-arbitrage](https://github.com/zlq4863947/triangular-arbitrage) | 301 | `cross-env NODE_ENV=test mocha dist/**/*.test.js --timeout 5000 --require intelli-espower-loader` | 
| [FinNLP/en-inflectors](https://github.com/FinNLP/en-inflectors) | 289 | `mocha` | 
| [Canner/apollo-link-firebase](https://github.com/Canner/apollo-link-firebase) | 287 | `TS_NODE_COMPILER_OPTIONS='{"module":"commonjs"}' mocha --timeout 10000 --compilers ts:ts-node/register --recursive --exit "test/**/*.spec.ts"` | 
| [mgechev/aspect.js](https://github.com/mgechev/aspect.js) | 284 | `tsc && mocha -R nyan ./dist/test/**/*.spec.js` | 
| [GoogleChrome/chrome-launcher](https://github.com/GoogleChrome/chrome-launcher) | 282 | `mocha --require ts-node/register --reporter=dot test/**/*-test.ts --timeout=10000` | 
| [alexcambose/motus](https://github.com/alexcambose/motus) | 282 | `cross-env mocha -r ts-node/register 'test/**/*.spec.ts'` | 
| [SweetIQ/schemats](https://github.com/SweetIQ/schemats) | 280 | `npm run lint && npm run build && npm run dependency-check && mocha` | 
| [cbowdon/TsMonad](https://github.com/cbowdon/TsMonad) | 273 | `mocha lib/test` | 
| [spiffcode/ghedit](https://github.com/spiffcode/ghedit) | 270 | `mocha` | 
| [cdonohue/polychrome](https://github.com/cdonohue/polychrome) | 270 | `mocha --compilers js:babel-register test/**/*.js` | 
| [dividab/tsconfig-paths](https://github.com/dividab/tsconfig-paths) | 270 | `mocha` | 
| [worr/node-imdb-api](https://github.com/worr/node-imdb-api) | 269 | `nyc --require ts-node/register --reporter=lcov node_modules/mocha/bin/mocha test/*.ts` | 
| [codemirror/codemirror.next](https://github.com/codemirror/codemirror.next) | 269 | `mocha -r ts-node/register/transpile-only doc/test/test-*.ts state/test/test-*.ts history/test/test-*.ts rangeset/test/test-rangeset.ts keymap/test/test-*.ts legacy-modes/test/test-*.ts view/test/test-heightmap.ts` | 
| [albburtsev/bem-cn](https://github.com/albburtsev/bem-cn) | 260 | `mocha src/**/*.spec.ts` | 
| [frankwallis/plugin-typescript](https://github.com/frankwallis/plugin-typescript) | 250 | `mocha --require ./test/environment --timeout 10000 ./test/*.ts` | 
| [cyclejs/react-native](https://github.com/cyclejs/react-native) | 245 | `TS_NODE_PROJECT=test/tsconfig.json mocha test/*.ts --require @huston007/react-native-mock/mock.js --require ts-node/register --recursive` | 
| [FormidableLabs/inspectpack](https://github.com/FormidableLabs/inspectpack) | 244 | `mocha "test/**/*.spec.ts"` | 
| [SpoonX/wetland](https://github.com/SpoonX/wetland) | 237 | `mocha dist/test/helper dist/test/unit/{*.spec.js,**/*.spec.js} --timeout 15000` | 
| [liangzeng/cqrs](https://github.com/liangzeng/cqrs) | 234 | `tsc && mocha` | 
| [RisingStack/node-typescript-starter](https://github.com/RisingStack/node-typescript-starter) | 234 | `tsc && mocha dist/**/*.spec.js` | 
| [dubzzz/fast-check](https://github.com/dubzzz/fast-check) | 233 | `npm run build && nyc mocha "test/unit/**/*.spec.ts"` | 
| [ReactiveX/rxjs-tslint](https://github.com/ReactiveX/rxjs-tslint) | 230 | `rimraf dist && tsc && mocha -R nyan dist/test --recursive` | 
| [duniter/duniter](https://github.com/duniter/duniter) | 225 | `nyc --reporter html mocha` | 
| [veonim/veonim](https://github.com/veonim/veonim) | 222 | `mocha test/unit` | 
| [renke/import-sort](https://github.com/renke/import-sort) | 220 | `mocha --require ts-node/register --recursive "packages/*/test/**/*.ts"` | 
| [AmirTugi/tea-school](https://github.com/AmirTugi/tea-school) | 219 | `npx ts-mocha ./src/tests/**.ts` | 
| [ClickSimply/Nano-SQL](https://github.com/ClickSimply/Nano-SQL) | 215 | `mocha -r ts-node/register tests/index.ts` | 
| [styleguidist/react-docgen-typescript](https://github.com/styleguidist/react-docgen-typescript) | 212 | `tsc && mocha --timeout 10000 ./lib/**/__tests__/**.js` | 
| [Kononnable/typeorm-model-generator](https://github.com/Kononnable/typeorm-model-generator) | 212 | `istanbul cover ./node_modules/mocha/bin/_mocha dist/test/**/*.test.js  -- -R spec` | 
| [Microsoft/vscode-cordova](https://github.com/Microsoft/vscode-cordova) | 211 | `node ./node_modules/mocha/bin/mocha --recursive -u bdd ./out/test/debugger` | 
| [stardustjs/stardust-core](https://github.com/stardustjs/stardust-core) | 208 | `mocha test` | 
| [rubenspgcavalcante/webpack-chrome-extension-reloader](https://github.com/rubenspgcavalcante/webpack-chrome-extension-reloader) | 207 | `NODE_ENV=test webpack && mocha dist/tests.js` | 
| [dolanmiu/docx](https://github.com/dolanmiu/docx) | 206 | `mocha-webpack "src/**/*.ts"` | 
| [HerringtonDarkholme/av-ts](https://github.com/HerringtonDarkholme/av-ts) | 204 | `mocha dist/test.js` | 
| [zekelevu/typeframework](https://github.com/zekelevu/typeframework) | 200 | `mocha -R spec test/integration` | 
| [jedmao/eclint](https://github.com/jedmao/eclint) | 198 | `nyc npm run mocha -- --reporter lcov --reporter spec` | 
| [Polymer/polyserve](https://github.com/Polymer/polyserve) | 197 | `npm run build && mocha && tslint "src/**/*.ts"` | 
| [thiagobustamante/typescript-rest](https://github.com/thiagobustamante/typescript-rest) | 196 | `cross-env NODE_ENV=test mocha` | 
| [Zarel/Pokemon-Showdown-Client](https://github.com/Zarel/Pokemon-Showdown-Client) | 195 | `eslint --config=.eslintrc.js --cache --cache-file=eslint-cache/base js/ data/ && eslint --config=build-tools/.eslintrc.js --cache --cache-file=eslint-cache/build build-tools/update build-tools/build-indexes && tsc && node build && mocha` | 
| [R-js/blasjs](https://github.com/R-js/blasjs) | 193 | `cross-env-shell NODE_ENV=test TS_NODE_DISABLE_WARNINGS=true nyc mocha` | 
| [bmewburn/intelephense](https://github.com/bmewburn/intelephense) | 187 | `mocha -r ts-node/register test/*.ts` | 
| [cartant/rxjs-tslint-rules](https://github.com/cartant/rxjs-tslint-rules) | 186 | `yarn run lint && yarn run test:build && yarn run test:mocha && yarn run test:tslint-v5 && yarn run test:tslint-v6 && yarn run test:tslint-v6-compat` | 
| [JumpFm/jumpfm](https://github.com/JumpFm/jumpfm) | 185 | `mocha js` | 
| [codeaholicguy/wowcup](https://github.com/codeaholicguy/wowcup) | 184 | `nyc mocha --forbid-only "test/**/*.test.ts"` | 
| [fabiandev/ts-runtime](https://github.com/fabiandev/ts-runtime) | 181 | `NODE_ENV=test TS_NODE_CACHE=false ./node_modules/mocha/bin/_mocha` | 
| [funkia/hareactive](https://github.com/funkia/hareactive) | 181 | `nyc mocha --recursive test/**/*.ts` | 
| [brentlintner/synt](https://github.com/brentlintner/synt) | 172 | `globstar -- _mocha "test/spec/**/*.coffee"` | 
| [felixfbecker/iterare](https://github.com/felixfbecker/iterare) | 172 | `mocha -r source-map-support/register lib/**/*.test.js` | 
| [ohjames/rxjs-websockets](https://github.com/ohjames/rxjs-websockets) | 172 | `npm run build && npm run mocha` | 
| [square/babel-codemod](https://github.com/square/babel-codemod) | 171 | `mocha "test/**/*Test.js"` | 
| [pnp/office365-cli](https://github.com/pnp/office365-cli) | 171 | `nyc -r=lcov -r=text mocha "dist/**/*.spec.js"` | 
| [microsoftgraph/msgraph-sdk-javascript](https://github.com/microsoftgraph/msgraph-sdk-javascript) | 171 | `mocha lib/spec/core` | 
| [staltz/html-looks-like](https://github.com/staltz/html-looks-like) | 170 | `npm run lint && npm run mocha` | 
| [oclif/cli-ux](https://github.com/oclif/cli-ux) | 169 | `mocha --forbid-only "test/**/*.test.ts"` | 
| [Polymer/polymer-analyzer](https://github.com/Polymer/polymer-analyzer) | 167 | `npm run clean && npm run build && npm run lint && mocha` | 
| [drew-y/cliffy](https://github.com/drew-y/cliffy) | 165 | `tsc && cd dist && mocha` | 
| [Chinachu/Mirakurun](https://github.com/Chinachu/Mirakurun) | 158 | `mocha --exit test/*.spec.js` | 
| [Microsoft/vscode-node-debug](https://github.com/Microsoft/vscode-node-debug) | 155 | `gulp compile && mocha --timeout 10000 -u tdd ./out/tests/` | 
| [championswimmer/vuex-module-decorators](https://github.com/championswimmer/vuex-module-decorators) | 153 | `cd test && mocha -r ts-node/register *.ts` | 
| [chenhaozhi/Cpage.js](https://github.com/chenhaozhi/Cpage.js) | 153 | `mocha -r ./node_modules/ts-node/register test/**/*_spec.ts --reporter mochawesome` | 
| [Talento90/typescript-node](https://github.com/Talento90/typescript-node) | 151 | `npm run build && mocha --exit --recursive dist/test/unit` | 
| [emmanueltouzery/prelude-ts](https://github.com/emmanueltouzery/prelude-ts) | 151 | `rm tests/apidoc-*; tsc && node ./dist/tests/Comments.js && tsc && ./node_modules/mocha/bin/mocha --throw-deprecation --timeout 60000 ./dist/tests/*.js` | 
| [kubernetes-client/javascript](https://github.com/kubernetes-client/javascript) | 150 | `nyc mocha` | 
| [jgranstrom/zipson](https://github.com/jgranstrom/zipson) | 147 | `mocha --require ts-node/register --watch-extensions ts 'test/**/*.ts'` | 
| [hydux/hydux](https://github.com/hydux/hydux) | 146 | `npm run mocha -- "src/test/unit/*.test.ts"` | 
| [calidion/vig](https://github.com/calidion/vig) | 145 | `npm run build && nyc --reporter=text --reporter=html --reporter=lcov mocha --bail --compilers ts:ts-node/register --recursive 'test/**/*.test.ts'` | 
| [nestjs/cqrs](https://github.com/nestjs/cqrs) | 139 | `tsc && mocha` | 
| [Commit451/skyhook](https://github.com/Commit451/skyhook) | 137 | `mocha -r ts-node/register test/*.ts` | 
| [Azure/azure-functions-pack](https://github.com/Azure/azure-functions-pack) | 136 | `npm run build && mocha --compilers ts:ts-node/register --recursive test/**/*-spec.ts` | 
| [martysweet/cfn-lint](https://github.com/martysweet/cfn-lint) | 136 | `mocha lib/test` | 
| [implydata/plyql](https://github.com/implydata/plyql) | 134 | `mocha` | 
| [nozer/quill-delta-to-html](https://github.com/nozer/quill-delta-to-html) | 132 | `./node_modules/nyc/bin/nyc.js ./node_modules/mocha/bin/mocha --compilers ts:ts-node/register -b "./test/**/*.ts"  ` | 
| [nspragg/filehound](https://github.com/nspragg/filehound) | 132 | `mocha -r ts-node/register test/*.ts` | 
| [rangle/typed-immutable-record](https://github.com/rangle/typed-immutable-record) | 131 | `npm run typings  && npm run lint && nyc npm run mocha` | 
| [rhysd/neovim-component](https://github.com/rhysd/neovim-component) | 131 | `mocha test/unit/ --exit` | 
| [danvk/localturk](https://github.com/danvk/localturk) | 130 | `mocha --require ts-node/register test/**/*.ts` | 
| [Microsoft/vscode-vsce](https://github.com/Microsoft/vscode-vsce) | 130 | `gulp compile && mocha` | 
| [Urigo/angular-meteor-base](https://github.com/Urigo/angular-meteor-base) | 130 | `TEST_BROWSER_DRIVER=puppeteer meteor test --driver-package=ardatan:mocha --raw-logs` | 
| [ConquestArrow/dtsmake](https://github.com/ConquestArrow/dtsmake) | 129 | `mocha --compilers ts:ts-node/register test/*.ts` | 
| [tomastrajan/ngx-model](https://github.com/tomastrajan/ngx-model) | 129 | `npm run clean && tslint *.ts && npm run format:ci && mocha ./lib/model.test.ts --require ts-node/register` | 
| [DotJoshJohnson/vscode-xml](https://github.com/DotJoshJohnson/vscode-xml) | 128 | `npm run compile && mocha ./out/test/**/*.js` | 
| [TrustWallet/trust-ray](https://github.com/TrustWallet/trust-ray) | 128 | `cross-env NODE_ENV=test mocha --recursive --require ts-node/register 'test/**/*.test.ts' --exit` | 
| [Microsoft/vscode-ios-web-debug](https://github.com/Microsoft/vscode-ios-web-debug) | 128 | `node ./node_modules/mocha/bin/mocha --recursive -u tdd ./out/test/` | 
| [cartant/rxjs-marbles](https://github.com/cartant/rxjs-marbles) | 126 | `yarn run lint && yarn run test:build && cross-env FAILING=0 yarn run test:ava && cross-env FAILING=0 yarn run test:jasmine && cross-env FAILING=0 yarn run test:jasmine-angular && cross-env FAILING=0 yarn run test:jest && cross-env FAILING=0 yarn run test:mocha && cross-env FAILING=0 yarn run test:tape` | 
| [mjhea0/typescript-node-api](https://github.com/mjhea0/typescript-node-api) | 126 | `mocha --reporter spec --compilers ts:ts-node/register 'test/**/*.test.ts'` | 
| [googlearchive/polylint](https://github.com/googlearchive/polylint) | 125 | `bower install && node_modules/.bin/jshint test && node_modules/.bin/mocha test/test.js` | 
| [arusanov/avatar-generator](https://github.com/arusanov/avatar-generator) | 124 | `mocha -r ts-node/register src/**/*.spec.ts` | 
| [interledgerjs/ilp](https://github.com/interledgerjs/ilp) | 124 | `istanbul test -- _mocha` | 
| [Half-Shot/matrix-appservice-discord](https://github.com/Half-Shot/matrix-appservice-discord) | 123 | `npm run-script build && mocha --opts test/mocha.opts build/test/config.js build/test` | 
| [paulcbetts/spawn-rx](https://github.com/paulcbetts/spawn-rx) | 120 | `mocha --compilers ts:ts-node/register ./test/*` | 
| [Goyoo/node-k8s-client](https://github.com/Goyoo/node-k8s-client) | 119 | `mocha test` | 
| [Soluto/graphql-to-mongodb](https://github.com/Soluto/graphql-to-mongodb) | 119 | `ts-mocha tests/**/*.spec.ts` | 
| [Enterprise-JS/vscode-ts-node-debugging](https://github.com/Enterprise-JS/vscode-ts-node-debugging) | 119 | `npm run mocha --recursive ./src/**/__tests__/*` | 
| [geofirestore/geofirestore-js](https://github.com/geofirestore/geofirestore-js) | 119 | `nyc --reporter=html --reporter=text mocha` | 
| [gamestdio/colyseus.js](https://github.com/gamestdio/colyseus.js) | 119 | `mocha test/*.ts --require ts-node/register` | 
| [indutny/llhttp](https://github.com/indutny/llhttp) | 117 | `npm run mocha && npm run lint` | 
| [pocesar/node-stratum](https://github.com/pocesar/node-stratum) | 117 | `node ./node_modules/typescript/bin/tsc -p tests.json && mocha test` | 
| [Microsoft/monaco-languages](https://github.com/Microsoft/monaco-languages) | 117 | `mocha` | 
| [TreeGateway/tree-gateway](https://github.com/TreeGateway/tree-gateway) | 115 | `cross-env NODE_ENV=test mocha --exit` | 
| [VirgilSecurity/demo-twilio-chat-js](https://github.com/VirgilSecurity/demo-twilio-chat-js) | 113 | `mocha --timeout 5000 -r ts-node/register -r tsconfig-paths/register ./api/tests/*.test.ts` | 
| [moodysalem/react-tournament-bracket](https://github.com/moodysalem/react-tournament-bracket) | 112 | `mocha --require ts-node/register src/**/*.test.tsx` | 
| [nestjs/typeorm](https://github.com/nestjs/typeorm) | 111 | `rimraf ./build && tsc && mocha --file ./build/compiled/test/utils/test-setup.js --bail --recursive --timeout 30000  ./build/compiled/test` | 
| [VirgilSecurity/demo-twilio-chat-js](https://github.com/VirgilSecurity/demo-twilio-chat-js) | 113 | `mocha --timeout 5000 -r ts-node/register -r tsconfig-paths/register ./api/tests/*.test.ts` | 
| [moodysalem/react-tournament-bracket](https://github.com/moodysalem/react-tournament-bracket) | 112 | `mocha --require ts-node/register src/**/*.test.tsx` | 
| [nestjs/typeorm](https://github.com/nestjs/typeorm) | 111 | `rimraf ./build && tsc && mocha --file ./build/compiled/test/utils/test-setup.js --bail --recursive --timeout 30000  ./build/compiled/test` | 
| [atomist/sdm](https://github.com/atomist/sdm) | 111 | `mocha --require espower-typescript/guess "test/**/*.test.ts"` | 
| [bradymholt/cRonstrue](https://github.com/bradymholt/cRonstrue) | 110 | `npx mocha --reporter spec --compilers ts:ts-node/register` | 
| [mgechev/ngresizable](https://github.com/mgechev/ngresizable) | 109 | `mocha --require ts-node/register test/**/*.spec.ts --recursive` | 
| [Microsoft/TypeScript-TmLanguage](https://github.com/Microsoft/TypeScript-TmLanguage) | 107 | `mocha --full-trace tests/test.js  --reporter mocha-multi-reporters` | 
| [nomiclabs/buidler](https://github.com/nomiclabs/buidler) | 107 | `nyc mocha` | 
| [Urigo/meteor-rxjs](https://github.com/Urigo/meteor-rxjs) | 107 | `cd tests && meteor test --driver-package practicalmeteor:mocha` | 
| [IBM/Decentralized-Energy-Composer](https://github.com/IBM/Decentralized-Energy-Composer) | 106 | `mocha --recursive -t 4000` | 
| [tunnelvisionlabs/antlr4ts](https://github.com/tunnelvisionlabs/antlr4ts) | 106 | `mocha` | 
| [toolness/p5.js-widget](https://github.com/toolness/p5.js-widget) | 106 | `webpack && mocha-phantomjs test/index.html` | 
| [materiahq/materia-server](https://github.com/materiahq/materia-server) | 105 | `mocha -R spec dist/test/**/*.js` | 
| [matthew-matvei/freeman](https://github.com/matthew-matvei/freeman) | 104 | `xvfb-maybe electron-mocha --renderer __tests__` | 
| [functionalone/serverless-iam-roles-per-function](https://github.com/functionalone/serverless-iam-roles-per-function) | 104 | `nyc mocha --require ts-node/register --require source-map-support/register  ./src/test/**/*.test.ts` | 
| [JoshGlazebrook/socks](https://github.com/JoshGlazebrook/socks) | 104 | `NODE_ENV=test mocha --recursive --compilers ts:ts-node/register test/**/*.ts` | 
| [palantir/typesettable](https://github.com/palantir/typesettable) | 103 | `npm-run-all build test:mocha test:coverage lint` | 
| [grantila/fetch-h2](https://github.com/grantila/fetch-h2) | 103 | `node_modules/.bin/nyc npm run mocha` | 
| [structured-log/structured-log](https://github.com/structured-log/structured-log) | 102 | `mocha --compilers ts:ts-node/register -r src/polyfills/objectAssign.js test/**/*.spec.ts` | 
| [tycho01/typical](https://github.com/tycho01/typical) | 101 | `tsc | tee tsc.log && mocha lib/**/*.test.js 2>&1 | sed 's/[0-9]\+)/×/g' | tee errors.log` | 
| [rjmacarthy/express-typescript-starter](https://github.com/rjmacarthy/express-typescript-starter) | 100 | `mocha -r ts-node/register -w ./spec/**/*.spec.ts` | 
| [rohitpaulk/todoist-tribute](https://github.com/rohitpaulk/todoist-tribute) | 100 | `mocha --compilers ts:ts-node/register app/javascript/packs/tests/**/*.ts` | 
| [redhat-developer/yaml-language-server](https://github.com/redhat-developer/yaml-language-server) | 100 | `mocha --require ts-node/register --ui tdd ./test/*.test.ts` | 
| [thomasboyt/manygolf](https://github.com/thomasboyt/manygolf) | 100 | `webpack --config webpack/test.js && mocha --no-colors build/test/test.bundle.js` | 
| [ajafff/tsutils](https://github.com/ajafff/tsutils) | 99 | `mocha test/*Tests.js && tslint --test 'test/rules/**/tslint.json'` | 
| [nicksenger/react-arcgis](https://github.com/nicksenger/react-arcgis) | 99 | `nyc mocha` | 
| [philcockfield/storybook-host](https://github.com/philcockfield/storybook-host) | 99 | `./node_modules/mocha/bin/mocha --require ts-node/register --watch-extensions ts,tsx 'src/**/*.test.ts{,x}'` | 
| [metaes/metaes](https://github.com/metaes/metaes) | 98 | `tsc; mocha --recursive lib/ test/runner` | 
| [palantir/react-layered-chart](https://github.com/palantir/react-layered-chart) | 98 | `mocha 'test/**/*.ts' && tslint --project tsconfig.json` | 
| [dsherret/ts-nameof](https://github.com/dsherret/ts-nameof) | 98 | `yarn run --silent copy-test-files && nyc --reporter=lcov mocha --opts mocha.opts` | 
| [horiuchi/dtsgenerator](https://github.com/horiuchi/dtsgenerator) | 97 | `istanbul cover _mocha test/*.js test/**/*.js` | 
| [englercj/tsd-jsdoc](https://github.com/englercj/tsd-jsdoc) | 97 | `mocha --ui tdd -r ts-node/register test/specs/**.ts` | 
| [secret-tech/backend-ico-dashboard](https://github.com/secret-tech/backend-ico-dashboard) | 97 | `nyc mocha ./src/**/*.spec.ts --require test/prepare.ts` | 
| [jf3096/json-typescript-mapper](https://github.com/jf3096/json-typescript-mapper) | 97 | `mocha ./spec/*.js` | 
| [nucleojs/nucleo](https://github.com/nucleojs/nucleo) | 96 | `mocha -r ts-node/register` | 
| [wildbit/postmark.js](https://github.com/wildbit/postmark.js) | 96 | `node_modules/mocha/bin/mocha --timeout 10000 --retries 1 -r ts-node/register test/**/*test.ts` | 
| [motorcyclejs/motorcyclejs](https://github.com/motorcyclejs/motorcyclejs) | 96 | `northbrook tslint && northbrook mocha && northbrook karma` | 
| [inversify/inversify-express-example](https://github.com/inversify/inversify-express-example) | 96 | `nyc --clean --all --require ts-node/register --require reflect-metadata/Reflect --extension .ts -- mocha --exit --timeout 5000` | 
| [jvilk/MakeTypes](https://github.com/jvilk/MakeTypes) | 95 | `npm-run-all --serial prepublish generate:test build:test mocha` | 
| [Kode/KodeStudio](https://github.com/Kode/KodeStudio) | 95 | `mocha` | 
| [AkashaProject/ipfs-connector](https://github.com/AkashaProject/ipfs-connector) | 93 | `./node_modules/istanbul/lib/cli.js cover ./node_modules/.bin/_mocha  ./tests.js` | 
| [InCar/ali-mns](https://github.com/InCar/ali-mns) | 93 | `node node_modules/mocha/bin/mocha` | 
| [any-json/any-json](https://github.com/any-json/any-json) | 92 | `npm run build && cp -Rf test/fixtures out/test/ && mocha --ui tdd out/test/` | 
| [Microsoft/typescript-tslint-plugin](https://github.com/Microsoft/typescript-tslint-plugin) | 90 | `mocha ./out/**/*.test.js --slow 2000 --timeout 10000` | 
| [cartant/ts-action](https://github.com/cartant/ts-action) | 90 | `yarn run lint && yarn run test:build && mocha ./build/**/*-spec.js` | 
| [sudheerj/generator-jhipster-primeng](https://github.com/sudheerj/generator-jhipster-primeng) | 90 | `mocha test/* --timeout 500000` | 
| [ENikS/LINQ](https://github.com/ENikS/LINQ) | 89 | `mocha test/ --recursive` | 
| [aurelia/vscode-extension](https://github.com/aurelia/vscode-extension) | 88 | `mocha ./dist/test --recursive` | 
| [gcanti/prop-types-ts](https://github.com/gcanti/prop-types-ts) | 88 | `npm run lint && npm run prettier && npm run mocha` | 
| [KarlPurk/redux-decorators](https://github.com/KarlPurk/redux-decorators) | 88 | `webpack --env=test > /dev/null && mocha dist/redux-decorators.spec.js` | 
| [mysticatea/vue-eslint-parser](https://github.com/mysticatea/vue-eslint-parser) | 88 | `nyc npm run _mocha` | 
| [vladotesanovic/typescript-mongoose-express](https://github.com/vladotesanovic/typescript-mongoose-express) | 88 | `mocha` | 
| [ynab/ynab-sdk-js](https://github.com/ynab/ynab-sdk-js) | 87 | `TS_NODE_PROJECT=./test/tsconfig.json npx mocha --reporter spec --require ts-node/register 'test/**/*.ts'` | 
| [atlassian/nucleus](https://github.com/atlassian/nucleus) | 87 | `mocha --compilers ts:ts-node/register src/__spec__/rest.ts src/**/__spec__/*_spec.ts src/**/**/__spec__/*_spec.ts` | 
| [indutny/llparse](https://github.com/indutny/llparse) | 86 | `npm run mocha && npm run lint` | 
| [carlansley/swagger2-koa](https://github.com/carlansley/swagger2-koa) | 85 | `npm run build && _mocha $(find build -name '*.spec.js') && npm run lint` | 
| [shlomiassaf/ngc-webpack](https://github.com/shlomiassaf/ngc-webpack) | 83 | `npm run build-test && ./node_modules/.bin/mocha dist/test/*.spec.js --recursive` | 
| [kimamula/ts-transformer-keys](https://github.com/kimamula/ts-transformer-keys) | 82 | `tsc && node ./test/compileMain.js && mocha ./test/main.js` | 
| [flagello/Essence](https://github.com/flagello/Essence) | 82 | `mocha` | 
| [koltyakov/sp-rest-proxy](https://github.com/koltyakov/sp-rest-proxy) | 81 | `ts-node ./test/init && mocha --opts test/mocha.opts || ECHO.` | 
| [neon-bindings/neon-cli](https://github.com/neon-bindings/neon-cli) | 81 | `npm run transpile && mocha dist/neon-cli-test/acceptance` | 
| [rh389/dynamodb-geo.js](https://github.com/rh389/dynamodb-geo.js) | 79 | `mocha --require ts-node/register test/**/*.ts` | 
| [wavesplatform/waves-api](https://github.com/wavesplatform/waves-api) | 78 | `npm run build && ./node_modules/.bin/tsc -p ./test/tsconfig.json && ./node_modules/.bin/mocha $(find ./tmp-node/test -name '*.spec.js')` | 
| [redhat-developer/vscode-yaml](https://github.com/redhat-developer/vscode-yaml) | 78 | `mocha --ui tdd out/test/extension.test.js` | 
| [CityOfZion/neo-js](https://github.com/CityOfZion/neo-js) | 77 | `mocha --reporter spec` | 
| [wbhob/nest-middlewares](https://github.com/wbhob/nest-middlewares) | 77 | `nyc --require ts-node/register mocha packages/**/*.spec.ts --reporter spec` | 
| [teambition/ReactiveDB](https://github.com/teambition/ReactiveDB) | 76 | `npm run lint && NODE_ENV=test tman --mocha spec-js/test/run.js` | 
| [olosegres/jsona](https://github.com/olosegres/jsona) | 76 | `npm run test-compile && env NODE_ENV=test ts-mocha ./**/*.test.ts` | 
| [argoproj/argo-ci](https://github.com/argoproj/argo-ci) | 76 | `TS_NODE_PROJECT=./src/tests/tsconfig.json mocha --require ts-node/register ./src/tests/**/*spec.ts` | 
| [vrimar/construct-ui](https://github.com/vrimar/construct-ui) | 75 | `cross-env TS_NODE_PROJECT=test/tsconfig.json mocha` | 
| [yakovlevga/brickyeditor](https://github.com/yakovlevga/brickyeditor) | 75 | `mocha --compilers js:babel-core/register --recursive` | 
| [funkia/jabz](https://github.com/funkia/jabz) | 74 | `nyc mocha --recursive test/**/*.ts` | 
| [gcanti/elm-ts](https://github.com/gcanti/elm-ts) | 74 | `npm run lint && npm run mocha` | 
| [suksant/sequelize-typescript-examples](https://github.com/suksant/sequelize-typescript-examples) | 74 | `gulp compile && mocha 'build/*/test/**/*.js'` | 
| [codius/codiusd](https://github.com/codius/codiusd) | 74 | `npm run lint && nyc mocha` | 
| [ui-jar/ui-jar](https://github.com/ui-jar/ui-jar) | 73 | `tsc && mocha "dist/test/**/*.js" ` | 
| [googleapis/nodejs-bigquery](https://github.com/googleapis/nodejs-bigquery) | 72 | `mocha build/test` | 
| [felixfbecker/sequelize-decorators](https://github.com/felixfbecker/sequelize-decorators) | 71 | `mocha dist/test` | 
| [Microsoft/NoSQLProvider](https://github.com/Microsoft/NoSQLProvider) | 71 | `mocha dist/tests/NoSqlProviderTests.js --timeout 5000` | 
| [Microsoft/vscode-chrome-debug-core](https://github.com/Microsoft/vscode-chrome-debug-core) | 71 | `mocha --exit --recursive -u tdd ./out/test/` | 
| [hawx1993/judge](https://github.com/hawx1993/judge) | 70 | `mocha --compilers ts:ts-node/register test/test.ts` | 
| [adrien2p/nestjs-graphql](https://github.com/adrien2p/nestjs-graphql) | 70 | `mocha -r ts-node/register src/**/tests/*.ts` | 
| [balassy/aws-lambda-typescript](https://github.com/balassy/aws-lambda-typescript) | 70 | `nyc mocha` | 
| [troch/path-parser](https://github.com/troch/path-parser) | 70 | `mocha -r ts-node/register 'test/main.js'` | 
| [AndrewPoyntz/time-ago-pipe](https://github.com/AndrewPoyntz/time-ago-pipe) | 70 | `mocha --reporter spec --require ts-node/register test/**/*.spec.ts` | 
| [Azure/azure-cosmos-js](https://github.com/Azure/azure-cosmos-js) | 69 | `mocha -r ./src/test/common/setup.ts ./lib/test/ --recursive --timeout 100000 -i -g .*ignore.js` | 
| [Cody2333/koa-swagger-decorator](https://github.com/Cody2333/koa-swagger-decorator) | 69 | `./node_modules/mocha/bin/mocha -r babel-core/register test/**/*.js --bail -t 2000000` | 
| [mrmlnc/vscode-scss](https://github.com/mrmlnc/vscode-scss) | 69 | `mocha out/**/*.spec.js` | 
| [indiejames/vscode-clojure-debug](https://github.com/indiejames/vscode-clojure-debug) | 69 | `node ./node_modules/mocha/bin/mocha -u tdd ./out/tests/` | 
| [levjj/esverify](https://github.com/levjj/esverify) | 69 | `TS_NODE_TRANSPILE_ONLY=true mocha -r ts-node/register tests/*.ts` | 
| [Microsoft/vscode-mock-debug](https://github.com/Microsoft/vscode-mock-debug) | 68 | `mocha -u tdd ./out/tests/` | 
| [Team-CHAD/DevDecks](https://github.com/Team-CHAD/DevDecks) | 68 | `cross-env NODE_ENV=test NODE_PATH=./app BABEL_DISABLE_CACHE=1 mocha --retries 2 --compilers ts:ts-node/register --recursive --require ignore-styles ./test/setup.ts test/**/*.spec.ts test/**/*.spec.tsx` | 
| [theGlenn/apollo-prophecy](https://github.com/theGlenn/apollo-prophecy) | 67 | `rm -rf coverage && nyc mocha --opts mocha.opts` | 
| [AlexGalays/immupdate](https://github.com/AlexGalays/immupdate) | 67 | `mocha test/test.js && node test/testCompilationErrors.js` | 
| [Polymer/polymer-editor-service](https://github.com/Polymer/polymer-editor-service) | 67 | `npm run clean && npm run build && mocha && npm run lint` | 
| [MariusAlch/json-to-ts](https://github.com/MariusAlch/json-to-ts) | 66 | `npm run build && mocha ./test/js-integration/index.js && mocha ./build/test` | 
| [bespoken/virtual-alexa](https://github.com/bespoken/virtual-alexa) | 66 | `nyc mocha lib/**/*Test.js` | 
| [Microsoft/vscode-css-languageservice](https://github.com/Microsoft/vscode-css-languageservice) | 66 | `npm run compile && mocha && npm run lint` | 
| [mattlewis92/generator-angular-library](https://github.com/mattlewis92/generator-angular-library) | 66 | `NODE_ENV=test mocha --timeout 300000` | 
| [hbenl/vscode-firefox-debug](https://github.com/hbenl/vscode-firefox-debug) | 66 | `TS_NODE_FILES=true mocha --opts src/test/mocha.opts "src/test/test*.ts"` | 
| [metadevpro/openapi3-ts](https://github.com/metadevpro/openapi3-ts) | 66 | `mocha --recursive --compilers ts:ts-node/register --require source-map-support/register "src/**/*.spec.ts"` | 
| [jinhduong/linq-fns](https://github.com/jinhduong/linq-fns) | 66 | `mocha -r ts-node/register test/*.ts` | 
| [puzzle-js/PuzzleJs](https://github.com/puzzle-js/PuzzleJs) | 64 | `nyc --check-coverage --lines=85 cross-env NODE_ENV=production mocha -r ts-node/register  --recursive 'test/**/*.spec.ts'` | 
| [tinganho/node-accept-language](https://github.com/tinganho/node-accept-language) | 64 | `node node_modules/mocha/bin/mocha Build/Tests/Test.js` | 
| [interledgerjs/ilp-connector](https://github.com/interledgerjs/ilp-connector) | 64 | `nyc mocha` | 
| [googleapis/node-gtoken](https://github.com/googleapis/node-gtoken) | 63 | `nyc mocha build/test` | 
| [cartant/rxjs-etc](https://github.com/cartant/rxjs-etc) | 62 | `yarn run lint && yarn run test:build && yarn run test:karma && yarn run test:mocha` | 
| [wikiwi/reassemble](https://github.com/wikiwi/reassemble) | 62 | `cross-env TS_NODE_COMPILER_OPTIONS='{"module":"commonjs"}' mocha --opts mocha.opts` | 
| [apollographql/graphql-document-collector](https://github.com/apollographql/graphql-document-collector) | 62 | `mocha 'lib/**/__tests__/*.js'` | 
| [HerringtonDarkholme/kilimanjaro](https://github.com/HerringtonDarkholme/kilimanjaro) | 62 | `mocha dist/test/*.js` | 
| [KoteiIto/node-athena](https://github.com/KoteiIto/node-athena) | 61 | `rm -rf coverage && istanbul cover _mocha -- -R spec build/test/*.js` | 
| [zenclabs/codetree](https://github.com/zenclabs/codetree) | 61 | `mocha -r ts-node/register src/**/*.spec.ts` | 
| [DavidDuwaer/Coloquent](https://github.com/DavidDuwaer/Coloquent) | 60 | `npm run build && mocha -r ts-node/register tests/**/*.test.ts` | 
| [wix/rawss](https://github.com/wix/rawss) | 60 | `mocha` | 
| [NativeScript/nativescript-vscode-extension](https://github.com/NativeScript/nativescript-vscode-extension) | 60 | `mocha --opts ./src/tests/config/mocha.opts` | 
| [timocov/dts-bundle-generator](https://github.com/timocov/dts-bundle-generator) | 60 | `mocha --timeout 10000 --slow 2500 tests/unittests/**/*.spec.js tests/functional-test-cases.js` | 
| [isc30/linq-collections](https://github.com/isc30/linq-collections) | 60 | `nyc mocha ./build/test/TestSuite.js --slow 0` | 
| [Microsoft/vscode-node-debug2](https://github.com/Microsoft/vscode-node-debug2) | 59 | `mocha --timeout 20000 -s 2000 -u tdd --colors --reporter node_modules/vscode-chrome-debug-core-testsupport/out/loggingReporter.js ./out/test/` | 
| [szdc/tiktok-api](https://github.com/szdc/tiktok-api) | 59 | `mocha` | 
| [pact-foundation/pact-node](https://github.com/pact-foundation/pact-node) | 59 | `cross-env LOGLEVEL=debug PACT_DO_NOT_TRACK=true mocha -r ts-node/register -R mocha-unfunk-reporter -t 15000 -s 5000 -b --check-leaks --exit "{src,test,bin,standalone}/**/*.spec.ts"` | 
| [pdupavillon/express-recaptcha](https://github.com/pdupavillon/express-recaptcha) | 58 | `mocha --compilers ts:ts-node/register test/**/*.spec.ts` | 
| [pdupavillon/express-recaptcha](https://github.com/pdupavillon/express-recaptcha) | 58 | `mocha --compilers ts:ts-node/register test/**/*.spec.ts` | 
| [alex-okrushko/backoff-rxjs](https://github.com/alex-okrushko/backoff-rxjs) | 58 | `mocha --opts spec/mocha.opts spec/**/*-spec.ts` | 
| [firebase/firebase-functions-test](https://github.com/firebase/firebase-functions-test) | 58 | `mocha .tmp/spec/index.spec.js` | 
| [matthiasferch/tsm](https://github.com/matthiasferch/tsm) | 57 | `mocha -r ts-node/register test/**/*.spec.ts` | 
| [19majkel94/class-transformer-validator](https://github.com/19majkel94/class-transformer-validator) | 57 | `mocha build/tests/index.js` | 
| [SqrTT/prophet](https://github.com/SqrTT/prophet) | 57 | `node ./node_modules/mocha/bin/mocha -u tdd ./out/tests/` | 
| [ktsn/vuetype](https://github.com/ktsn/vuetype) | 57 | `rimraf test/fixtures/*.d.ts && mocha --require espower-typescript/guess test/specs/**/*.ts` | 
| [deerawan/vscode-dash](https://github.com/deerawan/vscode-dash) | 57 | `./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- -R spec --ui tdd ./out/test/extension.test.js` | 
| [roblox-ts/roblox-ts](https://github.com/roblox-ts/roblox-ts) | 57 | `nyc --reporter=html mocha --timeout 0 --require ts-node/register --require source-map-support/register --recursive src/test.ts && lua tests/spec.lua` | 
| [mceachen/exiftool-vendored.js](https://github.com/mceachen/exiftool-vendored.js) | 56 | `nyc mocha --opts .mocha.opts` | 
| [jeswin/basho](https://github.com/jeswin/basho) | 55 | `./build.sh && mocha dist/test/test.js` | 
| [jupyter-attic/services](https://github.com/jupyter-attic/services) | 55 | `mocha --retries 3 test/build/**/*.spec.js --foo bar --terminalsAvailable True` | 
| [vechain/thorify](https://github.com/vechain/thorify) | 54 | `NODE_ENV=test mocha --require ts-node/register --timeout 20000 --recursive  --exclude './test/browser/*.ts' './**/*.test.ts'` | 
| [akoenig/gulp-svg2png](https://github.com/akoenig/gulp-svg2png) | 54 | `npm run build && npm run mocha` | 
| [nicojs/node-install-local](https://github.com/nicojs/node-install-local) | 54 | `mocha --timeout 30000 test/**/*.js` | 
| [hazelcast/hazelcast-nodejs-client](https://github.com/hazelcast/hazelcast-nodejs-client) | 54 | `mocha --recursive` | 
| [getsentry/sentry-electron](https://github.com/getsentry/sentry-electron) | 54 | `cross-env TS_NODE_PROJECT=tsconfig.json xvfb-maybe electron-mocha --require ts-node/register/transpile-only --timeout 3000 ./test/unit/**/*.ts` | 
| [yagajs/leaflet-ng2](https://github.com/yagajs/leaflet-ng2) | 53 | `npm run lint && npm run transpile && istanbul cover _mocha -- -- test/*.js` | 
| [WasabiFan/ev3dev-lang-js](https://github.com/WasabiFan/ev3dev-lang-js) | 53 | `grunt tsc && ./node_modules/mocha/bin/mocha` | 
| [PeculiarVentures/xadesjs](https://github.com/PeculiarVentures/xadesjs) | 53 | `mocha` | 
| [breakstring/xunfeisdk](https://github.com/breakstring/xunfeisdk) | 53 | `tsc && mocha -R nyan -t 15000 -r ts-node/register "./test/**/*.ts"` | 
| [bougarfaoui/back](https://github.com/bougarfaoui/back) | 53 | `mocha` | 
| [jsonapi-suite/jsorm](https://github.com/jsonapi-suite/jsorm) | 53 | `NODE_ENV=test mocha --opts test/mocha.opts` | 
| [DhyanaChina/koa2-typescript-guide](https://github.com/DhyanaChina/koa2-typescript-guide) | 52 | `mocha` | 
| [AkashaProject/geth-connector](https://github.com/AkashaProject/geth-connector) | 52 | `./node_modules/istanbul/lib/cli.js cover ./node_modules/.bin/_mocha  ./tests/index.js` | 
| [ryanatkn/ear-sharpener](https://github.com/ryanatkn/ear-sharpener) | 52 | `NODE_ENV=test mocha --require ts-node/register --require ignore-styles --require src/test src/**/*/test.{ts,tsx}` | 
| [duffman/tspath](https://github.com/duffman/tspath) | 52 | `mocha -r ts-node/register test/**.*/test.ts` | 
| [hcnode/koa-cola](https://github.com/hcnode/koa-cola) | 51 | `NODE_ENV=test nyc mocha` | 
| [infinum/mobx-jsonapi-store](https://github.com/infinum/mobx-jsonapi-store) | 51 | `NODE_ENV=test nyc mocha` | 
| [mrmlnc/emitty](https://github.com/mrmlnc/emitty) | 51 | `mocha out/test/{,**/}*.spec.js -s 0` | 
| [JBlaak/Express-Torch](https://github.com/JBlaak/Express-Torch) | 51 | `yarn lint && yarn mocha` | 
| [DhyanaChina/todo-live](https://github.com/DhyanaChina/todo-live) | 51 | `mocha` | 
| [sjohnsonaz/cascade](https://github.com/sjohnsonaz/cascade) | 50 | `tsc && node src/mocha/NodeRunner.js` | 
| [tusharmath/rwc](https://github.com/tusharmath/rwc) | 50 | `tsc && mocha -r src/TestSetup.js` | 
| [soywiz/atpl.js](https://github.com/soywiz/atpl.js) | 50 | `tsc && ./node_modules/.bin/mocha --ui exports --globals name ` | 
| [stevenxie/express-starter](https://github.com/stevenxie/express-starter) | 50 | `NODE_ENV=test; npm run build; mocha -Sb --exit tests/*.test.js` | 
| [rauschma/stringio](https://github.com/rauschma/stringio) | 49 | `mocha --ui qunit` | 
| [Microsoft/node-jsonc-parser](https://github.com/Microsoft/node-jsonc-parser) | 49 | `npm run compile && mocha` | 
| [evansolomon/nodejs-kinesis-client-library](https://github.com/evansolomon/nodejs-kinesis-client-library) | 49 | `npm run lint && mocha` | 
| [AlCalzone/node-tradfri-client](https://github.com/AlCalzone/node-tradfri-client) | 49 | `node_modules/.bin/mocha --watch` | 
| [SomeKittens/gustav](https://github.com/SomeKittens/gustav) | 49 | `mocha dist/test` | 
| [voodooattack/serialism](https://github.com/voodooattack/serialism) | 49 | `nyc mocha --expose-gc --ui mocha-typescript test/test_**.ts` | 
| [wearetheledger/fabric-node-chaincode-utils](https://github.com/wearetheledger/fabric-node-chaincode-utils) | 49 | `mocha -r ts-node/register test/**/*.spec.ts --reporter spec` | 
| [TonyRobotics/RoboWare-Studio](https://github.com/TonyRobotics/RoboWare-Studio) | 48 | `mocha` | 
| [mshanemc/shane-sfdx-plugins](https://github.com/mshanemc/shane-sfdx-plugins) | 48 | `mocha --forbid-only "test/**/*.test.ts"` | 
| [thiagobustamante/typescript-rest-swagger](https://github.com/thiagobustamante/typescript-rest-swagger) | 48 | `cross-env NODE_ENV=test mocha` | 
| [mike-lischke/antlr4-c3](https://github.com/mike-lischke/antlr4-c3) | 48 | `tsc --version && tsc && mocha out/test` | 
| [RobotlegsJS/RobotlegsJS](https://github.com/RobotlegsJS/RobotlegsJS) | 48 | `nyc mocha` | 
| [xmlking/koa-router-decorators](https://github.com/xmlking/koa-router-decorators) | 48 | `mocha .tmp/test/**/*.spec.js` | 
| [darkoverlordofdata/entitas-ts](https://github.com/darkoverlordofdata/entitas-ts) | 48 | `NODE_ENV=test mocha --compilers coffee:coffee-script --require test/test_helper.js --recursive` | 
| [mono/TsToCSharp](https://github.com/mono/TsToCSharp) | 48 | `npm run lint && mocha  ./dist/TsToCSharpTests.js` | 
| [realm/realm-graphql](https://github.com/realm/realm-graphql) | 47 | `mocha --opts config/mocha.opts` | 
| [Fundflow/apollo-redux-form](https://github.com/Fundflow/apollo-redux-form) | 47 | `mocha --reporter spec --full-trace lib/test/tests.js` | 
| [longlho/ts-transform-css-modules](https://github.com/longlho/ts-transform-css-modules) | 47 | `rm -rf test/fixture/*.js && mocha --require ts-node/register --recursive  test/**/*.test.ts` | 
| [tjson/tjson-js](https://github.com/tjson/tjson-js) | 47 | `mocha --compilers ts:ts-node/register --recursive` | 
| [rgraphql/soyuz](https://github.com/rgraphql/soyuz) | 47 | `npm run lint && npm run mocha` | 
| [ninoseki/mitaka](https://github.com/ninoseki/mitaka) | 47 | `nyc mocha -r ts-node/register "src/**/*.spec.ts"` | 
| [w11k/ngx-componentdestroyed](https://github.com/w11k/ngx-componentdestroyed) | 46 | `mocha --opts spec/mocha.opts src/**/*test.ts` | 
| [shlomiassaf/ng-router-loader](https://github.com/shlomiassaf/ng-router-loader) | 46 | `npm run compile_integration && npm run build && ./node_modules/.bin/mocha dist/test spec --recursive` | 
| [sketchglass/respass](https://github.com/sketchglass/respass) | 46 | `NODE_ENV=test mocha lib/test` | 
| [Microsoft/vscode-json-languageservice](https://github.com/Microsoft/vscode-json-languageservice) | 46 | `npm run compile && mocha && npm run lint` | 
| [ethereumjs/ethereumjs-blockstream](https://github.com/ethereumjs/ethereumjs-blockstream) | 46 | `mocha --require ts-node/register tests/**/*.ts` | 
| [marcinnajder/powerseq](https://github.com/marcinnajder/powerseq) | 46 | `mocha ./dist/cjs_es6/test -R spec --recursive --timeout 30000` | 
| [SPGoding/spu](https://github.com/SPGoding/spu) | 46 | `mocha --require espower-typescript/guess "./src/test/**/*.ts"` | 
| [teppeis/closure-ts](https://github.com/teppeis/closure-ts) | 46 | `npm-run-all --aggregate-output -p lint:ts build -p lint:js mocha` | 
| [KennethanCeyer/browser-detect](https://github.com/KennethanCeyer/browser-detect) | 46 | `nyc mocha` | 
| [balmbees/dynamo-types](https://github.com/balmbees/dynamo-types) | 46 | `AWS_REGION=us-east-1 AWS_ACCESS_KEY_ID=mock AWS_SECRET_ACCESS_KEY=mock DYNAMO_TYPES_ENDPOINT=http://127.0.0.1:8000 mocha -t 20000 dst/**/__test__/**/*.js` | 
| [mstssk/sw2dts](https://github.com/mstssk/sw2dts) | 45 | `mocha test/*.js` | 
| [Anonyfox/vuex-store-module-example](https://github.com/Anonyfox/vuex-store-module-example) | 45 | `rm -rf dist && tsc -p . && npm run lint && mocha dist/test` | 
| [waitingsong/node-win32-api](https://github.com/waitingsong/node-win32-api) | 45 | `mocha --opts test/mocha.opts` | 
| [sourcegraph/browser-extensions](https://github.com/sourcegraph/browser-extensions) | 45 | `mocha --require ts-node/register --watch --watch-extensions ts './src/**/*.test.ts?(x)'` | 
| [roginvs/space-rangers-quest](https://github.com/roginvs/space-rangers-quest) | 45 | `nyc --reporter=html --reporter=text mocha --bail built-node/test` | 
| [KennethanCeyer/formulize](https://github.com/KennethanCeyer/formulize) | 45 | `nyc mocha --opts test/mocha.opts` | 
| [mj1618/serverless-offline-sns](https://github.com/mj1618/serverless-offline-sns) | 44 | `nyc ts-mocha "test/**/*.ts" -p src/` | 
| [chanlito/simple-todos](https://github.com/chanlito/simple-todos) | 44 | `cross-env NODE_ENV=test nyc mocha --require test/index.ts --opts test/mocha.opts` | 
| [rsamec/react-binding](https://github.com/rsamec/react-binding) | 44 | `mocha -R spec ./test` | 
| [AEB-labs/cruddl](https://github.com/AEB-labs/cruddl) | 44 | `tsc --noEmit --skipLibCheck && mocha --opts ./spec/mocha.opts` | 
| [HdrHistogram/HdrHistogramJS](https://github.com/HdrHistogram/HdrHistogramJS) | 43 | `mocha --opts mocha.opts --watch` | 
| [brunolm/ts-react-redux-startup](https://github.com/brunolm/ts-react-redux-startup) | 43 | `npm run lint && mocha dist/spec` | 
| [crescware/walts](https://github.com/crescware/walts) | 43 | `npm run build && mocha --require intelli-espower-loader --reporter dot ./test/test.js` | 
| [sebawita/nativescript-angular-cli](https://github.com/sebawita/nativescript-angular-cli) | 43 | `istanbul cover node_modules/mocha/bin/_mocha -- --recursive --reporter spec-xunit-file --require test/test-bootstrap.js --timeout 1000 test/` | 
| [pubkey/solidity-cli](https://github.com/pubkey/solidity-cli) | 43 | `mocha --bail --exit ./dist/test/index.test.js  ./dist/test/integration.test.js` | 
| [rcjsuen/dockerfile-language-server-nodejs](https://github.com/rcjsuen/dockerfile-language-server-nodejs) | 43 | `mocha out/test` | 
| [sourcegraph/sourcegraph-extension-api](https://github.com/sourcegraph/sourcegraph-extension-api) | 43 | `TS_NODE_COMPILER_OPTIONS='{"module":"commonjs"}' mocha --require ts-node/register --require source-map-support/register --opts mocha.opts` | 
| [zswang/icity](https://github.com/zswang/icity) | 43 | `istanbul cover --hook-run-in-context node_modules/mocha/bin/_mocha -- -R spec` | 
| [fuse-box/angular2-example](https://github.com/fuse-box/angular2-example) | 43 | `cross-env TS_NODE_PROJECT=./src/tsconfig.mocha.json mocha --opts ./test/mocha.travis.opts` | 
| [adumont/tplink-cloud-api](https://github.com/adumont/tplink-cloud-api) | 42 | `mocha -r ts-node/register -p tsconfig.json lib/**/*.spec.ts` | 
| [JustinBeckwith/retry-axios](https://github.com/JustinBeckwith/retry-axios) | 42 | `nyc mocha build/test --timeout 5000 --require source-map-support/register` | 
| [gcanti/io-ts-codegen](https://github.com/gcanti/io-ts-codegen) | 42 | `npm run prettier && npm run lint && npm run mocha` | 
| [ikr/react-star-rating-input](https://github.com/ikr/react-star-rating-input) | 42 | `mocha -r ts-node/register -r tests/helpers/enzyme -b tests/*.spec.*` | 
| [RobinBuschmann/react.di](https://github.com/RobinBuschmann/react.di) | 42 | `mocha` | 
| [rhysd/fixjson](https://github.com/rhysd/fixjson) | 42 | `mocha test` | 
| [Lusito/forget-me-not](https://github.com/Lusito/forget-me-not) | 42 | `nyc mocha --require source-map-support/register --require ts-node/register test/**/*.ts` | 
| [Unibeautify/vscode](https://github.com/Unibeautify/vscode) | 41 | `mocha` | 
| [mrmlnc/vscode-csscomb](https://github.com/mrmlnc/vscode-csscomb) | 41 | `mocha out/{,**/}*.spec.js -s 0` | 
| [seansfkelley/synology-download-manager](https://github.com/seansfkelley/synology-download-manager) | 41 | `TS_NODE_PROJECT=test/tsconfig-test.json mocha --require ts-node/register 'test/**/*.{ts,tsx}'` | 
| [dupski/json-to-graphql-query](https://github.com/dupski/json-to-graphql-query) | 41 | `mocha -r ts-node/register --recursive "./src/**/__tests__/*"` | 
| [willryan/factory.ts](https://github.com/willryan/factory.ts) | 41 | `NODE_ENV=test mocha --require spec/setup.js --require ts-node/register` | 
| [ShyykoSerhiy/spotilocal](https://github.com/ShyykoSerhiy/spotilocal) | 41 | `./node_modules/typescript/bin/tsc && mocha "dist/test/**/*.js"` | 
| [bitjourney/ci-npm-update](https://github.com/bitjourney/ci-npm-update) | 41 | `TS_NODE_PROJECT=test/tsconfig.json mocha --opts test/support/default.opts test/**/*.test.ts` | 
| [cartant/rxjs-observe](https://github.com/cartant/rxjs-observe) | 41 | `yarn run lint && yarn run test:build && yarn run test:karma && yarn run test:mocha` | 
| [zaaack/inker](https://github.com/zaaack/inker) | 41 | `electron-mocha --renderer -r ./tools/register "src/test/**.test.ts"` | 
| [dalenguyen/firestore-backup-restore](https://github.com/dalenguyen/firestore-backup-restore) | 41 | `mocha --reporter spec` | 
| [ft-interactive/koa2-typescript-boilerplate](https://github.com/ft-interactive/koa2-typescript-boilerplate) | 41 | `tsc && mocha build/test` | 
| [ngParty/ts-helpers](https://github.com/ngParty/ts-helpers) | 41 | `mocha index.test.js` | 
| [ashleydavis/grademark](https://github.com/ashleydavis/grademark) | 41 | `nyc mocha --opts ./src/test/mocha.opts` | 
| [Quramy/graphql-decorator](https://github.com/Quramy/graphql-decorator) | 41 | `npm run build && npm run lint && mocha lib/**/*.spec.js` | 
| [ryu1kn/vscode-partial-diff](https://github.com/ryu1kn/vscode-partial-diff) | 40 | `mocha --opts cli-test-mocha.opts` | 
| [dirk/hummingbird](https://github.com/dirk/hummingbird) | 40 | `node_modules/.bin/mocha` | 
| [ethereum-ts/evm-ts](https://github.com/ethereum-ts/evm-ts) | 40 | `yarn lint && yarn test:mocha` | 
| [vilic/thenfail](https://github.com/vilic/thenfail) | 40 | `mocha && npm run aplus` | 
| [ryu1kn/vscode-partial-diff](https://github.com/ryu1kn/vscode-partial-diff) | 40 | `mocha --opts cli-test-mocha.opts` | 
| [dirk/hummingbird](https://github.com/dirk/hummingbird) | 40 | `node_modules/.bin/mocha` | 
| [ethereum-ts/evm-ts](https://github.com/ethereum-ts/evm-ts) | 40 | `yarn lint && yarn test:mocha` | 
| [vilic/thenfail](https://github.com/vilic/thenfail) | 40 | `mocha && npm run aplus` | 
| [just-animate/just-curves](https://github.com/just-animate/just-curves) | 40 | `node_modules/.bin/mocha --require ts-node/register --reporter spec ./tests/**/**.ts` | 
| [thundernet8/GithubProfile](https://github.com/thundernet8/GithubProfile) | 40 | `ts-mocha -p ./ test/**/*.spec.ts` | 
| [OmniSharp/omnisharp-node-client](https://github.com/OmniSharp/omnisharp-node-client) | 39 | `tsc && npm run lint && mocha` | 
| [stephenmartindale/kgs-leben](https://github.com/stephenmartindale/kgs-leben) | 39 | `gulp build:tests && mocha --timeout 1000 .build/tests.js` | 
| [googleapis/nodejs-spanner](https://github.com/googleapis/nodejs-spanner) | 39 | `nyc mocha build/test` | 
| [lukeautry/ts-app](https://github.com/lukeautry/ts-app) | 39 | `cross-env TS_NODE_PROJECT=./api/tsconfig.json mocha -t 15000 -r ts-node/register "./api/**/*.spec.ts"` | 
| [camesine/Typescript-restful-starter](https://github.com/camesine/Typescript-restful-starter) | 39 | `cross-env NODE_ENV=test mocha test/**/*.ts` | 
| [webix-hub/webix-jet](https://github.com/webix-hub/webix-jet) | 39 | `webpack && phantomjs node_modules/mocha-phantomjs-core/mocha-phantomjs-core.js tests/index.html spec` | 
| [aurelia/bundler](https://github.com/aurelia/bundler) | 39 | `mocha --reporter spec --compilers ts:ts-node/register test/**/*.spec.ts` | 
| [aiden/autobot](https://github.com/aiden/autobot) | 39 | `mocha --harmony --require source-map-support/register dist/test --recursive` | 
| [ivarvh/movielistr-backend-ts-ioc](https://github.com/ivarvh/movielistr-backend-ts-ioc) | 38 | `mocha -r ts-node/register test/**/*.spec.ts` | 
| [evebook/api](https://github.com/evebook/api) | 38 | `nyc --require ts-node/register mocha src/**/*.spec.ts --reporter spec` | 
| [ngerakines/express-typescript-sequelize](https://github.com/ngerakines/express-typescript-sequelize) | 38 | `istanbul cover node_modules/mocha/bin/_mocha -x *.spec.js -- --reporter spec` | 
| [AOEpeople/puppeteer-fetchbot](https://github.com/AOEpeople/puppeteer-fetchbot) | 38 | `npm run build && NODE_ENV=testing ./node_modules/.bin/mocha ./dist/lib/**/*.spec.js` | 
| [scopsy/node-typescript-starter](https://github.com/scopsy/node-typescript-starter) | 38 | `tsc && mocha dist/**/*.spec.js` | 
| [danrevah/typeserializer](https://github.com/danrevah/typeserializer) | 38 | `NODE_ENV=test mocha -r ts-node/register src/*.spec.ts src/**/*.spec.ts` | 
| [sinnerschrader/aem-react-js](https://github.com/sinnerschrader/aem-react-js) | 38 | `npm run build && npm run lint &&  nyc mocha --compilers ts:espower-typescript/guess test/*.js ` | 
| [usm4n/cycle-hn](https://github.com/usm4n/cycle-hn) | 37 | `cross-env NODE_ENV=test nyc mocha-webpack --timeout=100000 --colors --webpack-config configs/webpack.config.test.js test/**/*.test.*` | 
| [realm/realm-studio](https://github.com/realm/realm-studio) | 37 | `mocha-webpack --opts=configs/mocha-webpack.opts` | 
| [realm/realm-graphql-service](https://github.com/realm/realm-graphql-service) | 36 | `mocha --opts ./mocha.opts` | 
| [aleris/zxing-typescript](https://github.com/aleris/zxing-typescript) | 36 | `mocha --compilers js:babel-core/register "build-node/test/core/**/*.js" --timeout 30000 --colors` | 
| [JoshGlazebrook/smart-buffer](https://github.com/JoshGlazebrook/smart-buffer) | 36 | `NODE_ENV=test mocha --recursive --compilers ts:ts-node/register test/**/*.ts` | 
| [argoproj/argo-ui](https://github.com/argoproj/argo-ui) | 36 | `mocha --require ts-node/register ./src/app/**/*.spec.ts` | 
| [Polymer/polymer-linter](https://github.com/Polymer/polymer-linter) | 36 | `npm run build && mocha && npm run lint` | 
| [soraping/koa-ts](https://github.com/soraping/koa-ts) | 36 | `mocha --recursive` | 
| [utopian-io/api.utopian.io](https://github.com/utopian-io/api.utopian.io) | 36 | `cross-env NODE_ENV=test npx mocha --ui bdd --reporter spec --colors --recursive -r ts-node/register tests/index.ts` | 
| [snaptopixel/vuex-ts-decorators](https://github.com/snaptopixel/vuex-ts-decorators) | 35 | `mocha -r source-map-support/register -r ts-node/register -r es6-promise/auto test/**/*.ts` | 
| [fyndme/messenger-bot-tester](https://github.com/fyndme/messenger-bot-tester) | 35 | `mocha ./test-build` | 
| [nickpisacane/mips](https://github.com/nickpisacane/mips) | 35 | `__TS_PROJECT_PATH__=./test ts-mocha test/**/*.test.ts` | 
| [prismicio/prismic-javascript](https://github.com/prismicio/prismic-javascript) | 35 | `mocha` | 
| [zalando-incubator/authmosphere](https://github.com/zalando-incubator/authmosphere) | 35 | `npm run build && mocha lib/test lib/integration-test --recursive` | 
| [agea/CmisJS](https://github.com/agea/CmisJS) | 35 | `tsc && mocha dist/**/*.spec.js` | 
| [gcanti/hyper-ts](https://github.com/gcanti/hyper-ts) | 35 | `npm run prettier && npm run lint && npm run typings-checker && npm run mocha` | 
| [dhruvrajvanshi/ts-failable](https://github.com/dhruvrajvanshi/ts-failable) | 35 | `mocha --compilers ts:ts-node/register './test/**/*[tj]s'` | 
| [jaystack/odata-v4-server](https://github.com/jaystack/odata-v4-server) | 35 | `nyc mocha --reporter mochawesome --reporter-options reportDir=report,reportName=odata-v4-server,reportTitle="OData V4 Server" src/test/**/*.spec.ts` | 
| [paralin/grpc-bus](https://github.com/paralin/grpc-bus) | 35 | `npm run lint && npm run mocha` | 
| [indutny/bitcode](https://github.com/indutny/bitcode) | 35 | `npm run mocha && npm run lint` | 
| [microsoftgraph/msgraph-typescript-typings](https://github.com/microsoftgraph/msgraph-typescript-typings) | 35 | `tsc && mocha spec/` | 
| [infinum/mobx-collection-store](https://github.com/infinum/mobx-collection-store) | 35 | `NODE_ENV=test nyc mocha` | 
| [Draccoz/twc](https://github.com/Draccoz/twc) | 34 | `npm run lint && mocha --require ts-node/register --ui bdd tests/tests.spec.ts` | 
| [hg-pyun/iterize](https://github.com/hg-pyun/iterize) | 34 | `mocha --recursive ./test/*.ts --require ts-node/register` | 
| [davetemplin/web-request](https://github.com/davetemplin/web-request) | 34 | `mocha` | 
| [unbounce/iidy](https://github.com/unbounce/iidy) | 34 | `mocha lib/tests/_init.js lib/tests/**/*js` | 
| [forthright/vile](https://github.com/forthright/vile) | 34 | `globstar -- _mocha "test/spec/**/*.coffee"` | 
| [ste-vg/pop.svg](https://github.com/ste-vg/pop.svg) | 34 | `nyc mocha --require ./mocha.config.js -r ts-node/register 'src/**/*.spec.ts'  --exit --recursive --timeout 10000` | 
| [secret-tech/backend-token-wallets](https://github.com/secret-tech/backend-token-wallets) | 34 | `mocha -r ts-node/register -r test/prepare.ts src/**/*.spec.ts` | 
| [mixi-inc/css-semdiff](https://github.com/mixi-inc/css-semdiff) | 33 | `mocha --opts mocha.opts './dist/**/*.test.js'` | 
| [Jiasm/typescript-example](https://github.com/Jiasm/typescript-example) | 33 | `mocha -r ts-node/register test/**/*.spec.ts` | 
| [josephg/statecraft](https://github.com/josephg/statecraft) | 33 | `mocha -r ts-node/register test/*.ts` | 
| [functionalone/aws-least-privilege](https://github.com/functionalone/aws-least-privilege) | 33 | `nyc mocha --require ts-node/register --require source-map-support/register  ./src/test/**/*.test.ts` | 
| [userpixel/typescript](https://github.com/userpixel/typescript) | 33 | `mocha test` | 
| [tuzhanai/captcha](https://github.com/tuzhanai/captcha) | 33 | `mocha -b --require ts-node/register --require source-map-support/register --recursive --exit src/test.ts` | 
| [qtumproject/qtumjs](https://github.com/qtumproject/qtumjs) | 33 | `mocha  lib/*_test.js` | 
| [supergraphql/supergraph](https://github.com/supergraphql/supergraph) | 33 | `nyc mocha ./dist/**/*.spec.js` | 
| [mrmlnc/vscode-stylefmt](https://github.com/mrmlnc/vscode-stylefmt) | 32 | `mocha out/**/*.spec.js -s 0` | 
| [NikitchenkoSergey/scheme-designer](https://github.com/NikitchenkoSergey/scheme-designer) | 32 | `mocha` | 
| [davetemplin/async-parallel](https://github.com/davetemplin/async-parallel) | 32 | `mocha` | 
| [home-assistant/home-assistant-js-websocket](https://github.com/home-assistant/home-assistant-js-websocket) | 32 | `mocha test/*.spec.ts` | 
| [igorzg/typeix](https://github.com/igorzg/typeix) | 32 | `npm run compile && mocha build/tests/ --debug --full-trace` | 
| [Pravez/ReImproveJS](https://github.com/Pravez/ReImproveJS) | 32 | `mocha --reporter spec --compilers ts:ts-node/register 'test/*.spec.ts' --timeout 120000` | 
| [mulesoft-labs/yaml-ast-parser](https://github.com/mulesoft-labs/yaml-ast-parser) | 32 | `npm run build && mocha --ui tdd dist/test` | 
| [GoodgameStudios/RobotlegsJS](https://github.com/GoodgameStudios/RobotlegsJS) | 32 | `nyc mocha` | 
| [bpowers/sd.js](https://github.com/bpowers/sd.js) | 32 | `tsc -p .tsconfig.test.json && mocha` | 
| [Rich-Harris/port-authority](https://github.com/Rich-Harris/port-authority) | 32 | `mocha --opts mocha.opts` | 
| [Jason3S/rx-stream](https://github.com/Jason3S/rx-stream) | 32 | `mocha --recursive "dist/**/*.test.js"` | 
| [aleixmorgadas/nem-library-ts](https://github.com/aleixmorgadas/nem-library-ts) | 32 | `mocha --ui bdd --recursive ./dist/test ./dist/integration_test --timeout 60000` | 
| [vrudikov/typescript-rest-boilerplate](https://github.com/vrudikov/typescript-rest-boilerplate) | 32 | `cross-env NODE_ENV=test mocha` | 
| [glixlur/jsx-dom](https://github.com/glixlur/jsx-dom) | 31 | `nyc --reporter=html mocha test/test.tsx --require test/register` | 
| [tsframework/ts-framework](https://github.com/tsframework/ts-framework) | 31 | `mocha build-test --recursive` | 
| [creeperyang/id3-parser](https://github.com/creeperyang/id3-parser) | 31 | `TS_NODE_PROJECT='test/tsconfig.json' mocha --require ts-node/register 'test/*.spec.ts' --reporter dot` | 
| [ForbesLindesay/barrage](https://github.com/ForbesLindesay/barrage) | 31 | `mocha -R spec lib/test.js` | 
| [leizongmin/leizm-web](https://github.com/leizongmin/leizm-web) | 31 | `npm run format && mocha --require ts-node/register --exit "src/test/**/*.ts"` | 
| [tbluemel/rtf.js](https://github.com/tbluemel/rtf.js) | 31 | `mocha test/test.js` | 
| [siegebell/vsc-prettify-symbols-mode](https://github.com/siegebell/vsc-prettify-symbols-mode) | 31 | `tsc -p ./ && mocha -u tdd ./out/test` | 
| [Azure/oav](https://github.com/Azure/oav) | 30 | `npm run tsc && npm run tslint && nyc mocha ./test/**/*.ts -r ts-node/register -t 10000 --reporter mocha-junit-reporter --reporter spec` | 
| [typeorm/typescript-example](https://github.com/typeorm/typescript-example) | 30 | `mocha -r ts-node/register test/**/*.spec.ts` | 
| [acrazing/mobx-sync](https://github.com/acrazing/mobx-sync) | 30 | `mocha --require ts-node/register --slow 1000 ./src/**/*.spec.ts` | 
| [rhysd/electron-in-page-search](https://github.com/rhysd/electron-in-page-search) | 30 | `electron-mocha --timeout 10000 --renderer test/*.js` | 
| [fsahmad/typescript-uml](https://github.com/fsahmad/typescript-uml) | 30 | `npm run build && mocha --compilers ts:ts-node/register --recursive 'src/**/*-spec.ts'` | 
| [nilobarp/text2json](https://github.com/nilobarp/text2json) | 30 | `DEBUG=TP* mocha dist/test/spectrum-tests.js` | 
| [lazerwalker/storyboard](https://github.com/lazerwalker/storyboard) | 30 | `mocha-webpack tests` | 
| [RocketChat/Rocket.Chat.js.SDK](https://github.com/RocketChat/Rocket.Chat.js.SDK) | 30 | `nyc mocha './src/lib/**/*.spec.ts'` | 
| [ShieldBattery/node-interval-tree](https://github.com/ShieldBattery/node-interval-tree) | 30 | `mocha -R spec --compilers ts:ts-node/register test/*.ts` | 
| [haoliangyu/boundary.now](https://github.com/haoliangyu/boundary.now) | 30 | `mocha test/**/*.test.ts --require ts-node/register --require reflect-metadata` | 
| [bespoken/virtual-device-sdk](https://github.com/bespoken/virtual-device-sdk) | 30 | `nyc mocha lib/test/*Test.js` | 
| [huang6349/ts-dva](https://github.com/huang6349/ts-dva) | 30 | `atool-test-mocha ./src/**/*-test.js` | 
| [TomShacham/http4js](https://github.com/TomShacham/http4js) | 30 | `tsc; mocha --require ts-node/register 'src/{test,ssl}/**/*.ts'` | 
| [ProjectOpenSea/opensea-js](https://github.com/ProjectOpenSea/opensea-js) | 29 | `./node_modules/.bin/mocha test/*.ts --require ts-node/register --timeout 10000` | 