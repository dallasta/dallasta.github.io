---
permalink: /publications/
title: "Publications"
author_profile: true
---

# Publications

My research publications in statistical physics and complex systems.

For citation metrics and an automatically maintained profile, see
[Google Scholar](https://scholar.google.com/) and
[ORCID](https://orcid.org/).

{% assign pubs = site.publications | sort: "date" | reverse %}

{% assign current_year = "" %}
{% for pub in pubs %}
  {% assign pub_year = pub.date | date: "%Y" %}
  {% if pub_year != current_year %}
    {% assign current_year = pub_year %}
    {% if forloop.first == false %}

    {% endif %}
## {{ current_year }}
  {% endif %}

### {{ pub.title }}

{{ pub.authors }}

*{{ pub.venue }}*

{% if pub.paperurl %}[Paper]({{ pub.paperurl }}){% endif %}{% if pub.arxiv %} · [arXiv]({{ pub.arxiv }}){% endif %}{% if pub.doi %} · [DOI]({{ pub.doi }}){% endif %}

{% endfor %}
