---
layout:     post
title:      IntelliJ IDEA快捷键大全
subtitle:   Java开发工具
date:       2019-05-24
author:     Blue Demon
header-img: img/post-bg-swift.jpg
catalog: true
tags:
    - Java
---


> 本文首次发布于 [Blue Demon Blog](http://yuquanfeng.github.io), 作者 [@蓝魔(Blue Demon)](http://github.com/yuquanfeng) ,转载请保留原文链接.

## IntelliJ IDEA介绍

作为一个java开发基本上都有自己用的顺手的Java开发工具，有些公司用的是eclipse、有些公司用的是myeclipse、有些公司用的是IntellJ IDEA。以前我是用eclipse开发的，后来改用了idea，慢慢的发现idea功能真的很强大。idea里面集成了maven的可视化界面，以及databases等可视化界面，还有终端控制台，集成了git可视化界面，可以实现不用Git命令提交代码，只需点几个按键就可以实现代码的提交，给开发带来了很大的方便。

## IntelliJ IDEA快捷键介绍

### 1编辑【Editing】

|快捷键|英文说明|中文说明|
|  -----------       |    -----------    |   -------------   |
|Ctrl+Space          |Basic code completion (the name of any class, method or variable)             |补全代码，由于经常与操作系统的输入法的切换冲突，所以实际很少用。一般直接在 idea 中开启输入自动补全机制|
|Ctrl + Shift + Space|Smart code completion (filters the list of methods and variables by expected type|在列出的可选项中只显示出你所输入的关键字最相关的信息。（常用）|
|Ctrl + Shift + Enter|Complete statement|代码补全后，自动在代码末尾添加分号结束符|
|Ctrl + P|Parameter info (within method call arguments)|在某个方法中，调用该按键后，会展示出这个方法的调用参数列表信息。|
|Ctrl + Q|Quick documentation lookup|展示某个类或者方法的 API 说明文档|
|Ctrl + mouse(鼠标左键）|over code Brief Info|跳进到某个类或者方法源代码中进行查看。（常用）|
|Alt + Insert|Generate code… (Getters, Setters, Constructors, hashCode/equals, toString)|自动生成某个类的 Getters, Setters, Constructors, hashCode/equals, toString 等代码。（常用）|
|Ctrl + O|Override methods|重写方法|
|Ctrl + Alt + T|Surround with… (if..else,try..catch, for, synchronized, etc.)|自动生成具有环绕性质的代码，比如：if..else,try..catch, for, synchronized 等等，使用前要先选择好需要环绕的代码块。（常用）|
|Ctrl + /|	Comment/uncomment with line comment|对单行代码，添加或删除注释。分为两种情况：如果只是光标停留在某行，那么连续使用该快捷键，会不断注释掉下一行的代码；如果选定了某行代码（选定了某行代码一部分也算这种情况），那么连续使用该快捷键，会在添加或删除该行注释之间来回切换。（常用）|
|Ctrl + Shift + /|Comment/uncomment with block comment|对代码块，添加或删除注释。它与 Ctrl + / 的区别是，它只会在代码块的开头与结尾添加注释符号！（常用）|
|Ctrl + W|Select successively increasing code blocks|	选中当前光标所在的代码块，多次触发，代码块会逐级变大。（常用）|
|Ctrl + Shift + W|Decrease current selection to previous state|是 Ctrl + W 的反向操作，多次触发，代码块会逐级变小，最小变为光标。|
|Alt + Q|Context info|展示包含当前光标所在代码的父节点信息，比如在 java 方法中调用，就会展示方法签名信息。|
|Alt + Enter|Show intention actions and quick-fixes|展示当前当前光标所在代码，可以变化的扩展操作|
|Ctrl + Alt + L|Reformat code|格式化代码 （常用）|
|Ctrl + Alt + O|Optimize imports|去除没有实际用到的包，这在 java 类中特别有用。（常用）|
|Ctrl + Alt + I|Auto-indent line(s)|按照缩进的设定，自动缩进所选择的代码段。|
|Tab / Shift + Tab|Indent/unindent selected lines|缩进或者不缩进一次所选择的代码段。（常用）|
|Ctrl + X 或 Shift Delete|Cut current line or selected block to clipboard|剪切当前代码。 （常用）|
|Ctrl + C 或 Ctrl + Insert|Copy current line or selected block to clipboard|拷贝当前代码。 （常用）|
|Ctrl + V 或 Shift + Insert|Paste from clipboard|粘贴之前剪切或拷贝的代码。（常用）|
|Ctrl + Shift + V|Paste from recent buffers…|从之前的剪切或拷贝的代码历史记录中，选择现在需要粘贴的内容。（常用）|
|Ctrl + D|	Duplicate current line or selected block|复制当前选中的代码。（常用）|
|Ctrl + Y|Delete line at caret|删除当前光标所在的代码行。（常用）|
|Ctrl + Shift + J|Smart line join|把下一行的代码接续到当前的代码行。|
|Ctrl + Enter|	Smart line split|当前代码行与下一行代码之间插入一个空行，原来所在的光标不变。（常用）|
|Shift + Enter|Start new line|当前代码行与下一行代码之间插入一个空行，原来光标现在处于新加的空行上。（常用）|
|Ctrl + Shift + U|Toggle case for word at caret or selected block|所选择的内容进行大小写转换。。（常用）|
|Ctrl + Shift + ]/[|Select till code block end/start|从当前光标所在位置开始，一直选择到当前光标所在代码段起始或者结束位置。|
|Ctrl + Delete|Delete to word end|删除从当前光标所在位置开始，直到这个单词的结尾的内容。|
|Ctrl + NumPad(+/-)|Expand/collapse code block|展开或收缩代码段。 （常用）|
|Ctrl + Shift + NumPad(+)|Expand all|展开所有代码段。
|Ctrl + Shift + NumPad(-)|Collapse all|收缩所有代码段。
|Ctrl + F4|Close active editor tab|关闭当前标签页。
|Shift + F6|            |修改名字。（常用）