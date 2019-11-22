---
hehe: 么么哒~
title: 我的第一篇博客
zhaiyao: 123456789
---

<h1>name: {{page.name}}</h1>
<h1>文章标题： {{page.title}}！</h1>
<!-- 过滤器 -->
<h4>{{page.zhaiyao}}</h4>
<!-- 12... -->
<h4>{{page.zhaiyao | truncate:5,'*'}}</h4>

{{ '<a href="">123</a>' }}
{{ '<a href="">123</a>' | strip_html }}

<!-- 输出_config.yml中的数据 -->
<h1>
我今年{{site.age}}岁了。。。。
</h1>

<!-- 将时间格式化为年月日 时分秒 -->
<h1>{{site.time | date:'%Y-%m-%d %H:%M:%S'}}</h1>


site
page