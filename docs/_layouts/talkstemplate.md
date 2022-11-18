---
---

<h5>{{ entry.title }}</h5>
<div style="text-align:left;">
   {{ entry.conf }}
    <span style="float:right;">
       {{ entry.loc}}
    </span>
</div>

<div style="text-align:right;"> {{ entry.month | capitalize }} {{ entry.year }}</div>

{% if entry.abstract %}
<details>
<summary>Abstract</summary>
<p>{{ entry.abstract }}</p>
</details>
{% endif %}

