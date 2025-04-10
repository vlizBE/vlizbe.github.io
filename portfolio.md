---
layout: default
permalink: /portfolio
title: Portfolio
description: "Check out our connected projects and services. We offer a range of services to support the FAIR principles of data management. Learn more about our services and how they can help you in your research."
cover: /assets/media/img/datacenter/tech_2.jpg
curly: false

# Highlighted Networks
networks:
  - title: Open Geospatial Consortium
    description: "At OGC, we unite a global network of leaders across government, business, research institutions, startups, and the geospatial community."
    image_alt: "OGC logo"
    clickthrough_url: "https://www.ogc.org/"
    clickthrough_text: "Visit OGC"

  - title: EUROBIS
    description: "The European Node of the international Ocean Biodiversity Information System (OBIS) - publishes distribution data on marine species, collected within European marine waters or collected by European researchers."
    clickthrough_url: "https://www.eurobis.org/"
    clickthrough_text: "EUROBIS"

  - title: The Flemish Research Data Network (FRDN)
    description: "Develops the preconditions necessary to motivate and enable researchers from Flemish research performing organizations to exchange and reuse (FAIR) research (meta)data."
    clickthrough_url: "https://www.frdn.be/"
    clickthrough_text: "Visit FRDN"

  - title: The Blue Cluster
    description: "Promotes cooperation in project operations, research internationalization, events, and representation of VLIZ."
    clickthrough_url: "https://www.blauwecluster.be/"
    clickthrough_text: "Explore Blue Cluster"

  - title: EOSC Association
    description: "Works to advance Open Science for knowledge creation, education, and innovation."
    clickthrough_url: "https://eosc.eu/members/flanders-marine-institute-vliz/"
    clickthrough_text: "View EOSC Profile"

# Featured Data Systems
data_systems:
  - title: World Register of Marine Species (WoRMS)
    description: "Taxonomic database for marine species. +50 installations based on species or geography."
    clickthrough_url: "https://www.marinespecies.org/aphia.php?p=search"
    clickthrough_text: "Visit WoRMS"

  - title: IMIS - Integrated Marine Information System
    description: "Metadata on people, institutes, references, and datasets. +60 installations."
    clickthrough_url: "https://vliz.be/en/imis"
    clickthrough_text: "Access IMIS"

  - title: Photo Gallery
    description: "Image & video collection tied to projects & topics. +100 installations."
    clickthrough_url: "https://images.vliz.be/"
    clickthrough_text: "Browse Gallery"

  - title: IMERS
    description: "Stores measurement data from various marine samples. +10 installations."
    clickthrough_url: "https://vliz.be/vmdcdata/imers/"
    clickthrough_text: "Open IMERS"

  - title: MarinePass
    description: "Central authentication system."
    clickthrough_url: "https://www.marinepass.org/app/login"
    clickthrough_text: "Login"

  - title: Wiki
    description: "Coastal and marine knowledge base. +10 topic-based installs."
    clickthrough_url: "https://www.coastalwiki.org"
    clickthrough_text: "Visit Wiki"

  - title: EMODnet Biology
    description: "Marine biological data portal."
    clickthrough_url: "https://www.emodnet-biology.eu/toolbox/en/download/occurrence/explore"
    clickthrough_text: "Open Data Portal"

  - title: ETN
    description: "European Tracking Network with 800M+ detections."
    clickthrough_url: "https://www.lifewatch.be/etn/"
    clickthrough_text: "Explore ETN"

  - title: LifeWatch Belgium
    description: "Operates research infrastructure: species info, observatory, habitat mapping."
    clickthrough_url: "http://www.lifewatch.be/data-services"
    clickthrough_text: "View Services"

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

  - title: LifeWatch Buoys
    description: "Real-time logger data from marine buoys."
    clickthrough_url: "http://www.lifewatch.be/buoys"
    clickthrough_text: "Buoy Data"

  - title: OBIS Annotated List
    description: "Scientific names from OBIS not matched to WoRMS."
    clickthrough_url: "https://annotated-list.eurobis.org/"
    clickthrough_text: "View Annotated List"

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

{% include item/list/carrousel/waved/main.html
title="Data Systems"
items=page.data_systems %}

<h2>Networks</h2>
{% include item/list/row/text_image/main.html
title="Networks"
items=page.networks %}

