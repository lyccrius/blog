---
layout: post
title: "中小学电子教材下载"
date:   2022-08-12
categories: 
---

<a href="https://www.zxx.edu.cn" target="_blank">国家中小学智慧教育平台</a>

上个月这个网站上的电子教材还是可以直接下载的，

这个月网站更新后就不行了只能在线浏览。

就很烦。

希望国家部门直属的网站不要再像其他社交平台那样搞的花里胡哨的了。

以下是下载教程。

* 打开 <a href="https://www.zxx.edu.cn" target="_blank">国家中小学智慧教育平台</a>
* 点击 “教材” 一栏
* 选择需要的电子教材
* 点击右上角 “触控屏” 按钮（请先登录）
* 打开网站检查器
* 找到 “<body>”
* 依次展开：
* “<main>”
* “<div class="h-if-window-main courseware h-if-active">”
* “<div class="h-if-urlContainer h-if-active">”
* 在 <iframe> 标签中根据 “src” 获得 url
* 在新标签页中打开并下载