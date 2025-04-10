---
layout: default
graph_logo_bg: true
description: "Discover Open Science at VLIZ, where we're making science more efficient, reliable, and transparent. Learn about our mission, values, and core principles. Join us in our journey!"
cover: /assets/media/img/datacenter/Fisheries_4.jpg
title: "VLIZ DATA"
subblocks:
  - title: "Data submission"
    description: "Submit your data to  VLIZ"
    #image: /assets/media/img/ist/submit.jpg
    clickthrough_url: "/data/submit/"
  - title: "Data inventory"
    description: "Discover available data "
    #image: /assets/media/img/ist/inventory.jpg
    clickthrough_url: "/data/inventory/"
  - title: "Data resources"
    description: "Explore available resources"
    #image: /assets/media/img/ist/resources.jpg
    clickthrough_url: "/data/resources/"
special_collections:
  - title: Scheldemonitor
    description: "A Flemish-Dutch knowledge and information portal on research and monitoring in the Scheldt estuary."
    clickthrough_url: "https://www.scheldemonitor.be/nl/imis/datasets"
    clickthrough_text: "Select a dataset"
  - title: Belgian Datasets
    description: "Belgian datasets are datasets available in Belgium. These datasets have a substantive geographical scope that covers Belgium but also beyond."
    clickthrough_url: "https://marineinfo.org/imis?module=dataset&spcolid=131&show=search"
    clickthrough_text: "Datasets"
  - title: GEANS 
    description: " 
GEANS Data: Genetic tools for Ecosystem health Assessment in the North Sea region"
    clickthrough_url: "https://marineinfo.org/imis?module=dataset&spcolid=1021&show=search"
    clickthrough_text: "Dataset"


robotics_collections:
  - title: PORCUPINE with AUV Barabas
    description: "The campaign was part of the Porcupine fieldwork campaign in collaboration with the University of Gent, utilizing AUV Barabas, provided by the Marine Robotics Centre at VLIZ, equipped with side-scan sonar, sub-bottom profiler, and camera, and complemented by an oceanographic survey onboard RV Belgica. You can get the data here: <a href='https://erddap.vliz.be/erddap/tabledap/2022_PORCUPINE_Aanderaa_53e2_7187_893b.html' target='_blank'>https://erddap.vliz.be/erddap/tabledap/2022_PORCUPINE_Aanderaa_53e2_7187_893b.html</a>"
    clickthrough_url: "https://erddap.vliz.be/erddap/info/index.html?page=1&itemsPerPage=1000"
    clickthrough_text: "HERE IS THE DATA SET"

  - title: Cold-water cascade with Glider Yoko and AUV Barabas 
    description: "Deployment off Cap de Creus in 2023, to investigate the cold-water cascade from the continental shelf to the slope, with a focus on the morphology of subsea canyons. This work was in collaboration with the University of Barcelona and UTM-CSIC alongside an oceanographic survey onboard RV Garcia Del Cid, to collect high-resolution data and advance understanding of cold-water transport processes. You can access the data here: 
    <a href='https://erddap.vliz.be/erddap/tabledap/2023_ABRIC_FARDWO_Aanderaa_6465_6179_9713.html' target='_blank'>https://erddap.vliz.be/erddap/tabledap/2022_PORCUPINE_Aanderaa_53e2_7187_893b.html</a>"

    clickthrough_url: "https://erddap.vliz.be/erddap/info/index.html?page=1&itemsPerPage=1000"
    clickthrough_text: "LINK NEEDED"


  - title: Belgica Mound Province, Gollum Channels, and Kings Channel with AUV Barabas
    description: "Deployment in the Porcupine Basin, Ireland, from August 1, 2022, to August 18, 2022, to investigate ocean currents and collect high-resolution seabed data, focusing on three key sites: Belgica Mound Province (BMP), Gollum Channels, and Kings Channel. Check the data out here:
    <a href='https://erddap.vliz.be/erddap/tabledap/2022_PORCUPINE_Aanderaa_53e2_7187_893b.html' target='_blank'>https://erddap.vliz.be/erddap/info/2022_PORCUPINE_Aanderaa_53e2_7187_893b/index.html</a>"
    clickthrough_url: "https://erddap.vliz.be/erddap/info/2022_PORCUPINE_Aanderaa_53e2_7187_893b/index.html"
    clickthrough_text: "LINK NEEDED"
---

{% include light_bg.html content=
"<h2 style='text-align: center !important;'>Gateway to Marine Knowledge: Data Sharing and Preservation at the Flanders Marine Institute

</h2>

<p>
  
</p>
"
%}

{% include item/list/block/colored/main.html items=page.subblocks %}

   <p>Join a thriving community of <strong>26,783 individuals</strong> and <strong>9,547 institutes</strong>, driving innovation across <strong>3,940 projects</strong>. 
   <br>At Flanders Marine Institute, we harness the power of data to foster collaboration and unlock new insights. 
         </p>

<div class="counter-container" style="display: flex; align-items: center; margin-bottom: 10px;">
  <h1 id="counter" style="font-size:48px; margin-right: 10px; font-size: 24px;">0</h1>
  <span style="color: #354d9b;"><strong>and counting datasets available</strong></span>
</div>

<script>
  // Set the target value for the counter
  const target = 5836;
  
  // Select the counter element
  const counterElement = document.getElementById('counter');
  
  // Function to update the counter
  let count = 0;
  const updateCounter = () => {
    if (count < target) {
      count++;
      counterElement.textContent = count;
      setTimeout(updateCounter, 1); // Delay to animate the counter
    } else {
      counterElement.textContent = target; // Ensure it stops at 5836
    }
  };
  
  // Start the counter animation
  updateCounter();
</script>


<div class="row">
    <div class="col-md-6">
        <h4>Access to over 250,000 unique publications</h4>
The VLIZ serves as a trusted national and international hub for high-quality, reliable marine and estuarine data. We offer a wide range of services, technologies, tools, training, and support to scientists, policymakers, the blue economy, and citizens alike. Committed to making data accessible and open, we ensure it’s available in an efficient and user-friendly manner. As an accredited IODE National Oceanographic Data Center, the VLIZ is dedicated to advancing marine research and fostering collaboration across all sectors.
        <br>
        <style>
            .button {
                display: inline-block;
                padding: 10px 20px; /* Reduced padding */
                margin: 10px;
                font-size: 20px; /* Reduced font size */
                text-align: center;
                text-decoration: none;
                color: white;
                background-color: #0779bf; /* Button color */
                border-radius: 5px;
                transition: background-color 0.3s;
            }
            .button:hover {
                background-color: #0056b3; /* Darker button color on hover */
                color: white;
            }
        </style>
      <div style="display: flex; gap: 10px; margin-top: 20px;">
          <a href="/search" class="button"><strong>Find data & information</strong></a>
          <a href="/submit" class="button"><strong>Submit data</strong></a>
      </div>
      

</div>
  <div class="col-md-6">
    <img src="assets/media/img/datacenter/robots.jpg">
  <span style="font-size: smaller;">
  The <a href="https://www.vliz.be/nl/wat-we-doen/aanbod-infrastructuur/robotica">VLIZ Marine Robotics Centre</a> (MRC) pioneers in Marine Autonomous Systems (MAS) in order to enable comprehensive observations in remote, harsh, and vast environments within our world’s oceans and seas. Check out the data they collected below.
</span>
<br>
  </div>
  <br>
</div>
<br>
<h3>Showcase of Marine Robotics Missions</h3>
{% include item/list/block/colored/main.html
    title="Robotics collections"
    items=page.robotics_collections
%}
{% include item/list/carrousel/block/main.html
    title="Special Collections"
    items=page.special_collections
%}

 <script>
    function startCounting(targetNumber, duration, elementId) {
        const counterDisplay = document.getElementById(elementId);
        let count = 0; // Start from 0
        const incrementTime = Math.floor(duration / targetNumber); // Time for each increment

        const interval = setInterval(() => {
            if (count < targetNumber) {
                let increment = Math.max(1, Math.floor((targetNumber - count) / 125)); // Decrease increment as count approaches target
                count += increment;
                counterDisplay.textContent = count; // Update the display
            } else {
                clearInterval(interval); // Stop the counting when reaching the target
            }
        }, incrementTime);     
    }

    async function fetchDataAndStartCounting() {
        const modules = ['person', 'institute', 'dataset', 'project', 'ref'];
        const elements = {
            person: 'person-counter',
            institute: 'institute-counter',
            dataset: 'dataset-counter',
            project: 'project-counter',
            ref: 'ref-counter'
        };
        const defaultValues = {
            person: 26783,
            institute: 9547,
            dataset: 5836,
            project: 3940,
            ref: 250000
        };

        try {
            for (const module of modules) {
                const response = await fetch(`https://vliz.be/nl/imis?show=jsonportal&module=${module}&cnt=1&ext=1`);
                const data = await response.json();
                const value = data.cnt || defaultValues[module];
                startCounting(value, 2000, elements[module]);
            }
        } catch (error) {
            console.error('Error fetching data:', error);
            modules.forEach(module => {
                startCounting(defaultValues[module], 2000, elements[module]);
            });
        }
    }

    // Call the function to start counting when the whole document is loaded
    document.addEventListener('DOMContentLoaded', () => {
        fetchDataAndStartCounting(); // Fetch data and start counting
    });
</script>
