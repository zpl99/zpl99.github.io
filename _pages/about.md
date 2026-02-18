---
permalink: /
title: "Zeping Liu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.home-redesign {
  --ink: #1f2933;
  --muted: #5f6b76;
  --accent: #0f9cb1;
  --accent-strong: #0b7285;
  --line: #d9e7ed;
  --card: #ffffff;
  --soft-bg: linear-gradient(130deg, #f7fcfe 0%, #ecf5fa 55%, #f8fbff 100%);
  color: var(--ink);
}

.home-redesign .hero {
  background: var(--soft-bg);
  border: 1px solid var(--line);
  border-radius: 20px;
  padding: 2.2rem;
  box-shadow: 0 16px 36px rgba(12, 76, 99, 0.08);
  position: relative;
  overflow: hidden;
  margin-bottom: 1.5rem;
}

.home-redesign .hero:after {
  content: "";
  position: absolute;
  right: -70px;
  top: -70px;
  width: 220px;
  height: 220px;
  border-radius: 999px;
  background: radial-gradient(circle, rgba(15, 156, 177, 0.2) 0%, rgba(15, 156, 177, 0) 72%);
}

.home-redesign .eyebrow {
  margin: 0 0 0.5rem;
  color: var(--accent-strong);
  letter-spacing: 0.08em;
  text-transform: uppercase;
  font-size: 0.78rem;
  font-weight: 700;
}

.home-redesign h1 {
  margin: 0;
  font-size: 2.1rem;
  line-height: 1.1;
}

.home-redesign .hero p {
  color: var(--muted);
}

.home-redesign .tag-row {
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
  margin: 1rem 0 0.2rem;
}

.home-redesign .tag {
  border: 1px solid rgba(15, 156, 177, 0.28);
  color: var(--accent-strong);
  border-radius: 999px;
  font-size: 0.82rem;
  font-weight: 700;
  padding: 0.28rem 0.7rem;
  background: rgba(255, 255, 255, 0.72);
}

.home-redesign .cta-row {
  margin-top: 1rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.7rem;
}

.home-redesign .cta {
  display: inline-block;
  border-radius: 10px;
  padding: 0.48rem 0.82rem;
  border: 1px solid var(--line);
  background: #fff;
  color: var(--ink);
  text-decoration: none;
  font-weight: 700;
}

.home-redesign .cta:hover {
  border-color: var(--accent);
  color: var(--accent-strong);
}

.home-redesign .fellowship {
  margin-top: 0.9rem;
  font-weight: 700;
  color: var(--accent-strong);
}

.home-redesign .panel {
  background: var(--card);
  border: 1px solid var(--line);
  border-radius: 16px;
  padding: 1.25rem 1.35rem;
  margin-bottom: 1.1rem;
}

.home-redesign .panel h2 {
  margin-top: 0;
  margin-bottom: 0.85rem;
  font-size: 1.25rem;
}

.home-redesign .panel-note {
  margin-top: -0.15rem;
  margin-bottom: 1rem;
  color: var(--muted);
  font-size: 0.92rem;
}

.home-redesign .pub-item {
  border-left: 3px solid rgba(15, 156, 177, 0.35);
  padding-left: 0.85rem;
  margin: 0.85rem 0;
}

.home-redesign .pub-item h3 {
  margin: 0;
  font-size: 1.02rem;
}

.home-redesign .pub-item p {
  margin: 0.22rem 0 0;
  color: var(--muted);
  font-size: 0.92rem;
}

.home-redesign .grid-2 {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
}

.home-redesign .timeline-item {
  border-left: 2px solid rgba(15, 156, 177, 0.28);
  padding-left: 0.75rem;
  margin-bottom: 0.95rem;
}

.home-redesign .timeline-item h3 {
  margin: 0;
  font-size: 1rem;
}

.home-redesign .timeline-item p {
  margin: 0.22rem 0 0;
  color: var(--muted);
}

.home-redesign .award-list {
  margin: 0;
  padding-left: 1rem;
}

.home-redesign .award-list li {
  margin-bottom: 0.45rem;
}

.home-redesign .chip-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 0.6rem;
}

.home-redesign .chip {
  border: 1px solid var(--line);
  border-radius: 10px;
  padding: 0.55rem 0.65rem;
  background: linear-gradient(180deg, #ffffff 0%, #f7fbfd 100%);
  font-weight: 600;
}

.home-redesign .footer-note {
  color: var(--muted);
  font-size: 0.88rem;
  margin-top: 0.7rem;
}

@media (max-width: 850px) {
  .home-redesign h1 {
    font-size: 1.75rem;
  }

  .home-redesign .hero {
    padding: 1.4rem;
  }

  .home-redesign .grid-2,
  .home-redesign .chip-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="home-redesign">
  <section class="hero">
    <p class="eyebrow">Geospatial AI + Earth Observation</p>
    <h1>Zeping Liu</h1>
    <p>
      I am a second-year Ph.D. student in the Department of Geography and the Environment at the
      University of Texas at Austin, advised by <a href="https://gengchenmai.github.io/">Dr. Gengchen Mai</a>.
      My research focuses on Geospatial AI and Intelligent Earth Observation, with emphasis on
      geo-foundation models, spatial representation learning, and efficient large-scale high-resolution mapping.
    </p>

    <div class="tag-row">
      <span class="tag">Geo-foundation models</span>
      <span class="tag">Spatial representation learning</span>
      <span class="tag">Remote sensing mapping</span>
      <span class="tag">Multimodal geospatial learning</span>
    </div>

    <div class="cta-row">
      <a class="cta" href="https://drive.google.com/file/d/1dGAW29XeQNQu1OvVq1A842ZSXlrXVZEl/view?usp=sharing">CV</a>
      <a class="cta" href="https://scholar.google.com/citations?user=eSeCaz4AAAAJ">Google Scholar</a>
      <a class="cta" href="https://github.com/zpl99">GitHub</a>
      <a class="cta" href="mailto:zeping.liu@utexas.edu">Email</a>
    </div>

    <p class="fellowship">
      Amazon AI PhD Fellow (2025-2027)
    </p>
  </section>

  <section class="panel">
    <h2>Selected Publications</h2>
    <p class="panel-note">For complete records, see the Publications page.</p>

    <article class="pub-item">
      <h3><a href="https://openreview.net/pdf?id=ghybX0Qlls">LocDiff: Identifying Locations on Earth by Diffusing in the Hilbert Space</a></h3>
      <p>Zhangyu Wang, <strong>Zeping Liu</strong>, et al. Neurips 2025.</p>
    </article>

    <article class="pub-item">
      <h3><a href="https://arxiv.org/abs/2503.16683">GAIR: Improving Multimodal Geo-Foundation Model with Geo-Aligned Implicit Representations</a></h3>
      <p><strong>Zeping Liu</strong>, Fan Zhang, Junfeng Jiao, Ni Lao, Gengchen Mai. arXiv 2025.</p>
    </article>

    <article class="pub-item">
      <h3><a href="https://www.sciencedirect.com/science/article/pii/S1569843225000159">Towards the Next Generation of Geospatial Artificial Intelligence</a></h3>
      <p>Gengchen Mai, Yiqun Xie, Xiaowei Jia, et al. International Journal of Applied Earth Observation and Geoinformation, 2025.</p>
    </article>

    <article class="pub-item">
      <h3><a href="https://arxiv.org/abs/2406.15658">Torchspatial: A Location Encoding Framework and Benchmark for Spatial Representation Learning</a></h3>
      <p>Nemin Wu, Qian Cao, Zhangyu Wang, <strong>Zeping Liu</strong>, et al. Neurips 2024 Dataset Benchmark.</p>
    </article>

    <article class="pub-item">
      <h3><a href="https://www.sciencedirect.com/science/article/pii/S0034425724000282">Four Seasonal Composite Sentinel-2 Images for Large-Scale Building Story Estimation</a></h3>
      <p>Siqing Lyu, Chao Ji, <strong>Zeping Liu</strong>, Hong Tang, Liqiang Zhang, Xin Yang. Remote Sensing of Environment, 2024.</p>
    </article>

    <article class="pub-item">
      <h3><a href="https://www.sciencedirect.com/science/article/pii/S0048969724065793">CALIPSO-Based Aerosol Extinction Profile Estimation from MODIS and MERRA-2 with Transformer + CNN</a></h3>
      <p>Yang Zhen, Xin Yang, Hong Tang, Haoze Shi, <strong>Zeping Liu</strong>. Science of The Total Environment, 2024.</p>
    </article>

    <article class="pub-item">
      <h3><a href="https://essd.copernicus.org/articles/15/3547/2023/essd-15-3547-2023.html">China Building Rooftop Area: A Multi-Annual High-Resolution Dataset (2016-2021)</a></h3>
      <p><strong>Zeping Liu</strong>, Hong Tang, Lin Feng, Siqing Lyu. Earth System Science Data, 2023.</p>
    </article>

    <article class="pub-item">
      <h3><a href="https://www.tandfonline.com/doi/pdf/10.1080/15481603.2023.2196154">National-Scale Mapping of Building Footprints with Feature Super-Resolution Segmentation</a></h3>
      <p>Lin Feng, Penglei Xu, Hong Tang, <strong>Zeping Liu</strong>, Peng Hou. GIScience &amp; Remote Sensing, 2023.</p>
    </article>

    <article class="pub-item">
      <h3><a href="https://www.mdpi.com/2072-4292/15/7/1741">Learning Sparse Geometric Features for Building Segmentation from Low-Resolution Remote-Sensing Images</a></h3>
      <p><strong>Zeping Liu</strong>, Hong Tang. Remote Sensing, 2023.</p>
    </article>

    <article class="pub-item">
      <h3><a href="https://drive.google.com/file/d/1cV8hM7Ad_OOYLTwzjnpCml9QWrWJZeVn/view">Building Outline Delineation from VHR Images with CRNN + Line Segment Information</a></h3>
      <p><strong>Zeping Liu</strong>, Hong Tang, Wei Huang. IEEE TGRS, 2022.</p>
    </article>

    <article class="pub-item">
      <h3><a href="https://drive.google.com/file/d/1cV8hM7Ad_OOYLTwzjnpCml9QWrWJZeVn/view">Sequential Delineation of Rooftops with Holes from VHR Aerial Images</a></h3>
      <p>Wei Huang, <strong>Zeping Liu</strong>, Hong Tang, Jiayi Ge. Remote Sensing, 2021.</p>
    </article>

    <article class="pub-item">
      <h3><a href="https://link.springer.com/chapter/10.1007/978-3-030-88007-1_39">AFM-RNN: A Sequence Prediction Model for Delineating Building Rooftops</a></h3>
      <p><strong>Zeping Liu</strong>, Hong Tang, Wei Huang. Chinese Conference on Pattern Recognition and Computer Vision, 2021.</p>
    </article>
  </section>

  <section class="grid-2">
    <div class="panel">
      <h2>Industry Experience</h2>

      <div class="timeline-item">
        <h3>Intern, Esri Inc. (Part-time)</h3>
        <p>19 Aug 2025 - 7 Nov 2025</p>
        <p>Worked on the Spatial Co-Scientist project.</p>
      </div>

      <div class="timeline-item">
        <h3>Intern, Esri Inc. (Full-time)</h3>
        <p>20 May 2025 - 8 Aug 2025</p>
        <p>
          Developed Spatial Co-Scientist with Esri Generative AI Toolkit, combining RAG,
          LLM reasoning, and ArcGIS Pro workflows for practical spatial analysis;
          also collected expert interview insights and designed guided analysis flows.
        </p>
      </div>
    </div>

    <div class="panel">
      <h2>Awards</h2>
      <ul class="award-list">
        <li>Amazon AI PhD Fellowship (2025-2027)</li>
        <li>Second Place, UT GIS Day Student Presentation Competition (2024)</li>
        <li>Outstanding Graduate Student of Beijing (2024)</li>
        <li>Zhou Tingru Geography Youth Award (2024)</li>
        <li>First Prize, Graduate Academic Forum of National Remote Sensing Bulletin (2023)</li>
        <li>National Scholarship, Ministry of Education (China) (2023)</li>
        <li>National Scholarship, Ministry of Education (China) (2022)</li>
      </ul>
    </div>
  </section>

  <section class="panel">
    <h2>Reviewer Service</h2>
    <div class="chip-grid">
      <div class="chip">Scientific Reports</div>
      <div class="chip">Earth Science Informatics</div>
      <div class="chip">International Journal of Applied Earth Observation and Geoinformation</div>
      <div class="chip">Signal, Image and Video Processing</div>
      <div class="chip">Geocarto International</div>
      <div class="chip">Frontiers in Remote Sensing</div>
      <div class="chip">Geo-spatial Information Science</div>
    </div>

    <p class="footer-note">
      <a href="https://info.flagcounter.com/JzHz">Visitor map</a>
    </p>
  </section>
</div>
