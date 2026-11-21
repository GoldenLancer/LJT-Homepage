---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Junteng Liu is a first-year PhD candidate at the HKUST NLP Group. His research focuses on natural language processing and machine learning.

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–Present.
- **B.Eng.**, Shanghai Jiao Tong University, 2020–2024; graduated in June 2024.

## Honors and Awards

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University.

## Research Experience

- **Research Intern, MINIMAX** (February 2025–Present).
- **PhD Candidate / Researcher, HKUST NLP Group** (2024–Present), supervised by Professor Junxian He, who previously advised Junteng Liu during undergraduate studies at SJTU.
- **Research Intern, Tencent WXG** (June 2024–September 2024), advised by Zifei Shan.
- **Research Intern, Shanghai AI Lab** (June 2023–December 2023), advised by Prof. Yu Cheng.

## Skills and Research Interests

- Natural language processing.
- Machine learning.
- LLM reasoning and reinforcement learning.
- Hallucination in vision-language models.
- LLM truthfulness and interpretability.

## Publications

{% assign cv_publications = site.publications | sort: "order" %}
<ul>
{% for post in cv_publications %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Contact

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://x.com/junteng88716710)
