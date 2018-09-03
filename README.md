# markdown_edit
  
作者

----
## 生成目录
```
* [主标题](#1)  
  * [副标题1](#1.1)  
  * [副标题2](#1.2)  
  * [副标题3](#1.3)
 
<h3 id="1">主标题</h3>
<h4 id="1.1">副标题1-可以与目录的文字不一样</h4>
<h4 id="1.2">副标题2-只要id与目录括号里面的数字相同即可</h4>
<h4 id="1.3">副标题3</h4>
```
生成效果

* [主标题](#1)  
  * [副标题1](#1.1)  
  * [副标题2](#1.2)  
  * [副标题3](#1.3)

<h2 id="1">主标题</h2>
<h3 id="1.1">副标题1-可以与目录的文字不一样</h3>
<h3 id="1.2">副标题2-只要id与目录括号里面的数字相同即可</h3>
<h3 id="1.3">副标题3</h3>


<h5>副标题1-可以与目录的文字不一样</h5>


## [标题]

标题有两种，一种是“有等级标题”，另外一种是“无等级标题” 

### 无等级标题 
|    样例    |   输出  | 
| :-----:  | :------:| 
|  大标题  <br> ==== |  |
|   中标题 <br> ----  |   |


### 有等级标题
|    样例    |   输出  | 
| :-----:  | :------:| 
|   #一级标题  |    |
|  ##二级标题   |    |
| ###三级标题  |   |
| ####四级标题   |   |
| #####五级标题    |   |
| ######六级标题    |   |

----
## 文本
### 常用
|    样例    |   输出  | 
| :-------:  | :--------:| 
| \*\*加粗** | **加粗**  | 
| \*斜体*    | *斜体* | 
| \`高亮\`  |  `高亮` |
|  |  |

### 缩进
```
* 编程语言
    * 脚本语言
    这儿有一些文字
        * Python  
>编程语言  
>>脚本语言  
>>>Python
```
效果   
* 编程语言  
    * 脚本语言  
    这儿有一些文字
        * Python 
>编程语言  
>>脚本语言  
>>>Python

### 分割线
用至少三个以上的减号 -
```
分割线  
----- 
```

### [首行缩进]

全方大的空白\&emsp;或\&#8195;是等价写法；  
半方大的空白\&ensp;或\&#8194;是等价写法；  
不断行的空白\&nbsp;或\&#160;是等价写法；  

```
&emsp;&emsp;进行了首行缩进  
&ensp;&ensp;&ensp;&ensp;进行了首行缩进  
```
呈现效果  

&emsp;&emsp;进行了首行缩进   
&ensp;&ensp;&ensp;&ensp;进行了首行缩进   

### 换行

在最后一行添加

----

## 其他



### 链接

#### 
`[我的主页](https://github.com/yqx7150/)`   
呈现效果   
[我的主页](https://github.com/yqx7150/)

>* 注意：如果想链接到其他网页，不要忘了添加`https://`,如果不添加的话，GitHub会基于当前页面进行跳转。

### GitHub仓库里的图片
使用markdown语法：[点击跳转](#jump)



定义一个锚(id)：<span id="jump">跳转到的地方</span>






### [锚点]
字母要统统小写，空格统统要替换成 '-'  
URL 不区分大小写   

- [What's included](#whats-included)
- [Quick start](#quick-start)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [License](#license)
- [HTML 部分](#html-部分)

[What's included]
dsfw vc

[锚点]:https://www.jianshu.com/p/baa5aaab4018
[标题]:https://www.jianshu.com/p/63ff519e90e4
[首行缩进]:https://blog.csdn.net/thither_shore/article/details/52205748
