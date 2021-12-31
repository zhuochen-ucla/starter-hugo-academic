---
title: A New Window on Star Formation History of the NSC at the Galactic Center
#subtitle: Supermassive black hole

# Summary for listings and search engines

summary: As the closest galactic nucleus, Milky Way's Nuclear Star Cluster (NSC) provides a unique opportunity to resolve the stellar population and to study its composition and star formation in this extreme environment. The limitation in our current understanding of the NSC star formation history is that previous studies assumed that all stars have solar metallicity. However, age and metallicity are degenerate parameters in star formation histories; by ignoring the effect of metallicities, the age estimates can be biased. Recent spectroscopic surveys showed a significant spread in the metallicity of stars in the NSC, which motivates us to revisit the star formation history and its implications on the formation and evolution of the NSC. In this talk I will present the star formation history of the NSC for the first time with metallicity constraints as obtained from large sample of stellar metallicity measurements from Keck, Gemini and VLT. The analysis shows significantly different star formation history than any previously published works. In addition, we model the initial mass function for the first time simultaneously, and present more accurate estimates on the number of compact objects at the Galactic center. 

# Link this post with a project
projects: []

# Date published
date: "2021-08-09T00:00:00Z"

# Date updated
lastmod: "2021-08-09T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: true

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: The Milky Way galaxy hosts a supermassive black hole (named as Sgr A*, shown in the inset on the right), embedded in the Nuclear Star Cluster at the center, highlighted and enlarged in the middle panel. The supermassive black hole at the Milky Way Galactic Center is the only one where we can observe individual stars to study their formation and interactions.
  focal_point: ""
  placement: 3
  preview_only: true

authors:
- admin

tags:
- Academic

#categories:
#- Demo
#- 教程
---

  
{{< figure src="nsc_f1.jpg" title="NSC" caption="Figure 1: The Milky Way galaxy hosts a supermassive black hole (named as Sgr A*, shown in the inset on the right), embedded in the Nuclear Star Cluster (NSC) at the center, highlighted and enlarged in the middle panel. The supermassive black hole at the Milky Way Galactic Center is the only one where we can observe individual stars to study their formation and interactions. " width="100%" height="auto" >}}

<div style="text-align: justify">
	
Given its proximity, the Milky Way Galactic Center provides a valuable opportunity for studying phenomena and physical processes which may be happening in many other galactic nuclei. The innermost region of most galaxies is occupied by a spectacularly dense and massive assembly of stars, which forms the nuclear star cluster (NSC, **Figure 1**). The star formation in this region is believed to be affected by the central SMBH, but the physical mechanisms behind it are not entirely known. The Galactic Center provides a unique opportunity to resolve the stellar population and to study its composition and star formation, and also allows us to predict the number of compact objects. 

The limitation in our current understanding of the NSC star formation history is that previous studies assumed that all stars have solar metallicity. However, age and metallicity are degenerate parameters in star formation histories (**Figure 2**); by ignoring the effect of metallicities, the age estimates can be biased. ​​Recent spectroscopic surveys showed a significant spread in the metallicity of stars in NSC, which motivates us to revisit the star formation history and its implications on NSC’s formation and evolution.
</div>

{{< figure src="dege.jpg" title="Degeneracy" caption="Figure 2: H-R diagram with MIST isochrones for ages 3 Gyr (’dashed’) and 10 Gyr (’solid’) with colors showing the different metallicities. There is a strong degeneracy between the age and metallicity for modelling the cluster population. Generally, the stellar population with lower temperature and fainter brightness can be interpreted as either old or high metallicity." width="80%" height="auto">}}

<div style="text-align: justify">
	
In this project, I present NSC’s star formation history for the first time with metallicity constraints as obtained from a large sample of stellar metallicity measurements from Keck, Gemini and VLT. I developed a Bayesian inference methodology to derive NSC’s star formation history and global properties from photometry and spectroscopy of 770 late-type stars. I apply a forward-modeling approach and a Bayesian framework to derive properties using simulations of synthetic clusters while accounting for observational uncertainties, completeness, degeneracies between properties and stellar multiplicity. **I have successfully established a 3-d cluster modeling tool (Chen et al., in prep), that for the first time includes measurements of K luminosity, colors, effective temperature (Teff) and metallicity**. This tool improves the constraints on NSC’s age, metallicity distribution and initial mass function (IMF). I contributed to the open source Python package SPISEA (Hosek et al. 2020) with metallicity interpolation in generating clusters, and the first function of star formation history modeling.
</div>

{{< figure src="Hess_Do.png" title="Hess" caption="Figure 3: Hess diagrams of model-predicted clusters, overplotted with Do et al. (2015) dataset. Right panel: Low-temperature stars are able to be well fitted for the first time in this work. The observed dataset containing late-type stars is characterized by the modeled two bursts of star formation events. Bulk stellar mass (~ 90%) is older and metal-rich (bright strip in Right panel). The second burst (~ 10% of stellar mass) is younger and metal-poor (top left in Right panel). " width="100%" height="auto">}}

<div style="text-align: justify">

**RESULTS**: Roughly 90% of the stellar mass formed ~3.6 Gyr ago and is metal-rich (metallicity [Fe/H]=0.45), while the remaining 10% stellar mass formed ~0.6 Gyr ago and is metal-poor ([Fe/H]= -1.05). See **Figure 3**. The star formation history of the NSC favors a canonical IMF (Salpeter 1955) for late-type stars. Previous studies, assuming a solar metallicity for all stars, reported that ~80% of stellar masses formed more than 5 Gyr ago (Pfuhl et al. 2011). I performed a cluster modeling with fixed solar metallicity and the results yield an age of 7.1 Gyr. If the cluster is assumed to be solar metallicity, the age of the cluster would increase by a factor of two **(Figure 4)**. By including metallicity as a parameter, our models are able to account for stars that were previously difficult to fit, such as low-temperature red giants. 
</div>

{{< figure src="agefehfit.jpg" title="prob_comp" caption="Figure 4: 1D posterior probability density functions for fittings on the age and metallicity of the ancient burst (bulk mass). Top panels: With the cluster metallicity being constrained from stellar metallicity measurements, the bulk stellar mass was modeled to be 3.6 Gyr with [Fe/H]=0.45. Bottom panels: Fixed solar metallicity modeling yields an age of 7.1 Gyr, which is twice as old. The NSC is modeled to be half as young (~ 3 Gyr younger) if including metallicity constraints. " width="80%" height="auto">}}

<div style="text-align: justify">
	
Our reported younger age would challenge the mutual evolution of the NSC, the SMBH and the bulge (e.g., Graham & Spitler 2009), and may also challenge the formation scenario of infalling globular clusters (e.g., Gerhard 2001; Paumard et al. 2006) due to insufficient accumulation time. 

This work contributes to the most accurate predictions of the number of compact objects at the Galactic Center, and the rate at which they merge, releasing gravitational waves detectable by laser interferometers such as LIGO (e.g., Petrovich & Antonini 2017; Hoang et al. 2018). Of particular note: the predicted number of neutron stars, when metallicity measurements are included, decreases significantly (by a factor of 3) compared to earlier predictions, based on the assumption of solar metallicity **(Figure 5)**. This reduces the so-called “missing pulsar problem” (e.g., Johnston et al. 1995; Bates et al. 2011; Torne et al. 2021) and presents a more accurate description of the compact remnant population at the Galactic Center.  
</div>

{{< figure src="numcomp.jpg" title="numcomp" caption="Figure 5: IMF and metallicity are crucial cluster properties to measure for predicting the number of compact objects and their gravitational wave merger rates at the Galactic Center. High metallicity of the NSC, modeled in this project ([Fe/H]=0.5, **Chen et al., in prep**, yellow), predicts 3× fewer neutron stars (Left). A top-heavy IMF (α=1.7, Lu et al. 2013, red) predicts ~ 3× more black holes, 2× more neutron stars (right) than that with a canonical IMF **(Chen et al., in prep)**." width="90%" height="auto">}}

