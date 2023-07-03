---
title: "Using Probabilistic Movement Primitives in Analyzing Human Motion Differences Under Transcranial Current Stimulation"
authors:
- admin
- Rebecca Herzog
- Till M Berger
- Tobias Bäumer
- Anne Weissbach
- Elmar Rueckert
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-08-19T00:00:00Z"
doi: "https://doi.org/10.3389/frobt.2021.721890"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Frontiers in Robotics and AI, 8*"
publication_short: "Front. Robot. AI"

abstract: In medical tasks such as human motion analysis, computer-aided auxiliary systems have become the preferred choice for human experts for their high efficiency. However, conventional approaches are typically based on user-defined features such as movement onset times, peak velocities, motion vectors, or frequency domain analyses. Such approaches entail careful data post-processing or specific domain knowledge to achieve a meaningful feature extraction. Besides, they are prone to noise and the manual-defined features could hardly be re-used for other analyses. In this paper, we proposed probabilistic movement primitives (ProMPs), a widely-used approach in robot skill learning, to model human motions. The benefit of ProMPs is that the features are directly learned from the data and ProMPs can capture important features describing the trajectory shape, which can easily be extended to other tasks. Distinct from previous research, where classification tasks are mostly investigated, we applied ProMPs together with a variant of Kullback-Leibler (KL) divergence to quantify the effect of different transcranial current stimulation methods on human motions. We presented an initial result with 10 participants. The results validate ProMPs as a robust and effective feature extractor for human motions.
# Summary. An optional shortened abstract.
summary: In medical tasks such as human motion analysis, computer-aided auxiliary systems have become the preferred choice for human experts for their high efficiency. However, conventional approaches are typically based on user-defined features such as movement onset times, peak velocities, motion vectors, or frequency domain analyses ...
tags:
- Probabilistic Machine Learning

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.frontiersin.org/articles/10.3389/frobt.2021.721890/full
#url_code: 'https://github.com/ai-lab-science/Deep-Reinforcement-Learning-for-mapless-navigation-in-intralogistics'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: 'https://www.youtube.com/watch?v=HxvhiLem2XU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

#{{% callout note %}}
#Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}
#
#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the example.
#{{% /callout %}}
#
#Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
