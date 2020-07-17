---
permalink: /policy/
title: "Science & Public Policy"
author_profile: true
---

I am broadly interested in science and public policy, with a focus on immigration and foreign policy issues as they relate to science. I am a member of the [National Science Policy Network](https://scipolnetwork.org/) (NSPN) and the [Rice Science Policy Network](https://twitter.com/ricescipol?lang=en). My publications on these issues are listed below.
{% for post in site.policy reversed %}
  {% include archive-single-policy-modified.html %}
{% endfor %}