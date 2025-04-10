---
layout: default
permalink: /about
title: About us
description: "Learn more about the VLIZ Marine Data Centre, where we're making science more efficient, reliable, and transparent. Discover our mission, values, and core principles. Join us in our journey!"
cover: /assets/media/img/datacenter/boat.jpg
cover_url: /about
curly: false
subblocks:
  - title: "Vacatures"
    image: /assets/media/img/datacenter/218 web @Nick Decombel Fotografie.jpg
    clickthrough_url: "https://vliz.be/en/jobs"
  - title: "Other questions?"
    image: /assets/media/img/datacenter/286 web @Nick Decombel Fotografie.jpg
    clickthrough_url: "https://vliz.be/en/contact"
  - title: "About VLIZ data"
    image: /assets/media/img/datacenter/341 web @Nick Decombel Fotografie.jpg
    clickthrough_url: "/history"
---

VLIZ serves as a key national and international hub for high-quality, reliable marine and estuarine data. We offer a wide range of services, technologies, tools, training, and support to scientists, policymakers, the blue economy, and the general public. Our goal is to make data accessible in a user-friendly and open way. Additionally, VLIZ is proudly accredited as an <b>IODE National Oceanographic Data Center</b>.
<br>
{% include item/list/gallery/main.html items=page.subblocks first=false %}


<style>
  .support-contacts {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
    margin-top: 2rem;
  }

  .contact-item {
    background: #fdfdfd;
    padding: 1.5rem;
    border-radius: 12px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
    transition: box-shadow 0.2s ease;
    font-family: 'Sofia Pro', 'Poppins', sans-serif;
  }

  .contact-item:hover {
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.08);
  }

  .contact-item h5 {
    font-size: 1.1rem;
    color: #333;
    margin-bottom: 0.5rem;
    font-weight: 600;
  }

  .contact-item h5 a {
    color: #31b7bc;
    text-decoration: none;
  }

  .contact-item p {
    margin: 0;
    font-size: 0.95rem;
  }

  .contact-item a {
    color: #555;
    text-decoration: none;
    transition: color 0.2s ease;
  }

  .contact-item a:hover {
    color: #31b7bc;
  }

  .contact-header {
    margin-bottom: 1.5rem;
    font-size: 1.25rem;
    font-weight: 600;
    color: #222;
  }
</style>

<!-- Optional title -->
<div class="contact-item">
  <h5>VLIZ Marine Data Centre</h5>
  <p><a href="mailto:vmdc@vliz.be">vmdc@vliz.be</a></p>
</div>

<div class="support-contacts">
  <div class="contact-item">
    <h5>General Support</h5>
    <p><a href="mailto:data@vliz.be">data@vliz.be</a></p>
  </div>

  <div class="contact-item">
    <h5><a href="https://www.marineregions.org/">MarineRegions</a></h5>
    <p><a href="mailto:info@marineregions.org">info@marineregions.org</a></p>
  </div>

  <div class="contact-item">
    <h5><a href="https://www.marinespecies.org/">WoRMs</a></h5>
    <p><a href="mailto:info@marinespecies.org">info@marinespecies.org</a></p>
  </div>

  <div class="contact-item">
    <h5>Library</h5>
    <p><a href="mailto:library@vliz.be">library@vliz.be</a></p>
  </div>

  <div class="contact-item">
    <h5><a href="https://www.scheldemonitor.be/nl">Schelde monitor</a></h5>
    <p><a href="mailto:info@scheldemonitor.org">info@scheldemonitor.org</a></p>
  </div>

  <div class="contact-item">
    <h5><a href="https://www.vliz.be/en/imis">IMIS + MarineInfo</a></h5>
    <p><a href="mailto:imis-support@vliz.be">imis-support@vliz.be</a></p>
  </div>

  <div class="contact-item">
    <h5><a href="https://marinedataarchive.org/">Marine Data Archive (MDA)</a></h5>
    <p><a href="mailto:mda@vliz.be">mda@vliz.be</a></p>
  </div>
</div>
<br>
<br>
<br>
