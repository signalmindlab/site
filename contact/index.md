---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We're always excited to connect with students, researchers, and partners who share 
our passion for intersection of AI/ML, signal processing, and data analytics. 


Direct Email
Send your inquiries to: 
{%
  include button.html
  type="email"
  text="hello@signalmindlab.org"
  link="hello@signalmindlab.org"
%}

Best for: Detailed questions, collaboration proposals, or urgent matters.

<!--{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}-->


{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}
<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%% -->
<!--# Contact Us -->

<!-- <div class="contact-section">
  <h2>Have questions? Fill out the form below and we'll get back to you.</h2>
  <p>
    <a href="https://docs.google.com/forms/d/e/1FAIpQLSfSiHK-uUaKFaeHGmHQ8o9q5-jdpApIskqSv6V2niDE8VKK7w/viewform" 
       target="_blank" 
       rel="noopener noreferrer"
       class="form-link">
      Click here to open the contact form
    </a>
  </p>
</div>

<style>
  .contact-section {
    max-width: 700px;
    margin: 2rem auto;
    text-align: center;
  }
  
  .form-link {
    display: inline-block;
    padding: 12px 24px;
    background-color: #4285f4;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: 500;
    transition: background-color 0.3s;
  }
  
  .form-link:hover {
    background-color: #357ae8;
  }
</style> -->

{%
include button.html
type="link"
text="Fill out our contact form"
link="https://docs.google.com/forms/d/e/1FAIpQLSfSiHK-uUaKFaeHGmHQ8o9q5-jdpApIskqSv6V2niDE8VKK7w/viewform"
%}

**Best for:** Quick questions, tour requests, or initial interest

**What to Include:**
- Your name and affiliation
- Purpose of your inquiry
- Any relevant background or context
- Preferred method and timeline for response

---

> **Response Time:** We aim to respond to all inquiries within 2-3 business days.




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
