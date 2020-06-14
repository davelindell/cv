{% extends "section.md" %}

{% block body %}
<table class="table table-hover">
{% for person in items %}
<tr>
  <td class='col-md-2'>{{ person.person }}</td>
  <td>
    {{ person.place }}
  </td>
  <td>
    {{ person.date }}
  </td>
</tr>
{% endfor %}
</table>
{% endblock body %}
