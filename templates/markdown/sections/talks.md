{% extends "section.md" %}

{% block body %}
{% for talk in items %}
+ {{ talk.place }}, {{ talk.title}}, {{ talk.date }}
{% endfor %}
{% endblock body %}
