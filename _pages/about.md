---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

# About Me

Currently, I am a Research Intern at StepFun, mentored by [Dr. Quan Sun](https://github.com/Quan-Sun). Before that, I was a Research Intern at MSRA, mentored by [Dr. Dong Chen](http://dongchen.pro/). I also closely work with [Jingwei Wu](https://scholar.google.com/citations?user=Gtj6VDYAAAAJ&hl=zh-CN), [Guopeng Li](https://liguopeng0923.github.io), [Ruichuan An](https://arctanxarc.github.io).

My research interests focus on unified understanding and generation in MLLM. Please email me if you want to collaborate on academic research or have any questions.

# 🔥 News

- 2026.02: 🎉Two papers (UNIM and Draco) are accepted by CVPR 2026.

# 📝 Selected Publications <span style="font-size: 0.6em; font-weight: normal; margin-left: 8px;"><a href="https://scholar.google.com/citations?user=8K9DdX0AAAAJ&hl=zh-CN" target="_blank" rel="noopener noreferrer">Full Publications List</a></span>

**CoCo: Code as CoT for Text-to-Image Preview and Rare Concept Generation**

<div style="display: flex; gap: 20px; align-items: flex-start; margin-bottom: 20px;">
  <img src="/images/CoCo.jpg" alt="CoCo" style="width: 200px; flex-shrink: 0;">
  <div>
    <strong>Haodong Li</strong>, Chunmei Qing, Huanyu Zhang, Dongzhi Jiang, Yihang Zou, Hongbo Peng, Dingming Li, Yuhong Dai, ZePeng Lin, Juanxi Tian, Yi Zhou, Siqi Dai
    <br>
    ArXiv, 2026
    <br>
    [<a href="https://arxiv.org">ArXiv</a>]
  </div>
</div>

**GEBench: Benchmarking Image Generation Models as GUI Environments**

<div style="display: flex; gap: 20px; align-items: flex-start; margin-bottom: 20px;">
  <img src="/images/GEBench.png" alt="GEBench" style="width: 200px; flex-shrink: 0;">
  <div>
    <strong>Haodong Li</strong>, Juanxi Tian, Jingwei Wu, Quan Sun, Guopeng Li, Huanyu Zhang, Yanlin Lai, Ruichuan An, Hongbo Peng, Yuhong Dai, Chenxi Li, Chunmei Qing, Zheng Ge, Xiangyu Zhang, Daxin Jiang
    <br>
    ArXiv, 2026
    <br>
    [<a href="https://arxiv.org/pdf/2602.09007">ArXiv</a>] [<a href="https://github.com/stepfun-ai/GEBench">Code</a>] [<a href="https://stepfun-ai.github.io/GEBench/">Page</a>]
  </div>
</div>

**Draco: Draft as CoT for Text-to-Image Preview and Rare Concept Generation**

<div style="display: flex; gap: 20px; align-items: flex-start; margin-bottom: 20px;">
  <img src="/images/Draco.png" alt="Draco" style="width: 200px; flex-shrink: 0;">
  <div>
    Dongzhi Jiang, Renrui Zhang, <strong>Haodong Li</strong>, Zhuofan Zong, Ziyu Guo, Jun He, Claire Guo, Junyan Ye, Rongyao Fang, Weijia Li, Rui Liu, †Hongsheng Li
    <br>
    CVPR 2026 Findings
    <br>
    [<a href="https://arxiv.org/abs/2512.05112">ArXiv</a>] [<a href="https://github.com/CaraJ7/DraCo">Code</a>]
  </div>
</div>

**UNIM: A Unified Any-to-Any Interleaved Multimodal Benchmark**

<div style="display: flex; gap: 20px; align-items: flex-start; margin-bottom: 20px;">
  <img src="/images/UniBench.png" alt="UNIM" style="width: 200px; flex-shrink: 0;">
  <div>
    Yanlin Li, Minghui Guo, Kaiwen Zhang, Shize Zhang, Yiran Zhao, <strong>Haodong Li</strong>, Congyue Zhou, Weijie Zheng, Yushen Yan, Shengqiong Wu, Wei Ji, Lei Cui, †Furu Wei, Hao Fei, Mong-Li Lee, Wynne Hsu
    <br>
    CVPR 2026
    <br>
    [<a href="https://any2any-mllm.github.io/unim/">Page</a>]
  </div>
</div>

# 💻 Experiences

<div style="display: flex; gap: 20px; align-items: center; margin-bottom: 15px;">
  <img src="/images/StepFun.png" alt="StepFun" style="max-width: 80px; max-height: 80px; flex-shrink: 0; object-fit: contain;">
  <div>
    <strong>2025.10 - Present, Research Intern, StepFun, Foundation Model Group</strong>
  </div>
</div>

<div style="display: flex; gap: 20px; align-items: center; margin-bottom: 15px;">
  <img src="/images/MicroSoft.png" alt="MSRA" style="max-width: 80px; max-height: 80px; flex-shrink: 0; object-fit: contain;">
  <div>
    <strong>2025.03 - 2025.09, Research Intern, Microsoft Research Asia (MSRA), Visual Computing Group</strong>
  </div>
</div>

## 🖼️ Gallery

You can zoom images by clicking 🤫

<style>
.gallery-strip {
  display: flex;
  gap: 16px;
  overflow: hidden;
  width: 100%;
}
.gallery-track {
  display: flex;
  gap: 16px;
  animation: gallery-scroll 40s linear infinite; /* slower for smoother loop */
}
.gallery-strip:hover .gallery-track {
  animation-play-state: paused;
}
.gallery-track a { flex: 0 0 auto; }
.gallery-strip img {
  height: auto; /* use natural ratio */
  width: auto;
  max-height: 220px; /* cap size without distortion */
  border-radius: 8px;
}
@media (max-width: 768px) {
  .gallery-strip img { max-height: 140px; }
  .gallery-track { animation-duration: 30s; }
}
@keyframes gallery-scroll {
  0% { transform: translateX(0); }
  100% { transform: translateX(-50%); }
}
</style>

<div class="gallery-strip">
  <div class="gallery-track">
    <a href="/images/msra.jpg" class="image-popup"><img src="/images/msra.jpg" alt="MSRA"></a>
    <a href="/images/nanjing.png" class="image-popup"><img src="/images/nanjing.png" alt="Nanjing"></a>
    <a href="/images/shichahai.jpg" class="image-popup"><img src="/images/shichahai.jpg" alt="Shichahai"></a>
    <a href="/images/guangzhou.jpg" class="image-popup"><img src="/images/guangzhou.jpg" alt="Guangzhou"></a>
    <a href="/images/sichuang.jpg" class="image-popup"><img src="/images/sichuang.jpg" alt="Sichuang"></a>
    <a href="/images/south_korea.jpg" class="image-popup"><img src="/images/south_korea.jpg" alt="South Korea"></a>
    <!-- duplicate set for seamless loop -->
    <a href="/images/msra.jpg" class="image-popup"><img src="/images/msra.jpg" alt="MSRA"></a>
    <a href="/images/nanjing.png" class="image-popup"><img src="/images/nanjing.png" alt="Nanjing"></a>
    <a href="/images/shichahai.jpg" class="image-popup"><img src="/images/shichahai.jpg" alt="Shichahai"></a>
    <a href="/images/guangzhou.jpg" class="image-popup"><img src="/images/guangzhou.jpg" alt="Guangzhou"></a>
    <a href="/images/sichuang.jpg" class="image-popup"><img src="/images/sichuang.jpg" alt="Sichuang"></a>
    <a href="/images/south_korea.jpg" class="image-popup"><img src="/images/south_korea.jpg" alt="South Korea"></a>
  </div>
  
</div>
