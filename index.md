---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
image: assets/images/me.jpg
---

{% if page.image %}
<center>
    <img src="{{site.baseurl}}/{{page.image}}" width="400" height="600">
</center>
{% endif %}