## Getting started with test pages

{% capture code %}
 SELECT name,role FROM user
 WHERE country = 'JH'
{% endcapture %}

{% include code.html code=code lang="sql" %}

[Hello World](/hello.md)

