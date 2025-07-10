---
layout: default
permalink: /systems
title: Systems
description: "Explore the VLIZ Marine Data Centre and discover the data systems we manage. We provide a range of systems to support marine research and data management."
cover: /assets/media/img/datacenter/tech_2.jpg
curly: false

# Featured Data Systems
data_systems:
  - title: World Register of Marine Species (WoRMS)
    description: "Taxonomic database for marine species. +50 installations based on species or geography."
    clickthrough_url: "https://www.marinespecies.org/aphia.php?p=search"
    clickthrough_text: "Visit WoRMS"
    image: /assets/media/img/data_systems/WORMS.jpg

  - title: IMIS - Integrated Marine Information System
    description: "Metadata on people, institutes, references, and datasets. +60 installations."
    clickthrough_url: "https://vliz.be/en/imis"
    clickthrough_text: "Access IMIS"

  - title: Photo Gallery
    description: "Image & video collection tied to projects & topics. +100 installations."
    clickthrough_url: "https://images.vliz.be/"
    clickthrough_text: "Browse Gallery"

  - title: EMODnet Biology
    description: "Marine biological data portal."
    clickthrough_url: "https://www.emodnet-biology.eu/toolbox/en/download/occurrence/explore"
    clickthrough_text: "Open Data Portal"

  - title: ETN
    description: "European Tracking Network with 800M+ detections."
    clickthrough_url: "https://www.lifewatch.be/etn/"
    clickthrough_text: "Explore ETN"

  - title: ScheldeMonitor
    description: "Geoviewer for the Scheldt estuary portal."
    clickthrough_url: "http://www.scheldemonitor.org/geoviewer"
    clickthrough_text: "Launch Geoviewer"

  - title: Marine Regions Gazetteer
    description: "Standard list of geographic names with maps."
    clickthrough_url: "http://www.marineregions.org/gazetteer.php?p=search"
    clickthrough_text: "Explore Gazetteer"

  - title: Sea Level Station Monitoring Facility
    description: "Tracks real-time sea level stations. 1249 active in 2024."
    clickthrough_url: "http://www.ioc-sealevelmonitoring.org/"
    clickthrough_text: "Monitor Sea Level"

  - title: LifeWatch RShiny Data Explorer
    description: "Interactive explorer for LifeWatch data."
    clickthrough_url: "http://rshiny.lifewatch.be/"
    clickthrough_text: "Launch Explorer"

  - title: OpenAIS
    description: "Tools for vessel tracking data insight."
    clickthrough_url: "https://open-ais.org/"
    clickthrough_text: "Explore OpenAIS"

  - title: Cores Repository Index (CRI)
    description: "Manage & view sea core data. Authenticated CRUD support."

  - title: Vocab Server
    description: "Service to query vocabulary details."
    clickthrough_url: "http://docker-dev.vliz.be:3033/"
    clickthrough_text: "Access Vocab Server"
---

{% include item/list/row/image_text_link/main.html
title="Systems"
items=page.data_systems %}

