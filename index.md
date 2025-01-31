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
    clickthrough_url: "/ask_IT_when_module_made"
    clickthrough_text: "IMIS (not correct)"
  - title: Belgian datasets
    description: "Belgian datasets are datasets available in Belgium. These datasets have a substantive geographical scope that covers Belgium but also beyond."
    clickthrough_url: "/ask_IT_when_module_made"
    clickthrough_text: "IMIS (not correct)"
  - title: GEANS
    description: "Genetic tools for Ecosystem health Assessment in the North Sea region"
    clickthrough_url: "/ask_IT_when_module_made"
    clickthrough_text: "IMIS (not correct)"
  - title: Recreational beach fishing
    description: "A group all data sets from the porters, as well as other data sets related to recreational beach fishing"
    clickthrough_url: "/ask_IT_when_module_made"
    clickthrough_text: "IMIS (not correct)"
  - title: VLIZ robotics datasets 
    description: "Data sets containing all campaigns of the VLIZ marine robotics team"
    clickthrough_url: "/ask_IT_when_module_made"
    clickthrough_text: "IMIS (not correct)"
---

{% include light_bg.html content=
"<h2 style='text-align: center !important;'>Gateway to Marine Knowledge: Data Sharing and Preservation at the Flanders Marine Institute

</h2>

<p>
  
</p>
"
%}

{% include item/list/block/colored/main.html items=page.subblocks %}

  <div class="counter-container" style="display: flex; align-items: center;margin-bottom: 10px;">
    <h1 id="counter" style="font-size:48px;margin-right: 10px;font-size: 24px;">0</h1>
    <span style="color: #354d9b;"><strong>Datasets Available</strong></span>
  </div>

   <p>Join a thriving community of <strong>26,783 individuals</strong> and <strong>9,547 institutes</strong>, driving innovation across <strong>3,940 projects</strong>. 
   <br>At Flanders Marine Institute, we harness the power of data to foster collaboration and unlock new insights. 
         <br>
         <br>
         </p>

  <script>
        function startCounting(targetNumber, duration) {
            const counterDisplay = document.getElementById('counter');
            let count = 0; // Start from 0
            const incrementTime = Math.floor(duration / targetNumber); // Time for each increment
            console.log(incrementTime);

            const interval = setInterval(() => {
              if (count < targetNumber) {
                let increment = Math.max(1, Math.floor((targetNumber - count) / 125)); // Decrease increment as count approaches target
                count += increment;
                counterDisplay.textContent = count; // Update the display
              } else {
                clearInterval(interval); // Stop the counting when reaching the target
              }
            }, incrementTime);     }

        // Call the function to start counting automatically
        window.onload = () => {
            startCounting(5836, 0); // Change parameters as needed
        };
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
      <br>
        <p><a href="/about"><strong>Learn more about us</strong></a></p>

</div>
  <div class="col-md-6">
    <img src="assets/media/img/datacenter/robots.jpg">
      The <a href="https://www.vliz.be/nl/wat-we-doen/aanbod-infrastructuur/robotica">VLIZ Marine Robotics Centre</a> (MRC) pioneers in Marine Autonomous Systems (MAS) in order to enable comprehensive observations in remote, harsh, and vast environments within our world’s oceans and seas. Check out the data they collected in the database.
      <br>
      <br>
  </div>
</div>

{% include item/list/carrousel/block/main.html
    title="Special collections"
    items=page.special_collections
%}
