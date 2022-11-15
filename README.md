# CSS
# day 1

- **CSS使用：选择器（重点）**
- 美化网页（文字，阴影，超链接，列表，渐变）
- 浮动
- 定位
- 网页动画（特效）

### CSS（cascading style sheet）
**css发展**

1.0 

2.0 DIV + CSS

2.1 浮动，定位

3.0 圆角边框，阴影，动画

练习格式

### 使用

语法：

`选择器{
声明1;
声明2;
声明3;}`

在HTML中使用link标签引入style样式

*就近原则*

### 导入方法
链接式`link`

导入式`import`(不使用）


## 选择器
作用：选择页面上的某一个或某一类

1.基本选择器
- 标签选择器 选择一类标签 `标签{}`
- 类选择器  选择class属性一致的标签 `.类名{}`
- id选择器  全局唯一  `#id名{}`

*顺序* 

**id选择器>类选择器>标签选择器**，无就近原则


2.高级选择器
- 层次选择器
1. 后代选择器  后面所有`body p{background: aliceblue;}`
2. 子选择器  一代`body>p{background: #3b8686;}`
3. 相邻兄弟选择器  同类且下一个 `.active + p{background: blue;}`
4. 通用兄弟选择器  同类且下面所有`.active~p{background: chartreuse;}`

- 结构伪类选择器
伪类： 条件
