---
layout: page
---

## Journals

{::options parse_block_html="true" /}
<ul class="mylist">
{% for member in site.data.members %}
<li>
{{member.title}}, {{ member.authors }}, <i>{{member.journal}}</i>, <b>{{ member.year }}</b>, <a href="https://doi.org/{{ member.doi }}" style="color:#2a4d69">doi: {{ member.doi }}</a>
<p><b>Abstract</b>.&mdash;<i>{{ member.abstract }}</i></p>
</li>
{% endfor %}
</ul>

## Conferences

This is another publication

Panel Content here

## Patents

Yet another one.

