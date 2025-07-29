---
layout: default
permalink: /services
title: Services
description: "Check out the services provided by the VLIZ Marine Data Centre. We offer a range of services to support the FAIR principles of data management. Learn more about our services and how they can help you in your research."
cover: /assets/media/img/datacenter/tech_1.jpg
curly: false
items:
  - title: Data-request
    description: "Looking for clean, reliable, and quality-checked marine data? Whether you're from the private sector, academia, or an NGO, our team is here to assist. Send us your data request today, and we’ll provide the high-quality information you need for your research or projects."
    image: /assets/media/img/datacenter/datarequest_corpo.png
    url: "mailto:data@vliz.be"
    icon_url:
      envelope: "mailto:data@vliz.be" 
    tags: []
  - title: Map service
    description: "Use these links to launch map or vector‑data requests from VLIZ’s Marine Regions – choose your area and export common layers like EEZ, territorial sea, or named features in GeoJSON, Shapefile or KML. For advanced custom maps, email the VLIZ team for professional assistance. "
    image: /assets/media/img/datacenter/maps.png
    url: "mailto:maps@vliz.be"
    icon_url:
        map: "https://geo.vliz.be/geoserver/web/?0"
        map-o: "https://www.marineregions.org/"
    tags: []
  - title: Library
    description: "The library is a public information center housing a wealth of information about the Flemish coast, the North Sea, and the world's oceans. The collection can be browsed online or on-site at the InnovOcean Campus. The library is open to the public."
    image: /assets/media/img/datacenter/Lib.png
    icon_url:
      book: "https://www.vliz.be/en/catalogue"
      link: "mailto:library@vliz.be"
    tags: []
  - title: DOI
    description: "VLIZ offers a DOI (Digital Object Identifier) data publication service to enable researchers to publish their data as citable and traceable datasets. Why is a DOI important? It provides a permanent link to your data, ensuring it remains accessible and citable in the future. This service is essential for researchers who want to enhance the visibility and impact of their datasets."
    image: /assets/media/img/datacenter/doi.png
    icon_url:
      file-pdf-o: "https://www.vliz.be/sites/vliz.be/files/public/docs/DOI_Guidelines.pdf"
      link: "https://marineinfo.org/metasubmit/"
    tags: []
  - title: Open AIS - Data requests
    description: "Looking for AIS data to support your research? Visit to request access to high-quality ship position datasets. Whether you need temporal coverage within a specific point range or information on ship crossings near areas of interest, the Open-AIS team can help you get the data you need."
    image: assets\media\img\datacenter\open-ais-logo.svg
    icon_url:
      file-pdf-o: "https://open-ais.org/"
      link: "https://open-ais.org/page/support/"
    tags: []
---
{% include item/list/row/image_text_link/main.html items=page.items %}

 <div class="container">
  <!-- Store Your Data Card -->
  <div class="card">
    <div class="card-inner" style="--clr:#fff;">
      <div class="box">
        <div class="imgBox">
          <img src="/assets/media/img/content/logo_mda2.png" alt="Store" width="400">
        </div>
      </div>
    </div>
<div class="content">
  <h3>Store your data</h3>
  <p>VLIZ highly values Open Science, and is therefore happy to make the data that are collected and processed freely available. This is done both through the library in the form of publications, and through the data center in the form of datasets.</p>
  <ul>
  <a href="https://marinedataarchive.org/" target="_blank" class="store-button">STORE</a>
</ul>
</div>
  </div>

  <!-- Publish Your Data Card -->
  <div class="card">
    <div class="card-inner" style="--clr:#fff;">
      <div class="box">
        <div class="imgBox">
          <img src="/assets/media/img/content/Marine Info_logo pos RGB.jpg" alt="Publsh" width="400">
        </div>
      </div>
    </div>
    <div class="content">
      <h3>Publish your data</h3>
      <p>You can publish your (meta) data using IMIS on MarineInfo.org. Data is made accessible in an efficient and open manner. The VLIZ is accredited as an IODE National Oceanographic Data Center.</p>
      <ul>
          <a href="https://marineinfo.org/metasubmit/" target="_blank" class="store-button">PUBLISH</a>
      </ul>
    </div>
  </div>

<style>
  .store-button {
    display: inline-block;
    padding: 0.75em 1.5em;
    background-color: #f7c97c;
    color: white;
    text-decoration: none;
    font-weight: bold;
    border-radius: 6px;
    transition: background-color 0.3s ease;
  }

  .store-button:hover {
    background-color:rgb(241, 187, 92);
  }
</style>



<style>
  .imgBox {
    width: 100%;
    height: 350px; /* or adjust as needed */
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .imgBox img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* cover = fill & crop; contain = fit without crop */
  }
  .card > .content {
    padding: 20px;
  }
</style>


<style>
.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.card {
  flex: 1 1 calc(33% - 20px);
  margin: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.imgBox img {
  width: 100%;
  height: auto;
}
</style>


