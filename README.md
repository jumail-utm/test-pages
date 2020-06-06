## Getting started with test pages

{% capture code %}
 SELECT * FROM user
 WHERE country = 'JH'
{% endcapture %}

{% include code.html code=code lang="sql" %}

[Hello World](/hello.md)


{% capture code %}const foo = new Bar();
foo.doDangerousJavascriptThings();
console.log("I love Jekyll!");{% endcapture %}

{% include code.html code=code lang="javascript" %}
