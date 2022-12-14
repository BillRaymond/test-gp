---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
Page name: {{page.name}}

Page name + webp extension: {{page.name | split: '.' | first | append: '.webp'}}

Page name + relative url: {{page.name | relative_url}}

Page name + relative url + webp extension: {{page.name | relative_url | split: '.' | first | append: '.webp'}}


