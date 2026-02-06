# About this Seminar

{% if slide %}

```{card} 🔓 Open Source on Practical Scientific Computing
:class: tip
:link: https://github.com/t4d-gmbh/PracticalScientificComputing
:link-type: url

:::{image} ./git4acad.png
:align: center
:width: 180px
:alt: QR GitHub Repo.
:::

**<https://github.com/t4d-gmbh/PracticalScientificComputing>**
```
{% endif %}

```{toctree}
:maxdepth: {% if build == "slides" %}1{% else %}2{% endif %}

./syllabus
{% if slide %}
./requirements
./presenters
{% endif %}
```
_If you like this type of presentation format checkout the [t4d-gmbh/web-course-template](https://github.com/t4d-gmbh/web-course-template)_
