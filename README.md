## Vexo

> Vexo is a Hexo theme inspired by Vue's official website.

#### Intro

![](http://ww1.sinaimg.cn/large/006tKfTcgy1fggf5kinjcj30m80dwact.jpg)

#### Demo

[Live Example](http://yanm1ng.cn/hexo-theme-vexo/)

#### Features

* Fully Responsive
* Baidu Analytics
* Gitment
* Reward
* Share Qrcode
* SEO
* Immersive Status Bar

#### Install

1. Download this theme into your project

   ```
   cd your-hexo-folder

   git clone https://github.com/yanm1ng/hexo-theme-vexo.git themes/vexo

   cp themes/vexo/_source/* source/
   ```

2. Modify `_config.yml` with your own info. look like this

   ```
   themes: vexo
   ```

   Here theme's name must same as the theme folder name.

3. Or you can copy my theme `_config.yml` into you hexo blog directory , replace default `_config.yml`

4. That's all , hope you will like :)

#### Post

The **front-matter** of a post looks like that:

```
---
title: "Hello World"
date: 2016-06-10 23:00
tags:
 - Movies
 - Life
---
```

#### Comment

Vexo use [Gitment](https://github.com/imsun/gitment) as the third party discussion system.

You can easily complete your comment configuration by just adding your settings into `_config.yml`

```
# Gitment
gitment_owner: yanm1ng
gitment_repo: yanm1ng.github.io
gitment_oauth_id: 
gitment_oauth_secret: 
```

How to use Gitment ? [See]([https://imsun.github.io/gitment/](https://imsun.github.io/gitment/))

#### About

- Give a star if you like , fork or just clone to use , and also you can help me fix bugs and add new feature :)
- If you have any problem or requirement , just open an issue here and i will help you.
- Thanks to [imsun](https://github.com/imsun) , [Evan You](https://github.com/yyx990803) and [Hexo](https://hexo.io).

#### LICENSE
MIT