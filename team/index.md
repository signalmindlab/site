---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

At **SignalMind Lab**, our research explores how signals — whether embedded in medical images, wireless propagation patterns, IoT sensor streams, or complex datasets — are perceived, processed, and transformed into actionable intelligence. We study the intersection of signal processing, machine learning, and explainable AI, seeking to understand how information flows across telecommunications networks, diagnostic systems, and intelligent applications that bridge the digital and physical worlds.
Our interdisciplinary team brings together expertise from deep learning, wireless communications, computer vision, data science, and optimization. We develop ensemble methods for medical diagnostics, propagation models for next-generation wireless networks, real-time object detection systems, and intelligent forecasting algorithms for agriculture and finance. We believe in fostering a collaborative environment where mathematical rigor meets practical innovation, where explainable AI demystifies complex models, and where diverse perspectives drive breakthroughs in extracting meaning from signals across healthcare, telecommunications, IoT systems, and beyond.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% comment %}
{% include section.html background="images/background.jpg" dark=true %}
{% endcomment %}

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
