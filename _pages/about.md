---
permalink: /
title: "Welcome to Fangxin Liu's Homepage~"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  /* 现代克制学术风：去掉多余边框、阴影与复杂渐变 */
  .pub-container { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; color: #333; line-height: 1.6; }
  
  /* 开放式统计看板：无框大呼吸感 */
  .stats-board {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    margin: 25px 0;
    padding: 15px 0;
    border-top: 1px solid #eee;
    border-bottom: 1px solid #eee;
  }
  .stat-card { text-align: center; border-right: 1px solid #eee; }
  .stat-card:last-child { border-right: none; }
  .stat-num {
    display: block;
    font-size: 28px;
    font-weight: 700;
    color: #538F79;
    line-height: 1.2;
  }
  .stat-label {
    display: block;
    font-size: 13px;
    font-weight: 600;
    color: #222;
    margin-top: 4px;
  }
  .stat-sub {
    font-size: 11px;
    color: #777;
    margin-top: 2px;
    display: block;
  }

  /* News 列表：去掉背景色块，利用字重和间距制造高级感 */
  .news-box { margin-top: 15px; }
  .news-item {
    display: flex;
    margin-bottom: 16px;
    align-items: flex-start;
  }
  .news-date {
    font-size: 13px;
    font-weight: 600;
    color: #666;
    min-width: 105px;
    flex-shrink: 0;
    padding-top: 2px;
  }
  .news-text { font-size: 14.5px; flex: 1; color: #333; line-height: 1.5; }
  .news-text a { color: #538F79; text-decoration: none; font-weight: 600; }
  .news-text a:hover { text-decoration: underline; }
  
  summary { cursor: pointer; color: #538F79; font-weight: 600; padding: 8px 0; outline: none; font-size: 14px; }

  /* 学术红高亮 */
  .highlight-award { color: #b30000; font-weight: 600; }

  /* 研究方向精简版 */
  .res-compact-container { margin-top: 15px; }
  .res-group-compact { margin-bottom: 16px; }
  .res-title-compact { font-size: 15px; font-weight: 700; color: #111; margin-bottom: 4px; }
  .res-sub-list { list-style-type: circle; padding-left: 18px; margin: 0; }
  .res-item-compact { font-size: 13px; color: #333; margin: 4px 0; }
  /* 压低括号内文献的视觉权重，让出主线视线 */
  .res-pub-compact { color: #666; font-size: 12.5px; margin-left: 6px; }
  
  .bili-video-btn-micro {
    display: inline-flex;
    align-items: center;
    color: #00A1D6 !important;
    text-decoration: none;
    font-size: 11px;
    font-weight: 600;
    border: 1px solid rgba(0, 161, 214, 0.2);
    padding: 0px 4px;
    border-radius: 2px;
    margin-left: 6px;
  }
  
  @media (max-width: 768px) {
    .stats-board { grid-template-columns: 1fr 1fr; gap: 16px; }
    .stat-card:nth-child(even) { border-right: none; }
    .news-item { flex-direction: column; }
    .news-date { margin-bottom: 4px; }
  }
</style>
Fangxin (Leon) Liu is an **Assistant Professor** and **Ph.D. Supervisor** in the School of Computer Science at **Shanghai Jiao Tong University (SJTU)**. He is a core member of the [Scalable Computing and Systems Lab](https://www.cs.sjtu.edu.cn/yjjg/818.html), collaborating closely with Prof. [Haibing Guan](https://www.cs.sjtu.edu.cn/jiaoshiml/guanhaibing.html) and Prof. [Li Jiang](https://www.cs.sjtu.edu.cn/jiaoshiml/jiangli.html). He also serves as a Research Fellow at the **Shanghai Qi Zhi Institute**. 

His research focuses on **computer architecture and hardware-software co-design for efficient AI systems**, particularly for LLM/VLM, Computing-in-Memory (CIM/PIM) architectures, and Brain-inspired Computing. 

Dr. Liu has published over **60 papers**, including **40+ in CCF Tier-1** venues (e.g., *ISCA, MICRO, ASPLOS, HPCA, PPoPP*). His work has been recognized with the <span class="highlight-award">Best Paper Finalist at ISCA 2026</span>, the <span class="highlight-award">Outstanding Paper Award at ACM MM 2025 (Systems Theme)</span>, the <span class="highlight-award">Best Paper Award at DATE 2022</span>, and the **HUAWEI Spark Award (火花奖)**.


<div class="stats-board">
  <div class="stat-card">
    <span class="stat-num">40+</span>
    <span class="stat-label">CCF Tier A</span>
    <span class="stat-sub">1st / Corr. Author</span>
  </div>
  <div class="stat-card">
    <span class="stat-num">60+</span>
    <span class="stat-label">Total Pubs</span>
    <span class="stat-sub">1st / Corr. Author</span>
  </div>
  <div class="stat-card">
    <span class="stat-num">40%</span>
    <span class="stat-label">Cost Saved</span>
    <span class="stat-sub">Applied at Huawei, Ant, etc.</span>
  </div>
  <div class="stat-card">
    <span class="stat-num">6+</span>
    <span class="stat-label">Major Awards</span>
    <span class="stat-sub">Best Paper / Dissert.</span>
  </div>
</div>

His architectural and system solutions have been deployed by leading technology companies, including <font color=538F79><b>Huawei, Ant Group, ZTE, and Yizhu Tech.</b></font>, resulting in up to **40% computational cost reductions** in large-scale AI deployments.

---

### 🔥 Recruitment
Our [team](https://www.cs.sjtu.edu.cn/yjjg/818.html) is actively seeking self-motivated **PhD, Master, and Undergraduate students** interested in Computer Architecture, Efficient AI acceleration, and PIM Design. If you are interested, please [email me](mailto:liufangxin@sjtu.edu.cn) your CV.

---

### News
<div class="news-box">

<div class="news-item">
<span class="news-date">Apr. 27, 2026</span>
<div class="news-text">🏆 <b>Best Paper Candidate</b>: Our paper "<b>COMET</b>: A Cooperative Scheduling Framework for Concurrent PIM/CPU Execution on Mobile Devices" has been selected as one of the <b>five finalists for the Best Paper Award at ISCA 2026</b>. Congratulations to Yilong and all co-authors on this prestigious honor!</div>
</div>

<div class="news-item">
  <span class="news-date">Apr. 14, 2026</span>
  <div class="news-text">🛠️ Our high-performance <b>Attention Sparse Acceleration Kernels</b> have been officially integrated into the <b>Huawei CANN</b> (Compute Architecture for Neural Networks) software stack. Furthermore, our team has successfully passed the <b>CANN Core Developer Certification</b>, marking a significant step in bridging architectural research with large-scale industrial infrastructure.</div>
</div>

<div class="news-item">
  <span class="news-date">Apr. 06, 2026</span>
  <div class="news-text">🚀 <b>ACL 2026</b>: Our paper (<b>CSD</b>) on <b>Speculative Decoding Acceleration</b> has been accepted to the ACL 2026 Main Conference. Congratulations to <b>Xuwen</b> and all co-authors!</div>
</div>

<div class="news-item">
  <span class="news-date">Mar. 28, 2026</span>
  <div class="news-text">🚀 <b>ISCA 2026</b>: Three papers covering Sparse Matrix Multiplication (<b>Harmonia</b>), MoE Inference Optimization (<b>STEP</b>), and Mobile PIM/CPU Scheduling (<b>COMET</b>) have been accepted to the 53rd International Symposium on Computer Architecture. Congratulations to Jingkui, Ning, Yilong, and all co-authors!</div>
</div>

<div class="news-item">
  <span class="news-date">Feb. 24, 2026</span>
  <div class="news-text">🚀 Five papers covering Neuromorphic Computing, 3DGS, MoE and PCIe Simulation have been accepted to <b>DAC 2026</b>. Congratulations to Haomin, Chenyang, Zhibai and all co-authors!</div>
</div>

<div class="news-item">
  <span class="news-date">Feb. 04, 2026</span>
  <div class="news-text">📄 Our joint technical report with Huawei MindSpore team, <b>HyperOffload</b>, is released. It cuts peak memory by 26% with end-to-end performance lossless. arXiv: <a href="http://arxiv.org/abs/2602.00748">2602.00748</a></div>
</div>

<div class="news-item">
  <span class="news-date">Jan. 24, 2026</span>
  <div class="news-text">📄 Our paper "NICE: Deep Neural Network Acceleration via Hardware-Friendly Index Assisted Compression" has been accepted to <b>ACM TACO 2026</b>.</div>
</div>

<div class="news-item">
  <span class="news-date">Jan. 21, 2026</span>
  <div class="news-text">🏆 Our work “TFLOP” has received the <a href="https://mp.weixin.qq.com/s/rLS4hiEnpIpnJWj6FWYikg"><b>Special Feature Award</b></a> at the ASP-DAC University LSI Design Contest 2026.</div>
</div>

<div class="news-item">
  <span class="news-date">Nov. 26, 2025</span>
  <div class="news-text">📄 Our two papers on MoE memory bottleneck and 3DGS rendering have been accepted to <b>ASPLOS 2026</b>.</div>
</div>

<div class="news-item">
  <span class="news-date">Nov. 11, 2025</span>
  <div class="news-text">📄 Two papers on graph-based memory and sparse Transformer acceleration accepted to <b>PPoPP 2026</b>.</div>
</div>

<div class="news-item">
  <span class="news-date">Nov. 11, 2025</span>
  <div class="news-text">📄 Three papers on Modular Multiplication, LLM, and CPU-GPU computing accepted to <b>DATE 2026</b>.</div>
</div>

<div class="news-item">
  <span class="news-date">Nov. 10, 2025</span>
  <div class="news-text">🏆 <b>ASTER</b> awarded <a href="https://acmmm2025.org/awards/"><b>Outstanding Paper</b></a> in Systems Theme at ACM MM 2025.</div>
</div>

<details>
<summary>🕒 Click to view all Archived News (2025 - 2022)</summary>
<br>

<div class="news-item"><span class="news-date">Nov. 08, 2025</span><div class="news-text">📄 Two papers on 3DGS Acceleration accepted to <b>HPCA 2026</b>.</div></div>
<div class="news-item"><span class="news-date">Nov. 08, 2025</span><div class="news-text">📄 Paper "SpecQuant" accepted to <b>AAAI 2026</b>.</div></div>
<div class="news-item"><span class="news-date">Oct. 11, 2025</span><div class="news-text">🏆 Won <a href="https://mp.weixin.qq.com/s/wZfZkDkeL2mrB8OWYXd4Jw"><b>First & Third Prize</b></a> in the 2nd <a href="https://mp.weixin.qq.com/s/uk7T5agpwqQtEFaLGzAyNA">Chiplet Technology</a> Open Source Competition.</div></div>
<div class="news-item"><span class="news-date">Sep. 20, 2025</span><div class="news-text">🏆 Won <a href="https://mp.weixin.qq.com/s/UflGd8325kiKbmE-lA9o6A"><b>Grand Prize and Best Project Poster Award</b></a> in CCF Sys2025 Graph Computing Competition.</div></div>
<div class="news-item"><span class="news-date">Sep. 05, 2025</span><div class="news-text">📄 Paper "BLADE" on DRAM-based LLM Acceleration accepted to <a href="https://www.aspdac.com/aspdac2026"><b>ASP-DAC 2026</b></a>.</div></div>
<div class="news-item"><span class="news-date">Aug. 29, 2025</span><div class="news-text">📰 "FlexQuant" framework reported by <a href="https://mp.weixin.qq.com/s/E3WQiKRk5-jLML5Mg0jEgw"><b>Ant Group Asystem Team</b></a>.</div></div>
<div class="news-item"><span class="news-date">Aug. 21, 2025</span><div class="news-text">📄 Paper on Flexible Quantization for LLM accepted to <b>EMNLP 2025</b>.</div></div>
<div class="news-item"><span class="news-date">Jul. 06, 2025</span><div class="news-text">📄 Adaptive Dynamic Layer-skipping Framework for LLM accepted to <b>ACM MM (Oral) 2025</b>.</div></div>
<div class="news-item"><span class="news-date">Jul. 01, 2025</span><div class="news-text">📄 Three papers on PIM-LLM, circuit optimization, and PCIe tracing accepted to <b>ICCAD 2025</b>.</div></div>
<div class="news-item"><span class="news-date">May. 03, 2025</span><div class="news-text">📄 Paper on "Collision Detection Accelerator Based on RRAM-TCAMs" accepted to <b>IEEE TCAD 2025</b>.</div></div>
<div class="news-item"><span class="news-date">Apr. 29, 2025</span><div class="news-text">📄 Two papers on "PIM+NeRF" and "PIM+Database" accepted by <b>ASPLOS 2026</b>.</div></div>
<div class="news-item"><span class="news-date">Aug. 26, 2024</span><div class="news-text">💰 Received grant from <b>NSFC Youth Fund</b> for Adaptive Compression Encoding.</div></div>
<div class="news-item"><span class="news-date">Jul. 06, 2024</span><div class="news-text">🏆 Received <b>2023 ACM Shanghai Doctoral Dissertation Award</b>.</div></div>
<div class="news-item"><span class="news-date">Mar. 18, 2024</span><div class="news-text">🏆 Received <b>2023 Shanghai CCF Outstanding Dissertation Award</b>.</div></div>
<div class="news-item"><span class="news-date">Dec. 29, 2023</span><div class="news-text">📰 "SPARK" framework reported in <a href="https://mp.weixin.qq.com/s/SvLTyAyY8mZEmPL4OZ5Bcw"><b>Jiqizhixin (机器之心)</b></a>.</div></div>
<div class="news-item"><span class="news-date">Nov. 18, 2022</span><div class="news-text">📄 Paper "SIMSnn" accepted by <b>DATE 2023</b>.</div></div>

</details>

</div>

---

### 🔬 Research Interests
His research focuses on Hardware-Software Co-design for efficient AI systems:

<div class="res-compact-container">

  <!-- Focus 1: 大模型与神经网络加速栈 -->
  <div class="res-group-compact">
    <span class="res-title-compact">🚀 LLMs & Neural Network Acceleration</span>
    <ul class="res-sub-list">
      <li class="res-item-compact"><b>Algorithm-System Co-optimization & AI Deployment</b> <span class="res-pub-compact">[ACL'26, ASPLOS'25, EMNLP'25, <span class="highlight-award">ACM MM’25 (Outstanding Paper)</span>, ISCA’25, ASP-DAC’25]</span></li>
      <li class="res-item-compact"><b>Execution & Micro-architecture Optimization</b> <span class="res-pub-compact">[ISCA'26, <span class="highlight-award">LSI’25 Feature Awards</span>, TACO'26, HPCA'25, HPCA'24, 2×DATE’25, TPDS’24, ASP-DAC’24, DAC’26]</span></li>
      <li class="res-item-compact"><b>Sparsity Compilation & Efficient Encoding Acceleration</b> <span class="res-pub-compact">[PPoPP'26, HPCA’25, HPCA’24, DAC’24, ICCAD’25, TODAES’24, ASP-DAC’24]</span></li>
    </ul>
  </div>

  <!-- Focus 2: 存内计算 -->
  <div class="res-group-compact">
    <span class="res-title-compact">💾 Computing-in-Memory (CiM/PIM) Architecture</span>
    <ul class="res-sub-list">
      <li class="res-item-compact"><b>Hardware-Algorithm Co-design & PIM Scheduling</b> <span class="res-pub-compact">[<span class="highlight-award">ISCA’26 (Best Paper Finalist)</span>, ICCAD'25, MICRO’24, ASP-DAC’24, APPT’25, <span class="highlight-award">DATE’22 (Best Paper)</span>]</span></li>
    </ul>
  </div>

  <!-- Focus 3: 空间智能 -->
  <div class="res-group-compact">
    <span class="res-title-compact">👁️ Spatial Intelligence (Efficient 3D Perception & Rendering)</span>
    <ul class="res-sub-list">
      <li class="res-item-compact"><b>3D Scene Reconstruction & Rendering Acceleration</b> <span class="res-pub-compact">[HPCA’26, ASPLOS’25, DAC’26]</span> <a href="https://www.bilibili.com/video/BV1w5L265ESd/" target="_blank" class="bili-video-btn-micro"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="1em" height="1em" fill="currentColor" style="vertical-align: -0.15em; margin-right: 0.2em;"><path d="M17.813 4.653h.854c1.51.054 2.769.578 3.773 1.574 1.004.995 1.524 2.249 1.56 3.76v7.36c-.036 1.51-.556 2.769-1.56 3.773s-2.262 1.524-3.773 1.56H5.333c-1.51-.036-2.764-.556-3.76-1.56S.05 18.858 0 17.347v-7.36c.05-1.51.574-2.765 1.573-3.76.999-.996 2.258-1.52 3.76-1.574h.774l-1.174-1.12a1.234 1.234 0 0 1-.373-.906c0-.356.124-.658.373-.907l.027-.027c.267-.249.572-.373.92-.373.347 0 .653.124.92.373L9.653 4.44c.071.071.134.142.187.213h4.267a.836.836 0 0 1 .16-.213l2.853-2.747c.267-.249.573-.373.92-.373.347 0 .662.151.929.4.267.249.391.551.391.907 0 .355-.124.657-.373.906zM5.333 7.24c-.746.018-1.373.276-1.88.773-.506.498-.769 1.13-.786 1.894v7.52c.017.764.28 1.395.786 1.893.507.498 1.134.756 1.88.773h13.334c.746-.017 1.373-.275 1.88-.773.506-.498.769-1.129.786-1.893v-7.52c-.017-.764-.28-1.396-.786-1.894-.507-.497-1.134-.755-1.88-.773zM8 11.107c.373 0 .684.124.933.373.25.249.383.569.4.96v1.173c-.017.391-.15.711-.4.96-.249.25-.56.374-.933.374s-.684-.125-.933-.374c-.25-.249-.383-.569-.4-.96V12.44c0-.373.129-.689.386-.946.258-.258.574-.387.947-.387zm8 0c.373 0 .684.124.933.373.25.249.383.569.4.96v1.173c-.017.391-.15.711-.4.96-.249.25-.56.374-.933.374s-.684-.125-.933-.374c-.25-.249-.383-.569-.4-.96V12.44c0-.373.129-.689.386-.946.258-.258.574-.387.947-.387z"/></svg> <b>Video</b></a></li>
      <li class="res-item-compact"><b>Deformable Attention Optimization for Efficient 3D Detection</b> <span class="res-pub-compact">[DAC’24]</span></li>
    </ul>
  </div>

  <!-- Focus 4: 类脑计算 -->
  <div class="res-group-compact">
    <span class="res-title-compact">🧠 Brain-inspired Neuromorphic Computing</span>
    <ul class="res-sub-list">
      <li class="res-item-compact"><b>Neuromorphic Algorithms & Brain-inspired Applications</b> <span class="res-pub-compact">[ISCA'25, MICRO'24, DAC'24, DAC'23, AAAI'23, ICCAD’23, SIGIR’22]</span></li>
    </ul>
  </div>

  <!-- Focus 5: 安全AI -->
  <div class="res-group-compact">
    <span class="res-title-compact">🛡️ Hardware-assisted Secure & Trustworthy AI</span>
    <ul class="res-sub-list">
      <li class="res-item-compact"><b>Area-Efficient Cryptographic Design for LUT-based Modular Reduction</b> <span class="res-pub-compact">[DATE’26, DAC’25]</span></li>
      <li class="res-item-compact"><b>Secure Neuromorphic Computing Architecture</b> <span class="res-pub-compact">[TACO’25, DAC’24, ASP-DAC’24, DAC’23]</span></li>
    </ul>
  </div>

</div>


Recent Visits to this Site
-----------

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=tt&d=sNUIIgL1WU3gnVp7Lq7JpnhV-2YGPzHk9c4NSyeNuIc&co=4c98ce'></script>