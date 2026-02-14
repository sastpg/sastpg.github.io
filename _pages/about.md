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

# ✨ About Me
**Hello, my name is Kongcheng Zhang (张孔枨)**. I am currently a second-year master student in the [College of Computer Science and Technology](http://www.en.cs.zju.edu.cn/) at [Zhejiang University](https://www.zju.edu.cn/english/) and a member of [VIPA Group](https://www.vipazoo.cn/), supervised by Prof. [Mingli Song](https://scholar.google.com/citations?user=7oLbhAwAAAAJ). In 2024, I received my B.Eng. degree in Computer Science from Zhejiang University and was admitted to persue my M.S. degree in Zhejiang University without entrance examination.

My research filed is **Large Language Models (LLMs)**, particularly focusing on pushing forward the reasoning (*e.g.*, math and instruction following) and agentic (*e.g.*, coding and tool use) capabilities in LLMs through Reinforcement Learning (RL). Please feel free to contact me if you are interested in my research :)

# 📖 Educations
- 2020.06 - Present, [College of Computer Science and Technology, Zhejiang University](http://www.en.cs.zju.edu.cn/), Hangzhou, China
- 2020.09 - 2024.06, [College of Computer Science and Technology, Zhejiang University](http://www.en.cs.zju.edu.cn/), Hangzhou, China


# 📝 Selected Publications 
\* denotes equal contribution.

<ul class="publication-list">
  <li class="pub-item">
      <div class="pub-header">
          <h3 class="pub-title">Replay Failures as Successes: Sample-Efficient Reinforcement Learning for Instruction Following</h3>
          <span class="venue-badge green">Instruction Following</span>
      </div>
      <div class="pub-authors">
          <span class="me">Kongcheng Zhang</span>, Qi Yao, Shunyu Liu, Wenjian Zhang, Min Cen, Yang Zhou, Wenkai Fang, Yiru Zhao, Baisheng Lai, Mingli Song
      </div>
      <p>arXiv preprint arXiv:2512.23457</p>
      <div class="pub-links">
          <a href="https://arxiv.org/abs/2512.23457">PDF</a>
          <a href="https://github.com/sastpg/HIR">Code</a>
      </div>
  </li>

  <li class="pub-item">
      <div class="pub-header">
          <h3 class="pub-title">Consistent Paths Lead to Truth: Self-Rewarding Reinforcement Learning for LLM Reasoning</h3>
          <span class="venue-badge blue">Self Rewarding</span>
      </div>
      <div class="pub-authors">
          <span class="me">Kongcheng Zhang</span>, Qi Yao, Shunyu Liu, Yingjie Wang, Baisheng Lai, Jieping Ye, Mingli Song, Dacheng Tao
      </div>
      <p>Advances in Neural Information Processing Systems (<b>NeurIPS</b>), 2025</p>
      <div class="pub-links">
          <a href="https://arxiv.org/abs/2506.08745">PDF</a>
          <a href="https://github.com/sastpg/CoVo">Code</a>
      </div>
  </li>

  <li class="pub-item">
      <div class="pub-header">
          <h3 class="pub-title">Reasoning with Reinforced Functional Token Tuning</h3>
          <span class="venue-badge blue">Math Reasoning</span>
      </div>
      <div class="pub-authors">
          <span class="me">Kongcheng Zhang</span>, Qi Yao, Baisheng Lai, Jiaxing Huang, Wenkai Fang, Dacheng Tao, Mingli Song, Shunyu Liu
      </div>
      <p>International Conference on Learning Representations (<b>ICLR</b>), 2026</p>
      <div class="pub-links">
          <a href="https://arxiv.org/abs/2502.13389">PDF</a>
          <a href="https://github.com/sastpg/RFTT">Code</a>
      </div>
  </li>

  <li class="pub-item">
      <div class="pub-header">
          <h3 class="pub-title">Odyssey: Empowering Minecraft Agents with Open-World Skills</h3>
          <span class="venue-badge purple">Agent Skill</span>
      </div>
      <div class="pub-authors">
          Shunyu Liu<sup>*</sup>, Yaoru Li<sup>*</sup>, <span class="me">Kongcheng Zhang<sup>*</sup></span>, Zhenyu Cui<sup>*</sup>, Wenkai Fang<sup>*</sup>, Yuxuan Zheng, Tongya Zheng, Mingli Song
      </div>
      <p>International Joint Conference on Artificial Intelligence (<b>IJCAI</b>), 2025</p>
      <div class="pub-links">
          <a href="https://arxiv.org/abs/2407.15325">PDF</a>
          <a href="https://github.com/zju-vipa/Odyssey">Code</a>
      </div>
  </li>

  <li class="pub-item">
      <div class="pub-header">
          <h3 class="pub-title">SeRL: Self-Play Reinforcement Learning for Large Language Models with Limited Data</h3>
          <span class="venue-badge blue">Self Play</span>
      </div>
      <div class="pub-authors">
          Wenkai Fang, Shunyu Liu, Yang Zhou, <span class="me">Kongcheng Zhang</span>, Tongya Zheng, Kaixuan Chen, Mingli Song, Dacheng Tao
      </div>
      <p>Advances in Neural Information Processing Systems (<b>NeurIPS</b>), 2025</p>
      <div class="pub-links">
          <a href="https://arxiv.org/abs/2505.20347">PDF</a>
          <a href="https://github.com/wantbook-book/SeRL">Code</a>
      </div>
  </li>

  <li class="pub-item">
      <div class="pub-header">
          <h3 class="pub-title">MUSE: MCTS-Driven Red Teaming Framework for Enhanced Multi-Turn Dialogue Safety in Large Language Models</h3>
          <span class="venue-badge pink">Safety</span>
      </div>
      <div class="pub-authors">
          Siyu Yan, Long Zeng, Xuecheng Wu, Chengcheng Han, <span class="me">Kongcheng Zhang</span>, Chong Peng, Xuezhi Cao, Xunliang Cai, Chenjuan Guo
      </div>
      <p>Empirical Methods in Natural Language Processing (<b>EMNLP</b>), 2025</p>
      <div class="pub-links">
          <a href="https://arxiv.org/abs/2509.14651">PDF</a>
          <a href="https://github.com/yansiyu02/MUSE">Code</a>
      </div>
  </li>

  <li class="pub-item">
      <div class="pub-header">
          <h3 class="pub-title">Breaking the Exploration Bottleneck: Rubric-Scaffolded Reinforcement Learning for General LLM Reasoning</h3>
          <span class="venue-badge green">Rubrics</span>
      </div>
      <div class="pub-authors">
          Yang Zhou, Sunzhu Li, Shunyu Liu, Wenkai Fang, <span class="me">Kongcheng Zhang</span>, Jiale Zhao, Jingwen Yang, Yihe Zhou, Jianwei Lv, Tongya Zheng, Hengtong Lu, Wei Chen, Yan Xie, Mingli Song
      </div>
      <p>arXiv preprint arXiv:2508.16949</p>
      <div class="pub-links">
          <a href="https://arxiv.org/abs/2508.16949">PDF</a>
          <a href="https://github.com/IANNXANG/RuscaRL">Code</a>
      </div>
  </li>
</ul>


# 💬 Academic Services
Reviewer: ICLR 2026, ICML 2026
