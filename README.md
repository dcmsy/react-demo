# react-demo

这里是 Ant Design 学习demo。

#特性

Designed as Ant Design，提炼和服务企业级中后台产品的交互语言和视觉风格。
React Component 上精心封装的高质量 UI 库。
基于 npm + webpack + babel 的工作流，支持 ES2015。

#安装

$ npm install antd

#示例

import { DatePicker } from 'antd';
ReactDOM.render(<DatePicker />, mountNode);

#引入样式：

import 'antd/lib/index.css';  // or 'antd/style/index.less'
按需加载可通过此写法 import DatePicker from 'antd/lib/date-picker' 或使用插件 babel-plugin-antd。

#dora

dora 是一个开发服务器，通过插件的方式集合各种调试方案，比如 webpack、livereload、browsersync、数据 mock、本地代理、weinre、jsonapi 等等。

#atool-build

atool-build 是对 webpack 的进一步封装，它会为你生成配置文件并调用 webpack 进行构建。atool-build 默认使用的配置文件，包含了大部分常用的 webpack 的 loader 和插件；当这些功能不能满足你的项目需求，或你需要自定义化配置时，可以添加这个自定义配置文件。但请注意，这个文件的内容和标准的 webpack 的配置文件不一样。
