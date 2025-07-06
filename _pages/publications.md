---
title: "Publications"
layout: page
permalink: /publications/
order: 3
---

# Publications

Below is a comprehensive list of my research publications.

{% for pub in site.data.publications %}
## {{ pub.title }}

**Authors:** {{ pub.authors | join: ", " }}  
**Venue:** {{ pub.venue }} ({{ pub.year }})  
{% if pub.note %}*{{ pub.note }}*{% endif %}

{% if pub.abstract %}
**Abstract:** {{ pub.abstract }}
{% endif %}

**Links:**
{% if pub.url %}[📄 Paper]({{ pub.url }}){% endif %}
{% if pub.code %} • [💻 Code]({{ pub.code }}){% endif %}
{% if pub.slides %} • [📊 Slides]({{ pub.slides }}){% endif %}

---
{% endfor %}
