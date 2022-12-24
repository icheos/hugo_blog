+++
title = "教你用 hugo + org-mode 创建博客"
lastmod = 2022-12-24T12:33:03+08:00
draft = true
author = "icheos"
+++

使用本篇博客的前提是会 org-mode 的基础语法，如果不太清楚可以看我后期写的 org-mode 操作，或者直接使用更加方便的 markdown

视频可以参考:[21天学会Emacs：第11天使用org mode写博客](https://www.bilibili.com/video/BV1ZR4y1X7D7/?spm_id_from=333.999.0.0)

文字版推荐另一位的安装[教程](https://blog.jiayuanzhang.com/post/blog-with-ox-hugo/)

我在本篇文档主要结合上面的内容，额外补充一点东西


## 安装 hugo {#安装-hugo}

我的系统是 arch linux,在 arch 只需要 `sudo pacman -S hugo` 就能安装 hugo


## emacs 环境配置 {#emacs-环境配置}

关于插件的安装可以参考后续[doomemacs学习记录](<doomemacs 学习记录.md>)

我用的是 doomemacs, doomemacs 用户可以看 ox-hugo 上的[官方文档](https://ox-hugo.scripter.co),
