---
layout: default
title: Blog
---

<style>
  .blog-hero {
    text-align: center;
    padding: 3rem 1rem 2rem;
    border-bottom: 1px solid #e1e4e8;
    margin-bottom: 2.5rem;
  }
  .blog-hero h1 {
    font-size: 2.2rem;
    font-weight: 700;
    margin-bottom: 0.5rem;
    color: #24292e;
  }
  .blog-hero .subtitle {
    color: #586069;
    font-size: 1.1rem;
    max-width: 600px;
    margin: 0 auto;
    line-height: 1.6;
  }

  .post-card {
    display: flex;
    align-items: flex-start;
    padding: 1.5rem;
    margin-bottom: 1rem;
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    background: #ffffff;
    transition: all 0.2s ease;
    text-decoration: none !important;
  }
  .post-card:hover {
    border-color: #0366d6;
    box-shadow: 0 4px 12px rgba(3, 102, 214, 0.1);
    transform: translateY(-2px);
  }

  .post-date {
    min-width: 80px;
    text-align: center;
    margin-right: 1.5rem;
    padding: 0.5rem 0.8rem;
    background: #f6f8fa;
    border-radius: 8px;
    flex-shrink: 0;
  }
  .post-date .day {
    display: block;
    font-size: 1.5rem;
    font-weight: 700;
    color: #24292e;
    line-height: 1;
  }
  .post-date .month {
    display: block;
    font-size: 0.75rem;
    color: #586069;
    text-transform: uppercase;
    margin-top: 0.2rem;
    letter-spacing: 0.5px;
  }

  .post-content {
    flex: 1;
  }
  .post-title {
    font-size: 1.25rem;
    font-weight: 600;
    color: #0366d6;
    margin-bottom: 0.5rem;
    line-height: 1.4;
  }
  .post-excerpt {
    color: #586069;
    font-size: 0.95rem;
    line-height: 1.6;
    margin-bottom: 0.75rem;
  }

  .post-meta {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 0.5rem;
  }
  .tag {
    display: inline-block;
    padding: 0.2rem 0.6rem;
    font-size: 0.75rem;
    font-weight: 500;
    border-radius: 20px;
    background: #ddf4ff;
    color: #0969da;
    border: 1px solid #b6e3ff;
  }
  .tag-embodied { background: #fff8c5; color: #7a5c00; border-color: #f0d77a; }
  .tag-vla { background: #ffebe9; color: #9e2a2b; border-color: #ffc0c0; }
  .tag-survey { background: #dafbe1; color: #1a7f37; border-color: #a6e6b6; }

  .year-divider {
    display: flex;
    align-items: center;
    margin: 2.5rem 0 1.5rem;
  }
  .year-divider::before {
    content: "";
    flex: 1;
    height: 1px;
    background: #e1e4e8;
    margin-right: 1rem;
  }
  .year-divider .year-label {
    font-size: 0.85rem;
    font-weight: 600;
    color: #8c959f;
    background: #f6f8fa;
    padding: 0.3rem 0.8rem;
    border-radius: 20px;
    border: 1px solid #e1e4e8;
  }

  .author-footer {
    margin-top: 3rem;
    padding: 2rem;
    background: #f6f8fa;
    border-radius: 12px;
    text-align: center;
  }
  .author-footer h3 {
    margin-top: 0;
    color: #24292e;
  }
  .author-links {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin-top: 1rem;
    flex-wrap: wrap;
  }
  .author-links a {
    color: #0366d6;
    text-decoration: none;
    font-weight: 500;
  }
  .author-links a:hover {
    text-decoration: underline;
  }

  @media (max-width: 600px) {
    .post-card {
      flex-direction: column;
    }
    .post-date {
      margin-right: 0;
      margin-bottom: 1rem;
      display: flex;
      align-items: baseline;
      gap: 0.5rem;
      min-width: auto;
    }
    .post-date .day, .post-date .month {
      display: inline;
      font-size: 1rem;
    }
  }
</style>

<div class="blog-hero">
  <h1>📝 技术博客</h1>
  <p class="subtitle">
    记录大模型、视频生成、世界模型与具身智能领域的前沿洞察与深度思考
  </p>
</div>

<div class="year-divider">
  <span class="year-label">📅 2025</span>
</div>

<a href="https://blog.csdn.net/sdlcjx/article/details/160696022" class="post-card" target="_blank">
  <div class="post-date">
    <span class="day">04</span>
    <span class="month">2025</span>
  </div>
  <div class="post-content">
    <div class="post-title">
      VLA视觉-语言-动作模型数据：机器人数据基础设施的全景解析
    </div>
    <div class="post-excerpt">
      基于 Wang et al., arXiv:2604.23001 最新综述，系统梳理 VLA 研究三大支柱——数据集、基准测试与数据引擎。深入剖析真实世界与合成数据的 fidelity-cost 权衡困境，探讨从视频到数据引擎、硬件辅助采集到生成式数据引擎的技术演进路径。
    </div>
    <div class="post-meta">
      <span class="tag tag-survey">📊 综述</span>
      <span class="tag tag-embodied">🤖 具身智能</span>
      <span class="tag tag-vla">🔗 VLA</span>
      <span class="tag">⚙️ 数据引擎</span>
      <span class="tag">🧠 世界模型</span>
    </div>
  </div>
</a>

<!-- 后续文章可按相同格式追加 -->
<!-- 
<div class="year-divider">
  <span class="year-label">📅 2024</span>
</div>
-->

<div class="author-footer">
  <h3>👤 关于作者</h3>
  <p>
    <strong>金鑫博士</strong> · 华为云盘古多模态大模型首席架构师<br>
    华为云视频生成大模型、世界模型团队主管
  </p>
  <div class="author-links">
    <a href="https://jinxindeep.github.io/">🏠 个人主页</a>
    <a href="mailto:sdjinxin@gmail.com">📧 电子邮件</a>
    <a href="https://blog.csdn.net/sdlcjx">📖 CSDN 博客</a>
  </div>
  <p style="margin-top: 1.5rem; color: #8c959f; font-size: 0.85rem;">
    持续更新中，敬请期待更多技术分享 🚀
  </p>
</div>
