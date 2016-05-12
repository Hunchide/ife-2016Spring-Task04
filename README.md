#任务四说明
##review前
html结构，就是三个框，一灰两黄，灰包着两黄
位置关系上，父元素relative，子元素absolute，来个相对于父元素定位就好
水平居中，margin:0 auto;就好
问题是垂直居中怎么弄

然后按上面那个思路 感觉走不通了
并且自己执着于父元素一定要写relative,但是发现把父元素改成absolute后子元素的定位还是按相对父元素来定位的
这个原理不太懂！得再看看

父元素采用absolute后，就方便很多了，设置百分数的top和left就好

##review中

##review后
具体看看absolute会怎么默认，相对于哪个元素实现absolute定位

看其他同学的代码，好像还有flex和表格两种方法实现这种居中

得看看flex