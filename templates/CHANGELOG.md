## {{ release_title }}

{% for change in changes %}
### {{ change.title }}
{% for entry in change.entries %}
- {{ entry.message }}
{% endfor %}
{% endfor %}