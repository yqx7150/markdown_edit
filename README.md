# markdown_edit

针对GitHub上`.md`格式的用法

表格1
```
|表头1| 表头2|表头3|
|:-- | :----:  | ---:|
|左对齐| 居中 |右对齐|
|两边的`\|`线可以不要 | |
```
|表头1| 表头2|表头3|
|:-- | :--:  | --:|
|左对齐| 居中 |右对齐|
|两边的`\|`线可以不要 | |

> 注意
>>* 源码里面的`-`线至少要两个
>>* 控制左右对齐的`:`以及控制表头的`-`线中间不能有空格




>* 待完善...     

a<sub>n</sub>   
a<sup>n</sup>   
<u>x+y</u>   
<span style="text-decoration:overline;">a</span>   
√<span style="text-decoration:overline;">5</span>   

\begin {pmatrix}
12& 32&\\
12& 42
 \end{pmatrix}


$ <x^2> $  

$ <x^2>      


作者    | 联系方式
:---: | :---:
杨青新| yqx7150@163.com


>akdsjf;;
>



这是长和宽均为50的  
<div align=center><img width="50" height="50" src="https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg"/></div>
这是长和宽均为100的  
<div align=center><img width="100" height="100" src="https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg"/></div>
这是长和宽均为150的  
<div align=center><img width="150" height="150" src="https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg"/></div>  
这是不加宽度信息的  
<div align=center><img src="https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg"/></div>  

https://github.com/HeTingwei/ReadmeLearn 

<table><tr><td bgcolor=red>这里的背景色是：red</td></tr></table>

<tr><td bgcolor="red">这里的背景色是：red</td></tr>

<div align=center><img width="150" height="150" src="https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg"/></div>      



----

<table>
<tr>                                       #<tr></tr>的个数为：行数
    <td rowspan="7"> 合并多行成一列：<br/>  #<td></td>的个数为：列数
        使用rowspan="n" <br/>
        跨 n 行合并<br/>
        </td>
    <td>文件标识：</td>
    <td>内容</td>
</tr>
<tr>
    <td>第一行：</td>
    <td>该写什么呢？</td>
</tr>
<tr>
    <td>第二行：</td>
    <td>随便写吧！</td>
</tr>
<tr>
    <td>第三行：</td>
    <td>OK了！</td>
</tr>
</table>

<font color='green'>文本六</font> 

<table>
   <tr>
      <td>第一列</td>
      <td>第二列</td>
      <td>第三列</td>
   </tr>
   <tr>
      <td>合并第1，2列</td>
      <td>    第2行，第3列</td>
   </tr>
   <tr>
      <td>合并第1，2列</td>
      <td>       第3行，第3列</td>
   </tr>
</table>

<table>
    <tr>
        <th rowspan="2">值班人员</th>
        <th>星期一</th>
        <th>星期二</th>
        <th>星期三</th>
    </tr>
    <tr>
        <td>李强</td>
        <td>张明</td>
        <td>王平</td>
    </tr>
</table>

<table>
    <tr>
        <td bgcolor=#FF69B4>第一列</td> 
        <td>第二列</td>
        <td>第三列</td> 
   </tr>
    <tr>
        <td colspan="2"bgcolor=#7B68EE>合并第1，2列</td>
        <td>第2行，第3列</td    
    </tr>
    <tr>
        <td colspan="2" bgcolor=#ADFF2F>合并第1，2列</td>
        <td>第3行，第3列</td    
    </tr>
</table>

----
## 文本
### 常用
|    语法    |   效果  | 
| :-------:  | :--------:| 
| `**加粗**` | **加粗**  | 
| `*斜体*`    | *斜体* | 
| `~~删除线~~` | ~~删除线~~ | 
|  加粗且斜体 | ***立刻就会*** | 
|  `a<sub>n</sub>` |a<sub>n</sub> |
|`a<sup>2</sup>` |a<sup>2</sup>  | 
|   |  | 

### 列表
```
* 编程语言
    * 脚本语言
    这儿有一些文字
        * Python  
>编程语言  
>>脚本语言  
>>>Python

1. 标题1   
  1.1 标题1.1  
  1.2 标题1.1   
2. 标题2

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

C[^1]           
[^1]:https://github.com/yqx7150/

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

## 表格

|表头1| 表头2|表头3|
|:-- | : --:  | --:|
|左对齐| 居中 |右对齐 


## 代码

### 行内标记



```
文本 `标记或简短代码` 文本

```
文本 `标记或简短代码` 文本


### 代码块


\```  
这是代码块   
\```  

效果如下：
```
这是代码块
```

#### [代码语法高亮](https://github.com/github/linguist/blob/master/vendor/README.md)


```matlab
%% 这是备注
for i = 1:10
   disp(i);
end
```

```MATLAB
%% 不区分大小写
for i = 1:10 % 这是matlab的备注
   disp(i); 
end
```

```java
// 不区分大小写
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World"); // 这是java的备注
    }
}
```
```JAVA
// 这是备注
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

```python
import numpy as np #python
def foo():
    X = np.zeros(2)

```



<pre><code>这是一个代码区块。

</code></pre>  

(https://github.com/github/linguist/blob/master/vendor/README.md)

----

## [标题]

标题有两种，一种是“有等级标题”，另外一种是“无等级标题” 

### 无等级标题 
|    语法    |   效果  | 
| :-----:  | :------:| 
|  大标题  <br> ==== |  |
|   中标题 <br> ----  |   |


### 有等级标题
|    语法    |   效果  | 
| :-----:  | :------:| 
|   #一级标题  |    |
|  ##二级标题   |    |
| ###三级标题  |   |
| ####四级标题   |   |
| #####五级标题    |   |
| ######六级标题    |   |



## 链接

###
`[我的主页](https://github.com/yqx7150/)`   

呈现效果   

[我的主页](https://github.com/yqx7150/)

>* 注意：如果想链接到其他网页，不要忘了添加`https://`,如果不添加的话，GitHub会基于当前页面进行跳转。

### 图片
和超链接的语法非常相似。 

>* 只显示图片：
  >* 相对路径： `![github](/figs/github.bmp “GitHub_logo”)`
  ![github](/figs/github.bmp “GitHub_logo”)
  >* 绝对路径：`![baidu](https://www.baidu.com/ “百度logo”)`![baidu](https://www.baidu.com/ “百度logo”)
>* 点击图片进入另一个网页：`[![github]](https://github.com) ![github](/figs/github.bmp “跳转到github主页”)`[![github]](https://github.com) ![github](/figs/github.bmp “跳转到github主页”)

<div align=center><img width="150" height="150" src="https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg"/></div>



#### 给图片加上超链接
[![baidu]](http://baidu.com)  
[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo" 

### 视频[](https://gitlab.com/gitlab-org/gitlab-ce/blob/master/doc/user/markdown.md)
有效的视频扩展是`.mp4`，`.m4v`，`.mov`，`.webm`，和`.ogv`。
```
Here's a sample video:

![Sample Video](figs/markdown_video.mp4)
```
Here's a sample video:

![Sample Video](figs/markdown_video.mp4)

### 生成目录
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




### 页间跳转（锚点链接）
#### 方式一
 
#### 方式二
 
 >* 
<a name="我想跳到这个地方1">W3School</a>

<a id="我想跳到这个地方2">W3dddddddchool</a>


<a name="我想跳到这个地方1">W3School</a>

<a id="这是文章首段 ">W3dddddddchool</a>


[跳转到文档首段](#我想跳到这个地方1)

<img src="https://github.com/HeTingwei/ReadmeLearn/blob/master/avatar1.jpg" width="150" height="150" alt="图片加载失败时，显示这段字"/>

### 插入公式

>* 转为图片，然后插入图片
>* chrome插件[GitHub with MathJax](https://chrome.google.com/webstore/detail/github-with-mathjax/ioemnmodlmafdkllaclgeombjnmnbima)
>* 在文章中添加 `<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>`。但是GitHub 不能用，因为它的Markdown不支持mathjax的公式渲染。

### [锚点]
字母要统统小写，空格统统要替换成 '-'  
URL 不区分大小写   

[点击我跳转](#我想跳到这个地方1)
[点击我跳转](#我想跳到这个地方2)

- [What's included](#whats-included)
- [Quick start](#quick-start)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [License](#license)
- [HTML 部分](#html-部分)

[锚点]:https://www.jianshu.com/p/baa5aaab4018
[标题]:https://www.jianshu.com/p/63ff519e90e4
[首行缩进]:https://blog.csdn.net/thither_shore/article/details/52205748
