---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# layout: home
---
{% for item in site.items %}
* [{{item.title}}](describer{{item.url}})
{% endfor %}