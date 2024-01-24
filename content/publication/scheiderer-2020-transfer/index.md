---
title: Transfer of Hierarchical Reinforcement Learning Structures for Robotic Manipulation
  Tasks

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Christian Scheiderer
- Malte Mosbach
- Andrés Felipe Posada-Moreno
- Tobias Meisen

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2020-12-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-01-24T08:04:51.798621Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*2020 International Conference on Computational Science and Computational
  Intelligence (CSCI)*'
publication_short: ''

doi: 10.1109/CSCI51800.2020.00091

abstract: While it is apparent that the transfer of knowledge between tasks is beneficial
  for training efficiency, the application of trained deep reinforcement learning
  agents to solve new tasks is not trivial. Especially when tasks are differently
  structured, retraining and fine tuning is not necessarily beneficial. Instead, it
  is often the most convenient approach to train a new agent from scratch. One potential
  solution for effectively reusing learned knowledge may be found in hierarchical
  reinforcement learning. In this paper we investigate the possibility of reusing
  low-level policies to improve training efficiency when learning manipulation tasks
  with an industrial robot. We consider four different scenarios and demonstrate for
  three of them an increased sample efficiency when training a high-level policy on
  top of pre-trained low-level skills. In the fourth scenario we uncover the reason
  for a failed transfer to be an ambitious higher hierarchy level enforcing a relearning
  of the low-level skills.

# Summary. An optional shortened abstract.
summary: 'In this paper we investigate the possibility of reusing low-level policies to improve training efficiency when learning manipulation tasks with an industrial robot.'

tags:
- ''

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/9458186
---
