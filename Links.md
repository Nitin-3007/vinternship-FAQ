---
layout: page
title: Important links
permalink: /important_links/
links:
  # Example:
  # - label: "Pinternship GitHub Repository"
  #   url: "https://github.com/sudarshansudarshan/pinternship"
---

[← Back]({{ site.baseurl }}/)

{% if page.links and page.links.size > 0 %}

Below are some important links related to the Pinternship. Please use them as reference whenever needed:

{% for item in page.links %}
- [{{ item.label }}]({{ item.url }})
{% endfor %}

{% else %}

Important links will be shared here when they are available. Please check back later or refer to the announcements and resources shared with you.

{% endif %}

---

[← Back]({{ site.baseurl }}/)