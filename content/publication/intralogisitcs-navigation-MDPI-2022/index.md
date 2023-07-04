---
title: "Using Deep Reinforcement Learning with Automatic Curriculum Learning for Mapless Navigation in Intralogistics"
authors:
- admin
- Benedikt Hein
- Mohamed Bakr
- Georg Schildbach
- Bengt Abel
- Elmar Rueckert
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2022-03-19T00:00:00Z"
doi: "https://doi.org/10.3390/app12063153"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Applied Sciences, 12*(6), Special Issue: Intelligent Robotics"
publication_short: "Appl. Sci. 2022"

abstract: We propose a deep reinforcement learning approach for solving a mapless navigation problem in warehouse scenarios. In our approach, an automatic guided vehicle is equipped with two LiDAR sensors and one frontal RGB camera and learns to perform a targeted navigation task. The challenges reside in the sparseness of positive samples for learning, multi-modal sensor perception with partial observability, the demand for accurate steering maneuvers together with long training cycles. To address these points, we propose NavACL-Q as an automatic curriculum learning method in combination with a distributed version of the soft actor-critic algorithm. The performance of the learning algorithm is evaluated exhaustively in a different warehouse environment to validate both robustness and generalizability of the learned policy. Results in NVIDIA Isaac Sim demonstrates that our trained agent significantly outperforms the map-based navigation pipeline provided by NVIDIA Isaac Sim with an increased agent-goal distance of 3 m and a wider initial relative agent-goal rotation of approximately 45%. The ablation studies also suggest that NavACL-Q greatly facilitates the whole learning process with a performance gain of roughly 40% compared to training with random starts and a pre-trained feature extractor manifestly boosts the performance by approximately 60%.

# Summary. An optional shortened abstract.
summary: We propose a deep reinforcement learning approach for solving a mapless navigation problem in warehouse scenarios. In our approach, an automatic guided vehicle is equipped with two LiDAR sensors and one frontal RGB camera and learns to perform a targeted navigation task ...

tags:
- Deep Reinforcement Learning
- Curriculum Learning
- Lidar-based Navigation
- Visual Navigation
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.mdpi.com/2076-3417/12/6/3153
url_code: 'https://github.com/ai-lab-science/Deep-Reinforcement-Learning-for-mapless-navigation-in-intralogistics'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
url_video: 'https://www.youtube.com/watch?v=HxvhiLem2XU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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


#{{% callout note %}}
#Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}
#
#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the example.
#{{% /callout %}}
#
#Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
---