#react
1.准备React开发环境

Webpack/Vite:
Webpack 是一个前端资源加载 打包工具根据模块的依赖关系进行静态分析 然后将这些模块按照指定规则生成对应的静态资源
Vite 前端开发工具 开箱即用 基于原生es模块
区别:webpack是更底层的东西 vite是更上层的东西 webpack灵活度更高 vite开箱即用更简单 原理不同

脚手架
create-react-app
基于Webpack构建的
umi
基于Webpack构建

vite
基于Vite

 Npm安装 
作用:软件管理工具 是一个nodejs包管理和分发工具 
nrm:
作用:npm源管理器 允许你快速地在npm源间切换


Less, scss/sass
作用:css预处理语言 扩充了css语言 增加了一些功能
         Sass包括两套语法 最开始的叫缩进语法 使用回车将不同规则分隔开 较新的叫scss 使用和css一样的块语法
如何使用:使用源文件或者脚手架自带
区别: less更易上手 sass 需要编译环境不易上手

babel:
作用:js语法编译器 让浏览器能认识一些js语法

2.单页应用
index.html
优点:页面切换快(无需再次发起请求html文件 节约了http请求延时)
缺点:首屏时间稍慢 搜索引擎差(搜索引擎只认html 单页应用都是靠js渲染不好识别)

多页应用
a.html  b.html … n.html
优点:首屏时间快(服务器只需要返回一个html文件 经历一个http请求 请求响应回来就会展示页面) 搜索引擎好识别 根据内容好排名  
缺点:页面切换慢 (每次页面切换都要发起请求 网络差会卡顿)

首屏加载
从用户在浏览器的地址栏输入URL 地址 到首屏内容渲染完成的时间 此时网页不需要完全渲染完成 但需要当前视窗需要的内容



什么是class => es6
构造函数的另一种写法 ·

什么是hooks
不编写class的情况下使用state和react的其他特性
使用了js的闭包机制

useEffect 
会在每次渲染后执行不用考虑挂载与更新
在渲染后执行某些操作react会保存你传递的函数(就是effect) 并在dom更新后调用它    

componentDidMount() 组件已经被渲染到DOM中后运行



3.JSON

forEach和Map区别
Map会返回数据 forEach不会返回数据


ForEach
ayy.forEach(function(item,index)
	{return console.log(item)
	}
)
reduce对数组每个值进行叠加
Reduce (total(初始值),item(当前元素)){
	return console.log(total+item)
}
Es6 prototype

React memo
包含函数组件 避免相同props 下的重复渲染 达到优化效果 复用最近一次渲染结果

Alias
方便路径省略 插件
 
`	`符号
创建一个字符串 创建后不需要用加号连接字符串 

vite 和 webpack区别
开头有

classname 
引入后可设置多个样式

Object fit cover
在固定宽度高度下 不会挤压图片 多余的会裁减掉

Fill(要改成什么值, start, end) 将数组中的所有元素改为静态值 

filter((element, index, ) => {} ) 过滤掉不符合条件的 符合条件将返回

find((element )=> {}) 返回符合测试功能的第一个元素

findIndex((element )=> {}) 返回符合测试功能的第一个下标

indexOf((element fromIndex ) => {}) 寻找给定元素的第一个索引 不存在返回-1

push() 将一个或多个元素添加到数组的末尾并返回数组的新长度

join()连接数组中所有元素并返回一个新字符串 可添加分隔符


Hook 
Hook 是一个简单的函数 可以钩入react 的特性 
编写组件添加一些state 时就可以使用hook   