---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title : Jiho Blog
author : 
 name : Park Jiho
 email : whfhrs3260@daum.net
 github : p-jiho
---
<html>
  <head>
    <meta charset="utf-8">
    <title>{{ page.title }}</title>
  </head>
  <body>
    <nav>
      <a href="/">Home</a>
      <a href="/blog/">Blog</a>
    </nav>
    <h1>{{ page.title }}</h1>
    <section>
      {{ content }}
    </section>
  </body>
</html>
