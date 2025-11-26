---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is Ricky Xie (谢睿奇) <a href='https://scholar.google.com/citations?user=MGHImwUAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>, and I am currently a student at Tsinghua University, ZhiLi College, where I am majoring in Mathematical and Physical Sciences with a minor in Computer Science. I am also conducting research at the NICS-EFC Group in the Department of Electronics at Tsinghua University. My research interests include efficient deep learning, computer vision, and the development of efficient attention mechanisms. In the summer of 2025, I will be joining the Efficient Computing Lab at Yale University for a research internship.

In the near future, I will be pursuing a Master's degree in Electronic Information at Tsinghua University, continuing my academic and research journey in the field of advanced technologies.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NuerIPS 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PAROAttention: Pattern-Aware ReOrdering for Efficient Sparse and Quantized Attention in Visual Generation Models](https://arxiv.org/pdf/2506.16054)

Tianchen Zhao, Ke Hong, Xinhao Yang, Xuefeng Xiao, Huixia Li, Feng Ling, **Ruiqi Xie**, Siqi Chen, Hongyu Zhu, Yichong Zhang, Yu Wang

[**Project Page**](https://a-suozhang.xyz/paroattn.github.io/) 
- We analyze key challenges in attention sparsity and low-bit quantization for visual generation models, identifying their common issue as "diverse and scattered" attention patterns.
- Based on the "locality" prior in visual feature extraction, we show that these patterns arise from the tokenization process, which disrupts 3D spatial adjacency. The diverse patterns actually describe local aggregations in 3D space, which can be unified into a "regular and block-based" attention pattern.
- We design a simple "Token Reorder" method to convert diverse attention patterns into a unified, hardware-friendly block pattern. Tailored sparse and quantization strategies are introduced to optimize performance and hardware efficiency. Through CUDA Kernel implementation, PAROAttention achieves 20% densification with INT4 quantization on mainstream video (CogVideo, Wan) and image generation (Flux) models, improving attention and end-to-end acceleration while maintaining generation quality.
</div>
</div>

# 🎖 Honors and Awards
- *2023.09* First Prize, National College Students Mathematics Competition
- *2023.10* Tsinghua University Comprehensive Excellence Scholarship, Good Book Scholarship
- *2024.10* Tsinghua University Comprehensive Excellence Scholarship, Tsinghua Friends - Shenhua Scholarship
- *2025.10* Tsinghua University Comprehensive Excellence Scholarship, Tsinghua Friends - Zhenggerucing Scholarship

# 📖 Educations
- *2022.09 - 2026.07*, Undergraduate Student in Mathematical and Physical Sciences, Tsinghua University
- *2026.09 - Expected*, Master's student in Electronic Information, Tsinghua University

# 💻 Internships
- *2025.07 - 2025.08*, [Efficient Computing Lab](https://www.yecl.org/), Yale University.
