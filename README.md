# Web 开发学习路线与资料

## 基础

### HTML 、CSS 与 JavaScript

一开始，世界上只有纯文本，后来人们想要一种基于互联网的超文本系统，于是便有了 HTTP 、HTML 和浏览器。

后来，人们想要由页面本身决定其样式，于是便有了 CSS 。

再后来，人们想让页面中有可交互的内容，于是便有了 JavaScript 。

入门资料：

- [MDN 的入门指南](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)（可以选择中文版）

### HTML5 、 CSS3 与 ECMAScript

为了让页面能够拥有更多的功能，也为了让大家能够能轻松地开发，一些新特性被加入了 HTML 、CSS 与 JavaScript 。有些特性还会在将来被添加到标准当中。

一些资料：

- [mdn.io](https://mdn.io)（需要翻墙）

  - [MDN](https://developer.mozilla.org/) （不需要翻墙）的快速链接，在地址后面加上特性名称可以快速进入相关介绍。

  - 比如 [mdn.io/flex-layout](https://mdn.io/flex-layout) 、[mdn.io/canvas-element](https://mdn.io/canvas-element) 、[mdn.io/promise](https://mdn.io/promise)

  - 大部分页面可以选择中文版

#### 兼容性

有些旧浏览器不支持很新的特性。但是我们可以查到有什么特性不被什么浏览器支持。

- [caniuse](http://caniuse.com/) ：浏览器兼容性表

- [JS compat](https://kangax.github.io/compat-table/es6/) : ECMAScript 兼容性表

### 给新手的脚本与样式库： JQuery 与 Bootstrap

这两个库可以大幅度缩短开发时间

- JQuery 教程与文档

  - [runoob.com 的 JQuery 教程](http://www.runoob.com/jquery/jquery-tutorial.html)

  - [JQuery 官方文档](http://api.jquery.com/)

- Bootstrap 教程与文档

  - [runoob.com 的 Bootstrap 教程](http://www.runoob.com/bootstrap/bootstrap-tutorial.html)

  - [Bootstrape 官方教程与文档](http://getbootstrap.com/)

### Node.js ：离开浏览器的 JavaScript

为什么 JavaScript 一定要在浏览器里跑呢？

一些资料：

- [runoob.com 的 Node.js 教程](http://www.runoob.com/nodejs/nodejs-tutorial.html)

- [Node.js 官方文档](https://nodejs.org/en/docs/)

### 杂项

#### 包管理器

包管理器能够让你在一个地方下到所有的库与工具，并保存你的配置，让你不用把别人的库拷来拷去。

- [npm](https://www.npmjs.com/) ：JavaScript 的包管理器

#### 代码检查

让你能够统一代码风格，并减少出错的可能性。

- [eslint](http://eslint.org/) ：JavaScript 的代码检查器

## 前端

前端的技术与框架太多了，标有⭐的是我们所使用的技术。

### 编译到 HTML 、CSS 与 JavaScript

#### 从模版语言编译到 HTML

这样就不用复制粘贴好多遍 HTML 代码了。


- [ejs](http://www.embeddedjs.com/)

- ⭐[pug](https://pugjs.org)

#### 用 CSS 预处理器编译到 CSS

这样就可以在 CSS 里使用变量、函数之类的东西了，这样更好维护。

- [less](http://lesscss.org/)

- [sass 与 ⭐scss](sass-lang.com/)

- [stylus](stylus-lang.com/)

#### 从更新的 JavaScript 编译到旧的 JavaScript

谁叫你们还用旧浏览器呢。

- ⭐[babel](https://babeljs.io/)

#### 从类似 JavaScript 的语言编译到 JavaScript

总是有人觉得 JavaScript 不好，于是他们决定用自己的方式拯救心爱的语言。

- [typescript](https://www.typescriptlang.org/)

- [coffeescript](coffeescript.org/)（已过气）

### 前端框架

使用组件化与数据绑定，让你像写 GUI 一样写前端。

- [react](https://facebook.github.io/react/)

- ⭐[vue](http://vuejs.org/)

- [angular](https://angularjs.org/)

- ⭐[polymer](https://www.polymer-project.org/)

### 自动构建

我总不能用三个命令分别编译出 HTML 、CSS 与 JavaScript 吧。

- [grunt](https://gruntjs.com/)（已过气）

- ⭐[gulp](https://gruntjs.com/)

- ⭐[webpack](https://webpack.github.io/)（和前两个的区别就跟 cmake 和 make 的区别一样）

## 后端

*待补充*