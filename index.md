---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults


---
### Test

Welcome to My Home Page with jekyll Timeago plugin

{% assign date = '2016-03-23T10:20:00Z' %}

- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}
