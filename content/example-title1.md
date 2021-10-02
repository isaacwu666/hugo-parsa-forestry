+++
categories = ["S "]
date = 2021-10-18T16:00:00Z
description = "是"
image = "/images/img_1718.JPG"
tags = ["S"]
title = "example title1"
type = "post"

+++
测试哥哥哥

我的博客之前一直托管在 coding 上，图片等静态资源放在七牛云的 cdn 上，这样国内国外访问速度都还可以。

  
去年七牛云的 cdn 强制需要做域名备案，备案是不可能的，这辈子都不可能，所以把所有静态资源都直接扔到 coding 上。coding 也发生了几次博客推送后不更新问题，一怒之下，就直接把博客迁到 GitHub Pages，不过对国内用户来说，访问速度和稳定性不是很好。

  
正当我在想怎么办的时候，发现了 Netlify。

[Netlify](https://link.zhihu.com/?target=https%3A//www.netlify.com/) 是一个提供静态资源网络托管的综合平台，提供CI服务，能够将托管 GitHub，GitLab 等网站上的 Jekyll，Hexo，Hugo 等代码自动编译并生成静态网站。

Netlify 有如下的功能:

* 能够托管服务，免费 CDN
* 能够绑定自定义域名
* 能够启用免费的TLS证书，启用HTTPS
* 支持自动构建
* 提供 Webhooks 和 API

## **使用 Netlify**

首先使用你的 GitHub 账号登陆 Netlify，登陆后进入空间管理中心，，点击`New site from git`按钮开始部署你的博客：