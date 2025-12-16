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

I'm an undergraduate student at Nanjing University of Science and Technology, and I will be a PhD student at the Department of Computer Science, Hong Kong University of Science and Technology in fall 2026, supervised by Prof. Shuai Wang.

My research interest includes Trustworthy AI, Large Language Model and Diffusion Model. I have published several papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=bS5yQmwAAAAJ'>google scholar citations <span id='total_cit'>20+</span></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=bS5yQmwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2025.07*: &nbsp;🎉🎉 I got the offer from the School of Computer Science, Peking University at the summer camp.
- *2025.05*: &nbsp;🎉🎉 Our work is online <a href="https://arxiv.org/pdf/2505.14455" target="_blank"><strong>arxiv</strong></a>
- *2024.12*: &nbsp;🎉🎉 Our paper is accepted by <a href="https://ojs.aaai.org/index.php/AAAI/article/view/32377" target="_blank"><strong>AAAI2025</strong></a>, congratulations to our co-authors!

# 📝 Publications 

- **[Arxiv]** [CtrlDiff: Boosting Large Diffusion Language Models with Dynamic Block Prediction and Controllable Generation](https://arxiv.org/pdf/2505.14455), **Chihan Huang**, Hao Tang. <span class='show_paper_citations' data='bS5yQmwAAAAJ:roLk4NBRz8UC'></span>
- **[Arxiv]** [ScoreAdv: Score-based Targeted Generation of Natural Adverarial Examples via Diffusion Models](https://arxiv.org/abs/2507.06078), **Chihan Huang**, Hao Tang, [code](https://github.com/6tonystark6/ScoreAdv). <span class='show_paper_citations' data='bS5yQmwAAAAJ:Se3iqnhoufwC'></span>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/aaai2025-cover.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HUANG: A Robust Diffusion Model-based Targeted Adversarial Attack Against Deep Hashing Retrieval](https://ojs.aaai.org/index.php/AAAI/article/view/32377) [**[Code]**](https://github.com/6tonystark6/HUANG) <strong><span class='show_paper_citations' data='bS5yQmwAAAAJ:LkGwnXOMwfcC'></span></strong>

**Chihan Huang**, Xiaobo Shen

Deep hashing models excel in retrieval but share the vulnerability of deep networks to adversarial attacks. While most attacks focus on classification, few target retrieval models. We propose HUANG, the first black-box targeted adversarial attack for hashing retrieval using a diffusion model. Our method guides the shift from benign to adversarial distributions via adversarial perturbations and a residual image. Experiments show HUANG achieves state-of-the-art performance in black-box targeted attacks across datasets, with strong robustness and transferability due to the dynamic interplay between denoising and perturbation addition.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING 2025</div><img src='images/coling2025-cover.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PoemBERT: A Dynamic Masking Content and Ratio Based Semantic Language Model For Chinese Poem Generation](https://aclanthology.org/2025.coling-main.5.pdf) [**[Code]**](https://github.com/6tonystark6/PoemBERT) <strong><span class='show_paper_citations' data='bS5yQmwAAAAJ:_FxGoFyzp5QC'></span></strong>

**Chihan Huang**, Xiaobo Shen

Ancient Chinese poetry lacks dedicated pre-trained models. We propose PoemBERT, a BERT-based model trained on classical poetry. By incorporating sentiment and pinyin embeddings, along with novel Character Importance-based and dynamic masking strategies, it better captures poetic emotion, imagery, and linguistic nuances. Fine-tuned for tasks like generation and classification, PoemBERT achieves state-of-the-art performance in automated and human evaluations.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING 2025</div><img src='images/icassp2025-cover.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Efficient Multi-branch Black-box Semantic-aware Targeted Attack Against Deep Hashing Retrieval](https://ieeexplore.ieee.org/abstract/document/10889223) [**[Code]**](https://github.com/6tonystark6/EmbSTar) <strong><span class='show_paper_citations' data='bS5yQmwAAAAJ:ufrVoPGSRksC'></span></strong>

**Chihan Huang**, Xiaobo Shen

Deep hashing excels in retrieval but remains vulnerable to adversarial attacks. Existing methods rarely address targeted black-box attacks on these models. We propose EmbSTar, an efficient multi-branch attack framework. It first distills a knockoff model, then uses novel Target Fusion and Adaptation modules to semantically align adversarial images with a target. This enables powerful, query-efficient attacks. Extensive experiments show EmbSTar achieves state-of-the-art performance in targeted black-box scenarios.
</div>
</div>


# 🎖 Honors and Awards
- *2025.12* Top Moral Student at NJUST (Top 0.1%)
- *2024.09* Top Moral Student at NJUST (Top 0.3%)
- *2024.09* Superior Scholarship at NJUST 
- *2024.04* First Prize Scholarship at NJUST 
- *2023.04* First Prize Scholarship at NJUST 

# 📖 Educations
- *2026.09 -  (incoming)*, PhD at Hong Kong University of Science and Technology. 
- *2022.09 - 2026.06*, undergraduate at Nanjing University of Science and Technology. 

/ / # 💬 Invited Tal
/ / / - *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
/ / / - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 🔧 Services
## Conference Reviewer
- AAAI 2026
- NeurIPS 2025
- IJCAI 2025
- IJCNN 2025
- ICWSM 2025

## Journal Reviewer
- IEEE Transactions on Multimedia
- Neurocomputing
- Applied Intelligence
- Pattern Recognition Letters

# 💻 Internships
- *July. 2025 - Sep. 2025*, Research Assistant at [Zayed University](https://www.zu.ac.ae/), UAE.
- *Jan. 2025 - Jun. 2025*, Research Intern at [School of Computer Science, Peking University](https://cs.pku.edu.cn/), China.

# 😋 Interests

Outside of research, I enjoy **playing badminton**, **singing**, **watching TV shows** and **travelling**. I rarely play video games. Some of my favorite singers include *Jay Chou*, *JJ Lin*, *Jason Zhang*, *Joker Xue*, *Shen Zhou*, *G.E.M*, *Ghost Huang* and *Feige Zhou*. That said, I listen to a wide range of music and mostly Mandopop.

My taste in shows is also quite diverse. I like British dramas like *Sherlock*, American series like *The Good Doctor*, and Marvel shows such as *Agents of S.H.I.E.L.D.*, *What If...?*, and *WandaVision*. I also watch Chinese dramas like *Lighter and Princess*, *The Knockout*, and *Blossoms Shanghai*. I enjoy music variety shows too, such as *Singer*, *The Treasured Voice*, and *Melody Journey*.

If you play badminton, hit me up! I’m up for men’s singles, men’s doubles, or mixed doubles (barely tried mixed but always open to trying!).

I'm fond of travelling and I've visited 17 countries so far:
- **Asia** (6): Cambodia, China, Malaysia, Thailand, Turkey, Vietnam
- **Europe** (10): France, Greece, Iceland, Italy, Russia, Spain, Sweden, Switzerland, The United Kingdom, Vatican
- **America** (1): USA
