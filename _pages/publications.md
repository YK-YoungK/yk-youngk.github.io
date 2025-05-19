---
layout: default
title: "Publications"
permalink: /publications/
author_profile: true
---

# 📝 Publications and Preprints
<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %} -->
\* denotes equal contribution. 


<span class='anchor' id='contextures'></span>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='{{ site.baseurl }}/images/publications/contextures.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[ICML 2025]** [Contextures: Representations from Contexts](https://arxiv.org/abs/2505.01557)

Runtian Zhai, **Kai Yang**, Che-Ping Tsai, Burak Varıcı, Zico Kolter, Pradeep Ravikumar

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

- Establish the contexture theory, which shows many representation learning methods can be characterized as learning from the association between the input and a context variable.
- Demonstrate that many popular methods can approximate the top-d singular functions of the expectation operator induced by the context, which we call the represetnation learns the contexture.
- Prove the representation that learns the contexture are optimal on those tasks that are compatible with the context. Thus, scaling up the model size will finally yields diminishing returns.
- Propose a metric to evaluate the usefulness of a context without knowing the downstream tasks.
</div>
</div>


<span class='anchor' id='precision'></span>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='{{ site.baseurl }}/images/publications/precision.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[ACL 2025 Findings]** [How Numerical Precision Affects Arithmetical Reasoning Capabilities of LLMs](https://arxiv.org/abs/2410.13857)

Guhao Feng\*, **Kai Yang\***, Yuntian Gu, Xinyue Ai, Shengjie Luo, Jiacheng Sun, Di He, Zhenguo Li, Liwei Wang

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

- Identify numerical precision as a key factor influencing the effectiveness of LLMs in arithmetic tasks.
- Theoretically demonstrate that Transformers with low numerical precision fail to address elementary arithmetic tasks such as iterated addition and integer multiplication, unless the model size increases super-polynomially with respect to the input length.
- Theoretically prove that Transformers with standard numerical precision can efficiently handle elementary arithmetic tasks with moderate model sizes.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='{{ site.baseurl }}/images/publications/efficient_Transformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[ICML 2024]** [Do Efficient Transformers Really Save Computation?](https://arxiv.org/abs/2402.13934)

**Kai Yang**, Jan Ackermann, Zhenyu He, Guhao Feng, Bohang Zhang, Yunzhen Feng, Qiwei Ye, Di He, Liwei Wang

- Understand the capabilities and limitations of efficient Transformers, specifically the Sparse Transformer and Linear Transformer on their reasoning capabilities with Chain-of-Thought.
- Theoretically reveal that while these efficient Transformers are expressive enough to perform Chain-of-Thought reasoning, they require a model size that scales with the problem size, which finally offsets their efficiency.
- Theoretically prove that Transformers with standard numerical precision can efficiently handle elementary arithmetic tasks with moderate model sizes.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='{{ site.baseurl }}/images/publications/BiPE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[ICML 2024]** [Two Stones Hit One Bird: Bilevel Positional Encoding for Better Length Extrapolation](https://arxiv.org/abs/2401.16421)

Zhenyu He\*, Guhao Feng\*, Shengjie Luo\*, **Kai Yang**, Liwei Wang, Jingjing Xu, Zhi Zhang, Hongxia Yang, Di He

[[Code](https://github.com/zhenyuhe00/BiPE)]

- Leverage the intrinsic segmentation of language sequences and design a new positional encoding method called Bilevel Positional Encoding (BiPE).
- The intra-segment encoding identifies the locations within a segment and helps the model capture the semantic information via absolute positional encoding. 
- The inter-segment encoding specifies the segment index and models the relationships between segments, aiming to improve extrapolation capabilities via relative positional encoding.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->
