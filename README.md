hexo-theme-gruffalo
================

[![Join the chat at https://gitter.im/hexo-theme-indigo/Lobby](https://badges.gitter.im/hexo-theme-indigo/Lobby.svg)](https://gitter.im/hexo-theme-gruffalo/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
![Thanks](https://img.shields.io/badge/Say%20Thanks-💗-ff69b4.svg)

hexo-theme-gruffalo主题，基于 Hexo 3.0+ 制作。 [【博客1】](http://cenxiaoer.com/) [【博客2】](http://dearzoe.coding.me/)

>白天模式

![白天模式](http://huwenzhe.com/blogIndex/images/font1.jpg)

>夜间模式

![夜间模式](http://huwenzhe.com/blogIndex/images/font2.jpg)

## 主题安装

```ja
git clone https://github.com/dearzoe/hexo-theme-gruffalo.git themes/gruffalo
```

## 依赖安装

```js
//Less(主题默认使用 less 作为 css 预处理工具。)
$ npm install hexo-renderer-less --save
//Feed(用于生成 rss。)
$ npm install hexo-generator-feed --save
//Json-content(用于生成静态站点数据，用作站内搜索的数据源。)
$ npm install hexo-generator-json-content --save
//QRCode(用于生成微信分享二维码。)
$ npm install hexo-helper-qrcode --save
```

## Feature

1. 仅支持 IE10+ 等现代浏览器。
2. 去 jQuery，更轻。相信现代浏览器的原生兼容性。
3. 使用 Less 作为 css 预处理器，需要安装 `hexo-renderer-less`。
4. 添加了英文字体支持 Roboto。
5. 添加了一些波纹效果。By [Waves](https://github.com/fians/Waves)
6. 无前端依赖的分享实现。
7. 基于静态数据的站内搜索，无第三方侵入。
8. 支持文章打赏。

## more
需要额外安装字数统计插件（感谢dinphy）：

```bash
npm install --save hexo-wordcount
```
## Useage

[文档 | Document](https://github.com/dearzoe/hexo-theme-gruffalo/wiki)

## ChangeLog

升级前请仔细查看更改内容，如非必要可不升级。

[ChangeLog](https://github.com/dearzoe/hexo-theme-gruffalo/releases)

## Star

[![Star History Chart](https://api.star-history.com/svg?repos=u10k/hexo-theme-gruffalo&type=Date)](https://star-history.com/#u10k/hexo-theme-gruffalo&Date)

