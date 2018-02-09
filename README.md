# 墨水——Jekyll主题
墨水主题改版自[kaeyleo](https://github.com/kaeyleo/jekyll-theme-H2O)的主题。将原现代风主题处理为水墨风主题，故名墨水。改动：更改配色方案，涂鸦风格。在前人基础上优化评论、社交分享和移动端优化。

实际效果
[奇怪的小阁楼](blog.nintheavens.com)

## 墨水 Theme

[原主题源码及使用文档 →](https://github.com/kaeyleo/jekyll-theme-H2O)

![](https://github.com/nimocat/nimocat.github.io/blob/master/screenshot/first-page.png?raw=true)

新主题名叫"H2O"，基于Jekyll 3.0.x（使用```gem update jekyll```升级Jekyll），Markdown的代码高亮不再支持pygments转而使用rouge，咱已经默认配置了 ```highlighter: rouge``` 。用到的技术栈也很简单：引入jQuery类库，使用Sass编写样式，使用Gulp来编译Sass、合并压缩css、js，开源在[Github](https://github.com/kaeyleo/jekyll-theme-H2O)上，稍作配置即可用于你的Jekyll博客上。

下面是墨水的新特性

## 新特性

### 水磨风格标签与主页

涂鸦风格首屏页面与Tags标签，移动端适配完成。
![](https://github.com/nimocat/nimocat.github.io/blob/master/screenshot/all.png?raw=true)
![](https://github.com/nimocat/nimocat.github.io/blob/master/screenshot/tags.png?raw=true)

### 主题配色

使用暗色+白底字强调。

### 字蛛压缩字体文件

相比自己上一个版本的博客主题，首页增加了侧边栏，方便展示博主的个人信息和文章标签。

### 网站ICO

使用阿里的图标管理平台[Iconfont](http://iconfont.cn/)整理了一套<strike>墙内外</strike>常用的社交图标，包括微博、知乎、掘金、简书、Github等十多个网站，鼠标悬停会显示该站的主题色。

![social iconfont](http://on2171g4d.bkt.clouddn.com/jekyll-theme-h2o-snstext.jpg)



### 头图个性化底纹

在没有图片的情况下单纯显示颜色会不会太无趣了点？于是想到了加入底纹元素，底纹素材是SVG格式的（保存在css样式里），加载比图片快很多。

![](http://on2171g4d.bkt.clouddn.com/jekyll-theme-h2o-headerpatterns.jpg)

## 原作与更新

此主题原作者可在fork处见到，此版本为水墨风版本，以上新特性为水墨版本特性。

