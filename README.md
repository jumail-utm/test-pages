## Getting started with test pages

{% capture code %}
 SELECT role FROM user
 WHERE country = 'JHR'
{% endcapture %}

{% include code.html code=code lang="sql" file="code/examples/query.sql" %}

[Hi World](/hello.md)

