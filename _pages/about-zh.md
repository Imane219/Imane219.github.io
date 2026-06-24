---
permalink: /zh/
title: ""
excerpt: ""
author_profile: true
---

<span class='anchor' id='about-me'></span>

目前，我就职于**阿里巴巴集团阿里妈妈广告技术部**担任算法工程师，主要致力于多模态内容理解前沿方向的研发工作。

在此之前，我本硕均毕业于**华中科技大学（HUST）**。我于计算机科学与技术学院获得硕士学位，师从**邹逸雄教授**与**李瑞轩教授**；并于网络空间安全学院获得学士学位。

我的核心研究兴趣集中在<u>多模态大语言模型（Multimodal Large Language Models）、视频理解（Video Understanding</u>。在学术研究方面，我曾在 NeurIPS、ICML、CVPR 等国际顶级学术会议上发表 5 篇论文；在本科与硕士阶段两度荣获**国家奖学金（Top 1%）**；并多次在国内外重量级 AI 算法竞赛中斩获全国冠军及亚军。

在工业界深耕的同时，我始终保持对学术探索的热情，并拥有丰富的实习生指导经验（曾作为 **Tech Lead** 带领实习生完成并发表顶会论文）。

目前我们团队正在开放实习生招聘！如果您正在寻找学术合作、工业界机会或实习岗位，欢迎随时通过邮件与我联系：[pp1@alibaba-inc.com](mailto:pp1@alibaba-inc.com)。

<span class='anchor' id='zh-news'></span>

# 🔥 动态
- *2026.05*: &nbsp;🎉 指导实习生完成的两篇论文被 **ICML 2026** 接受！
- *2025.07*: 加入**阿里巴巴集团阿里妈妈广告技术部**，担任算法工程师！
- *2025.06*: 获得**硕士学位**！
- *2024.09*: &nbsp;🎉 一篇论文被 **NeurIPS 2024** 接受！
- *2024.02*: &nbsp;🎉 一篇论文被 **CVPR 2024** 接受！
- *2022.06*: 获得**优秀毕业生**及**荣誉学士学位**称号！

<span class='anchor' id='zh-publications'></span>

# 📝 论文

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='/images/icml26_1.jpg' alt="HiDe" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**HiDe: Rethinking The Zoom-IN method in High Resolution MLLMs via Hierarchical Decoupling**

Xianjie Liu\*, **Yiman Hu\* (Tech Lead)**, Yixiong Zou, Liang Wu, Jian Xu, Bo Zheng

我们发现多模态大语言模型处理高分辨率图像的真正瓶颈是背景干扰而非目标大小。HiDe 通过 Token 级注意力解耦与布局保留解耦，在 V\*Bench 上达到 SOTA（92.1 分），同时降低 75% 显存占用。

[\[论文\]](https://arxiv.org/abs/2510.00054) [\[项目\]](https://tennine2077.github.io/HiDe.github.io/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='/images/icml26_2.jpg' alt="E-VAds" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**E-VAds: An E-commerce Short Videos Understanding Benchmark for MLLMs**

Xianjie Liu\*, **Yiman Hu\* (Tech Lead)**, Liang Wu, Ping Hu, Yixiong Zou, Jian Xu, Bo Zheng

我们构建 E-VAds，首个专门评测多模态大语言模型在转化导向电商短视频理解上的基准，涵盖 3,961 段视频与 5 类共 19,785 个问答对。当前模型在高密度商业内容上表现显著不足；我们的 E-VAds-R1 推理模型在商业意图推理任务上取得 109.2% 的性能增益。

[\[论文\]](https://arxiv.org/abs/2602.08355) [\[项目\]](https://github.com/TaobaoTmall-AlgorithmProducts/E-VAds_Benchmark) [\[模型\]](https://huggingface.co/TaobaoTmall-AlgorithmProducts/E-VAds-R1-Qwen2.5VL) [\[数据\]](https://huggingface.co/datasets/TaobaoTmall-AlgorithmProducts/E-VAds_Benchmark)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='/images/nips24.jpg' alt="NeurIPS2024" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Generate Universal Adversarial Perturbations for Few-Shot Learning**

**Yiman Hu**, Yixiong Zou, Ruixuan Li, Yuhua Li

传统通用对抗扰动因任务偏移与语义偏移在小样本学习中显著失效。我们提出 FSAFW 统一攻击框架，通过对齐代理任务并利用预训练编码器的泛化性，攻击性能超越基线方法 16%。

[\[论文\]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/ba1c5356d9164bb64c446a4b690226b0-Abstract-Conference.html)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neural Networks</div><img src='/images/nn.jpg' alt="NeuralNetworks" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Alleviating Noise Memorization for Adversarially Robust Few-Shot Learning**

**Yiman Hu**, Yixiong Zou, Xiaosen Wang, Yuhua Li, Kun He, Ruixuan Li

小样本对抗训练驱使模型记忆对抗噪声而非学习鲁棒特征，硬标签进一步加剧了过拟合问题。我们提出 ANM，结合自适应标签平滑与鲁棒权重学习，将噪声记忆与鲁棒性解耦，在对抗基准上取得更优泛化性能。

[\[论文\]](https://www.sciencedirect.com/science/article/abs/pii/S0893608025013966)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='/images/cvpr24.jpg' alt="CVPR2024" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Flatten Long-Range Loss Landscapes for Cross-Domain Few-Shot Learning**

Yixiong Zou, Yicong Liu, **Yiman Hu**, Yuhua Li, Ruixuan Li

我们将损失景观分析扩展至表征空间，发现尖锐极值点同时阻碍跨域小样本学习的迁移与微调。仅替换归一化层即可实现长程平坦化，在 8 个数据集上相比最优方法提升最高达 9%。

[\[论文\]](https://arxiv.org/abs/2403.00567)
</div>
</div>

<span class='anchor' id='zh-honors'></span>

# 🎖 荣誉奖项
- *2024.10* 国家奖学金（Top 1%）
- *2024.01* IEEE Cybermatics 第二届国际"Vision Meets Algae"挑战赛亚军（Top 1%）
- *2023.12* 第五届全球人工智能算法精英大赛全国总决赛冠军（Top 1%）
- *2023.07* 2023 星火杯认知大模型场景创新赛全国总决赛第六名
- *2022.06* 优秀毕业生 & 荣誉学士学位（Top 1%）
- *2020.10* 国家奖学金（Top 1%）

<span class='anchor' id='zh-education'></span>

# 📖 教育经历
- *2022.09 - 2025.06*，硕士，计算机科学与技术学院，华中科技大学。导师：邹逸雄教授、李瑞轩教授。
- *2018.09 - 2022.06*，学士，网络空间安全学院，华中科技大学。

<span class='anchor' id='zh-work'></span>

# 💻 工作经历
- *2025.07 - 至今*，算法工程师，阿里巴巴集团阿里妈妈广告技术部，杭州。
- *2024.05 - 2024.09*，算法实习生，阿里巴巴，杭州。
