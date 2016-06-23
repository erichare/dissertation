# My Dissertation

My dissertation for a PhD in Statistics (Co-Major in Computer Science) at Iowa State University

## Title

Enabling Scientists to Understand Their Data using Web-based Statistical Tools.

## Outline

1. Automatic Matching of Bullet Lands
2. Introducing Statistics with intRo (or bullets follow-up paper)
3. A Web Framework for Rapid Deployment of Visual Inference Studies

## Proposal (Containing Lit Review)

My proposal to the committee of what im going to do (15 pages):

Roughly 12 pages other people's work, 3 pages what i will do.

1. Review literature (show that we know the literature and what I'm talking about)
2. Point out where literature is inadequate
    a. Working between statistics and computer science - All the tools we would use. Focus on the things that go beyond Shiny, but may be generalizable - Things that I see myself doing with every one of the applications. Show that i can adapt and create something new. biology, stats ed, forensics science
    b. The statistics itself - Bullets, composition of a lot of smaller data analysis self. Outline each step, and talk about transparency of the process and getting things online (x3prplus, x3p files). This needs to be a pretty major cultural shift - No more black boxes.
    c. The computer science itself - Interface design. Read "The Design of Everyday Things"
3. Cover bullets and visual inference literature (about 10 papers for visual inference total)

Read through literature with 2009 report in mind (Careful with how we cite Bachrach - Say it is stated in this paper, not that it has been shown)
    
## TODO

1. Read https://www.researchgate.net/publication/241780159_Development_of_ballistics_identification-from_image_comparison_to_topography_measurement_in_surface_metrology
2. Put some kind of marker/tags for things to have Heike look at.
3. Read through full bullet paper (check reference list to make sure all are included)
4. DONE Update instructions on x3prplus for new database
5. For degraded paper, check through literature with regards to stats (CMS in particular). Identify the features, program the features. Bring alan on board. Use each feature independently as predicting matching. Stress the algorithm by using different amounts of degradation, see how it changes.
6. DONE Update CV

## NIST Notes

AFTE Journals (get as much as i can)
Get involved with second paper (degraded bullets, assessing matches of)
  Hopefully full access to database
Exposure/intro to the microscope
  Rescan a few hamby ones?
Talk about algorithms with them
  Implement in R?
Give access to shiny matching (maybe on server, or alen's computer)

Database Access - Make informed setup for ISU site database

1. Database (Implementation Side)
  a. Couple hours with Alan
  b. Backend + Setup
2. Degraded Bullets (Research Side)
  a. Access to literature on this
  b. State of the art (exposure to research)
  c. Get technical reports
  d. Think about what a degraded bullet looks like

Write those two up as items (Write a half page proposal, paragraph for each of the two)
"These are the two things we hope to do. We hope in a week we can resolve..."

Future Research

ALWAYS Look at NIST Publications and explain how we're going further
Look at NIST Publications page, figure out how to use

1) Degraded bullets
2) 3D computer based utility
3) Full surface signatures
4) Explore use of width and angle of striae at different depths and heights

1) While our current automated matching algorithm appears to perform well with full bullet scans, matching degraded bullets presents a new set of technical challenges. Features will need to be derived which take into account the length of the recovered fragments (For instance, CMS per micrometer). Aligning two bullet signatures will be more challenging if the signatures happen to be wildly varying lengths. We hope to provide a quantitative assessment of the power of our algorithm as a function of the degradation of the bullet.
2) The 3D computer based microscope and analysis utility will allow researchers to upload two .x3p files representing individual bullet lands. A fully interactive viewer will allow the surfaces to be rotated, panned, zoomed, and aligned. Lighting parameters can be fully adjusted. Finally, an interface to the automatic bullet matching algorithm will be provided, which will allow a quantitative assessment of the probability that the two lands match.
3) Currently, our algorithm operates by extracting a 1-dimensional signature at a particular height of the bullet. We hope to improve on this by instead extracting full surface signatures, in two dimensions. To do this, we must identify the stable region of the bullet, and re-derive features such that striae can be described as multi-dimensional features. This should also make the algorithm more robust to degradation, as the degraded regions may not always be parallel to the coordinate system from which a 1-dimensional signature is currently being extracted.
4) We can derive several more properties of particular striae that may aid in terms of matching bullets. In particular, the width of the striae could be important. Currently, we are identifying the "peak" of the striae, and using this to determine its location in the signature as a single point - Thus, we only extract the height of the striae and not the width. Finally, the angle of the striation could also indicate information pertinent to matching.

Meeting with Bill Eddy
Slides from Xiao Hui's Talk - John Song was interested. Collaborate with him directly.
Look at NIST Template for Proposals
Iowa Crime Lab - Give talk about bullet matching
