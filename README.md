这个项目是《Web 开发权威指南》的读书实践项目。

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