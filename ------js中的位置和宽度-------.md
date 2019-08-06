#### ------js中的位置和宽度-------

##### 一、clientWidth和clientHeight、clientTop和clientTop

~~~
1.clientWidth的实际宽度
clientWidth = width + 左右padding
2.clientHeight的实际高度
clientHeight = height +上下padding
3.clientTop的实际宽度
clientTop = border.top(上边框的宽度)
4.clientLeft的实际宽度
clientLeft = border.left(左边框的宽度)

~~~

##### 二、offsetWidth和offsetHeight、offsetTop和offfsetLeft

~~~
offsetWidth和offsetHeight、offsetTop和offfsetLeft

~~~

##### 三、scrollWidth 和scrollHeight、scrollTop和scrollLeft

~~~
1.scrollWidth的实际宽度
	scrollWidth：获取指定标签内容层的真实宽度（可视区域宽度+被隐藏区域宽度）
2.scrollHeight的实际高度
	获取指定标签内容层的真实高度（可视区域高度+被隐藏区域高度）
3.scrollTop
	scrollTop： 内容层顶部，到可视区域顶部的距离
4.scrollLeft
	scrollLeft：内容层左端到可视区域左端的距离；
~~~

!1559730568737](C:\Users\15928\AppData\Local\Temp\1559730568737.png)