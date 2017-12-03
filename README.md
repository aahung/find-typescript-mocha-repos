# Find Repos in TypeScript Tested using Mocha

The list was updated at 00:38:14 12/03/17 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [Microsoft/vscode](https://github.com/Microsoft/vscode) | 39644 | `mocha` | 
| [ReactiveX/rxjs](https://github.com/ReactiveX/rxjs) | 9507 | `cross-env TS_NODE_FAST=true mocha --compilers ts:ts-node/register --opts spec/support/coverage.opts "spec/**/*-spec.ts"` | 
| [nexe/nexe](https://github.com/nexe/nexe) | 3895 | `mocha` | 
| [palantir/tslint](https://github.com/palantir/tslint) | 2630 | `npm-run-all test:pre -p test:mocha test:rules` | 
| [nestjs/nest](https://github.com/nestjs/nest) | 2618 | `nyc --require ts-node/register mocha src/**/*.spec.ts --reporter spec` | 
| [Microsoft/sqlopsstudio](https://github.com/Microsoft/sqlopsstudio) | 2474 | `mocha` | 
| [decaffeinate/decaffeinate](https://github.com/decaffeinate/decaffeinate) | 2196 | `mocha 'test/**/*.ts'` | 
| [yortus/asyncawait](https://github.com/yortus/asyncawait) | 1712 | `mocha` | 
| [michaelgrosner/tribeca](https://github.com/michaelgrosner/tribeca) | 1437 | `mocha` | 
| [mgechev/codelyzer](https://github.com/mgechev/codelyzer) | 1434 | `rimraf dist && tsc && cp -r test/fixtures dist/test && mocha dist/test --recursive` | 
| [staltz/xstream](https://github.com/staltz/xstream) | 1318 | `npm run lint && npm run mocha && npm run doctest` | 
| [vuejs/vue-class-component](https://github.com/vuejs/vue-class-component) | 1252 | `npm run build && webpack --config test/webpack.config.js && mocha test/test.build.js` | 
| [s-panferov/awesome-typescript-loader](https://github.com/s-panferov/awesome-typescript-loader) | 1225 | `rimraf .test && mocha --timeout 30000 dist/__test__` | 
| [Polymer/polymer-bundler](https://github.com/Polymer/polymer-bundler) | 1222 | `tsc && tslint -c tslint.json src/*.ts src/**/*.ts && mocha` | 
| [compodoc/compodoc](https://github.com/compodoc/compodoc) | 1042 | `cross-env TS_NODE_PROJECT=test/tsconfig.json TS_NODE_DISABLE_WARNINGS=1 nyc mocha --opts test/mocha.opts` | 
| [Microsoft/vscode-chrome-debug](https://github.com/Microsoft/vscode-chrome-debug) | 906 | `mocha --timeout 20000 -s 2000 -u tdd --colors "./out/test/*.test.js"` | 
| [WuTheFWasThat/vimflowy](https://github.com/WuTheFWasThat/vimflowy) | 813 | `mocha --opts test/mocha.opts` | 
| [cherow/cherow](https://github.com/cherow/cherow) | 793 | `mocha test/specs/**/*.ts -R spec --bail` | 
| [vscode-icons/vscode-icons](https://github.com/vscode-icons/vscode-icons) | 791 | `nyc -c -x '' mocha ./out/test --recursive` | 
| [gamestdio/colyseus](https://github.com/gamestdio/colyseus) | 720 | `mocha --require ts-node/register test/**Test.ts` | 
| [angular/dgeni](https://github.com/angular/dgeni) | 683 | `mocha --compilers ts:ts-node/register -R spec src/**/*.spec.ts` | 
| [davidkpiano/xstate](https://github.com/davidkpiano/xstate) | 650 | `npm run prettify && mocha --require ts-node/register test/**.ts test/**/*.ts` | 
| [laoqiren/mlhelper](https://github.com/laoqiren/mlhelper) | 581 | `mocha --recursive` | 
| [jaysoo/todomvc-redux-react-typescript](https://github.com/jaysoo/todomvc-redux-react-typescript) | 518 | `tsc && mocha --require test-setup --recursive ./dist/**/__spec__/**/*-spec.js` | 
| [rill-js/rill](https://github.com/rill-js/rill) | 513 | `nyc --extension=.ts --include=src/**/*.ts --reporter=lcov --reporter=text-summary npm run mocha` | 
| [simonbengtsson/jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) | 480 | `mocha --compilers ts:ts-node/register test/*.js || true` | 
| [SierraSoftworks/Iridium](https://github.com/SierraSoftworks/Iridium) | 469 | `mocha --opts test/mocha.opts dist/test` | 
| [emilioastarita/lyricfier](https://github.com/emilioastarita/lyricfier) | 451 | `mocha` | 
| [Microsoft/dts-gen](https://github.com/Microsoft/dts-gen) | 448 | `mocha bin/tests/test.js` | 
| [gcanti/fp-ts](https://github.com/gcanti/fp-ts) | 388 | `npm run lint && npm run prettier && npm run mocha` | 
| [Asana/typed-react](https://github.com/Asana/typed-react) | 387 | `istanbul cover _mocha -- --reporter ${MOCHA_REPORTER-nyan} --slow 10 --ui tdd --recursive build/**/*_test.js` | 
| [surf-build/surf](https://github.com/surf-build/surf) | 353 | `mocha --compilers ts:ts-node/register ./test/*.ts` | 
| [strongloop/loopback-next](https://github.com/strongloop/loopback-next) | 352 | `node packages/build/bin/run-nyc npm run mocha` | 
| [mgechev/ngrev](https://github.com/mgechev/ngrev) | 350 | `electron-mocha app/specs.js.autogenerated --renderer --require source-map-support/register` | 
| [Microsoft/BotFramework-WebChat](https://github.com/Microsoft/BotFramework-WebChat) | 343 | `concurrently  "node test/mock_dl/index.js" "mocha test" ` | 
| [williamngan/pts](https://github.com/williamngan/pts) | 341 | `mocha --opts mocha.opts` | 
| [itsFrank/vue-typescript](https://github.com/itsFrank/vue-typescript) | 336 | `mocha` | 
| [electron/electron-rebuild](https://github.com/electron/electron-rebuild) | 332 | `mocha --compilers ts:ts-node/register ./test/*.ts` | 
| [ngParty/ng-metadata](https://github.com/ngParty/ng-metadata) | 329 | `mocha ./test/index.ts --require ts-node/register --colors --watch-extensions ts` | 
| [coinbase/gdax-tt](https://github.com/coinbase/gdax-tt) | 326 | `yarn run lint && yarn run test:mocha` | 
| [vvakame/typescript-formatter](https://github.com/vvakame/typescript-formatter) | 320 | `npm run build && mocha --reporter spec --timeout 20000 --require intelli-espower-loader` | 
| [opentracing/opentracing-javascript](https://github.com/opentracing/opentracing-javascript) | 310 | `mocha lib/test/unittest.js --check-leaks --color` | 
| [andrerpena/react-mde](https://github.com/andrerpena/react-mde) | 302 | `mocha --timeout 15000 --compilers js:babel-register ./test/*Spec.js` | 
| [FinNLP/en-inflectors](https://github.com/FinNLP/en-inflectors) | 283 | `mocha` | 
| [gcanti/io-ts](https://github.com/gcanti/io-ts) | 268 | `npm run prettier && npm run lint && npm run typings-checker && npm run mocha` | 
| [steelsojka/lodash-decorators](https://github.com/steelsojka/lodash-decorators) | 252 | `mocha --opts mocha.opts` | 
| [RxJS-CN/RxJS-Docs-CN](https://github.com/RxJS-CN/RxJS-Docs-CN) | 251 | `npm-run-all clean_spec build_spec test_mocha clean_spec` | 
| [davidkpiano/flipping](https://github.com/davidkpiano/flipping) | 250 | `mocha -r ts-node/register test/**.test.ts` | 
| [felixfbecker/vscode-php-debug](https://github.com/felixfbecker/vscode-php-debug) | 249 | `mocha out/test --timeout 20000 --slow 1000 --retries 4` | 
| [frankwallis/plugin-typescript](https://github.com/frankwallis/plugin-typescript) | 238 | `mocha --require ./test/environment --timeout 10000 ./test/*.ts` | 
| [YousefED/typescript-json-schema](https://github.com/YousefED/typescript-json-schema) | 233 | `npm run build && mocha -t 5000 --require source-map-support/register test` | 
| [spiffcode/ghedit](https://github.com/spiffcode/ghedit) | 227 | `mocha` | 
| [Polymer/prpl-server-node](https://github.com/Polymer/prpl-server-node) | 225 | `npm run build && mocha` | 
| [line/line-bot-sdk-nodejs](https://github.com/line/line-bot-sdk-nodejs) | 224 | `API_BASE_URL=http://localhost:1234/ TEST_PORT=1234 TS_NODE_CACHE=0 mocha -r ts-node/register test/*.spec.ts` | 
| [zekelevu/typeframework](https://github.com/zekelevu/typeframework) | 203 | `mocha -R spec test/integration` | 
| [duniter/duniter](https://github.com/duniter/duniter) | 198 | `nyc --reporter html mocha` | 
| [lukeautry/tsoa](https://github.com/lukeautry/tsoa) | 198 | `cross-env NODE_ENV=test mocha **/*.spec.ts --compilers ts:ts-node/register` | 
| [SpoonX/wetland](https://github.com/SpoonX/wetland) | 195 | `mocha dist/test/helper dist/test/unit/**` | 
| [ethanresnick/json-api](https://github.com/ethanresnick/json-api) | 192 | `export NODE_ENV=testing; mocha --compilers ts:ts-node/register --recursive test/unit/ test/integration/` | 
| [apollographql/persistgraphql](https://github.com/apollographql/persistgraphql) | 192 | `mocha --reporter spec --full-trace lib/test/tests.js` | 
| [cbowdon/TsMonad](https://github.com/cbowdon/TsMonad) | 190 | `mocha lib/test` | 
| [mgechev/aspect.js](https://github.com/mgechev/aspect.js) | 184 | `tsc && mocha -R nyan ./dist/test/**/*.spec.js` | 
| [liangzeng/cqrs](https://github.com/liangzeng/cqrs) | 183 | `tsc && mocha --require source-map-support/register dist/test && node example/main.js ` | 
| [stardustjs/stardust-core](https://github.com/stardustjs/stardust-core) | 182 | `mocha test` | 
| [renke/import-sort](https://github.com/renke/import-sort) | 176 | `mocha --require ts-node/register --recursive "packages/*/test/**/*.ts"` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 174 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [Polymer/polyserve](https://github.com/Polymer/polyserve) | 171 | `npm run build && mocha && tslint "src/**/*.ts"` | 
| [brentlintner/synt](https://github.com/brentlintner/synt) | 169 | `globstar -- _mocha "test/spec/**/*.coffee"` | 
| [cartant/rxjs-spy](https://github.com/cartant/rxjs-spy) | 168 | `yarn run lint && yarn run test:build && yarn run test:karma && yarn run test:mocha` | 
| [SweetIQ/schemats](https://github.com/SweetIQ/schemats) | 167 | `npm run lint && npm run build && npm run dependency-check && mocha` | 
| [firebase/firebase-functions](https://github.com/firebase/firebase-functions) | 163 | `mocha .tmp/spec/index.spec.js` | 
| [Microsoft/vscode-cordova](https://github.com/Microsoft/vscode-cordova) | 163 | `node ./node_modules/mocha/bin/mocha --recursive -u bdd ./out/test/debugger` | 
| [staltz/html-looks-like](https://github.com/staltz/html-looks-like) | 163 | `npm run lint && npm run mocha` | 
| [sourcegraph/javascript-typescript-langserver](https://github.com/sourcegraph/javascript-typescript-langserver) | 162 | `mocha --require source-map-support/register --timeout 7000 --slow 2000 lib/test/**/*.js` | 
| [Polymer/polymer-analyzer](https://github.com/Polymer/polymer-analyzer) | 162 | `npm run clean && npm run build && npm run lint && mocha` | 
| [felixfbecker/iterare](https://github.com/felixfbecker/iterare) | 156 | `mocha -r source-map-support/register lib/**/*.test.js` | 
| [HerringtonDarkholme/av-ts](https://github.com/HerringtonDarkholme/av-ts) | 155 | `mocha dist/test.js` | 
| [jedmao/eclint](https://github.com/jedmao/eclint) | 154 | `nyc npm run mocha -- --reporter lcov --reporter spec` | 
| [biesbjerg/ngx-translate-extract](https://github.com/biesbjerg/ngx-translate-extract) | 151 | `mocha -r ts-node/register tests/**/*.spec.ts` | 
| [JumpFm/jumpfm](https://github.com/JumpFm/jumpfm) | 140 | `mocha js` | 
| [chenhaozhi/Cpage.js](https://github.com/chenhaozhi/Cpage.js) | 138 | `mocha -r ./node_modules/ts-node/register test/**/*_spec.ts --reporter mochawesome` | 
| [Tyriar/node-pty](https://github.com/Tyriar/node-pty) | 136 | `cross-env NODE_ENV=test mocha -R spec lib/*.test.js` | 
| [hayjs/hay](https://github.com/hayjs/hay) | 135 | `yarn run lint && TS_NODE_PROJECT=tsconfig.test.json mocha --compilers ts:ts-node/register` | 
| [PolymerLabs/polylint](https://github.com/PolymerLabs/polylint) | 133 | `bower install && node_modules/.bin/jshint test && node_modules/.bin/mocha test/test.js` | 
| [Romakita/ts-express-decorators](https://github.com/Romakita/ts-express-decorators) | 126 | `npm run clean && npm run tsc && npm run tslint && NODE_ENV=test nyc --reporter=html --reporter=text _mocha --recursive` | 
| [Urigo/angular-meteor-base](https://github.com/Urigo/angular-meteor-base) | 121 | `TEST_BROWSER_DRIVER=phantomjs meteor test --driver-package=ardatan:mocha` | 
| [Microsoft/vscode-node-debug](https://github.com/Microsoft/vscode-node-debug) | 116 | `mocha --timeout 10000 -u tdd ./out/tests/` | 
| [calidion/vig](https://github.com/calidion/vig) | 115 | `npm run build && nyc --reporter=text --reporter=html --reporter=lcov mocha --bail --compilers ts:ts-node/register --recursive 'test/**/*.test.ts'` | 
| [Microsoft/vscode-ios-web-debug](https://github.com/Microsoft/vscode-ios-web-debug) | 114 | `node ./node_modules/mocha/bin/mocha --recursive -u tdd ./out/test/` | 
| [rhysd/neovim-component](https://github.com/rhysd/neovim-component) | 113 | `mocha test/unit/ --exit` | 
| [rangle/typed-immutable-record](https://github.com/rangle/typed-immutable-record) | 111 | `npm run typings  && npm run lint && nyc npm run mocha` | 
| [stipsan/scroll-into-view-if-needed](https://github.com/stipsan/scroll-into-view-if-needed) | 109 | `cypress run --browser chrome --reporter junit --reporter-options 'mochaFile=junit/test-results.xml'` | 
| [paulcbetts/spawn-rx](https://github.com/paulcbetts/spawn-rx) | 108 | `mocha --compilers ts:ts-node/register ./test/*` | 
| [alexjlockwood/avdo](https://github.com/alexjlockwood/avdo) | 107 | `./node_modules/.bin/mocha --require ts-node/register ./test/**/*.spec.ts` | 
| [frptools/collectable](https://github.com/frptools/collectable) | 107 | `mocha --opts ./mocha.opts` | 
| [mjhea0/typescript-node-api](https://github.com/mjhea0/typescript-node-api) | 106 | `mocha --reporter spec --compilers ts:ts-node/register 'test/**/*.test.ts'` | 
| [webshell/materia-server](https://github.com/webshell/materia-server) | 104 | `mocha -R spec dist/test/**/*.js` | 
| [implydata/plyql](https://github.com/implydata/plyql) | 103 | `mocha` | 
| [staltz/easy-ssb-pub](https://github.com/staltz/easy-ssb-pub) | 102 | `npm run lint && npm run mocha` | 