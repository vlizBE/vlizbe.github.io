---
layout: default
permalink: /portfolio
title: Portfolio
description: "Check out our connected projects and services. We offer a range of services to support the FAIR principles of data management. Learn more about our services and how they can help you in your research."
cover: /assets/media/img/datacenter/tech_2.jpg
curly: false
networks:
  - title: Open Geospatial Consortium
    description: "At OGC, we unite a global network of leaders across government, business, research institutions, startups, and the geospatial community."
    image: 
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
    clickthrough_text: 
  - title: EOSC Association
    description: "The EOSC Association works to advance Open Science in the service of creating new knowledge, inspiring education, spurring innovation and promoting accessibility and transparency"
    clickthrough_url: "https://eosc.eu/members/flanders-marine-institute-vliz/"
    clickthrough_text: 

data_systems:
  - title: World Register of Marine Species (WoRMs)
    description: "Taxonomic database (taxon names, distributions, specimens, ...)<br>
    <br>
     +50 installations based on species or geographical context"
    image_url: 
    image_alt: 
    clickthrough_url: "https://www.marinespecies.org/aphia.php?p=search"
    clickthrough_text: "Visit OGC"
  - title: IMIS - The Integrated Marine Information System
    description: "Metadata on people, institutes, references, and datasets, describing the marine landscape. <br> <br>+60 installations based on projects, topics or institutes"
    clickthrough_url: "https://vliz.be/en/imis"
    clickthrough_text: "IMIS"
  - title: Photo gallery
    description: "A collection of images & movies related to different projects & websites, accessible via their own URL's. <br> <br> +100 installations based on projects, topics or institutes. "
    clickthrough_url: "https://images.vliz.be/"
    clickthrough_text: 
  - title: IMERS
    description: "Stores measurement data based on water, sediment, suspended matter and biota samples <br><br> +10 installations based on projects Output framework: PHP"
    clickthrough_url: "https://vliz.be/vmdcdata/imers/"
    clickthrough_text: 
  - title: MarinePass
    description: "Central authentication system"
    clickthrough_url: "https://www.marinepass.org/app/login"
    clickthrough_text: 
  - title: Wiki
    description: "Wikipedia installation <br> <br> +10 installations based on topic or project"
    clickthrough_url: "www.coastalwiki.org"
    clickthrough_text: 
  - title:  EMODnet biology
    description: "Data portal and view occurrence and other data types"
    clickthrough_url: "https://www.emodnet-biology.eu/toolbox/en/download/occurrence/explore"
    clickthrough_text: "Data portal"
  - title: ETN
    description: "European Tracking Network-Data platform, featuring<br><br> +800,000,000 detections"
    clickthrough_url: "https://www.lifewatch.be/etn/"
    clickthrough_text: 
  - title: LifeWatch Belgium
    description: "Develops and operates a number of essential and complementary infrastructure components (species information backbone, observatory, and habitat mapping)"
    clickthrough_url: "http://www.lifewatch.be/data-services"
    clickthrough_text: 
  - title: ScheldeMonitor
    description: "Geoviewer for a Flemish-Dutch knowledge and information portal on research and monitoring in the Scheldt estuary."
    clickthrough_url: "http://www.scheldemonitor.org/geoviewer"
    clickthrough_text: "Data platform, featuring 882961381 detections"
  - title: Marine Regions Gazetteer
    description: "Standard, relational list of geographic names, coupled with information and maps of the geographic location of these features. "
    clickthrough_url: "http://www.marineregions.org/gazetteer.php?p=search"
    clickthrough_text: "hierarchical list of place names"
  - title: Sea Level Station Monitoring Facility
    description: "Monitor the status of real time sea level stations. <br><br> Active stations tracked : <br> 2024: 1249 <br> 2023: 1234 "
    clickthrough_url: "http://www.ioc-sealevelmonitoring.org/"
    clickthrough_text: "Monitor the status of real time sea level stations"
  - title: LifeWatch<br> RShiny Data Explorer
    description: "Expose all lifewatch data types"
    clickthrough_url: "http://rshiny.lifewatch.be/"
    clickthrough_text: 
  - title: LifeWatch <br> Buoys
    description: "Capture real-time data from logger on buoys <br><br>(Thornton, Spuikom, Meetnet Vlaamse Banken (MVB), ...)"
    clickthrough_url: "http://www.lifewatch.be/buoys"
    clickthrough_text: "hierarchical list of place names"
  - title: OBIS Annotated List
    description: "Scientific names originating from OBIS not matched to WoRMS"
    clickthrough_url: "https://annotated-list.eurobis.org/"
    clickthrough_text: "Scientific names originating from OBIS not matched to WoRMS"
  - title: OpenAIS
    description: "Set of tools that are aimed at reducing the time, technical skills, and domain expertise required to derive meaningful insight from raw vessel tracking data."
    clickthrough_url: "https://open-ais.org/"
    clickthrough_text: 
  - title: Cores Repository Index (CRI)
    description: "Manages data about cores drilled out of the sea. Users can view core data and add metadata (CRUD operations). <br><br> All get routes are accessible to everyone, but modifications require using authentication via JWT."
    clickthrough_url: ""
    clickthrough_text: ""
  - title: Vocab Server
    description: "A service where users or applications can query for details about a specific vocabulary"
    clickthrough_url: "http://docker-dev.vliz.be:3033/"
    clickthrough_text: "Vocabulary server kept up to date, for pick lists"
---

{% include item/list/carrousel/waved/main.html
    title="Data Systems"
    items=page.data_systems
%}

<h2>Networks</h2>

{% include item/list/row/text_image/main.html
    title="Networks"
    items=page.networks
%}


