---
layout: default
permalink: /about
title: About us
description: "Learn more about the VLIZ Marine Data Centre, where we're making science more efficient, reliable, and transparent. Discover our mission, values, and core principles. Join us in our journey!"
cover: \assets\media\img\datacenter\waves.webp
cover_url: /about
curly: false
subblocks:
  - title: "Vacancies "
    image: /assets/media/img/datacenter/218 web @Nick Decombel Fotografie.jpg
    clickthrough_url: "https://vliz.be/en/jobs"
  - title: "Other questions?"
    image: /assets/media/img/datacenter/286 web @Nick Decombel Fotografie.jpg
    clickthrough_url: "https://vliz.be/en/contact"
  - title: "About VLIZ data"
    image: /assets/media/img/datacenter/341 web @Nick Decombel Fotografie.jpg
    clickthrough_url: "/history"
---




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
    background: #fdfdfd; /* Light background for contrast #fdfdfd;*/ 
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
    font-size: 1.4rem;
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
    font-size: 1.15rem;
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
    <h5>Library</h5>
    <p><a href="mailto:library@vliz.be">library@vliz.be</a></p>
  </div>

</div>
<br>
<br>
<br>
