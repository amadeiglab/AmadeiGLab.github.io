---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

**Address:** Complesso Vallisneri, 1st floor south, Via Ugo Bassi 58 B, 35131 Padova (PD), Italy

**Email:** gianluca.amadei@unipd.it

**Telephone:** +39 0498276348

The laboratory space is in the Department of Biology at Complesso Vallisneri, located north of Padova's beautiful historic city centre. 

{%
  include button.html
  type="email"
  text="gianluca.amadei@unipd.it"
  link="gianluca.amadei@unipd.it"
%}
{%
  include button.html
  type="phone"
  text="+39 0498276348"
  link="+39 0498276348"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/G8mNuy2gFigMveXcA"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/Vallisneri.jpg"
  caption="Complesso Vallisneri"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/Portello.jpg"
  caption="Porta Portello"
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
