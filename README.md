# DevNotes

DevNotes 是为 [Hexo](http://hexo.io) 设计的一款清新且具有响应式的主题，拥有更丰富的特性并支持了很多的国内服务。DevNotes 基于 [Jacman](https://github.com/wuchong/jacman)，改进了诸多细节。

**DevNotes 支持 Hexo 3.0 !**


##安装教程
###安装
```
$ git clone https://github.com/yuanshihao/DevNotes.git themes/DevNotes
```
**DevNotes 需要 Hexo 2.7 及以上版本** 

###启用
修改博客根目录下的配置文件 `config.yml`，把 `theme` 的值修改为 `DevNotes`
###更新
```
cd themes/DevNotes
git pull origin master
```
**请先备份您主题目录下的 `_config.yml` 文件后再升级。**

##配置指南

修改 `/themes/jacman/_config.yml` 中的配置。

**DevNote** 的配置与 **Jacman** 的配置相同。

通过参考 **Jacman** 的 [配置指南wiki](https://github.com/wuchong/jacman/wiki/%E9%85%8D%E7%BD%AE%E6%8C%87%E5%8D%97) 了解更多

##功能
- **菜单 menu**  
 主导航菜单
- **控件 widget**  
 侧边栏的控件。包括：分类、标签、RSS、归档、标签云、友情链接、微博秀。
- **图片相关 Image**  
 设置网站图标、网站logo、作者头像、博客顶部大图等。还提供了多种图片样式`img-logo`,`img-topic`,`img-center`等
- **首页模式 index**  
 主题提供了两种首页展示模式，你可以访问 [主题演示](http://jacman.wuchong.me) 来了解其不同。
- **作者 author**  
 作者信息，主要用于展示网站右下角的社交网络链接。包括：微博、豆瓣、知乎、邮箱、GitHub、StackOverflow、Twitter、Facebook、Linkedin、Google+。
- **目录 toc**  
 在文章中和侧边栏可以显示目录。
- **评论 comments**  
 支持 [多说](http://duoshuo.com/) & [disqus](https://disqus.com/) 评论。
- **分享 jiathis**  
 启用 内建分享工具 或 [加网](http://www.jiathis.com/) 分享系统。
- **网站统计 Analytiscs**  
 支持 [谷歌统计](http://www.google.com/analytics/) & [百度统计](http://tongji.baidu.com/) & [CNZZ站长统计](http://www.cnzz.com/)。
- **Search**  
 支持 [谷歌自定义搜索](https://www.google.com/cse/ ) & [百度站内搜索](http://zn.baidu.com/)  &[微搜索](http://tinysou.com/)。
- **totop**  
 回到顶部。
- **rss**  
 RSS 订阅链接。
- **fancybox**  
 图片查看的 [Fancybox](http://fancyapps.com/fancybox/) 工具。
- **自定义主题颜色**
 在`_config.yaml`中就可以修改主题的颜色，而不用去找那些奇怪的 stylus 文件。
- **其他**
 你可以设置侧边栏在博文页面中不显示。

你可以通过[配置指南](https://github.com/wuchong/jacman/wiki/配置指南)了解更多使用细节。

##网站列表
- [idevNotes](http://idevnotes.com) - The demo site 

##协议
[MIT](/LICENSE)


