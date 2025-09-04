---
layout: default
permalink: /search
title: Find data and information
description: "Explore the VLIZ Marine Data Centre and discover the data available in the VLIZ Marine Data Centre"
cover: assets\media\img\datacenter\finddata_2.webp
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

<h2 style="text-align: center;">Hosted Data Systems</h2>
<div class="section-bg">
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
        <a href="https://www.lifewatch.be/data-services" target="_blank">
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
  </div>
  <!-- Data Portals Section: Organized and visually enhanced -->
  <h2 style="text-align: center;">VLIZ Data Portals</h2>
  <div class="section-bg">
<!-- Biodiversity -->
    <div class="section-bg">
    <h3>Biodiversity</h3>
    <br>
      <!-- Biodiversity Portals List -->
      <div style="display: flex; flex-direction: column; gap: 1.5rem;">
        <!-- ETN -->
        <div style="display: flex; align-items: center; gap: 1.5rem;">
          <img src="/assets/media/img/datacenter/ETN_logo.png" alt="ETN Logo" style="width:90px; height:auto; border-radius:8px;">
          <div>
            <h5>ETN</h5>
            <p>
              The <strong>European Tracking Network (ETN)</strong> data portal provides access to aquatic animal tracking data, including acoustic telemetry and archival data. Explore movement patterns and research on aquatic species across Europe.
            </p>
          </div>
          <a href="https://www.lifewatch.be/etn/" target="_blank" title="ETN Homepage" style="display: inline-block; background: #31b7bc; border-radius: 50%; min-width: 48px; height: 48px; text-align: center; line-height: 48px; margin-left: 0.5rem;">
            <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="white" viewBox="0 0 24 24" style="vertical-align: middle;">
              <path d="M3.9 12a5.1 5.1 0 0 1 5.1-5.1h3V5H9A7 7 0 0 0 9 19h3v-1.9h-3A5.1 5.1 0 0 1 3.9 12zm4.6 1h7v-2h-7v2zm6-8.1V5h1.9A5.1 5.1 0 0 1 21.1 12a5.1 5.1 0 0 1-5.1 5.1H15v1.9h1.9A7 7 0 0 0 15 5z"/>
            </svg>     
          </a>
        </div>
        <div style="display: flex; align-items: center; gap: 1.5rem;">
          <img src="assets/media/img/datacenter/lw-eric.png" alt="LifeWatch Belgium Logo" style="width:90px; height:auto; border-radius:8px;">
          <div>
            <h5>LifeWatch Belgium</h5>
            <p>
              <strong>LifeWatch Belgium</strong> offers data services and tools for biodiversity research, including species observations, ecological datasets, and data processing platforms supporting marine and terrestrial studies.
            </p>
          </div>
          <a href="https://www.lifewatch.be/data-services" target="_blank" title="LifeWatch Belgium" style="display: inline-block; background: #31b7bc; border-radius: 50%; min-width: 48px; height: 48px; text-align: center; line-height: 48px; margin-left: 0.5rem;">
            <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="white" viewBox="0 0 24 24" style="vertical-align: middle;">
              <path d="M3.9 12a5.1 5.1 0 0 1 5.1-5.1h3V5H9A7 7 0 0 0 9 19h3v-1.9h-3A5.1 5.1 0 0 1 3.9 12zm4.6 1h7v-2h-7v2zm6-8.1V5h1.9A5.1 5.1 0 0 1 21.1 12a5.1 5.1 0 0 1-5.1 5.1H15v1.9h1.9A7 7 0 0 0 15 5z"/>
            </svg>  
          </a>
        </div>
        <div style="display: flex; align-items: center; gap: 1.5rem;">
          <img src="assets/media/img/datacenter/EurOBIS_logo_.png" alt="EurOBIS Logo" style="width:90px; height:auto; border-radius:8px;">
          <div>
            <h5>EurOBIS</h5>
            <p>
              The <strong>European Ocean Biodiversity Information System (EurOBIS)</strong> is a data portal for biogeographic distribution of marine species, supporting research and policy with harmonized occurrence records.
            </p>
          </div>
          <a href="https://www.eurobis.org/data_access_services" target="_blank" title="EurOBIS Portal" style="display: inline-block; background: #31b7bc; border-radius: 50%; min-width: 48px; height: 48px; text-align: center; line-height: 48px; margin-left: 0.5rem;">
          <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="white" viewBox="0 0 24 24" style="vertical-align: middle;">
              <path d="M3.9 12a5.1 5.1 0 0 1 5.1-5.1h3V5H9A7 7 0 0 0 9 19h3v-1.9h-3A5.1 5.1 0 0 1 3.9 12zm4.6 1h7v-2h-7v2zm6-8.1V5h1.9A5.1 5.1 0 0 1 21.1 12a5.1 5.1 0 0 1-5.1 5.1H15v1.9h1.9A7 7 0 0 0 15 5z"/>
            </svg>  
          </a>
        </div>
        <!-- EMODnet Biology -->
        <div style="display: flex; align-items: center; gap: 1.5rem;">
          <img src="/assets/media/img/datacenter/emodnet.png" alt="EMODnet Logo" style="width:90px; height:auto; border-radius:8px;">
          <div>
            <h5>EMODnet Biology</h5>
            <p>
              <strong>EMODnet Biology</strong> provides access to in-situ marine biological data, including species distribution, abundance, and habitat information for European waters.
            </p>
          </div>
          <a href="https://emodnet.ec.europa.eu/geoviewer/" target="_blank" title="EMODnet Biology" style="display: inline-block; background: #31b7bc; border-radius: 50%; min-width: 48px; height: 48px; text-align: center; line-height: 48px; margin-left: 0.5rem;"><svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="white" viewBox="0 0 24 24" style="vertical-align: middle;">
              <path d="M3.9 12a5.1 5.1 0 0 1 5.1-5.1h3V5H9A7 7 0 0 0 9 19h3v-1.9h-3A5.1 5.1 0 0 1 3.9 12zm4.6 1h7v-2h-7v2zm6-8.1V5h1.9A5.1 5.1 0 0 1 21.1 12a5.1 5.1 0 0 1-5.1 5.1H15v1.9h1.9A7 7 0 0 0 15 5z"/>
            </svg>  
          </a>
        </div>
        <div style="display: flex; align-items: center; gap: 1.5rem;">
          <img src="/assets/media/img/datacenter/scheldemonitor_logo.svg" alt="ScheldeMonitor Logo" style="width:90px; height:auto; border-radius:8px;">
          <div>
            <h5>ScheldeMonitor</h5>
            <p>
              <strong>ScheldeMonitor</strong> is a Flemish-Dutch portal for research and monitoring in the Scheldt estuary, providing access to environmental data, reports, and knowledge resources.
            </p>
          </div>
          <a href="https://www.scheldemonitor.be/en" target="_blank" title="ScheldeMonitor" style="display: inline-block; background: #31b7bc; border-radius: 50%; min-width: 48px; height: 48px; text-align: center; line-height: 48px; margin-left: 0.5rem;"><svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="white" viewBox="0 0 24 24" style="vertical-align: middle;">
              <path d="M3.9 12a5.1 5.1 0 0 1 5.1-5.1h3V5H9A7 7 0 0 0 9 19h3v-1.9h-3A5.1 5.1 0 0 1 3.9 12zm4.6 1h7v-2h-7v2zm6-8.1V5h1.9A5.1 5.1 0 0 1 21.1 12a5.1 5.1 0 0 1-5.1 5.1H15v1.9h1.9A7 7 0 0 0 15 5z"/>
            </svg>  
          </a>
        </div>
      </div>
    </div>
    <div class="section-bg">
      <h3>Acoustic</h3>
      <br>
      <div style="display: flex; align-items: flex-start; gap: 2rem; flex-wrap: wrap; margin-bottom: 2rem;">
        <img src="/assets/media/img/datacenter/soundlib_logo.JPG" alt="SoundLib Logo" style="width:90px; height:auto; border-radius:8px;">
        <div style="flex: 1;">
          <h5>SoundLib</h5>
          <p>
            <strong>SoundLib</strong> is an open-access, AI-powered underwater sound library for the North Sea. It supports research on marine soundscapes, biodiversity, and noise pollution by providing curated audio datasets and analysis tools.
          </p>
        </div>
        <div style="display: flex; align-items: center; justify-content: flex-end; min-width: 60px;">
          <a href="https://www.marinesoundlib.org/data/en/stations" target="_blank" title="Visit SoundLib" style="display: inline-block; background: #31b7bc; border-radius: 50%; min-width: 48px; height: 48px; text-align: center; line-height: 48px;">
            <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="white" viewBox="0 0 24 24" style="vertical-align: middle;">
              <path d="M3.9 12a5.1 5.1 0 0 1 5.1-5.1h3V5H9A7 7 0 0 0 9 19h3v-1.9h-3A5.1 5.1 0 0 1 3.9 12zm4.6 1h7v-2h-7v2zm6-8.1V5h1.9A5.1 5.1 0 0 1 21.1 12a5.1 5.1 0 0 1-5.1 5.1H15v1.9h1.9A7 7 0 0 0 15 5z"/>
            </svg>  
          </a>
        </div>
      </div>
    </div>

   <!-- Geographic -->
   <div class="section-bg">
    <h3>Geographic</h3>
    <br>
    <!-- Marine Regions -->
    <div style="display: flex; align-items: flex-start; gap: 2rem; flex-wrap: wrap; margin-bottom: 2rem;">
      <img src="assets\media\img\datacenter\MR_icon.jpg" alt="Marine Regions Logo" style="width:90px; height:auto; border-radius:8px;">
      <div style="flex: 1;">
        <h5>Marine Regions</h5>
        <p>
          <strong>Marine Regions</strong> provides standardized geographic information on marine features, boundaries, and place names, supporting mapping and spatial analysis for marine science and policy.
        </p>
      </div>
      <div style="display: flex; align-items: center; justify-content: flex-end; min-width: 60px;">
        <a href="https://marineregions.org/gazetteer.php?p=search" target="_blank" title="Marine Regions" style="display: inline-block; background: #31b7bc; border-radius: 50%; min-width: 48px; height: 48px; text-align: center; line-height: 48px;">
          <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="white" viewBox="0 0 24 24" style="vertical-align: middle;">
              <path d="M3.9 12a5.1 5.1 0 0 1 5.1-5.1h3V5H9A7 7 0 0 0 9 19h3v-1.9h-3A5.1 5.1 0 0 1 3.9 12zm4.6 1h7v-2h-7v2zm6-8.1V5h1.9A5.1 5.1 0 0 1 21.1 12a5.1 5.1 0 0 1-5.1 5.1H15v1.9h1.9A7 7 0 0 0 15 5z"/>
            </svg>  
        </a>
      </div>
    </div>
    <!-- Bathymetry -->
    <div style="display: flex; align-items: flex-start; gap: 2rem; flex-wrap: wrap; margin-bottom: 2rem;">
      <img src="assets\media\img\datacenter\deepsea.JPG" alt="Bathymetry Icon" style="width:90px; height:auto; border-radius:8px;">
      <div style="flex: 1;">
        <h5>Bathymetry</h5>
        <p>
          We have made available some high resolution VLIZ bathymetry datasets from the Belgian part to the North Sea (BPNS) to EMODnet Bathymetry. Additionally, an overview of some more measurements that were carried out in the Belgian part of the North Sea can be seen on Kustportaal and downloaded via MDA.
        </p>
      </div>
      <div style="display: flex; flex-direction: column; align-items: flex-end; gap: 0.5rem; min-width: 60px;">
        <a href="https://www.kustportaal.be/geoviewer/index.php?lang=nl&layer_collections=KP_Bathymetrie+en+Bodemsamenstelling&active_layer_themes=Bathymetrie#!/" target="_blank" title="Kustportaal- BPNS" style="display: inline-block; background: #31b7bc; border-radius: 50%; min-width: 48px; height: 48px; text-align: center; line-height: 48px;">
          <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="white" viewBox="0 0 24 24" style="vertical-align: middle;">
              <path d="M3.9 12a5.1 5.1 0 0 1 5.1-5.1h3V5H9A7 7 0 0 0 9 19h3v-1.9h-3A5.1 5.1 0 0 1 3.9 12zm4.6 1h7v-2h-7v2zm6-8.1V5h1.9A5.1 5.1 0 0 1 21.1 12a5.1 5.1 0 0 1-5.1 5.1H15v1.9h1.9A7 7 0 0 0 15 5z"/>
            </svg>  
        </a>
        <a href="https://cdi.seadatanet.org/search/welcome.php?query=3219&query_code={927CE7BC-D84E-4814-B408-132599C94896}" target="_blank" title="SeaDataNet" style="display: inline-block; background: #31b7bc; border-radius: 50%; width: 48px; height: 48px; text-align: center; line-height: 48px;">
          <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="white" viewBox="0 0 24 24" style="vertical-align: middle;">
              <path d="M3.9 12a5.1 5.1 0 0 1 5.1-5.1h3V5H9A7 7 0 0 0 9 19h3v-1.9h-3A5.1 5.1 0 0 1 3.9 12zm4.6 1h7v-2h-7v2zm6-8.1V5h1.9A5.1 5.1 0 0 1 21.1 12a5.1 5.1 0 0 1-5.1 5.1H15v1.9h1.9A7 7 0 0 0 15 5z"/>
            </svg>  
        </a>
      </div>
    </div>
  </div>
  <!-- Taxonomic -->
  <div class="section-bg">
    <h3>Taxonomic</h3>
    <br>
    <div style="display: flex; align-items: flex-start; gap: 2rem; flex-wrap: wrap; margin-bottom: 2rem;">
      <img src="/assets/media/img/data_systems/WORMS.jpg" alt="WoRMS Logo" style="width:90px; height:auto; border-radius:8px;">
      <div style="flex: 1;">
        <h5>WoRMS</h5>
        <p>
          The <strong>World Register of Marine Species (WoRMS)</strong> is the authoritative database for marine species taxonomy, providing validated names, classification, and distribution information.
        </p>
      </div>
      <div style="display: flex; align-items: center; justify-content: flex-end; min-width: 60px;">
        <a href="https://www.marinespecies.org/aphia.php?p=search" target="_blank" title="WoRMS Search" style="display: inline-block; background: #31b7bc; border-radius: 50%; min-width: 48px; height: 48px; text-align: center; line-height: 48px;">
          <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" fill="white" viewBox="0 0 24 24" style="vertical-align: middle;">
              <path d="M3.9 12a5.1 5.1 0 0 1 5.1-5.1h3V5H9A7 7 0 0 0 9 19h3v-1.9h-3A5.1 5.1 0 0 1 3.9 12zm4.6 1h7v-2h-7v2zm6-8.1V5h1.9A5.1 5.1 0 0 1 21.1 12a5.1 5.1 0 0 1-5.1 5.1H15v1.9h1.9A7 7 0 0 0 15 5z"/>
            </svg>  
        </a>
      </div>
    </div>
  </div>


</div >
<h2 style="text-align: center;">Published data products and datasets </h2>
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

  <h4>Biodiversity dataset(s)</h4>
  <div style="display: flex; gap: 0.75rem; margin-bottom: 0.75rem;">
    <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
      <a href="https://www.vliz.be/nl/imis?module=dataset&dasid=4687" target="_blank" style="color: white;">Zooplankton by ZooScan</a>
    </button>
    <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
      <a href="https://www.vliz.be/nl/imis?module=dataset&dasid=4688" target="_blank" style="color: white;">Phytoplankton by FlowCam</a>
    </button>
    <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
      <a href="https://www.vliz.be/nl/imis?module=dataset&dasid=6720" target="_blank" style="color: white;">Zooplankton by VPR</a>
    </button>
  </div>
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
          <a href="https://www.vliz.be/en/imis?dasid=4598&amp;doiid=125" target="_blank" style="color: white;">Mesozooplankton</a>
        </button>
      </div>
      <div style="display: flex; gap: 0.75rem;">
        <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
          <a href="https://www.vliz.be/en/imis?dasid=4598&amp;doiid=125" target="_blank" style="color: white;">Belgian</a>
        </button>
        <button style="flex: 0 0 auto; width: auto; min-width: 100px; padding: 0.5rem 1rem;">
          <a href="https://marineinfo.org/imis?module=dataset&spcolid=1021&show=search" target="_blank" style="color: white;">Genetic</a>
        </button>
      </div>
    </div>
  </div>

  <h4>Robotics</h4>
  <div class="image-right">
    <div style="display: flex; flex-direction: column; align-items: center;">
      <img src="assets\media\img\datacenter\17_VLIZ_AUV_Barabas_Credit_VLIZ_WieterBoone.png" alt="RV Simon Stevin" width="250" height="auto">
      <span style="font-size: 0.9rem; color: #888; margin-top: 0.25rem;">Photo credit: Wieter Boone (VLIZ)</span>
    </div>
    <p>
      VLIZ operates a fleet of advanced marine robots, including one autonomous underwater vehicle (AUV), two uncrewed surface vehicles (USVs), and two ocean gliders. These systems are well-suited for both fundamental and applied research, environmental monitoring, seabed mapping, water quality assessment, and the collection of biological and physical data in challenging marine environments.
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
