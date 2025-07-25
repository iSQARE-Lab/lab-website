---
title: Team
nav:
  order: 3
  tooltip: About our team
redirect_from:
  - /lab-members
  - /alums
  - /mascots
  - /staff
  - /trainees
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The iSQARE lab is a diverse group of passionate researchers, including graduate and undergraduate students, working under the guidance of Dr. Anthony Peruma. We foster a collaborative and inclusive environment where curiosity drives innovation and mentorship helps develop the next generation of software engineering researchers and practitioners.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'master' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad' and group != 'alum'" %}

{% include section.html dark=true %}

We welcome motivated students and industry partners interested in software engineering research to join iSQARE. Whether you are a prospective graduate student, an undergraduate eager to explore research, or an industry partner with a real-world problem, there’s a place for you to contribute to our ongoing projects or start new ones.


{% include section.html %}

## Alumni

Our alumni have played a vital role in shaping the growth and success of iSQARE. They have gone on to pursue impactful careers, continuing to contribute to the field of software engineering. We are proud of their achievements and remain grateful for their lasting contributions to the lab’s research, culture, and community.

{% include list.html data="members" component="portrait" filter="group == 'alum'" style="small" %}

{% comment %}
{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
{% endcomment %}
