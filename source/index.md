```{include} 
:end-before: 
```
{% if build == "slides" %}
<!-- <p style="font-size: 0.9em;"><strong>Dr. Jonas I. Liechti</strong><br>
<strong>Dr. Matteo Delucchi</strong></p> -->
:::{admonition} Authors
:class: note, margin
Dr. Jonas I. Liechti  
Dr. Matteo Delucchi
:::

:::{admonition} Editors
:class: note, margin
Barbara Mejia
:::
{% else %}
### Authors

**Dr. Jonas I. Liechti**  
**Dr. Matteo Delucchi**  


### Editors

**Barbara Mejia**
{% endif %}

### Content

```{toctree}
:caption: About
:maxdepth: {% if build == "slides" %}1{% else %}2{% endif %}
{% if build == "slides" %}:hidden:
{% endif %}

content/about/index
```


```{toctree}
:caption: Outro
:maxdepth: {% if build == "slides" %}1{% else %}2{% endif %}
{% if build == "slides" %}:hidden:
{% endif %}

content/outro/index
```