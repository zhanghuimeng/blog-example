---
title: excerpt和description测试
urlname: excerpt-and-description-test
date: 2019-04-03 19:55:37
tags:
description: 这是front-matter的description中写的内容
---

这里写了一句话，但是下面没有`<!--more-->`，所以应该显示摘要，且应该显示front-matter的`description`中写的内容。

[官方文档 - 页面配置 - Front-matter](https://xaoxuu.com/wiki/material-x/front-matter/index.html#Front-matter)中说，`excerpt`是layout=post时特有的字段。

[官方文档 - 页面配置- 文章摘要](https://xaoxuu.com/wiki/material-x/front-matter/index.html#%E6%96%87%E7%AB%A0%E6%91%98%E8%A6%81)中说：

>第一优先级是寻找正文中的`<!--more-->`，其前面的为摘要，可以显示在文章列表中，后面的是正文。
>如果没有，则寻找Front-matter中的`excerpt`字段，以其为摘要。
>如果还没有，就没有摘要，文章列表会显示全文。
