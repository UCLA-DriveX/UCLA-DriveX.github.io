---
layout: about
title:
permalink: /
subtitle: AI Research for Generalizable and Interpretable Machine Autonomy
display_categories:
news: true  # includes a list of news items
latest_posts: true  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
nav_order: 0

---

<!-- _pages/publications.md -->
<div class="publications" >

<h2 id="papers">Papers</h2>

<!-- To use years as categories, add 
years: [2023,2022,2021]
to header!
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}
-->

<div class="research-section">
{% bibliography -f {{ site.scholar.bibliography }} %}
</div>

</div>

<!--software-->

<h2 id="software">Software</h2>

<div class="research-section">

  <section style="text-align: center;">
  <h3>MetaDrive</h3>
    <p>AI Research for Generalizable and Interpretable Machine Autonomy</p>

    <p class="nav-links">
      <a href="https://github.com/metadriverse/metadrive" target="_blank">Code</a> |
      <a href="https://metadrive-simulator.readthedocs.io/en/latest/" target="_blank">Documentation</a> |
      <a href="https://www.youtube.com/embed/3ziJPqC_-T4" target="_blank">Demo Video</a> |
      <a href="https://arxiv.org/pdf/2109.12674.pdf" target="_blank">Paper</a>
    </p>
  </section>

  <video style="display:block; width:100%; height:auto;" autoplay muted loop controls playsinline>
    <source src="https://raw.githubusercontent.com/decisionforce/archive/master/MetaDrive/metadrive_teaser.mp4" type="video/mp4"/>
  </video>

  <br>

  <h3>MetaDrive Simulator</h3>
  <p>To facilitate the research of generalizable reinforcement learning, we develop an open-source, highly efficient and flexible driving simulator MetaDrive, which holds the following key features:</p>
  <ul>
    <li>Modular</li>
    <li>Lightweight</li>
    <li>Customizable</li>
    <li>Realistic</li>
  </ul>
  <p>We construct a variety of RL tasks and baselines in both single-agent and multi-agent settings, including benchmarking generalizability across unseen scenes, safe exploration, and modeling multi-agent behaviors.</p>
  <p>Empowered by <strong><em><a href="https://metadriverse.github.io/scenarionet/">ScenarioNet</a></em></strong>, all features of MetaDrive can be applied to the virtual environments reconstructed from the open-source dataset, such as Waymo Open Dataset, nuPlan, and L5.</p>

  <br>
  
  <h3>OpenCDA</h3>
  <img style="display:block; width:100%; height:auto;" src="/assets/img/DriveX/openCDA.png" alt="OpenCDA Logo"/>
  <img style="display:block; width:100%; height:auto;" src="/assets/img/DriveX/openCDA2.gif" alt="OpenCDA Demo GIF"/>
  <p><strong>OpenCDA:</strong> an open co-simulation-based research/engineering framework integrated with prototype cooperative driving automation pipelines and automated driving components.</p>
  <p>Xu, Runsheng, et al. “OpenCDA: an open cooperative driving automation framework integrated with co-simulation.” 2021 IEEE International Intelligent Transportation Systems Conference (ITSC). IEEE, 2021.</p>
  <p><a href="https://github.com/ucla-mobility/OpenCDA">https://github.com/ucla-mobility/OpenCDA</a></p>
</div>


<!--Datasets-->

<h2 id="datasets">Datasets</h2>

<div class="research-section">
    <h3 style="text-align: left">DIVA Dataset</h3>

    <div class="white-background">
        <img src="/assets/img/DriveX/DIVA-sim.png">
    </div>
</div>

<div class="research-section">
    <h3 style="text-align: left">Vid2Sim Dataset</h3>

    <div class="white-background">
        <img src="/assets/img/DriveX/Vid2sim.png">
    </div>
</div>

<div class="research-section">
    <h3 style="text-align: left">CityWalker Dataset</h3>

    <div class="white-background">
        <img src="/assets/img/DriveX/CityWalker.png">
    </div>
</div>

<div class="research-section">
    <h3 style="text-align: left">V2X-Real Dataset</h3>
    <ul style="list-style-type: none; padding-left: 0;">
        V2X-Real: the first large-scale real-world dataset for Vehicle-to-Everything (V2X) cooperative perception.

        Xiang, Hao, et al. “V2X-Real: a large-scale dataset for vehicle-to-everything cooperative perception." European Conference on Computer Vision. Cham: Springer Nature Switzerland, 2024.

        https://mobility-lab.seas.ucla.edu/v2x-real/
        https://github.com/ucla-mobility/V2X-Real

    </ul>

    <div class="white-background">
        <img src="/assets/img/DriveX/V2X.png">
    </div>
</div>

<!--Outreach-->
<h2 id="outreach">Outreach</h2>

<div class="research-section">
    <h3 style="text-align: left">Workshops & Panels & Webinars</h3>
    <ul style="padding-left: 10;">
    <li>
        <a href="https://metadriverse.github.io/ucla_ucb_workshop/" target="_blank" rel="noopener">
        1st UCLA‑UCB Joint Workshop
        </a>: Towards Next Generation of Open‑Source Simulator for Embodied AI and Autonomous Driving 2025
    </li>
    <li>
        <a href="https://poets2024.github.io/" target="_blank" rel="noopener">
        Workshop of Populating Empty Cities
        </a> – Virtual Humans for Robotics and Autonomous Driving at CVPR 2024
    </li>
    </ul>

</div>

<div class="research-section">
    <h3 style="text-align: left">Online Educational Resources</h3>
    <ul style="padding-left: 10;">
        <li><a href="https://metadrive-simulator.readthedocs.io/en/latest/" target="_blank" rel="noopener"> Colab and Tutorial of MetaDrive </a></li>
    </ul>
</div>


<!--Outreach-->
<h2 id="acknowledgement">Acknowledgement</h2>


<div class="row justify-content-center align-items-center">
    <div class="col-xs-3 col-md-3 col-img">
        <img src="/assets/img/DriveX/nsf.png" alt="NSF" class="logo">
    </div>
    <div class="col-xs-4 col-md-4 col-img">
        The project is supported by <b> NSF Grants CNS-2235012, TI-2346267 and IIS-2339769</b>.
    </div> 
</div>


<style>
.custom-heading {
  font-size: 1.5em;
  font-weight: bold;
  margin-bottom: 10px; /* Adjust this value as needed */
}
.white-background {
    background-color: white;
    display: block; /* Changed from inline-block if you want it to take the full width available */
    width: 100%; /* Ensures it takes the full width of its parent container */
    overflow: hidden; /* This will prevent any overflow outside this div */
    padding: 10px;
}
.white-background img {
    width: 100%; /* Makes the image responsive */
    height: auto; /* Keeps the image's aspect ratio intact */
}
.logo {
    display: inline; /* Changed from inline-block if you want it to take the full width available */
    width: 100%; /* Ensures it takes the full width of its parent container */
    overflow: hidden; /* This will prevent any overflow outside this div */
    padding: 10px;
}
.logo img {
    width: 100%; /* Makes the image responsive */
    height: auto; /* Keeps the image's aspect ratio intact */
}
.video-grid {
    display: grid;
    grid-template-columns: 1fr 1fr; /* Creates two columns */
    grid-gap: 20px; /* Space between videos */
}
.video iframe {
    width: 100%; /* Ensures iframe takes the full width of the container */
    height: 250px; /* Fixed height for all videos */
}

@media (max-width: 600px) {
    .video-grid {
        grid-template-columns: 1fr; /* Stacks videos into a single column on small screens */
    }
}
.gif img {
    width: 100%; /* Ensures the GIFs fill the cells */
    height: auto; /* Maintains the aspect ratio */
}
</style>




