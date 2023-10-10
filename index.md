---
layout: homepage
---

## About Me

I am an aspiring astronomer and exoplanet researcher. I graduated with my B.S. in Physics from Georgetown University in 2021, after which I spent a year as a research intern at the Space Telescope Science Institute. I currently work as a data analyst while continuing my research and outreach activities, and I plan to pursue a PhD in astronomy/astrophysics. **I am currently applying for PhD positions during the 2023-2024 application cycle.** My main research interests lie in exoplanet detection and characterization, particularly the search for habitable, Earth-like exoplanets, as well as star and planet formation, the characterization of exoplanet atmospheres, and astrobiology.

When I'm not looking to the stars, I enjoy cooking and baking, reading, making art, traveling, and cuddling with my cat, Missy.

<img src="/assets/img/raspberrypie.jpg" width="200px"><img src="/assets/img/librairie.jpg" width="200px"><img src="/assets/img/missy.jpg" width="200px">

## Research

**Identifying Techniques to Separate Stellar Activity from Planetary Signals:** One of the main methods that researchers use to discover exoplanets is the radial velocity (RV) method, which measures and analyzes the Doppler shifts in stellar spectra caused by a planet "wobbling" its host star. This method has seen vast improvements in recent years, but as instruments near the precision levels needed to detect the small shifts caused by an Earth-like planet orbiting a Sun-like star, the detection of these planets is still limited by stellar activity masquerading as planetary signals in RV measurements.

<figure>
  <img src="/assets/img/rv.gif" width="600px">
  <figcaption>Image credit: Alysa Obertas</figcaption>
</figure>

In my work at the Space Telescope Science Institute, we sought to use machine learning as a tool to predict stellar activity signals from spectral features and distinguish between stellar activity and real planetary signals. Previously, [de Beurs et al.](https://arxiv.org/abs/2011.00003) used a convolutional neural network (CNN) to correlate shape changes in the cross-correlation functions (CCFs) of both simualted stellar spectra and solar spectra from the high-resolution spectrograph HARPS-N with stellar activity and remove those stellar activity signals from the measured RVs. We applied similar techniques to solar and stellar spectra from NEID, another high-resolution spectrograph with a broader wavelength range than HARPS-N. To identify informative inputs and calibrate our predictions for the models, we analyzed NEID data for activity-correlated/sensitive features. During the course of this research, we determined that although machine learning has the potential to be a powerful tool in stellar activity mitigation, further research on the relationships between stellar activity and spectral features is necessary to avoid relying on "black box" models. 

To this end, we investigated a set of NEID spectra of ε Eridani, a young, active K-dwarf star, to probe these relationships. [Wise et al.](https://arxiv.org/abs/1808.09009) previously included ε Eridani in a study that identified a set of activity-sensitive spectral lines. We built upon this work by creating a partially automated method to analyze spectral lines, correlate their features (depth, full width at half maximum, and integrated flux) with known activity indicators, and filter and curate for well-behaved lines whose shape changes are sensitive to certain types of stellar activity. We identified a list of nine lines correlated with the S-index in all three line features, including four newly-identified activity-sensitive lines; as well as additional lines correlated with S-index in at least one feature. These lines, which trace activity periodic at the star's rotational period, can be used as reference points for future work on mitigating stellar activity signals in RV measurements and illustrate the importance of studying the time evolution of line morphologies with stabilized spectrographs, in the overall effort to mitigate activity in the search for small, potentially Earth-like exoplanets.

## Publications

**Jiang, S.**, Roy, A., Halverson, S., et al. Revisitingε Eridani with NEID: Identifying New Activity-Sensitive Lines in a Young
K Dwarf Star. *Submitted to AJ.*

## Outreach and Community Involvement

I enjoy sharing my passion for astronomy through teaching and outreach and I strive to be involved with community collaboration efforts as much as possible. I am particularly passionate about increasing the accessibility of astronomy to underserved communities and students and hope to increase opportunities for students from all backgrounds to become inspired by astronomy. I participate in a number of outreach activities, including but not limited to the following:

**Planet Finder Academy:** The Planet Finder Academy is an outreach program hosted by the California Institute of Technology for Pasadena-area high school students to learn about exoplanets and exoplanet science. Over the course of a one-week summer session in July and additional follow-up sessions during the school year, PFA students learn about the history of exoplanet science, the skills and methods that researchers use to study exoplanets today, and how to become involved with exoplanet research themselves. I am honored to be one of the lead instructors for the Planet Finder Academy. As part of the program's content, I developed Jupyter notebooks and worksheets for students to learn the basics of Python for scientific programming and the RV method for detecting exoplanets which can be found [here](/pfa). I also assist with general day-to-day planning and instruction during the program.

<figure>
  <img src="/assets/img/pfa.jpg" width="600px">
  <figcaption>Photo credit: Scott Phelps</figcaption>
</figure>

You can read more about the Planet Finder Academy [here](https://www.admissions.caltech.edu/explore-more/news/outreach-program-engages-public-high-school-students-in-the-discovery-of-exoplanets), [here](https://www.coloradoboulevard.net/27-pasadena-unified-students-are-planet-finders/), and [here](https://www.coloradoboulevard.net/pasadena-unified-high-schoolers-train-as-planet-finders-at-caltech/).

**EPRV Research Coordination Network:** The [EPRV Research Coordination Network (RCN)](https://exoplanets.nasa.gov/exep/NNExplore/EPRV-RCN/EPRV-RCN-welcome/) is an intiative sponsored by the NASA Exoplanet Exploration Program to facilitate collaboration among RV researchers. As a member of the EPRV RCN, I participate in periodic meetings to help coordinate RV research efforts across the community and I have been fortunate to work with many other members of the EPRV RCN.

In the past, I have also served as the co-president of the [Georgetown University Astronomical Society](https://www.instagram.com/gtown_astro/), as an undergraduate board member of the [Georgetown University Women in Physics](https://physics.georgetown.edu/georgetown-university-women-in-physics-guwip/) (fun fact: I designed the logo!), and a member of the Student Advisory Council for the American Physical Society (APS)'s [Conference for Undergraduate Women in Physics](https://www.aps.org/programs/women/cuwip/index.cfm). I was also a member of the Georgetown University [Physicists Against Racism](https://par.georgetown.domains/) and the Georgetown University [Society of Physics Students](https://sps.georgetown.domains/). I was also an undergraduate teaching assistant for PHYS 101: Principles of Physics I and PHYS 102: Principles of Physics II.
