---
title: vivo主题修改文字教程
tags: [vivo,主题,教程]
index_img: https://dl2.img.timecdn.cn/2022/10/28/termux.png
banner_img: https://b.zhutix.com/bizhi/iWin/02.png
date: 2022-10-27 21:00:00
---
# 前言
- vivo制作主题时，除了可以修改图片外，还可以通过主题包修改显示的字体！教程适用于funtouch os，origin未知
<!-- more -->
# 正文
- 首先，mt打开apk文件的arsc文件，就标准版编辑器就OK
![arsc编辑器](https://i0.hdslb.com/bfs/article/00d168a80d549236801a86c2ca885fd47c17900b.jpg)
- 接着点进最下面那一栏（一串英文），里面有个叫做string的，点进去，不出所料的话里面你就看到了各个国家的语言包，我们主要看string-zh-rCN不同国家不同选择（方法全球通用）。
![zh-cn](https://i0.hdslb.com/bfs/article/ac46e85413aafd37527b319b6e95e8e56baa65ec.jpg)
- 找到你需要改动的文字如果找不到就去app里面看看语句，直接搜关键词，一般搜的到，（别搜动态语句，比如百分比面的数字）。找到后点进去复制标题（点一下就ok）
![点击标题复制标题内容](https://i0.hdslb.com/bfs/article/c596a2231f57b02df4909a736fdc9659a4eed097.jpg)
- 接着，打开主题包，创建一个theme_values.xml文件，输入以下内容（注意，保存为UTF-8格式的文件编码）

```copy
<?xml version-"1.0" encoding-"utf-8"standalone="no"?>
<vivo_theme_values>
<string name-"粘贴你复制的标题名字">填写你想要的文字</string>
</vivo_theme_values>
```

- 保存退出压缩xml文件，压缩包名称不带zip后缀，包名为app包名（如图，点击app高亮部分复制包名）
![点击包名复制](https://i0.hdslb.com/bfs/article/2f42f40c17de9fa5121a10920874d038477ae9e3.jpg)
- 最后导入主题包应用即可。

# 附加
此次教程同样可以修改文本颜色（16进制），代码保存在一个xml文件内，以下是代码架构：

```copy
<?xml version-"1.0" encoding-"utf-8"standalone="no"?>
<vivo_theme_values>
<color name-"粘贴你复制的标题名字">填写你想要的颜色（16进制）</string>
</vivo_theme_values>
```

# 警告
博客内的所有教程仅限用于学习和研究目的；不得将上述内容用于商业或者非法用途，否则，一切后果自负。