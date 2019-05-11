{% extends "section.md" %}

{% block body %}
{% for thesis in items %}
+ {{ thesis.title }}, {{ thesis.supervisor}}
{% endfor %}
{% endblock body %}
