---
layout: default
permalink: /search
title: Start Exploring
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
</style>

<div class="section-bg">
    <h4>VMDC Database</h4>
    <p>Dive into an ocean of knowledge with our new linked open data catalogue - discover, connect and explore the vast network of marine data using MarineInfo.org.</p>
    <table>
        <tr>
            <td><button onclick="location.href='https://marineinfo.org/imis?module=person'">People</button></td>
            <td><button onclick="location.href='https://marineinfo.org/imis?module=institute'">Institutes</button></td>
            <td><button onclick="location.href='https://marineinfo.org/imis?module=project'">Projects</button></td>
        </tr>
        <tr>
            <td><button onclick="location.href='https://marineinfo.org/imis?module=dataset'">Dataset</button></td>
            <td><button onclick="location.href='https://marineinfo.org/imis-search'">Publications</button></td>
            <td><button onclick="location.href='https://marineinfo.org/imis?module=conference'">Events</button></td>
        </tr>
    </table>
</div>
<div class="section-bg">
    <h4>Hosted Datasystems</h4>
    <p>VLIZ Data Centre hosts various data systems that support marine and coastal research. These systems store, manage, and provide access to large datasets related to marine biodiversity, ecology, oceanography, and environmental monitoring.</p>
    <table>
        <tr>
            <td><button onclick="location.href='https://www.marinespecies.org/'">WoRMs</button></td>
            <td><button onclick="location.href='https://emodnet.ec.europa.eu/en/biology'">EMODnet Biology</button></td>
        </tr>
        <tr>
            <td><button onclick="location.href='https://marineregions.org/'">Marine Regions</button></td>
            <td><button onclick="location.href='https://www.eurobis.org/'">EurOBIS</button></td>
        </tr>
    </table>

<h4>Cruise Database</h4>

<div class="image-right">
        <img src="assets/media/img/datacenter/USVGobelijn.jpg" alt="MIDAS Logo">
        <p>
            MIDAS stands for Marine Information and Data Acquisition System. This suite of programs is developed at Flanders Marine Institute to plan the cruises of the RV Simon Stevin, to register the research activities during these cruises and to capture navigational, meteorological, and oceanographic parameters while underway.
            <br><br>
            All data is organized in cruises and trips. Either use the schedule, the chronological list of cruises, or the cruises ordered by campaigns to select a specific cruise and trip. For each performed trip a link to the underway data, the stations, research activities, and a map of the track is available.
        </p>
    </div>

<table>
        <tr>
            <td><button onclick="location.href='https://www.vliz.be/vmdcdata/midas/casts'">CTD Casts</button></td>
            <td><button onclick="location.href='https://www.vliz.be/vmdcdata/midas/stations/map'">Stations</button></td>
        </tr>
        <tr>
            <td><button onclick="location.href='https://www.vliz.be/vmdcdata/midas/cruises'">Cruises</button></td>
            <td><button onclick="location.href='https://www.vliz.be/vmdcdata/midas/campaigns'">Campaigns</button></td>
        </tr>
    </table>
</div>





