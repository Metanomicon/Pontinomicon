# Lexicon

{% for lexeme in site.lexicon %}
* [__{{ lexeme.title }}__]({{ site.baseurl }}{{ lexeme.url }}) : {{lexeme.description}}
{% endfor %}
