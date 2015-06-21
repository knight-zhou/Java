# Java
为了能够更好的理解jsp程序的设计原理。能更好的理解jsp和数据库的结构关系。
这里是一个最简单
的网站帮助理解。
而这个zip是在myeclips倒出来的。真正有用的是Webroot下的内容还有数据库数据。
其中 WebRoot\WEB-INF\lib 下的是jar包。这是连接mysql的程序驱动包。
WebRoot下还有什么css 这是定义样式的
什么upload.jsp这是定义上传的 和php上传页面差不多。

部署思路：
对于mysql：
create database mytest;
source mytest.sql

然后将WebRoot下的内容拷贝到tomcat或者resin的根目录下即可。

到此部署完成能够访问。
