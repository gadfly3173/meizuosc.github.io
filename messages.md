---
layout: page
title: "留言板"
description: "留言板"
group: navigation
comments: true
---
## 留言板
<div id="container"></div>
<link rel="stylesheet" href="https://imsun.github.io/gitment/style/default.css">
<script src="https://imsun.github.io/gitment/dist/gitment.browser.js"></script>
<script>
var gitment = new Gitment({
  owner: 'gadfly3173',
  repo: 'comments_for_blog',
  oauth: {
    client_id: '1d74d093270dc8149157',
    client_secret: '11828cfbb6455dde70ddc074eb3e64743e748064',
  },
})
gitment.render('container')
</script>