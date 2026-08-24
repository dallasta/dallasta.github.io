---
permalink: /publications/
title: "Publications"
author_profile: true
---

# Publications

My publications are listed below. The page will be progressively populated from structured publication records.

For the complete and up-to-date list, including citation metrics, please refer to:

- [Google Scholar](https://scholar.google.com/citations?user=LucaDallAsta)
- [ORCID](https://orcid.org/0000-0002-3868-6188)

{% assign pubs = site.publications | sort: "date" | reverse %}
{% for pub in pubs %}
### {{ pub.title }}

{{ pub.authors }}

*{{ pub.venue }}*, {{ pub.date | date: "%Y" }}.

{% if pub.paperurl %}[Paper]({{ pub.paperurl }}){% endif %}
{% if pub.arxiv %} · [arXiv]({{ pub.arxiv }}){% endif %}
{% if pub.doi %} · [DOI]({{ pub.doi }}){% endif %}

{% unless forloop.last %}---{% endunless %}
{% endfor %}
