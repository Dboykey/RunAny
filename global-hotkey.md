#### **【全局热键】**

在别名最末尾添加<kbd>Tab</kbd>制表符+热键

> 热键格式参考AHK写法:
`^`代表<kbd>Ctrl</kbd> 
`!`代表<kbd>Alt</kbd> 
`#`代表<kbd>Win</kbd>
`+`代表<kbd>Shift</kbd>

1. 按 <kbd>Alt</kbd>+<kbd>b</kbd> 一键百度、谷歌
2. 按 <kbd>Win</kbd>+<kbd>z</kbd>一键翻译选中文字
3. 按 <kbd>Alt</kbd>+<kbd>z</kbd>启动或激活浏览器

<PRE>
百度 (&B)&#9!b|https://www.baidu.com/s?wd=
谷歌 (&G)&#9!g|http://www.google.com/search?q=%s&gws_rd=ssl
翻译 (&F)&#9#z|http://translate.google.cn/#auto/zh-CN/
浏览器(&Z)&#9!z|chrome.exe
</PRE>

> 搜索网址的关键字，如果在中间而不是在末尾，用%s表示，默认不加就是加在末尾来搜索
> - 在选中文字的情况下按全局热键，可以直接用搜索网址搜索选中文字~
> - 在选中文件情况下按全局热键，就可以直接用该热键的应用打开该文件；

**所有exe程序设置独立全局热键后有三种功能：**
1. 启动、最小化时激活
2. 已激活时最小化
3. 同个exe程序多窗口切换功能于一体

![RunAny新增修改菜单项](/assets/images/RunAny新增修改菜单项.jpg)

?> [手动写RunAny.ini可以了解更多AHK热键写法文档](https://wyagd001.github.io/zh-cn/docs/Hotkeys.htm)