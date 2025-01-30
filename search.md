---
layout: default
permalink: /search
title: Find data and information
description: "Explore the VLIZ Marine Data Centre and discover the data available in the VLIZ Marine Data Centre"
cover: /assets/media/img/datacenter/boat_1.jpg
curly: false
---

<style>
/* Section Header Styling */
    h4 {
        color: #354d9b; /* Navy blue color for headers */
    }
/* Table Styling */
    table {
        width: 100%;
        margin-bottom: 40px;
        border-collapse: collapse;
        background-color: #fff; /* White background for tables */
    }
    th, td {
        padding: 10px;
        text-align: left;
        border: 1px solid #ccc;
    }
/* Button Styling */
    button {
        padding: 10px 20px;
        width:100%;
        font-size: 16px;
        cursor: pointer;
        border: none;
        border-radius: 5px;
        background-color: #354d9b; /* Updated button color */
        color: white;
        transition: background-color 0.3s;
    }
    button:hover {
        background-color: #2c3e70; /* Slightly darker color for hover effect */
    }

/* Image Alignment */
    .image-right {
        display: flex;
        align-items: flex-start;
        flex-direction: row-reverse;
    }
    .image-right img {
        width: 250px;
        border-radius:5px;
        height: auto;
        margin-left: 20px;
    }
    .button-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 10px;
    }
</style>

<div class="section-bg">
    <h4>Catalogue</h4>
    <p>Dive into an ocean of knowledge with our new linked open (meta) data catalogue - discover, connect and explore the vast network of marine data using MarineInfo.org.</p>
    <div class="button-grid">
        <button onclick="location.href='https://marineinfo.org/imis?module=person'">People</button>
        <button onclick="location.href='https://marineinfo.org/imis?module=institute'">Institutes</button>
        <button onclick="location.href='https://marineinfo.org/imis?module=project'">Projects</button>
        <button onclick="location.href='https://marineinfo.org/imis?module=dataset'">Dataset</button>
        <button onclick="location.href='https://marineinfo.org/imis-search'">Publications</button>
        <button onclick="location.href='https://marineinfo.org/imis?module=conference'">Events</button>
    </div>
<br>
</div>
<div class="section-bg">
    <h4>Data systems</h4>
    <p>VLIZ hosts various data systems that support marine and coastal research. These systems store, manage, and provide access to large datasets related to marine biodiversity, ecology, oceanography, and environmental monitoring.</p>
    <div class="button-grid">
        <button onclick="location.href='https://www.marinespecies.org/aphia.php?p=search'">Search marine names on <br>WoRMs</button>
        <button onclick="location.href='https://emodnet.ec.europa.eu/geoviewer/'">Search in-situ marine data on <br>EMODnet Biology</button>
        <button onclick="location.href='https://marineregions.org/gazetteer.php?p=search'">Search marine places on <br>Marine Regions</button>
        <button onclick="location.href='https://www.eurobis.org/data_access_services'">Search biogeographic data on <br>EurOBIS</button>
    </div>
<br>
<h4>Cruise Database</h4>

<div class="image-right">
    <img src="assets/media/img/datacenter/USVGobelijn.jpg" alt="MIDAS Logo">
    <p>
        MIDAS stands for <b>Marine Information and Data Acquisition System</b>. This suite of programs is developed at Flanders Marine Institute to plan the cruises of the RV Simon Stevin, to register the research activities during these cruises and to capture navigational, meteorological, and oceanographic parameters while underway. All data is organized in cruises and trips. Either use the schedule, the chronological list of cruises, or the cruises ordered by campaigns to select a specific cruise and trip. For each performed trip a link to the underway data, the stations, research activities, and a map of the track is available.
    </p>
</div>

<div class="button-grid">
    <button onclick="location.href='https://www.vliz.be/vmdcdata/midas/casts'">CTD Casts</button>
    <button onclick="location.href='https://www.vliz.be/vmdcdata/midas/stations/map'">Stations</button>
    <button onclick="location.href='https://www.vliz.be/vmdcdata/midas/cruises'">Cruises</button>
    <button onclick="location.href='https://www.vliz.be/vmdcdata/midas/campaigns'">Campaigns</button>
</div>
<br>
</div>





