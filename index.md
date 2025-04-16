---
layout: default
graph_logo_bg: true
description: "Discover Open Science at VLIZ, where we're making science more efficient, reliable, and transparent. Learn about our mission, values, and core principles. Join us in our journey!"
cover: /assets/media/img/datacenter/Fisheries_4.jpg
title: "VLIZ DATA"
subblocks:
  - title: "Data submission"
    description: "Submit your data to  VLIZ"
    clickthrough_url: "/data/submit/"
  - title: "Data inventory"
    description: "Discover available data "
    clickthrough_url: "/data/inventory/"
  - title: "Data resources"
    description: "Explore available resources"
    clickthrough_url: "/data/resources/"
special_collections:
  - title: Scheldemonitor
    description: "A Flemish-Dutch knowledge and information portal on research and monitoring in the Scheldt estuary."
    clickthrough_url: "https://www.scheldemonitor.be/nl/imis/datasets"
    clickthrough_text: "Dataset"
  - title: Belgian Datasets
    description: "Belgian datasets are datasets available in Belgium. These datasets have a substantive geographical scope that covers Belgium but also beyond."
    clickthrough_url: "https://marineinfo.org/imis?module=dataset&spcolid=131&show=search"
    clickthrough_text: "Datasets"
  - title: GEANS 
    description: "GEANS Data: Genetic tools for Ecosystem health Assessment in the North Sea region"
    clickthrough_url: "https://marineinfo.org/imis?module=dataset&spcolid=1021&show=search"
    clickthrough_text: "Dataset"

robotics_collections:
  - title: PORCUPINE with AUV Barabas
    description: "The campaign was part of the Porcupine fieldwork campaign in collaboration with the University of Gent, utilizing AUV Barabas, provided by the Marine Robotics Centre at VLIZ, equipped with side-scan sonar, sub-bottom profiler, and camera, and complemented by an oceanographic survey onboard RV Belgica."
    clickthrough_url: "https://erddap.vliz.be/erddap/info/index.html?page=1&itemsPerPage=1000"
    clickthrough_text: "HERE IS THE DATA SET"

  - title: Cold-water cascade with Glider Yoko and AUV Barabas 
    description: "Deployment off Cap de Creus in 2023, to investigate the cold-water cascade from the continental shelf to the slope, with a focus on the morphology of subsea canyons. This work was in collaboration with the University of Barcelona and UTM-CSIC alongside an oceanographic survey onboard RV Garcia Del Cid."
    clickthrough_url: "https://erddap.vliz.be/erddap/info/index.html?page=1&itemsPerPage=1000"
    clickthrough_text: "LINK NEEDED"

  - title: Belgica Mound Province, Gollum Channels, and Kings Channel with AUV Barabas
    description: "Deployment in the Porcupine Basin, Ireland, from August 1, 2022, to August 18, 2022, to investigate ocean currents and collect high-resolution seabed data, focusing on three key sites: Belgica Mound Province (BMP), Gollum Channels, and Kings Channel."
    clickthrough_url: "https://erddap.vliz.be/erddap/info/2022_PORCUPINE_Aanderaa_53e2_7187_893b/index.html"
    clickthrough_text: "LINK NEEDED"
---

{% include light_bg.html content="<h2 style='text-align: center !important;'>Gateway to Marine Knowledge: Data Sharing and Preservation at the Flanders Marine Institute</h2><p></p>" %}

{% include item/list/block/colored/main.html items=page.subblocks %}

<p>Join a thriving community of <strong>26,783 individuals</strong> and <strong>9,547 institutes</strong>, driving innovation across <strong>3,940 projects</strong>. <br>At Flanders Marine Institute, we harness the power of data to foster collaboration and unlock new insights.</p>

<div class="counter-container" style="display: flex; align-items: center; margin-bottom: 10px;">
  <h1 id="counter" style="font-size:48px; margin-right: 10px; font-size: 24px;">0</h1>
  <span style="color: #354d9b;"><strong>and counting datasets available</strong></span>
</div>

<script>
  const target = 5836;
  const counterElement = document.getElementById('counter');
  let count = 0;
  const updateCounter = () => {
    if (count < target) {
      count++;
      counterElement.textContent = count;
      setTimeout(updateCounter, 1);
    } else {
      counterElement.textContent = target;
    }
  };
  updateCounter();
</script>

<style>
  .pretty-button {
    display: inline-block;
    padding: 0.75rem 1.5rem;
    background-color: #0077b6;
    color: #fff;
    border: none;
    border-radius: 8px;
    font-size: 1rem;
    font-weight: 600;
    text-align: center;
    transition: all 0.3s ease;
    text-decoration: none;
    cursor: pointer;
  }
  .pretty-button:hover {
    background-color: #005f87;
    transform: translateY(-2px);
  }
  .button-container {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    margin-top: 1.5rem;
  }
</style>

<div class="row">
  <div class="col-md-6">
    <h4>Access to over 250,000 unique publications</h4>
    <p>The VLIZ serves as a trusted national and international hub for high-quality, reliable marine and estuarine data. We offer a wide range of services, technologies, tools, training, and support to scientists, policymakers, the blue economy, and citizens alike. Committed to making data accessible and open, we ensure it’s available in an efficient and user-friendly manner. As an accredited IODE National Oceanographic Data Center, the VLIZ is dedicated to advancing marine research and fostering collaboration across all sectors.</p>
    <div class="button-container">
      <a href="/search" class="pretty-button">Find data & information</a>
      <a href="/submit" class="pretty-button">Submit data</a>
    </div>
  </div>
  <div class="col-md-6">
    <img src="assets/media/img/datacenter/robots.jpg" alt="Marine Robotics">
    <p style="font-size: smaller;">
      The <a href="https://www.vliz.be/nl/wat-we-doen/aanbod-infrastructuur/robotica">VLIZ Marine Robotics Centre</a> (MRC) pioneers in Marine Autonomous Systems (MAS) in order to enable comprehensive observations in remote, harsh, and vast environments within our world’s oceans and seas. Check out the data they collected below.
    </p>
  </div>
</div>

<h3>Showcase of Marine Robotics Missions</h3>
{% include item/list/block/colored/main.html title="Robotics collections" items=page.robotics_collections %}
{% include item/list/carrousel/block/main.html title="Special Collections" items=page.special_collections %}
