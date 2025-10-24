---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

At Signal Mind Lab, our research explores how signals — whether neural, sensory, environmental, or digital — are perceived, processed, and transformed into meaningful representations of the world. We study the intersection of signal perception, intelligent computation, and cognitive modeling, seeking to understand how information flows across systems both natural and artificial.

Our interdisciplinary team brings together expertise from signal processing, machine learning, neuroscience, systems engineering, and computational modeling. We believe in fostering a collaborative environment where mathematical rigor meets creative exploration, and where diverse perspectives drive innovation in understanding signals in their many forms.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

{% comment %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
{% endcomment %}

{% comment %}
{% include section.html %}
{% endcomment %}

{% capture content %}

{% comment %}
{% include figure.html image="images/photo.jpg" %}
{% endcomment %}

{% comment %}
{% include figure.html image="images/photo.jpg" %}
{% endcomment %}

{% comment %}
{% include figure.html image="images/photo.jpg" %}
{% endcomment %}

{% endcapture %}
{% comment %}
{% include grid.html style="square" content=content %}
{% endcomment %}
