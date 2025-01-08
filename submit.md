---
layout: default
permalink: /submit
title: Submit
description: "Come and submit your data to the VLIZ Marine Data Centre. We offer a range of services to support the FAIR principles of data management. Learn more about our services and how they can help you in your research."
cover: /assets/media/img/datacenter/submit.jpg
curly: false
---

<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #f0f0f0;
        padding: 20px;
        color: #333;
    }

    h4 {
        color: #354d9b; 
        margin-bottom: 10px;
    }

    .button {
        display: inline-flex; 
        align-items: center; 
        padding: 12px 24px;
        margin: 10px 5px; 
        font-size: 18px;
        text-align: center;
        text-decoration: none;
        color: #fff; 
        border: none;
        border-radius: 5px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.15); 
        transition: background-color 0.3s, transform 0.2s;
    }

    .marineinfo-button {
        background-color: #0779bf; 
    }
    .marineinfo-button:hover {
        background-color: #0056b3; 
        color: #fff;
    }
 
    .container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        margin-top: 20px; /_ Added margin for separation _/
    }
    .card {
        flex: 1 1 calc(33% - 20px);
        margin: 10px;
        box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        background: white;
        border-radius: 5px; 
        overflow: hidden; 
    }
    .imgBox img {
        width: 100%;
        height: auto;
    }
    .content {
    padding: 20px; 
    }
    
    @media (max-width: 768px) {
        .card {
            flex: 1 1 calc(50% - 20px); 
        }
    }
    @media (max-width: 480px) {
        .card {
            flex: 1 1 100%; 
        }
    }
</style>
<h4>Submission Options</h4>
<p>At VLIZ, we offer <strong>two</strong> robust options for storing your data:</p>
<ul>
<li><strong>Marine Data Archive (MDA)</strong></li>
<li><strong>MarineInfo</strong></li>
</ul>
<p>Each option serves different purposes, so you can choose the one that best aligns with your data management goals. Read on to explore the features of each.</p>

  <div class="container">
        <div class="card">
            <div class="card-inner">
                <div class="box">
                    <div class="imgBox">
                        <img src="/assets/media/img/datacenter/submit.jpg" alt="Marine Data Archive" width="200" />
                    </div>
                </div>
            </div>
            <div class="content">
                <h3><a href="https://marinedataarchive.org/">Archive</a></h3>
                <br>
                <p>
                    <a href="https://marinedataarchive.org/"><strong>Marine Data Archive</strong></a> or MDA is an online marine repository designed to independently archive data files with comprehensive documentation. Whether you're an individual researcher, part of a consortium, or affiliated with an institute, the MDA offers versatile solutions for managing your data.
                </p>
                <p>Here’s what the MDA can do for you:</p>
                <ul>
                    <li><strong>Data Management:</strong> Organize data files and track versions specific to your projects, reports, analyses, or monitoring campaigns.</li>
                    <li><strong>Personal or Institutional Archiving:</strong> Serve as a reliable backup system for both personal and institutional data.</li>
                    <li><strong>Open Repository:</strong> Facilitate the publication of your data in an accessible manner.</li>
                </ul>
                <p>If you have questions, <a href="mailto:mda@vliz.be">send us an email</a>.</p>
                <a href="https://marinedataarchive.org/mdamanual.pdf" class="button marineinfo-button"><strong>Manual</strong></a>
                <a href="https://marinedataarchive.org/archive.php" class="button marineinfo-button"><strong>Submit</strong></a>
            </div>
        </div>
        <div class="card">
            <div class="card-inner">
                <div class="box">
                    <div class="imgBox">
                        <img src="/assets/media/img/datacenter/submit.jpg" alt="MarineInfo" width="200" />
                    </div>
                </div>
            </div>
            <div class="content">
                <h3><a href="https://marineinfo.org/" mia-extra-properties="nochange">Publish</a></h3>
                <br>
                <p> You can publish your data using IMIS on MarineInfo</p><p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. </p>
                <p>
                <br>
                    <a href="https://marineinfo.org/sites/marineinfo.org/files/managed/imis-data-policy-1.0.pdf" class="button marineinfo-button" mia-extra-properties="nochange"><strong>Data Policy</strong></a>
                    <a href="https://marineinfo.org/submit-form" class="button marineinfo-button" mia-extra-properties="nochange"><strong>Submit</strong></a>
                </p>
            </div>
        </div>
    </div>
