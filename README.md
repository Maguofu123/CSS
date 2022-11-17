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

3.属性选择器（重点）
标签\[存在属性的元素]
标签\[属性名=属性值]

=绝对等于
\*=包含这个元素
^=以这个元素开头
$=以这个结尾

（区分大小写）

# day 2

行内元素`span`分割

块元素用`div`分割

**字体样式**
字体，粗细，大小，颜色

**文本样式**
RGB颜色，RGBA透明度，text-align排版

水平居中：text-align:center

首行缩进：text-indent:2em

竖直居中：使图片框大小和行大小相同，vertical-align

超链接伪类：一般使用hover，active，link，visited很少使用

**列表**
div标签，选中一定的范围，和span一样


**背景图片**
水平平铺，竖直平铺，不平铺

**渐变**
www.grabient.com

**盒子模型**
- margin外边距
- padding内边距
- border边框，（粗细，样式，颜色）

# day 3
**内外边距**

元素大小=margin+border+padding+内容宽度

**圆角边框**

border-radius

**盒子阴影**

box-shadow
