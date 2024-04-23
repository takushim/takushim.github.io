---
title: Contact
nav:
  order: 5
  tooltip: Email, address and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our laboratory is a part of Division of Molecular and Integrative Physiology, Department of Biomedicine, Southern Illinois University (SIU) School of Medicine and located in the second floor of Life Science III building in Carbondale, IL.

{%
  include button.html
  type="email"
  text="tmiyoshi26@siumed.edu"
  link="tmiyoshi26@siumed.edu"
%}
{%
  include button.html
  type="phone"
  text="(618) 453-2931"
  link="+1-618-453-2931"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/G2LpiBGfXgFx3aFp8"
%}

{%
  include figure.html
  image="images/SIU_logos/SIU_Logo_Horz.png"
  width="200px"
  link="https"//siumed.edu/"
%}

{% include section.html %}
{% capture col1 %}
{%
  include figure.html
  image="images/contact/SIU_Campus_Lake.jpg"
  caption="Campus Lake (photo by Devout1145)"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/contact/Pulliam_Hall.jpg"
  caption="Pulliam Hall (photo by Veeresh dandur)"
%}
{% endcapture %}
{% capture col3 %}
{%
  include figure.html
  image="images/contact/Life_Science_III.jpg"
  caption="Lab location (photo by Takushi Miyoshi)"
%}
{% endcapture %}
{% include cols.html col1=col1 col2=col2 col3=col3%}
