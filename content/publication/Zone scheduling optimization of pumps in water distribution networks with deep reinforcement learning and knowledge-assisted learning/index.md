---
title: "Zone scheduling optimization of pumps in water distribution networks with deep reinforcement learning and knowledge-assisted learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Hongyuan Wang 
- Jun Rao
- Jingcheng Wang

# Author notes (optional)
author_notes:
- "Main contribution"

date: "2021-09-04T00:00:00Z"
doi: "10.1007/s00500-021-06177-3"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Soft computing
publication_short: Springer

abstract: This article studies the pump scheduling optimization problem in water distribution networks (WDNs) through a novel algorithm that combines knowledge learning and deep reinforcement learning. The optimization problem is modeled as a Markov decision process by taking three objectives in pressure management into consideration. Knowledge-assisted learning is incorporated into the reinforcement learning framework (KA-RL) to help evaluate the state value and guide the design of reward function, since the proposed KA-RL framework leverages the notion that historical data of WDNs could be utilized to produce optimal trajectories with respect to parametric variations. The knowledge-assisted proximal policy optimization (KA-PPO) algorithm, which only uses nodal pressure data, is proposed based on the KA-RL framework to address the arbitrary WDN topology and time-varying water demand. The effectiveness and applicability of the proposed algorithm are illustrated by virtue of the 22-node network with two pumps in a pump station. Empirical results demonstrate that KA-PPO works well in practice and compares favorably to Nelder–Mead method.

# Summary. An optional shortened abstract.
summary: In this article, we have proposed a DRL-based method for scheduling optimization of pumps in WDNs in a time-varying water demand condition. To help terminate the training process and design the reward function, we have established the KA-RL learning framework by combing knowledge-assisted learning with the DRL. Besides, a new algorithm called KA-PPO is proposed. The predictor is used in the KA learning for calculating the best state value of the WDNs.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/article/10.1007/s00500-021-06177-3'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
sledes: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
