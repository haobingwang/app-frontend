这个项目是《Web 开发权威指南》的读书实践项目。

## 组织结构

<table>
<tr><th>项目名称</th><th>项目简介</tr>
<tr><td>Ottergram</td><td>第一个项目是一个基于 Web 的图片浏览应用。通过构建 Ottergram，能教会你通过使用 HTML、CSS以及 JavaScript 进行浏览器编程的基础知识。你将手动构建用户界面（User Interface，UI），并且掌握浏览器加载和渲染内容的方式</td></tr>
<tr><td>CoffeeRun</td><td>CoffeeRun 的一部分是咖啡订购表单，另一部分是清单。构建本应用涉及一系列 JavaScript 技术，包括编写模块代码、使用闭包，以及使用 Ajax 与远程服务器通信。你的关注点会从之前的手动创建 UI 转移到通过编程创建和操作 UI</td></tr>
<tr><td>Chattrbox</td><td>Chattrbox 的内容最少，但也最特别。你将用 JavaScript创建一个聊天系统，用 Node.js 编写一个聊天服务器和一个基于浏览器的聊天客户端</td></tr>
<tr><td>Tracker</td><td>最后一个项目将使用 Ember.js，它是前端开发最强大的框架之一。你将会创建一个应用，用来收录人们见过的奇异、神秘的珍稀生物。在开发过程中，你会学习支持 Ember.js 框架的丰富的生态系统</td></tr>
</table>

## 总结

- CSS ——通过类名选择器与 HTML 交互。
- JavaScript —— 使用 data 属性与 HTML 交互。

## JavaScript

### IIFE 立即调用函数表达式

IIFE（Immediately Invoked Function Expression）—— 立即调用函数表达式。

例如：

```js
// IIFE 的核心是两个括号：()()
// 第一个括号内是一个函数；
// 第二个括号内放入需要传进函数里的参数；
(function(){
  var version = '0.1';
})();
```

### webshim 库

### promise 链 —— 解决回调面条式代码

Promise 提供了一种管理复杂异步操作的方法，不再依赖模块之间通过回调的方式通信，使用 promise 对象可以一步步解耦模块。