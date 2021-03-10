---
title: Konfiguracja
has_children: true
nav_exclude: false
has_toc: false
parent: "Gotowce"
---
Konfiguracja
{: .label .label-red }

# Konfiguracja

<ul>
    {% for pg in site.pages %}
        {% if pg.parent == page.title %}
            <li>
                <a href="{{ site.url }}{{ site.baseurl }}/{{ pg.url }}">{{ pg.title }}</a>
            </li>
        {% endif %}
    {% endfor %}
</ul>
