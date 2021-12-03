# A Study Note about Markdown

## 0. 写在前面

这篇关于Markdown的学习笔记是由本人（CloudyZhao）撰写，之后会继续完善直至完结。建立此公共仓库和文件的主要目的是记录与分享关于Markdown的学习。如有问题可在issues中指出，本人在此表示衷心的感谢。

The unfinished tutorial is written by CloudyZhao, and will continue to be updated until the end. The study note about Markdown is made public in this repository to facilitate sharing and discussion with others. Please point out any errors in issues, and I would like to express my heartfelt thanks.

```
目录
1. 标题
2. 提醒文字
3. 变量
4. 图像
5. 链接
```

## 1. 标题
标题可以有两种方式来定义，具体方式如下：

### 1.1 使用符号```#```来定义


**【推荐用法】** Markdown中一共可以定义1~6级标题，使用符号```#```来定义。

#### 1.1.1 示例代码

```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

#### 1.1.2 实现效果

> # 一级标题
> ## 二级标题
> ### 三级标题
> #### 四级标题
> ##### 五级标题
> ###### 六级标题


2.
斜体文字用一对星号或者一对下划线包围表示
表达式：
`* 斜体文字 *  or  _ 斜体文字 _`
示例：
`*这行文本是斜体*`
`_这行文本是斜体_`

3.
粗体文字用两对星号或者两对下划线包围表示
表达式：** 斜体文字 **  or  __ 斜体文字 __
示例：
这行文本是**粗体**
__这行文本是粗体__
这行文本是**粗体**+ *斜体*
***这行文本是 粗体 + 斜体***

4.
标记文字用两对等号包围表示
表达式：== 斜体文字 ==
示例：
==*这行文本是标记斜体*==
==***这行文本是标记+加粗+斜体***==

5.
删除线文字用两对波浪号包围表示
表达式：~~ 斜体文字 ~~
示例：
~~*这行文本是删除线标记斜体*~~
==~~***这行文本是删除线+标记+加粗+斜体***~~==

6.
引用文字用两对波浪号包围表示
表达式：~~ 斜体文字 ~~
示例：
~~*这行文本是删除线标记斜体*~~
==~~***这行文本是删除线+标记+加粗+斜体***~~==


~~_这行文本是 **粗体** + 斜体_ + 删除线~~

[Markdown指南]: https://markdown.budshome.com

引用链接：

key引用：[Markdown指南]

value引用：[未定义文本][Markdown指南]

$$
a \ b \\
a \quad b \\
a \qquad b \\
\mathit{a} + \mathbf{b} \\
X^{2m}_{3n} \\
\text{注意和下面默认大小对比——} \\
\tiny X^{2m}_{3n} \\
\scriptsize X^{2m}_{3n} \\
\small X^{2m}_{3n} \\
\normalsize X^{2m}_{3n} \text{（默认大小）} \\
\large X^{2m}_{3n}  \\
\Large X^{2m}_{3n}  \\
\huge X^{2m}_{3n}  \\
\Huge X^{2m}_{3n}  \\
$$
