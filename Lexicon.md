# Lexicon

{% for page in site.lexicon %}
[__{{ page.term }}__]({{ site.baseurl }}{{ page.url }}) : {{ page.definition }}<br/>
{% endfor %}
