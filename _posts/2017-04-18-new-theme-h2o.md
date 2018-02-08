---
layout: post
title: 'H2O theme for Jekyll'
subtitle: '或许是最漂亮的Jekyll主题'
date: 2017-04-18
categories: 技术
cover: 'http://on2171g4d.bkt.clouddn.com/jekyll-theme-h2o-postcover.jpg'
tags: jekyll 前端开发 设计
---

正如我在[微博](http://weibo.com/1374146504/profile?topnav=1&wvr=6)上所说的，使用[Jekyll](http://jekyll.com.cn/)半年以来一直没有令我满意的主题模板，所以开始计划自己写一套好看又好用的主题模板。设计之初就明确了极简主义，风格采用扁平化了，通过卡片式设计来进行区块分明的布局，参考了Medium的ui样式和知乎专栏的视觉风格。

## H2O——水墨风版本

[源码及使用文档 →](https://github.com/kaeyleo/jekyll-theme-H2O)

![](http://on2171g4d.bkt.clouddn.com/jekyll-theme-h2o-realhome.jpg)

新主题名叫"H2O"，基于Jekyll 3.0.x（使用```gem update jekyll```升级Jekyll），Markdown的代码高亮不再支持pygments转而使用rouge，咱已经默认配置了 ```highlighter: rouge``` 。用到的技术栈也很简单：引入jQuery类库，使用Sass编写样式，使用Gulp来编译Sass、合并压缩css、js，开源在[Github](https://github.com/kaeyleo/jekyll-theme-H2O)上，稍作配置即可用于你的Jekyll博客上。

使用Sketch完成H2O主题的原型设计

![My Jekyll themes](http://on2171g4d.bkt.clouddn.com/jekyll-theme-vs.jpg)

比之前漂亮不少吧，下面聊聊H2O的新特性。

## 新特性

### 水磨风格标签与主页

涂鸦风格首屏页面与Tags标签，移动端适配完成。

### 主题配色

使用暗色+白底字强调。

###字蛛压缩字体文件

相比自己上一个版本的博客主题，首页增加了侧边栏，方便展示博主的个人信息和文章标签。

### 网站ICO

使用阿里的图标管理平台[Iconfont](http://iconfont.cn/)整理了一套<strike>墙内外</strike>常用的社交图标，包括微博、知乎、掘金、简书、Github等十多个网站，鼠标悬停会显示该站的主题色。

![social iconfont](http://on2171g4d.bkt.clouddn.com/jekyll-theme-h2o-snstext.jpg)



### 头图个性化底纹

在没有图片的情况下单纯显示颜色会不会太无趣了点？于是想到了加入底纹元素，底纹素材是SVG格式的（保存在css样式里），加载比图片快很多。

![](http://on2171g4d.bkt.clouddn.com/jekyll-theme-h2o-headerpatterns.jpg)

##原作与更新

此主题原作者可在fork处见到，此版本为水墨风版本，以上新特性为水墨版本特性。