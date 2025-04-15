---
---

# Welcome

**Website under slow construction!**

We study the mechanisms promoting (or preventing) local adaptation. Our research combines the power of genomics with ecological and natural history approaches to gain insights into the mode and tempo of evolution in the wild. Based in Uppsala University since September 2024.

Check out the website and get in touch if you’d like to join us.


{% include section.html %}

## Highlights

{% capture text %}

Most recent publications can be found here

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

Check out a non-exhaustive list of active and past projects in the lab. Includes tutorials and datasets.

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

We are an international team of researchers based in the Department of Ecology and Genetics (Uppsala University, Sweden) and collaborators from around the globe.

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
