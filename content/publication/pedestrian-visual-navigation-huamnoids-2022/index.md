---
title: 'End-To-End Deep Reinforcement Learning for First-Person Pedestrian Visual Navigation in Urban Environments'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Rui Song
  - Julian Petzold
  - Benedikt Hein
  - Heiko Hamann
  - Elmar Rueckert
  

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-09-15T00:00:00Z'
doi: '10.1109/Humanoids53995.2022.10000201'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-09-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE-RAS 21st International Conference on Humanoid Robots*
publication_short: In *Humanoids*

abstract: We solve a pedestrian visual navigation problem with a first-person view in an urban setting via deep reinforcement learning in an end-to-end manner. The major challenges lie in severe partial observability and sparse positive experiences of reaching the goal. To address partial observability, we propose a novel 3D-temporal convolutional network to encode sequential historical visual observations, its effectiveness is verified by comparing to a commonly-used Frame-Stacking approach. For sparse positive samples, we propose an improved automatic curriculum learning algorithm NavACL + , which proposes meaningful curricula starting from easy tasks and gradually generalizing to challenging ones. NavACL + is shown to facilitate the learning process with 21% earlier convergence, to improve the task success rate on difficult tasks by 40% compared to the original NavACL algorithm [1] and to offer enhanced generalization to different initial poses compared to training from a fixed initial pose.

# Summary. An optional shortened abstract.
summary: We solve a pedestrian visual navigation problem with a first-person view in an urban setting via deep reinforcement learning in an end-to-end manner ...

tags:
- Deep Reinforcement Learning
- Curriculum Learning
- Visual Navigation
# tags: [] original 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10000201'
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_video: 'https://drive.google.com/file/d/1lI0GTkCeTBrj-qSv-ZM8RTRT0A83odWD/view?usp=sharing'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example


#{{% callout note %}}
#Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}
#
#{{% callout note %}}
#Create your slides in Markdown - click the _Slides_ button to check out the example.
#{{% /callout %}}
#
#Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
---