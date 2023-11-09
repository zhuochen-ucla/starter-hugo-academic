---
title: "A New Cosmic Ray Rejection Routine for HST WFC3/UVIS via label-free training of deepCR"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- K. Zhang
- B. Williams 
- M. Durbin 

# Author notes (optional)
author_notes:
- "First author"

date: "2023-11-07T00:00:00Z"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Submitted to *The Astroiphysical Journal*
publication_short: Submitted to *ApJ*

abstract: deepCR is a deep-learning-based cosmic ray (CR) rejection framework originally presented by Zhang & Bloom (2020). The original approach requires a dedicated training set that consists of multiple frames of the same fields, enabling automatic CR labeling through comparison with their median co-adds. Here, we present a novel training approach that circumvents the need for a dedicated training set, but instead utilizes dark frames and the science images requiring CR removal themselves. During training, CRs present in dark frames are added to the science images, which the network is then trained to identify. In turn, the trained deepCR model can then be applied to identify CRs originally present in the science images. Using this approach, we present a new deepCR model trained on a diverse set of Hubble Space Telescope (HST) images taken from resolved galaxies in the local group, which is universally applicable across all WFC3/UVIS filters. We further evaluate the performance of the deepCR model on the Panchromatic Hubble Andromeda Southern Treasury (PHAST) survey and provide insights into how users can robustly determine the threshold for generating binary cosmic-ray masks from deepCR probability map predictions.

# Summary. An optional shortened abstract.
summary: We present a novel deep-learning-based cosmic ray (CR) rejection routine for HST that is applicable across all HST WFC3/UVIS filters. Our label-free training approach circumvents the need for a dedicated training set, but instead utilizes dark frames and the science images requiring CR removal themselves. During training, CRs present in dark frames are added to the science images, which the network is then trained to identify. In turn, the trained deepCR model can then be applied to identify CRs originally present in the science images. (See full abstract in the title link)

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---


