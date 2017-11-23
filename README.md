# Find Repos in TypeScript Tested using Mocha

The list was updated at 00:39:24 11/23/17 PST

## Requirements

```sh
pip install requests
```

## Repo List

| Repo | Stars | Test Script |
| --- | --- | --- |
| [Microsoft/vscode](https://github.com/Microsoft/vscode) | 39007 | `mocha` | 
| [ReactiveX/rxjs](https://github.com/ReactiveX/rxjs) | 9346 | `cross-env TS_NODE_FAST=true mocha --compilers ts:ts-node/register --opts spec/support/coverage.opts "spec/**/*-spec.ts"` | 
| [nexe/nexe](https://github.com/nexe/nexe) | 3825 | `mocha` | 
| [palantir/tslint](https://github.com/palantir/tslint) | 2592 | `npm-run-all test:pre -p test:mocha test:rules` | 
| [nestjs/nest](https://github.com/nestjs/nest) | 2482 | `nyc --require ts-node/register mocha src/**/*.spec.ts --reporter spec` | 
| [decaffeinate/decaffeinate](https://github.com/decaffeinate/decaffeinate) | 2187 | `mocha 'test/**/*.ts'` | 
| [Microsoft/sqlopsstudio](https://github.com/Microsoft/sqlopsstudio) | 2176 | `mocha` | 
| [yortus/asyncawait](https://github.com/yortus/asyncawait) | 1697 | `mocha` | 
| [mgechev/codelyzer](https://github.com/mgechev/codelyzer) | 1419 | `rimraf dist && tsc && cp -r test/fixtures dist/test && mocha dist/test --recursive` | 
| [michaelgrosner/tribeca](https://github.com/michaelgrosner/tribeca) | 1382 | `mocha` | 
| [staltz/xstream](https://github.com/staltz/xstream) | 1313 | `npm run lint && npm run mocha && npm run doctest` | 
| [Polymer/polymer-bundler](https://github.com/Polymer/polymer-bundler) | 1221 | `tsc && tslint -c tslint.json src/*.ts src/**/*.ts && mocha` | 
| [vuejs/vue-class-component](https://github.com/vuejs/vue-class-component) | 1207 | `npm run build && webpack --config test/webpack.config.js && mocha test/test.build.js` | 
| [s-panferov/awesome-typescript-loader](https://github.com/s-panferov/awesome-typescript-loader) | 1204 | `rimraf .test && mocha --timeout 30000 dist/__test__` | 
| [compodoc/compodoc](https://github.com/compodoc/compodoc) | 1001 | `cross-env TS_NODE_PROJECT=test/tsconfig.json TS_NODE_DISABLE_WARNINGS=1 nyc mocha --opts test/mocha.opts` | 
| [Microsoft/vscode-chrome-debug](https://github.com/Microsoft/vscode-chrome-debug) | 892 | `mocha --timeout 20000 -s 2000 -u tdd --colors "./out/test/*.test.js"` | 
| [WuTheFWasThat/vimflowy](https://github.com/WuTheFWasThat/vimflowy) | 809 | `mocha --opts test/mocha.opts` | 
| [cherow/cherow](https://github.com/cherow/cherow) | 786 | `mocha test/specs/**/*.ts -R spec --bail` | 
| [vscode-icons/vscode-icons](https://github.com/vscode-icons/vscode-icons) | 763 | `nyc -c -x '' mocha ./out/test --recursive` | 
| [gamestdio/colyseus](https://github.com/gamestdio/colyseus) | 713 | `mocha --require ts-node/register test/**Test.ts` | 
| [angular/dgeni](https://github.com/angular/dgeni) | 682 | `mocha --compilers ts:ts-node/register -R spec src/**/*.spec.ts` | 
| [davidkpiano/xstate](https://github.com/davidkpiano/xstate) | 623 | `npm run prettify && mocha --require ts-node/register test/**.ts test/**/*.ts` | 
| [jaysoo/todomvc-redux-react-typescript](https://github.com/jaysoo/todomvc-redux-react-typescript) | 515 | `tsc && mocha --require test-setup --recursive ./dist/**/__spec__/**/*-spec.js` | 
| [laoqiren/mlhelper](https://github.com/laoqiren/mlhelper) | 511 | `mocha --recursive` | 
| [rill-js/rill](https://github.com/rill-js/rill) | 510 | `nyc --extension=.ts --include=src/**/*.ts --reporter=lcov --reporter=text-summary npm run mocha` | 
| [simonbengtsson/jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) | 469 | `mocha --compilers ts:ts-node/register test/*.js || true` | 
| [SierraSoftworks/Iridium](https://github.com/SierraSoftworks/Iridium) | 466 | `mocha --opts test/mocha.opts dist/test` | 
| [emilioastarita/lyricfier](https://github.com/emilioastarita/lyricfier) | 444 | `mocha` | 
| [Microsoft/dts-gen](https://github.com/Microsoft/dts-gen) | 434 | `mocha bin/tests/test.js` | 
| [Asana/typed-react](https://github.com/Asana/typed-react) | 388 | `istanbul cover _mocha -- --reporter ${MOCHA_REPORTER-nyan} --slow 10 --ui tdd --recursive build/**/*_test.js` | 
| [gcanti/fp-ts](https://github.com/gcanti/fp-ts) | 368 | `npm run lint && npm run prettier && npm run mocha` | 
| [surf-build/surf](https://github.com/surf-build/surf) | 353 | `mocha --compilers ts:ts-node/register ./test/*.ts` | 
| [strongloop/loopback-next](https://github.com/strongloop/loopback-next) | 342 | `node packages/build/bin/run-nyc npm run mocha` | 
| [mgechev/ngrev](https://github.com/mgechev/ngrev) | 339 | `electron-mocha app/specs.js.autogenerated --renderer --require source-map-support/register` | 
| [itsFrank/vue-typescript](https://github.com/itsFrank/vue-typescript) | 336 | `mocha` | 
| [Microsoft/BotFramework-WebChat](https://github.com/Microsoft/BotFramework-WebChat) | 334 | `concurrently  "node test/mock_dl/index.js" "mocha test" ` | 
| [ngParty/ng-metadata](https://github.com/ngParty/ng-metadata) | 329 | `mocha ./test/index.ts --require ts-node/register --colors --watch-extensions ts` | 
| [electron/electron-rebuild](https://github.com/electron/electron-rebuild) | 321 | `mocha --compilers ts:ts-node/register ./test/*.ts` | 
| [williamngan/pts](https://github.com/williamngan/pts) | 320 | `mocha --opts mocha.opts` | 
| [vvakame/typescript-formatter](https://github.com/vvakame/typescript-formatter) | 314 | `npm run build && mocha --reporter spec --timeout 20000 --require intelli-espower-loader` | 
| [opentracing/opentracing-javascript](https://github.com/opentracing/opentracing-javascript) | 305 | `mocha lib/test/unittest.js --check-leaks --color` | 
| [coinbase/gdax-tt](https://github.com/coinbase/gdax-tt) | 297 | `yarn run lint && yarn run test:mocha` | 
| [andrerpena/react-mde](https://github.com/andrerpena/react-mde) | 293 | `mocha --timeout 15000 --compilers js:babel-register ./test/*Spec.js` | 
| [FinNLP/en-inflectors](https://github.com/FinNLP/en-inflectors) | 282 | `mocha` | 
| [gcanti/io-ts](https://github.com/gcanti/io-ts) | 258 | `npm run prettier && npm run lint && npm run typings-checker && npm run mocha` | 
| [felixfbecker/vscode-php-debug](https://github.com/felixfbecker/vscode-php-debug) | 245 | `mocha out/test --timeout 20000 --slow 1000 --retries 4` | 
| [steelsojka/lodash-decorators](https://github.com/steelsojka/lodash-decorators) | 242 | `mocha --opts mocha.opts` | 
| [RxJS-CN/RxJS-Docs-CN](https://github.com/RxJS-CN/RxJS-Docs-CN) | 240 | `npm-run-all clean_spec build_spec test_mocha clean_spec` | 
| [frankwallis/plugin-typescript](https://github.com/frankwallis/plugin-typescript) | 238 | `mocha --require ./test/environment --timeout 10000 ./test/*.ts` | 
| [YousefED/typescript-json-schema](https://github.com/YousefED/typescript-json-schema) | 228 | `npm run build && mocha -t 5000 --require source-map-support/register test` | 
| [spiffcode/ghedit](https://github.com/spiffcode/ghedit) | 226 | `mocha` | 
| [Polymer/prpl-server-node](https://github.com/Polymer/prpl-server-node) | 223 | `npm run build && mocha` | 
| [line/line-bot-sdk-nodejs](https://github.com/line/line-bot-sdk-nodejs) | 216 | `API_BASE_URL=http://localhost:1234/ TEST_PORT=1234 TS_NODE_CACHE=0 mocha -r ts-node/register test/*.spec.ts` | 
| [zekelevu/typeframework](https://github.com/zekelevu/typeframework) | 203 | `mocha -R spec test/integration` | 
| [duniter/duniter](https://github.com/duniter/duniter) | 198 | `nyc --reporter html mocha` | 
| [SpoonX/wetland](https://github.com/SpoonX/wetland) | 194 | `mocha dist/test/helper dist/test/unit/**` | 
| [lukeautry/tsoa](https://github.com/lukeautry/tsoa) | 192 | `cross-env NODE_ENV=test mocha **/*.spec.ts --compilers ts:ts-node/register` | 
| [ethanresnick/json-api](https://github.com/ethanresnick/json-api) | 191 | `export NODE_ENV=testing; mocha --compilers ts:ts-node/register --recursive test/unit/ test/integration/` | 
| [cbowdon/TsMonad](https://github.com/cbowdon/TsMonad) | 187 | `mocha lib/test` | 
| [apollographql/persistgraphql](https://github.com/apollographql/persistgraphql) | 187 | `mocha --reporter spec --full-trace lib/test/tests.js` | 
| [liangzeng/cqrs](https://github.com/liangzeng/cqrs) | 183 | `tsc && mocha --require source-map-support/register dist/test && node example/main.js ` | 
| [stardustjs/stardust-core](https://github.com/stardustjs/stardust-core) | 182 | `mocha test` | 
| [mgechev/aspect.js](https://github.com/mgechev/aspect.js) | 181 | `tsc && mocha -R nyan ./dist/test/**/*.spec.js` | 
| [Polymer/polyserve](https://github.com/Polymer/polyserve) | 171 | `npm run build && mocha && tslint "src/**/*.ts"` | 
| [davidkpiano/flipping](https://github.com/davidkpiano/flipping) | 170 | `mocha -r ts-node/register test/**.test.ts` | 
| [brentlintner/synt](https://github.com/brentlintner/synt) | 169 | `globstar -- _mocha "test/spec/**/*.coffee"` | 
| [anandanand84/technicalindicators](https://github.com/anandanand84/technicalindicators) | 164 | `mocha --compilers js:babel-register --require babel-polyfill` | 
| [staltz/html-looks-like](https://github.com/staltz/html-looks-like) | 164 | `npm run lint && npm run mocha` | 
| [SweetIQ/schemats](https://github.com/SweetIQ/schemats) | 163 | `npm run lint && npm run build && npm run dependency-check && mocha` | 
| [Microsoft/vscode-cordova](https://github.com/Microsoft/vscode-cordova) | 161 | `node ./node_modules/mocha/bin/mocha --recursive -u bdd ./out/test/debugger` | 
| [firebase/firebase-functions](https://github.com/firebase/firebase-functions) | 160 | `mocha .tmp/spec/index.spec.js` | 
| [Polymer/polymer-analyzer](https://github.com/Polymer/polymer-analyzer) | 160 | `npm run clean && npm run build && npm run lint && mocha` | 
| [sourcegraph/javascript-typescript-langserver](https://github.com/sourcegraph/javascript-typescript-langserver) | 156 | `mocha --require source-map-support/register --timeout 7000 --slow 2000 lib/test/**/*.js` | 
| [felixfbecker/iterare](https://github.com/felixfbecker/iterare) | 156 | `mocha -r source-map-support/register lib/**/*.test.js` | 
| [HerringtonDarkholme/av-ts](https://github.com/HerringtonDarkholme/av-ts) | 156 | `mocha dist/test.js` | 
| [cartant/rxjs-spy](https://github.com/cartant/rxjs-spy) | 154 | `yarn run lint && yarn run test:build && yarn run test:karma && yarn run test:mocha` | 
| [jedmao/eclint](https://github.com/jedmao/eclint) | 154 | `nyc npm run mocha -- --reporter lcov --reporter spec` | 
| [biesbjerg/ngx-translate-extract](https://github.com/biesbjerg/ngx-translate-extract) | 146 | `mocha -r ts-node/register tests/**/*.spec.ts` | 
| [hayjs/hay](https://github.com/hayjs/hay) | 135 | `yarn run lint && TS_NODE_PROJECT=tsconfig.test.json mocha --compilers ts:ts-node/register` | 
| [JumpFm/jumpfm](https://github.com/JumpFm/jumpfm) | 134 | `mocha js` | 
| [PolymerLabs/polylint](https://github.com/PolymerLabs/polylint) | 133 | `bower install && node_modules/.bin/jshint test && node_modules/.bin/mocha test/test.js` | 
| [chenhaozhi/Cpage.js](https://github.com/chenhaozhi/Cpage.js) | 132 | `mocha -r ./node_modules/ts-node/register test/**/*_spec.ts --reporter mochawesome` | 
| [Tyriar/node-pty](https://github.com/Tyriar/node-pty) | 131 | `cross-env NODE_ENV=test mocha -R spec lib/*.test.js` | 
| [Romakita/ts-express-decorators](https://github.com/Romakita/ts-express-decorators) | 121 | `npm run clean && npm run tsc && npm run tslint && NODE_ENV=test nyc --reporter=html --reporter=text _mocha --recursive` | 
| [calidion/vig](https://github.com/calidion/vig) | 115 | `npm run build && nyc --reporter=text --reporter=html --reporter=lcov mocha --bail --compilers ts:ts-node/register --recursive 'test/**/*.test.ts'` | 
| [Microsoft/vscode-node-debug](https://github.com/Microsoft/vscode-node-debug) | 114 | `mocha --timeout 10000 -u tdd ./out/tests/` | 
| [Microsoft/vscode-ios-web-debug](https://github.com/Microsoft/vscode-ios-web-debug) | 114 | `node ./node_modules/mocha/bin/mocha --recursive -u tdd ./out/test/` | 
| [rhysd/neovim-component](https://github.com/rhysd/neovim-component) | 110 | `mocha test/unit/ --exit` | 
| [rangle/typed-immutable-record](https://github.com/rangle/typed-immutable-record) | 109 | `npm run typings  && npm run lint && nyc npm run mocha` | 
| [paulcbetts/spawn-rx](https://github.com/paulcbetts/spawn-rx) | 108 | `mocha --compilers ts:ts-node/register ./test/*` | 
| [mjhea0/typescript-node-api](https://github.com/mjhea0/typescript-node-api) | 107 | `mocha --reporter spec --compilers ts:ts-node/register 'test/**/*.test.ts'` | 
| [webshell/materia-server](https://github.com/webshell/materia-server) | 104 | `mocha -R spec dist/test/**/*.js` | 
| [stipsan/scroll-into-view-if-needed](https://github.com/stipsan/scroll-into-view-if-needed) | 104 | `cypress run --browser chrome --reporter junit --reporter-options 'mochaFile=junit/test-results.xml'` | 
| [implydata/plyql](https://github.com/implydata/plyql) | 101 | `mocha` | 
| [frptools/collectable](https://github.com/frptools/collectable) | 100 | `mocha --opts ./mocha.opts` | 
| [staltz/easy-ssb-pub](https://github.com/staltz/easy-ssb-pub) | 100 | `npm run lint && npm run mocha` | 