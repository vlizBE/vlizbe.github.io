---
layout: default
permalink: /search
title: Start Exploring
description: "Explore the VLIZ Marine Data Centre and discover the data available in the VLIZ Marine Data Centre"
cover: /assets/media/img/datacenter/boat_1.jpg
curly: false
networks:
  - title: Open Geospatial Consortium
    description: "At OGC, we unite a global network of leaders across government, business, research institutions, startups, and the geospatial community."
    image: "/assets/media/img/content/ogclogo.png" #LOGO NOT APPEARING, WOULD BE NICE TO SHOW THE LOGO 
    image_alt: "OGC logo"
    clickthrough_url: "https://www.ogc.org/"
    clickthrough_text: "Visit OGC"
  - title: EUROBIS
    description: "The European Node
      of the international Ocean Biodiversity Information System (OBIS) - publishes distribution data on marine species, collected within European marine waters or collected by European researchers"
    clickthrough_url: "https://www.eurobis.org/"
    clickthrough_text: "IMIS (not correct)"
  - title: The Flemish Research Data Network (FRDN)
    description: "Develops the preconditions necessary to motivate and enable researchers from Flemish research performing organizations to exchange and reuse (FAIR) research (meta)data. This contributes to the integrity, quality, and efficiency of research and thus to accelerating innovation in society."
    clickthrough_url: "https://www.frdn.be/"
    clickthrough_text: "https://www.ogc.org/"
  - title: The Blue Cluster
    description: "In 2019, a cooperation agreement was concluded between the VLIZ and The Blue Cluster to promote cooperation in the areas of project operation, internationalization of research, scientific support, joint events and communication, as well as around the representation of the VLIZ in the management bodies of The Blue Cluster."
    clickthrough_url: "https://www.blauwecluster.be/"
    clickthrough_text: "https://www.ogc.org/"
  - title: EOSC Association
    description: "The EOSC Association works to advance Open Science in the service of creating new knowledge, inspiring education, spurring innovation and promoting accessibility and transparency"
    clickthrough_url: "https://eosc.eu/members/flanders-marine-institute-vliz/"
    clickthrough_text: "https://www.ogc.org/"
---

{% include item/list/row/text_image/main.html
    title="Networks"
    items=page.networks
%}
---
# Search VMDC Database

Lorem ipsum dolor sit amet, consectetur adipiscing elit sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

here you would put other stuff

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
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
    <table>
        <tr>
            <td>Access to all the people held in our database</td>
            <td><button onclick="location.href='https://www.example.com/page1'">People</button></td>
        </tr>
        <tr>
                <td>Access to all the institutes held in our database</td>
                <td><button onclick="location.href='https://www.example.com/page2'">Institutes</button></td>
        </tr>
        <tr>
            <td>Access to all the projects held in our database</td>
            <td><button onclick="location.href='https://www.example.com/page3'">Projects</button></td>
        </tr>
        <tr>
            <td>Access to all the datasets held in our database</td>
            <td><button onclick="location.href='https://www.example.com/page4'">Dataset</button></td>
        </tr>
    </table>
</div>
<div class="section-bg">
    <h4>Hosted Datasystems</h4>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
    <table>
        <tr>
            <td><button onclick="location.href='https://www.marinespecies.org/'">WoRMs</button></td>
            <td>Minimize the number of clicks to go directly to searching the database.</td>
        </tr>
        <tr>
            <td><button onclick="location.href='https://emodnet.ec.europa.eu/en/biology'">EMODnet Biology</button></td>
            <td>Blah blah Blah....</td>
        </tr>
        <tr>
            <td><button onclick="location.href='https://marineregions.org/'">Marine Regions</button></td>
            <td>Blah blah Blah....</td>
        </tr>
        <tr>
            <td><button onclick="location.href='https://www.eurobis.org/'">EurOBIS</button></td>
            <td>Blah blah Blah....</td>
        </tr>
    </table>
</div>
<h4>Cruise Database</h4>

<div class="image-right">
    <img src="assets/media/img/datacenter/USVGobelijn.jpg" alt="MIDAS Logo">
    <p>
        MIDAS stands for Marine Information and Data Acquisition System. This suite of programs is developed at Flanders Marine Institute (VLIZ) to plan the cruises of the RV Simon Stevin, to register the research activities during these cruises and to capture navigational, meteorological, and oceanographic parameters while underway.  
        <br><br>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...
    </p>
</div>

 <table>
    <tr>
        <td><button onclick="location.href='https://www.vliz.be/vmdcdata/midas/casts'">CTD Casts</button></td>
        <td>CTD data</td>
    </tr>
    <tr>
        <td><button onclick="location.href='https://www.vliz.be/vmdcdata/midas/stations/map'">Stations</button></td>
        <td>Blah blah Blah....</td>
    </tr>
    <tr>
        <td><button onclick="location.href='https://www.vliz.be/vmdcdata/midas/cruises'">Cruises</button></td>
        <td>Blah blah Blah....</td>
    </tr>
    <tr>
        <td><button onclick="location.href='https://www.vliz.be/vmdcdata/midas/campaigns'">Campaigns</button></td>
        <td>List of campaigns</td>
    </tr>
</table>

[**Do we want this?**](https://www.coretrustseal.org/why-certification/requirements/?)




