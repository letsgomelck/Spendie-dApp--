# 自学 Vue

> 2022-03-24  00:01



bilibili https://www.bilibili.com/video/BV1Zy4y1K7SH?p=4![Screen Shot 2022-03-24 at 00.02.10](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 00.02.102hUVe0.png)



 # 1.搭建Vue开发环境

## 1.1 安装VSC visual studio code

Live Server插件安装

## 1.2 Vue中文官网先引用script形式搭建Vue



> 之后会学 脚手架 CLI来应用Vue，初学者建议script

Vue开发版本就是开发用的

Vue生产版本是最终交付产品用的

下载下来，然后学习

https://cn.vuejs.org/v2/guide/installation.html#Vue-Devtools

![Screen Shot 2022-03-24 at 00.04.36](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 00.04.36pya75Ln9WkJv.png)



## 1.3 Chrome下载Vue Devtools插件

![Screen Shot 2022-03-24 at 00.13.59](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 00.13.59nwugo9.png)



## 1.4 用API关闭了烦人的提示



https://v2.vuejs.org/v2/api/#productionTip

![Screen Shot 2022-03-24 at 00.13.34](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 00.13.34pDf4ffsutUGU.png)

https://cn.vuejs.org/v2/api/#productionTip

![Screen Shot 2022-03-24 at 00.13.18](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 00.13.18KT90GJ.png)





# 2. Vue技术Hello小案例

## 2.1 vsc小快捷键

``` javascript
div#root然后回车
script然后回车
script tab下滑选项回车
```

就会触发快捷键

``` javascript
!或者！！然后回车就是html的框架
```



## 2.2 Shift+F5强制刷新后意外发现错误



![Screen Shot 2022-03-24 at 00.26.45](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 00.26.45d0BAes.png)

![Screen Shot 2022-03-24 at 00.27.18](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 00.27.18gbR26F.png)





在Network里强制刷新一次发现404



![Screen Shot 2022-03-24 at 00.30.14](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 00.30.14qGT69n.png)



点开之后发现 URL

![Screen Shot 2022-03-24 at 00.30.43](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 00.30.43LB9mwr.png)





## 2.3 将一个ico文件放入根目录就可以解决2.2的问题



https://cloudconvert.com/webp-to-ico

可以把png转换成ico

![Screen Shot 2022-03-24 at 00.39.12](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 00.39.121piVaA.png)





# 3.赶紧写一个Vue的代码

> 让Vue跑起来



尽量在全局配置之后开始代码

``` javascript
const x = new Vue()
```

教程里是mvvm

const vm = new Vue（）后面会教

现在怎么简单怎么来

![Screen Shot 2022-03-24 at 00.40.19](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 00.40.19uPJHeD.png)



然后（）里传什么，一般是配置对象 {}

比如javascript里的

``` vue
axios({
  url:'http://???###'
})
```



## 3.1 Vue里的第一个配置el

``` vue
const x = new Vue({
	el:'#root'
})
```

element元素的简称，像CSS里的id选择器



# 4. bilibili搜索VSC小插件

https://www.bilibili.com/video/BV1yD4y1c7WZ?spm_id_from=333.337.search-card.all.click

## 4.1 Color Manager，Color Highlight

## 4.2 GitLens查看代码都是谁写的

## 4.3 Project Manager 多项目同时打开 和 Peacock 更改窗口颜色区分不同项目

## 4.4 Code Time

## 4.5 Code runner 单独执行某个脚本

比如只测试某个函数或脚本文件，就不用运行整个项目了

``` javascript
console.log('一键三连')
```

## 4.6 Quokka.js 可以一边写代码一边显示输出结果

免费版需要先运行Quokka，然后通过Quokka去新建文件，再把代码拷进来就可以用

![Screen Shot 2022-03-24 at 01.01.59](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 01.01.59hS7rob.png)



## 4.7 REST Client，调试接口

类似于postman，可以直接在vscode中调试接口(省时间且没有大量接口的时候用)

在vsc中新建一个.http或者.rest，输入请求内容（send request），就可以看到接口返回的信息显示在右边

![Screen Shot 2022-03-24 at 01.04.27](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 01.04.27Mt3gaO.png)



## 4.8 Rainbow CSV 和 edit CSV 和 JSON to CSV

可以舒适的预览csv，编辑，将CSV转成json数据。整理数据时很方便



## 4.9 quotify

在写大量静态数据的时候，可以自动给字符串加上双引号![Screen Shot 2022-03-24 at 01.07.07](https://raw.githubusercontent.com/letsgomelck/Picsee/main/Picsee/Screen Shot 2022-03-24 at 01.07.07L9JUmG.png)



## 4.9 vscode-faker

自动生成假地址啥的



## 4.10 代码美化prettier， indenticator用一条直线突出显示当前的缩进

ident one space改变大段代码的空格缩进



## 4.11 bracket-padder输入括号后自动添加空格



## 4.12 Eslint 规范到每一个空格都要对齐

Eslint Chinese Rules



## 4.13 CodeSnap 自动截图选中的代码，方便问问题



## 4.14 搜索@popular查热门插件，或者vue搜索相关语言插件



学到P5  09:26 2022-03-24 01:36