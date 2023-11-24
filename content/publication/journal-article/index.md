---
title: "HYBRID CNN-VIT MODELS FOR MEDICAL IMAGE CLASSIFICATION"
authors:
- admin
- Dimitrios Pantelaios
date: "2023-011-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Under review - **International Symposium on Biomedical Imaging 2024**
publication_short: Under review - **ISBI 2024**

abstract: The success of Transformers in the field of Natural Language Processing and Computer Vision inspired their use in various image analysis tasks. Vision Transformers capture longrange global dependencies through attention layers, but lack inductive biases, making it challenging for them to generalize when trained on small datasets. As a result, larger datasets are required for their training, which poses a significant obstacle specifically in the medical image classification task. This study focuses on the classification of chest X-ray images corresponding to different diseases affecting the lungs, such as COVID-19. To address the aforementioned challenges, hybrid models were devised, aiming to incorporate some advantages of CNNs into Vision Transformers, enabling the training of models on smaller datasets. So, in this work, we compare the hybrid models pre-trained on ImageNet1k with the traditional Vision Transformer pre-trained on ImageNet-21k using both a subset and the entire available COVID-QU-Ex dataset, while we also explore training the models from scratch. The results obtained demonstrate the superiority of the hybrid models in terms of accuracy, training time and the number of data required for training.

# Summary. An optional shortened abstract.
summary: Comparing hubrid CNN-VIT models for medical image classification.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
# url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Paper Overview: [**Architecture**](featured.jpg)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo academia's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

