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
data_systems:
  - title: Aphia
    description: "Main: www.marinespecies.org What: Taxonomic database (taxon names, distributions, specimens, ...) +50 installations based on species or geographical context"
    image_url: "/assets/media/img/content/ogclogo.png" #LOGO NOT APPEARING, WOULD BE NICE TO SHOW THE LOGO 
    image_alt: "OGC logo"
    clickthrough_url: "www.marinespecies.org"
    clickthrough_text: "Visit OGC"
  - title: IMIS
    description: "Main: vliz.be/imis
What: Metadata on Persons/Institutes/References/Datasets/... describing the marine landscape)
+60 installations based on projects, topics or institutes
Output framework: PHP"
    clickthrough_url: "https://vliz.be/en/imis"
    clickthrough_text: "IMIS (not correct)" 
  - title: Photogallery
    description: "Main: images.vliz.be
What: photo and multimedia gallery
+100 installations based on projects, topics or institutes
Output framework: PHP."
    clickthrough_url: "https://images.vliz.be/"
    clickthrough_text: "https://www.ogc.org/"
  - title: IMERS
    description: "Main: vliz.be/vmdcdata/imers What: Integrated Marine Environmental Readings & Samples +10 installations based on projects Output framework: PHP"
    clickthrough_url: "https://vliz.be/vmdcdata/imers/"
    clickthrough_text: "https://www.ogc.org/"
  - title: MarinePass
    description: "+30 installations What: central authentication system Output framework: PHP Input framework: PHP, MS Access"
    clickthrough_url: "https://eosc.eu/members/flanders-marine-institute-vliz/"
    clickthrough_text: "https://www.ogc.org/"
  - title: Wiki
    description: "Main: www.coastalwiki.org What: own, closed wikipedia installation +10 installations based on topic or project Integration via: web scraper"
    clickthrough_url: "www.coastalwiki.org"
    clickthrough_text: "https://www.ogc.org/"
 - title: Drupal (version 7 + 9)
    description: "Main: vliz.be What Content Management System (CMS) +50 websites based on projects or institutes Input framework: PHP Output framework: PHP Integration of other VLIZ data systems via module"
    clickthrough_url: "www.coastalwiki.org"
    clickthrough_text: "https://www.ogc.org/"
---

{% include item/list/carrousel/waved/main.html
    title="Networks"
    items=page.networks
%}

{% include item/list/card/colored/main.html
    title="Data Systems"
    items=page.data_systems
%}

{% include item/list/block/colored/main.html
    title="Networks"
    items=page.networks
%}

{% include item/list/row/text_image/main.html
    title="Networks"
    items=page.networks
%}

{% include item/list/carrousel/block/main.html
    title="Data systems"
    items=page.data_systems
%}

