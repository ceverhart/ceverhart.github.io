---
title: Career Phases
layout: template
filename: career
description: Career Phases
---

## Phases of my career - remote sensing and GIS

### Undergraduate

I was pretty lost for the first two years of undergraduate, a biology major that wasn't sure that was the right answer. A geology major friend said that there were interesting things with cameras and mapping in geography. He showed me some pictures in a textbook and even said "remote sensing". After one more frustrating semester in bio classes, I changed my major to geography and took a remote sensing class right off the bat.

### Internship

During my senior year, I got a job with the NYS Dept. of Environmental Conservation. It was an internship supporting a elevation modernization program, converting scanned USGS quadrangle hypsography layers to vector contours. The vector contours were eventually converted to DEM for analysis and archive. At the beginning, it was a lot manual editing, the raster-to-vector conversion worked great for contours that were spaced far apart, but made vector "spider webs" where contours bled together after scanned. After a heads-down period of time doing editing work, i was asked to start setting up the preprocessing (raster-to-vector) - *__my first automation task__*.

### Orthophoto

Freshly graduated, I got my first job and moved out of state. The company was considered to be a large mapping company, and growing rapidly. The job was in the orthophoto production department using their propprietary processing application. The application was pretty tight, pulling together all of the components needed to rectify aerial images into  orthos. When I think back about that experience, it was like they had built an enteprise application for map production, since it did more than just orthophoto production. That experience included some bash scriptiing to automate processing, but the experience taught me a lot about the *__automated data processing pipeline__*.

### LiDAR, beginning

I left the big mapping company and joined a small, scrappy company doing aerial photography and orthophotos in order to move to Denver. It was a good experience, but just a stepping stone to the next big phase of my career. My next job was with a small, grassroots LiDAR company - with proprietary processing software and a homegrown LiDAR system. At first, it was a lot of editing - a CAD application would draw contours for the point cloud and we would remove points that appeared to be trees (concentric contours) or buildings (stacked contours). We would talk about how points and lines were burned into our vision, seeing those shapes when we closed our eyes at night. As with my internship, working dilligently on editing paved the way to learn LiDAR processing. Post processing of GPS, IMU, and laser data, sensor calibration, and were mostly separate steps, but provided valuable insight into  the *__LiDAR data processing pipeline__*. It a very challenging, but rewarding experience.

The small company mnetioned above went through some ups and down thorugh the years, and eventually merged with another company. That's not to say that the new company was big, but it did bring opportunities to learn new software. The new company used commercial processing software for post-processing and calibration, but had proprietary software for filtering and tracking editing. It was a pretty clunky solution, but the original developers were proud of it. That made me start thinking about how I would do it differently.

####  Masters of Engineering in GIS
During the time I was at the merged company, I started a masters program at the University of Colorado at Denver. Getting a masters degree was a goal and dream of mine since undergrad senior year. I looked at several programs at the local colleges and univertities, but wasn't interested in the academic focused Geography degrees or even the technical degrees outside GIS and remote sensing. The program at CU Denver was exactly what I was looking for, a curriculum focused on the technology for the geospatial professional. I came away from that with a well-rounded knowledge of geospatial technologies.

### LiDAR and GIS, bigger opportunity
As I was finishing my masters program, I got a call from an colleague who was hiring "project coordinators" for a growing LiDAR processing department. The role would be provide technical leadership and coordinate work on projects, including tracking all phases of LiDAR production. It also gave me a chance to mentor some really great people, which made me feel like the time I had spent learning well worth it and very rewarding. This company had purchased their sensors and was using commercial processing software for LiDAR post-processing. That gave me a chance to learn the commercial software using the knowledge I had gained from working with proprietary software. There were sonme features that the commercial software didn't have, so the department director assigned me a project early in my time there - build an ArcGIS extension to track acquisition, processing, and editing. 

Building that ArcGIS LiDAR tracking extension was a transition to developing and using GIS for mapping production work. The tracking extension was a success, and it was used for a couple of years. There were also other ways to apply GIS to aerial mapping and I embraced those opportunities. Processing breaklines, automating raster and vector product generation, and LiDAR dataset QC tools. It was also during this time that I started making use of the LAS header. The LAS specification was very straightforward and alllowed me to get more from our LiDAR datasets. One of my favorite tools came out of that time - LAS bounding box to shapefile.

After a few years, I left that company to become a developer for a LiDAR software startup. The objective of that new job was to build an ArcGIS extension for their LiDAR processing software. I did build that extension, but the company was not successful and I ended up at the company (from the last two paragraphs). I returned to that company as a technical lead, picking up much of the GIS work that I had done on the first round.

### Enterprise Applications


__...to be continued__
