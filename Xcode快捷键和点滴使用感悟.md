﻿# Xcode快捷键和点滴使用感悟

标签（空格分隔）： iOS xcode

---

# Xcode常用的快捷键
刚入职六个月，从Android转到iOS开发，熟悉了Xcode的基本使用，在此记录一下所用到的基本快捷键和一些实用技巧，也强烈欢迎各位有更好的，更加快捷的Xcode使用技巧，一起分享。
当然，在使用Xcode的时候，免不了会用到一些Mac的快捷键。
## Mac常用快捷键
1. 修改文件或文件夹的名称-----Enter
2. 复制粘贴命令不必多说。注意在Mac下面，Command+X是没有剪切文件，文件夹的功能的。
3. Command+Tab--不同应用程序之间的切换。
4. Command+Space--输入法切换，建议下载其他输入法。
5. Command+Shift+Esc--快速打开任务管理器，强制关闭应用。
6. 在Finder打开情况下，通过绝对路径访问文件夹，这种方式还可以访问隐藏的文件夹。
7. Command+Q--退出当前应用程序。
8. Command++W--关闭当前应用程序（或者该应用某个页面，如浏览器）。
9. Command+Shift+N，在Finder打开的情况下，新建文件夹。
10. Command+Delete--删除文件和文件夹（与Win有差异）

### 浏览器上常用的快捷键
1. Command+N--在新的窗口打开浏览器。
2. Command+T--打开一个新的浏览器标签
3. Command+L--打开浏览器的情况下，快速定位到地址栏。
4. Command+鼠标点击超链接，在新窗口打开网页。

### 截屏快捷键
1. Command+Shift+3（4）————对整个屏幕（固定区域）截屏，保存在桌面。
2. Command+Ctrl+Shift+3（4）————对整个屏幕截屏，图片保存在剪切版中。

## Xcode快捷键
###左侧菜单的快捷键
上面共有8个可选菜单，分别用Command+1～8可以打开，常用的有1，3，4，7，分别对应目录，全局搜索关键字，查看警告和错误，查看所有断点。最常用的就是1，可以通过快捷键Command+Shift＋J快速定位到当前所在编辑的文件。

* Command+N--新建文件
* Command+Shift+N--新建一个项目
* Command+B——编译代码。写了一段代码后，可以先编译看看有没有错误。编译－链接－生成目标文件
* Command+R——运行项目
* Command+.——中断项目的运行。
* Esc——代码的提示与补全，或者有代码提示不想用的时候，按此键解除。
* Command+／——接触代码注释
* Command+<-,->——光标跳转到本行代码最前面，最后面。
* Alt+<-,->——光标向前（后）跳转一个单词。
* Command+Shift+<-,->——选中光标（后）前的所有代码。
* Command+上下箭头————光标定位到最上（下）面
* Shift+上下箭头————选中上面的一行代码，多个选择多行。
* Command+Shift＋K————清理项目，多次编译，运行后需要。
* Command+K————清理Console的内容，打印变量是需要
* Command+Shift+F————类似于Command+3的效果，更加方便。
* Command+0————隐藏左侧的菜单栏，查看代码有同。
* Command+L————输入行数，定位到该行。改代码有用。
* Command+Control+左右箭头————显示前后文件的内容。
* Command+Control+上下箭头————进行.h和.m文件的切换，非常有用。
* Command+Z————撤销，Command+Shift+Z————反撤销。