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
  --ink: #121926;
  --muted: #4a5565;
  --line: #d8dee9;
  --accent: #0f4c81;
  color: var(--ink);
  font-family: "Source Serif 4", "Iowan Old Style", "Palatino Linotype", "Book Antiqua", Palatino, serif;
}

.about-minimal .intro {
  border-bottom: 1px solid var(--line);
  padding-bottom: 1.35rem;
  margin-bottom: 1.4rem;
}

.about-minimal .kicker {
  margin: 0;
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  font-size: 0.8rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: var(--muted);
}

.about-minimal h1 {
  margin: 0.25rem 0 0.7rem;
  font-size: 2.05rem;
  line-height: 1.15;
  font-weight: 700;
}

.about-minimal .lead {
  margin: 0;
  font-size: 1.06rem;
  line-height: 1.75;
}

.about-minimal .fellowship {
  margin: 0.75rem 0 0;
  color: var(--accent);
  font-weight: 700;
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
}

.about-minimal .quick-links {
  margin-top: 0.95rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.65rem;
}

.about-minimal .quick-links a {
  text-decoration: none;
  border: 1px solid var(--line);
  border-radius: 999px;
  padding: 0.3rem 0.72rem;
  font-size: 0.84rem;
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  color: var(--ink);
}

.about-minimal .quick-links a:hover {
  border-color: var(--accent);
  color: var(--accent);
}

.about-minimal .section {
  margin: 1.55rem 0;
}

.about-minimal .section-title {
  margin: 0 0 0.85rem;
  padding-bottom: 0.5rem;
  border-bottom: 1px solid var(--line);
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  font-size: 0.95rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.about-minimal .publication-list {
  margin: 0;
  padding-left: 1.15rem;
}

.about-minimal .publication-list li {
  margin-bottom: 0.9rem;
}

.about-minimal .pub-title {
  margin: 0;
  line-height: 1.5;
  font-weight: 700;
}

.about-minimal .pub-meta {
  margin: 0.16rem 0 0;
  line-height: 1.5;
  font-size: 0.94rem;
  color: var(--muted);
}

.about-minimal .two-col {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.25rem;
}

.about-minimal .subhead {
  margin: 0 0 0.55rem;
  font-family: "Source Sans 3", "Avenir Next", "Segoe UI", sans-serif;
  font-size: 0.95rem;
  font-weight: 700;
}

.about-minimal .item {
  margin-bottom: 0.85rem;
}

.about-minimal .item p {
  margin: 0.2rem 0 0;
  color: var(--muted);
  font-size: 0.95rem;
  line-height: 1.6;
}

.about-minimal ul.compact {
  margin: 0;
  padding-left: 1.1rem;
}

.about-minimal ul.compact li {
  margin-bottom: 0.42rem;
}

.about-minimal .reviewer-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 0.46rem 1rem;
  margin: 0;
  padding-left: 1.1rem;
}

.about-minimal .section-note {
  margin-top: 0.75rem;
  font-size: 0.88rem;
  color: var(--muted);
}

@media (max-width: 860px) {
  .about-minimal h1 {
    font-size: 1.75rem;
  }

  .about-minimal .two-col,
  .about-minimal .reviewer-grid {
    grid-template-columns: 1fr;
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
    <p class="fellowship">I am the Amazon AI PhD Fellow (2025-2027)</p>
    <div class="quick-links">
      <a href="https://drive.google.com/file/d/1eQzVQG8wziwlJqVxce35biLFio1SaKTJ/view?usp=sharing">CV</a>
      <a href="https://scholar.google.com/citations?user=eSeCaz4AAAAJ">Google Scholar</a>
      <a href="mailto:zeping.liu@utexas.edu">Email</a>
    </div>
  </header>

  <section class="section">
    <h2 class="section-title">Selected Publications</h2>
    <ol class="publication-list">
      <li>
        <p class="pub-title"><a href="https://openreview.net/pdf?id=ghybX0Qlls">LocDiff: Identifying Locations on Earth by Diffusing in the Hilbert Space</a></p>
        <p class="pub-meta">Zhangyu Wang, <strong>Zeping Liu</strong>, et al. Neurips 2025.</p>
      </li>
      <li>
        <p class="pub-title"><a href="https://arxiv.org/abs/2503.16683">GAIR: Improving Multimodal Geo-Foundation Model with Geo-Aligned Implicit Representations</a></p>
        <p class="pub-meta"><strong>Zeping Liu</strong>, Fan Zhang, Junfeng Jiao, Ni Lao, Gengchen Mai. arXiv 2025.</p>
      </li>
      <li>
        <p class="pub-title"><a href="https://www.sciencedirect.com/science/article/pii/S1569843225000159">Towards the Next Generation of Geospatial Artificial Intelligence</a></p>
        <p class="pub-meta">Gengchen Mai, Yiqun Xie, Xiaowei Jia, et al. International Journal of Applied Earth Observation and Geoinformation, 2025.</p>
      </li>
      <li>
        <p class="pub-title"><a href="https://arxiv.org/abs/2406.15658">Torchspatial: A Location Encoding Framework and Benchmark for Spatial Representation Learning</a></p>
        <p class="pub-meta">Nemin Wu, Qian Cao, Zhangyu Wang, <strong>Zeping Liu</strong>, et al. Neurips 2024 Dataset Benchmark.</p>
      </li>
      <li>
        <p class="pub-title"><a href="https://www.sciencedirect.com/science/article/pii/S0034425724000282">Four Seasonal Composite Sentinel-2 Images for Large-Scale Building Story Estimation</a></p>
        <p class="pub-meta">Siqing Lyu, Chao Ji, <strong>Zeping Liu</strong>, Hong Tang, Liqiang Zhang, Xin Yang. Remote Sensing of Environment, 2024.</p>
      </li>
      <li>
        <p class="pub-title"><a href="https://www.sciencedirect.com/science/article/pii/S0048969724065793">CALIPSO-Based Aerosol Extinction Profile Estimation from MODIS and MERRA-2 with Transformer + CNN</a></p>
        <p class="pub-meta">Yang Zhen, Xin Yang, Hong Tang, Haoze Shi, <strong>Zeping Liu</strong>. Science of The Total Environment, 2024.</p>
      </li>
      <li>
        <p class="pub-title"><a href="https://essd.copernicus.org/articles/15/3547/2023/essd-15-3547-2023.html">China Building Rooftop Area: A Multi-Annual High-Resolution Dataset (2016-2021)</a></p>
        <p class="pub-meta"><strong>Zeping Liu</strong>, Hong Tang, Lin Feng, Siqing Lyu. Earth System Science Data, 2023.</p>
      </li>
      <li>
        <p class="pub-title"><a href="https://www.tandfonline.com/doi/pdf/10.1080/15481603.2023.2196154">National-Scale Mapping of Building Footprints with Feature Super-Resolution Segmentation</a></p>
        <p class="pub-meta">Lin Feng, Penglei Xu, Hong Tang, <strong>Zeping Liu</strong>, Peng Hou. GIScience and Remote Sensing, 2023.</p>
      </li>
      <li>
        <p class="pub-title"><a href="https://www.mdpi.com/2072-4292/15/7/1741">Learning Sparse Geometric Features for Building Segmentation from Low-Resolution Remote-Sensing Images</a></p>
        <p class="pub-meta"><strong>Zeping Liu</strong>, Hong Tang. Remote Sensing, 2023.</p>
      </li>
      <li>
        <p class="pub-title"><a href="https://drive.google.com/file/d/1cV8hM7Ad_OOYLTwzjnpCml9QWrWJZeVn/view">Building Outline Delineation from VHR Images with CRNN and Line Segment Information</a></p>
        <p class="pub-meta"><strong>Zeping Liu</strong>, Hong Tang, Wei Huang. IEEE TGRS, 2022.</p>
      </li>
      <li>
        <p class="pub-title"><a href="https://drive.google.com/file/d/1cV8hM7Ad_OOYLTwzjnpCml9QWrWJZeVn/view">Sequential Delineation of Rooftops with Holes from VHR Aerial Images</a></p>
        <p class="pub-meta">Wei Huang, <strong>Zeping Liu</strong>, Hong Tang, Jiayi Ge. Remote Sensing, 2021.</p>
      </li>
      <li>
        <p class="pub-title"><a href="https://link.springer.com/chapter/10.1007/978-3-030-88007-1_39">AFM-RNN: A Sequence Prediction Model for Delineating Building Rooftops</a></p>
        <p class="pub-meta"><strong>Zeping Liu</strong>, Hong Tang, Wei Huang. Chinese Conference on Pattern Recognition and Computer Vision, 2021.</p>
      </li>
    </ol>
    <p class="section-note">For complete records, please see my Google Scholar.</p>
  </section>

  <section class="section two-col">
    <div>
      <h2 class="section-title">Industry Experience</h2>
      <div class="item">
        <p class="subhead">Intern, Esri Inc. (Part-time)</p>
        <p>19 Aug 2025 - 7 Nov 2025</p>
        <p>Worked on the Spatial Co-Scientist project.</p>
      </div>
      <div class="item">
        <p class="subhead">Intern, Esri Inc. (Full-time)</p>
        <p>20 May 2025 - 8 Aug 2025</p>
        <p>
          Developed Spatial Co-Scientist with Esri Generative AI Toolkit, combining RAG,
          LLM reasoning, and ArcGIS Pro workflows for practical spatial analysis;
          also collected expert interview insights and designed guided analysis flows.
        </p>
      </div>
    </div>

    <div>
      <h2 class="section-title">Awards</h2>
      <ul class="compact">
        <li>IGIF Scholarship Award (2026) </li>
        <li>UT Austin Dean's Prestigious Supplement Fellowship (2025) </li>
        <li>Amazon AI PhD Fellowship (2025-2027)</li>
        <li>Second Place, UT GIS Day Student Presentation Competition (2024)</li>
        <li>Outstanding Graduate Student of Beijing, China (2024)</li>
        <li>Zhou Tingru Geography Youth Award (2024)</li>
        <li>First Prize, Graduate Academic Forum of National Remote Sensing Bulletin (2023)</li>
        <li>National Scholarship, Ministry of Education (China) (2023)</li>
        <li>National Scholarship, Ministry of Education (China) (2022)</li>
      </ul>
    </div>
  </section>

  <section class="section">
    <h2 class="section-title">Reviewer Service</h2>
    <ul class="reviewer-grid">
      <li>ICLR 2025</li>
      <li>KDD 2026 AI for Science Track</li>
      <li>Scientific Reports</li>
      <li>Earth Science Informatics</li>
      <li>International Journal of Applied Earth Observation and Geoinformation</li>
      <li>Signal, Image and Video Processing</li>
      <li>Geocarto International</li>
      <li>Frontiers in Remote Sensing</li>
      <li>Geo-spatial Information Science</li>
    </ul>
    <p class="section-note"><a href="https://info.flagcounter.com/JzHz">Visitor map</a></p>
  </section>
</div>
