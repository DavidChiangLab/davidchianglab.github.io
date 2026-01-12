---
---

# Chiang Lab

Based in Brigham and Women's Hospital and Harvard Medical School.

{% include section.html %}

{% capture text %}

Genetic research for cardiac loss of function

{%
  include button.html
  link="research"
  text="Learn More"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/phosphorylation.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Check out our current zebrafish research!

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
  image="images/zebrafish.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

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
  image="images/longwood.jpg"
  link="team"
  title="Our Team"
  text=text
%}
