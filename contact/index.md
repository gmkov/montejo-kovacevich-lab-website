---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

The lab is based in the Animal Ecology Program at the Ecology and Genetics Department, Evolutionary Biology Centre, Uppsala University.

{%
  include button.html
  type="email"
  text="PI email"
  link="gabriela.montejo-kovacevich@scilifelab.uu.se"
%}
{%
  include button.html
  type="Address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/YEZXoRv3f2AoyDbU9"
%}


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
Evolutionary Biology Centrum, Uppsala University
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 %}
