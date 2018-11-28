# vue 学习笔记
2018.11.28
### Vue 模板语法
1、v-once 指令，可以执行一次性插值，当数据改变时，插值处的内容不会更新。

2、v-html 指令，可以输出解释为 html 代码。

3、v-bind 指令，作用在 HTML 特性上，值为 true， false，null，undefined
****
2018.11.19
****
1、 JavaScript Date 对象
toLocaleString() 方法可根据本地时间把 Date 对象转换为字符串，并返回结果。

2、Object.freeze(obj) 方法可以冻结一个对象，冻结指的是不能向这个对象添加新的属性，不能修改其已有属性的值，不能删除已有属性，以及不能修改该对象已有属性的可枚举性、可配置性、可写性。该方法返回被冻结的对象。

3、Vue 生命周期：created、mounted、updated、destroyed。
生命周期钩子的 this 上下文指向调用它的 Vue 实例。