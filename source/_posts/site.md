---
title: 小白部署 Hexo 极简教程
tags: [github,hexo,vercel,netify,教程]
index_img: https://www.hawksworx.com/images/netlify-banner.png
banner_img: https://cdn.sanity.io/images/o180qdl3/production/5b48a59c547c52931f22cd845a02ba8e46df76bc-1920x1080.png?w=1200&h=675&fit=crop&auto=format
date: 2022-10-27 21:00:00
---

# 前言
- 此次教程为本人累积经验而来，请勿转载！
- 此次教程无需任何除浏览器以外的软件！
- 此次教程搭建的博客可通过vercel或netlify所访问（github需要特殊仓库也可访问）。
- 有问题？我在结尾会回答！


# 简单流程
- 创建Github账户；
- 创建vercel账户；
- 创建netlify账户；
- 在vercel一键部署Hexo（jykell、hugo等都可以）；
- 在netlify链接；

# 详细教程

## 一、创建github账户
- 这简单，直接前往[github](github.com)创建个人账户即可，QQ邮箱也行。

## 二、创建vercel账户
- 首先，前往[vercel](vercel.com)，直接绑定你的github账户即可；
- 然后，会来到一个欢迎界面，里面会有一个黑色的github按钮，直接点github；
- 接着，会要求你选一个仓库，直接点右下角Browse All Templates；
- 找到hexo，你可以选择别的博客系统；
- 选择后会继续选择github选项，这里后面会让你填写仓库名称，你自己取一个就行，也可以是比如我是xiaoji235，我直接创建一个 xiaoji235.github.io 的仓库，这样不仅vercel和netlify提供的链接可以访问你的博客，搭建完成后在浏览器上输入比如 xiaoji235.github.io 也可以访问！
- 由于vercel创建的博客在国内无法访问，这里需要netlify继续
- 进入[netlify](app.netlify.com)，还是用github登陆，进去后也是会停在欢迎界面，还是找到github那一项，点进去，会提示你链接github仓库，直接链接你刚创建的github仓库；
- 链接完成后即可使用的的博客了。

# 问题回答
- Q：为啥有vercel了还要什么netlify？
 - A：因为vercel只有面板能在国内访问，但就是你创建的博客访问不了（可能是vercel.app被墙了），你也可以给你的博客用自的域名！
- Q：为啥不直接用netlify创建呢？
 - A：我也想啊，但是自己fork github里面的博客系统老是出问题，而且没有hexo博客系统（别问我为什么只用hexo，因为我看中了hexo的一款主题），如果你使用别的博客系统，你可以直接跳过vercel用netlify。
- Q：你有 了，为什么不直接用你创建的 xiaoji235.github.io  ？
 -　A：访问太慢！
- Q：你的封面为什么只用netlify的图片？
 - A：要你管？哼！

# 结尾
如果还有什么问题请前往[github我的issue](https://github.com/xiaoji235)内提出（随便哪个项目的issue）。
