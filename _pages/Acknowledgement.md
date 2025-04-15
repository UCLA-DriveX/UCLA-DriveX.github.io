---
layout: research
permalink: /Acknowledgement/
title: Acknowledgement
page_title: Acknowledgement
nav: true
nav_order: 5
---

<div class="row justify-content-center align-items-center">
    <div class="col-xs-3 col-md-3 col-img">
        <img src="/assets/img/DriveX/nsf.png" alt="NSF" class="logo">
    </div>
    <div class="col-xs-4 col-md-4 col-img">
        The workshop is supported by <b>NSF CCRI grants 2235012 and 2235013</b>.
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
