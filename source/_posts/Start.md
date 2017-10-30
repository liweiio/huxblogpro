---
img-path: Start-blog
title: Start blog
date: 2017-10-29 00:01:52
header-img: "timg.jpg"
tags:
	- 日记
	- LPL
	- 英雄联盟
---

## 2017-10-29
1. 修改了layout的配置文件以及替换了js和css
2. 通过修改config里面的url解决路径问题，把图片分成公共图片和文章图片，index页面的图片通过加入img-path属性进行读取到每个文件夹里面的文章图片
```
<% if(page["header-img"] ){%> <%= config['url'] %>/<%= page['img-path'] %>/<%= page["header-img"]  %> <%} else {%> <%= config["header-img"]%>  <% } %>
```
而页面详情里面的图片通过图片路径读取，这样使用配置url
```
<% if(page["header-img"] ){%> <%= page["header-img"]  %> <%} else {%> <%= config["header-img"]%>  <% } %>
```
3. 保留原始layout和config和更新后的layout和config文件
4. 去freenom使用域名绑定功能和CNAME文件进行绑定
5. LPL全军覆没,但或许是一个新的开始