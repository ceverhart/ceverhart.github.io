---
title: Experience
layout: template
filename: experience
description: Experience
---

## Overview of services and experience

__Programming and Automation__

* Leveraging tools already owned by the client/employer or free and open-source tools/modules 
* Development scenarios
  * Projects
  * Single purpose tools
  * Emergency/trouble-shooting (quick turn-around)
* Python programming
  * Tools
    * Jupyter Notebook, Azure Data Studio
    * IDLE (Python)
    * Visual Studio
  * Python Package Index - utilize freely available packages
  * Custom development
 * Development lifecycle tools
  *  Git/GitHub, SVN
  *  Jira, Trello 

__Geospatial__

* Geoprocessing automation 
  * Open source Python modules (laspy, GDAL, OGR, etc.)
  * ArcPy
  * APIs from other commercial or free applications
* GIS desktop applications
  * GUI setup and training
  * QGIS, ArcGIS, others
  * Install and configuration
* Remote sensing (LiDAR)
  * Post-processing pipeline
  * QA/QC - custom QA/QC tools
  * Acquisition tracking and planning using GIS tools
  * LAS format specification
    * Tool development
    * Use in COTS processing software
    * Product development
  * Product generation (DEM, contours, CSV, intensity image)
* Orthophoto/Photogrammetry
    * Orthophoto processing pipeline 
    * Knowledge of photogrammetry principles 

__Web development, web services, and APIs__

* OGC web service types
* Web mapping development (PHP, GeoDjango)
* Leveraging REST APIs and other internet web services

__Database and Data Management__

* SQL development
  * Experience with various DBMS: MS SQL, Oracle, PostgreSQL/PostGIS
  * Tools: SSMS, SQL Developer
  * MS SQL stored procedures, views, functions, and stand-alone queries)
* ETL processes (SSIS, Azure Data Studio)

__Reporting__

* Report development and generation

__R&D and Problem-Solving__

* Learning and integrating new tools and technologies
* Troubleshooting software, data, and workflows
  
__Productivity__

* Confluence/OneNote for notes and tracking projects
* Developed a personal productivity method based on "rule of 3" (3 weekly goals, 3 daily goals)

__General Geography/GIS/Remote sensing knowledge__

* BA in Geography, MEng in GIS
* Coordinate systems, transformations, maps


## Phases of my career - remote sensing and GIS

### Undergraduate

I was pretty lost for the first two years of undergraduate, a biology major that wasn't sure that was the right answer. A geology major friend said that there were interesting things with cameras and mapping in geography. He showed me some pictures in a textbook and even said "remote sensing". After one more frustrating semester in bio classes, I changed my major to geography and took a remote sensing class right off the bat.

### Internship

During my senior year, I got a job with the NYS Dept. of Environmental Conservation. It was an internship supporting a elevation modernization program, converting scanned USGS quadrangle hypsography layers to vector contours. The vector contours were eventually converted to DEM for analysis and archive. At the beginning, it was a lot manual editing, the raster-to-vector conversion worked great for contours that were spaced far apart, but made vector "spider webs" where contours bled together after scanned. After a heads-down period of time doing editing work, i was asked to start setting up the preprocessing (raster-to-vector) - *__my first automation task__*.

### Orthophoto

Freshly graduated, I got my first job and moved out of state. The company was considered to be a large mapping company, and growing rapidly. The job was in the orthophoto production department using their propprietary processing application. The application was pretty tight, pulling together all of the components needed to rectify aerial images into  orthos. When I think back about that experience, it was like they had built an enteprise application for map production, since it did more than just orthophoto production. That experience included some bash scriptiing to automate processing, but the experience taught me a lot about the *__automated data processing pipeline__*.

### LiDAR

I left the big mapping company and joined a small, scrappy company doing aerial photography and orthophotos in order to move to Denver. It was a good experience, but just a stepping stone to the next big phase of my career. My next job was with a small, grassroots LiDAR company - with proprietary processing software and a homegrown LiDAR system. At first, it was a lot of editing - a CAD application would draw contours for the point cloud and we would remove points that appeared to be trees (concentric contours) or buildings (stacked contours). We would talk about how points and lines were burned into our vision, seeing those shapes when we closed our eyes at night. As with my internship, working dilligently on editing paved the way to learn LiDAR processing. Post processing or GPS, IMU, and laser data, sensor calibration, and were mostly separate steps, but provided valuable insight into  the *__LiDAR data processing pipeline__*. It a very challenging, but rewarding experience.

