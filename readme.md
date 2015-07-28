This is an H1
=============

This is an H2
-------------

*************



# #这是H1

## ##这是H2

### ###这是H3


Markdown 也允许你偷懒只在整个段落的第一行最前面加上 > ：
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.




区块引用可以嵌套（例如：引用内的引用），只要根据层次加上不同数量的 > ：
> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.


引用的区块内也可以使用其他的 Markdown 语法，包括标题、列表、代码区块等：
> ## 这是一个标题。
> 
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");


# 列表
## Markdown 支持有序列表和无序列表。
无序列表使用星号、加号或是减号作为列表标记：
*   Red
*   Green
*   Blue

等同于：

+   Red
+   Green
+   Blue

也等同于：

-   Red
-   Green
-   Blue


有序列表则使用数字接着一个英文句点：
1.  Bird
2.  McHale
3.  Parish


列表项目标记通常是放在最左边，但是其实也可以缩进，最多 3 个空格，项目标记后面则一定要接着至少一个空格或制表符。
要让列表看起来更漂亮，你可以把内容用固定的缩进整理好：
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
	viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
	Suspendisse id sem consectetuer libero luctus adipiscing.


如果列表项目间用空行分开，在输出 HTML 时 Markdown 就会将项目内容用 <p> 标签包起来，举例来说：
*   Bird
*   Magic
会被转换为：
<ul>
<li>Bird</li>
<li>Magic</li>
</ul>

但是这个：
*   Bird

*   Magic
会被转换为：
<ul>
<li><p>Bird</p></li>
<li><p>Magic</p></li>
</ul>


# link链接
链接内容定义的形式为：
方括号（前面可以选择性地加上至多三个空格来缩进），里面输入链接文字
接着一个冒号
接着一个以上的空格或制表符
接着链接的网址
选择性地接着 title 内容，可以用单引号、双引号或是括弧包着

下面这三种链接的定义都是相同：
+ 1. [PHPXUN.COM](http://phpxun.com/)  "This is my blog home page"
+ 2. [JIANXUNS.COM](http://jianxuns.com/)  'This is my worldpress'

*****************

强调
====

Markdown 使用星号（*）和底线（_）作为标记强调字词的符号，被 * 或 _ 包围的字词会被转成用 <em> 标签包围，用两个 * 或 _ 包起来的话，则会被转成 <strong>，例如：

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__


图片
====

# 我的头像  My Phontos

![我的头像](resource/dog.jpg)   




  

















