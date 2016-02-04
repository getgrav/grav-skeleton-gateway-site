---
title: Blog
blog_url: blog
menu: Blog
body_classes: blog group-blog infinite-scroll neverending infinity-end

sitemap:
    changefreq: monthly
    priority: 1.03

content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true

feed:
    description: Sample Blog Description
    limit: 10

pagination: true
---
## Latest News
### Change these titles to anything you'd like in the customizer.
