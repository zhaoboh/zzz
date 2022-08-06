#internet
1.网络与浏览器

 DOMcontentLoaded 与 load
DOM文档加载步骤
1 解析html结构
2 加载外部脚本和样式表文件
3 解析并执行脚本代码
4 构造HTML DOM模型 //DOMContentLoaded执行点
5 加载图片等外部文件
6 页面加载完毕 // load

主域名 子域名
主域名由两个及两个以上字母构成 整个域名通常只有一个点号
子域名有很多个 是主域名的下一级或下下级域名
子域名与子域名一般权限都是分开的 不会彼此影响

DNS 
域名系统 将域名和IP地址相互映射的一个分布式数据库 

TCP
传输控制协议 传输层可靠的通信协议 
建立一个连接需要3次握手 终止一个连接需要4次握手

URL 
协议( http )  
域名部分 ( 主体 ) 
端口 ( 可忽略 )
虚拟目录 ( path )
文件名 
参数部分
片段部分

2.sessionStorage localStorage cookie 区别
1 都保存在浏览器端 且同源
2 Cookie需要网络请求数据 sessionStorage localStorage不会主动发送数据
3 cookie一般4k sessionStorage localStorage一般5M甚至更大 
4 sessionStorage 仅存于浏览器存在时  localStorage 保存在本地会一直存在
Cookie时间由设置时间决定

同源
同源的条件：
URL的主机一致
协议（Scheme）一致
端口号一致

CDN
内容分发网络的一套体系 提升文件下载速度的一种机制
离自己最近的CDN服务器进行下载
不过只能用于静态数据的加速 动态接口不能加载

3.Window 对象：浏览器窗口对象
History：浏览器当前窗口的访问历史记录对象
Location：浏览器当前窗口的地址栏对象









