# vue.js

MVVM前端视图层开发思想（提供数据双向绑定），VM是MVVM核心。

M:保存每个页面中单独的数据

VM：调度。分割M和V，V层想获取后保存数据需要经过VM中间处理

V:页面中HTML代码

js表达式  js代码（语句）

1.表达式：一个表达式会产生一个值，可以放在任何一个需要值的地方：

（1）a
（2）a+b
（3）demo（1）
（4）x===y？'a':'b'

2.js代码（语句）
（1）if（）{}
（2）for（）{}

1.想让Vue工作，必须创建一个Vue实例，且要传入一个配置对象

2.root容器里的代码被称为【Vue模板】

3.Vue实例和容器是一一对应的 

4.只能有一个Vue实例，配合组件一起使用

5.{{js表达式}}

6.data中数据发生改变，模板中相对应数据改变

模板语法

.toUpperCase()【大写】

插值语法（解析标签体内容）

指令语法（解析标签，包括标签属性、标签体内容、绑定事件。。。。。。）

v-bind：（单项绑定，数据只能从data流向页面）可以给任何属性动态赋值（可以简写为英文：）

v-model:（双向绑定，数据不仅能从data流向页面，还可以从页面流向data）
              1.双向绑定一般都应用在表单类元素上（如：input、select等）
              2.v-model：value可以简写为v-model，因为v-model默认收集的就是value值
