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

<div class="home-page" markdown="0">

<section class="home-profile home-block" id="about-me">
  <h2 class="home-section-title">About Me</h2>
  <p>I'm currently a fourth-year <strong>PhD student</strong> of Data Science at the <strong>City University of Hong Kong (CityU)</strong> under the advisory of Prof. Xiangyu Zhao. Prior to CityU, I completed my MSc under the advisory of Prof. Danwei Wang at Nanyang Technological University (NTU) in 2022 and my BEng under the advisory of Prof. Shaopeng Dong at Beihang University (BUAA) in 2021.</p>
  <p>My research interest includes <span class="home-tags">Recommender Systems · Large Language Models · Deep Reinforcement Learning · Machine Learning</span>. I have published several papers at the top international AI conferences with <a href="https://scholar.google.com/citations?user=tkis1Q0AAAAJ" target="_self">800+ citations</a>.</p>
</section>

<section class="home-opportunities home-block" id="opportunities">
  <h2 class="home-section-title">Open to Opportunities</h2>
  <p class="home-opportunity-lead"><strong>Expected PhD graduation:</strong> October 2026. Actively seeking opportunities in <strong>Recommender Systems</strong>, <strong>Ads tech</strong> (retrieval/recall, bidding, etc.) and other <strong>LLM-related positions</strong> worldwide. Feel free to <strong>reach out via email</strong>.</p>
</section>

<section class="home-section home-block home-block--news" id="news">
  <h2 class="home-section-title">News</h2>
  <ul class="news-list">
    <li class="news-item">
      <span class="news-date">2026.05</span>
      <span class="news-content">🎉🎉 Our paper "Generative Auto-Bidding in Large-Scale Auctions via Diffusion Completer-Aligner" has been accepted by KDD 2026 ADS Track.</span>
    </li>
    <li class="news-item">
      <span class="news-date">2026.05</span>
      <span class="news-content">🎉🎉 Our paper "Hierarchical Residual Policy Optimization for Generative Recommendations" has been accepted by KDD 2026.</span>
    </li>
    <li class="news-item">
      <span class="news-date">2026.03</span>
      <span class="news-content">🎉🎉 The <a href="https://mp.weixin.qq.com/s/DwKtynzSfsYErgtdWuYOpQ">AML Lab Collaboration Project</a> that I was involved in Ranked No.1 as Kuaishou's "Outstanding Research Collaboration Project"! Congratulations!</span>
    </li>
    <li class="news-item">
    <span class="news-date">2025.09</span>
      <span class="news-content">🎉🎉 Two of our paper has been accepted by WWW'26. Congratulations!</span>
    </li>
    <li class="news-item">
      <span class="news-date">2025.04</span>
      <span class="news-content">🎉🎉 Our paper "Generative Auto-Bidding with Value-Guided Explorations" has been accepted by SIGIR 2025.</span>
    </li>
    <li class="news-item">
      <span class="news-date">2025.02</span>
      <span class="news-content">Our survey "<a href="https://arxiv.org/abs/2502.12448">From Principles to Applications: A Comprehensive Survey of Discrete Tokenizers in Generation, Comprehension, Recommendation, and Information Retrieval</a>" is available on Arxiv. Welcome to cite it.</span>
    </li>
    <li class="news-item">
      <span class="news-date">2024.12</span>
      <span class="news-content">🎉🎉 We achieved <strong>1st place</strong> in the "<a href="https://tianchi.aliyun.com/competition/entrance/532236/">[NeurIPS] 2024 AIGB Track: Learning Auto-Bidding Agent with Generative Models</a>" competition hosted by Alimama over thousands of teams!</span>
    </li>
  </ul>
</section>

<div class="home-card-grid home-block">
  <section class="home-card" id="honors">
    <h2 class="home-card-title">Honors and Awards</h2>
    <div class="award-group">
      <h3 class="award-year">2025</h3>
      <ul>
        <li>Outstanding Academic Performance Award (OAPA-CityU 2025)</li>
        <li>WWW'25 Student Travel Award</li>
      </ul>
    </div>
    <div class="award-group">
      <h3 class="award-year">2024</h3>
      <ul>
        <li><strong>1st place</strong> in the "<a href="https://tianchi.aliyun.com/competition/entrance/532236/">[NeurIPS] 2024 AIGB Track: Learning Auto-Bidding Agent with Generative Models</a>" competition hosted by Alimama over thousands of teams. (Team KGAB)</li>
        <li><strong>2nd place overall</strong> in the "<a href="https://discourse.aicrowd.com/t/announcing-the-winners-of-amazon-kdd-cup-2024/10758">KDD CUP 2024 (Multi-Task Online Shopping Challenge for LLMs)</a>" competition hosted by Amazon. (Group AML666)</li>
        <li>Outstanding Academic Performance Award (OAPA-CityU 2024)</li>
      </ul>
    </div>
    <div class="award-group">
      <h3 class="award-year">2023</h3>
      <ul>
        <li>IJCAI'23 Travel Award</li>
        <li>Research Tuition Scholarship (RTS-CityU 2023)</li>
        <li>Outstanding Academic Performance Award (OAPA-CityU 2023)</li>
      </ul>
    </div>
  </section>

  <section class="home-card" id="experience">
    <h2 class="home-card-title">Professional Experience</h2>
    <ul class="experience-list">
      <li><span class="exp-period">2024.08 – Present</span><span class="exp-role">Research Intern at <strong>Kuaishou</strong></span></li>
      <li><span class="exp-period">2022 – 2024.06</span><span class="exp-role">Research Intern at <strong>Huawei</strong></span></li>
      <li><span class="exp-period">Service</span><span class="exp-role">PC member of CIKM, IJCAI</span></li>
    </ul>
  </section>
</div>

<section class="home-section pub-section home-block home-block--pubs" id="publications">
  <h2 class="home-section-title">Publications</h2>

  <h3 class="pub-subsection-title">Tutorials</h3>
  <div class="pub-list">

    <article class="pub-item">
      <span class="pub-id">[4]</span>
      <div class="pub-body">
        <h4 class="pub-title">Joint Modeling in Deep Recommender Systems</h4>
        <p class="pub-authors">Pengyue Jia, <strong>Jingtong Gao</strong>, Yuhao Wang, Xiaopeng Li, Qidong Liu, Yichao Wang, Bo Chen, Huifeng Guo, Ruiming Tang</p>
        <p class="pub-venue">WWW'25, Proceedings of the ACM Web Conference 2025</p>
        <p class="pub-links"><a href="bibtex/jia2025joint.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">[3]</span>
      <div class="pub-body">
        <h4 class="pub-title">Joint Modeling in Recommendations: Foundations and Frontiers</h4>
        <p class="pub-authors">Xiangyu Zhao, Yichao Wang, Bo Chen, Pengyue Jia, Yuhao Wang, <strong>Jingtong Gao</strong>, Huifeng Guo, Ruiming Tang</p>
        <p class="pub-venue">IJCAI'23, Proceedings of the 32st International Joint Conference on Artificial Intelligence</p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">[2]</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://arxiv.org/abs/2209.10117">Trustworthy Recommender Systems: Foundations and Frontiers</a></h4>
        <p class="pub-authors">Wenqi Fan, Xiangyu Zhao, Lin Wang, Xiao Chen, <strong>Jingtong Gao</strong>, Qidong Liu, Shijie Wang</p>
        <p class="pub-venue">IJCAI'23, Proceedings of the 32nd International Joint Conference on Artificial Intelligence</p>
        <p class="pub-venue">KDD'23, Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining</p>
        <p class="pub-links"><a href="bibtex/fan2023trustworthy.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">[1]</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://arxiv.org/abs/2209.10117">A Comprehensive Survey on Trustworthy Recommender Systems</a></h4>
        <p class="pub-authors">Wenqi Fan, Xiangyu Zhao, Xiao Chen, Jingran Su, <strong>Jingtong Gao</strong>, Lin Wang, Qidong Liu, Yiqi Wang, Han Xu, Lei Chen, Qing Li</p>
        <p class="pub-venue">WWW'23, Companion Proceedings of the Web Conference 2023</p>
        <p class="pub-links"><a href="bibtex/fan2022comprehensive.html">CITE</a></p>
      </div>
    </article>

  </div>

  <h3 class="pub-subsection-title pub-subsection-title--papers">Conference and Journal Papers</h3>
  <div class="pub-list">

    <article class="pub-item">
      <span class="pub-id">C15</span>
      <div class="pub-body">
        <h4 class="pub-title">Generative Auto-Bidding in Large-Scale Auctions via Diffusion Completer-Aligner</h4>
        <p class="pub-authors">Yewen Li, <strong>Jingtong Gao</strong>, Peng Jiang, Ruyi An, Xiangyu Zhao, Bo An, Fei Pan, Qingpeng Cai, Peng Jiang, Kun Gai</p>
        <p class="pub-venue">KDD'26 ADS Track, Proceedings of the 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining</p>
        <div class="pub-badges">
          <span class="pub-badge pub-badge--deployed pub-badge--kuaishou">Deployed online · Kuaishou</span>
        </div>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C14</span>
      <div class="pub-body">
        <h4 class="pub-title">Hierarchical Residual Policy Optimization for Generative Recommendations</h4>
        <p class="pub-authors">Kaifeng Guo, Yiming Yang, <strong>Jingtong Gao</strong>, Guolei Zeng, Fukang Yang, Yukang Liang, Peng Jiang, Qingpeng Cai, Xiangyu Zhao</p>
        <p class="pub-venue">KDD'26, Proceedings of the 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining</p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C13</span>
      <div class="pub-body">
        <h4 class="pub-title">Detecting Miscitation on the Scholarly Web through LLM-Augmented Text-Rich Graph Learning</h4>
        <p class="pub-authors">Huidong Wu, Haojia Xiang, Jingtong Gao, Xiangyu Zhao, Dengsheng Wu and Jianping Li</p>
        <p class="pub-venue">WWW'26, Proceedings of the ACM Web Conference 2026</p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C12</span>
      <div class="pub-body">
        <h4 class="pub-title">BlossomRec: Block-level Fused Sparse Attention Mechanism for Sequential Recommendations</h4>
        <p class="pub-authors">Mengyang Ma, Xiaopeng Li, Wanyu Wang, Zhaocheng Du, Jingtong Gao, Pengyue Jia, Yuyang Ye, Yiqi Wang, Yunpeng Weng, Weihong Luo, Xiao Han and Xiangyu Zhao</p>
        <p class="pub-venue">WWW'26, Proceedings of the ACM Web Conference 2026</p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C11</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://arxiv.org/abs/2412.17374">Scenario-Wise Rec: A Multi-Scenario Recommendation Benchmark</a></h4>
        <p class="pub-authors">Xiaopeng Li, <strong>Jingtong Gao (Co-first author)</strong>, Pengyue Jia, Xiangyu Zhao, Yichao Wang, Wanyu Wang, Yejing Wang, Yuhao Wang, Xiangyu Zhao, Huifeng Guo, Ruiming Tang</p>
        <p class="pub-venue">CIKM'25, Proceedings of the 34th ACM International Conference on Information &amp; Knowledge Management</p>
        <p class="pub-links"><a href="https://github.com/Xiaopengli1/Scenario-Wise-Rec">Github</a> · <a href="bibtex/li2025scenario.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item pub-item--preprint">
      <span class="pub-id">—</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://arxiv.org/abs/2505.17621">Navigate the Unknown: Enhancing LLM Reasoning with Intrinsic Motivation Guided Exploration</a></h4>
        <p class="pub-authors"><strong>Jingtong Gao</strong>, Ling Pan, Yejing Wang, Rui Zhong, Chi Lu, Qingpeng Cai, Peng Jiang, Xiangyu Zhao</p>
        <p class="pub-venue">Arxiv</p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C10</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3726302.3729987">Generative Auto-Bidding with Value-Guided Explorations</a></h4>
        <p class="pub-authors"><strong>Jingtong Gao</strong>, Yewen Li, Shuai Mao, Peng Jiang, Nan Jiang, Yejing Wang, Qingpeng Cai, Fei Pan, Peng Jiang, Kun Gai, Bo An, Xiangyu Zhao</p>
        <p class="pub-venue">SIGIR'25, Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval</p>
        <div class="pub-badges">
          <span class="pub-badge pub-badge--deployed">Deployed online</span>
        </div>
        <p class="pub-links"><a href="bibtex/gao2025generative.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item pub-item--preprint">
      <span class="pub-id">—</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://arxiv.org/abs/2502.12448">From Principles to Applications: A Comprehensive Survey of Discrete Tokenizers in Generation, Comprehension, Recommendation, and Information Retrieval</a></h4>
        <p class="pub-authors">Jian Jia, <strong>Jingtong Gao (Co-first)</strong>, Ben Xue, Junhao Wang, Qingpeng Cai, Quan Chen, Xiangyu Zhao, Peng Jiang, Kun Gai</p>
        <p class="pub-venue">Arxiv</p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C9</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3701716.3715253">SampleLLM: Optimizing Tabular Data Synthesis in Recommendations</a></h4>
        <p class="pub-authors"><strong>Jingtong Gao</strong>, Zhaocheng Du, Xiaopeng Li, Xiangyu Zhao, Yichao Wang, Xiangyang Li, Huifeng Guo, Ruiming Tang</p>
        <p class="pub-venue">WWW'25, Proceedings of the ACM Web Conference 2025</p>
        <div class="pub-badges">
          <span class="pub-badge pub-badge--oral">Oral Presentation</span>
          <span class="pub-badge pub-badge--deployed pub-badge--huawei">Deployed online · Huawei</span>
        </div>
        <p class="pub-links"><a href="bibtex/gao2025samplellm.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C8</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3696410.3714922">LLM4Rerank: LLM-based Auto-Reranking Framework for Recommendations</a></h4>
        <p class="pub-authors"><strong>Jingtong Gao</strong>, Bo Chen, Xiangyu Zhao, Weiwen Liu, Xiangyang Li, Yichao Wang, Wanyu Wang, Huifeng Guo, Ruiming Tang</p>
        <p class="pub-venue">WWW'25, Proceedings of the ACM Web Conference 2025</p>
        <div class="pub-badges">
          <span class="pub-badge pub-badge--oral">Oral Presentation</span>
        </div>
        <p class="pub-links"><a href="bibtex/gao2025llm4rerank.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C7</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3701716.3715226">GAS: Generative Auto-bidding with Post-training Search</a></h4>
        <p class="pub-authors">Yewen Li, Shuai Mao, <strong>Jingtong Gao</strong>, Nan Jiang, Yujian Xu, Qingpeng Cai, Fei Pan, Peng Jiang, Bo An</p>
        <p class="pub-venue">WWW'25, Proceedings of the ACM Web Conference 2025</p>
        <p class="pub-links"><a href="bibtex/li2025gas.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C6</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://arxiv.org/pdf/2406.10244">GLINT-RU: Gated Lightweight Intelligent Recurrent Units for Sequential Recommender Systems</a></h4>
        <p class="pub-authors">Sheng Zhang, Maolin Wang, Wanyu Wang, <strong>Jingtong Gao</strong>, Xiangyu Zhao, Yu Yang, Xuetao Wei, Zitao Liu, Tong Xu</p>
        <p class="pub-venue">KDD'25, Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining</p>
        <p class="pub-links"><a href="bibtex/zhang2025glint.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">J3</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3695461">Multimodal Recommender Systems: A Survey</a></h4>
        <p class="pub-authors">Qidong Liu, Jiaxi Hu, Yutian Xiao, Xiangyu Zhao, <strong>Jingtong Gao</strong>, Wanyu Wang, Qing Li, Jiliang Tang</p>
        <p class="pub-venue">CSUR, ACM Computing Surveys</p>
        <p class="pub-links"><a href="bibtex/liu2024multimodal.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C5</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3627673.3679615">HierRec: Scenario-Aware Hierarchical Modeling for Multi-scenario Recommendations</a></h4>
        <p class="pub-authors"><strong>Jingtong Gao</strong>, Bo Chen, Menghui Zhu, Xiangyu Zhao, Xiaopeng Li, Yuhao Wang, Yichao Wang, Huifeng Guo, Ruiming Tang</p>
        <p class="pub-venue">CIKM'24, Proceedings of the 33nd ACM International Conference on Information &amp; Knowledge Management</p>
        <div class="pub-badges">
          <span class="pub-badge pub-badge--deployed pub-badge--huawei">Deployed online · Huawei</span>
        </div>
        <p class="pub-links"><a href="bibtex/gao2024hierrec.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C4</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://arxiv.org/abs/2209.10117">A Comprehensive Survey on Trustworthy Recommender Systems</a></h4>
        <p class="pub-authors">Wenqi Fan, Xiangyu Zhao, Xiao Chen, Jingran Su, <strong>Jingtong Gao</strong>, Lin Wang, Qidong Liu, Yiqi Wang, Han Xu, Lei Chen, Qing Li</p>
        <p class="pub-venue">IJCAI'23 Tutorial, WWW'23 Tutorial</p>
        <p class="pub-links"><a href="bibtex/fan2022comprehensive.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">J2</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3637871">SMLP4Rec: An Efficient all-MLP Architecture for Sequential Recommendations</a></h4>
        <p class="pub-authors"><strong>Jingtong Gao</strong>, Xiangyu Zhao, Muyang Li, Minghao Zhao, Runze Wu, Ruocheng Guo, Yiding Liu, Dawei Yin</p>
        <p class="pub-venue">TOIS, Transactions on lnformation Systems</p>
        <p class="pub-links"><a href="bibtex/gao2024smlp4rec.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C3</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3539618.3591701">AutoTransfer: Instance Transfer for Cross-Domain Recommendations</a></h4>
        <p class="pub-authors"><strong>Jingtong Gao</strong>, Xiangyu Zhao, Bo Chen, Fan Yan, Huifeng Guo, Ruiming Tang</p>
        <p class="pub-venue">SIGIR'23, Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval</p>
        <p class="pub-links"><a href="bibtex/gao2023autotransfer.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C2</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3539618.3591717">LinRec: Linear Attention Mechanism for Long-term Sequential Recommender Systems</a></h4>
        <p class="pub-authors">Langming Liu, Liu Cai, Chi Zhang, Xiangyu Zhao, <strong>Jingtong Gao</strong>, Wanyu Wang, Yifu Lv, Wenqi Fan, Yiqi Wang, Ming He, Zitao Liu, Qing Li</p>
        <p class="pub-venue">SIGIR'23, Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval</p>
        <p class="pub-links"><a href="bibtex/liu2023linrec.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">C1</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://dl.acm.org/doi/pdf/10.1145/3543507.3583467">Multi-Task Recommendations with Reinforcement Learning</a></h4>
        <p class="pub-authors">Ziru Liu, Jiejie Tian, Qingpeng Cai, Xiangyu Zhao, <strong>Jingtong Gao</strong>, Shuchang Liu, Dayou Chen, Tonghao He, Dong Zheng, Peng Jiang, Kun Gai</p>
        <p class="pub-venue">WWW'23, Proceedings of the ACM Web Conference 2023</p>
        <p class="pub-links"><a href="bibtex/liu2023multi.html">CITE</a></p>
      </div>
    </article>

    <article class="pub-item">
      <span class="pub-id">J1</span>
      <div class="pub-body">
        <h4 class="pub-title"><a href="https://www.emerald.com/insight/content/doi/10.1108/EC-10-2021-0624/full/pdf">DRN-GAN: an integrated deep learning-based health degradation assessment model for naval propulsion system</a></h4>
        <p class="pub-authors"><strong>Jingtong Gao</strong>, Shaopeng Dong, Jin Cui, Mei Yuan, Juanru Zhao</p>
        <p class="pub-venue">Engineering Computations</p>
        <p class="pub-links"><a href="bibtex/gao2022drn.html">CITE</a></p>
      </div>
    </article>

  </div>
</section>

</div>
