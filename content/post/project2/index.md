---
title: Reconstruction of the star formation history of the NSC
#subtitle: Supermassive black hole

# Summary for listings and search engines
summary: As the closest galactic nucleus, Milky Way's Nuclear Star Cluster (NSC) provides a unique opportunity to resolve the stellar population and to study its composition and star formation in this extreme environment. The limitation in our current understanding of the NSC star formation history is that previous studies assumed that all stars have solar metallicity due to limited observed samples. However, age and metallicity are degenerate parameters in star formation histories; by ignoring the effect of metallicities, the age estimates can be biased. Recent spectroscopic surveys showed a significant spread in the metallicity of stars in the NSC, which motivates us to revisit the star formation history and its implications on the formation and evolution of the NSC. Here we present the star formation history of the NSC for the first time with metallicity constraints as obtained from large sample of stellar metallicity measurements from Keck, Gemini and VLT. In addition, we model the initial mass function for the first time simultaneously, and present more accurate estimates on the number of compact objects at the Galactic center. 

# Link this post with a project
projects: []

# Date published
date: "2021-08-09T00:00:00Z"

# Date updated
lastmod: "2021-08-09T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: The Milky Way galaxy hosts a supermassive black hole (named as Sgr A*, shown in the inset on the right), embedded in the Nuclear Star Cluster at the center, highlighted and enlarged in the middle panel. The supermassive black hole at the Milky Way Galactic Center is the only one where we can observe individual stars to study their formation and interactions.
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

tags:
- Academic

#categories:
#- Demo
#- 教程
---

As the closest galactic nucleus, the center of the Milky Way galaxy provides a distinct opportunity for studying phenomena and physical processes which may be happening in many other galactic nuclei. The innermost region of most galaxies is occupied by spectacularly dense and massive assemblies of stars, which forms the nuclear star cluster. The star formation in this extreme environment is believed to be affected by the central supermassive black hole, but the physical mechanisms behind are not entirely known. The Milky Way Galactic Center is the only place where we can observe in detail how the black hole affects the star formation in its vicinity.

This project furthers the star formation history study of the nuclear star cluster at the Galactic Center for the first time with new measurements of metal abundances for stars in this region. Age and metal abundances introduce some degeneracy in modeling the star formation history because stars with higher metal abundances or older ages both show lower brightness and surface temperature. The limitation of current star formation history analysis is that all previous studies have assumed a solar metal abundances for all stars due to limited observed samples, which would lead to large systematic errors in estimating the cluster age. 

{{< figure src="dege.jpg" title="Data comparison" caption="Figure 2: H-R diagram with MIST isochrones for ages 3 Gyr (’dashed’) and 10 Gyr (’solid’) with colors showing the different metallicities. There is a strong degeneracy between the age and metallicity for modelling the cluster population. Generally, the stellar population with lower temperature and fainter brightness can be interpreted as either old or high metallicity." width="100%" height="auto">}}

**Three proposed datasets:** 1) 83 late-type stars from the Gemini Near Infrared Integral Field Spectrograph survey (Do et al. 2015); 2) 687 late-type stars and 114 early-type stars from VLT KMOS Integral Field Spectrograph survey (Feldmeier-Krause et al. 2017); 3) 126 early-type stars from the Keck Galactic Center OSIRIS Wide-field Survey (GCOWS, Chu et al., in prep).

**Methodology:** We apply forward modeling and Bayesian framework to derive cluster physical properties by comparing observations to a synthetic cluster (**Figure 3**). The observable features include stellar brightness, surface temperature, number of cluster members, and metallicity (metal abundances). The big contribution is to probe how metallicity affects stellar properties and breaks the degeneracy between stellar age and metallicity, and to predict a more convincing cluster age. We consider several star formation history model candidates: 1) One ancient single burst; 2) A constant star formation with linear/exponential rate; 3) Multiple bursts.

{{< figure src="model.jpg" title="Data comparison" caption="Figure 3: Diagram of generation of a synthetic normalized cluster with observational and completeness correction. " width="100%" height="auto">}}

This project will also model the initial mass function for the first time simultaneously, and present more accurate estimates on the number of compact objects at the Galactic center. This will result in the most accurate predictions so far of the rate of mergers of stellar-mass black holes and neutron stars, which is important for locating and interpreting gravitational-wave detections like those from laser interferometers like LIGO. See **Figure 4**. 


{{< figure src="gw_pred.jpg" title="Data comparison" caption="Figure 4: From Hosek et al. 2020. Left: Predicted number of compact objects generated by NSC after 10 Gyr assuming a top-heavy IMF (red, α = 1.7, Lu et al. 2013) and standard Kroupa IMF (blue). Top-heavy IMF produces ∼ 3.3 times more BH and ∼ 2.1 times more NS. Right: Predicted BH-BH merger rates within 0.4 pc of NSC with given BH radial profiles and BH-BH binary merger fractions. A top-heavy IMF can produce BH-BH mergers with a rate up to ∼ 7 times higher. " width="100%" height="auto">}}
