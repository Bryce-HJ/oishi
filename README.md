# Oishi

根据landscape-plus主题和Writing主题进行修改。

## 演示

你可以点击[这里](http://www.cnhalo.com/)，查看演示。

## 安装

``` bash
$ git clone https://github.com/henryhuang/oishi.git themes/oishi
```
**Oishi 需要 Hexo 2.7 及以上版本.**

## 启用

修改主题的设置文件`_config.yml`，把`theme`的值设置为`oshi`

## 更新

``` bash
cd themes/oishi
git pull
```

## 配置

```yml
# Header
menu:
  首页: /
  归档: /archives

# Content
excerpt_link: ...
fancybox: false

# Sidebar
sidebar: 
widgets:
- category
- tag
- tagcloud
- archive
- recent_posts
- links

# Links
links:

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
fb_admins: 
fb_app_id:

# Duoshuo
duoshuo_shortname: 

# Baidu share
baidushare: false

# scrollUp 样式
scrollUp: image

# social
social:
  github: https://github.com/github_id
  weibo: http://weibo.com/weibo_id
```

## 所有新特性