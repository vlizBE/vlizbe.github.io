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

<style>
  .section-bg {
    background-color: #f9f9f9;
    padding: 3rem 2rem;
    border-radius: 16px;
    margin: 3rem auto;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.06);
    font-family: 'Sofia Pro', sans-serif;
    max-width: 1200px;
  }

  .section-bg h4 {
    font-size: 1.75rem;
    margin-bottom: 0.75rem;
    color: #222;
    font-weight: 600;
  }

  .section-bg p {
    font-size: 1.05rem;
    color: #444;
    margin-bottom: 2rem;
    line-height: 1.6;
  }

  .button-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1.2rem;
    margin-bottom: 3rem;
  }

  .button-grid button {
    padding: 1rem 1.25rem;
    background-color: #31b7bc;
    color: white;
    border: none;
    border-radius: 8px;
    font-weight: 600;
    font-size: 1rem;
    cursor: pointer;
    text-align: center;
    transition: background-color 0.3s ease, transform 0.2s ease;
  }

  .button-grid button:hover {
    background-color: #2da3a7;
    transform: translateY(-2px);
  }

  .image-right {
    display: flex;
    align-items: flex-start;
    gap: 2rem;
    flex-wrap: wrap;
    margin-bottom: 2rem;
  }

  .image-right img {
    width: 100%;
    max-width: 350px;
    border-radius: 8px;
    object-fit: cover;
    box-shadow: 0 2px 12px rgba(0, 0, 0, 0.1);
  }

  .image-right p {
    flex: 1;
    font-size: 1rem;
    color: #444;
    line-height: 1.6;
  }

  @media (max-width: 768px) {
    .image-right {
      flex-direction: column;
    }

    .image-right img {
      max-width: 100%;
    }
  }
</style>

<div class="section-bg">
  <h4>Most relevant</h4>
  <p>VLIZ hosts various data systems that support marine and coastal research. These systems store, manage, and provide access to large datasets related to marine biodiversity, ecology, oceanography, and environmental monitoring.</p>
  <div class="button-grid">
    <button onclick="location.href='https://www.marinespecies.org/aphia.php?p=search'">
      Search marine names on <br>WoRMS
    </button>
    <button onclick="location.href='https://emodnet.ec.europa.eu/geoviewer/'">
      Search in-situ marine data on <br>EMODnet Biology
    </button>
    <button onclick="location.href='https://marineregions.org/gazetteer.php?p=search'">
      Search marine places on <br>Marine Regions
    </button>
    <button onclick="location.href='https://www.eurobis.org/data_access_services'">
      Search biogeographic data on <br>EurOBIS
    </button>
  </div>

  <h4>Catalogue</h4>
  <p>Dive into an ocean of knowledge with our new linked open (meta) data catalogue – discover, connect and explore the vast network of marine data using MarineInfo.org.</p>
  <div class="button-grid">
    <button onclick="location.href='https://marineinfo.org/imis?module=person'">People</button>
    <button onclick="location.href='https://marineinfo.org/imis?module=institute'">Institutes</button>
    <button onclick="location.href='https://marineinfo.org/imis?module=project'">Projects</button>
    <button onclick="location.href='https://marineinfo.org/imis?module=dataset'">Datasets</button>
    <button onclick="location.href='https://marineinfo.org/imis-search'">Publications</button>
    <button onclick="location.href='https://marineinfo.org/imis?module=conference'">Events</button>
  </div>

  <h4>Cruise Database</h4>
  <div class="image-right">
    <img src="\assets\media\img\datacenter\simonsteven.jpg" alt="RV Simon Stevin" width="250" height="auto">
    <p>
      <strong>MIDAS</strong> stands for <strong>Marine Information and Data Acquisition System</strong>. This suite of programs is developed at Flanders Marine Institute to plan the cruises of the RV Simon Stevin, to register the research activities during these cruises and to capture navigational, meteorological, and oceanographic parameters while underway.
      All data is organized in cruises and trips. Use the schedule, the chronological list of cruises, or cruises ordered by campaigns to select a specific cruise or trip. For each performed trip, a link to the underway data, the stations, research activities, and a map of the track is available.
    </p>
  </div>

  <div class="button-grid">
    <button onclick="location.href='https://www.vliz.be/vmdcdata/midas/casts'">CTD Casts</button>
    <button onclick="location.href='https://www.vliz.be/vmdcdata/midas/stations/map'">Stations</button>
    <button onclick="location.href='https://www.vliz.be/vmdcdata/midas/cruises'">Cruises</button>
    <button onclick="location.href='https://www.vliz.be/vmdcdata/midas/campaigns'">Campaigns</button>
  </div>
</div>




<style>
  .cta-box {
    background: #f4f4f4;
    border-left: 6px solid #f7c97c;
    padding: 1.5rem;
    margin: 2rem 0;
    border-radius: 8px;
    font-family: 'sofia-pro', sans-serif;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  }

  .cta-box h4 {
    margin-top: 0;
    font-size: 1.25rem;
    color: #333;
  }

  .cta-box p {
    margin-bottom: 1rem;
    font-size: 1rem;
    color: #555;
  }

  .cta-box a.cta-button {
    display: inline-block;
    padding: 0.75rem 1.5rem;
    background-color: #f7c97c;
    color: white;
    font-weight: bold;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  }

  .cta-box a.cta-button:hover {
    background-color:rgb(216, 144, 36);
  }
</style>

<div class="cta-box">
  <h4>Can't find what you're looking for?</h4>
  <p>Send us your data request today, and we’ll provide the high-quality information you need for your research or projects.</p>
  <a href="mailto:data@vliz.be" class="cta-button">Send a data request</a>
</div>


