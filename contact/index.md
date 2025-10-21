---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="hello@signalmindlab.com"
  link="hello@signalmindlab.com"
%}
<!--{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}-->
<--{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}-->

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
# Contact Us

Have questions? Fill out the form below and we'll get back to you.

<div class="google-form-container">
  <iframe 
    src="https://docs.google.com/forms/d/e/1FAIpQLSfSiHK-uUaKFaeHGmHQ8o9q5-jdpApIskqSv6V2niDE8VKK7w/viewform?embedded=true" 
    width="100%" 
    height="2000" 
    frameborder="0" 
    marginheight="0" 
    marginwidth="0" 
    scrolling="no">
    Loading…
  </iframe>
</div>

<style>
.google-form-container {
  max-width: 700px;
  margin: 2rem auto;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.google-form-container iframe {
  display: block;
  background: white;
  overflow: hidden;
}
</style>
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
