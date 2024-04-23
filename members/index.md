---
title: Members
nav:
  order: 3
  tooltip: Lab members
---

# {% include icon.html icon="fa-solid fa-users" %}Members

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}
