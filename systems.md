---
layout: default
permalink: /systems
title: Systems
description: "Explore the VLIZ Marine Data Centre and discover the data systems we manage. We provide a range of systems to support marine research and data management."
cover: /assets/media/img/datacenter/tech_2.jpg
curly: false

# Featured Data Systems
data_systems:
  - title: WoRMS - World Register of Marine Species
    description: "The World Register of Marine Species (WoRMS) provides an authoritative list of marine organism names, prioritizing valid names while including synonyms to aid in interpreting taxonomic literature. It supports several projects, including LifeWatch Species Information."
    clickthrough_url: "https://www.marinespecies.org/aphia.php?p=search"
    clickthrough_text: "Visit WoRMS"
    image: /assets/media/img/data_systems/WORMS.jpg

  - title: IMIS - Integrated Marine Information System
    description: "IMIS is a metadata catalog for people, institutes, references, and datasets, designed to integrate with VLIZ databases like the Marine Data Archive (MDA) and WoRMS. It follows the FAIR principles to ensure data is Findable, Accessible, Interoperable, and Reusable."
    clickthrough_url: "https://vliz.be/en/imis"
    clickthrough_text: "Access IMIS"
    image: assets\media\img\datacenter\imis_logo.png

  - title: Photo Gallery
    description: "A collection of 169,821 images and 772 videos (~380GB) organized into 3,544 albums across 125 projects and websites. Content is licensed under Creative Commons Attribution-Noncommercial-Share Alike 4.0. The collection is directly linked to VLIZ data systems such as Aphia, IMIS, and the Marineregions Gazetteer"
    clickthrough_url: "https://images.vliz.be/"
    clickthrough_text: "Browse Gallery"
    image: assets\media\img\datacenter\photogallery_logo.png

  - title: EMODnet Biology - European Marine Observation and Data Network
    description: "Marine biological data portal. European Marine Observation and Data Network provides open access to high-quality, standardized marine data across Europe, supporting marine research, policy, and sustainable management."
    clickthrough_url: "https://www.emodnet-biology.eu/toolbox/en/download/occurrence/explore"
    clickthrough_text: "Open Data Portal"
    image: /assets/media/img/datacenter/emodnet.png

  - title: ETN - European Tracking Network
    description: "The European Tracking Network (ETN) by LifeWatch Belgium is a large-scale platform tracking aquatic animal movements using acoustic telemetry. It aggregates data from thousands of tagged animals across many species, supporting research on migration, habitat use, and climate impacts"
    clickthrough_url: "https://www.lifewatch.be/etn/"
    clickthrough_text: "Explore ETN"
    image: assets/media/img/datacenter/ETN_logo.png

  - title: ScheldeMonitor
    description: "Geoviewer for the Scheldt estuary portal. A Flemish-Dutch knowledge and information portal focused on research and monitoring within the Scheldt estuary. It serves as a central hub for data and information related to the entire area of the Western Scheldt and the Sea Scheldt."
    clickthrough_url: "http://www.scheldemonitor.org/geoviewer"
    clickthrough_text: "Launch Geoviewer"
    image: assets\media\img\datacenter\scheldemonitor_logo.svg

  - title: Marine Regions Gazetteer
    description: "A catalogue of over 79,000 place names across more than 64,000 marine locations globally, including seas, bays, ridges, and sampling stations. The Gazetteer supports various applications, such as linking species distribution data from the World Register of Marine Species (WoRMS) and integrating with the ScheldeMonitor. Each geographic feature is assigned a unique identifier (MRGID) and can be visualized through dynamic maps and accessed via web services."
    clickthrough_url: "http://www.marineregions.org/gazetteer.php?p=search"
    clickthrough_text: "Explore Gazetteer"
    image: assets\media\img\datacenter\MR_logo.jpg

  - title: Sea Level Station Monitoring Facility
    description: "A global platform providing real-time sea level data from over 1,250 monitoring stations across 170 operators worldwide. Established in 2006 to address sea-level monitoring gaps, particularly in Africa, the facility has since expanded to support tsunami early warning systems and climate research. It is recognized as an Ocean Decade Project under the Ocean Decade Tsunami Programme."
    clickthrough_url: "http://www.ioc-sealevelmonitoring.org/"
    clickthrough_text: "Monitor Sea Level"
    image: assets\media\img\datacenter\SLM_logo.png

  - title: LifeWatch RShiny Data Explorer
    description: "Interactive explorer for LifeWatch data. The platform offers access to an extensive array of environmental and biodiversity datasets acquired through diverse monitoring programs. It enables users to explore, visualize, and conduct analyses of data pertaining to both marine and terrestrial ecosystems."
    clickthrough_url: "http://rshiny.lifewatch.be/"
    clickthrough_text: "Launch Explorer"
    image: assets\media\img\datacenter\lw-eric.png

  - title: OpenAIS
    description: "Provides a suite of containerized software tools designed to process, store, and analyze Automatic Identification System (AIS) data. These tools enable researchers to transform raw vessel tracking information into structured datasets, facilitating spatio-temporal analyses and integration with other research data. OpenAIS aims to reduce the technical barriers to utilizing AIS data, making it more accessible for scientific inquiry and public good applications."
    clickthrough_url: "https://open-ais.org/"
    clickthrough_text: "Explore OpenAIS"
    image: assets\media\img\datacenter\open-ais-logo.svg

  - title: Vocab Server
    description: "A web service that hosts controlled vocabularies or ontologies designed to standardize terminology within marine and environmental data. It provides structured and authoritative lists of terms—such as categories, definitions, and classifications—used across VLIZ’s databases and projects to promote consistent data annotation and enhance interoperability."
    clickthrough_url: "http://docker-dev.vliz.be:3033/"
    clickthrough_text: "Access Vocab Server"
    image: assets\media\img\datacenter\vocabserver_logo.png


  - #title: Cores Repository Index (CRI)
    #description: "Manage & view sea core data. Authenticated CRUD support."
    #clickthrough_url: "https://open-ais.org/"
    #clickthrough_text: "Explore OpenAIS"
    #image: /assets/media/img/data_systems/WORMS.jpg


---

{% include item/list/row/image_text_link/main.html
title="Systems"
items=page.data_systems %}

