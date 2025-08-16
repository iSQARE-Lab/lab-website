---
---

# Welcome to iSQARE

The Intelligent Software Quality Assurance Research & Engineering Laboratory (iSQARE) is a dynamic research group at the University of Hawaiʻi at Mānoa led by [Dr. Anthony S. Peruma](https://www.peruma.me/){:target="_blank"}. We are dedicated to advancing the field of software engineering with a focus on software quality, maintenance, and evolution through empirical studies, intelligent systems, and developer-centered tools.

{% include section.html %}

## Overview

{% capture text %}

We aim to advance the science and practice of software quality assurance through intelligent, developer-focused research. We strive to understand the human and technical factors that shape software development, and to create solutions that make code more reliable, maintainable, and meaningful.

{% endcapture %}

{%
  include feature.html
  image="images/homepage_mission.jpg"
  title="Our Mission"
  flip=true
  style="bare"
  text=text
%}


{% capture text %}

Our research spans multiple interconnected domains within software engineering, focusing on understanding and improving how developers write, comprehend, maintain, and evolve software systems. We utilize real-world data to develop evidence-based solutions that enhance maintainability, security, and comprehensibility. Through empirical studies, tool development, industry collaborations, and educational innovations, we aim to support developers with practical insights and automated tools that are grounded in real-world relevance.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/homepage_research.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% comment %}
{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
  flip=true
%}
{% endcomment %}
