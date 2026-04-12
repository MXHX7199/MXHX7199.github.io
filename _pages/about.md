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
  .pub-container { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; color: #333; line-height: 1.6; }
  
  /* 统计看板：进化版 - 侧重工业应用 */
  .stats-board {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 12px;
    margin: 30px 0;
    padding: 22px 15px;
    background: linear-gradient(145deg, #ffffff, #f9f9f9);
    border-radius: 12px;
    border: 1px solid #eee;
    box-shadow: 0 4px 12px rgba(0,0,0,0.03);
  }
  .stat-card { text-align: center; border-right: 1px solid #eee; }
  .stat-card:last-child { border-right: none; }
  .stat-num {
    display: block;
    font-size: 26px;
    font-weight: 900;
    color: #538F79;
    font-family: "Arial Black", sans-serif;
    line-height: 1.2;
  }
  .stat-label {
    display: block;
    font-size: 13px;
    font-weight: 700;
    color: #222;
    margin-top: 5px;
  }
  .stat-sub {
    font-size: 10px;
    color: #999;
    line-height: 1.2;
    margin-top: 3px;
    display: block;
  }

  /* News 列表：保持严格间距与链接颜色 */
  .news-box { margin-top: 25px; }
  .news-item {
    display: flex;
    margin-bottom: 20px;
    align-items: flex-start;
  }
  .news-date {
    font-family: 'Courier New', Courier, monospace;
    font-size: 12.5px;
    font-weight: 700;
    color: #538F79;
    background: #f0f4f2;
    padding: 2px 6px;
    border-radius: 4px;
    margin-right: 15px;
    min-width: 110px;
    text-align: center;
    flex-shrink: 0;
  }
  .news-text { font-size: 14.5px; flex: 1; color: #444; }
  .news-text a { color: #1a73e8; text-decoration: none; }
  .news-text a:hover { text-decoration: underline; }
  
  summary { cursor: pointer; color: #538F79; font-weight: bold; padding: 10px 0; outline: none; }

  @media (max-width: 768px) {
    .stats-board { grid-template-columns: 1fr 1fr; gap: 20px; }
    .stat-card:nth-child(even) { border-right: none; }
    .news-item { flex-direction: column; }
    .news-date { margin-bottom: 8px; }
  }
</style>

Fangxin (Leon) Liu is an **Assistant Professor** and **Ph.D. supervisor** in the School of Computer Science at **Shanghai Jiao Tong University (SJTU)**. I also serve as a Research Fellow at the **Shanghai Qi Zhi Institute**. My research interests include neural network acceleration (e.g., mixed-precision computing and SW/HW co-design), in-memory computing, and brain-inspired neuromorphic computing.

I received my Ph.D. degree from SJTU in 2023, advised by **Prof. Li Jiang**. To date, I have published over **60 papers** as **first or corresponding author**, with more than **40 in CCF Tier A** venues, including top-tier architecture conferences and journals such as **ISCA, MICRO, ASPLOS, HPCA, PPoPP, DAC, IEEE TC, TPDS, and TCAD**. My work has been recognized with honors such as the **Spark Award from HUAWEI**, the **Outstanding Doctoral Dissertation Award** from the Shanghai Computer Society, the **ACM China Shanghai Excellent Doctoral Dissertation Award**, and the **Best Paper Award at DATE 2022**.

<div class="stats-board">
  <div class="stat-card">
    <span class="stat-num" style="color:#222;">40+</span>
    <span class="stat-label">CCF Tier A</span>
    <span class="stat-sub">as 1st or Corr. Author</span>
  </div>
  <div class="stat-card">
    <span class="stat-num">60+</span>
    <span class="stat-label">Total Pubs</span>
    <span class="stat-sub">as 1st or Corr. Author</span>
  </div>
  <div class="stat-card">
    <span class="stat-num">5+</span>
    <span class="stat-label">Industrial Adoption</span>
    <span class="stat-sub">Applied at Huawei, Ant, etc.</span>
  </div>
  <div class="stat-card">
    <span class="stat-num" style="color:#d48806;">5+</span>
    <span class="stat-label">Major Awards</span>
    <span class="stat-sub">Best Paper/Dissert.</span>
  </div>
</div>

My research has been successfully adopted by leading technology companies, including <font color=538F79><b>Huawei, Ant Group, ZTE, and Yizhu Tech.</b></font>, to advance real-world applications such as efficient LLM inference, low-precision deployment, and optimized AI compilation. For instance, my work on mixed-precision computing and SW/HW co-design has enabled up to **40% reductions** in computational costs for large-scale AI deployments. I am committed to bridging cutting-edge research with practical industry solutions and welcome opportunities for further collaboration.

---

### 🔥 Recruitment
Our [team](https://www.cs.sjtu.edu.cn/yjjg/818.html) is actively seeking self-motivated **PhD, Master, and Undergraduate students** interested in Computer Architecture, Efficient AI acceleration, and PIM Design. If you are interested, please [email me](mailto:liufangxin@sjtu.edu.cn) your CV.

---

### News
<div class="news-box">
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

### Research
His research bridges the gap between **Cutting-edge Architecture** and **Practical AI Solutions**, focusing on:
* **LLM & Generative AI Acceleration** (Mixed-precision, Quantization, MoE)
* **In-Memory Computing** (RRAM/DRAM-based PIM/CiM)
* **Brain-inspired Computing** (Spiking Neural Networks, HDC)
* **AI Compilation & HW/SW Co-design**

Recent Visits to this Site
-----------

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=tt&d=sNUIIgL1WU3gnVp7Lq7JpnhV-2YGPzHk9c4NSyeNuIc&co=4c98ce'></script>