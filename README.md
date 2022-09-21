# Hugo Theme Content

This is Hugo's theme, which was inspired by [https://www.bwsl.wang/](https://www.bwsl.wang/)

# Demo

[https://wjinlei.github.io/](https://wjinlei.github.io/)

# Features
- `Alt+/` Search
- The column on the right is displayed randomly
- The article set-top
- Recent updates
- Overdue reminder
- Read the statistics  
- Comments  
  Must install [https://utteranc.es/](https://utteranc.es/) app

# Example

```toml
baseURL = 'http://wjinlei.github.io/'
languageCode = 'zh-cn'
title = "Example's Blog"
theme = 'content'

[outputs]
home = ["HTML", "RSS", "JSON"]

[params]
Subtitle = "珍爱生命，远离卷王，拒绝内卷，从我做起。温馨提示: 按 Alt+/ 可以搜索哦 ^_^"
page_view_conter = true
  [params.utteranc]
  enable = true
  theme = "github-light"
  issueTerm = "title"
  repo = "your github page repo url must install utteranc app"

[menu]
  [[menu.left]]
  name = "首页"
  pre = "fa-solid fa-house" // https://fontawesome.com/ icon class
  url = "/"
  weight = 1

  [[menu.left]]
  name = "文章"
  pre = "fa-solid fa-pen-nib"  // https://fontawesome.com/ icon class
  url = "/posts/"
  weight = 2

  [[menu.right]]
  name = "我的QQ"
  pre = "fa-brands fa-qq"  // https://fontawesome.com/ icon class
  url = "#"
  weight = 1

  [[menu.right]]
  name = "我的微信"
  pre = "fa-brands fa-weixin"  // https://fontawesome.com/ icon class
  url = "#"
  weight = 2

  [[menu.right]]
  name = "我的Github"
  pre = "fa-brands fa-github"  // https://fontawesome.com/ icon class
  url = "https://github.com/Wjinlei"
  weight = 3

  [[menu.right]]
  name = "我的邮箱"
  pre = "fa-solid fa-envelope"  // https://fontawesome.com/ icon class
  url = "mailto:your email url"
  weight = 4

[markup]
  [markup.tableOfContents]
  ordered = false
  startLevel = 2
  endLevel = 4

  [markup.highlight]
  style = "dracula"
  tabWidth = 8
  noClasses = true
  lineNos = false
```
