---
permalink: /publications/
title: "Publications"
author_profile: false
sidebar:
  nav: false
---

My research publications in statistical physics and complex systems.

For citation metrics and an automatically maintained profile, see [Google Scholar](https://scholar.google.com/citations?user=nZ8H4nsAAAAJ&hl=en/) and [ORCID](https://orcid.org/0000-0003-1630-8723).


<br>

---

<br>

## Preprints

{% assign preprints = site.publications | where: "preprint", true | sort: "date" | reverse %}
{% if preprints.size > 0 %}
  {% for pub in preprints %}
### {{ pub.title }}

{{ pub.authors }}

*{{ pub.venue | default: "Preprint" }}*

{% if pub.paperurl %}[Paper]({{ pub.paperurl }}){% endif %}{% if pub.arxiv %}{% if pub.paperurl %} · {% endif %}[arXiv]({{ pub.arxiv }}){% endif %}{% if pub.doi %}{% if pub.paperurl or pub.arxiv %} · {% endif %}[DOI]({{ pub.doi }}){% endif %}

  {% endfor %}
{% else %}
*No current preprints.*
{% endif %}

<br>

## Published Papers

{% assign pubs = site.publications | sort: "date" | reverse %}
{% assign current_year = "" %}

{% for pub in pubs %}
  {% unless pub.preprint %}
    {% assign pub_year = pub.date | date: "%Y" %}
    {% if pub_year != current_year %}
      {% assign current_year = pub_year %}
### {{ current_year }}
    {% endif %}

#### {{ pub.title }}

{{ pub.authors }}

*{{ pub.venue }}*

{% if pub.paperurl %}[Paper]({{ pub.paperurl }}){% endif %}{% if pub.arxiv %}{% if pub.paperurl %} · {% endif %}[arXiv]({{ pub.arxiv }}){% endif %}{% if pub.doi %}{% if pub.paperurl or pub.arxiv %} · {% endif %}[DOI]({{ pub.doi }}){% endif %}

  {% endunless %}
{% endfor %}
