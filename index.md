---
---

# Welcome to iSQARE

The Intelligent Software Quality Assurance Research & Engineering Laboratory (iSQARE) is a dynamic research group at the University of Hawaiʻi at Mānoa led by Dr. Anthony S. Peruma. We are dedicated to advancing the field of software engineering with a focus on software quality, maintenance, and evolution through empirical studies, intelligent systems, and developer-centered tools.

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Our research spans multiple interconnected domains within software engineering, focusing on understanding and improving how developers write, comprehend, maintain, and evolve software systems. We investigate both technical aspects of code quality and human factors that influence software development decisions. By combining technical and human dimensions, we use real-world data to create evidence-based solutions that improve maintainability, security, and comprehensibility.  Through empirical studies, tool development, industry collaborations, and educational innovations, we strive to support developers with automated tools and insights grounded in practical relevance.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

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
%}
