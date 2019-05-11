{% extends "section.md" %}

{% block body %}
{% for demo in items %}
+ {{ demo.title }}, {{ demo.authors}}, {{ demo.year }}, {{ demo.place }}.
{% endfor %}
{% endblock body %}
