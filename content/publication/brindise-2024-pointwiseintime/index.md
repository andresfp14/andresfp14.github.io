---
title: 'Pointwise-in-Time Diagnostics for Reinforcement Learning during Training and Runtime'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Noel Brindise
- Andrés Felipe Posada-Moreno
- Cedric Langbort
- Sebastian Trimpe

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-06-11'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-06-11T08:04:51.749292Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

doi: ''

abstract: Explainable AI Planning (XAIP), a subfield of xAI, offers a variety of methods to interpret the behavior of autonomous systems. A recent "pointwise-in-time" explanation method, called Rule Status Assessment (RSA), characterizes an agent’s behavior at individual time steps in a trajectory using linear temporal logic (LTL) rules. In this work, RSA is applied for the first time in a reinforcement learning (RL) context. We first demonstrate RSA diagnostics as a substantial supplement to the basic RL reward curve, tracking whether and when specified subtasks are accomplished. We then introduce a novel “Interactive RSA” which provides the user with detailed diagnostic information automatically at any desired point in a trajectory. We apply RSA to an advanced agent at runtime and show that RSA and its novel interactive variant constitute a promising step towards explainable RL.

# Summary. An optional shortened abstract.
summary: 'A framework for explaining RL agents during training and runtime based the definition of an agents desired behavior through linear temporal logic (LTL).'

tags:
- Explainable AI Planning
- Explainable Reinforcement Learning
- Linear Temporal Logic
- Markov Decision Processes
- Explainable artificial intelligence

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
  url: https://proceedings.mlr.press/v242/brindise24a.html
---
