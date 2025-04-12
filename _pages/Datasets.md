---
layout: research
permalink: /Datasets/
title: Datasets
page_title: Datasets
nav: true
nav_order: 2
---

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
