---
---

# Amadei Laboratory

Welcome to the Amadei Lab website! Here you will find information about what we do, who we are and where to find us!

{%
  include feature.html
  image="images/photo.jpg"
%}


{% capture text %}

Our research group is all about using different kinds of stem cells to generate embryo-like structures to model development. There is still a long way to go, but with our effort we would like to reduce our reliance on natural embryos, accelerate the pace of mammalian research and, of course, learn some new and exciting biology along the way!

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

Projects in the laboratory may wary greatly but in general they fall under these different types: 1) Optimisation of ETiX-embryoids, ie. how can we make this stem cell-based system EVEN BETTER as a proxy of mouse embryonic development? 2) Understanding similarities and differences between ETiX-embryoids and mouse natural embryos. 3) Testing whether ETiX-embryoids respond to developmental perturbations in the same way as natural embryos. 4) Development of novel methodologies of analysis.

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

Meet the team of young and upcoming scientist who work with ETiX-embryoids in the Department of Biology! In our team we believe in supporting each other, speaking our mind freely, and pushing the boundaries of what can currently be done with embryo-like structures.

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
