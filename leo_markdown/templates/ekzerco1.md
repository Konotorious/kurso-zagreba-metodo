#### {{ enhavo.fasado['Traduku'] }}

{% for vico in leciono.ekzercoj['Traduku'] %}
  {% for esperante, fontlingve in vico.items() %}
- {{ esperante }}:

  {% endfor %}
{% endfor %}
