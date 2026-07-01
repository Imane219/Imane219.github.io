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

I am currently an Algorithm Engineer at **Alimama Advertising Technology Department, Alibaba Group**, focusing on multimodal understanding.

Prior to this, I received my **B.S.** and **M.S.** degrees from **Huazhong University of Science and Technology (HUST)**, where I was advised by **Prof. Yixiong Zou** and **Prof. Ruixuan Li**.

My primary research interests include <u>Multimodal Large Language Models and Video Understanding</u>. I have published 5 papers at top-tier international conferences, including NeurIPS, ICML, and CVPR. During my undergraduate and graduate studies, I was twice awarded the <u>National Scholarship (Top 1%)</u>. I have also won national championships and runner-up awards <u>in major AI algorithm competitions (Top 1%)</u>.

I remain highly active in academic research, with extensive experience mentoring interns and guiding them to top-tier conference publications. I continue to serve as a **Tech Lead** to support interns in pursuing high-quality research.

If you are interested in academic collaboration, industry opportunities, or internship positions, please feel free to contact me at [pp1@alibaba-inc.com](mailto:pp1@alibaba-inc.com). **We are hiring interns!**

# 🔥 News
- *2026.05*: &nbsp;🎉 Two papers under my mentorship are accepted to **ICML 2026**!
- *2025.07*: I join **Alibaba Group** as an Algorithm Engineer!
- *2025.06*: I receive my **Master's degree** from HUST!
- *2024.09*: &nbsp;🎉 One paper is accepted by **NeurIPS 2024**!
- *2024.02*: &nbsp;🎉 One paper is accepted by **CVPR 2024**!
- *2022.06*: I receive the **Outstanding Graduate** and **Honor Bachelor's Degree** from HUST!

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/icml26_1.jpg' alt="HiDe" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**HiDe: Rethinking The Zoom-IN method in High Resolution MLLMs via Hierarchical Decoupling**

Xianjie Liu\*, **Yiman Hu\* (Tech Lead, Corresponding Author)**, Yixiong Zou, Liang Wu, Jian Xu, Bo Zheng

We discover the real bottleneck of MLLMs on high-resolution images is background interference rather than object size. HiDe uses Token-level Attention Decoupling and Layout Preservation Decoupling to achieve SOTA on V\*Bench (92.1) with 75% memory reduction.

[\[Paper\]](https://arxiv.org/abs/2510.00054) [\[Project\]](https://tennine2077.github.io/HiDe.github.io/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/icml26_2.jpg' alt="E-VAds" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**E-VAds: An E-commerce Short Videos Understanding Benchmark for MLLMs**

Xianjie Liu\*, **Yiman Hu\* (Tech Lead, Corresponding Author)**, Liang Wu, Ping Hu, Yixiong Zou, Jian Xu, Bo Zheng

We build E-VAds, the first benchmark for evaluating MLLMs on conversion-oriented e-commerce short video understanding, covering 3,961 videos and 19,785 QA pairs across 5 tasks. Current MLLMs struggle significantly on high-density commercial content; our E-VAds-R1 reasoning model achieves a 109.2% gain on commercial intent reasoning.

[\[Paper\]](https://arxiv.org/abs/2602.08355) [\[Project\]](https://github.com/TaobaoTmall-AlgorithmProducts/E-VAds_Benchmark) [\[Model\]](https://huggingface.co/TaobaoTmall-AlgorithmProducts/E-VAds-R1-Qwen2.5VL) [\[Data\]](https://huggingface.co/datasets/TaobaoTmall-AlgorithmProducts/E-VAds_Benchmark)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/nips24.jpg' alt="NeurIPS2024" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Generate Universal Adversarial Perturbations for Few-Shot Learning**

**Yiman Hu**, Yixiong Zou, Ruixuan Li, Yuhua Li

Traditional Universal Adversarial Perturbations (UAPs) fail in few-shot learning due to task shift and semantic shift. We propose FSAFW, a unified attack framework that aligns proxy tasks and leverages pre-trained encoder generalizability, exceeding baseline attack performance by over 16%.

[\[Paper\]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/ba1c5356d9164bb64c446a4b690226b0-Abstract-Conference.html)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neural Networks</div><img src='images/nn.jpg' alt="NeuralNetworks" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Alleviating Noise Memorization for Adversarially Robust Few-Shot Learning**

**Yiman Hu**, Yixiong Zou, Xiaosen Wang, Yuhua Li, Kun He, Ruixuan Li

Adversarial training in few-shot learning drives models to memorize adversarial noise rather than learning robust features, with hard labels further exacerbating overfitting. We propose ANM (Adaptive Label Smoothing + Robust Weight Learning) to decouple noise memorization from robustness, outperforming current adversarial benchmarks.

[\[Paper\]](https://www.sciencedirect.com/science/article/abs/pii/S0893608025013966)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/cvpr24.jpg' alt="CVPR2024" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Flatten Long-Range Loss Landscapes for Cross-Domain Few-Shot Learning**

Yixiong Zou, Yicong Liu, **Yiman Hu**, Yuhua Li, Ruixuan Li

We extend loss landscape analysis to representation space, revealing sharp minima simultaneously impede transferability and fine-tuning in cross-domain few-shot learning. A lightweight normalization layer achieves long-range flattening with up to 9% improvement over state-of-the-art across 8 datasets.

[\[Paper\]](https://arxiv.org/abs/2403.00567)
</div>
</div>

# 🎖 Honors and Awards
- *2024.10* National Scholarship (Top 1%)
- *2024.01* Runner-up, IEEE Cybermatics 2nd International "Vision Meets Algae" Challenge (Top 1%)
- *2023.12* 1st Place, 5th Global AI Algorithm Elite Competition National Finals (Top 1%)
- *2023.07* 6th Place, 2023 Spark Cup Cognitive Large Model Scene Innovation Competition National Finals (Top 6%)
- *2022.06* Outstanding Graduate & Honor Bachelor's Degree (Top 1%)
- *2020.10* National Scholarship (Top 1%)

# 📖 Educations
- *2022.09 - 2025.06*, M.S., School of Computer Science and Technology, Huazhong University of Science and Technology (HUST). Advised by Prof. Yixiong Zou and Prof. Ruixuan Li.
- *2018.09 - 2022.06*, B.S., School of Cyber Science and Engineering, Huazhong University of Science and Technology (HUST).

# 💻 Work Experience
- *2025.07 - present*, Algorithm Engineer, Alimama Advertising Technology Department, Alibaba Group.
- *2024.05 - 2024.09*, Summer Intern, Alibaba.
