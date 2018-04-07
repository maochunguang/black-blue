# Hexo黑蓝主题
![主题图片](http://o7kalf5h3.bkt.clouddn.com/blog-index.png)

## 特性
本主题由**SPFK**修改而成，具体改进如下：
1. 颜色由黑色和蓝色为主，主题鲜明直观
2. 压缩css和js（SPFK主题没有压缩css，js）
3. seo优化，
4. 增加站内搜索（根据title来搜索）
5. 删除stylus，直接使用css
6. 评论插件修改，删除多说，增加畅言,增加gitment评论插件

## 注意1：
大家使用主题的时候，把**主题配置文件_config.yml**以下几项必须修改，
```yml
## 项目里实用的是我博客的正式代码，请大家修改成自己的！
google_analytics: xxx
baidu_analytics: xxxxxxx
disqus:
  on: false
  shortname: xxxx
# 畅言评论
changyan:
  on: true
  appid: xxxx
  conf: xxxxx

```

## 注意2：
如果域名是https的话，https必须配置为true，不是https设置为false
```yml
# 域名是否启用https，如果启用，js文件必须https加载
isHttps: true
```
## 注意3：
如果使用gitment作为评论插件，参考一下两篇文章。
[gitment常见问题](http://xichen.pub/2018/01/31/2018-01-31-gitment/)
[自动初始化gitment](https://draveness.me/git-comments-initialize)


注意：使用本主题请仔细查看[black-blue Hexo使用介绍](http://geeksblog.cc/hexo-theme.html)

