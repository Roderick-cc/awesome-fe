
## 打包工具

* [**webpack**](https://github.com/webpack/webpack) - 打包项目。
* [**rollup**](https://github.com/rollup/rollup) - 打包 npm 库。
* [**parcel**](https://github.com/parcel-bundler/parcel) - webpack 竞品，但发展前景不乐观，再观察一段时间。
* [**systemjs**](https://github.com/systemjs/systemjs) - 针对一些特殊场景会比较有用，比如云 ide，支付宝小程序 IDE 等。
* [**microbundle**](https://github.com/developit/microbundle) - 基于 rollup，简化配置。
* [**bili**](https://github.com/egoist/bili) - 基于 rollup，同上。
* [**father**](https://github.com/umijs/father) - 组件打包工具，提供 babel 和 rollup 两种打包方式。
* [**vue-cli**](https://github.com/vuejs/vue-cli) - vue 命令行工具。
* [**create-react-app**](https://github.com/facebook/create-react-app) - react 官方脚手架。
* [**prepack**](https://github.com/facebook/prepack) - 通过预先执行的方式优化打包结果。
* [**lebab**](https://github.com/lebab/lebab) - 把 es5 代码转成 es6，反向 babel。
* [**esm-to-cjs**](https://github.com/sidvishnoi/esm-to-cjs) - 把 esm 转成 cjs。
* [**tsdx**](https://github.com/palmerhq/tsdx) - Zero-config CLI for TypeScript package development.

### webpack 辅助工具、Loader 和插件

* [**webpack-dev-server**](https://github.com/webpack/webpack-dev-server) - webpack 开发服务器。
* [**webpack-dev-middleware**](https://github.com/webpack/webpack-dev-middleware) - webpack 中间件。
* [**webpack-merge**](https://github.com/survivejs/webpack-merge) - 合并 webpack 配置。
* [**webpack-chain**](https://github.com/neutrinojs/webpack-chain) - 通过 chain 风格 api 的方式修改 webpack 配置。
* [**svgr**](https://github.com/smooth-code/svgr) - svg 转 react 组件。
* [**postcss**](https://github.com/postcss/postcss) - CSS 界的 babel。
* [**autoprefixer**](https://github.com/postcss/autoprefixer) - 为 CSS 选择权自动加 prefix。
* [**cssnano**](https://github.com/cssnano/cssnano) - CSS 压缩，也有类 preset 的概念。
* [**mini-css-extract-plugin**](https://github.com/webpack-contrib/mini-css-extract-plugin) - 提取 CSS 为单独文件。
* [**webpackbar**](https://github.com/nuxt/webpackbar) - webpack 进度条。
* [**webpack-bundle-analyzer**](https://github.com/webpack-contrib/webpack-bundle-analyzer) - 构建产物占比分析。
* [**uglifyjs-webpack-plugin**](https://github.com/webpack-contrib/uglifyjs-webpack-plugin) - JS 压缩，产物为 ES5 语法。
* [**terser-webpack-plugin**](https://github.com/webpack-contrib/terser-webpack-plugin) - JS 压缩，产物为 ES6 语法。
* [**webpack-manifest-plugin**](https://github.com/danethurber/webpack-manifest-plugin) - 生成 manifest.json。
* [**copy-webpack-plugin**](https://github.com/webpack-contrib/copy-webpack-plugin) - 复制额外的文件到输出目录。
* [**case-sensitive-paths-webpack-plugin**](https://github.com/Urthen/case-sensitive-paths-webpack-plugin) - 大小写敏感检测，能规避一些问题，但构建时性能消耗较大。
* [**css-hot-loader**](https://github.com/shepherdwind/css-hot-loader) - CSS 热更新，搭配 mini-css-extract-plugin 使用。
* [**duplicate-package-checker-webpack-plugin**](https://github.com/darrenscerri/duplicate-package-checker-webpack-plugin) - 重复依赖检测。
* [**fork-ts-checker-webpack-plugin**](https://github.com/Realytics/fork-ts-checker-webpack-plugin) - ts 语法检测。
* [**speed-measure-webpack-plugin**](https://github.com/stephencookdev/speed-measure-webpack-plugin) - 统计 webpack 各阶段耗时。

### Bundless

* [**vite**](https://github.com/vitejs/vite)
* [**snowpack**](https://github.com/pikapkg/snowpack) - 浏览器里跑 npm 依赖，面向现代浏览器。
* [**es-dev-server**](https://github.com/open-wc/open-wc/tree/master/packages/es-dev-server)

### 非 JavaScript 编译工具

* [**boa**](https://github.com/boa-dev/boa) - 基于 Rust，嵌入式 Javascript 引擎。
* [**cjs-module-lexer**](https://github.com/guybedford/cjs-module-lexer) - 通上，cjs 模块解析，也可以用 [cjs-module-lexer-rollup-reexports](https://github.com/yyx990803/cjs-module-lexer-rollup-reexports)。
* [**deno_lint**](https://github.com/denoland/deno_lint) - 基于 Rust，支持 JavaScript 和 TypeScript 的 lint 工具。
* [**dprint**](https://github.com/dprint/dprint) - 基于 Rust，代码格式化工具，Prettier 替代品。
* [**elsa**](https://github.com/elsaland/elsa) - 基于 Go，JavaScript 和 TypeScript 的 runtime。 
* [**es-module-lexer**](https://github.com/guybedford/es-module-lexer) - 基于 C，输出 Web Assembly，esm 模块解析。
* [**esbuild**](https://github.com/evanw/esbuild) - 基于 Go，Webpack 替代品。
* [**esbuild-node-tsc**](https://github.com/a7ul/esbuild-node-tsc) - 用 esbuild 编译 TypeScript 项目，但不支持类型检测。
* [**markdown-wasm**](https://github.com/rsms/markdown-wasm) - 基于 wasm 的 markdown 解析工具。
* [**minify**](https://github.com/tdewolff/minify) - 基于 Go，压缩器，支持 HTML5、CSS3、JS、JSON、SVG 和 XML。
* [**paperclip**](https://github.com/crcn/paperclip) - 基于 Rust 和 WAMS，React 视图组件的快速编译和预览。
* [**RSLint**](https://github.com/RDambrosio016/RSLint) - 基于 Rust，lint 工具。
* [**sucrase**](https://github.com/alangpierce/sucrase) - 基于 Rust，Babel 替代品。
* [**swc**](https://github.com/swc-project/swc) - 基于 rust 的语法转换器，babel 的竞争者。
* [**swc-node**](https://github.com/Brooooooklyn/swc-node)
* [**quick-lint-js**](https://github.com/quick-lint/quick-lint-js) - 基于 C++。
* [**markdown-wasm**](https://github.com/rsms/markdown-wasm) - 基于 wasm 的 markdown 解析工具。

## 包管理

* [**npm**](https://github.com/npm/cli)

## babel

* [**babel**](https://github.com/babel/babel)
* [**babel-plugin-dynamic-import-node**](https://github.com/airbnb/babel-plugin-dynamic-import-node) - 有些场景下会需要禁用 `import()` 语法。
* [**babel-plugin-macros**](https://github.com/kentcdodds/babel-plugin-macros) - 前端文件写 node 逻辑。
* [**babel-plugin-rawest**](https://github.com/sokra/rawact) - React 的 DOM 直出方案。
* [**babel-plugin-react-require**](https://github.com/vslinko/babel-plugin-react-require) - 自动为 jsx 语法加 react 引用。
* [**babel-plugin-transform-react-remove-prop-types**](https://github.com/oliviertassinari/babel-plugin-transform-react-remove-prop-types) - 删除 prop-types，生产环境用。

### macros

* [**import-all.macro**](https://github.com/kentcdodds/import-all.macro)

## 测试

* [**jest**](https://github.com/facebook/jest)
* [**ts-jest**](https://github.com/kulshekhar/ts-jest)
* [**enzyme**](https://github.com/airbnb/enzyme)
* [**jsdom**](https://github.com/jsdom/jsdom)
* [**puppeteer**](https://github.com/GoogleChrome/puppeteer)
* [**react-test-rerender**](https://github.com/facebook/react/tree/master/packages/react-test-renderer) - 官方出品。
* [**react-testing-library**](https://github.com/kentcdodds/react-testing-library) - kentcdodds 出品。

## 框架
* [**gastby**](https://github.com/gatsbyjs/gatsby)
* [**rekit**](https://github.com/rekit/rekit) - IDE and toolkit for building scalable web applications with React, Redux and React-router.
* [**choo**](https://github.com/choojs/choo) - dva 最初的 API 是参考这个实现的，已经不怎么发展了，再关注一段时间。
* [**after.js**](https://github.com/jaredpalmer/after.js)
* [**mint**](https://github.com/mint-lang/mint) - 提供了语言层方案的框架。
* [**quasar**](https://github.com/quasarframework/quasar) - 基于 vue，一套代码多处适用。

## react 相关库

* [**preact**](https://github.com/developit/preact) - 轻量级 React 实现。
* [**inferno**](https://github.com/infernojs/inferno) - 轻量级 React 实现。
* [**react-router**](https://github.com/ReactTraining/react-router) - React 路由方案。
* [**material-ui**](https://github.com/mui-org/material-ui) - UI 库。
* [**react-intl**](https://github.com/yahoo/react-intl) - React 的国际化方案。
* [**react-dnd**](https://github.com/react-dnd/react-dnd) - 拖拽实现。
* [**react-helmet**](https://github.com/nfl/react-helmet) - 修改 html 的 header 内容。
* [**react-jsonschema-form**](https://github.com/mozilla-services/react-jsonschema-form) - A React component for building Web forms from JSON Schema.


## 工具类

* [**history**](https://github.com/ReactTraining/history)
* [**path-to-regexp**](https://github.com/pillarjs/path-to-regexp) - path 转正则，路由相关处理的底层库。
* [**lodash**](https://github.com/lodash/lodash) - 工具集合。
* [**fastclick**](https://github.com/ftlabs/fastclick)
* [**date-fns**](https://github.com/date-fns/date-fns) - 时间处理。



## 性能优化

* [**workbox**](https://github.com/GoogleChrome/workbox) - PWA 方案，Google 出品。
* [**critical**](https://github.com/addyosmani/critical) - 提取关键 CSS。

## 语言

* [**typescript**](https://github.com/Microsoft/TypeScript)
* [**flow**](https://github.com/facebook/flow)
* [**graphql**](https://github.com/graphql/graphql-js)

## 文档

* [**dumi**](https://github.com/umijs/dumi)
* [**vuepress**](https://github.com/vuejs/vuepress)
* [**docz**](https://github.com/pedronauck/docz)
* [**storybook**](https://github.com/storybooks/storybook)
* [**mdx**](https://github.com/mdx-js/mdx) - jsx + markdown。

## 工程

* [**lerna**](https://github.com/lerna/lerna) - monorepo 管理。
* [**lerna-changelog**](https://github.com/lerna/lerna-changelog) - 为 lerna 项目自动生成 changelog。
* [**eslint**](https://github.com/eslint/eslint) - JS 风格约束。
* [**eslint-config-airbnb**](https://github.com/airbnb/javascript)
* [**xo**](https://github.com/xojs/xo) - 封装自 eslint。
* [**prettier**](https://github.com/prettier/prettier) - 更主观的风格自动修改。
* [**yeoman-generator**](https://github.com/yeoman/generator) - 脚手架工具。
* [**serve**](https://github.com/zeit/serve) - 本地静态服务器。
* [**servor**](https://github.com/lukejacksonn/servor) - 另一个静态服务器。
* [**budo**](https://github.com/mattdesl/budo) - 又一个静态服务器。
* [**np**](https://github.com/sindresorhus/np) - npm publish 辅助，自动 push、打 tag、升版本等。
* [**lint-staged**](https://github.com/okonet/lint-staged) - eslint 提速，只 lint 提交的代码。
* [**coveralls**](https://github.com/marketplace/coveralls) - 覆盖率。
* [**husky**](https://github.com/typicode/husky) - 添加 git hooks。
* [**cross-env**](https://github.com/kentcdodds/cross-env) - 跨平台的环境变量声明。
* [**projj**](https://github.com/popomore/projj) - 本地 git 项目管理，支持 github 和 gitlab。
* [**nvm**](https://github.com/creationix/nvm) - 管理 node 版本。
* [**concurrently**](https://github.com/kimmobrunfeldt/concurrently) - 在 npm scripts 里并行执行命令。
* [**@zeit/ncc**](https://github.com/zeit/ncc) - 打包为 npm 包为一个文件。
* [**npm-check**](https://github.com/dylang/npm-check) - 检测依赖升级情况，我会和 `yarn upgrade-interactive` 配合着用，主要用来检测冗余依赖。
* [**cpx**](https://github.com/mysticatea/cpx) - 复制，支持 glob，并且可以 watch。
* [**onchange**](https://github.com/Qard/onchange) - 监听文件变动然后做一些事。
* [**just**](https://github.com/Microsoft/just) - 微软出的任务管理器。
* [**tern**](https://github.com/ternjs/tern) - 代码分析器，为不少编辑器服务。
* [**lightproxy**](https://github.com/alibaba/lightproxy) - 底层协议代理工具，跨平台。

## 编辑器

* [**VSCode**](https://code.visualstudio.com/)
* [**IntelliJ IDEA**](https://www.jetbrains.com/idea/) 
* [**codesandbox**](https://codesandbox.io/)
* [**stackblitz**](https://stackblitz.com/)

## CloudIDE

* [**che**](https://github.com/eclipse/che)
* [**codesandbox-client**](https://github.com/CompuIves/codesandbox-client)
* [**theia**](https://github.com/theia-ide/theia)

## 字体

* [**Dank Mono**](https://dank.sh/)
* [**FiraCode**](https://github.com/tonsky/FiraCode)
* [**Operator Mono**](https://www.typography.com/blog/introducing-operator)

## CSS

* [**css modules**](https://github.com/css-modules/css-modules)
* [**emotion**](https://github.com/emotion-js/emotion)

## 命令行

* [**ajv**](https://github.com/epoberezkin/ajv) - 参数校验。
* [**chalk**](https://github.com/chalk/chalk) - 输出不同颜色。
* [**cheerio**](https://github.com/cheeriojs/cheerio) - 用类 jQuery 语法处理 HTML。
* [**chokidar**](https://github.com/paulmillr/chokidar) - 文件监听。
* [**clipboardy**](https://github.com/sindresorhus/clipboardy) - 复制文本到粘贴板。
* [**debug**](https://github.com/visionmedia/debug) - 打印调试信息。
* [**depd**](https://github.com/dougwilson/nodejs-depd) - 给出 deprecated 警告。
* [**deprecate**](https://github.com/brianc/node-deprecate) - 给过期警告。
* [**enquirer**](https://github.com/enquirer/enquirer) - 同上，更 cool 一些。
* [**execa**](https://github.com/sindresorhus/execa) - 比 child_process 好用，返回 Promise。
* [**figures**](https://github.com/sindresorhus/figures) - ✔︎ 等特殊字符，做了 windows 兼容处理。
* [**glob**](https://github.com/isaacs/node-glob) - 文件查找。
* [**ink**](https://github.com/vadimdemedes/ink) - 用 React 处理命令行输出。
* [**inquirer**](https://github.com/SBoudrias/Inquirer.js) - 交互式命令接口，比如 prompt。
* [**ora**](https://github.com/sindresorhus/ora) - 控制命令行光标，显示 loading 等。
* [**rimraf**](https://github.com/isaacs/rimraf) - 删除文件。
* [**signale**](https://github.com/klaussinani/signale) - 漂亮的日志打印。
* [**semver**](https://github.com/npm/node-semver) - semver 版本处理。
* [**tiny-glob**](https://github.com/terkelg/tiny-glob) - 文件查找。
* [**update-notifier**](https://github.com/yeoman/update-notifier) - 更新提醒。
* [**why-is-node-running**](https://github.com/mafintosh/why-is-node-running) - 检查 node 没退出的原因。
* [**yargs**](https://github.com/yargs/yargs) - 命令行入口套件。
* [**yargs-parser**](https://github.com/yargs/yargs-parser) - 命令行参数解析。

## 压缩解压缩

* [**compressing**](https://github.com/node-modules/compressing) - 压缩和解压缩。
* [**tar-fs**](https://github.com/mafintosh/tar-fs) - tar 的压缩和解压缩。
* [**yauzl**](https://github.com/thejoshwolfe/yauzl) - zip 解压缩。
* [**yazl**](https://www.npmjs.com/package/yazl) - zip 压缩。

## 语法解析

* [**esquery**](https://github.com/estools/esquery) - 语法树查询。

## Markdown

* [**markdown-it**](https://github.com/markdown-it/markdown-it) - Markdown 转 HTML。
* [**remark**](https://github.com/remarkjs/remark) - Markdown 语法解析器。

## 其他

* [**electron**](https://github.com/electron/electron)
* [**fx**](https://github.com/antonmedv/fx) - 交互式 JSON 查看。
* [**DeskGap**](https://github.com/patr0nus/DeskGap/) - 类 electron，由于不包含浏览器的部分，所以产物更小


## vscode 插件

* `GitLens` 【荐】
* `Git History` 有些同学习惯使用编辑器中的 Git 管理工具，而不太喜欢要打开另外一个 Git UI 工具的同学，这一款插件满足你查询所有 Git 记录的需求。
* `GitLens` 【荐】热更新
* `Chinese (Simplified) Language Pack for Visual Studio Code` 让软件显示为简体中文语言。
* `Bracket Pair Colorizer 2`：突出显示成对的括号【荐】
* `sftp`：文件传输 【荐】
* `open in browser` 在 HTML 文件中「右键选择 --> Open in Default Browser」，即可在浏览器中预览网页。
* `highlight-icemode`：选中相同的代码时，让高亮显示更加明显【荐】VS Code 自带的高亮就可以关掉了：在用户设置里添加"editor.selectionHighlight": false即可。 [** vscode 选中后相同内容高亮插件推荐 **](https://blog.csdn.net/palmer_kai/article/details/79548164)
* `vscode-icons`  根据文件的后缀名来显示不同的图标
* `Project Manager`  提供了专门的视图来展示你的项目，我们可以把常用的项目保存在这里，需要时一键切换，十分方便。
* `TODO Highlight` 写代码过程中，突然发现一个 Bug，但是又不想停下来手中的活，以免打断思路，怎么办？按照代码规范，我们一般是在代码中加个 TODO 注释。比如：（注意，一定要写成大写TODO，而不是小写的todo）
* `WakaTime ` 统计在 VS Code 里写代码的时间
* `Code Time` 录编程时间，统计代码行数。
* `Markdown Preview Github Styling` 【荐】以 GitHub 风格预览 Markdown 样式
* `Markdown Preview Enhanced` 预览 Markdown 样式。
* `Markdown All in One` 这个插件将帮助你更高效地在 Markdown 中编写文档
* `Settings Sync` 多台设备之间，同步 VS Code 配置。通过登录 GitHub 账号来使用这个同步工具
* `vscode-syncing` 多台设备之间，同步 VS Code 配置。
* `Vetur` Vue 多功能集成插件，包括：语法高亮，智能提示，emmet，错误提示，格式化，自动补全，debugger。VS Code 官方钦定 Vue 插件，Vue 开发者必备。
* `ES7 React/Redux/GraphQL/React-Native snippets` React/Redux/react-router 的语法智能提示。
* `minapp`：小程序支持
* `Prettier`：代码格式化
* `ESLint`：代码格式校验
* `Beautify` 代码格式化工具。
* `JavaScript(ES6) code snippets` ES6 语法智能提示，支持快速输入。
* `Search node_modules` 【荐】
* `indent-rainbow`：突出显示代码缩进
* `javascript console utils`：快速打印 log 日志【荐】
* `Code Spell Checker`：单词拼写错误检查
* `Local History` 【荐】 维护文件的本地历史记录，强烈建议安装。代码意外丢失时，有时可以救命。
* `Polacode-2020`：生成代码截图 【荐】
* `Image Preview` 【荐】 图片预览。鼠标移动到图片 url 上的时候，会自动显示图片的预览和图片尺寸。
* `Auto Close Tag、Auto Rename Tag` 自动闭合标签、自动对标签重命名
* `Better Comments` 为注释添加更醒目、带分类的色彩。
* `CSS Peek` 增强 HTML 和 CSS 之间的关联，快速查看该元素上的 CSS 样式。
* `Vue CSS Peek` CSS Peek 对 Vue 没有支持，该插件提供了对 Vue 文件的支持。
* `Color Info` 这个便捷的插件，将为你提供你在 CSS 中使用颜色的相关信息。你只需在颜色上悬停光标，就可以预览色块中色彩模型的（HEX、 RGB、HSL 和 CMYK）相关信息了。
* `RemoteHub` 可以在本地查看 GitHub 网站上的代码，而不需要将代码下载到本地。
* `Live Share`：实时编码分享
* `Import Cost` 我们会引入很多 npm 包，有时候可能只用到了某个包里的一个方法，却引入了整个包，导致代码体积增大很多。Import Cost插件可以在代码中友好的提示我们，当前引入的包会增加多少体积，这很有助于帮我们优化代码的体积。
* `paste JSON as Code` 此插件可以将剪贴板中的 JSON 字符串转换成工作代码。支持多种语言。