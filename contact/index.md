---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

iSQARE is based at the [University of Hawaiʻi at Mānoa](https://manoa.hawaii.edu/), within the [Department of Information and Computer Sciences](https://www.ics.hawaii.edu/) in beautiful Honolulu, Hawaiʻi. We welcome visitors, collaborators, and prospective students to connect with us and explore opportunities in our tropical research paradise.

{%
  include button.html
  type="email"
  text="peruma@hawaii.edu"
  link="peruma@hawaii.edu"
%}

{% comment %}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{% endcomment %}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/jspaomZGdXj2DPPu6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/buildings/uhmanoa.jpg"
  caption="The University of Hawaiʻi at Mānoa"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/buildings/post_building.jpg"
  caption="Department of Information and Computer Sciences"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}



{% comment %}
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
{% endcomment %}