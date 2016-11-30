# 前端关注点（Experts）

> 我们建立关注点的目的在于，让团队中的每一个人具备产品基础研发能力的同时，有所专长，以至于达到一种多角放射的团队能力模型。

前端从本质上来说是在处理：**数据可视化** 和 **人机交互** 的问题。我们使用 Web，使用浏览器等作为媒介，所以我们被称为 Web 前端研发工程师。而现代的前端将不仅仅局限在 Web 了，而是向着全栈、全端的方向发展。

发展历史参考：`前端的发展历史.md`

总而言之，我想回答自己一个问题，我们现在的前端工程师团队究竟在做些什么？我们建立关注点的目的在于，让团队中的每一个人具备产品基础研发能力的同时，有所专长，以至于达到一种多角放射的团队能力模型。

我们可以参考：**前端团队系统图.graffle** 中对较大型（>=50人）的工程技术团队的结构展示。

![前端团队系统图](/Users/yeqingnan/Documents/Reference/ref_images/01/前端团队系统图.png)

## 前端基础设施技术

> 每一门技术都应该在合理实践之后，再加之以评论。

前端技术团队在 *软件工程* 的基础上，为多个业务团队提供底层的技术支持，针对一系列共性的问题，提出通用可行的解决方案，提高业务产出的效率（成本、速度、产出质量）。

### 前端技术背景

#### 计算机科学

- 高等数学基础概念
- 离散数学
- 计算机体系结构
- 计算机网络
- 操作系统
- 编译原理
- 软件工程

#### 程序设计背景

- 数据结构与算法
  - 熟悉最基本的数据结构：`List`, `Map`, `Stack`, `Queue`, `Set / HashList` ...
  - 熟悉复合的数据结构：树、堆、图 ...
  - 熟悉最基础的算法：搜索、排序、递归、贪心、图算法 ...
- 程序设计模式
- 程序架构设计（Micro-Services Architecture、Pub-Sub Pattern, Module, OO, Functional Programming）
- 编程范型：面向过程、面向对象（OOP）、函数式编程、AOP 等

#### 运行环境背景

- JavaScript 程序设计语言背景（语法核心、最佳实践、DOM、BOM、HTML5 ...）
  - 动态语言特征
  - 重要概念：`原型链` `作用域链` `函数` `闭包` `鸭式辩型` `原型继承` ...
  - JavaScript 虚拟机基础工作原理：内存管理（垃圾回收）、单线程 JS。
- 浏览器内核知识
  - 内核：Trident(IE Series) / Firefox(Gecko) / Chrome(Blink) / Safari(Webkit) / Opera(Blink) 参考：`Webkit.md`。
  - 览器的工作原理（重点：网络模块、渲染模块）参考：`浏览器网页渲染.md`。
- 服务器端基础知识
  - HTTP
  - Server-Side App

#### 安全背景

- CSRF / XSS
- SCP
- Same-origin policy
- ADsafe / Caja / Sandbox
- ...

#### 业界会议

- D2 / WebRebuild
- JSConf
- MDN
- ...

#### SEO

- 流量优化
- 内容优化
- 搜索引擎排名

### 基础技术标准

- 程序设计语言标准（HTML5, EcmaScript 3 / 5 / 6 / 7 , CSS3 ...）
  - 地方方言：`TypeScript`, `CoffeeScript`
- W3C: DOM / BOM / XHTML / XML / JSON / JSONP / ...
- 兼容标准（IE8+, Mobile 兼容性）
- 语义网络 Semantic Web（MicroData, RDFa）
- Web Accessibility（WCAG, Role Attribute, WAI-ARIA）
- 编码规范（JS 编码规范、CSS 编码规范, HTML 编码规范）
- 编辑器规范（Tab/Space, Index, UTF-8）
- 网络协议
  - HTTP 1.1 / HTTP 2.0
  - 通信标准（WebRTC, WebSocket, Ajax）
- 存储技术（WebSQL, IndexedDB）
- ...

### 社区基础技术

#### JavaScript 框架和库

- UI 框架：`React`, `Angular`, `Vue`, `Polymer`, `ExtJS` ...
- App 架构：`Redux`, `Reflux`, `Backbone` ...
- 工具库： `lodash`, `underscore.js` ...
  - 语言特性和工具：`lodash`, `underscore.js`
  - DOM 操作和增强：`jQuery`
  - 数据不可变性：`immutable.js`
  - 函数式编程：`ramda`, `folktale`
- 图形图像库：`d3`, `highchart`, `echarts` ...
- 模板引擎：`jade`, `dust` ...
- 动画库：`tween`, `bounce.js`, `three.js` ...
  - 物理引擎库
- 测试工具
  - 自动化测试框架启动器：`Karma`
  - 测试框架：`Mocha`, `QUnit`
  - 断言库：`expect.js`, `Chai`, `Should`
- ...

#### 跨平台

- WebAssembly
- WebWorker: `parallel.js`

##### 移动端

- 原生应用开发能力（Java / Swift）
- ReactNative
- Weex

##### Node 和生态：服务器、桌面端

- Node API：`Node.md`
- npm 包和依赖管理
  - `webpack`, `gulp`, `grunt`, `yoman`
- 服务器端库和框架
  - `express`, `koa`,
- npm 小颗粒度功能模块 / node.js
  - `async`, `fetch` ...
- 桌面端：`Electorn`, `NW.js`


#### CSS

- BEM：Block, Element, Modifier 是一种简明的 CSS 命名规范，利于 CSS 的调试和维护性成本的提高。[BEM Doc](https://en.bem.info/)
- 预处理语言：Stylus, Less, Sass ...
- 组件和样式框架：SemanticUI, Bootstrap, JuiceUI, FoundationUI, MaterialUI ...


### 前端工具链路

提供一系列的工具链来提高团队日常工作和效率。

#### 设计工具

- Sketch / Photoshop / Illustrator
- 3D Modeling Tool

#### 开发工具

- 代码编辑器 / IDE（Sublime, Atom, WebStorm, VSCode, Vim）
- 代码调试工具（Chrome DevTools）: DOM、网络、样式、断点、Profiler、内存 ...
- 代码规范化工具（Eslint, CSSLint, HTML Validator）
- 代码复审工具（Phabricator Diff）
- 版本管理工具 / 分布式开发管理工具（Git, Subversion）
- 包、依赖管理工具（npm, home-brew, pip, gem）
- 网络分析和代理工具（dns, web-proxy, web analysis）
- 代码托管工具（github, gitlab）
- 文档构建工具（JSDoc, gitbook）

#### 测试工具

- 单元测试工具（Mocha）
- 性能测试工具（DevTool Profiler, Google Page Speed）
- 集成测试工具（WebDriver）
- 环境模拟工具（iOS / Android Simulator,  `Phamthon.js`）
- 跨平台测试工具（`BrowserSync ` `SourceLabs`, `BrowserStack`）

#### 构建工具

- 基于 Node 的构建工具（`Gulp`, `Grunt`, `Yoman`, `Webpack`）
  - `uglify`, `clean-css` ...
  - `dev-server`

### 前端 UI 框架

#### PC 框架 / Mobile 框架

- 基础颗粒度组件
- 基础业务组件

#### 模板

- 可复用级别的页面 / 功能模板

## 前端中台技术和赋能

中台技术部门在基础技术部门的基础上提供成熟的针对特定问题的解决方案。这种解决方案多以「服务」的形式沉淀下来。

### 日志 / 监控技术

为整个前端体系和产品服务的稳定性奠定基础，也是高质量产品的保证。

- 性能优化：应用程序性能、网络性能、后端性能等
- 日志系统（反馈）
    - 日志系统：访问日志、行为日志、错误日志
    - 访问分析：日志分析
- 数据监控
    - 监控与报警系统

### 数据和元数据技术

为前端的项目提供底层的数据支持。可以是元数据平台，也可以是沉淀基础项目数据的平台。总之意在实现整个前端团队的「数据驱动」的目的。

### 文档和知识沉淀

#### 文档平台

- 通用规范
- 产品文档
- 开发文档
- 设计文档

#### 赋能平台

- 学习平台
- 考试平台

## 用户体验和应用设计流程

视觉展现和交互技术：在视觉和用户体验上做到极致，带来绝佳的感官体验。

- 平面设计 Graphic Design
    - 平面设计的基础知识
    - 平面设计工具的使用：`PS` / `Ai` / `Sketch` 等
    - 视觉设计所需要的：素养、积累、灵感
- 用户体验设计 User Experience Design
    - 交互设计的基本知识
    - 交互设计工具的使用
- 三维 / 多媒体技术
    - 三维基础知识
    - 媒体基础知识
    - 动画制作知识
- 程序实现：数据和信息可视化
    - 图像技术：滤镜技术
    - 动画技术
    - 声音技术
    - 视频技术
    - 三维技术
    - `CSS3` / `H5` / `SVG` 等 Web 富媒体技术




## 产品、业务和服务

这一层开发者专注提供「业务级别」的 App 开发和构建。

### App 的架构和框架的设计

为 App 的功能实现提供最基本的支持。也是 App 的中流砥柱，提供针对特定领域或者业务的服务解决方案。

- 项目的技术选型
- 前端程序的架构和设计，参考：`前端架构设计.md`
  - UI模块（React, WebComponent）
  - 通信模块
  - 存储模块
  - 安全模块
- 前端框架的设计和实现
- 业务定制化的：图形图像以及可视化框架。

---

- [Front-end Development](https://github.com/dypsilon/frontend-dev-bookmarks)
- [中文资源参考](https://github.com/foru17/front-end-collect)
- [前端面试的资料](https://github.com/hawx1993/Front-end-Interview-questions)
- [Awesome JavaScript Library](https://github.com/sorrycc/awesome-javascript)
- [NodeJS 中文资料](https://github.com/youyudehexie/node123)
- [Mobile 研发](https://github.com/hoosin/mobile-web-favorites)
- [前端技能树: FKS](https://github.com/JacksonTian/fks)