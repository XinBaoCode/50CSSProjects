# 学习到的技术

## CSS

### box-sizing

`box-sizing`允许以特定的方式定义匹配某个区域的特定元素，默认值是`content-box`

| 值 | 描述 |
| -- | -- |
| content-box | 宽度和高度对应元素的内容框，不包括内边距(padding)和边框(border) |
| border-box | 宽度和高度包含了内边距(padding)和边框(border) |
| inherit | 从父元素继承box-sizing 属性的值 |


### overflow

`overflow`是当元素内容太大而无法适应块级格式化上下文时，所采用的的策略，它是`overflow-x`
和`overflow-y`的简写属性，默认值是`visible`

| 值 |  描述 |
| --- | --- |
| visible | 默认值，内容不会被修剪，会呈现在元素框之外|
| hidden | 内容被修剪，并且其余内容不可见 |
| scroll | 内容被修剪，浏览器有滚动条可以查看其余内容 |
| auto | 由浏览器定夺，如果内容被修剪，则有滚动条 |
| inherit | 继承父元素的overflow的值 |


### outline

轮廓（`outline`）是绘制于元素周围的一条线，位于边框边缘的外围，可起到突出元素的作用。

<img src="/image/2_outline.png" width="800" />

`outline`是不占空间的，即不会增加额外的width或者height
