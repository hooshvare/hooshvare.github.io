---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
nav_order: 1
description: "Hooshvare Research Lab"
permalink: /
---

# Hooshvare Research Lab
{: .fs-9 }

Founded in 2020, Hooshvare team consists of young AI enthusiasts who seek to empower the AI scientific community. Hooshvare strives to produce and provide rich scientific and educational material to individuals as well as organizations with an interdisciplinary mindset. Hooshvare research lab is focused on various AI subjects and is currently carrying out multiple research projects mostly centered around NLP applications.
{: .fs-5 .fw-300 }



## Research Scope

Our research scope entails building AI solutions for localized needs. Most of this effort, for the time being, hinges around building Persian-specific solutions for different NLP tasks and problems. Since the resources for Persian is severely limited, we have made it our mission to fill the gap and enrich this area with strong and credible research resource and materials.

## Research

- [ParsBERT]({{ site.baseurl }}{% link /docs/research/parsbert.md %})


## Open Data

- [Persian Sentiment Analysis]({{ site.baseurl }}{% link /docs/datasets/sentiment_analysis.md %})
- [Persian Text Classification]({{ site.baseurl }}{% link /docs/datasets/text_classification.md %})
- [Persian Named Entity Recognition]({{ site.baseurl }}{% link /docs/datasets/ner.md %})


### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/hooshvare/hooshvare.github.io).

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="64" height="64" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>


### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/hooshvare/hooshvare.github.io/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository.