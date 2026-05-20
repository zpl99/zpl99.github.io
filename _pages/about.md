---
permalink: /
# title: "Zeping Liu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.about-minimal {
  --ink: #0f1620;
  --ink-soft: #2a3340;
  --muted: #5a6573;
  --faint: #8a94a3;
  --line: #e2e6ec;
  --line-strong: #c9d0d9;
  --accent: #0f4c81;
  --accent-soft: #eaf1f8;
  --bg-soft: #fafbfc;
  color: var(--ink);
  font-family: "Source Serif 4", "Iowan Old Style", "Palatino Linotype", "Book Antiqua", Palatino, serif;
  font-feature-settings: "kern", "liga", "onum";
}

.about-minimal a {
  color: var(--ink);
  text-decoration: none;
  background-image: linear-gradient(var(--accent), var(--accent));
  background-size: 0 1px;
  background-repeat: no-repeat;
  background-position: 0 100%;
  transition: background-size 0.25s ease, color 0.2s ease;
}

.about-minimal a:hover {
  color: var(--accent);
  background-size: 100% 1px;
}

.about-minimal .intro {
  border-bottom: 1px solid var(--line);
  padding-bottom: 1.5rem;
  margin-bottom: 1.6rem;
}

.about-minimal h1 {
  margin: 0 0 0.7rem;
  font-size: 2.15rem;
  line-height: 1.12;
  font-weight: 700;
  letter-spacing: -0.01em;
}

.about-minimal .lead {
  margin: 0;
  font-size: 1.07rem;
  line-height: 1.75;
  color: var(--ink-soft);
}

.about-minimal .fellowship {
  margin: 0.85rem 0 0;
  display: inline-block;
  padding: 0.28rem 0.7rem;
  background: var(--accent-soft);
  color: var(--accent);
  font-weight: 700;
  font-size: 0.88rem;
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  border-radius: 4px;
  letter-spacing: 0.01em;
}

.about-minimal .quick-links {
  margin-top: 1.05rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
}

.about-minimal .quick-links a {
  border: 1px solid var(--line-strong);
  border-radius: 999px;
  padding: 0.32rem 0.85rem;
  font-size: 0.85rem;
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  font-weight: 500;
  color: var(--ink-soft);
  background-image: none;
  transition: border-color 0.2s ease, color 0.2s ease, background 0.2s ease;
}

.about-minimal .quick-links a:hover {
  border-color: var(--accent);
  color: var(--accent);
  background: var(--accent-soft);
}

.about-minimal .section {
  margin: 1.85rem 0;
}

.about-minimal .section-title {
  margin: 0 0 1rem;
  padding-bottom: 0.55rem;
  border-bottom: 1px solid var(--line);
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  font-size: 0.82rem;
  font-weight: 700;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  color: var(--ink);
  display: flex;
  align-items: baseline;
  justify-content: space-between;
}

.about-minimal .section-title .count {
  font-weight: 500;
  color: var(--faint);
  letter-spacing: 0.06em;
  font-size: 0.78rem;
}

.about-minimal .publication-list {
  list-style: none;
  margin: 0;
  padding: 0;
  counter-reset: pub;
}

.about-minimal .publication-list li {
  display: grid;
  grid-template-columns: 3.4rem 1fr;
  gap: 0.4rem 0.9rem;
  padding: 0.65rem 0;
  border-bottom: 1px dashed var(--line);
}

.about-minimal .publication-list li:last-child {
  border-bottom: none;
}

.about-minimal .pub-year {
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  font-size: 0.78rem;
  font-weight: 700;
  letter-spacing: 0.05em;
  color: var(--faint);
  padding-top: 0.18rem;
}

.about-minimal .pub-body {
  min-width: 0;
}

.about-minimal .pub-title {
  margin: 0;
  line-height: 1.45;
  font-weight: 600;
  font-size: 1rem;
}

.about-minimal .pub-meta {
  margin: 0.22rem 0 0;
  line-height: 1.5;
  font-size: 0.9rem;
  color: var(--muted);
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
}

.about-minimal .pub-meta .me {
  color: var(--ink);
  font-weight: 700;
}

.about-minimal .pub-meta .venue {
  font-style: italic;
  color: var(--ink-soft);
}

.about-minimal .two-col {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 2rem;
}

.about-minimal .item {
  margin-bottom: 1.1rem;
  padding-bottom: 1.1rem;
  border-bottom: 1px dashed var(--line);
}

.about-minimal .item:last-child {
  margin-bottom: 0;
  padding-bottom: 0;
  border-bottom: none;
}

.about-minimal .item-head {
  display: flex;
  flex-wrap: wrap;
  align-items: baseline;
  gap: 0.55rem;
  margin-bottom: 0.35rem;
}

.about-minimal .subhead {
  margin: 0;
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  font-size: 0.98rem;
  font-weight: 700;
  color: var(--ink);
}

.about-minimal .date-chip {
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  font-size: 0.74rem;
  font-weight: 600;
  letter-spacing: 0.04em;
  color: var(--muted);
  background: var(--bg-soft);
  border: 1px solid var(--line);
  padding: 0.12rem 0.5rem;
  border-radius: 4px;
  white-space: nowrap;
}

.about-minimal .item p {
  margin: 0;
  color: var(--ink-soft);
  font-size: 0.95rem;
  line-height: 1.65;
}

.about-minimal .award-list {
  list-style: none;
  margin: 0;
  padding: 0;
}

.about-minimal .award-list li {
  display: grid;
  grid-template-columns: 1fr auto;
  align-items: baseline;
  gap: 0.6rem;
  padding: 0.42rem 0;
  border-bottom: 1px dashed var(--line);
  font-size: 0.95rem;
  line-height: 1.45;
}

.about-minimal .award-list li:last-child {
  border-bottom: none;
}

.about-minimal .award-year {
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  font-size: 0.78rem;
  font-weight: 600;
  color: var(--faint);
  letter-spacing: 0.04em;
  white-space: nowrap;
}

.about-minimal .award-list .highlight {
  color: var(--accent);
  font-weight: 600;
}

.about-minimal .reviewer-group {
  margin-bottom: 1.1rem;
}

.about-minimal .reviewer-group:last-child {
  margin-bottom: 0;
}

.about-minimal .reviewer-label {
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  font-size: 0.78rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: var(--faint);
  margin: 0 0 0.5rem;
}

.about-minimal .reviewer-list {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem 0.45rem;
}

.about-minimal .reviewer-list li {
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  font-size: 0.85rem;
  color: var(--ink-soft);
  background: var(--bg-soft);
  border: 1px solid var(--line);
  padding: 0.22rem 0.65rem;
  border-radius: 4px;
}

.about-minimal .section-note {
  margin-top: 0.95rem;
  font-size: 0.85rem;
  color: var(--muted);
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
}

@media (max-width: 860px) {
  .about-minimal h1 {
    font-size: 1.78rem;
  }

  .about-minimal .two-col {
    grid-template-columns: 1fr;
    gap: 1.25rem;
  }

  .about-minimal .publication-list li {
    grid-template-columns: 1fr;
    gap: 0.2rem;
  }

  .about-minimal .pub-year {
    padding-top: 0;
  }
}
</style>

<div class="about-minimal">
  <header class="intro">
    <h1>Zeping Liu</h1>
    <p class="lead">
      I am a second-year Ph.D. student in the Department of Geography and the Environment at the
      University of Texas at Austin, advised by <a href="https://gengchenmai.github.io/">Dr. Gengchen Mai</a>.
      My research focuses on Geospatial AI and Intelligent Earth Observation, with an emphasis on
      geo-foundation models, spatial representation learning, and efficient large-scale high-resolution mapping.
    </p>
    <span class="fellowship">Amazon AI PhD Fellow · 2025–2027</span>
    <div class="quick-links">
      <a href="https://drive.google.com/file/d/1eQzVQG8wziwlJqVxce35biLFio1SaKTJ/view?usp=sharing">CV</a>
      <a href="https://scholar.google.com/citations?user=eSeCaz4AAAAJ">Google Scholar</a>
      <a href="mailto:zeping.liu@utexas.edu">Email</a>
    </div>
  </header>

  <section class="section">
    <h2 class="section-title">
      <span>Selected Publications</span>
      <span class="count">12 entries</span>
    </h2>
    <ol class="publication-list">
      <li>
        <span class="pub-year">2025</span>
        <div class="pub-body">
          <p class="pub-title"><a href="https://openreview.net/pdf?id=ghybX0Qlls">LocDiff: Identifying Locations on Earth by Diffusing in the Hilbert Space</a></p>
          <p class="pub-meta">Zhangyu Wang, <span class="me">Zeping Liu</span>, et al. <span class="venue">NeurIPS 2025</span>.</p>
        </div>
      </li>
      <li>
        <span class="pub-year">2025</span>
        <div class="pub-body">
          <p class="pub-title"><a href="https://arxiv.org/abs/2503.16683">GAIR: Improving Multimodal Geo-Foundation Model with Geo-Aligned Implicit Representations</a></p>
          <p class="pub-meta"><span class="me">Zeping Liu</span>, Fan Zhang, Junfeng Jiao, Ni Lao, Gengchen Mai. <span class="venue">arXiv 2025</span>.</p>
        </div>
      </li>
      <li>
        <span class="pub-year">2025</span>
        <div class="pub-body">
          <p class="pub-title"><a href="https://www.sciencedirect.com/science/article/pii/S1569843225000159">Towards the Next Generation of Geospatial Artificial Intelligence</a></p>
          <p class="pub-meta">Gengchen Mai, Yiqun Xie, Xiaowei Jia, et al. <span class="venue">International Journal of Applied Earth Observation and Geoinformation, 2025</span>.</p>
        </div>
      </li>
      <li>
        <span class="pub-year">2024</span>
        <div class="pub-body">
          <p class="pub-title"><a href="https://arxiv.org/abs/2406.15658">TorchSpatial: A Location Encoding Framework and Benchmark for Spatial Representation Learning</a></p>
          <p class="pub-meta">Nemin Wu, Qian Cao, Zhangyu Wang, <span class="me">Zeping Liu</span>, et al. <span class="venue">NeurIPS 2024 Datasets &amp; Benchmarks</span>.</p>
        </div>
      </li>
      <li>
        <span class="pub-year">2024</span>
        <div class="pub-body">
          <p class="pub-title"><a href="https://www.sciencedirect.com/science/article/pii/S0034425724000282">Four Seasonal Composite Sentinel-2 Images for Large-Scale Building Story Estimation</a></p>
          <p class="pub-meta">Siqing Lyu, Chao Ji, <span class="me">Zeping Liu</span>, Hong Tang, Liqiang Zhang, Xin Yang. <span class="venue">Remote Sensing of Environment, 2024</span>.</p>
        </div>
      </li>
      <li>
        <span class="pub-year">2024</span>
        <div class="pub-body">
          <p class="pub-title"><a href="https://www.sciencedirect.com/science/article/pii/S0048969724065793">CALIPSO-Based Aerosol Extinction Profile Estimation from MODIS and MERRA-2 with Transformer + CNN</a></p>
          <p class="pub-meta">Yang Zhen, Xin Yang, Hong Tang, Haoze Shi, <span class="me">Zeping Liu</span>. <span class="venue">Science of The Total Environment, 2024</span>.</p>
        </div>
      </li>
      <li>
        <span class="pub-year">2023</span>
        <div class="pub-body">
          <p class="pub-title"><a href="https://essd.copernicus.org/articles/15/3547/2023/essd-15-3547-2023.html">China Building Rooftop Area: A Multi-Annual High-Resolution Dataset (2016–2021)</a></p>
          <p class="pub-meta"><span class="me">Zeping Liu</span>, Hong Tang, Lin Feng, Siqing Lyu. <span class="venue">Earth System Science Data, 2023</span>.</p>
        </div>
      </li>
      <li>
        <span class="pub-year">2023</span>
        <div class="pub-body">
          <p class="pub-title"><a href="https://www.tandfonline.com/doi/pdf/10.1080/15481603.2023.2196154">National-Scale Mapping of Building Footprints with Feature Super-Resolution Segmentation</a></p>
          <p class="pub-meta">Lin Feng, Penglei Xu, Hong Tang, <span class="me">Zeping Liu</span>, Peng Hou. <span class="venue">GIScience and Remote Sensing, 2023</span>.</p>
        </div>
      </li>
      <li>
        <span class="pub-year">2023</span>
        <div class="pub-body">
          <p class="pub-title"><a href="https://www.mdpi.com/2072-4292/15/7/1741">Learning Sparse Geometric Features for Building Segmentation from Low-Resolution Remote-Sensing Images</a></p>
          <p class="pub-meta"><span class="me">Zeping Liu</span>, Hong Tang. <span class="venue">Remote Sensing, 2023</span>.</p>
        </div>
      </li>
      <li>
        <span class="pub-year">2022</span>
        <div class="pub-body">
          <p class="pub-title"><a href="https://drive.google.com/file/d/1cV8hM7Ad_OOYLTwzjnpCml9QWrWJZeVn/view">Building Outline Delineation from VHR Images with CRNN and Line Segment Information</a></p>
          <p class="pub-meta"><span class="me">Zeping Liu</span>, Hong Tang, Wei Huang. <span class="venue">IEEE TGRS, 2022</span>.</p>
        </div>
      </li>
      <li>
        <span class="pub-year">2021</span>
        <div class="pub-body">
          <p class="pub-title"><a href="https://drive.google.com/file/d/1cV8hM7Ad_OOYLTwzjnpCml9QWrWJZeVn/view">Sequential Delineation of Rooftops with Holes from VHR Aerial Images</a></p>
          <p class="pub-meta">Wei Huang, <span class="me">Zeping Liu</span>, Hong Tang, Jiayi Ge. <span class="venue">Remote Sensing, 2021</span>.</p>
        </div>
      </li>
      <li>
        <span class="pub-year">2021</span>
        <div class="pub-body">
          <p class="pub-title"><a href="https://link.springer.com/chapter/10.1007/978-3-030-88007-1_39">AFM-RNN: A Sequence Prediction Model for Delineating Building Rooftops</a></p>
          <p class="pub-meta"><span class="me">Zeping Liu</span>, Hong Tang, Wei Huang. <span class="venue">Chinese Conference on Pattern Recognition and Computer Vision, 2021</span>.</p>
        </div>
      </li>
    </ol>
    <p class="section-note">For complete records, please see my <a href="https://scholar.google.com/citations?user=eSeCaz4AAAAJ">Google Scholar</a>.</p>
  </section>

  <section class="section two-col">
    <div>
      <h2 class="section-title"><span>Industry Experience</span></h2>
      <div class="item">
        <div class="item-head">
          <p class="subhead">Research Intern, Esri Inc.</p>
          <span class="date-chip">Aug – Nov 2025 · Part-time</span>
        </div>
        <p>Continued work on the Spatial Co-Scientist project.</p>
      </div>
      <div class="item">
        <div class="item-head">
          <p class="subhead">Research Intern, Esri Inc.</p>
          <span class="date-chip">May – Aug 2025 · Full-time</span>
        </div>
        <p>
          Developed Spatial Co-Scientist with the Esri Generative AI Toolkit, combining RAG,
          LLM reasoning, and ArcGIS Pro workflows for practical spatial analysis;
          collected expert interview insights and designed guided analysis flows.
        </p>
      </div>
    </div>

    <div>
      <h2 class="section-title"><span>Selected Awards</span></h2>
      <ul class="award-list">
        <li><span>IGIF Scholarship Award</span><span class="award-year">2026</span></li>
        <li><span class="highlight">Amazon AI PhD Fellowship</span><span class="award-year">2025–2027</span></li>
        <li><span>UT Austin Dean's Prestigious Supplement Fellowship</span><span class="award-year">2025</span></li>
        <li><span>Second Place, UT GIS Day Student Presentation</span><span class="award-year">2024</span></li>
        <li><span>Outstanding Graduate Student of Beijing</span><span class="award-year">2024</span></li>
        <li><span>Zhou Tingru Geography Youth Award</span><span class="award-year">2024</span></li>
        <li><span>First Prize, National Remote Sensing Bulletin Forum</span><span class="award-year">2023</span></li>
        <li><span>National Scholarship, Ministry of Education (China)</span><span class="award-year">2022, 2023</span></li>
      </ul>
    </div>
  </section>

  <section class="section">
    <h2 class="section-title"><span>Reviewer Service</span></h2>
    <div class="reviewer-group">
      <p class="reviewer-label">Conferences</p>
      <ul class="reviewer-list">
        <li>ICLR 2025</li>
        <li>KDD 2026 (AI for Science Track)</li>
      </ul>
    </div>
    <div class="reviewer-group">
      <p class="reviewer-label">Journals</p>
      <ul class="reviewer-list">
        <li>Scientific Reports</li>
        <li>Earth Science Informatics</li>
        <li>Int'l Journal of Applied Earth Observation and Geoinformation</li>
        <li>Signal, Image and Video Processing</li>
        <li>Geocarto International</li>
        <li>Frontiers in Remote Sensing</li>
        <li>Geo-spatial Information Science</li>
      </ul>
    </div>
    <p class="section-note"><a href="https://info.flagcounter.com/JzHz">Visitor map</a></p>
  </section>
</div>
