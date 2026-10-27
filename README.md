# GROUP27_DCNs
Scripts used to support quantitative data analysis for ACM GROUP 2027 publication "By the People, for the People: What Two Decentralized Network Communities Reveal about Collective Infrastructure Sovereignty"

## Overview
This script provides functionality for conducting an LDA analysis on posts and apply topic labels to post. This includes model tuning. We create distinct models for Helium and Meshtastic.

It also provides functions for conducting the retention analysis to examine the number of users who are retained day-to-day, month-to-month, and year to year. In the paper, we focus on year-to-year. 

## Data
Following ethical best practices, we do not release data we used in this study as it may conflict with Reddit users' ongoing rights to delete posts that they created. We leveraged the PushPull API to gather all available posts associated with _r/HeliumNetwork_ and _r/Meshtastic_.

Alternatively, interested users could attempt to replicate our study by accessing the ArcticShift project (https://arctic-shift.photon-reddit.com/), with the note that the data is living and dynamic and prone to being deleted by users and moderators. 

For now, we provide a synthetic data set that follows the format and header structure of the data we used in our analysis. 


# Read and Cite the Paper
More details about the decisions undergirding our methodological approach can be found in this paper. 

Morgan Vigil-Hayes and Yuxuan Wang. 2027. By the People, for the People: What Two Decentralized Network Communities Reveal about Collective Infrastructure Sovereignty. Proc. ACM Hum.-Comput. Interact. 11, 1, Article GROUP11 (January 2027), 31 pages. https://doi.org/10.1145/3859397