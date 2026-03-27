---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
  .pub-container { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; max-width: 100%; color: #333; }
  .pub-legend { font-size: 13px; color: #666; margin-bottom: 25px; padding: 12px 15px; background: #fbfbfb; border-left: 5px solid #538F79; display: flex; justify-content: space-between; flex-wrap: wrap; gap: 10px; }
  .year-header { border-bottom: 2px solid #538F79; font-size: 22px; font-weight: bold; margin: 45px 0 20px 0; color: #222; }
  
  .pub-item { margin-bottom: 25px; display: flex; flex-direction: row; align-items: flex-start; line-height: 1.5; }
  .pub-venue { font-weight: 800; min-width: 115px; flex-shrink: 0; color: #111; font-size: 14.5px; padding-top: 2px; }
  .pub-content { flex-grow: 1; }
  .pub-title { font-weight: 700; color: #111; text-decoration: none; font-size: 16px; display: inline; transition: 0.2s; }
  .pub-title:hover { color: #538F79; border-bottom: 1px solid #538F79; }
  .pub-authors { font-size: 14px; color: #555; margin-top: 5px; }
  .pub-authors b { color: #000; text-decoration: none; border-bottom: 1.5px solid #333; }

  /* 按钮链接样式 */
  .pub-links { margin-top: 8px; display: flex; gap: 8px; flex-wrap: wrap; }
  .link-btn { font-size: 12px; font-weight: 600; color: #538F79; text-decoration: none; padding: 2px 8px; border: 1px solid #538F79; border-radius: 4px; transition: 0.2s; }
  .link-btn:hover { background: #538F79; color: #fff; }

  /* 标签体系 */
  .tag { font-size: 11px; padding: 1px 6px; border-radius: 4px; font-weight: 600; display: inline-block; margin-left: 4px; vertical-align: middle; }
  .tag-ccf { color: #1a73e8; background: #eef6ff; border: 1px solid #d0e7ff; }
  .tag-acc { color: #52c41a; background: #f6ffed; border: 1px solid #b7eb8f; }
  .tag-award { color: #d48806; background: #fffbe6; border: 1px solid #ffe58f; }
  .tag-industry { color: #cf1322; background: #fff1f0; border: 1px solid #ffa39e; }
  .tag-italic { font-size: 11px; color: #777; font-style: italic; margin-left: 4px; }

  /* 移动端适配 */
  @media (max-width: 768px) {
    .pub-item { flex-direction: column; }
    .pub-venue { margin-bottom: 6px; font-size: 13px; background: #eee; padding: 1px 8px; border-radius: 4px; min-width: auto; }
    .pub-title { font-size: 15px; }
    .pub-authors { font-size: 13px; }
    .pub-links { gap: 5px; }
    .link-btn { padding: 1px 6px; font-size: 11px; }
  }

 /* 强制单行容器 */
  .stats-simple-row {
    display: flex !important;
    flex-direction: row !important;
    flex-wrap: nowrap !important; /* 强制不换行 */
    justify-content: space-between;
    align-items: center;
    background: #fcfcfc;
    border: 1px solid #eee;
    border-radius: 6px;
    padding: 10px 0;
    margin: 20px 0 30px 0;
    width: 100%;
  }

  .stat-unit {
    flex: 1;
    text-align: center;
    border-right: 1px dotted #ddd;
    padding: 0 5px;
    min-width: 0; /* 防止内容撑开容器 */
  }

  .stat-unit:last-child {
    border-right: none;
  }

  .stat-num {
    font-size: 19px;
    font-weight: 800;
    color: #538F79;
    display: block;
    line-height: 1.1;
  }

  .stat-text {
    font-size: 12.5px;
    font-weight: 600;
    color: #333;
    white-space: nowrap; /* 强制文字不换行 */
  }

  .stat-sub {
    font-size: 10px;
    color: #999;
    display: block;
    transform: scale(0.9); /* 让备注更小更精致 */
  }

  /* 移动端微调：依然保持一行，缩小字号 */
  @media (max-width: 600px) {
    .stat-num { font-size: 16px; }
    .stat-text { font-size: 11px; }
    .stat-sub { display: none; }
  }
</style>

<div class="stats-simple-row"><div class="stat-unit"><span class="stat-num">20+</span><span class="stat-text">Architecture</span><span class="stat-sub">ISCA / MICRO / HPCA / ASPLOS</span></div>

<div class="stat-unit"><span class="stat-num">20+</span><span class="stat-text">EDA / Automation</span><span class="stat-sub">DAC / ICCAD</span></div>

<div class="stat-unit" style="border-bottom:none;"><span class="stat-num" style="color: #d48806;">3+</span><span class="stat-text" style="color: #d48806;">Awards</span><span class="stat-sub">Best / Outstanding / Features Papers</span></div></div>

<div class="pub-container">
  <div class="pub-legend">
    <span><b>{=}</b> Equal contribution &nbsp;&nbsp; <b>{*}</b> Corresponding author</span>
    <a href="https://scholar.google.com/citations?hl=zh-TW&user=dXzsaIsAAAAJ" style="color: #1a73e8; font-weight: bold; text-decoration: none;">[Google Scholar Profile]</a>
  </div>

  <div class="year-header">2026</div>

  <div class="pub-item">
    <span class="pub-venue">[ISCA '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">Harmonia: A Unified Hierarchical Scheduling Framework for Sparse Matrix Multiplication</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Jingkui Yang=, <b>Fangxin Liu=,*</b>, Xin Ju, Ning Yang, Chenyang Guan, Junjie Wang, Zongwu Wang, Mei Wen, Jian Liu, Li Jiang, Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ISCA '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">STEP: Adaptive Spatio-Temporal Expert Prefetching for Low-Latency and Memory-Efficient MoE Inference</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Ning Yang=, Zongwu Wang, Chenyang Guan, Haomin Li, Yu Feng, Liqiang Lu, Xiang Li, Siran Yang, Jiamang Wang, Lin Qu, Li Jiang, Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ISCA '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">COMET: A Cooperative Scheduling Framework for Concurrent PIM/CPU Execution on Mobile Devices</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Yilong Zhao, Onur Mutlu, Mingyu Gao, <b>Fangxin Liu*</b>, Jian Liu, Haibing Guan, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">GEMM-GS: Accelerating 3D Gaussian Splatting on Tensor Cores with GEMM-Compatible Blending</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Haomin Li, Bowen Zhu, <b>Fangxin Liu*</b>, Zongwu Wang, Xinran Liang, Li Jiang, Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">Brain-Like Hyper-Dimensional Graph Learning System with Hardware-Efficient Adaptive Sparsity</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Haomin Li, <b>Fangxin Liu*</b>, Z. Wang, S. Huang, N. Yang, C. Guan, T. Yang, X. Liang, H. Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">ExQuant: Global Expert Ranking–Guided Mixed-Precision Quantization for Efficient MoE Inference</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Chenyang Guan, <b>Fangxin Liu=*</b>, Junjie Wang, Ning Yang and Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">The Phantom of PCIe: Constraining Generative AIs for Practical Peripherals Trace Synthesizing</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Zhibai Huang, Chen Chen, James Yen, ... <b>Fangxin Liu*</b>, Tao Song, Mingyuan Xia, Zhengwei Qi</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">SkiST: Memory-Efficient Fine-Tuning of Spiking Neural Networks via Spatio-Temporal Adaptation</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Zhibai Huang, James Yen, Zhixiang Wei, Yun Wang, <b>Fangxin Liu*</b> and Zhengwei Qi</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[Tech Report]</span>
    <div class="pub-content">
      <a href="http://arxiv.org/abs/2602.00748" class="pub-title">HyperOffload: Graph-Driven Hierarchical Memory Management for LLMs on SuperNode</a>
      <span class="tag tag-industry">Applied at HUAWEI MindSpore</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Qinghua Zhang=, Hanjing Shen=, Zhibo Liang, Li Jiang, Haibing Guan, Xuefeng Jin</div>
      <div class="pub-links"><a href="http://arxiv.org/abs/2602.00748" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[TACO '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">NICE: Deep Neural Network Acceleration via Hardware-Friendly Index Assisted Compression</a>
      <span class="tag-italic">(Top Jour. in Arch)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Ning Yang=, <b>Fangxin Liu=,*</b>, Zongwu Wang, Haomin Li, Li Jiang, and Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ASPLOS '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">EARTH: An Efficient MoE Accelerator with Entropy-Aware Speculative Prefetch and Result Reuse</a>
      <span class="tag tag-acc">Acc: 10.6%</span>
      <div class="pub-authors"><b>Fangxin Liu=,*</b>, Ning Yang=, Jingkui Yang, Zongwu Wang, Chenyang Guan, Li Jiang, Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ASPLOS '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">Nebula: Infinite-Scale 3D Gaussian Splatting in VR via Collaborative Rendering</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 10.6%</span>
      <div class="pub-authors">He Zhu, Zheng Liu, Xingyang Li, Anbang Wu, Jieru Zhao, <b>Fangxin Liu</b>, Jingwen Leng, Yu Feng</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[PPoPP '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">BEEMS: Boosting Machine Vision Efficiency via Computation Graph-Based Memory Smoothing</a>
      <span class="tag-italic">(Top Conf. in Sys.)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 11.5%</span>
      <div class="pub-authors">Hanjing Shen, <b>Fangxin Liu=,*</b>, Jian Liu, Li Jiang, and Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[PPoPP '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">Accelerating Sparse Transformer Inference on GPU</a>
      <span class="tag-italic">(Top Conf. in Sys.)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 11.5%</span>
      <div class="pub-authors">Wenhao Dai, Haodong Deng, Mengfei Rong, Xinyu Yang, <b>Fangxin Liu</b>, Hailong Yang, Qianwen Cao, Qingxiao Sun</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DATE '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">LaMoS: Enabling Efficient Large Number Modular Multiplication through SRAM-based CiM</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-B</span><span class="tag tag-acc">Acc: 25%</span>
      <div class="pub-authors">Haomin Li, <b>Fangxin Liu*</b>, Chenyang Guan, Zongwu Wang, Li Jiang and Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[AAAI '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">SpecQuant: Spectral Decomposition and Adaptive Truncation for Ultra-Low-Bit LLMs Quantization</a>
      <span class="tag-italic">(Top Conf. in AI)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 17.6%</span>
      <div class="pub-authors">Zhixiong Zhao, <b>Fangxin Liu=*</b>, Junjie Wang, Chenyang Guan, Zongwu Wang, Li Jiang, Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[HPCA '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">ORANGE: Exploring Ockham's Razor for Neural Rendering by Accelerating 3DGS on NPUs</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 19.7%</span>
      <div class="pub-authors">Haomin Li, Yue Liang, <b>Fangxin Liu=,*</b>, Bowen Zhu, Zongwu Wang, Yu Feng, Li Jiang, and Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[HPCA '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">Splatonic: Architecture Support for 3D Gaussian Splatting SLAM via Sparse Processing</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 19.7%</span>
      <div class="pub-authors">Xiaotong Huang, He Zhu, Tianrui Ma, <b>Fangxin Liu</b>, Zhezhi He, Yiming Gan, Jingwen Leng, Yu Feng, Minyi Guo</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ASPDAC '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">BLADE: Boosting LLM Decoding's Communication Efficiency in DRAM-based PIM</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 29%</span>
      <div class="pub-authors">Yilong Zhao, <b>Fangxin Liu*</b>, Zongwu Wang, Mingjian Li, Mingxing Zhang, Chixiao Chen, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ASPLOS '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">ASDR: Exploiting Adaptive Sampling and Data Reuse for CIM-based Instant Neural Rendering</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 23%</span>
      <div class="pub-authors"><b>Fangxin Liu=*</b>, Haomin Li=, Bowen Zhu, Zongwu Wang, Zhuoran Song, Haibing Guan, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ASPLOS '26]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">PUSHtap: PIM-based In-Memory HTAP with Unified Data Storage Format</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 23%</span>
      <div class="pub-authors">Yilong Zhao, Mingyu Gao, Huanchen Zhang, <b>Fangxin Liu*</b>, Gongye Chen, He Xian, Haibing Guan, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="year-header">2025</div>

  <div class="pub-item">
    <span class="pub-venue">[TACO '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">Rethinking Variable-Length Encoding: Bit Sparsity for Parallel Decoding in LLM Accelerators</a>
      <span class="tag-italic">(Top Jour. in Arch)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Ning Yang, <b>Fangxin Liu*</b>, Junjie Wang, Chenyang Guan, Zongwu Wang, Junping Zhao, Li Jiang, Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[TACO '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">MIX-PC: Enabling Efficient DNN Inference with Mixed Numeric Precision Compilation Optimization</a>
      <span class="tag-italic">(Top Jour. in Arch)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Shiyuan Huang, <b>Fangxin Liu=,*</b>, Zongwu Wang, Ning Yang, Haomin Li, Haibing Guan, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[EMNLP '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">FlexQuant: A Flexible and Efficient Dynamic Precision Switching Framework for LLM Quantization</a>
      <span class="tag-italic">(Top Conf. in NLP)</span><span class="tag tag-ccf">CCF-B</span><span class="tag tag-industry">Applied at Ant Group</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Wongwu Wang, Jinhong Xia, Junping Zhao*, Shouren Zhao, Li Jiang*, Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ACM MM '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">ASTER: Adaptive Dynamic Layer-Skipping for Efficient Transformer Inference via MDP</a>
      <span class="tag-italic">(Top Conf. in Multimedia/AI)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-award">🏆 Outstanding Paper</span>
      <div class="pub-authors"><b>Fangxin Liu=*</b>, Junjie Wang=, Ning Yang, Zongwu Wang, Junping Zhao, Li Jiang, and Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ICCAD '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">QUARK: Quantization-Enabled Circuit Sharing for Transformer Acceleration via Pattern Exploiting</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-B</span><span class="tag tag-acc">Acc: 24%</span>
      <div class="pub-authors">Zhixiong Zhao=, Haomin Li=, <b>Fangxin Liu*</b>, Yuncheng Lu, Zongwu Wang, Tao Yang, Haibing Guan, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ICCAD '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">PLAIN: Leveraging High Internal Bandwidth in PIM for LLM Inference via Mixed-Precision</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-B</span><span class="tag tag-acc">Acc: 24%</span>
      <div class="pub-authors">Yiwei Hu, <b>Fangxin Liu=*</b>, Zongwu Wang, Yilong Zhao, Tao Yang, Haibing Guan, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ICCAD '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">DevTrace: Efficient and Fine-grained PCIe Transaction Tracing for Edge Intelligence Workloads</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-B</span><span class="tag tag-acc">Acc: 24%</span>
      <div class="pub-authors">Zhibai Huang, Kailiang Xu, Zhixiang Wei, Yinghao Deng, Chen Chen, James Yen, <b>Fangxin Liu*</b>, MingYuan Xia, Zhengwei Qi</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[TCAD '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">A Sub-10 μs In-Memory-Search Collision Detection Accelerator Based on RRAM-TCAMs</a>
      <span class="tag-italic">(Top Jour. in EDA)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Jiahao Sun, Yijian Zhang, <b>Fangxin Liu*</b>, Li Jiang, and Rui Yang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[TACO '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">Attack and Defense: Enhancing Robustness of Binary Hyper-Dimensional Computing</a>
      <span class="tag-italic">(Top Jour. in Arch)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Haomin Li, <b>Fangxin Liu*</b>, Zongwu Wang, Ning Yang, Shiyuan Huang, Xiaoyao Liang, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ISCA '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">FATE: Boosting HDC Intelligence Performance with Flexible Numerical Data Type</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 21%</span>
      <div class="pub-authors">Haomin Li=, <b>Fangxin Liu=*</b>, Yichi Chen, Zongwu Wang, Shiyuan Huang, Ning Yang, Dongxu Lyu, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ISCA '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">Qtenon: Towards Low-Latency Architecture Integration for Accelerating Hybrid Quantum-Classical Computing</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 21%</span>
      <div class="pub-authors">Chenning Tao, Liqiang Lu, Size Zheng, Li-Wen Chang, Minghua Shen, Hanyu Zhang, <b>Fangxin Liu</b>, Kaiwen Zhou, Jianwei Yin</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">ALLMod: Exploring Area-Efficiency of LUT-based Large Number Modular Reduction via Hybrid Workloads</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 23%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Haomin Li=, Zongwu Wang, Bo Zhang, Mingzhe Zhang, Shoumeng Yan, Li Jiang, Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">MILLION: MasterIng Long-Context LLM Inference Via Outlier-Immunized KV Product Quantization</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-industry">Applied at HUAWEI</span>
      <div class="pub-authors">Zongwu Wang=, Peng Xu=, <b>Fangxin Liu*</b>, Yiwei Hu, Qingxiao Sun, Xuan Wang, Li Jiang, Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">BLOOM: Bit-Slice Framework for DNN Acceleration with Mixed-Precision</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-industry">Applied at ZTE</span>
      <div class="pub-authors"><b>Fangxin Liu=*</b>, Ning Yang=, Zongwu Wang, Xuanpeng Zhu, Haidong Yao, Xiankui Xiong, Li Jiang, Haibing Guan</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">PISA: Efficient Precision-Slice Framework for LLMs with Adaptive Numerical Type</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 23%</span>
      <div class="pub-authors">Ning Yang, Zongwu Wang, Qingxiao Sun, Liqiang Lu, and <b>Fangxin Liu*</b></div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DATE '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">HyperDyn: Dynamic Dimensional Masking for Efficient Hyper-Dimensional Computing</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-B</span><span class="tag tag-acc">Acc: 21%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Haomin Li=, Zongwu Wang, Dongxu Lyu, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DATE '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">HyperNeO: Efficient and Accurate Hyper-Dimensional Regression via Neural Optimization</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-B</span><span class="tag tag-acc">Acc: 21%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Haomin Li=, Zewen Sun, Zongwu Wang, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DATE '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">TAIL: Temporal Asynchronous Execution for Efficient SNNs with Inter-Layer Parallelism</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-B</span><span class="tag tag-acc">Acc: 21%</span>
      <div class="pub-authors">Haomin Li=, <b>Fangxin Liu=</b>, Z. Wang, D. Lyu, S. Huang, N. Yang, Q. Sun, Z. Song, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DATE '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">OPS: Outlier-aware Precision-Slice Framework for LLM Acceleration</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-B</span><span class="tag tag-acc">Acc: 21%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Ning Yang=, Zongwu Wang, Xuanpeng Zhu, Haidong Yao, Xiankui Xiong, Qi Sun, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DATE '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">EVASION: Efficient KV Cache Compression via Product Quantization</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-B</span><span class="tag tag-acc">Acc: 21%</span>
      <div class="pub-authors">Zongwu Wang, <b>Fangxin Liu</b>, Peng Xu, Qingxiao Sun, Junping Zhao and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[HPCA '25]</span>
    <div class="pub-content">
      <a href="https://ieeexplore.ieee.org/abstract/document/10946829" class="pub-title">CROSS: Compiler-Driven Optimization of Sparse DNNs Using Sparse/Dense Computation Kernels</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 21%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Shiyuan Huang=, Ning Yang, Zongwu Wang, Haomin Li, and Li Jiang</div>
      <div class="pub-links"><a href="https://ieeexplore.ieee.org/abstract/document/10946829" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[HPCA '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">GSArch: Breaking Memory Barriers in 3D Gaussian Splatting Training via Architectural Support</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 21%</span>
      <div class="pub-authors">Houshu He, Gang Li, <b>Fangxin Liu</b>, Li Jiang, Xiaoyang Liang, and Zhuoran Song</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ASPDAC '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">Exploiting Differential-Based Data Encoding for Enhanced Query Efficiency</a>
      <span class="tag tag-acc">Acc: 28%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Zongwu Wang=, Peng Xu, Shiyuan Huang and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ASPDAC '25]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">NeuronQuant: Accurate and Efficient Post-Training Quantization for Spiking Neural Networks</a>
      <span class="tag tag-acc">Acc: 28%</span>
      <div class="pub-authors">Haomin Li=, <b>Fangxin Liu=</b>, Zewen Sun, Zongwu Wang, Shiyuan Huang, Ning Yang, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="year-header">2024</div>

  <div class="pub-item">
    <span class="pub-venue">[TCAS-AI '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">SearchQ: Search-based Fine-Grained Quantization for Data-Free Model Compression</a>
      <span class="tag tag-industry">Applied at HUAWEI</span>
      <div class="pub-authors">Ning Yang=, <b>Fangxin Liu=</b>, Zongwu Wang, Junping Zhao, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[TODAES '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">STCO: Enhancing Training Efficiency via Structured Sparse Tensor Compilation Optimization</a>
      <span class="tag tag-industry">Applied at Yizhu Tech.</span>
      <div class="pub-authors">Shiyuan Huang=, <b>Fangxin Liu=</b>, Tian Li, Zongwu Wang, Ning Yang, Haomin Li and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[TCAD '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">SpMMPlu-Pro: An Enhanced Compiler Plug-In for Efficient SpMM and Sparsity Propagation</a>
      <span class="tag-italic">(Top Jour. in EDA)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors">Shiyuan Huang, <b>Fangxin Liu*</b>, Tao Yang, Zongwu Wang Ning Yang, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ICCD '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">T-BUS: Taming Bipartite Unstructured Sparsity for Energy-Efficient DNN Acceleration</a>
      <span class="tag tag-acc">Acc: 25%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Ning Yang=, Zongwu Wang, Zhiyan Song, Tao Yang, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ICCD '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">HOLES: Boosting LLMs Efficiency with Hardware-friendly Lossless Encoding</a>
      <span class="tag tag-acc">Acc: 25%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Ning Yang=, Zhiyan Song, Zongwu Wang and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ICCD '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">PS4: A Low Power SNN Accelerator with Spike Speculative Scheme</a>
      <span class="tag tag-acc">Acc: 25%</span>
      <div class="pub-authors">Zongwu Wang=, <b>Fangxin Liu=</b>, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ICCD '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">Ninja: A Hardware Assisted System for Accelerating Nested Address Translation</a>
      <span class="tag tag-acc">Acc: 25%</span>
      <div class="pub-authors">Longyu Zhao, Zongwu Wang, <b>Fangxin Liu*</b>, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[MICRO '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">COMPASS: SRAM-Based Computing-in-Memory SNN Accelerator with Adaptive Spike Speculation</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 22%</span>
      <div class="pub-authors">Zongwu Wang, <b>Fangxin Liu*</b>, Ning Yang, Shiyuan Huang, Haomin Li, and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[MICRO '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">SRender: Boosting Neural Radiance Field Efficiency via Sensitivity-Aware Dynamic Precision Rendering</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 22%</span>
      <div class="pub-authors">Zhuoran Song, Houshu He, <b>Fangxin Liu*</b>, Yifan Hao, Xinkai Song, Li Jiang and Xiaoyao Liang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[TPDS '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">Exploiting Temporal-Unrolled Parallelism for Energy-Efficient SNN Acceleration</a>
      <span class="tag-italic">(Top Jour. in Arch)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors"><b>Fangxin Liu</b>, Z. Wang, W. Zhao, N. Yang, Y. Chen, S. Huang, H. Li, T. Yang, S. Pei, X. Liang, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ISLPED '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">LowPASS: A Low power PIM-based accelerator with Speculative Scheme for SNNs</a>
      <span class="tag tag-acc">Acc: 21%</span>
      <div class="pub-authors">Zongwu Wang, <b>Fangxin Liu*</b>, Longyu Zhao, Shiyuan Huang and Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ISCA '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">UM-PIM: DRAM-based PIM with Uniform & Shared Memory Space</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 18%</span>
      <div class="pub-authors">Yilong Zhao, Mingyu Gao, <b>Fangxin Liu*</b>, Yiwei Hu, Zongwu Wang, Han Lin, Ji Li, He Xian, Naifeng Jing, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">INSPIRE: Accelerating Deep Neural Networks via Hardware-friendly Index-Pair Encoding</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 23%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Ning Yang=, Haomin Li, Zongwu Wang, Zhuoran Song, Songwen Pei, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">EOS: An Energy-Oriented Attack Framework for Spiking Neural Networks</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 23%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Ning Yang=, Haomin Li, Zongwu Wang, Zhuoran Song, Songwen Pei, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DATE '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">RTSA: An RRAM-TCAM based In-Memory-Search Accelerator for Sub-100 μs Collision Detection</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-B</span><span class="tag tag-acc">Acc: 24%</span>
      <div class="pub-authors">Jiahao Sun, <b>Fangxin Liu=</b>, Yijian Zhang, Li Jiang and Rui Yang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ASPLOS '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">CMC: Video Transformer Acceleration via CODEC Assisted Matrix Condensing</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 24%</span>
      <div class="pub-authors">Zhuoran Song, Chunyu Qi, <b>Fangxin Liu=</b>, Naifeng Jing, Xiaoyao Liang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[HPCA '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">SPARK: Scalable and Precision-Aware Acceleration of Neural Networks via Efficient Encoding</a>
      <span class="tag-italic">(Top Conf. in Arch)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 18%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Ning Yang=, Haomin Li, Zongwu Wang, Zhuoran Song, Songwen Pei, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ASPDAC '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">PAAP-HD: PIM-Assisted Approximation for Efficient Hyper-Dimensional Computing</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-acc">Acc: 29%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Haomin Li=, Ning Yang, Yichi Chen, Zongwu Wang, Tao Yang, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ASPDAC '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">TEAS: Exploiting Spiking Activity for Temporal-wise Adaptive Spiking Neural Networks</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-acc">Acc: 29%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Haomin Li=, Ning Yang, Zongwu Wang, Tao Yang, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ASPDAC '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">TSTC: Enabling Efficient Training via Structured Sparse Tensor Compilation</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-acc">Acc: 29%</span>
      <div class="pub-authors">Shiyuan Huang=, <b>Fangxin Liu=</b>, Tian Li, Zongwu Wang, Haomin Li, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ASPDAC '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">HyperFeel: An Efficient Federated Learning Framework Using Hyperdimensional Computing</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-acc">Acc: 29%</span>
      <div class="pub-authors">Haomin Li=, <b>Fangxin Liu=</b>, Yichi Chen, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '24]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">HyperAttack: An Efficient Attack Framework for HyperDimensional Computing</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-ccf">CCF-A</span><span class="tag tag-acc">Acc: 23%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Haomin Li=, Zongwu Wang, Yongbiao Chen, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

<div class="year-header">2023</div>

  <div class="pub-item">
    <span class="pub-venue">[IEEE TC '23]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">ERA-BS: Efficiency of ReRAM-based PIM Accelerator with Fine-Grained Bit-Level Sparsity</a>
      <span class="tag-italic">(Top Jour. in Arch)</span><span class="tag tag-ccf">CCF-A</span>
      <div class="pub-authors"><b>Fangxin Liu</b>, Wenbo Zhao, Zongwu Wang, Yongbiao Chen, Xiaoyao Liang, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ICCD '23]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">PSQ: An Automatic Search Framework for Data-Free Quantization on PIM-based Architecture</a>
      <span class="tag tag-acc">Acc: 28%</span>
      <div class="pub-authors"><b>Fangxin Liu=</b>, Ning Yang=, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[ICCAD '23]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">HyperNode: An Efficient Node Classification Framework Using HyperDimensional Computing</a>
      <span class="tag-italic">(Top Conf. in EDA)</span><span class="tag tag-acc">Acc: 23%</span>
      <div class="pub-authors">Haomin Li=, <b>Fangxin Liu=</b>, Yichi Chen, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="year-header">2022</div>

  <div class="pub-item">
    <span class="pub-venue">[DATE '22]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">Self-Terminated Write of MLC ReRAM for Efficient Neuromorphic Computing</a>
      <span class="tag tag-award">🏆 Best Paper Award</span><span class="tag-italic">(Top Conf. in EDA)</span>
      <div class="pub-authors">Zongwu Wang, <b>Fangxin Liu</b>, et al.</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[AAAI '22]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">SpikeConverter: An Efficient Conversion Framework Zipping the Gap between ANNs and SNNs</a>
      <span class="tag tag-award">🏆 Oral (Top 15%)</span><span class="tag-italic">(Top Conf. in AI)</span>
      <div class="pub-authors"><b>Fangxin Liu</b>, Wenbo Zhao*, Yongbiao Chen, Zongwu Wang, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[TCAD '22]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">SoBS-X: Squeeze-Out Bit Sparsity for ReRAM-Crossbar-Based Neural Network Accelerator</a>
      <span class="tag tag-ccf">CCF-A</span><span class="tag-italic">(Top Jour. in EDA)</span>
      <div class="pub-authors"><b>Fangxin Liu</b>, Zongwu Wang, Yongbiao Chen, Zhezhi He, Tao Yang, Xiaoyao Liang, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DAC '22]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">EBSP: Evolving Bit Sparsity Patterns for Hardware Friendly Inference of Quantized DNNs</a>
      <span class="tag tag-acc">Acc: 24.7%</span><span class="tag-italic">(Top Conf. in EDA)</span>
      <div class="pub-authors"><b>Fangxin Liu</b>, Wenbo Zhao, Zongwu Wang, Yongbiao Chen, Zhezhi He, Naifeng Jing, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[SIGIR '22]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">L3E-HD: A Framework Enabling Efficient Ensemble in High-Dimensional Space for Language Tasks</a>
      <span class="tag tag-acc">Acc: 24%</span><span class="tag-italic">(Top Conf. in IR)</span>
      <div class="pub-authors"><b>Fangxin Liu</b>, Haomin Li, Xiaokang Yang, Li Jiang</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

  <div class="pub-item">
    <span class="pub-venue">[DATE '22]</span>
    <div class="pub-content">
      <a href="#" class="pub-title">DTQAtten: Leveraging Dynamic Token-based Quantization for Efficient Attention</a>
      <span class="tag tag-award">Best Paper Nomination</span>
      <div class="pub-authors">Tao Yang, <b>Fangxin Liu</b>, et al.</div>
      <div class="pub-links"><a href="#" class="link-btn">[Paper]</a><a href="#" class="link-btn">[Code]</a><a href="#" class="link-btn">[BibTeX]</a></div>
    </div>
  </div>

</div>

<!-- You can also find my articles on <u><a href="https://scholar.google.com/citations?hl=zh-TW&user=dXzsaIsAAAAJ">my Google Scholar profile</a></u> -->
<!-- <font color=538F79>{=} denotes equal contribution; &emsp; {*} denotes corresponding author</font> -->


<!-- After joining SJTU. -->
<!-- <table width="100%" style="table-layout:auto;" style="font-size:inherit;" >
<tr><td style="font-size:inherit;"><strong>DAC 2026</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"> Haomin Li, Bowen Zhu, <u><b>Fangxin Liu*</b></u>, Zongwu Wang, Xinran Liang, Li Jiang and Haibing Guan<br> <a href="#">GEMM-GS: Accelerating 3D Gaussian Splatting on Tensor Cores with GEMM-Compatible Blending</a> <strong>(CCF Tier A)</strong>
</td></tr>

<tr><td bgcolor="#F7F7F7"><strong>DAC 2026</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;" bgcolor="#F7F7F7"> Haomin Li, <u><b>Fangxin Liu*</b></u>, Zongwu Wang, Shiyuan Huang, Ning Yang, Chenyang Guan, Tao Yang, Xinran Liang and Haibing Guan<br> <a href="#">Brain-Like Hyper-Dimensional Graph Learning System with Hardware-Efficient Adaptive Sparsity</a> <strong>(CCF Tier A)</strong>
</td></tr>



<tr><td style="font-size:inherit;"><strong>DAC 2026</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"> Chenyang Guan <u><b>Fangxin Liu=*</b></u>, Junjie Wang, Ning Yang and Haibing Guan<br> <a href="#">ExQuant: Global Expert Ranking–Guided Mixed-Precision Quantization for Efficient MoE Inference</a> <strong>(CCF Tier A)</strong>
</td></tr>

<tr><td bgcolor="#F7F7F7"><strong>DAC 2026</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;" bgcolor="#F7F7F7"> Zhibai Huang, Chen Chen, James Yen, Yihan Shen, Yongchen Xie, Zhixiang Wei, Kailiang Xu, Yun Wang, <u><b>Fangxin Liu*</b></u>, Tao Song, Mingyuan Xia and Zhengwei Qi<br> <a href="#">The Phantom of PCIe: Constraining Generative Artificial Intelligences for Practical Peripherals Trace Synthesizing</a> <strong>(CCF Tier A)</strong>
</td></tr>

<tr><td style="font-size:inherit;"><strong>DAC 2026</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"> Zhibai Huang, James Yen, Zhixiang Wei, Yun Wang, <u><b>Fangxin Liu*</b></u> and Zhengwei Qi<br> <a href="#">SkiST: Memory-Efficient Fine-Tuning of Spiking Neural Networks via Spatio-Temporal Adaptation</a> <strong>(CCF Tier A)</strong>
</td></tr>



<tr ><td bgcolor="#F7F7F7"><strong>Technical Report</strong><br>(with Huawei MindSpore)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Qinghua Zhang=, Hanjing Shen=, Zhibo Liang, Li Jiang, Haibing Guan, Chong Bao, and Xuefeng Jin<br> <a href="http://arxiv.org/abs/2602.00748"> HyperOffload: Graph-Driven Hierarchical Memory Management for Large Language Models on SuperNode Architectures</a> <strong>[Applied at HUAWEI]</strong> 
</td></tr>

<tr ><td style="font-size:inherit;"><strong>TACO 2026</strong><br>(Top Jour. in Computer Architecture)</td><td style="font-size:inherit;"> Ning Yang=, <u><b>Fangxin Liu=,*</b></u>, Zongwu Wang, Haomin Li, Hongbo Zhao, Xinran Liang, Li Jiang, and Haibing Guan<<br> <a href="#">NICE: Deep Neural Network Acceleration via Hardware-Friendly Index Assisted Compression</a>  <strong>(CCF Tier A)</strong> 

</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>ASPLOS 2026</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=,*</b></u>, Ning Yang=, Jingkui Yang, Zongwu Wang, CHenyang Guan, Yu Feng, Li Jiang, and Haibing Guan<br> <a href="#">EARTH: An Efficient MoE Accelerator with Entropy-Aware Speculative Prefetch and Result Reuse</a> <strong>(Acceptance Rate: 10.6%)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;"><strong>ASPLOS 2026</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"> He Zhu, Zheng Liu, Xingyang Li, Anbang Wu, Jieru Zhao, <u><b>Fangxin Liu</b></u>, Yiming Gan, Jingwen Leng, and Yu Feng <br> <a href="#">Nebula: Infinite-Scale 3D Gaussian Splatting in VR via Collaborative Rendering and Accelerated Stereo Rasterization</a>  <strong>(Acceptance Rate: 10.6%)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>TACO 2025</strong><br>(Top Jour. in Computer Architecture)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Ning Yang, <u><b>Fangxin Liu*</b></u>, Junjie Wang, Chenyang Guan, Zongwu Wang, Junping Zhao, Li Jiang, and Haibing Guan<br> <a> Rethinking Variable-Length Encoding: Exploiting Bit Sparsity for Parallel Decoding in LLM Accelerators</a> <strong>(CCF Tier A)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;"><strong>TACO 2025</strong><br>(Top Jour. in Computer Architecture)</td><td style="font-size:inherit;"> Shiyuan Huang, <u><b>Fangxin Liu=,*</b></u>, Zongwu Wang, Ning Yang, Haomin Li, Haibing Guan, and Li Jiang<br> <a href="#"> MIX-PC: Enabling Efficient DNN Inference with Mixed Numeric Precision Compilation Optimization</a>  <strong>(CCF Tier A)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>PPoPP 2026</strong><br>(Top Conf. in Computer System)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Hanjing Shen, <u><b>Fangxin Liu=,*</b></u>, Jian Liu, Li Jiang, and Haibing Guan<br> <a href="#"> BEEMS: Boosting Machine Vision Efficiency via Computation  Graph-Based Memory Smoothing</a> <strong>(Acceptance Rate: 11.5%)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;"><strong>PPoPP 2026</strong><br>(Top Conf. in Computer System)</td><td style="font-size:inherit;"> Wenhao Dai, Haodong Deng, Mengfei Rong, Xinyu Yang, Hongyu Liu, <u><b>Fangxin Liu</b></u>, Hailong Yang, Qianwen Cao, and Qingxiao Sun <br> <a href="#">  Accelerating Sparse Transformer Inference on GPU</a>  <strong>(Acceptance Rate: 11.5%)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>DATE 2026</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7">  Haomin Li, <u><b>Fangxin Liu*</b></u>, Chenyang Guan, Zongwu Wang, Li Jiang and Haibing Guan<br> <a href="#"> LaMoS: Enabling Efficient Lrge Number Modular Multiplication through SRAM-based CiM Acceleration</a> <strong>(Acceptance Rate: 25%)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;"><strong>AAAI 2026</strong><br>(Top Conf. in AI)</td><td style="font-size:inherit;"> Zhixiong Zhao, <u><b>Fangxin Liu=*</b></u>, Junjie Wang, Chenyang Guan, Zongwu Wang, Li Jiang, Haibing Guan <br> <a href="#"> SpecQuant: Spectral Decomposition and Adaptive Truncation for Ultra-Low-Bit LLMs Quantization</a>  <strong>(Acceptance Rate: 17.6%)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>HPCA 2026</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Haomin Li, Yue Liang, <u><b>Fangxin Liu=,*</b></u>, Bowen Zhu, Zongwu Wang, Yu Feng, Liqiang Lu, Li Jiang, and Haibing Guan<br> <a href="#"> ORANGE: Exploring Ockham's Razor for Neural Rendering by Accelerating 3DGS on NPUs with GEMM-Friendly Blending and Balanced Workloads</a> <strong>(Acceptance Rate: 19.7%)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;"><strong>HPCA 2026</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"> Xiaotong Huang, He Zhu, Tianrui Ma, Yuxiang Xiaong, <u><b>Fangxin Liu</b></u>, Zhezhi He, Yiming Gan, Zihan Liu, Jingwen Leng, Yu Feng, and Minyi Guo <br> <a href="#">  Splatonic: Architecture Support for 3D Gaussian Splatting SLAM via Sparse Processing</a>  <strong>(Acceptance Rate: 19.7%)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>ASP-DAC 2026</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Yilong Zhao, <u><b>Fangxin Liu*</b></u>, Zongwu Wang, Mingjian Li, Mingxing Zhang, Chixiao Chen, Li Jiang<br> <a href="#"> BLADE: Boosting LLM Decoding's Communication Efficiency in DRAM-based PIM</a> <strong>(Acceptance Rate: 29%)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;"><strong>EMNLP 2025</strong><br>(Top Conf. in NLP)</td><td style="font-size:inherit;"> <u><b>Fangxin Liu=</b></u>, Wongwu Wang, Jinhong Xia, Junping Zhao*, Shouren Zhao, Jinjin Li, Jian Liu, Li Jiang*, Haibing Guan <br> <a href="#">  FlexQuant: A Flexible and Efficient Dynamic Precision Switching Framework for LLM Quantization</a>  <strong>(Acceptance Rate: 22%)</strong>  <font color=800e13><b>[Applied at Ant Group]</b></font>
</td></tr>

<tr ><td style="font-size:inherit;"><strong>ACM MM 2025</strong><br>(Top Conf. in AI)</td><td style="font-size:inherit;"> <u><b>Fangxin Liu=*</b></u>, Junjie Wang=, Ning Yang, Zongwu Wang, Junping Zhao, Li Jiang, and Haibing Guan<br> <a href="#"> ASTER: Adaptive Dynamic Layer-Skipping for Efficient Transformer Inference via Markov Decision Process</a>  <strong>(Oral)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>ICCAD 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Zhixiong Zhao=, Haomin Li=, <u><b>Fangxin Liu*</b></u>, Yuncheng Lu, Zongwu Wang, Tao Yang, Haibing Guan, and Li Jiang<br> <a href="#"> QUARK: Quantization-Enabled Circuit Sharing for Transformer Acceleration by Exploiting Common Patterns in Nonlinear Operations</a> <strong>(Acceptance Rate: 24%)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;"><strong>ICCAD 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"> Yiwei Hu, <u><b>Fangxin Liu=*</b></u>, Zongwu Wang, Yilong Zhao, Tao Yang, Haibing Guan, and Li Jiang <br> <a href="#"> PLAIN: Leveraging High Internal Bandwidth in PIM for Accelerating Large Language Model Inference via Mixed-Precision Quantization</a>  <strong>(Acceptance Rate: 24%)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>ICCAD 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Zhibai Huang, Kailiang Xu, Zhixiang Wei, Yinghao Deng, Chen Chen, James Yen, Yun Wang,  <u><b>Fangxin Liu*</b></u>, , MingYuan Xia, and Zhengwei Qi <br> <a href="#"> DevTrace: Efficient and Fine-grained PCIe Transaction Tracing for Edge Intelligence Workloads</a> <strong>(Acceptance Rate: 24%)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;"><strong>IEEE TCAD 2025</strong><br>(Top Jour. in Computer Architecture)</td><td style="font-size:inherit;"> Jiahao Sun, Yijian Zhang, <u><b>Fangxin Liu*</b></u>, Li Jiang, and Rui Yang <br> <a href="https://ieeexplore.ieee.org/abstract/document/11002546"> A Sub-10 μs In-Memory-Search Collision Detection Accelerator Based on RRAM-TCAMs</a>  <strong>(CCF Tier A)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>ASPLOS 2026</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"><u><b>Fangxin Liu=*</b></u>, Haomin Li=, Bowen Zhu, Zongwu Wang, Zhuoran Song, Haibing Guan, and Li Jiang <br> <a href="#"> ASDR: Exploiting Adaptive Sampling and Data Reuse for CIM-based Instant Neural Rendering</a> <strong>(Acceptance Rate: 23%)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;"><strong>ASPLOS 2026</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"> Yilong Zhao, Mingyu Gao, Huanchen Zhang, <u><b>Fangxin Liu*</b></u>, Gongye Chen, He Xian, Haibing Guan, and Li Jiang <br> <a href="#"> PUSHtap: PIM-based In-Memory HTAP with Unified Data Storage Format</a>  <strong>(Acceptance Rate: 23%)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>TACO 2025</strong><br>(Top Jour. in Computer Architecture)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Haomin Li, <u><b>Fangxin Liu*</b></u>, Zongwu Wang, Ning Yang, Shiyuan Huang, Xiaoyao Liang, and Li Jiang <br> <a href="https://dl.acm.org/doi/pdf/10.1145/3736172"> Attack and Defense: Enhancing Robustness of Binary Hyper-Dimensional Computing</a> <strong>(CCF Tier A)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;"><strong>ISCA 2025</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;">  Haomin Li=,  <u><b>Fangxin Liu=*</b></u>,  Yichi Chen, Zongwu Wang, Shiyuan Huang, Ning Yang, Dongxu Lyu, and Li Jiang<br> <a href="https://dl.acm.org/doi/full/10.1145/3695053.3731031"> FATE: Boosting the Performance of Hyper-Dimensional Computing Intelligence with Flexible Numerical DAta TypE</a>  <strong>(Acceptance Rate: 21%)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>ISCA 2025</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Chenning Tao, Liqiang Lu, Size Zheng, Li-Wen Chang, Minghua Shen, Hanyu Zhang, <u><b>Fangxin Liu</b></u>, Kaiwen Zhou and Jianwei Yin <br> <a href="https://dl.acm.org/doi/pdf/10.1145/3695053.3731087"> Qtenon: Towards Low-Latency Architecture Integration for Accelerating Hybrid Quantum-Classical Computing</a> <strong>(Acceptance Rate: 21%)</strong> 

<tr ><td style="font-size:inherit;"><strong>DAC 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;">  <u><b>Fangxin Liu=</b></u>,  Haomin Li=, Zongwu Wang, Bo Zhang, Mingzhe Zhang, Shoumeng Yan, Li Jiang, and Haibing Guan<br> <a href="http://arxiv.org/abs/2503.15916"> ALLMod: Exploring Area-Efficiency of LUT-based Large Number Modular Reduction via Hybrid Workloads</a>  <strong>(Acceptance Rate: 23%)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>DAC 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Zongwu Wang=, Peng Xu=, <u><b>Fangxin Liu*</b></u>, Yiwei Hu, Qingxiao Sun, Gezi Li, Cheng Li, Xuan Wang, Li Jiang, and Haibing Guan <br> <a href="https://arxiv.org/abs/2504.03661"> MILLION: MasterIng Long-Context LLM InferenceVia Outlier-Immunized KV Product OuaNtization</a> <strong>(Acceptance Rate: 23%)</strong>  <font color=800e13><b>[Applied at HUAWEI]</b></font>
</td></tr>

<tr ><td style="font-size:inherit;"><strong>DAC 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"> <u><b>Fangxin Liu=*</b></u>, Ning Yang=, Zongwu Wang, Xuanpeng Zhu, Haidong Yao, Xiankui Xiong, Li Jiang and Haibing Guan <br> <a href="#"> BLOOM: Bit-Slice Framework for DNN Acceleration with Mixed-Precision</a>  <strong>(Acceptance Rate: 23%)</strong>  <font color=800e13><b>[Applied at ZTE]</b></font>
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>DAC 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Ning Yang, Zongwu Wang, Qingxiao Sun, Liqiang Lu, and <u><b>Fangxin Liu*</b></u> <br> <a href="#"> PISA:Efficient Precision-Slice Framework forLLMs with Adaptive Numerical Type</a>  <strong>(Acceptance Rate: 23%)</strong>  
</td></tr>

<tr ><td style="font-size:inherit;"><strong>DATE 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;">  <u><b>Fangxin Liu=</b></u>, Haomin Li=, Zongwu Wang, Dongxu Lyu, and Li Jiang<br> <a href="#"> HyperDyn: Dynamic Dimensional Masking forEffcient Hyper-Dimensional Computing</a>  <strong>(Acceptance Rate: 21%)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>DATE 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Haomin Li=, Zewen Sun, Zongwu Wang, and Li Jiang <br> <a href="#"> HyperNeO: Efficient and AccurateHyper-Dimensional Regression via Neural Optimization</a> <strong>(Acceptance Rate: 21%)</strong>  
</td></tr>

<tr ><td style="font-size:inherit;"><strong>DATE 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"> Haomin Li=, <u><b>Fangxin Liu=</b></u>, Zongwu Wang, Dongxu Lyu, Shiyuan Huang, Ning Yang, Qi Sun, Zhuoran Song, and Li Jiang<br> <a href="#"> TAIL: Exploiting Temporal Asynchronous Execution for Efficient Spiking Neural Networks with Inter-Layer Parallelism</a>  <strong>(Acceptance Rate: 21%)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>DATE 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Ning Yang=, Zongwu Wang, Xuanpeng Zhu, Haidong Yao, Xiankui Xiong, Qi Sun, and Li Jiang <br> <a href="#"> OPS: Outlier-aware Precision-Slice Framework for LLM Acceleration</a>  <strong>(Acceptance Rate: 21%)</strong>  
</td></tr>

<tr ><td style="font-size:inherit;"><strong>DATE 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"> Zongwu Wang, <u><b>Fangxin Liu</b></u>, Peng Xu, Qingxiao Sun, Junping Zhao and Li Jiang <br> <a href="#">EVASION: Efficient KV Cache Compression via Product Quantization</a>  <strong>(Acceptance Rate: 21%)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>HPCA 2025</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Shiyuan Huang=, Ning Yang, Zongwu Wang, Haomin Li, and Li Jiang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10946829"> CROSS: Compiler-Driven Optimization of Sparse DNNs Using  Sparse/Dense Computation Kernels</a> <strong>(Acceptance Rate: 21%)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;"><strong>HPCA 2025</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"> Houshu he, Gang Li, <u><b>Fangxin Liu</b></u>, Li Jiang, Xiaoyang Liang, and Zhuoran Song <br> <a href="#"> GSArch: Breaking Memory Barriers in 3D Guassian  Splatting Training via Arcitectural Support</a>  <strong>(Acceptance Rate: 21%)</strong> 
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>IEEE TCAS-AI 2024</strong><br>(Imp. Jour. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Ning Yang=, <u><b>Fangxin Liu=</b></u>, Zongwu Wang, Junping Zhao, Li Jiang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10744537"> SearchQ: Search-based Fine-Grained Quantization for Data-Free Model Compression</a>  <font color=800e13><b>[Applied at HUAWEI]</b></font>
</td></tr>

<tr ><td style="font-size:inherit;"><strong>IEEE TODAES 2024</strong><br>(Imp. Jour. in Design Automation)</td><td style="font-size:inherit;"> Shiyuan Huang=, <u><b>Fangxin Liu=</b></u>, Tian Li, Zongwu Wang, Ning Yang, Haomin Li and Li Jiang <br> <a href="https://dl.acm.org/doi/abs/10.1145/3701033"> STCO: Enhancing Training Efficiency via Structured Sparse Tensor Compilation Optimization</a>  <strong>(CCF Tier B)</strong>  <font color=800e13><b>[Applied at Yizhu Tech.]</b></font>
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>ASP-DAC 2025</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Zongwu Wang=, Peng Xu, Shiyuan Huang and Li Jiang <br> <a href="https://dl.acm.org/doi/abs/10.1145/3658617.3697565"> Exploiting Differential-Based Data Encoding for Enhanced Query Efficiency</a>  <strong>(Acceptance Rate: 28%)</strong>
</td></tr>

<tr ><td style="font-size:inherit;"><strong>ASP-DAC 2025</strong><br>(Top. Conf. in Design Automation)</td><td style="font-size:inherit;"> Haomin Li=, <u><b>Fangxin Liu=</b></u>, Zewen Sun, Zongwu Wang, Shiyuan Huang, Ning Yang, and Li Jiang <br> <a href="https://dl.acm.org/doi/abs/10.1145/3658617.3697716"> NeuronQuant: Accurate and Efficient Post-Training Quantization for Spiking Neural Networks</a>  <strong>(Acceptance Rate: 28%)</strong>
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>IEEE TCAD 2024</strong><br>(Top Journal in Computer-Aided Design)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Shiyuan Huang, <u><b>Fangxin Liu*</b></u>, Tao Yang, Zongwu Wang Ning Yang, and Li Jiang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10640142"> SpMMPlu-Pro: An Enhanced Compiler Plug-In for Efficient SpMM and Sparsity Propagation Algorithm</a>  <strong>(CCF Tier A)</strong>
</td></tr>


<tr ><td style="font-size:inherit;"><strong>ICCD 2024</strong><br>(Import. Conf. in Computer Architecture)</td><td style="font-size:inherit;"> <u><b>Fangxin Liu=</b></u>, Ning Yang=, Zongwu Wang, Zhiyan Song, Tao Yang, and Li Jiang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10818081"> T-BUS: Taming Bipartite Unstructured Sparsity for Energy-Effcient DNN Acceleration</a>  <strong>(Acceptance Rate: 25%)</strong>
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>ICCD 2024</strong><br>(Import. Conf. in Computer Architecture)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Ning Yang=,Zhiyan Song, Zongwu Wang and Li Jiang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10817951"> HOLES: Boosting Large Language Models Efficiency with Hardware-friendly Lossless Encoding</a>  <strong>(Acceptance Rate: 25%)</strong>
</td></tr>


<tr ><td style="font-size:inherit;"><strong>ICCD 2024</strong><br>(Import. Conf. in Computer Architecture)</td><td style="font-size:inherit;"> Zongwu Wang=, <u><b>Fangxin Liu=</b></u>, and Li Jiang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10818108"> PS4:A Low Power SNN Accelerator with Spike Speculative Scheme</a>  <strong>(Acceptance Rate: 25%)</strong>
</td></tr>


<tr ><td bgcolor="#F7F7F7"><strong>ICCD 2024</strong><br>(Import. Conf. in Computer Architecture)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Longyu Zhao, Zongwu Wang, <u><b>Fangxin Liu*</b></u>, and Li Jiang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10818016"> Ninja: A Hardware Assisted System for Accelerating Nested Address Translation</a>  <strong>(Acceptance Rate: 25%)</strong>
</td></tr>


<tr ><td style="font-size:inherit;"><strong>MICRO 2024</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"> Zongwu Wang, <u><b>Fangxin Liu*</b></u>, Ning Yang, Shiyuan Huang, Haomin Li, and Li Jiang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10764497"> COMPASS: SRAM-Based Computing-in-Memory SNN Accelerator with  Adaptive Spike Speculation</a>  <strong>(Acceptance Rate: 22%)</strong>
</td></tr>


<tr ><td bgcolor="#F7F7F7"><strong>MICRO 2024</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Zhuoran Song, Houshu He,<u><b>Fangxin Liu*</b></u>, Yifan Hao, Xinkai Song, Li Jiang and Xiaoyao Liang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10764630"> SRender: Boosting Neural Radiance Field Efficiency via  Sensitivity-Aware Dynamic Precision Rendering</a>  <strong>(Acceptance Rate: 22%)</strong>
</td></tr>

<tr ><td style="font-size:inherit;"><strong>IEEE TPDS 2024</strong><br>(Top Journal in Computer Architecture)</td><td style="font-size:inherit;"> <u><b>Fangxin Liu</b></u>, Zongwu Wang, Wenbo Zhao, Ning Yang, Yongbiao Chen, Shiyuan Huang, Haomin Li, Tao Yang, Songwen Pei, Xiaoyao Liang,and Li Jiang <br> <a href="https://ieeexplore.ieee.org/document/10561563"> Exploiting Temporal-Unrolled Parallelism for Energy-Efficient SNN Acceleration</a>  <strong>(CCF Tier A)</strong>
</td></tr>


<tr ><td bgcolor="#F7F7F7"><strong>ISLPED 2024</strong><br>(Top Conf. in Low Power Design)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Zongwu Wang, <u><b>Fangxin Liu*</b></u>, Longyu Zhao, Shiyuan Huang and Li Jiang <br> <a href="https://dl.acm.org/doi/pdf/10.1145/3665314.3672279"> LowPASS: A Low power PIM-based accelerator with Speculative Scheme for SNNs</a>  <strong>(Acceptance Rate: 21%)</strong>
</td></tr>

<tr ><td style="font-size:inherit;"><strong>ISCA 2024</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"> Yilong Zhao, Mingyu Gao, <u><b>Fangxin Liu*</b></u>, Yiwei Hu, Zongwu Wang, Han Lin, Ji Li, He Xian, Hanlin Dong, Tao Yang, Naifeng Jing, Xiaoyao Liang, Li Jiang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10609641"> UM-PIM: DRAM-based PIM with Uniform & Shared Memory Space</a>  <strong>(Acceptance Rate: 18%)</strong>
</td></tr>


<tr ><td bgcolor="#F7F7F7"><strong>DAC 2024</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Ning Yang=, Haomin Li, Zongwu Wang, Zhuoran Song, Songwen Pei, Li Jiang <br> <a href="https://dl.acm.org/doi/abs/10.1145/3649329.3655896"> INSPIRE: Accelerating Deep Neural Networks via Hardware-friendly Index-Pair Encoding</a>  <strong>(Acceptance Rate: 23%)</strong>
</td></tr>

<tr ><td style="font-size:inherit;"><strong>DAC 2024</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"> <u><b>Fangxin Liu=</b></u>, Ning Yang=, Haomin Li, Zongwu Wang, Zhuoran Song, Songwen Pei, Li Jiang <br> <a href="https://dl.acm.org/doi/abs/10.1145/3649329.3655981">EOS: An Energy-Oriented Attack Framework for Spiking Neural Networks</a>  <strong>(Acceptance Rate: 23%)</strong>
</td></tr>

<tr ><td bgcolor="#F7F7F7"><strong>DATE 2024</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Jiahao Sun, <u><b>Fangxin Liu=</b></u>, Yijian Zhang, Li Jiang and Rui Yang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10546586">RTSA: An RRAM-TCAM based In-Memory-Search Accelerator for Sub-100 Î¼s Collision Detection</a>  <strong>(Acceptance Rate: 24%)</strong>
</td></tr>

<tr ><td style="font-size:inherit;"><strong>ASPLOS 2024</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"> Zhuoran Song, Chunyu Qi, <u><b>Fangxin Liu=</b></u>, Naifeng Jing, Xiaoyao Liang <br> <a href="https://dl.acm.org/doi/abs/10.1145/3620665.3640393">CMC: Video Transformer Acceleration via CODEC  Assisted Matrix Condensing</a>  <strong>(Acceptance Rate: 24%)</strong>
</td></tr>


<tr ><td bgcolor="#F7F7F7"><strong>HPCA 2024</strong><br>(Top Conf. in Computer Architecture)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Ning Yang=, Haomin Li, Zongwu Wang, Zhuoran Song, Songwen Pei, Li Jiang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10476472">SPARK: Scalable and Precision-Aware Acceleration of Neural  Networks via Efficient Encoding</a>  <strong>(Acceptance Rate: 18%)</strong>
</td></tr>

<tr ><td style="font-size:inherit;" ><strong>ASPDAC 2024</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;" > <u><b>Fangxin Liu=</b></u>, Haomin Li=, Ning Yang, Yichi Chen, Zongwu Wang, Tao Yang, Li Jiang <br> <a href="https://ieeexplore.ieee.org/abstract/document/10473823">PAAP-HD: PIM-Assisted Approximation for Efficient Hyper-Dimensional Computing</a> <strong>(Acceptance Rate: 29%)</strong>
</td></tr>

<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>ASPDAC 2024</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Haomin Li=, Ning Yang, Zongwu Wang, Tao Yang, Li Jiang <br> <a href="https://ieeexplore.ieee.org/document/10473984">TEAS: Exploiting Spiking Activity for Temporal-wise Adaptive Spiking Neural Networks</a>  <strong>(Acceptance Rate: 29%)</strong>
</td></tr>

<tr ><td style="font-size:inherit;" ><strong>ASPDAC 2024</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;" > Shiyuan Huang=, <u><b>Fangxin Liu=</b></u>, Tian Li, Zongwu Wang, Haomin Li, Li Jiang<br> <a href="https://ieeexplore.ieee.org/abstract/document/10473981">TSTC: Enabling Efficient Training via Structured Sparse Tensor Compilation</a>  <strong>(Acceptance Rate: 29%)</strong>
</td></tr>

<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>ASPDAC 2024</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Haomin Li=, <u><b>Fangxin Liu=</b></u>, Yichi Chen, Li Jiang<br> <a href="https://ieeexplore.ieee.org/abstract/document/10473907">HyperFeel: An Efficient Federated Learning Framework Using Hyperdimensional Computing</a>  <strong>(Acceptance Rate: 29%)</strong>
</td></tr>

<tr ><td style="font-size:inherit;"  ><strong>ICCD 2023</strong></td><td style="font-size:inherit;"  > <u><b>Fangxin Liu=</b></u>, Ning Yang=, Li Jiang<br> <a href="https://ieeexplore.ieee.org/abstract/document/10361000">PSQ: An Automatic Search Framework for Data-Free Quantization on PIM-based Architecture</a>  <strong>(Acceptance Rate: 28%)</strong>
</td></tr>

<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>ICCAD 2023</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Haomin Li=, <u><b>Fangxin Liu=</b></u>, Yichi Chen, Li Jiang<br> <a href="https://ieeexplore.ieee.org/abstract/document/10323813">HyperNode: An Efficient Node Classification Framework Using HyperDimensional Computing</a>  <strong>(Acceptance Rate: 23%)</strong>
</td></tr>


<tr ><td style="font-size:inherit;" ><strong>IEEE TC 2023</strong><br>(Top Journal in Computer Architecture)</td><td style="font-size:inherit;" > <u><b>Fangxin Liu</b></u>, Wenbo Zhao, Zongwu Wang, Yongbiao Chen, Xiaoyao Liang, Li Jiang<br> <a href="https://ieeexplore.ieee.org/document/10177200">ERA-BS: Boosting the Efficiency of ReRAM-based PIM Accelerator with Fine-Grained Bit-Level Sparsity</a>  <strong>(CCF Tier A)</strong>
</td></tr>


<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>DAC 2024</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Haomin Li=, Zongwu Wang, Yongbiao Chen, Li Jiang<br> <a href="https://ieeexplore.ieee.org/abstract/document/10247811">HyperAttack: An Efficient Attack Framework for HyperDimensional Computing</a>  <strong>(Acceptance Rate: 23%)</strong>
</td></tr>

<tr ><td style="font-size:inherit;" ><strong>ICCD 2022</strong></td><td style="font-size:inherit;" > <u><b>Fangxin Liu</b></u>, Zongwu Wang, Yongbiao Chen, Li Jiang<br> <a href="https://ieeexplore.ieee.org/abstract/document/9978437">Randomize and Match: Exploiting Irregular Sparsity for Energy Efficient Processing in SNNs</a>  <strong>(Acceptance Rate: 24%)</strong>
</td></tr>


<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>IEEE TCAD 2022</strong><br>(Top Journal in Computer-Aided Design)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu</b></u>, Zongwu Wang, Yongbiao Chen, Zhezhi He, Tao Yang, Xiaoyao Liang, Li Jiang<br> <a href="https://ieeexplore.ieee.org/document/9769275">SoBS-X: Squeeze-Out Bit Sparsity for ReRAM-Crossbar-Based Neural Network Accelerator</a>  <strong>(CCF Tier A)</strong>
</td></tr>


<tr ><td style="font-size:inherit;" ><strong>SIGIR 2022</strong><br>(Top Conf. in Information Retrieval)</td><td style="font-size:inherit;" > <u><b>Fangxin Liu</b></u>, Haomin Li, Xiaokang Yang, Li Jiang<br> <a href="https://dl.acm.org/doi/abs/10.1145/3477495.3531761">L3E-HD: A Framework Enabling Efficient Ensemble in High-Dimensional Space for Language Tasks</a>  <strong>(Acceptance Rate: 24%)</strong>
</td></tr>


<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>IEEE TCAD 2022</strong><br>(Top Journal in Computer-Aided Design)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Wenbo Zhao, Zongwu Wang, Yilong Zhao, Tao Yang, Yiran Chen, Li Jiang<br> <a href="https://ieeexplore.ieee.org/document/972425">IVQ: In-Memory Acceleration of DNN Inference Exploiting Varied Quantization</a>  <strong>(CCF Tier A)</strong>
</td></tr>

<tr ><td style="font-size:inherit;" ><strong>DAC 2022</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;" > <u><b>Fangxin Liu</b></u>, Wenbo Zhao, Zongwu Wang, Yongbiao Chen, Zhezhi He, Naifeng Jing, Xiaoyao Liang, Li Jiang<br> <a href="/files/%5BDAC-2022%5DEBSP_preprint.pdf">EBSP: Evolving Bit Sparsity Patterns for Hardware Friendly Inference of Quantized Deep Neural Networks</a>  <strong>(Acceptance Rate: 24.7%)</strong> 
</td></tr>


<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>DAC 2022</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Wenbo Zhao, Yongbiao Chen, Zongwu Wang, Zhezhi He, Rui Yang, Qidong Tang, Tao Yang, Cheng Zhuo<br> <a href="/files/%5BDAC-2022%5DPIM-DH_preprint.pdf">PIM-DH: ReRAM based Processing in Memory Architecture for Deep Hashing Acceleration</a> <strong>(Acceptance Rate: 24.7%)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;" ><strong>DAC 2022</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;" > <u><b>Fangxin Liu</b></u>, Wenbo Zhao, Zongwu Wang, Yongbiao Chen, Tao Yang, Zhezhi He, Xiaokang Yang, Li Jiang<br> <a href="/files/%5BDAC-2022%5DSATO_preprint.pdf">SATO: Spiking Neural Network Acceleration via Temporal Oriented Dataflow and Architecture</a> <strong>(Acceptance Rate: 24.7%)</strong> 
</td></tr>


<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>ICASSP 2022</strong><br>(Top Conf. in Signal Processing)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Wenbo Zhao, Yongbiao Chen, Zongwu Wang, Fei Dai<br> <a href="/files/%5BICASSP-22%5DDynSNN_preprint.pdf">Dynsnn: A dynamic approach to reduce redundancy in spiking neural networks</a> <strong>(CCF Tier B)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;" ><strong>AAAI'22 (Oral)</strong><br>(Top Conf. in Artificial Intelligence)</td><td style="font-size:inherit;" > <u><b>Fangxin Liu</b></u>, Wenbo Zhao*, Yongbiao Chen, Zongwu Wang, Li Jiang<br> <a href="https://ojs.aaai.org/index.php/AAAI/article/view/20061">SpikeConverter: An Efficient Conversion Framework Zipping the Gap between Artificial Neural Networks and Spiking Neural Networks</a> <strong>(Acceptance Rate: 15%)</strong> 
</td></tr>


<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>Frontiers in Neuroscience, 2021</strong><br>(SCI Tier 2)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Wenbo Zhao=, Yongbiao Chen, Zongwu Wang, Tao Yang, Li Jiang<br> <a href="https://www.frontiersin.org/articles/10.3389/fnins.2021.756876/full">SSTDP: Supervised Spike Timing Dependent Plasticity for Efficient Spiking Neural Network Training</a> <strong>(Impact Factor: 4.7)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;" ><strong>ICCD 2021</strong></td><td style="font-size:inherit;" > <u><b>Fangxin Liu</b></u>, Wenbo Zhao, Zhezhi He, Zongwu Wang, Yilong Zhao, Tao Yang, Jingnai Feng, Xiaoyao Liang, Li Jiang<br> <a href="https://ieeexplore.ieee.org/document/9643646">SME: ReRAM-based Sparse-Multiplication-Engine to Squeeze-Out Bit Sparsity of Neural Network</a> <strong>(Acceptance Rate: 24.4%)</strong> 
</td></tr>


<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>ICCV 2021</strong><br>(Top Conf. in Computer Vision)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Wenbo Zhao, Zhezhi He, Yanzhi Wang, Zongwu Wang, Changzhi Dai, Xiaoyao Liang, Li Jiang<br> <a href="https://openaccess.thecvf.com/content/ICCV2021/html/Liu_Improving_Neural_Network_Efficiency_via_Post-Training_Quantization_With_Adaptive_Floating-Point_ICCV_2021_paper.html">Improving Neural Network Efficiency via Post-training Quantization with Adaptive Floating-Point</a> <strong>(Acceptance Rate: 25.9%)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;" ><strong>ICCAD 2021</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;" > <u><b>Fangxin Liu</b></u>, Wenbo Zhao, Zhezhi He, Zongwu Wang, Yilong Zhao, Yongbiao Chen, Li Jiang<br> <a href="https://ieeexplore.ieee.org/document/9643569">Bit-Transformer: Transforming Bit-level Sparsity into Higher Preformance in ReRAM-based Accelerator</a> <strong>(Acceptance Rate: 23.5%)</strong> 
</td></tr>


<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>GLSVLSI 2021</strong></td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> <u><b>Fangxin Liu=</b></u>, Wenbo Zhao, Zongwu Wang, Tao Yang, Li Jiang<br> <a href="https://dl.acm.org/doi/abs/10.1145/3453688.3461491">IM3A: Boosting Deep Neural Network Efficiency via In-Memory Addressing-Assisted Acceleration</a> <strong>(Acceptance Rate: 24%)</strong> 
</td></tr>

<tr ><td style="font-size:inherit;" ><strong>ICMR 2022</strong></td><td style="font-size:inherit;" > Yongbiao Chen, <u><b>Fangxin Liu</b></u>, et al.<br> <a href="#">TransHash: Transformer-based Hamming Hashing for Efficient Image Retrieval</a>
</td></tr>


<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>ICMR 2022</strong></td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Yongbiao Chen, <u><b>Fangxin Liu</b></u>, et al.<br> <a href="#">Supervised Contrastive Vehicle Quantization for Efficient Vehicle Retrieval</a>
</td></tr>

<tr ><td style="font-size:inherit;" ><strong>DATE 2022</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;" > Zongwu Wang, <u><b>Fangxin Liu</b></u>, et al.<br> <a href="#">Self-Terminated Write of Multi-Level Cell ReRAM for Efficient Neuromorphic Computing</a> <strong>(Best Paper Award)</strong>
</td></tr>


<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>DATE 2022</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Tao Yang, <u><b>Fangxin Liu</b></u>, et al.<br> <a href="#">DTQAtten: Leveraging Dynamic Token-based Quantization for Efficient Attention Architecture</a> <strong>(Nominated for Best Paper)</strong>
</td></tr>

<tr ><td style="font-size:inherit;" ><strong>ASPDAC 2022</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;" > Qidong Tang, <u><b>Fangxin Liu</b></u>, et al.<br> <a href="#">HAWIS: Hardware-Aware Automated WIdth Search for Accurate, Energy-Efficient and Robust Binary Neural Network on ReRAM Dot-Product Engine</a>
</td></tr>


<tr ><td style="font-size:inherit;"  bgcolor="#F7F7F7"><strong>DAC 2022</strong><br>(Top Conf. in Design Automation)</td><td style="font-size:inherit;"  bgcolor="#F7F7F7"> Tao Yang, <u><b>Fangxin Liu</b></u>, et al.<br> <a href="#">PIMGCN: A ReRAM-based PIM Design for Graph Convolutional Network Acceleration</a>
</td></tr>

</table> -->


--------
<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
