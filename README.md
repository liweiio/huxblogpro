# 2017-10-30 升级记录
1. 下载huxbolg
2. 修改_config.yml文件```anchorjs: fasle```取消锚点和注释disqus_username属性
3. 修改post内容把目录信息从ajax生成修改为hexo自己生成

# 2017-10-29 升级记录
1. 修改page页面信息取消首页上半部分背景图,每个页面上加入获取背景图，移植css
2. 移植blog.js信息,blog.css样式

# Hexo-Theme-Huxblog

> Ported Theme of [Hux Blog](https://github.com/Huxpro/huxpro.github.io), Thank [Huxpro](https://github.com/Huxpro) for designing such a flawless theme.

### [Demo &rarr;](http://kaijun.github.io/hexo-theme-huxblog)


![](http://huangxuan.me/img/blog-desktop.jpg)

## Usage

I didn't publish it as a single theme folder because a few of the pages are added and modified manually, so you should manually create some extra folders in `source` for the new pages and modify the `_config.yml` if you only have the single theme folder.

So i just pushed the whole hexo project for your convenience, all pre settings and boilerplates are included, have a look and go ahead customizing your own blog!

##### 1.Init

```
git clone https://github.com/Kaijun/hexo-theme-huxblog.git
cd hexo-theme-huxblog
npm install
```

##### 2.Modify
Modify `_config.yml` file with your own info.
Especially the section:

```
deploy:
  type: git
  repo: https://github.com/Kaijun/hexo-theme-huxblog
  branch: gh-pages
```
Replace with your own repo!

##### 3.Writting/Serve/Deploy

```
hexo new post IMAPOST
hexo serve // run hexo in local environment
hexo clean && hexo deploy // hexo will push the static files automatically into the specific branch(gh-pages) of your repo!
```

##### 4.Enjoy! 
Please [**Star**](https://github.com/kaijun/hexo-theme-huxblog/stargazers) this Project if you like it! [**Following**](https://github.com/Kaijun) would also be appreciated!
