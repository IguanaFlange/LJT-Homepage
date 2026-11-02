---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first-year PhD candidate at the HKUST NLP Group, Hong Kong University of Science and Technology (HKUST), advised by Prof. Junxian He, who previously advised me during my undergraduate studies at Shanghai Jiao Tong University (SJTU). I graduated from SJTU in June 2024. My research focuses on natural language processing and machine learning.

## Research Interests

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLMs)
- LLM Truthfulness and Interpretability

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024 - Present
- **B.Eng.**, Shanghai Jiao Tong University, 2020 - 2024 (graduated June 2024)

## Research Experience

- **Research Intern**, MINIMAX, February 2025 - Present
- **Research Intern**, Tencent WXG, June 2024 - September 2024; Advisor: Zifei Shan
- **Research Intern**, Shanghai AI Lab, June 2023 - December 2023; Advisor: Prof. Yu Cheng

## Skills

- Natural Language Processing
- Machine Learning
  - LLM Reasoning and Reinforcement Learning
  - Hallucination in Vision-Language Models
  - LLM Truthfulness and Interpretability

## Publications

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Awards

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

## Contact

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
