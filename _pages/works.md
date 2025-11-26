---
layout: archive
title: "Selected Works"
permalink: /works/
author_profile: true
---

<style>
  /* 网格布局容器：自动适应屏幕宽度 */
  .video-gallery {
    display: grid;
    /* 核心代码：列宽最小300px，空间够就自动并排，空间不够就单列 */
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); 
    gap: 30px; /* 视频之间的间距 */
    margin-top: 20px;
  }

  /* 单个视频卡片的样式 */
  .video-item {
    background: #f9f9f9;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    transition: transform 0.2s; /* 鼠标悬停时的动效 */
  }
  
  /* 鼠标悬停微微上浮，增加交互感 */
  .video-item:hover {
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  }

  .video-item h3 {
    margin-top: 0;
    margin-bottom: 10px;
    font-size: 1rem;
    line-height: 1.4;
    border-bottom: none;
    color: #333;
  }

  /* 重点推荐作品样式：在宽屏下横跨所有列 */
  .featured-item {
    grid-column: 1 / -1;
    background: #fff;
    border: 2px solid #eaeaea;
  }
  
  .featured-item h3 {
    font-size: 1.4em;
    color: #d9534f; /* 突出显示的标题颜色 */
  }

  /* 视频标签通用设置 */
  video {
    width: 100%;
    border-radius: 4px;
    background: #000; /* 视频加载前的黑底 */
    aspect-ratio: 16/9; /* 强制保持16:9比例，防止抖动 */
  }
</style>

<div class="video-gallery">

  <div class="video-item featured-item">
    <h3>🏆 代表作：《万火归一》 (FIRST影展提名)</h3>
    <video controls preload="metadata" poster="/images/poster_wanhuo.jpg">
      <source src="https://work.huyang.online/%E3%80%8A%E4%B8%87%E7%81%AB%E5%BD%92%E4%B8%80%E3%80%8B.mp4" type="video/mp4">
    </video>
    <p style="font-size:0.9em; color:#666; margin-top:8px;">
      <b>Role:</b> Producer <br>
      入围第47届莫斯科国际影像节 | FIRST青年影展最佳短片提名
    </p>
  </div>

  <div class="video-item">
    <h3>《天下无毒·光明永驻》</h3>
    <video controls preload="metadata">
      <source src="https://work.huyang.online/%E3%80%8A%E5%A4%A9%E4%B8%8B%E6%97%A0%E6%AF%92%C2%B7%E5%85%89%E6%98%8E%E6%B0%B8%E9%A9%BB%E3%80%8B.mp4" type="video/mp4">
    </video>
  </div>

  <div class="video-item">
    <h3>《2107学兵连》</h3>
    <video controls preload="metadata">
      <source src="https://work.huyang.online/%E3%80%8A2107%E5%AD%A6%E5%85%B5%E8%BF%9E%E3%80%8B.mp4" type="video/mp4">
    </video>
  </div>

  <div class="video-item">
    <h3>《西安高新硬科技创新示范区》</h3>
    <video controls preload="metadata">
      <source src="https://work.huyang.online/%E3%80%8A%E8%A5%BF%E5%AE%89%E9%AB%98%E6%96%B0%E7%A1%AC%E7%A7%91%E6%8A%80%E5%88%9B%E6%96%B0%E7%A4%BA%E8%8C%83%E5%8C%BA%E3%80%8B.mp4" type="video/mp4">
    </video>
  </div>

  <div class="video-item">
    <h3>《邮梦启航》</h3>
    <video controls preload="metadata">
      <source src="https://work.huyang.online/%E3%80%8A%E9%82%AE%E6%A2%A6%E5%90%AF%E8%88%AA%E3%80%8B.mp4" type="video/mp4">
    </video>
  </div>

  <div class="video-item">
    <h3>《人生不过词九片》</h3>
    <video controls preload="metadata">
      <source src="https://work.huyang.online/%E3%80%8A%E4%BA%BA%E7%94%9F%E4%B8%8D%E8%BF%87%E8%AF%8D%E4%B9%9D%E7%89%87%E3%80%8B.mp4" type="video/mp4">
    </video>
  </div>

  <div class="video-item">
    <h3>《塬》</h3>
    <video controls preload="metadata">
      <source src="https://work.huyang.online/%E3%80%8A%E5%A1%AC%E3%80%8B.mp4" type="video/mp4">
    </video>
  </div>

  <div class="video-item">
    <h3>《方》</h3>
    <video controls preload="metadata">
      <source src="https://work.huyang.online/%E3%80%8A%E6%96%B9%E3%80%8B.mp4" type="video/mp4">
    </video>
  </div>

  <div class="video-item">
    <h3>《晚归》</h3>
    <video controls preload="metadata">
      <source src="https://work.huyang.online/%E3%80%8A%E6%99%9A%E5%BD%92%E3%80%8B.mp4" type="video/mp4">
    </video>
  </div>

  <div class="video-item">
    <h3>《秋雨》</h3>
    <video controls preload="metadata">
      <source src="https://work.huyang.online/%E3%80%8A%E7%A7%8B%E9%9B%A8%E3%80%8B.mp4" type="video/mp4">
    </video>
  </div>

  <div class="video-item">
    <h3>《窗外》</h3>
    <video controls preload="metadata">
      <source src="https://work.huyang.online/%E3%80%8A%E7%AA%97%E5%A4%96%E3%80%8B.mp4" type="video/mp4">
    </video>
  </div>

</div>
