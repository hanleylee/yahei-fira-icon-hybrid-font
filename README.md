# Yahei-Consolas-Icon-Hybrid-Font

本字体适用于 Vim 及终端图标的中英文混合字体.

做这套字体的原因是因为需要在终端使用 [lsd](https://github.com/Peltoche/lsd) 插件, 但是这个插件是基于NerdFont 图标字体, 不支持中文.

考虑到国人在终端中还是有显示中文字体的需求的, 因此有了这套字体. 字体在终端以及 Vim 的显示效果如下:

![himg](https://a.hanleylee.com/HKMS/2020-01-20-223603.png?x-oss-process=style/WaMa)

![himg](https://a.hanleylee.com/HKMS/2020-01-20-221736.png?x-oss-process=style/WaMa)

## 字体使用

### 安装(以 macOS 为例)

1. 使用系统自带的`FontBook`软件打开字体文件

    ![himg](https://a.hanleylee.com/HKMS/2020-02-03-043210.png?x-oss-process=style/WaMa)

2. 确认安装

    ![himg](https://a.hanleylee.com/HKMS/2020-02-03-043844.png?x-oss-process=style/WaMa)

此时, 打开`FontBook`便可以看到安装的字体文件

![himg](https://a.hanleylee.com/HKMS/2020-02-03-044119.png?x-oss-process=style/WaMa)

### 终端中使用

1. iTerm

    `iTerm` → `Preference` → `Profile` → `Text` → `Font`

    ![himg](https://a.hanleylee.com/HKMS/2020-02-03-044341.jpg?x-oss-process=style/WaMa)

    iTerm 的字体设置分为 ASCII 字符的字体与非 ASCII 字符的字体, 建议均设置为本字体, 达到统一效果

    ps: 终端中的 vim 字体为终端使用的字体, 不能针对终端 vim 设置自定义字体.

2. MacVim

    在`~/.vimrc`做如下设定

    ```bash
    set guifont=YaHei\ Consolas\ Icon\ Hybrid:h16 "设置 GUI 下字体及大小, 针对 MacVim 进行设置
    set guifontwide=YaHei\ Consolas\ Icon\ Hybrid:h14 "设置 GUI 下中文字体及大小, 针对 MacVim 进行设置
    ```

## 特性

- ✅ 支持 Vim 中 Powerline 字体显示
- ✅ 支持终端中图形字符显示
- ✅ 同时支持中文与英文优化显示

## 字体组成

中文字符: Microsoft Yahei, PingFang-SC(极少量)

西文字符: Consolas

Iconic 字符: [NerdFont](https://github.com/ryanoasis/nerd-fonts)

## 开源许可

本仓库的所有代码基于 [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0) 进行分发与使用. 协议全文见 [LICENSE](https://github.com/HanleyLee/Yahei-Consolas-Icon-Hybrid-Font/blob/master/LICENSE) 文件.

Copyright 2020 HanleyLee

---

欢迎使用, 有任何 bug, 希望给我提 issues. 如果对你有用的话请标记一颗星星 ⭐️
