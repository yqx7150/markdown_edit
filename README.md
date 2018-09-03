# markdown_edit
  
作者

----
生成目录的方法:

* [1.语法示例](#1)

* [1.1图片](#1.1)

* [1.2换行](#1.2)

生成效果:

在正文中，只要将章节标题的id对应上去即可:

<h2 id="1">1.语法示例</h1>

<h2 id="2">1.1图片</h2>

<h2 id="3">1.2换行</h3>
## [标题]
标题有两种，一种是“有等级标题”，另外一种是“无等级标题”  
### 无等级标题
|    样例    |   输出  | 
| :-----:  | :------:| 
|  大标题  <br> ==== |  |
|   中标题 <br> ----  |    |


### 有等级标题
|    样例    |   输出  | 
| :-----:  | :------:| 
|   #一级标题  |    |
|  ##二级标题   |    |
| ###三级标题  |   |
| ####四级标题   |   |
| #####五级标题    |   |
| ######六级标题    |   |


## 文本

|    样例    |   输出  | 
| :-------:  | :--------:| 
| \*\*加粗** | **加粗**  | 
| \*斜体*    | *斜体* | 
| \[链接](`https://github.com/yqx7150/`) [注意1]  | [链接](https://github.com/yqx7150/) | 
|                 |   |


[注意1]：如果想链接到其他网页，不要忘了添加`https://`,如果不添加的话，GitHub会基于当前页面进行跳转。

>* \[链接](`https://github.com/yqx7150/`)注意：如果想链接到其他网页，不要忘了添加`https://`,如果不添加的话，GitHub会基于当前页面进行跳转。
>* \


**加粗** 
*斜体* 
[链接](https://github.com/yqx7150/)注意：如果想链接到其他网页，不要忘了添加`https://`,如果不添加的话，GitHub会基于当前页面进行跳转。

<span style="color: red"> Some red text </span>      
           <span color='red'  size=3 face="黑体">  红色，黑体，size为3 </span> 

## 其他

### 分割线
用至少三个以上的减号 -
```
分割线  
----- 
```

### 链接
[还是链接到百度][1]

[1]:https://www.baidu.com 

### [锚点]
字母要统统小写，空格统统要替换成 '-'  
URL 不区分大小写   

- [What's included](#whats-included)
- [Quick start](#quick-start)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [License](#license)
- [HTML 部分](#html-部分)

[锚点]:https://www.jianshu.com/p/baa5aaab4018
[标题]:https://www.jianshu.com/p/63ff519e90e4
