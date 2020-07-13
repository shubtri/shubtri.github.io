---
permalink: /policy/
title: "Science & Public Policy"
author_profile: true
redirect_from:
  - /policy/
  - /policy.html
---

I am broadly interested in science and public policy with particular focus on immigration and foreign policy. I am a member of the [National Science Policy Network](https://scipolnetwork.org/) and the [Rice Science Policy Network](https://twitter.com/ricescipol?lang=en). My publications on these issues are listed below.
{% for post in site.policy reversed %}
  {% include archive-single-modified-pub.html %}
{% endfor %}