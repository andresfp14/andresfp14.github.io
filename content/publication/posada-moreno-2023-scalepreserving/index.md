---
title: Scale-Preserving Automatic Concept Extraction (SPACE)
authors:
- Andrés Felipe Posada-Moreno
- Lukas Kreisköther
- Tassilo Glander
- Sebastian Trimpe
date: '2023-11-01'
publishDate: '2024-01-23T16:18:17.733428Z'
publication_types:
- article-journal
doi: 10.1007/s10994-023-06373-2
abstract: Convolutional Neural Networks (CNN) have become a common choice for industrial
  quality control, as well as other critical applications in the Industry 4.0. When
  these CNNs behave in ways unexpected to human users or developers, severe consequences
  can arise, such as economic losses or an increased risk to human life. Concept extraction
  techniques can be applied to increase the reliability and transparency of CNNs through
  generating global explanations for trained neural network models. The decisive features
  of image datasets in quality control often depend on the feature’s scale; for example,
  the size of a hole or an edge. However, existing concept extraction methods do not
  correctly represent scale, which leads to problems interpreting these models as
  we show herein. To address this issue, we introduce the Scale-Preserving Automatic
  Concept Extraction (SPACE) algorithm, as a state-of-the-art alternative concept
  extraction technique for CNNs, focused on industrial applications. SPACE is specifically
  designed to overcome the aforementioned problems by avoiding scale changes throughout
  the concept extraction process. SPACE proposes an approach based on square slices
  of input images, which are selected and then tiled before being clustered into concepts.
  Our method provides explanations of the models’ decision-making process in the form
  of human-understandable concepts. We evaluate SPACE on three image classification
  datasets in the context of industrial quality control. Through experimental results,
  we illustrate how SPACE outperforms other methods and provides actionable insights
  on the decision mechanisms of CNNs. Finally, code for the implementation of SPACE
  is provided.
tags:
- 68T01
- 68T20
- Explainable artificial intelligence
- Image processing
- Industry
- Neural networks
links:
- name: URL
  url: https://doi.org/10.1007/s10994-023-06373-2
---
