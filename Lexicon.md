# Lexicon

{% for term in site.lexicon %}
[__{{ term.title }}__]({{ site.baseurl }}{{ term.url }}) : {{term.description}}<br/>
{% endfor %}
