# ネコミミでもわかるフロンドエンド開発環境構築

## 2章

```
$ yarn add --dev @babel/preset-env
yarn add v1.12.3
info No lockfile found.
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
warning "@babel/preset-env > @babel/plugin-syntax-object-rest-spread@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-proposal-json-strings@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-syntax-async-generators@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-proposal-optional-catch-binding@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-proposal-unicode-property-regex@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-proposal-object-rest-spread@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-proposal-async-generator-functions@7.1.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-syntax-optional-catch-binding@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-arrow-functions@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-block-scoping@7.1.5" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-block-scoped-functions@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-async-to-generator@7.1.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-classes@7.1.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-destructuring@7.1.3" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-dotall-regex@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-computed-properties@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-duplicate-keys@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-for-of@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-exponentiation-operator@7.1.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-function-name@7.1.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-literals@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-modules-amd@7.1.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-modules-commonjs@7.1.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-modules-systemjs@7.1.3" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-modules-umd@7.1.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-new-target@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-object-super@7.1.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-spread@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-shorthand-properties@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-regenerator@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-parameters@7.1.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-sticky-regex@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-template-literals@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-typeof-symbol@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-transform-unicode-regex@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning "@babel/preset-env > @babel/plugin-proposal-json-strings > @babel/plugin-syntax-json-strings@7.0.0" has unmet peer dependency "@babel/core@^7.0.0-0".
warning " > @babel/preset-env@7.1.6" has unmet peer dependency "@babel/core@^7.0.0-0".
[4/4] 📃  Building fresh packages...

success Saved lockfile.
success Saved 73 new dependencies.
info Direct dependencies
└─ @babel/preset-env@7.1.6
info All dependencies
├─ @babel/generator@7.1.6
├─ @babel/helper-builder-binary-assignment-operator-visitor@7.1.0
├─ @babel/helper-call-delegate@7.1.0
├─ @babel/helper-define-map@7.1.0
├─ @babel/helper-explode-assignable-expression@7.1.0
├─ @babel/helper-member-expression-to-functions@7.0.0
├─ @babel/helper-wrap-function@7.1.0
├─ @babel/highlight@7.0.0
├─ @babel/parser@7.1.6
├─ @babel/plugin-proposal-async-generator-functions@7.1.0
├─ @babel/plugin-proposal-json-strings@7.0.0
├─ @babel/plugin-proposal-object-rest-spread@7.0.0
├─ @babel/plugin-proposal-optional-catch-binding@7.0.0
├─ @babel/plugin-proposal-unicode-property-regex@7.0.0
├─ @babel/plugin-syntax-json-strings@7.0.0
├─ @babel/plugin-transform-arrow-functions@7.0.0
├─ @babel/plugin-transform-async-to-generator@7.1.0
├─ @babel/plugin-transform-block-scoped-functions@7.0.0
├─ @babel/plugin-transform-block-scoping@7.1.5
├─ @babel/plugin-transform-classes@7.1.0
├─ @babel/plugin-transform-computed-properties@7.0.0
├─ @babel/plugin-transform-destructuring@7.1.3
├─ @babel/plugin-transform-dotall-regex@7.0.0
├─ @babel/plugin-transform-duplicate-keys@7.0.0
├─ @babel/plugin-transform-exponentiation-operator@7.1.0
├─ @babel/plugin-transform-for-of@7.0.0
├─ @babel/plugin-transform-function-name@7.1.0
├─ @babel/plugin-transform-literals@7.0.0
├─ @babel/plugin-transform-modules-amd@7.1.0
├─ @babel/plugin-transform-modules-commonjs@7.1.0
├─ @babel/plugin-transform-modules-systemjs@7.1.3
├─ @babel/plugin-transform-modules-umd@7.1.0
├─ @babel/plugin-transform-new-target@7.0.0
├─ @babel/plugin-transform-object-super@7.1.0
├─ @babel/plugin-transform-parameters@7.1.0
├─ @babel/plugin-transform-regenerator@7.0.0
├─ @babel/plugin-transform-shorthand-properties@7.0.0
├─ @babel/plugin-transform-spread@7.0.0
├─ @babel/plugin-transform-sticky-regex@7.0.0
├─ @babel/plugin-transform-template-literals@7.0.0
├─ @babel/plugin-transform-typeof-symbol@7.0.0
├─ @babel/plugin-transform-unicode-regex@7.0.0
├─ @babel/preset-env@7.1.6
├─ ansi-styles@3.2.1
├─ browserslist@4.3.4
├─ caniuse-lite@1.0.30000910
├─ chalk@2.4.1
├─ color-convert@1.9.3
├─ color-name@1.1.3
├─ debug@4.1.0
├─ electron-to-chromium@1.3.84
├─ escape-string-regexp@1.0.5
├─ has-flag@3.0.0
├─ invariant@2.2.4
├─ js-levenshtein@1.1.4
├─ js-tokens@4.0.0
├─ jsesc@0.5.0
├─ loose-envify@1.4.0
├─ ms@2.1.1
├─ node-releases@1.0.4
├─ private@0.1.8
├─ regenerate-unicode-properties@7.0.0
├─ regenerator-transform@0.13.3
├─ regjsgen@0.4.0
├─ regjsparser@0.3.0
├─ source-map@0.5.7
├─ supports-color@5.5.0
├─ to-fast-properties@2.0.0
├─ trim-right@1.0.1
├─ unicode-canonical-property-names-ecmascript@1.0.4
├─ unicode-match-property-ecmascript@1.0.4
├─ unicode-match-property-value-ecmascript@1.0.2
└─ unicode-property-aliases-ecmascript@1.0.4
✨  Done in 3.04s.
```

```
vi .babelrc
```

webpack 追加
```
yarn add --dev webpack webpack-cli @babel/core babel-loader
yarn add v1.12.3
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 📃  Building fresh packages...
success Saved lockfile.
success Saved 290 new dependencies.
info Direct dependencies
├─ @babel/core@7.1.6
├─ babel-loader@8.0.4
├─ webpack-cli@3.1.2
└─ webpack@4.26.0
info All dependencies
├─ @babel/core@7.1.6
├─ @babel/helpers@7.1.5
├─ @webassemblyjs/floating-point-hex-parser@1.7.11
├─ @webassemblyjs/helper-code-frame@1.7.11
├─ @webassemblyjs/helper-fsm@1.7.11
├─ @webassemblyjs/helper-wasm-section@1.7.11
├─ @webassemblyjs/wasm-edit@1.7.11
├─ @webassemblyjs/wasm-opt@1.7.11
├─ @xtuc/ieee754@1.2.0
├─ abbrev@1.1.1
├─ acorn-dynamic-import@3.0.0
├─ acorn@5.7.3
├─ ajv-errors@1.0.0
├─ ansi-regex@2.1.1
├─ anymatch@2.0.0
├─ aproba@1.2.0
├─ are-we-there-yet@1.1.5
├─ arr-flatten@1.1.0
├─ asn1.js@4.10.1
├─ assert@1.4.1
├─ assign-symbols@1.0.0
├─ async-each@1.0.1
├─ atob@2.1.2
├─ babel-loader@8.0.4
├─ balanced-match@1.0.0
├─ base@0.11.2
├─ base64-js@1.3.0
├─ big.js@3.2.0
├─ binary-extensions@1.12.0
├─ bluebird@3.5.3
├─ brace-expansion@1.1.11
├─ braces@2.3.2
├─ browserify-aes@1.2.0
├─ browserify-cipher@1.0.1
├─ browserify-des@1.0.2
├─ browserify-sign@4.0.4
├─ browserify-zlib@0.2.0
├─ buffer-xor@1.0.3
├─ buffer@4.9.1
├─ builtin-status-codes@3.0.0
├─ cacache@11.3.1
├─ cache-base@1.0.1
├─ camelcase@5.0.0
├─ chokidar@2.0.4
├─ chownr@1.1.1
├─ chrome-trace-event@1.0.0
├─ class-utils@0.3.6
├─ cliui@4.1.0
├─ code-point-at@1.1.0
├─ collection-visit@1.0.0
├─ commander@2.17.1
├─ concat-map@0.0.1
├─ concat-stream@1.6.2
├─ console-browserify@1.1.0
├─ console-control-strings@1.1.0
├─ constants-browserify@1.0.0
├─ convert-source-map@1.6.0
├─ copy-concurrently@1.0.5
├─ copy-descriptor@0.1.1
├─ core-util-is@1.0.2
├─ create-ecdh@4.0.3
├─ create-hmac@1.1.7
├─ cross-spawn@6.0.5
├─ crypto-browserify@3.12.0
├─ cyclist@0.2.2
├─ date-now@0.1.4
├─ debug@2.6.9
├─ decode-uri-component@0.2.0
├─ deep-extend@0.6.0
├─ delegates@1.0.0
├─ des.js@1.0.0
├─ detect-libc@1.0.3
├─ diffie-hellman@5.0.3
├─ domain-browser@1.2.0
├─ duplexify@3.6.1
├─ emojis-list@2.1.0
├─ errno@0.1.7
├─ es-abstract@1.12.0
├─ es-to-primitive@1.2.0
├─ eslint-scope@4.0.0
├─ esrecurse@4.2.1
├─ estraverse@4.2.0
├─ events@1.1.1
├─ execa@0.10.0
├─ expand-brackets@2.1.4
├─ extglob@2.0.4
├─ fast-deep-equal@2.0.1
├─ fast-json-stable-stringify@2.0.0
├─ figgy-pudding@3.5.1
├─ fill-range@4.0.0
├─ find-cache-dir@1.0.0
├─ flush-write-stream@1.0.3
├─ for-in@1.0.2
├─ from2@2.3.0
├─ fs-minipass@1.2.5
├─ fs.realpath@1.0.0
├─ fsevents@1.2.4
├─ gauge@2.7.4
├─ get-caller-file@1.0.3
├─ get-stream@3.0.0
├─ get-value@2.0.6
├─ glob-parent@3.1.0
├─ glob@7.1.3
├─ global-modules-path@2.3.0
├─ has-symbols@1.0.0
├─ has-unicode@2.0.1
├─ has-value@1.0.0
├─ has-values@1.0.0
├─ hash.js@1.1.5
├─ hmac-drbg@1.0.1
├─ https-browserify@1.0.0
├─ iconv-lite@0.4.24
├─ ieee754@1.1.12
├─ ignore-walk@3.0.1
├─ import-local@2.0.0
├─ indexof@0.0.1
├─ inflight@1.0.6
├─ ini@1.3.5
├─ interpret@1.1.0
├─ invert-kv@2.0.0
├─ is-accessor-descriptor@1.0.0
├─ is-binary-path@1.0.1
├─ is-callable@1.1.4
├─ is-data-descriptor@1.0.0
├─ is-date-object@1.0.1
├─ is-descriptor@1.0.2
├─ is-extglob@2.1.1
├─ is-fullwidth-code-point@2.0.0
├─ is-glob@4.0.0
├─ is-plain-object@2.0.4
├─ is-regex@1.0.4
├─ is-stream@1.1.0
├─ is-symbol@1.0.2
├─ is-windows@1.0.2
├─ isarray@1.0.0
├─ isexe@2.0.0
├─ json-parse-better-errors@1.0.2
├─ json-schema-traverse@0.4.1
├─ json5@2.1.0
├─ kind-of@3.2.2
├─ lcid@2.0.0
├─ loader-runner@2.3.1
├─ loader-utils@1.1.0
├─ locate-path@3.0.0
├─ lodash.debounce@4.0.8
├─ lru-cache@4.1.4
├─ map-age-cleaner@0.1.3
├─ map-visit@1.0.0
├─ mem@4.0.0
├─ memory-fs@0.4.1
├─ micromatch@3.1.10
├─ miller-rabin@4.0.1
├─ mimic-fn@1.2.0
├─ minimalistic-crypto-utils@1.0.1
├─ minimatch@3.0.4
├─ minimist@1.2.0
├─ minizlib@1.1.1
├─ mississippi@3.0.0
├─ mixin-deep@1.3.1
├─ move-concurrently@1.0.1
├─ ms@2.0.0
├─ nan@2.11.1
├─ nanomatch@1.2.13
├─ needle@2.2.4
├─ nice-try@1.0.5
├─ node-libs-browser@2.1.0
├─ node-pre-gyp@0.10.3
├─ nopt@4.0.1
├─ npm-bundled@1.0.5
├─ npm-packlist@1.1.12
├─ npm-run-path@2.0.2
├─ npmlog@4.1.2
├─ number-is-nan@1.0.1
├─ object-assign@4.1.1
├─ object-copy@0.1.0
├─ object-keys@1.0.12
├─ object.getownpropertydescriptors@2.0.3
├─ os-browserify@0.3.0
├─ os-homedir@1.0.2
├─ os-locale@3.0.1
├─ os-tmpdir@1.0.2
├─ osenv@0.1.5
├─ p-defer@1.0.0
├─ p-finally@1.0.0
├─ p-is-promise@1.1.0
├─ p-limit@2.0.0
├─ p-locate@3.0.0
├─ p-try@2.0.0
├─ pako@1.0.6
├─ parallel-transform@1.1.0
├─ pascalcase@0.1.1
├─ path-browserify@0.0.0
├─ path-dirname@1.0.2
├─ path-key@2.0.1
├─ path-parse@1.0.6
├─ pify@3.0.0
├─ posix-character-classes@0.1.1
├─ process-nextick-args@2.0.0
├─ process@0.11.10
├─ promise-inflight@1.0.1
├─ prr@1.0.1
├─ pseudomap@1.0.2
├─ public-encrypt@4.0.3
├─ pump@3.0.0
├─ pumpify@1.5.1
├─ punycode@1.4.1
├─ querystring-es3@0.2.1
├─ querystring@0.2.0
├─ randomfill@1.0.4
├─ rc@1.2.8
├─ readable-stream@2.3.6
├─ readdirp@2.2.1
├─ remove-trailing-separator@1.1.0
├─ repeat-element@1.1.3
├─ require-directory@2.1.1
├─ require-main-filename@1.0.1
├─ resolve-cwd@2.0.0
├─ resolve-from@3.0.0
├─ resolve-url@0.2.1
├─ resolve@1.8.1
├─ ret@0.1.15
├─ rimraf@2.6.2
├─ run-queue@1.0.3
├─ safer-buffer@2.1.2
├─ sax@1.2.4
├─ schema-utils@0.4.7
├─ serialize-javascript@1.5.0
├─ set-blocking@2.0.0
├─ set-value@2.0.0
├─ setimmediate@1.0.5
├─ shebang-command@1.2.0
├─ shebang-regex@1.0.0
├─ signal-exit@3.0.2
├─ snapdragon-node@2.1.1
├─ snapdragon-util@3.0.1
├─ source-list-map@2.0.1
├─ source-map-resolve@0.5.2
├─ source-map-support@0.5.9
├─ source-map-url@0.4.0
├─ source-map@0.6.1
├─ split-string@3.1.0
├─ ssri@6.0.1
├─ static-extend@0.1.2
├─ stream-browserify@2.0.1
├─ stream-each@1.2.3
├─ stream-http@2.8.3
├─ string_decoder@1.1.1
├─ string-width@2.1.1
├─ strip-ansi@3.0.1
├─ strip-eof@1.0.0
├─ strip-json-comments@2.0.1
├─ tapable@1.1.0
├─ tar@4.4.8
├─ terser-webpack-plugin@1.1.0
├─ terser@3.10.12
├─ through2@2.0.5
├─ timers-browserify@2.0.10
├─ to-arraybuffer@1.0.1
├─ to-regex-range@2.1.1
├─ tslib@1.9.3
├─ tty-browserify@0.0.0
├─ typedarray@0.0.6
├─ union-value@1.0.0
├─ unique-filename@1.1.1
├─ unique-slug@2.0.1
├─ unset-value@1.0.0
├─ upath@1.1.0
├─ uri-js@4.2.2
├─ urix@0.1.0
├─ url@0.11.0
├─ use@3.1.1
├─ util-deprecate@1.0.2
├─ util.promisify@1.0.0
├─ util@0.10.4
├─ v8-compile-cache@2.0.2
├─ vm-browserify@0.0.4
├─ watchpack@1.6.0
├─ webpack-cli@3.1.2
├─ webpack-sources@1.3.0
├─ webpack@4.26.0
├─ which-module@2.0.0
├─ which@1.3.1
├─ wide-align@1.1.3
├─ worker-farm@1.6.0
├─ wrap-ansi@2.1.0
├─ xtend@4.0.1
├─ y18n@4.0.0
├─ yallist@3.0.3
├─ yargs-parser@11.1.1
└─ yargs@12.0.5
✨  Done in 12.53s.
```

webpack.config.js 追加
```
vi webpack.config.js
const path = require('path');

const src = path.join(__dirname, 'src');
const dist = path.join(__dirname, 'dist');

module.exports = {
  // developmentモードで実行します
  mode: 'development',
  // ビルドを実行するファイルパス
  entry: path.resolve(src, 'js/index.js'),
  output: {
    // 生成されるファイル名
    filename: 'index.bundle.js',
    // 生成先のディレクトリー
    path: dist
  },
  resolve: {
    // import文のパス指定にnode_modulesを省略できるようにします
    modules: ['node_modules'],
    // .jsまたは.jsxの拡張子を省略できるようにします
    extensions: ['.js', '.jsx']
  },
  module: {
    rules: [
      {
        // ルールを適用するファイルの正規表現
        test: /\.(js|jsx)$/,
        // node_modules以下のファイルには適用しないようにします
        exclude: /node_modules/,
        // 使用するloader
        loader: 'babel-loader'
      }
    ]
  },
  // sourceMappingの設定
  devtool: 'cheap-module-eval-source-map',
};
```

package.json にコマンド追加
```
  "scripts": {
    "build:dev": "webpack --config webpack.config.js",
  },
```

src/js/inde.js 追加して
```
export class Hello {
  constructor(name) {
    this.say(name);
  }

  say(name) {
    console.log(`Hello ${name} World!`);
  }
}

export default new Hello('Nekomimi');
```

webpack 実行。
```
$ yarn build:dev
yarn run v1.12.3
$ webpack --config webpack.config.js
Hash: 79a59f1ccb7a529c26f1
Version: webpack 4.26.0
Time: 561ms
Built at: 2018-11-22 11:06:46
          Asset      Size  Chunks             Chunk Names
index.bundle.js  5.72 KiB    main  [emitted]  main
Entrypoint main = index.bundle.js
[./src/js/index.js] 1020 bytes {main} [built]
✨  Done in 1.15s.
```

```
$ node ./dist/index.bundle.js
Hello Nekomimi World!

```

ブラウザーでの動作チェック。

webpack-dev-server 追加。
```
$ yarn add --dev webpack-dev-server html-webpack-plugin
yarn add v1.12.3
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 📃  Building fresh packages...

success Saved lockfile.
success Saved 117 new dependencies.
info Direct dependencies
├─ html-webpack-plugin@3.2.0
└─ webpack-dev-server@3.1.10
info All dependencies
├─ accepts@1.3.5
├─ ansi-colors@3.2.1
├─ ansi-html@0.0.7
├─ array-flatten@1.1.1
├─ array-union@1.0.2
├─ array-uniq@1.0.3
├─ async@1.5.2
├─ batch@0.6.1
├─ body-parser@1.18.3
├─ bonjour@3.5.0
├─ buffer-indexof@1.1.1
├─ camel-case@3.0.0
├─ camelcase@4.1.0
├─ clean-css@4.2.1
├─ compressible@2.0.15
├─ compression@1.7.3
├─ connect-history-api-fallback@1.5.0
├─ content-disposition@0.5.2
├─ cookie-signature@1.0.6
├─ cookie@0.3.1
├─ css-select@1.2.0
├─ css-what@2.1.2
├─ deep-equal@1.0.1
├─ default-gateway@2.7.2
├─ del@3.0.0
├─ destroy@1.0.4
├─ detect-node@2.0.4
├─ dns-equal@1.0.0
├─ dns-packet@1.3.1
├─ dns-txt@2.0.2
├─ dom-converter@0.2.0
├─ dom-serializer@0.1.0
├─ domhandler@2.1.0
├─ domutils@1.1.6
├─ ee-first@1.1.1
├─ entities@1.1.2
├─ eventemitter3@3.1.0
├─ eventsource@1.0.7
├─ express@4.16.4
├─ faye-websocket@0.10.0
├─ finalhandler@1.1.1
├─ follow-redirects@1.5.10
├─ forwarded@0.1.2
├─ globby@6.1.0
├─ handle-thing@1.2.5
├─ he@1.2.0
├─ hpack.js@2.1.6
├─ html-entities@1.2.1
├─ html-minifier@3.5.21
├─ html-webpack-plugin@3.2.0
├─ htmlparser2@3.3.0
├─ http-deceiver@1.2.7
├─ http-errors@1.6.3
├─ http-parser-js@0.5.0
├─ http-proxy-middleware@0.18.0
├─ http-proxy@1.17.0
├─ internal-ip@3.0.1
├─ ip-regex@2.1.0
├─ ip@1.1.5
├─ ipaddr.js@1.8.1
├─ is-path-cwd@1.0.0
├─ is-path-in-cwd@1.0.1
├─ is-path-inside@1.0.1
├─ is-wsl@1.1.0
├─ json3@3.3.2
├─ killable@1.0.1
├─ loglevel@1.6.1
├─ lower-case@1.1.4
├─ media-typer@0.3.0
├─ merge-descriptors@1.0.1
├─ methods@1.1.2
├─ mime-db@1.37.0
├─ mime@2.3.1
├─ multicast-dns-service-types@1.1.0
├─ multicast-dns@6.2.3
├─ negotiator@0.6.1
├─ node-forge@0.7.5
├─ nth-check@1.0.2
├─ obuf@1.1.2
├─ on-headers@1.0.1
├─ opn@5.4.0
├─ original@1.0.2
├─ p-map@1.2.0
├─ param-case@2.1.1
├─ path-is-inside@1.0.2
├─ path-to-regexp@0.1.7
├─ pinkie-promise@2.0.1
├─ pinkie@2.0.4
├─ portfinder@1.0.19
├─ pretty-error@2.1.1
├─ proxy-addr@2.0.4
├─ querystringify@2.1.0
├─ raw-body@2.3.3
├─ relateurl@0.2.7
├─ renderkid@2.0.2
├─ select-hose@2.0.0
├─ selfsigned@1.10.4
├─ serve-index@1.9.1
├─ serve-static@1.13.2
├─ sockjs-client@1.3.0
├─ sockjs@0.3.19
├─ spdy-transport@2.1.1
├─ spdy@3.4.7
├─ thunky@1.0.3
├─ toposort@1.0.7
├─ uglify-js@3.4.9
├─ unpipe@1.0.0
├─ upper-case@1.1.3
├─ utils-merge@1.0.1
├─ uuid@3.3.2
├─ wbuf@1.7.3
├─ webpack-dev-middleware@3.4.0
├─ webpack-dev-server@3.1.10
├─ websocket-extensions@0.1.3
├─ xregexp@4.0.0
├─ yargs-parser@10.1.0
└─ yargs@12.0.2
✨  Done in 4.17s.
```

webpack.config.js に webpack-dev-server, html-webpack-plugin 追加。
```
vi webpack.config.js
const path = require('path');
// webpackモジュールを読み込む
const webpack = require('webpack');
// html-webpack-pluginモジュールを読み込む
const HtmlWebpackPlugin = require('html-webpack-plugin');

const src = path.join(__dirname, 'src');
const dist = path.join(__dirname, 'dist');

module.exports = {
  // developmentモードで実行します
  mode: 'development',
  // ビルドを実行するファイルパス
  entry: path.resolve(src, 'js/index.js'),
  output: {
    // 生成されるファイル名
    filename: 'index.bundle.js',
    // 生成先のディレクトリー
    path: dist
  },
  resolve: {
    // import文のパス指定にnode_modulesを省略できるようにします
    modules: ['node_modules'],
    // .jsまたは.jsxの拡張子を省略できるようにします
    extensions: ['.js', '.jsx']
  },
  module: {
    rules: [
      {
        // ルールを適用するファイルの正規表現
        test: /\.(js|jsx)$/,
        // node_modules以下のファイルには適用しないようにします
        exclude: /node_modules/,
        // 使用するloader
        loader: 'babel-loader'
      }
    ]
  },
  // sourceMappingの設定
  devtool: 'cheap-module-eval-source-map',
  devServer: {
    contentBase: dist, // 開発サーバーを立ち上げる参照ディレクトリー
    hot: true, // hot-reloadを有効にします
    port: 3000 // サーバーを立ち上げるポート番号
  },
  plugins: [
    // hot-reloadを有効にするプラグインを追加
    new webpack.HotModuleReplacementPlugin(), // HtmlWebpackPluginプラグインを追加
    new HtmlWebpackPlugin()
  ]
};
```

```
$ yarn serve
yarn run v1.12.3
$ webpack-dev-server --config webpack.config.js
ℹ ｢wds｣: Project is running at http://localhost:3000/
ℹ ｢wds｣: webpack output is served from /
ℹ ｢wds｣: Content not from webpack is served from /Users/hatanaka/jsDev/dist
ℹ ｢wdm｣: Hash: caa2a9d110cfda20f433
Version: webpack 4.26.0
Time: 933ms
Built at: 2018-11-22 11:26:51
          Asset       Size  Chunks             Chunk Names
index.bundle.js    882 KiB    main  [emitted]  main
     index.html  188 bytes          [emitted]  
Entrypoint main = index.bundle.js
[0] multi (webpack)-dev-server/client?http://localhost:3000 (webpack)/hot/dev-server.js ./src/js/index.js 52 bytes {main} [built]
[./node_modules/ansi-html/index.js] 4.16 KiB {main} [built]
[./node_modules/ansi-regex/index.js] 135 bytes {main} [built]
[./node_modules/loglevel/lib/loglevel.js] 7.68 KiB {main} [built]
[./node_modules/strip-ansi/index.js] 161 bytes {main} [built]
[./node_modules/url/url.js] 22.8 KiB {main} [built]
[./node_modules/webpack-dev-server/client/index.js?http://localhost:3000] (webpack)-dev-server/client?http://localhost:3000 7.78 KiB {main} [built]
[./node_modules/webpack-dev-server/client/overlay.js] (webpack)-dev-server/client/overlay.js 3.58 KiB {main} [built]
[./node_modules/webpack-dev-server/client/socket.js] (webpack)-dev-server/client/socket.js 1.05 KiB {main} [built]
[./node_modules/webpack/hot sync ^\.\/log$] (webpack)/hot sync nonrecursive ^\.\/log$ 170 bytes {main} [built]
[./node_modules/webpack/hot/dev-server.js] (webpack)/hot/dev-server.js 1.61 KiB {main} [built]
[./node_modules/webpack/hot/emitter.js] (webpack)/hot/emitter.js 75 bytes {main} [built]
[./node_modules/webpack/hot/log-apply-result.js] (webpack)/hot/log-apply-result.js 1.27 KiB {main} [built]
[./node_modules/webpack/hot/log.js] (webpack)/hot/log.js 1.11 KiB {main} [built]
[./src/js/index.js] 1020 bytes {main} [built]
    + 13 hidden modules
Child html-webpack-plugin for "index.html":
     1 asset
    Entrypoint undefined = index.html
    [./node_modules/html-webpack-plugin/lib/loader.js!./node_modules/html-webpack-plugin/default_index.ejs] 376 bytes {0} [built]
    [./node_modules/lodash/lodash.js] 527 KiB {0} [built]
    [./node_modules/webpack/buildin/global.js] (webpack)/buildin/global.js 489 bytes {0} [built]
    [./node_modules/webpack/buildin/module.js] (webpack)/buildin/module.js 497 bytes {0} [built]
ℹ ｢wdm｣: Compiled successfully.

```

<http://localhost:3000> 開くと，JavaScriptコンソールに表示されてる。

## 3章

ESLint 入れる。

eslint-config-airbnb 入れるので，依存モジュールのバージョン確認して…
```
$ yarn info eslint-config-airbnb peerDependencies
yarn info v1.12.3
{ eslint:
   '^4.19.1 || ^5.3.0',
  'eslint-plugin-import':
   '^2.14.0',
  'eslint-plugin-jsx-a11y':
   '^6.1.1',
  'eslint-plugin-react':
   '^7.11.0' }
✨  Done in 0.20s.
```

指定バージョン入れる。
```
$ yarn add --dev eslint-config-airbnb
yarn add v1.12.3
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
warning "eslint-config-airbnb > eslint-config-airbnb-base@13.1.0" has unmet peer dependency "eslint@^4.19.1 || ^5.3.0".
warning "eslint-config-airbnb > eslint-config-airbnb-base@13.1.0" has unmet peer dependency "eslint-plugin-import@^2.14.0".
warning " > eslint-config-airbnb@17.1.0" has unmet peer dependency "eslint@^4.19.1 || ^5.3.0".
warning " > eslint-config-airbnb@17.1.0" has unmet peer dependency "eslint-plugin-import@^2.14.0".
warning " > eslint-config-airbnb@17.1.0" has unmet peer dependency "eslint-plugin-jsx-a11y@^6.1.1".
warning " > eslint-config-airbnb@17.1.0" has unmet peer dependency "eslint-plugin-react@^7.11.0".
[4/4] 📃  Building fresh packages...

success Saved lockfile.
success Saved 3 new dependencies.
info Direct dependencies
└─ eslint-config-airbnb@17.1.0
info All dependencies
├─ eslint-config-airbnb-base@13.1.0
├─ eslint-config-airbnb@17.1.0
└─ eslint-restricted-globals@0.1.1
✨  Done in 2.31s.
```

忘れた。
```
$ yarn add --dev eslint-config-airbnb eslint@^5.3.0 eslint-plugin-import@^2.14.0 eslint-plugin-jsx-a11y@^6.1.1 eslint-plugin-react@^7.11.0 babel-eslint
$ yarn add --dev eslint-config-airbnb eslint@^5.3.0 eslint-plugin-import@^2.14.0 eslint-plugin-jsx-a11y@^6.1.1 eslint-plugin-react@^7.11.0 babel-eslint
yarn add v1.12.3
[1/4] 🔍  Resolving packages...
warning eslint > file-entry-cache > flat-cache > circular-json@0.3.3: CircularJSON is in maintenance only, flatted is its successor.
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 📃  Building fresh packages...

success Saved lockfile.
success Saved 75 new dependencies.
info Direct dependencies
├─ babel-eslint@10.0.1
├─ eslint-config-airbnb@17.1.0
├─ eslint-plugin-import@2.14.0
├─ eslint-plugin-jsx-a11y@6.1.2
├─ eslint-plugin-react@7.11.1
└─ eslint@5.9.0
info All dependencies
├─ ansi-escapes@3.1.0
├─ argparse@1.0.10
├─ aria-query@3.0.0
├─ axobject-query@2.0.2
├─ babel-eslint@10.0.1
├─ builtin-modules@1.1.1
├─ caller-path@0.1.0
├─ callsites@0.2.0
├─ chardet@0.7.0
├─ circular-json@0.3.3
├─ cli-cursor@2.1.0
├─ cli-width@2.2.0
├─ contains-path@0.1.0
├─ damerau-levenshtein@1.0.4
├─ deep-is@0.1.3
├─ emoji-regex@6.5.1
├─ error-ex@1.3.2
├─ eslint-config-airbnb@17.1.0
├─ eslint-import-resolver-node@0.3.2
├─ eslint-module-utils@2.2.0
├─ eslint-plugin-import@2.14.0
├─ eslint-plugin-jsx-a11y@6.1.2
├─ eslint-plugin-react@7.11.1
├─ eslint-utils@1.3.1
├─ eslint@5.9.0
├─ espree@4.1.0
├─ esprima@4.0.1
├─ esquery@1.0.1
├─ external-editor@3.0.3
├─ fast-levenshtein@2.0.6
├─ figures@2.0.0
├─ file-entry-cache@2.0.0
├─ flat-cache@1.3.4
├─ functional-red-black-tree@1.0.1
├─ hosted-git-info@2.7.1
├─ ignore@4.0.6
├─ inquirer@6.2.0
├─ is-arrayish@0.2.1
├─ is-builtin-module@1.0.0
├─ is-promise@2.1.0
├─ is-resolvable@1.1.0
├─ js-yaml@3.12.0
├─ json-stable-stringify-without-jsonify@1.0.1
├─ levn@0.3.0
├─ load-json-file@2.0.0
├─ mute-stream@0.0.7
├─ natural-compare@1.4.0
├─ normalize-package-data@2.4.0
├─ onetime@2.0.1
├─ optionator@0.8.2
├─ parse-json@2.2.0
├─ path-type@2.0.0
├─ pluralize@7.0.0
├─ progress@2.0.1
├─ prop-types@15.6.2
├─ read-pkg-up@2.0.0
├─ read-pkg@2.0.0
├─ regexpp@2.0.1
├─ require-uncached@1.0.3
├─ resolve-from@1.0.1
├─ restore-cursor@2.0.0
├─ run-async@2.3.0
├─ rxjs@6.3.3
├─ slice-ansi@1.0.0
├─ spdx-correct@3.0.2
├─ spdx-exceptions@2.2.0
├─ sprintf-js@1.0.3
├─ strip-bom@3.0.0
├─ table@5.1.0
├─ text-table@0.2.0
├─ through@2.3.8
├─ tmp@0.0.33
├─ validate-npm-package-license@3.0.4
├─ wordwrap@1.0.0
└─ write@0.2.1
✨  Done in 7.75s.

```

.eslintrc 作る。
```
vi .eslintrc
{
  "extends": ["airbnb", "plugin:flowtype/recommended"], # airbnbのルールを継承します
  "env": {
    "browser": true, # ブラウザーのグローバル変数を有効化します
    "es6": true # es6(es2015)の構文を有効化します
  },
  "parser": "babel-eslint", # babel-eslintをパーサとして使用
  "parserOptions": {
    "ecmaFeatures": {
      "jsx": true # jsxを有効化します
    }
  }
}
```

package.json に lint:js コマンド追加。
```
  "scripts": {
    "build:dev": "webpack --config webpack.config.js",
    "serve": "webpack-dev-server --config webpack.config.js",
    "lint:js": "eslint './src/js/*.{js,jsx}'"
  },
```

ESLint 実行。
```
$ yarn lint:js
yarn run v1.12.3
$ eslint './src/js/*.{js,jsx}'
Error: Cannot find module 'eslint-plugin-flowtype'
Referenced from: /Users/hatanaka/jsDev/.eslintrc
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:580:15)
    at Function.resolve (internal/modules/cjs/helpers.js:30:19)
    at resolve (/Users/hatanaka/jsDev/node_modules/eslint/lib/config/config-file.js:475:31)
    at load (/Users/hatanaka/jsDev/node_modules/eslint/lib/config/config-file.js:556:26)
    at configExtends.reduceRight (/Users/hatanaka/jsDev/node_modules/eslint/lib/config/config-file.js:430:36)
    at Array.reduceRight (<anonymous>)
    at applyExtends (/Users/hatanaka/jsDev/node_modules/eslint/lib/config/config-file.js:408:26)
    at loadFromDisk (/Users/hatanaka/jsDev/node_modules/eslint/lib/config/config-file.js:528:22)
    at Object.load (/Users/hatanaka/jsDev/node_modules/eslint/lib/config/config-file.js:564:20)
    at Config.getLocalConfigHierarchy (/Users/hatanaka/jsDev/node_modules/eslint/lib/config.js:227:44)
error Command failed with exit code 2.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.

```

??
```
$ yarn add --dev eslint-plugin-flowtype
 
```

再び
```
$ yarn lint:js
yarn run v1.12.3
$ eslint './src/js/*.{js,jsx}'

/Users/hatanaka/jsDev/src/js/index.js
   6:6   error    Expected 'this' to be used by class method 'say'  class-methods-use-this
   7:5   warning  Unexpected console statement                      no-console
  11:38  error    Newline required at end of file but not found     eol-last

✖ 3 problems (2 errors, 1 warning)
  1 error and 0 warnings potentially fixable with the `--fix` option.

error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.

```

class method で this 使わないから怒られる。
```
$ vi src/js/index.js
export class Hello {
  constructor(name) {
    this.name = name;
    this.say();
  }

  say() {
    console.log(`Hello ${this.name} World!`);
  }
}

export default new Hello('Nekomimi');

```

も一回。
```
$ yarn lint:js
yarn run v1.12.3
$ eslint './src/js/*.{js,jsx}'

/Users/hatanaka/jsDev/src/js/index.js
  8:5  warning  Unexpected console statement  no-console

✖ 1 problem (0 errors, 1 warning)

✨  Done in 1.22s.
```

まずはよし，と。

ビルドごとに実行するために eslint-loader 入れる。
```
$ yarn add --dev eslint-loader
yarn add v1.12.3
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 📃  Building fresh packages...

success Saved lockfile.
success Saved 3 new dependencies.
info Direct dependencies
└─ eslint-loader@2.1.1
info All dependencies
├─ eslint-loader@2.1.1
├─ loader-fs-cache@1.0.1
└─ object-hash@1.3.1
✨  Done in 2.61s.
```

webpack.config.js にeslint-loader の設定追加。
```

     {
        test: /\.(js|jsx)$/,
        exclude: /node_modules/,
        enforce: 'pre', // babel-loaderよりも前に実行される
        loader: 'eslint-loader'
      },

```

prettier 入れる。
```
$ yarn add --dev prettier
yarn add v1.12.3
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 📃  Building fresh packages...

success Saved lockfile.
success Saved 1 new dependency.
info Direct dependencies
└─ prettier@1.15.2
info All dependencies
└─ prettier@1.15.2
✨  Done in 2.48s.
```

.prettierrc 作る。
```
vi .prettierrc
{
  "printWidth": 100, # 1行あたりの最大文字数(それ以降は改行します)
  "singleQuote": true # ダブルクォートの代わりにシングルクォートを使用する
}
```

package.json に prettier コマンド。
```
    "prettier": "prettier --write './src/js/*.{js,jsx}'"
```

実行。
```
$ yarn prettier
yarn run v1.12.3
$ prettier --write './src/js/*.{js,jsx}'
src/js/index.js 47ms
✨  Done in 0.34s.
```

Flow 入れる。
```
$ yarn add --dev flow-bin @babel/preset-flow eslint-plugin-flowtype
yarn add v1.12.3
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 📃  Building fresh packages...

success Saved lockfile.
success Saved 5 new dependencies.
info Direct dependencies
├─ @babel/preset-flow@7.0.0
├─ eslint-plugin-flowtype@3.2.0
└─ flow-bin@0.86.0
info All dependencies
├─ @babel/plugin-syntax-flow@7.0.0
├─ @babel/plugin-transform-flow-strip-types@7.1.6
├─ @babel/preset-flow@7.0.0
├─ eslint-plugin-flowtype@3.2.0
└─ flow-bin@0.86.0
✨  Done in 3.39s.
```

.babelrc の preset に追加。
```
"@babel/preset-flow"
```

ESLint とのコンフリクト解消のため eslint-plugin-flowtype 入れたので，.eslintrc に追加。
```
  "plugins": ["flowtype"],
```

.flowconfig 追加。
```
$ vi .flowconfig
[ignore]
# Flowの対象除外ファイルパスを記述します

[include]
# ルート以外のFlowの対象ファイルパスを記述します 6:

[libs]
# 外部のFlow定義等のファイルパスを記述します 9:

[options]
# オプションの定義を記述します
```

package.json にコマンド追加。
```
    "flow": "flow"
```

src/js/index.js で，Flow の使用を宣言。
```
// @flow
```

やってみる。
```
$ yarn flow
yarn run v1.12.3
$ flow
Launching Flow server for /Users/hatanaka/jsDev
Spawned flow server (pid=6304)
Logs will go to /private/tmp/flow/zSUserszShatanakazSjsDev.log
Monitor logs will go to /private/tmp/flow/zSUserszShatanakazSjsDev.monitor_log
Error ┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈ src/js/index.js:3:15

Missing type annotation for name.

     1│ // @flow
     2│ export class Hello {
     3│   constructor(name) {
     4│     this.name = name;
     5│     this.say();
     6│   }


Error ┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈ src/js/index.js:4:10

Cannot assign name to this.name because property name is missing in Hello [1].

     1│ // @flow
 [1] 2│ export class Hello {
     3│   constructor(name) {
     4│     this.name = name;
     5│     this.say();
     6│   }
     7│


Error ┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈ src/js/index.js:9:31

Cannot get this.name because property name is missing in Hello [1].

 [1]  2│ export class Hello {
      3│   constructor(name) {
      4│     this.name = name;
      5│     this.say();
      6│   }
      7│
      8│   say() {
      9│     console.log(`Hello ${this.name} World!`);
     10│   }
     11│ }
     12│



Found 3 errors
error Command failed with exit code 2.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```

## 4章 React

追加。
```
$ yarn add react react-dom
yarn add v1.12.3
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 📃  Building fresh packages...

success Saved lockfile.
success Saved 2 new dependencies.
info Direct dependencies
├─ react-dom@16.6.3
└─ react@16.6.3
info All dependencies
├─ react-dom@16.6.3
└─ react@16.6.3
✨  Done in 2.75s.
```
```
$ yarn add --dev @babel/preset-react
yarn add v1.12.3
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 📃  Building fresh packages...

success Saved lockfile.
success Saved 6 new dependencies.
info Direct dependencies
└─ @babel/preset-react@7.0.0
info All dependencies
├─ @babel/helper-builder-react-jsx@7.0.0
├─ @babel/plugin-transform-react-display-name@7.0.0
├─ @babel/plugin-transform-react-jsx-self@7.0.0
├─ @babel/plugin-transform-react-jsx-source@7.0.0
├─ @babel/plugin-transform-react-jsx@7.1.6
└─ @babel/preset-react@7.0.0
✨  Done in 2.56s.
```

.babelrc に React 用設定追加。
```
vi .babelrc
    "@babel/preset-react",
```

src/html/index.html
```
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="utf-8">
<title>React test</title>
</head>
<body>
	<main id="react-test"></main>
</body>
</html>
```

webpack.config.js に追加・変更。
```
      template: path.resolve(src, 'html/index.html')
```

