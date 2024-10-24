---
layout: default
graph_logo_bg: true
description: "Discover Open Science at VLIZ, where we're making science more efficient, reliable, and transparent. Learn about our mission, values, and core principles. Join us in our journey!"
cover: /assets/media/img/datacenter/Fisheries_4.jpg
title: "DATA VLIZ"
subblocks:
  - title: "Data submission"
    description: "Submit your data to the VLIZ Marine Data Centre"
    #image: /assets/media/img/ist/submit.jpg
    clickthrough_url: "/data/submit/"
  - title: "Data inventory"
    description: "Discover the data available in the VLIZ Marine Data Centre"
    #image: /assets/media/img/ist/inventory.jpg
    clickthrough_url: "/data/inventory/"
  - title: "Data resources"
    description: "Explore the resources available in the VLIZ Marine Data Centre"
    #image: /assets/media/img/ist/resources.jpg
    clickthrough_url: "/data/resources/"
special_collections:
  - title: Scheldemonitor
    description: "Een Vlaams-Nederlands kennis- en informatieportaal rond onderzoek en monitoring in het Schelde-estuarium."
    clickthrough_url: "/ask_IT_when_module_made"
    clickthrough_text: "IMIS (not correct)"
  - title: EUROBIS
    description: "the European Node
      of the international Ocean Biodiversity Information System (OBIS) - publishes distribution data on marine species, collected within European marine waters or collected by European researchers"
    clickthrough_url: "/ask_IT_when_module_made"
    clickthrough_text: "IMIS (not correct)"
  - title: Lorem
    description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
    clickthrough_url: "/ask_IT_when_module_made"
    clickthrough_text: "IMIS (not correct)"
  - title: IPSUM
    description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Count Up Animation</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start; /* Align items at the top */
            min-height: 100vh; /* Ensure minimum height for the viewport */
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            padding: 20px;
            box-sizing: border-box;
            margin: 0; /* Remove default body margin */
        }
        .counter-container {
            display: flex;
            align-items: center; /* Center items vertically */
            font-size: 24px; /* Adjust text size as needed */
            margin-bottom: 10px; /* Reduced space below the counter text */
        }
        #counter {
            font-size: 48px; /* Make the counter larger */
            margin-right: 10px; /* Space between counter and text */
        }
    </style>
</head>
<body>

    <div class="counter-container">
        <h1 id="counter">0</h1>
        <span>Datasets Available</span>
    </div>

         <p>Join a thriving community of <strong>26,783 individuals</strong> and <strong>9,547 institutes</strong>, driving innovation across <strong>3,940 projects</strong>. At Flanders Marine Institute, we harness the power of data to foster collaboration and unlock new insights.</p>


    <script>
        function startCounting(targetNumber, duration) {
            const counterDisplay = document.getElementById('counter');
            let count = 0; // Start from 0
            const incrementTime = Math.floor(duration / targetNumber); // Time for each increment

            const interval = setInterval(() => {
                if (count < targetNumber) {
                    count++;
                    counterDisplay.textContent = count; // Update the display
                } else {
                    clearInterval(interval); // Stop the counting when reaching the target
                }
            }, incrementTime);
        }

        // Call the function to start counting automatically
        window.onload = () => {
            startCounting(5836, 3000); // Change parameters as needed
        };
    </script>

</body>
</html>




<div class="row">
    <div class="col-md-6">
        <h4>Access to over 270,084 unique publications</h4>
        The VLIZ Marine Data Centre or VMDC is a national and international point of contact for quality and reliable marine and estuarine data. The VMDC provides services, technologies, tools, training and support to scientists, policy, blue economy and citizens. Data is made accessible in an efficient and open manner. The VMDC is accredited as an IODE National Oceanographic Data Center.
        <style>
  .button {
    display: inline-block;
    padding: 15px 30px;
    margin: 10px;
    font-size: 24px;
    text-align: center;
    text-decoration: none;
    color: white;
    background-color: #0779bf; /* Button color */
    border-radius: 5px;
    transition: background-color 0.3s;
  }

  .button:hover {
    background-color: #0056b3; /* Darker shade on hover */
  }
</style>

<p><a href="/search" class="button"><strong>Start exploring</strong></a></p>
<p><a href="/submit" class="button"><strong>Submit your data</strong></a></p>


        
        <h4>What does VMDC do?</h4>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        <p><a href="/about">Learn more about us</a></p>
    </div>
    <div class="col-md-6">
        <img src="assets/media/img/datacenter/robots.jpg">
        The <a href="https://www.vliz.be/nl/wat-we-doen/aanbod-infrastructuur/robotica">VLIZ Marine Robotics Centre</a> (MRC) pioneers in Marine Autonomous Systems (MAS) in order to enable comprehensive observations in remote, harsh, and vast environments within our world’s oceans and seas.
    </div>
</div>

{% include item/list/carrousel/block/main.html
    title="Special collections"
    items=page.special_collections
%}


