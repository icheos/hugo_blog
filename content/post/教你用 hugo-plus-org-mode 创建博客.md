+++
title = "教你用 hugo + org-mode 创建博客"
lastmod = 2022-12-24T15:20:21+08:00
author = "icheos"
+++

上期内容:[用hugo写博客](/post/用-hugo-写博客/)

本篇博客的前提是会 org-mode 的基础语法，如果不太清楚可以看我后期写的
[org-mode使用指南](https://icheos.github.io/hugo_blog/post/org-mode-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97/) 或者直接使用更加方便的 markdown

视频可以参考:[21天学会Emacs：第11天使用org mode写博客](https://www.bilibili.com/video/BV1ZR4y1X7D7/?spm_id_from=333.999.0.0),文字版推荐另一位的安装[教程](https://blog.jiayuanzhang.com/post/blog-with-ox-hugo/)

详细内容请看[官方文档](https://ox-hugo.scripter.co/doc/usage/)

我在本篇文档主要结合上面的内容，额外补充一点东西

---


## emacs 环境配置 {#emacs-环境配置}

关于插件的安装可以参考后续[doomemacs学习记录](/post/doomemacs-学习记录/)

我用的是 doomemacs, 非 doomemacs 用户可以看 ox-hugo 上的[官方文档](https://ox-hugo.scripter.co),


## 安装 hugo {#安装-hugo}

我的系统是 arch linux,在 arch 只需要 `sudo pacman -S hugo` 就能安装 hugo


## hugo 博客模板 {#hugo-博客模板}

使用 `org-capture` 命令或 `SPC-X` (看你的配置)找到

{{< figure src="/img/screenshots_1.png" >}}

然后就可以快乐的写博客了


## 我认为好用的快捷键 {#我认为好用的快捷键}

`C-x n s`:显示当前子标题内容,这个命令能让我们可以和其他博客分开编写，就像在新的文件里写文章一样

`C-x h w`:当前文件全部内容,和上面命令结合能很好的对文件进行布局，也不用担心不小心写到别的博客上去
