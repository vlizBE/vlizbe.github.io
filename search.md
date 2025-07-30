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

  .button-grid > button > a {
    color: white;
    text-decoration: none;
    transition: color 0.3s ease;
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
<h2>Hosted data systems</h2>
<br> 
  <h4>Most relevant</h4>
  <div class="button-grid">
    <button>
        <a href="https://www.marinespecies.org/aphia.php?p=search" target="_blank">
            Search marine names on <br>WoRMS
        </a>
    </button>
    <button>
        <a href="https://emodnet.ec.europa.eu/geoviewer/" target="_blank">
            Search in-situ marine data on <br>EMODnet Biology
        </a>
    </button>
    <button>
        <a href="https://marineregions.org/gazetteer.php?p=search" target="_blank">
            Search marine features on <br>Marine Regions
        </a>
    </button>
    <button>
        <a href="https://www.eurobis.org/data_access_services" target="_blank">
            Search biogeographic data on <br>EurOBIS
        </a>
    </button>
        <button>
        <a href="https://www.eurobis.org/data_access_services" target="_blank">
            Search data processing tools  <br>LifeWatch Belgium
        </a>
    </button>
  </div>
<br>


  <h4>Metadata Catalogue</h4>
  <p>Access to our new linked open (meta) data catalogue – discover, re-use, or search the vast network of marine data using MarineInfo.org via Integrated Marine Information System (IMIS). Here at the VLIZ we are applying linked-open-data principles and technologies as a basis for ensuring the FAIR values. </p>
  <div class="button-grid">
    <button>
        <a href="https://marineinfo.org/search?size=n_20_n&filters%5B0%5D%5Bfield%5D=type&filters%5B0%5D%5Bvalues%5D%5B0%5D=person&filters%5B0%5D%5Btype%5D=aggregation&filters%5B0%5D%5Bpersistent%5D=false" target="_blank">People</a>
    </button>
    <button>
        <a href="https://marineinfo.org/search?size=n_20_n&filters%5B0%5D%5Bfield%5D=type&filters%5B0%5D%5Bvalues%5D%5B0%5D=institute&filters%5B0%5D%5Btype%5D=aggregation&filters%5B0%5D%5Bpersistent%5D=false">Institutes</a>
    </button>
    <button>
        <a href="https://marineinfo.org/search?size=n_20_n&filters%5B0%5D%5Bfield%5D=type&filters%5B0%5D%5Bvalues%5D%5B0%5D=project&filters%5B0%5D%5Btype%5D=aggregation&filters%5B0%5D%5Bpersistent%5D=false" target="_blank">Projects</a>
    </button>
    <button>
        <a href="https://marineinfo.org/search?size=n_20_n&filters%5B0%5D%5Bfield%5D=type&filters%5B0%5D%5Bvalues%5D%5B0%5D=dataset&filters%5B0%5D%5Btype%5D=aggregation&filters%5B0%5D%5Bpersistent%5D=false" target="_blank">Datasets</a>
    </button>
    <button>
        <a href="https://marineinfo.org/search?size=n_20_n&filters%5B0%5D%5Bfield%5D=type&filters%5B0%5D%5Bvalues%5D%5B0%5D=publication&filters%5B0%5D%5Btype%5D=aggregation&filters%5B0%5D%5Bpersistent%5D=false" target="_blank">Publications</a>
    </button>
    <button>
        <a href="https://marineinfo.org/search?size=n_20_n&filters%5B0%5D%5Bfield%5D=type&filters%5B0%5D%5Bvalues%5D%5B0%5D=event&filters%5B0%5D%5Btype%5D=aggregation&filters%5B0%5D%5Bpersistent%5D=false" target="_blank">Events</a>
    </button>
  </div>
  <h3>European and Belgian</h3>
  <br>
<div class="image-right">
  <img src="/assets/media/img/datacenter/ETN_logo.png" alt="ETN Logo" style="width:90px; height:auto; border-radius:8px;">
  <p>
    The ETN - European tracking network data portal gives access to different types of aquatic animal tracking data. Currently acoustic telemetry, archival data, and acoustic-archival data are supported.
  </p>
</div>
 <div class="button-grid">
    <div style="display: flex; justify-content: flex-start;">
      <button style="width: auto; min-width: 120px; padding: 0.5rem 1rem;">
        <a href="https://www.lifewatch.be/etn/" target="_blank" style="color: white;">ETN Homepage</a>
      </button>
    </div>
  </div>
 
<br>
  <h4>ScheldMonitor</h4>
  <div class="image-right">
    <img src="/assets/media/img/datacenter/scheldemonitor_logo.svg" alt="ScheldMonitor Logo" style="width:140px; height:auto; border-radius:8px;">
    <p>
      ScheldeMonitor is a Flemish-Dutch knowledge and information portal on research and monitoring in the Scheldt estuary. Commissioned by the Flemish-Dutch Scheldt Committee (VNSC), the portal serves as a central point for capturing and distributing many kinds of data and information concerning the various aspects that play a role across the entire area of the Western Scheldt and the Sea Scheldt.
    </p>
  </div>
  <div class="button-grid">
    <div style="display: flex; justify-content: flex-start;">
      <button style="width: auto; min-width: 120px; padding: 0.5rem 1rem;">
        <a href="https://www.scheldemonitor.be/en" target="_blank" style="color: white;">Scheldemonitor</a>
      </button>
    </div>
  </div>

  <h4>SoundLib</h4>
  <div class="image-right">
    <img src="/assets/media/img/datacenter/soundlib_logo.JPG" alt="SoundLib Logo" style="width:140px; height:auto; border-radius:8px;">
    <p>
      An AI underwater sound library for the North Sea: SoundLib is an open-access library, dedicated to underwater sound recordings and acoustic data from marine environments. The project aims to support research on marine soundscapes, biodiversity, and the impact of noise pollution by providing curated audio datasets, metadata, and analysis tools for scientists, educators, and policymakers.
    </p>
  </div>
  <div class="button-grid">
    <div style="display: flex; gap: 0.75rem;">
      <button style="width: auto; min-width: 120px; padding: 0.5rem 1rem;">
        <a href="https://marinesoundlib.org/en" target="_blank" style="color: white;">SoundLib</a>
      </button>
      <button style="width: auto; min-width: 120px; padding: 0.5rem 1rem;">
        <a href="https://www.vliz.be/en/ai-underwater-sound-library-north-sea" target="_blank" style="color: white;">More info</a>
      </button>
    </div>
  </div>

</div>
<h2>Published data products </h2>
<br>
  <h4>Cruise database</h4>
  <div class="image-right">
    <img src="\assets\media\img\datacenter\simonsteven.jpg" alt="RV Simon Stevin" width="250" height="auto">
    <p>
      <strong>MIDAS</strong> stands for <strong>Marine Information and Data Acquisition System</strong>.
      All data is organized in cruises and trips. Use the schedule, the chronological list of cruises, or cruises ordered by campaigns to select a specific cruise or trip. For each performed trip, a link to the underway data, the stations, research activities, and a map of the track is available.
    </p>
    <div style="display: flex; gap: 0.75rem; margin-top: 0.5rem;">
      <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
        <a href="https://www.vliz.be/vmdcdata/midas/campaigns" target="_blank" style="color: white;">Campaigns</a>
      </button>
      <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
        <a href="https://www.vliz.be/vmdcdata/midas/cruises" target="_blank" style="color: white;">Cruises</a>
      </button>
      <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
        <a href="https://www.vliz.be/vmdcdata/midas/stations/map" target="_blank" style="color: white;">Stations</a>
      </button>
      <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
        <a href="https://www.vliz.be/vmdcdata/midas/casts" target="_blank" style="color: white;">CTD Casts</a>
      </button>
    </div>
  </div>

  <h4>Biodiversity</h4>
  <div class="image-right">
    <img src="\assets\media\img\content\Thema_Biodiversiteit_tekst_optie1_small.jpg" alt="RV Simon Stevin" width="250" height="auto">
    <p>
    VLIZ explores <strong>marine biodiversity</strong> through a range of research projects, focusing on organisms of all sizes and habitats. Our collections include comprehensive biodiversity datasets that support research on the health of marine ecosystems across Europe.
    </p>
    <div style="display: flex; flex-direction: column; gap: 0.75rem; margin-top: 0.5rem;">
      <div style="display: flex; gap: 0.75rem;">
        <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
          <a href="https://obis.org/dataset/781886f1-2d10-4752-9b04-24a22d6205ff" target="_blank" style="color: white;">Phytoplankton</a>
        </button>
        <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
          <a href="https://obis.org/dataset/7a58ffd1-09d6-48a6-ba0b-07b8c4d474ca" target="_blank" style="color: white;">Macrobenthos</a>
        </button>
        <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
          <a href="https://obis.org/dataset/877a23ca-4950-4237-a405-be49217cfc94" target="_blank" style="color: white;">Bentic Fauna</a>
        </button>
      </div>
      <div style="display: flex; gap: 0.75rem;">
        <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
          <a href="https://www.vliz.be/en/imis?dasid=5659&doiid=303" target="_blank" style="color: white;">Zooplankton</a>
        </button>
        <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
          <a href="https://erddap.eurobis.org/erddap/info/north_sea_hypbent_com/index.html" target="_blank" style="color: white;">Hyperbenthic communities</a>
        </button>
     <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
          <a href="https://www.vliz.be/en/imis?dasid=4598&amp;doiid=125" target="_blank" style="color: white;">Mesozooplankton </a>
        </button>
      </div>
    </div>
  </div>

  <h4>Robotics</h4>
  <div class="image-right">
    <img src="assets\media\img\datacenter\ClayTectonics_AUV_Barabas.jpg" alt="RV Simon Stevin" width="250" height="auto">
    <p>
    VLIZ operates a fleet of advanced marine robots, including one autonomous underwater vehicle (AUV), two uncrewed surface vehicles (USVs), and two ocean gliders. These systems are well-suited for both fundamental and applied research, environmental monitoring, seabed mapping, water quality assessment, and the collection of biological and physical data in challenging marine environments
      <br>
      <br>
      Check the data out on <a href="https://www.ncei.noaa.gov/erddap/index.html" target="_blank">ERDDAP</a> — it connects to remote servers for you, fetches and reformats the data, so you get what you need without hopping between sources.
    </p>
    <div style="display: flex; gap: 0.75rem; margin-top: 0.5rem;">
      <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
        <a href="https://erddap.vliz.be/erddap/search/index.html?page=1&itemsPerPage=1000&searchFor=VLIZ" target="_blank" style="color: white;">AUV Barabas</a>
      </button>
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


