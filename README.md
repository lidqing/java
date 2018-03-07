# git操作
一、下载git文件

1. 确保已安装git工具

2. 在想要目录下右键—>GitBash，输入
git clone git@xxx.xxx.xx.xxx:android/xxx.git
说明：xxx.git为下载的文件或文件夹

二、上传git文件

1. 在要上传的工程master下，右键—>GitBash
2. git status
3. git add . -A
4. git commit -m "更新说明"
5. git push git@xxx.xxx.xx.xxx:android/xxx.git master

三、新上传一个工程到git服务器

1. 在要上传的工程master下（工程里面目录），右键—>GitBash
2. git init
3. git add . -A
4. git commit -m "更新说明"
5. git push git@xxx.xxx.xx.xxx:android/xxx.git master


java学习，资料整理
========
中标题
------

# 一级标题
## 二级标题


![baidu](http://www.baidu.com/img/bdlogo.gif)  

![github仓库里的图片](https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif)  

###### 给图片加上超链接
[![baidu]](http://baidu.com)  
[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo" 

```Java
public static void main(String[] args) //java
