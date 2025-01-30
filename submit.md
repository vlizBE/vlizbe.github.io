---
layout: default
permalink: /submit
title: Submit data
description: "Come and submit your data to the VLIZ Marine Data Centre. We offer a range of services to support the FAIR principles of data management. Learn more about our services and how they can help you in your research."
cover: /assets/media/img/datacenter/submit.jpg
curly: false
---

<style>
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

  <div class="container">
        <div class="card">
            <div class="card-inner">
                <div class="box">
                    <div class="imgBox">
                        <img src="/assets/media/img/content/logo_mda2.png" alt="Marine Data Archive" width="200" />
                    </div>
                </div>
            </div>
            <div class="content">
                <h3><a href="https://marinedataarchive.org/">Archive</a></h3>
                <br>
                <p>
                    <a href="https://marinedataarchive.org/"><strong>Marine Data Archive</strong></a> or MDA is an online marine repository designed to independently archive data files with comprehensive documentation. Whether you're an individual researcher, part of a consortium, or affiliated with an institute, the MDA offers versatile solutions for managing your data.
                </p>
                <ul>
                    <li><strong>Data Management:</strong> Organize data files and track versions specific to your projects, reports, analyses, or monitoring campaigns.</li>
                    <li><strong>Personal or Institutional Archiving:</strong> Serve as a reliable backup system for both personal and institutional data.</li>
                    <li><strong>Open Repository:</strong> Facilitate the publication of your data in an accessible manner.</li>
                </ul>
                <p>If you have questions, <a href="mailto:mda@vliz.be">send us an email</a>.</p>
                <a href="https://marinedataarchive.org/archive.php" class="button marineinfo-button"><strong>Archive</strong></a>
                <a href="https://marinedataarchive.org/mdamanual.pdf" class="button marineinfo-button"><strong>Manual</strong></a>
            </div>
        </div>
        <div class="card">
            <div class="card-inner">
                <div class="box">
                    <div class="imgBox">
                        <img src="/assets/media/img/content/marineinfo_logo.png" alt="MarineInfo" width="200" />
                    </div>
                </div>
            </div>
            <div class="content">
                <h3><a href="https://marineinfo.org/" mia-extra-properties="nochange">Publish</a></h3>
                <br>
                <p> You can publish your data using IMIS on MarineInfo</p><p>
                Dive into an ocean of knowledge with our new linked open data catalogue - discover, connect and explore the vast network of marine data like never before!
                </p>
                <p>
                <br>
                    <a href="https://marineinfo.org/metasubmit/" class="button marineinfo-button" mia-extra-properties="nochange"><strong>Submit</strong></a>
                </p>
            </div>
        </div>
    </div>
