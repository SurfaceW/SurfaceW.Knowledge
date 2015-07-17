# 前端技术概述

> 以下的每一门技术我都必须使用之后，再加之以评论。

## 前端关注点（Experts）

> 我们建立关注点的目的在于，让团队中的每一个具备产品基础研发能力的同时，有所专长，以至于达到一种多角放射的团队能力模型。

### App 架构、框架、工具构建技术

> 为 App 的功能实现提供最基本的支持。也是 App 的中流砥柱。

- App 程序的架构和设计
- 框架的设计
- 工具的设计

### 视觉展现和交互技术

- 平面设计 Graphic Design
    - 平面设计的基础知识
    - 平面设计工具的使用
        - PS Ai Sketch
    - 视觉设计所需要的：素养、积累、灵感
- 交互设计
    - 交互设计的基本知识
    - 交互设计工作的使用
- 三维 / 多媒体技术
    - 三维基础知识
    - 媒体基础知识
    - 动画制作知识
- 程序实现
    - 图像技术
        - 滤镜技术
    - 动画技术
    - 声音技术
    - 视频技术
    - 三维技术
    - CSS3 / H5 / SVG 等 Web 富媒体技术

### 性能、反馈、监控技术

- 性能优化
- 数据监控
- 反馈系统

### 通信、存储、安全技术

- 通信技术
- 存储技术
- 安全技术

### 工程化技术

- 自动化部署
- 自动化测试
- 自动化上线

## 前端技术体系

### 前端环境知识

- 计算机科学与技术基础知识：编译原理、操作系统、计算机网络、算法与数据结构、软件工程 ...
- 编程知识
    - 数据结构
    - OOP / AOP
    - 原型链 / 作用域链
    - 闭包
    - 编程范型
    - 设计模式
    - ...
- 浏览器知识：Trident(IE Series) / Firefox(Gecko) / Chrome(Blink) / Safari(Webkit) / Opera(Blink)
    - 浏览器的工作原理（网络模块、渲染模块）
- 多媒体技术
    - SVG / Canvas / VML
    - SVG: D3 / Snap.svg / DataV
    - Canvas: ZRender / CreateJS / KineticJS
    - WebGL: ThreeJS
- 移动端开发知识
    - Google Web 开发指南
    - 响应式网页设计
    - Hybrid
        - PhoneGap
        - jQuery Mobile
    - Native
        - React Native
        - TypeScript
- 标准与规范
    - 网络规范：HTTP/1.1 / HTTP/2
    - ECMAScript 3/5/6
    - W3C: DOM / BOM / XHTML / XML / JSON / JSONP / ...
    - CommonJS / AMD
    - HTML5 / CSS3
    - Semantic Web
        - MicroData
        - RDFa
    - Web Accessibility
        - WCAG
        - Role Attribute
        - WAI-ARIA
- 安全知识
    - CSRF / XSS
    - SCP
    - Same-origin policy
    - ADsafe / Caja / Sandbox
- 业界会议
    - D2 / WebRebuild
    - JSConf
    - MDN
    - ...

### 语言

- JavaScript:ES1, ES3, ES5 / **ES6**
    - Preprocess-Language as TypeScript / CoffeeScript
- CSS（DSL）
    - Preprocess-Language as LESS/Sass/Stylus ...
- HTML（DSL）
- Java for Android / Embedded System
- OBC / Swift for iOS

### 工具

- 编码工具：SublimeText / WebStorm / Atom / Vim ...
- 原型工具：Photoshop / Illustrator / Sketch ...
- 调试工具：Firebug / Chrome Dev Tools ...
- 版本管理：SVN / Git / Mercurial ...
- 代码托管：Github / SourceForge ...

#### 代码质量

##### Coding Style

- JSLint / JSHint / ESLint
- CSSLint
- Markup Validation Service
- HTML Validator

##### 单元测试

- QUnit / Jasmine
- **Mocha** / Should / Chai / Expect
- UnitJS

##### 自动化测试

- WebDriver / Protractor / Karma Runner / Sahi
- phantomjs
- SourceLas / BrowserStack

##### 性能优化

- JSPerf
- YSlow 35 rules
- PageSpeed
- HTTPWatch
- DynaTrace's Ajax
- *purifycss*
    - 删除没有使用的 CSS

#### SEO

- 流量优化

#### 部署流程

- 压缩合并
    - YUI Compressor / Google Clousure Complier / Uglify JS / CleanCSS
- 文档输出
    - JSDoc / Dox / Doxmate / Grunt-Doxmate
- 项目构建工具
    - make/Ant / GYP / Grunt / Gulp / Yeoman / FIS / Mod
- 代码组织
    - 类库模块化：CommonJS / AMD / YUI3
    - 逻辑业务模块化：bower / component
    - 文件加载：LABjs / SeaJS / Require.js
    - 模块化预处理器：Browserify

### 类库与框架

#### JS 框架

- jQuery / Underscore / Mootools / Prototype.js
- YUI3 / Dojo / ExtJS / KISSY
- Backbone / KnockoutJS / Emberjs
- AngularJS
- React / React Native
- Polymer
- Atoms
- qooxdoo
- Brick
- ...

#### 样式组件框架

- Backbone
- Semantic UI
- Juice UI
- Foundation UI
- ...

#### 工具库

- 图表展示：eCharts
- 图书制作：gitbook
- 异步编程：async(Node)
- 动画工具：animate.css / move.js / TweenJS / bounce.js
- ...


## 技术演变史

### 石器时代

- HTML
- CSS
- XML技术系列（XML / SVG 等）
- 微量的 JavaScript 构建的网页
- 一些特殊功能需要用 ActiveX / Applet / Flash / Silverlight 等技术来扩展实现
- 用基本的后端技术：ASP / JSP / PHP 等做动态网站

### 铁器时代

- Ajax 技术的引入
- 衍生出第一代 JS 库和框架：Prototype Mootool 等
- 衍生出第二代 JS 库和框架：YUI ExtJS 等
- 衍生出第三代 JS 库和框架：jQuery 等
- HTML5 和 CSS3 逐渐趋于成熟，浏览器大混战逐渐达到统一，IE6、7等古董级浏览器逐渐降低市场份额
	- 富媒体的 HTML5 和 CSS3 大量刷新 Web 的表现形式和程序设计
	- RIA 技术逐渐退出历史的舞台
- 模块化和组件化的引入
	- CommonJS / AMD 规范
	- RequireJS 等模块异步加载方案的出现
- NodeJS 出现，前端工程师也能跳出浏览器的沙盒了，以此开始构建服务端应用和各种提升效率的工具。
- 衍生出第四代 JS 库和框架：(MV* 框架) 模板引擎 + Router 等前端扩展
	- Backbone 风格
	- AngularJS 风格
	- Polymer / React / FLUX 架构

### 工业时代

- Web Component 思想的提倡，标签即为组件
- 移动端研发
    - Native 流
    - Web 流：也被称为 Hybrid 技术，它基于 Web 相关技术来实现界面及功能（内嵌入 WebView，内部API，JS调用）
        - PhoneGap / Cordorva
    - 代码转换流：将某个语言转成 Objective-C、Java 或 C#，然后使用不同平台下的官方工具来开发
    - 编译流：将某个语言编译为二进制文件，生成动态库或打包成 apk/ipa/xap 文件
    - 虚拟机流：通过将某个语言的虚拟机移植到不同平台上来运行
        - React Native / NativeScript
        - Adobe AIR / Dart
- ES6：新的特性让 JavaScript 变得更强
- 高度复杂化的多样技术的引入，有点百家争鸣的感觉，从而也迸发了前端无限的生机和活力
    - Canvas / WebGL ...


## 综合资源

[Front-end Development](https://github.com/dypsilon/frontend-dev-bookmarks)
[中文资源参考](https://github.com/foru17/front-end-collect)
[前端面试的资料](https://github.com/hawx1993/Front-end-Interview-questions)
[Awesome JavaScript Library](https://github.com/sorrycc/awesome-javascript)
[NodeJS 中文资料](https://github.com/youyudehexie/node123)
[Mobile 研发](https://github.com/hoosin/mobile-web-favorites)

---

参考文章：

[前端技能树: FKS](https://github.com/JacksonTian/fks)

----
version 1.1 via 2015年03月06日 凭借现在的理解所写
