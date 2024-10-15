---
layout: default
graph_logo_bg: true
description: "Discover Open Science at VLIZ, where we're making science more efficient, reliable, and transparent. Learn about our mission, values, and core principles. Join us in our journey!"
cover: /assets/media/img/cover/graph_concept_art.jpg
title: "DATA VLIZ"
subblocks:
  - title: "Data submission"
    description: "Submit your data to the VLIZ Marine Data Centre"
    #image: /assets/media/img/ist/submit.jpg
    clickthrough_url: "/data/submit/"
  - title: "Data inventory"
    description: "Discover the data available in the VLIZ Marine Data Centre"
    #image: /assets/media/img/ist/inventory.jpg
    clickthrough_url: "/data/inventory/"
  - title: "Data resources"
    description: "Explore the resources available in the VLIZ Marine Data Centre"
    #image: /assets/media/img/ist/resources.jpg
    clickthrough_url: "/data/resources/"
special_collections:
  - title: Scheldemonitor
    description: "Een Vlaams-Nederlands kennis- en informatieportaal rond onderzoek en monitoring in het Schelde-estuarium."
    clickthrough_url: "/ask_IT_when_module_made"
    clickthrough_text: "IMIS (not correct)"
  - title: EUROBIS
    description: "the European Node
      of the international Ocean Biodiversity Information System (OBIS) - publishes distribution data on marine species, collected within European marine waters or collected by European researchers"
    clickthrough_url: "/ask_IT_when_module_made"
    clickthrough_text: "IMIS (not correct)"
  - title: Lorem
    description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
    clickthrough_url: "/ask_IT_when_module_made"
    clickthrough_text: "IMIS (not correct)"
  - title: IPSUM
    description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
    clickthrough_url: "/ask_IT_when_module_made"
    clickthrough_text: "IMIS (not correct)"
---

{% include light_bg.html content=
"<h2> Gateway to high-quality, accessible marine and estuarine data, supporting scientific research and informed policy-making hosted by the VLIZ Marine Data Centre</h2>

<p>
  
</p>
"
%}

{% include item/list/block/colored/main.html items=page.subblocks %}

<div class="row">
    <div class="col-md-6">
        <h3>ADD an impressive stat about IMIS (access to over 130,000 unique data sets or something like this)</h3>
        The VLIZ data center is a national and international point of contact for quality and reliable marine and estuarine data. The VLIZ Marine Data Center (VMDC) provides services, technologies, tools, training and support to scientists, policy, blue economy and citizens. Data is made accessible in an efficient and open manner. The VMDC is accredited as an IODE National Oceanographic Data Center.
        <h3>What does VMDC do?</h3>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        <p><a href="/about">Learn more about us</a></p>
    </div>
    <div class="col-md-6">
        <img src="assets/media/img/datacenter/Pain_3.jpg">
        if this image is 2 short you can write some stuff down here or find a rectangular image
    </div>
</div>

{% include item/list/carrousel/block/main.html
    title="special collections"
    items=page.special_collections
%}
