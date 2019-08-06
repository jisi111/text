### flex布局

##### flex布局是什么？

~~~html
 Flex是Flexible Box的缩写，意为"弹性布局"，用来为盒状模型提供最大的灵活性。
任何一个容器都可以指定为flex布局
.box{
	display:flex;
}
行内元素也可以使用Flex布局
.box{
display:inline-flex;
}
Webkit内核的浏览器，必须加上-webkit的前缀
.box{
	display:-webkit-flex;/*Safari*/
	display:flex;
}
注意：设为Flex布局以后，子元素的float，clear和vertical-align属性将失效
~~~

#### 基本概念

~~~CQL
采用Flex布局的元素，称为Flex容器（flex container），简称"容器"，它的所有子元素自动成为容器成员，成为Flex项目（flex item），简称"项目"。
容器默认存在两根轴：水平的主轴（main axis）和垂直的交叉轴（cross axis）。主轴的开始位置（与边框的交叉点）叫做main start，结束位置叫做main end；交叉轴的开始位置叫做cross start，结束位置叫做cross end。

项目默认沿主轴排列。单个项目占据的主轴空间叫做main size，占据的交叉轴空间叫做cross size。
~~~

##### 容器属性

~~~
以下6个属性设置在容器上
1.flex-direction:row| row-reverse|column|column-reverse //决定项目的排列方向
2.flex-wrap: nowrap（不换行）|wrap 换行，第一行在上方|wrap-reverse（换行，第一行在下方） //如果一条轴线排不下，如何换行
3.flex-flow:<flex-direction> <flex-erap>;//1和2的简写形式
4.justify-content:flex-statrt|flex-end|center|space-between|space-around//项目在主轴上的对齐方式
5.align-items:flex-start| flex-end|center|baseline|stretch(默认值)//属性定义在交叉轴上如何对齐;
6.align-content::flex-start| flex-end|center|baseline|stretch(默认值)//属性定义了多根轴线的对齐方式
~~~

#### 项目属性

~~~
以下6个属性定义在项目上
order：<integer>//定义项目的排列顺序，数值越小，排列越靠前，默认为0
flex-grow
flex-shrink
flex-basis
flex
align-self
~~~

