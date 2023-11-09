---
title: A New Cosmic Ray Rejection Routine for HST WFC3/UVIS via label-free training of deepCR
#subtitle: Supermassive black hole

# Summary for listings and search engines

summary: deepCR is a deep-learning-based cosmic ray (CR) rejection framework originally presented by Zhang & Bloom (2020). The original approach requires a dedicated training set that consists of multiple frames of the same fields, enabling automatic CR labeling through comparison with their median co-adds. Here, we present a novel training approach that circumvents the need for a dedicated training set, but instead utilizes dark frames and the science images requiring CR removal themselves. During training, CRs present in dark frames are added to the science images, which the network is then trained to identify. In turn, the trained deepCR model can then be applied to identify CRs originally present in the science images. Using this approach, we present a new deepCR model trained on a diverse set of Hubble Space Telescope (HST) images taken from resolved galaxies in the local group, which is universally applicable across all WFC3/UVIS filters. We further evaluate the performance of the deepCR model on the Panchromatic Hubble Andromeda Southern Treasury (PHAST) survey and provide insights into how users can robustly determine the threshold for generating binary cosmic-ray masks from deepCR probability map predictions. This work has been submitted to ApJS. 
# Link this post with a project
projects: []

# Date published
date: "2023-10-08T00:00:00Z"

# Date updated
lastmod: "2023-10-08T00:00:00Z"

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

  
{{< figure src="cr_fig1.jpg" title="comparison" caption="Figure 1: Top left: WFC3/UVIS calibrated dark frame (HST:16568). Top right: WFC3/UVIS image in F336W of M31 (HST:16801). Bottom left: The result of adding the dark frame to the raw image. Bottom right: The same image with all CRs removed by deepCR, including both from the raw image and dark frame. Masked pixel values are filled with a 3 × 3 median filter." width="100%" height="auto" >}}

<div style="text-align: justify">
	
deepCR is a deep-learning-based cosmic ray (CR) rejection framework originally presented by Zhang & Bloom (2020). The original approach requires a dedicated training set that consists of multiple frames of the same fields, enabling automatic CR labeling through comparison with their median co-adds. Here, we present a novel training approach that circumvents the need for a dedicated training set, but instead utilizes dark frames and the science images requiring CR removal themselves. During training, CRs present in dark frames are added to the science images, which the network is then trained to identify. In turn, the trained deepCR model can then be applied to identify CRs originally present in the science images. Using this approach, we present a new deepCR model trained on a diverse set of Hubble Space Telescope (HST) images taken from resolved galaxies in the local group, which is universally applicable across all WFC3/UVIS filters. 

</div>

{{< figure src="cr_fig2.jpg" title="phasttest" caption="Figure 2: Top left: Fraction of total number of GST stars from one example HST visit as applied with different deepCR masking thresholds compared to the legacy mode. The resulting number of GST stars drops quickly below the threshold of 0.1. Top right: Fraction of GST stars that are added or lost with different deepCR masking thresholds, respectively, which together construct the overall curve on the left figure. Bottom left: UV GST CMD. The red box marks the CMD features of the most importance. Bottom right: Fraction of GST stars that are added or lost within the CMD featured box as a function of deepCR masking thresholds. Dashed lines represent the results when the featured box is dithered to avoid selection edge effects. deepCR masking keeps adding more GST stars within the CMD featured region until the threshold is around 0.08, while the masking starts to lose featured stars prominently below the threshold of 0.1." width="100%" height="auto">}}
