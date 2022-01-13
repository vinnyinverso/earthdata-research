# earthdata-research

## Overview

This repo hosts a site https://vinnyinverso.github.io/earthdata-research/ which showcases analyses performed on a 
corpus of research publications which reference ESODIS datasets.

### article_db
Contains the main listing of all research articles in the corpus, along with the datasets that they reference.

### cluster_totals
Contains aggregate counts of clusters that were obtained by analyzing article abstracts (using BERTopic https://github.com/MaartenGr/BERTopic).

### locations
Contains geocoded locations that were extracted from research articles using spaCy (https://spacy.io/) and OpenStreetMap (https://www.openstreetmap.org).

## Contributions

### Authors
Vincent Inverso (Goddard Space Flight Center)

Christopher Lynnes (Goddard Space Flight Center)

### Data Contributions
Irina Gerasimov and Dave Meyer (GES DISC DAAC)

Wade Albright (Alaska Satellite Facility DAAC) 

Chris Torbert and Danielle Golon (The Land Processes DAAC)

Suresh Vannan and Ed Armstrong (The Physical Oceanography DAAC) 

Bruce Wilson (Oak Ridge National Laboratory DAAC)

### Tools and Sources
The Semantic Scholar Open Research Corpus (https://github.com/allenai/s2orc, DOI=10.18653/v1/2020.acl-main.447)

Astrophysics Data System (https://ui.adsabs.harvard.edu/help/api/)
