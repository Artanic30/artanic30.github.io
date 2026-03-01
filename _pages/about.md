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

Hi there! I am a forth-year Ph.D. candidate at ShanghaiTech university's [PLUS](https://plus.sist.shanghaitech.edu.cn) lab, under the mentorship of Prof. [Xuming He](https://faculty.sist.shanghaitech.edu.cn/faculty/hexm/index.html). Previously, I got my B.Sc. degree in 2022 from ShanghaiTech University. I also had the wonderful opportunity to spend time as a research intern at Shanghai AI Lab, supervised by [Dr. Peng Gao](https://scholar.google.com/citations?user=_go6DPsAAAAJ&hl=zh-CN).
I am currently a research intern at **Tencent Youtu Lab**, where I focus on post-training for multimodal document understanding.

My research interest includes Multimodel Learning and Data-centric AI. In pursuit of this goal, my current research work involves **multimodal large language model**, and **post training with RL**.

# 🔥 News

- *2026.02*: &nbsp;🎉🎉 one papers accepted by CVPR 2026
- *2026.01*: &nbsp;🎉🎉 one papers accepted by ICLR 2026
- *2025.12*: &nbsp;🎉🎉 one papers accepted by TMLR 2025
- *2025.12*: I attended the NeurIPS 2025 conference onsite in San Diego and gave a poster presentation.
- *2025.09*: &nbsp;🎉🎉 one papers accepted by NeurIPS 2025
- *2025.01*: &nbsp;🎉🎉 one papers accepted by ICLR 2025
- *2024.07*: &nbsp;🎉🎉 one papers accepted by ECCV 2024
- *2024.05*: &nbsp;🎉🎉 one papers accepted by ICML 2024
- *2024.02*: I attended the AAAI24 conference onsite in Vancouver and gave a poster presentation.
- *2023.12*: &nbsp;🎉🎉 one papers accepted by AAAI 2024
- *2023.06*: I attended the CVPR23 conference onsite in Vancouver and gave a poster presentation.
- *2023.02*: &nbsp;🎉🎉 one papers accepted by CVPR 2023
- *2022.11*: &nbsp;🎉🎉 one papers accepted by AAAI 2023

# 📝 Selected Publications

\*Equal contribution

- [WikiCLIP: An Efficient Contrastive Baseline for Open-domain Visual Entity Recognition]()<br>Shan Ning, **Longtian Qiu**, Jiaxuan Sun, Xuming He, **CVPR 2026**
- [Wiki-R1: Incentivizing Multimodal Reasoning for Knowledge-based VQA via Data and Sampling Curriculum](https://openreview.net/forum?id=TH1Tgbjkm7)<br>Shan Ning, **Longtian Qiu**, Xuming He, **ICLR 2026**
- [DA-DPO: Cost-efficient Difficulty-aware Preference Optimization for Reducing MLLM Hallucinations](https://artanic30.github.io/project_pages/DA-DPO)<br>**Longtian Qiu**, Shan Ning, Chuyu Zhang, Jiaxun Sun, Xuming He, **TMLR 2025**
- [NoisyGRPO: Incentivizing Multimodal CoT Reasoning via Noise Injection and Bayesian Estimation](https://artanic30.github.io/project_pages/NoisyGRPO)<br>**Longtian Qiu**, Shan Ning, Jiaxun Sun, Xuming He, **NeurIPS 2025**
- [Lumina-T2X: Scalable Flow-based Large Diffusion Transformer for Flexible Resolution Generation](https://arxiv.org/pdf/2405.05945)<br>Peng Gao\*, Le Zhuo\*, Dongyang Liu\*, Ruoyi Du\*, Xu Luo\*, **Longtian Qiu\***, Yuhang Zhang, Rongjie Huang, Shijie Geng, Renrui Zhang, Junlin Xie, Wenqi Shao, Zhengkai Jiang, Tianshuo Yang, Weicai Ye, Tong He, Jingwen He, Junjun He, Yu Qiao, Hongsheng Li, **ICLR 2025**
- [SPHINX: The joint mixing of weights, tasks, and visual embeddings for multi-modal large language models](https://arxiv.org/abs/2311.07575)<br>Ziyi Lin\*, Chris Liu\*, Renrui Zhang\*, Peng Gao\*, **Longtian Qiu\***, Han Xiao, Han Qiu, Chen Lin, Wenqi Shao, Keqin Chen, Jiaming Han, Siyuan Huang, Yichi Zhang, Xuming He, Hongsheng Li, Yu Qiao, **ECCV 2024**
- [SPHINX-X: Scaling Data and Parameters for a Family of Multi-modal Large Language Models](https://arxiv.org/abs/2402.05935)<br>Dongyang Liu\*, Renrui Zhang\*, **Longtian Qiu\***, Siyuan Huang\*, Weifeng Lin\*, Shitian Zhao, Shijie Geng, Ziyi Lin, Peng Jin, Kaipeng Zhang, Wenqi Shao, Chao Xu, Conghui He, Junjun He, Hao Shao, Pan Lu, Hongsheng Li, Yu Qiao, Peng Gao, **ICML 2024**
- [Mining Fine-Grained Image-Text Alignment for Zero-Shot Captioning via Text-Only Training](https://arxiv.org/abs/2401.02347)<br>**Longtian Qiu\***, Shan Ning\*, Xuming He, **AAAI 2024**
- [HOICLIP: Efficient Knowledge Transfer for HOI Detection with Vision-Language Models](https://arxiv.org/abs/2303.15786)<br>Shan Ning\*, **Longtian Qiu\***, Xuming He, **CVPR 2023**
- [Calip: Zero-shot enhancement of clip with parameter-free attention](https://arxiv.org/abs/2209.14169)<br>Ziyu Guo\*, Renrui Zhang\*,**Longtian Qiu\***, Xianzheng Ma, Xupeng Miao, Xuming He, Bin Cui, **AAAI 2023**

[//]: # (- [Joint-mae: 2d-3d joint masked autoencoders for 3d point cloud pre-training]&#40;https://arxiv.org/abs/2302.14007&#41;<br>Ziyu Guo, Renrui Zhang, **Longtian Qiu**, Xianzhi Li, Pheng-Ann Heng, **IJCAI 2023**)

[//]: # (# 🎖 Honors and Awards)

[//]: # (- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[//]: # (- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[//]: # (# 💬 Invited Talks)

[//]: # (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]]&#40;https://github.com/&#41;)

[//]: # ()
[//]: # (# 💻 Internships)

[//]: # (- *2019.05 - 2020.02*, [Lorem]&#40;https://github.com/&#41;, China.)

# 📖 Educations

- *2018.09 - 2022.06*, **B.E.** in School of Information Science and Technology, ShanghaiTech University, Shanghai, China
- *2022.09 - now*, **Ph.D.** in School of Information Science and Technology, ShanghaiTech University, Shanghai, China

# 💻 Academic Service

- Reviewer of CVPR 2024~2026, ECCV 2024, NeurIPS 2024~2025, ICLR 2024~2026, ICCV 2025
