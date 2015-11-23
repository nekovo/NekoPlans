---
layout: post
title:  "Learning Collect"
date:   2015-10-27 21:45:49 +0800
categories: collect
---
## Laracasts - Be Awesome in PHPStorm (2014)
- 01 Hello
  - Install: PhpStorm Early Access Program
- 02 Minimalism
  - `IDE theme`: Darcula
  - `Editor colors and fonts`: Darcula
  - `⌘  + 1`: 打开/隐藏侧边栏
  - `⌘  + Shift + A`: Find Action
  - `View: Status Bar`: 隐藏状态栏
  - `View: Navigation Bar`: 隐藏导航栏
  - `Show breadcrumb`: 隐藏面包屑
  - `Tabs Placement: None`: 隐藏 Tabs

- 03 Color IDE
  - Install Plugin `Color Ide`

- 04 Two Important Keybindings
  - `⌘  + P`: `Navgate -> File...` 文件跳转
  - `⌘  + R`: `Navgate -> File Structure` 方法跳转

- 05 Create New Files Quickly
  - `⌘  + ↑` + `⌘ + N`

- 06 Custom File Templates
  - `File and Code Templates`

- 07 Live Templates
  - `⌘  + E`: 打开的文件之间跳转
  - `⌥  + ↑`: 扩大选择范围
  - `save live template`: 添加当前选中的内容为代码片段

- 08 Custom Formatting
  - `Reformat Code...`: 格式化
  - `⌥  + ⌘  + L`: 格式化当前文件
  - `https://github.com/deringer/phpstorm-laravel-code-style`

- 09 Refactoring Name and Method
- 10 Refactoring Pull Up
- 11 Refactoring Extract Interface
- 12 Refactoring Extract and Inline Variable
- 13 Fast Composition
- 14 Navigating to Sass Symbols
- 15 PHPStorm's Laravel Facades Issue
- 16 Multiple Cursors
- 17 Splits
- 18 Vi-Mode With Mappings
  - Install Plugin `IdeaVim`
  - `~/.ideavimrc` 配置文件
- 19 Xdebug
- 20 Xdebug and Laravel
- 21 Composer Dependencies and PHPStorm
- 22 Testing in PHPStorm
- 23 Code Coverage


## Code
- 设计模式
  - [深入理解 Yii2.0 » Yii 模式 » MVC](http://www.digpage.com/mvc.html)
  - [Laravel - 从百草园到三味书屋 "From Apprentice To Artisan" 翻译](http://my.oschina.net/zgldh/blog/389246)
  - [被误解的 MVC 和被神化的 MVVM](http://blog.devtang.com/blog/2015/11/02/mvc-and-mvvm/)
- 单元测试
  - [单元测试在软件开发中的作用？](http://segmentfault.com/q/1010000000692485)

## Vim
  - [VIM as PHP IDE - PHP Unconference 2015](https://www.youtube.com/watch?v=2ME-aqoUpaU)
  - [Using VIM as a PHP IDE](http://mjacobus.github.io/2015/04/17/using-vim-as-a-php-ide.html)
  - [WKLKEN BUILDING - Vim](http://www.wklken.me/category/vim.html)
  - [Vim 的哲学系列](http://segmentfault.com/a/1190000000458565)

## Vim Config
  - Ctags
    - 安装

          # you have ctags but it does not work...
          $ ctags -R --exclude=.git --exclude=log *
          ctags: illegal option -- R
          usage: ctags [-BFadtuwvx] [-f tagsfile] file ...
          
          #you need to get new ctags, i recommend homebrew but anything will work
          $ brew install ctags
          
          #alias ctags if you used homebrew
          $ alias ctags="`brew --prefix`/bin/ctags"

    - 使用
        - ctrl-] 匹配单词并压入标签栈
        - ctrl-o 返回上次光标停留行
        - ctrl-t 返回上个标签
        - <leader>tn :tnext<CR> 下一个标签
        - <leader>tp :tprevious<CR> 上一个标签
        

  - tpope/vim-surround
    - cs"'
    - cs'<q>
    - cst"
    - ds"
    - ysiw]
    - cs]{
    - yssb or yss)
    - ds{ds)
    - `ysiw<em>`
    

  - arnaud-lb/vim-php-namespace
    - 自动补完 use
    - inoremap <Leader>u <C-O>:call PhpInsertUse()<CR>
    - noremap <Leader>u :call PhpInsertUse()<CR>

  - godlygeek/tabular
    - 对齐插件
    - a= ar a




## 口琴

## AMV
  - 软件
    - [Adobe CC 2015 下载](http://www.macx.cn/thread-2164746-1-2.html)
    - [Adobe CC 2015 全套完美注册机 X-FORCE（含参考安装视频）](http://www.lookae.com/macxf2015/)
  - 素材处理
    - [ffmpeg Documentation](https://www.ffmpeg.org/ffmpeg.html)
    - [FFmpeg 常用基本命令](http://www.cnblogs.com/dwdxdy/p/3240167.html)
  - 教程
    - [(饺紫猫)我知道你想学做视频！！点进来~~](http://www.bilibili.com/video/av2251441/)
    - [教练我想学系列](http://www.bilibili.com/video/av2884017/)
  - 心得
    - [其实这是水经验，再谈自己做MAD的思路](http://tieba.baidu.com/p/2810880348)
    - [拉镜头？素材的命名？渣渣分享一下自己的愚见](http://tieba.baidu.com/p/2382959899)
    - [写给新人的一些建议，分享一下自己做视频的](http://tieba.baidu.com/p/2216694777)
    - [自己的经验分享第二弹有关转场及其他技巧](http://tieba.baidu.com/p/2308418418)
    - [(翻译)So You Want To Be a "GOOD" Anime Music Video Editor?](http://tieba.baidu.com/p/2396426125?see_lz=1)
  - 压制
    - [AviSynth 运行环境的搭建与使用](http://bbs.feng.com/read-htm-tid-7948832.html)
    - [尽量不浪费压制时间的简单视频高压要点](http://blog.sina.com.cn/s/blog_3df9d2330100zcy4.html)
  - 上传
    - [关于后黑科技LetvBugger和网络视频的必备扫盲](http://tieba.baidu.com/p/3244249465)
  - Log
    - 2015/10/31
      - 开坑~
    - 2015/11/04
      - 后面这 8 次 loop 闹哪样！！！ 做不下去了啊摔！！！！
      - 找更多的资源？
      - 加入战斗画面？(pass)
      - 加入手书画面？(pass)
    - 2015/11/08
      - 完工～

## Jekyll
  - [使用 Github Pages 建独立博客](http://beiyuu.com/github-pages/)
  - [jekyll - 掌心 系列博客](http://www.zhanxin.info/jekyll/)
