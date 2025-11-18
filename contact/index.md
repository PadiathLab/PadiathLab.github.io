---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Dr. Padiath leads the laboratory. For inquiries, including potential collaborations, please feel free to contact us using the information provided below. We welcome the opportunity to discuss future partnerships.

{%
  include button.html
  type="email"
  text="qpadiath@pitt.edu"
  link="qpadiath@pitt.edu"
%}
{%
  include button.html
  type="phone"
  text="(412) 624-7203"
  link="+1-412-624-7203"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/WurgJqtA6cmnTA6t7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/Padiath-Quasar.jpg"
  caption="Dr. Quasar S Padiath"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption=""
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}

{% endcapture %}

{% capture col2 %}

{% endcapture %}

{% capture col3 %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
