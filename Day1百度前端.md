# day1
## 自己的水平
1. 慕课网上**简单**的CSS和HTML代码编写
2. Dreamweaver写过一两个页面

## 今日学习内容
### “利器”
1.建立showcase收藏夹，用来收藏厉害的网页
  看了课程介绍的网页，打破我对前端的认知，页面很酷炫，页面分享如下：
***
    http://2014.artsy.net/
    https://codepen.io/Yakudoo/full/rJjOJx
    https://codepen.io/pissang/full/geajpX
    https://codepen.io/tsuhre/full/BYbjyg
    https://wangyasai.github.io/Stars-Emmision/
    https://pissang.github.io/papercut-box-art/
    https://demo.marpi.pl/biomes/
    https://pissang.github.io/voxelize-image/
    http://echarts.baidu.com/examples/index.html#chart-type-globe
    https://tympanus.net/Development/AudioVisualizers/（推荐戴耳机）
***
2.注册opencode和github账户
### 知识点
* ## JS
弹出窗口代码块：

	document.getElementById("btn").onclick = function () {
	// 点按钮后弹出一个文字，你可以尝试改变文字内容
	alert("学前端，就来百度前端技术学院");
	}

##阅读笔记
###web建站技术：
1.web建站技术中各个名词概念：
	很有意思的一个观点“html是名词，css是形容词，javascript是动词。三个互相配合才是一句句子”

	html：（表示内容和语义）
		标记语言，界面会按html渲染出效果呈现给用户，但是都比较简洁不够美观；
	css：（规定样式）
		用来写自定义或规定样式的代码文件；可以根据需要和美观写相应的css代码；浏览器根据css代码画出对应的样式；
	Html5:
		通行标准，加了一些属性和标签，我的理解是加了更多封装好的功能可以直接调用；
    
   以上为静态页面；

	JavaScript：（动态效果）
	
	Ajax：
		Ajax 即“Asynchronous Javascript And XML”（异步 JavaScript 和 XML），是指一种创建交互式网页应用的网页开发技术。
		Ajax = 异步 JavaScript 和 XML（标准通用标记语言的子集）。
		Ajax 是一种用于创建快速动态网页的技术。
		Ajax 是一种在无需重新加载整个网页的情况下，能够更新部分网页的技术。
	
	PHP：服务器脚本语言


	Apache：web服务器软件
	Tornado：是一种 Web 服务器软件的开源版本。
	Nginx (engine x) ：是一个高性能的HTTP和反向代理服务器,也是一个IMAP/POP3/SMTP服务器。	
	
2.几种常见的框架：
	LAMP=Linux + Apache + MySQL + PHP（P还可能是Python或Perl。有时候L会改成W=Windows。）
	重点不在技术而且在乎成本的新网站比较喜欢用 LAMP

	J2EE，Java 世界的架构，通常是企业用的（银行、大型公司,.etc），比较常见地还会搭配一种 UNIX 做操作系统，Apache 做 Web Server，Tomcat 转换 JSP 到 Java 给服务器程序用（其实它也自带 Web Server），Oracle 数据库等等。不一定拿来建站，常常用来提供企业里的各种需要用到网络的业务。


	重视安全稳定和速度的企业和机构喜欢 J2EE

	ASP.net:微软构架，通常会搭配 Windows Server 操作系统，SQL Server 数据库，IIS 做 Web Server；
	想省事的网站喜欢 ASP.NET

	MEAN架构（比较新的架构），MongoDB做数据库，Express做 Web Framework，Angular 做前端的 JavaScript 框架，Node.js 用于编写 Web Server。神奇之处在于这几个东西的语言都是 JavaScript （MongoDB的实现不是，但与外界沟通用的语言是）。
