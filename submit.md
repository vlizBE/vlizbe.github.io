---
layout: default
permalink: /submit
title: Submit
description: "Come and submit your data to the VLIZ Marine Data Centre. We offer a range of services to support the FAIR principles of data management. Learn more about our services and how they can help you in your research."
cover: /assets/media/img/datacenter/submit.jpg
curly: false
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Submission Options</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0" />
    <style>
        /* General Body Styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0; /* Light background for better contrast */
            padding: 20px;
            color: #333; /* Dark text for readability */
        }
   /* Section Header Styling */
        h4 {
            color: #354d9b; /* Navy blue color for headers */
            margin-bottom: 10px;
        }
    /* Button Styling */
        .button {
            display: inline-flex; /* Use flexbox for alignment */
            align-items: center; /* Center items vertically */
            padding: 12px 24px;
            margin: 10px 5px; /* Slightly adjust margins */
            font-size: 18px;
            text-align: center;
            text-decoration: none;
            color: #fff; /* White text */
            border: none;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.15); /* Subtle shadow */
            transition: background-color 0.3s, transform 0.2s;
        }
     /* Button Color Variations */
        .mda-button {
            background-color: #4a4a4a; /* Dark gray background */
        }
        .mda-button:hover {
            background-color: #333; /* Darker gray on hover */
        }
  .marineinfo-button {
            background-color: #0779bf; /* Blue background */
        }
        .marineinfo-button:hover {
            background-color: #0056b3; /* Darker blue on hover */
        }
     /* Card Container */
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-top: 20px; /* Added margin for separation */
        }
      .card {
            flex: 1 1 calc(33% - 20px);
            margin: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            background: white; /* White background for cards */
            border-radius: 5px; /* Rounded corners */
            overflow: hidden; /* Ensure images don't overflow */
        }
    .imgBox img {
            width: 100%;
            height: auto;
        }
   .content {
           padding: 20px; /* Add padding to the content area */
        }
  /* Responsive Styles */
        @media (max-width: 768px) {
            .card {
                flex: 1 1 calc(50% - 20px); /* Two cards on smaller screens */
            }
        }
  @media (max-width: 480px) {
            .card {
                flex: 1 1 100%; /* Single card on mobile */
            }
        }
    </style>
</head>
<body>
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
                    <div class="icon">
                        <a href="#" class="iconBox"> 
                            <span class="material-symbols-outlined">arrow_outward</span>
                        </a>
                    </div>
                </div>
            </div>
            <div class="content">
                <h3><a href="https://marinedataarchive.org/">MDA</a></h3>
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
                <a href="https://marinedataarchive.org/mdamanual.pdf" class="button mda-button"><strong>Manual</strong></a>
                <a href="https://marinedataarchive.org/archive.php" class="button mda-button"><strong>Submit</strong></a>
            </div>
        </div>
        <div class="card">
            <div class="card-inner">
                <div class="box">
                    <div class="imgBox">
                        <img src="/assets/media/img/datacenter/queen.jpg" alt="MarineInfo" width="200" />
                    </div>
                    <div class="icon">
                        <a href="#" class="iconBox"> 
                            <span class="material-symbols-outlined">arrow_outward</span>
                        </a>
                    </div>
                </div>
            </div>
            <div class="content">
                <h3><a href="https://marineinfo.org/">MarineInfo</a></h3>
                <br>
                <p>The VLIZ Marine Data Centre is made up of several teams, each with its own focus and expertise. These teams work together to develop and maintain the tools and services that support the FAIR principles of data management.</p>
                <p>MarineInfo is a database to search and store your metadata records, centralising all data regarding the names, education, professional background, publications, projects, and datasets of scientists. This helps VLIZ facilitate scientific research.</p>
                <p>
                <br>
                    <a href="https://marineinfo.org/sites/marineinfo.org/files/managed/imis-data-policy-1.0.pdf" class="button marineinfo-button"><strong>Data Policy</strong></a>
                    <a href="https://marineinfo.org/submit-form" class="button marineinfo-button"><strong>Submit</strong></a>
                </p>
            </div>
        </div>
    </div>
</body>
</html>
