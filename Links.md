---
layout: page
title: Important links
permalink: /link/
links:
    - label: "Dashboard Sheet"
      url: "https://docs.google.com/spreadsheets/d/1J0U2-pzfBpfyY9-31lGgVB284gix8KkEeFTdT64qzAo/edit?usp=sharing"
    - label: "HP Master sheet"
      url: "https://docs.google.com/spreadsheets/d/1H3FVi3JFhw1qol7S7vdYIKzeYfKlGg84eby0psuoQPg/edit?usp=sharing"
    - label: "Activities Document"
      url: "https://writer.zoho.in/writer/open/tk5iv6abecfc364de41289e542b876c05f3e0"
    - label: "Milestones Document"
      url: "https://writer.zoho.in/writer/open/tk5iv07e84d64c700499b9023cd251b66ebc9"
---

[← Back]({{ site.baseurl }}/)

{% if page.links and page.links.size > 0 %}

Below are some important links related to the Pinternship. Please use them as reference whenever needed:

{% for item in page.links %}
- [{{ item.label }}]({{ item.url }}){:target="_blank"}
{% endfor %}

{% else %}

Important links will be shared here when they are available. Please check back later or refer to the announcements and resources shared with you.

{% endif %}

---

[← Back]({{ site.baseurl }}/)