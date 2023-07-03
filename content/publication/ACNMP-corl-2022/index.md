---
title: 'ACNMP: Skill transfer and task extrapolation through learning from demonstration and reinforcement learning via representation sharing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - M. Tuluhan Akbulut
  - Erhan Oztop
  - M. Yunus Seker
  - admin
  - Ahmet E. Tekden
  - Emre Ugur
  

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-11-15T00:00:00Z'
#doi: '10.1109/Humanoids53995.2022.10000201'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Conference on Robot Learning, 2020*
publication_short: In *CORL*

abstract: To equip robots with dexterous skills, an effective approach is to first transfer the desired skill via Learning from Demonstration (LfD), then let the robot improve it by self-exploration via Reinforcement Learning (RL). In this paper, we propose a novel LfD+RL framework, namely Adaptive Conditional Neural Movement Primitives (ACNMP), that allows efficient policy improvement in novel environments and effective skill transfer between different agents. This is achieved through exploiting the latent representation learned by the underlying Conditional Neural Process (CNP) model, and simultaneous training of the model with supervised learning (SL) for acquiring the demonstrated trajectories and via RL for new trajectory discovery. Through simulation experiments, we show that (i) ACNMP enables the system to extrapolate to situations where pure LfD fails; (ii) Simultaneous training of the system through SL and RL preserves the shape of demonstrations while adapting to novel situations due to the shared representations used by both learners; (iii) ACNMP enables order-of-magnitude sample-efficient RL in extrapolation of reaching tasks compared to the existing approaches; (iv) ACNMPs can be used to implement skill transfer between robots having different morphology, with competitive learning speeds and importantly with less number of assumptions compared to the state-of-the-art approaches. Finally, we show the real-world suitability of ACNMPs through real robot experiments that involve obstacle avoidance, pick and place and pouring actions
# Summary. An optional shortened abstract.
summary: To equip robots with dexterous skills, an effective approach is to first transfer the desired skill via Learning from Demonstration (LfD), then let the robot improve it ...

tags:
- Deep Reinforcement Learning
- Representation Learning
- Learning from Demonstration
- Deep Learning
# tags: [] original 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://www.cmpe.boun.edu.tr/~emre/papers/Akbulut-2020-CORL.pdf
url_code: 'https://mtuluhanakbulut.github.io/ACNMP/'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_video: 'https://drive.google.com/file/d/1lI0GTkCeTBrj-qSv-ZM8RTRT0A83odWD/view?usp=sharing'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
---

#{{% callout note %}}
#Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}
#
#{{% callout note %}}
#Create your slides in Markdown - click the _Slides_ button to check out the example.
#{{% /callout %}}
#
#Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
