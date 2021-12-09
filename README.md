## Final Project Proposal: Crevasses on George VI Ice Shelf
Emily Glazer

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pangeo-data/pangeo-docker-images/2021.09.30?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fecglazer%252Frces_final_project%26urlpath%3Dtree%252Frces_final_project%252Ffinal_project.ipynb%26branch%3Dmain)

#### Scientific question:

In this project, I would like to investigate crevasses in the George VI ice shelf (GVIIS), one of the fastest melting ice shelves on the Antarctic Peninsula. More specifically, I plan to look at the relationship between basal crevasses and ice surface crevasses.

My goal will be to answer the question: What is the relationship between the locations of basal crevasses and surface crevasses on GVIIS?

#### Links to relevant datasets:

- Radar data to examine basal crevasses: [CReSIS: Center for Remote Sensing of Ice Sheets](https://data.cresis.ku.edu/)
- Satellite data to examine surface crevasses: [REMA: Reference Elevation Model of Antarctica](https://www.pgc.umn.edu/data/rema/)


#### Summary of analysis:

I plan to read in CReSIS radar data and REMA surface elevation data over GVIIS into Python XArray datasets. I will then process the radar data and extract the elevation profiles over the radar flight paths so that I can juxtapose the surface profiles and basal radar echograms along 4 different 50-km flight trajectories. I will examine the side-by-side profiles to see if there is a relationship worth further investigation between the locations of surface and basal features.
