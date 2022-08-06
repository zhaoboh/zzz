#html&css

1.盒子模型  
所有的 ht           换行符 
inline 此元素显示为内联元素 元素前后没有换行符
inline-block 行内块元素
list-item 作为列表显示

2.常用块级标签
p  h1-h6  ul ol   hr  table  div. form  

常用行内元素
img  span  br  a  strong  b I.   input  

3.Flex
弹性布局 任何容器都可指定为flex 它的所有子元素自动成为容器成员
对块生效 

弹性布局 
Flex布局为什么要给min-width
在一个flex布局中 设置了一个flex为1的容器 在对其设置min-width为0保证内容不超出外层

Gap: 也是弹性盒子 设置网格行与列之间的间隙 

inline-fiex:将对象设为内联元素弹性伸缩盒显示 设置后盒子宽度会包裹子元素

Justify-content:
定义了横轴上的对齐方式  
Align-item:
定义了纵轴方向上的对齐方式

如果是内联元素 如何做到左右上下居中
左右居中: text-align
上下居中: line-height



4.Margin 
	1  对块生效 
	2  auto属性左右居中
	3  四个值 上 右 下 左 

绝对定位
absolute 和 fixed 统称为绝对定位  
使元素绝对定位 通过 left right top bottom 来定位 离元素最近的设置了绝对或相对定位的父元素来定位的  没有这样的父元素就根据html来定位

相对定位 
Relative  相对于自身的位置定位
使元素相对定位  相对于自己的正常位置进行定位

浮动定位 fixed 



5.CSS选择器有哪些:
.class   #ID   *所有元素   div ,p选择所有div和p    div p选择所有的diiv里的p元素
 a:link 所有未访问链接 a:visited 所有访问过的链接  
:first-child 其父级的第一个子元素
:last-child  其父级的最后一个字元素

Css执行顺序
 元素上的style>文件头部的style>外部的文件
 元素选择器越精确优先级越高 
 元素上的style>ID选择器>class选择器>元素类型选择器>子选择器>后代选择器>
 伪类选择器
 !important最高

css文本单行/多行显示省略号
 先隐藏超出部分 overflow:hidden  限制文本行数 -webkit-line-clamp  溢出显示省略号text-overflow:ellipsis


window.onload 
用于网页加载完毕后立即执行的操作 比如当html加载完毕后立即执行某个方法

Border-radius 
圆角可以单独设置不用边框

White space
规定文本不进行换行


CSS背景
Background-size 
指定图片大小
background-repeat
指定如何重复背景图像
Background-position
指定背景图像位置
Background: url()


Line-height
字体高度
font-family
多个名字名称作为退回系统保持 如果浏览器不支持第一个 则用下一个
