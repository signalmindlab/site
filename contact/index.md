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
<!--{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}-->
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

  <div class="contact-method">
    <h4>Online Form</h4>
    <p>
      <a href="https://docs.google.com/forms/d/e/1FAIpQLSfSiHK-uUaKFaeHGmHQ8o9q5-jdpApIskqSv6V2niDE8VKK7w/viewform" 
         target="_blank" 
         rel="noopener noreferrer"
         class="form-button">
        Fill out our contact form
      </a>
    </p>
    <p><strong>Best for:</strong> Quick questions, tour requests, or initial interest</p>
    
    <div class="form-guidelines">
      <p><strong>What to Include:</strong></p>
      <ul>
        <li>Your name and affiliation</li>
        <li>Purpose of your inquiry</li>
        <li>Any relevant background or context</li>
        <li>Preferred method and timeline for response</li>
      </ul>
    </div>
  </div>

  <p class="response-time">We aim to respond to all inquiries within 2-3 business days.</p>
</div>

<style>
  .contact-section {
    max-width: 800px;
    margin: 2rem auto;
    padding: 2rem;
    line-height: 1.6;
  }

  .contact-section h2 {
    color: #333;
    margin-bottom: 1rem;
  }

  .contact-section h3 {
    color: #444;
    margin-top: 2rem;
    margin-bottom: 1.5rem;
  }

  .contact-method {
    background: #f8f9fa;
    padding: 1.5rem;
    margin-bottom: 1.5rem;
    border-radius: 8px;
    border-left: 4px solid #4285f4;
  }

  .contact-method h4 {
    color: #333;
    margin-top: 0;
    margin-bottom: 1rem;
  }

  .contact-method p {
    margin: 0.5rem 0;
  }

  .form-button {
    display: inline-block;
    padding: 12px 24px;
    background-color: #4285f4;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: 500;
    transition: background-color 0.3s;
    margin: 1rem 0;
  }

  .form-button:hover {
    background-color: #357ae8;
  }

  .form-guidelines {
    margin-top: 1rem;
    padding: 1rem;
    background: white;
    border-radius: 5px;
  }

  .form-guidelines ul {
    margin: 0.5rem 0;
    padding-left: 1.5rem;
  }

  .form-guidelines li {
    margin: 0.3rem 0;
  }

  .response-time {
    text-align: center;
    font-style: italic;
    color: #666;
    margin-top: 2rem;
    padding: 1rem;
    background: #fff9e6;
    border-radius: 5px;
  }

  a[href^="mailto:"] {
    color: #4285f4;
    text-decoration: none;
    font-weight: 500;
  }

  a[href^="mailto:"]:hover {
    text-decoration: underline;
  }
</style>




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
