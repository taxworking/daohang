# 蜗牛个人导航

### Live Demo
- [https://s.eallion.com](https://s.eallion.com)

### 关于

最开始出于收藏导航的目的，收集了很多博客和网站，后来收集的内容越来越多，浏览器书签已经放不下了，而且当时还没有自己的电脑，就专门建立了一个个人导航网站。

最原始的版本始于 2006 年，基于 [jobidc.com](http://eallion.jobidc.com/) 模板。详细（并不）的 ChangeLog 记录于此：[https://github.com/eallion/favorite/blob/main/changelog.md](https://github.com/eallion/favorite/blob/main/changelog.md)

用各种各样的框架和模板折腾过导航网站：Wordpress、Typecho、Drupal、Dokuwiki、MDwiki、Hexo、Hugo、HTML。基本上还体验过 Google 和 GitHub 能搜索到的所有导航网站源码。因为个人导航网站的数据量非常小，现在使用的是一个纯静态的 HTML 模板。这套模板从 [https://github.com/TopVitamin/static-nav](https://github.com/TopVitamin/static-nav) fork 而来，不过基本上已完全重构，添加了一些个人需要的功能，做了一些优化。

本站目前采用 VS Code 编辑，用 Git 管理，托管于 GitHub，通过 Vercel 构建部署。

原始模板托管在 `master` 分支。https://github.com/eallion/favorite/tree/master 。可通过  [https://eallion.github.io/favorite](https://eallion.github.io/favorite/) 预览。

本人热爱开源分享，欢迎探讨交流。但因为本站为个人使用，除非个人需要，一般不会有 Breaking Change，也没时间处理功能性需求。本站已开放源码，稍加修改即可部署使用。通过 Issue 和邮件提出的问题，我可能不及时，但一定会回复。
### 优化与负优化

 - 手机端适配
 - 搜索框重构
 - jQuery：<https://jquery.com/>
 - Google fonts：<https://fonts.google.com/>
 - Google favicon API：<https://www.google.cn/s2/favicons?domain_url=https://s.eallion.com>
 - Self-hosted favicon api (Vercel)：<https://favicon.api.eallion.com/?sz=32&url=https://s.eallion.com>
 - Iconify：<https://iconify.design/>
 - 今日诗词：<https://www.jinrishici.com/>
 - Umami 统计：<https://github.com/mikecao/umami.git>
 - Staticfile CDN：<http://staticfile.org/>
 - 和风天气：<https://www.qweather.com/>
 - Vanilla lazyload：<https://github.com/verlok/vanilla-lazyload>
 - PWA：<https://web.dev/progressive-web-apps/>
 - Moment：<https://github.com/moment/moment>
 - Lately：<https://tokinx.github.io/lately/index-zh.html>
 - Smooth scroll：<https://github.com/mmkjony/jQuery.toTop>
 - Toggle menu：<https://codepen.io/Siddharth11/pen/vNEEZp>
 - Dark mode: <https://github.com/coliff/dark-mode-switch>
 - 极客族：<https://cdn.geekzu.org/cached.html>
 - 腾讯云开发：<https://cloud.tencent.com/product/tcb>
 - 嘀咕 Talk：<https://eallion.com/talk/>
 - 腾讯公益 404：<https://news.qq.com/404/>

### Inspiration
- <https://github.com/TopVitamin/static-nav>
- <https://github.com/soulteary/docker-flare>
- <https://edui123.com/>
- <https://nav.wsoso.com/>
- <https://www.milkdh.com/>

### LICENSE
```
GLWT（祝你好运）公共许可证
版权所有（C）每个人，除了作者

任何人都被允许复制、分发、修改、合并、销售、出版、再授权或
任何其它操作，但风险自负。

作者对这个项目中的代码一无所知。
代码处于可用或不可用状态，没有第三种情况。


                祝你好运公共许可证
            复制、分发和修改的条款和条件

0 ：在不导致作者被指责或承担责任的情况下，你可以做任何你想
要做的事情。

无论是在合同行为、侵权行为或其它因使用本软件产生的情形，作
者不对任何索赔、损害承担责任。

祝你好运及一帆风顺。
```