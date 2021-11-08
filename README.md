# README.learningnotes.maekdown
GitHub上的README.md的编辑的学习笔记。

README（自述文件）文件的后缀名为md(markdown)，markdown是一种编程式的博客编辑方案，区别于CSDN的可视化的博客编辑器，可能入门比较困难。不过能够来G站扒代码的人估计或多或少都能懂一点编程。GitHub支持的MD语法在标准的markdown语法的基础上做了一些修改，称为GitHub Flavored Markdown（GFM）。

## 标题
<br>

### 大，中标题与横线

<br>
关于在MD中添加标题可以使用连续等于号“===”与连续减号“---”来实现。
如果想要添加一个大标题，就只需要在文本下方加上等于号，等于号的个数可以随便但是一定要大于0。<br>

![](https://github.com/CalacalaBoom/README.learningnotes.maekdown/blob/5b4e575676a1ef9de4bcc7aebf84acdcda5cb24e/png/1.png)

<br>
效果如下：
<br>

大标题
===
<br>
同样的，在文本的下方加上减号，就可以添加中标题的效果，对于减号的数量同样没有限制。

![](https://github.com/CalacalaBoom/README.learningnotes.maekdown/blob/5b4e575676a1ef9de4bcc7aebf84acdcda5cb24e/png/2.png)

效果如下：
<br>

中标题
---
<br>
可以发现的是在大标题和中标题之间有一条横线，这就是使用了等于号和减号的标志。而想要不为文本添加标题效果而只显示这条线，就只需要在文本与减号之间补一个空行。用人话讲就是按一个回车空一行。需要注意的是这种用法存在减号的数量限制，必须要使用三个减号以上。可以使用星号“***”和下划线“___”来代替减号（我等于号哭晕在厕所）

![](https://github.com/CalacalaBoom/README.learningnotes.maekdown/blob/5b4e575676a1ef9de4bcc7aebf84acdcda5cb24e/png/3.png)

效果如下：
<br>
<br>
EDG牛逼！！！

---
<br>
补空行：是很常用的用法，当你不想上下两个不同的布局方式交错到一起的时候，就要在两种布局之间补一个空行。
<br>

### 等级表示法

<br>
此外还可以使用等级表示法来表示标题（有那么好的东西我为什么要用等于号？）。等级表示法把标题分为六个等级，文本大小依次递减。使用井号来区分“#”等级，一级标题在文本之前加一个井号，二级标题有两个，以此类推。

![](https://github.com/CalacalaBoom/README.learningnotes.maekdown/blob/5b4e575676a1ef9de4bcc7aebf84acdcda5cb24e/png/4.png)

效果如下：
<br>

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

<br>
一级标题等于大标题，二级标题等于中标题。这里需要注意的是在井号与文本之间有一个空格。
<br>

## 文本

<br>

### 普通文本

<br>

在编辑器中直接输入的文字就是普通文本，普通文本是不支持换行的，想要换行可以使用\<br>标签。\<br>是html中的标签，事实上markdown是支持html标签的，但是没有人愿意用html标签来写README.md，至于为什么我不知道，或许可以发个朋友圈问问。<br>
如果想要显示\<br>怎么办，这里就引入了转义，通过在\<br>的前边加上反斜杠"\\"就可以实现转义。同理所有的编辑标记都可以通过转义来显示出来。<br>
效果就像上边这两句话。而在编辑器里边它是这样的:

![](https://github.com/CalacalaBoom/README.learningnotes.maekdown/blob/5b4e575676a1ef9de4bcc7aebf84acdcda5cb24e/png/5.PNG)












