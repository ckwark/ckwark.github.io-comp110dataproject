---
# Do not edit the text between these lines!
layout: default
---

# COMP110 Focus Track Proposal

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="100"/>

## Summary

**Data:** Data was collected from student surveys from spring 2026 COMP110 sections 001 and 002.

**Goal:** Determine to what extent COMP110 students would benefit from major-specific focus track courses.

**Analysis:** 
1. **Computer Science (CS) Majors/Minors vs Non-CS Majors/Minors:** 
    From the larger dataset, only the "comp_major" responses were considered. There were three possible affirmative responses: "Yes-BA","Yes-BA", and "Yes-Minor." These counts were conglomerated into the broader CS Major/Minor count. Only "No" responses were considered in the Non-CS count. A bar plot was used to visualize the difference in student counts between CS Majors/Minors and Non-CS Majors/Minors.

<img src="static/imgs/cs_in_comp110.png" alt="Bar plot comparison of CS and Non-CS students. "  width="450"/>

2. **COMP110 Course Content Interest: CS vs Non-CS Students:** 
    In addition to the "comp_major" responses, student scores about interest in course content (1 to 7) were considered. Similar to the previous method, the three possible "Yes" responses were considered CS-Major responses. Each student's response was categorized into a Major (orange) or Non-Major (blue) response, and their scores are shown on the x-axis. The responses are shown as a percent of the major affiliation count (percent of CS students scoring 5 vs percent of non-CS students scoring 5) for normalization.

<img src="static/imgs/content_interest" alt="Histogram comparing percents of majors and non-majors interested in COMP110 content. "  width="450"/>