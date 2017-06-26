---
layout: page
title: "留言板"
description: "留言板"
group: navigation
comments: true
---

<div id="gitment_container"></div>
<link rel="stylesheet" href="/gitment/style/default.css">
<script src="/gitment/dist/gitment.browser.js"></script>
<script>
var gitment = new Gitment({
  owner: 'gadfly3173',
  repo: 'comments_for_blog',
  oauth: {
    client_id: '1d74d093270dc8149157',
    client_secret: '11828cfbb6455dde70ddc074eb3e64743e748064',
  },
})
gitment.render('gitment_container')
</script>
<noscript>请开启浏览器的JavaScript功能或使用支持JavaScript功能的浏览器来使用由<a href="https://imsun.github.io/gitment/">Gitment</a>提供的评论功能</noscript>

