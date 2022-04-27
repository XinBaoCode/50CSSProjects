# 学习到的技术
## CSS
### Flex
我们发现在这个项目中，很多时候使用到了flex:1,flex:10的概念，所以有必要在这对flex技术进行解释。
**flex后接一个数字，这个数字的值代表flex-grow的值**

<img src="../image/1_Flex.png" />
这里解释一下flex-grow,flex-shrink和flex-basis的含义

|  名称 | 含义  |
| ---- | ---- |
| flex-grow |  flex-grow 定义项目的放大比例，默认为0，即如果存在剩余空间，也不放大 |
| flex-shrink |flex-shrink 定义了项目的缩小比例，默认为1，即如果空间不足，该项目将缩小 |
| flex-basis | flex-basis 给上面两个属性分配多余空间之前, 计算项目是否有多余空间, 默认值为 auto, 即项目本身的大小 |


这里的flex-grow为10的意思就是选中的图片是其他的未选中图片大小的10倍。

### CSS3的过渡动画
**-webkit-transition**
首先这个词可以拆成-webkit和transition两个词
对于**webkit**,是为了让chrome兼容。还有其他如下的前缀。

|Name | 意思  |
|--- | ---|
| -moz  | 代表firefox浏览器私有属性  |
| -ms |   代表IE浏览器私有属性 |
| -webkit | 代表chrome、safari私有属性 |
| -o- | 表示opera|

然后是**transition**,这个是CSS3的动画，它是4如下个属性简写构成。

|属性名 | 意思 |
| ---   | --- |
| transition-property | 过渡属性的名称，有all表示被动画的属性都表现出过渡动画|
| transition-duration | 以秒或毫秒为单位指定过渡动画所需的时间。默认值为 0s ，表示不出现过渡动画|
| transition-t慢速开始iming-function | 表示过渡动画的运动曲线,ease-in表示慢速开始 | 
| transition-delay | 表示过渡效果的延迟时间|

**使用场景**:transition一般在css中配合:hover, :active等伪类使用,实现相应等动画效果。