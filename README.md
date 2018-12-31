# Web开发知识体系总结
--大前端工程师知识体系结构详细分析

| Module | General |
| --- | --- |
| Basement | HTML / CSS / JavaScript |
| 类库 / Server 端技术 / 数据 | jQuery / Node.js, PHP, Python, JSP / MySQL, MongoDB / XML, JSON |
| 响应式 / 移动端 APP | 适配技术 / 移动端 APP 相关 |
| 工程开发工具 | 开发框架 / 开发工具 |

> updated 2018-12-31

## 1.Basement HTML/CSS/JavaScript
* `HTML`: 根据标签(`Tag`)标记(`Markup`)内容结构(`Content Structure`)
    * 通过 `HTML` 实现页面布局，语义化
    * 掌握 `HTML5` 新增的标签和属性
        * `HTML5` 移动端特性
        * `HTML5` 游戏特性
* `CSS`: 渲染内容效果
* `CSS3`: 增加了变形、过渡、转换、翻转效果
* `JavaScript`: 脚本语言，实现客户端交互体现


## 2.基于 `JavaScript` 实现的 `jQuery` 及其相关类库
* `jQuery`: 是 `JavaScript` 的类库
    * `write less, do more`
    * 通过 `jQuery` 可以轻松地实现客户端交互行为


* 基于 `jQuery` 又拓展了很多常用的类库，通过类库可以快速地构建客户端常用的组件、UI 呈现效果
    * `jQuery UI`, 基于 `jQuery` 的一个 UI 代码库
    * `jQuery EasyUI`, 基于 `jQuery` 的一个 UI 插件集合，用于打造丰富的 UI 界面
    * `ExtJS`, 基于 `jQuery` 的一个跨浏览器兼容组件，使用 `JSON` / `XML` 开发的

## 3.更多的 UI 效果 -- UI 类库
* `Highcharts`
    * 基于 `JavaScript` 实现的统计图表库，可以在页面添加交互图表，如：饼图、柱状图
* `Chart`
    * 基于 `HTML5 Canvas` 技术实现的图标库，功能 `Highcharts`
* `Two`
    * 基于 `HTML5` 实现的 2D API 绘图接口


## 4.与 Sever 端数据交互

* `JSP` - `Java`
* `ASP.NET`
* `PHP`：解释性的、服务器端编程语言
* `Python`: Server 学习入门


## 5. Database

* `MySQL`: 关系型数据库 / open source / by Oracle
* `SQL Server`
* `Oracle`
* `MongoDB`：基于分布式文件存储的数据库 / 可拓展的、高性能存储方案


## 6.数据交换格式

* `XML`: 数据传输、配置文件 / 描述数据格式
* `JSON`：`JavaScript` 的一个子集 / 纯文本、数据交换
* `AJAX`：基于 `JavaScript` 的异步交互实现，和 `XML` 的结合体 / 局部刷新


## 7. Framework：自动适配不同的客户端
* `Bootstrap`：Twitter 推出的前端响应式框架，基于 HTML/CSS/JavaScript 实现
* `Foundation`


## 8. Mobile APP
* `Cordova`/`PhoneGap`
    * `Cordova`: 通过 JS 访问原生设备
* `jQuery Mobile`
* `ionic`
    * 开发混合 Mobile APP
* `Reactive Native`

## 9.Engineer Framework
* `Node.js`: 基于 Google V8 引擎，用于搭建响应式框架工具
* `yo`/`grunt`/`bower`: 包管理工具
* `Gulp`/`Fis`: 自动化构建工具
* `RequireJS`/`Webpack`: 模块加载、打包工具
* 基于 MVC 或 MVVM 开发框架
    * `AngularJS`: 前端框架，用于单页面框架
    * `React`
    * `Ember`
    * `Backbone`
    * `Knockout`
    * `Spine`
    * `Batman`
    * `Vue.js`(MVVM)
