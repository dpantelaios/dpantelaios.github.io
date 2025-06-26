---
title: "HYBRID CNN-VIT MODELS FOR MEDICAL IMAGE CLASSIFICATION"
authors:
# - admin
- Dimitrios Pantelaios
- "Paraskevi-Antonia Theofilou"
- "Paraskevi K. Tzouveli"
- "Stefanos D. Kollias"
date: "2024-05-27T00:00:00Z"
doi: ""
link_authors: false 

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Accepted - **International Symposium on Biomedical Imaging 2024**
publication_short: Accepted - **ISBI 2024**

abstract: Vision Transformers capture long-range global dependencies through attention layers, but lack inductive biases, which poses a challenge for generalization on small datasets, particularly in medical image classification. This study focuses on the classification of chest X-ray images corresponding to different diseases affecting the lungs, such as COVID-19, and Viral and Bacterial Pneumonia. To address the aforementioned challenges, hybrid models were explored, aiming to incorporate some advantages of CNNs into Vision Transformers, enabling the training of models on smaller datasets. So, in this work, we compare the hybrid models pre-trained on ImageNet-1k with the traditional Vision Transformer pre-trained on ImageNet-21k using both a subset and the entire available COVID-QU-Ex dataset, while we also explore training the models from scratch. The results obtained demonstrate the superiority of the hybrid models in terms of accuracy, training time, and dataset size requirements.

# Summary. An optional shortened abstract.
summary: Comparing hybrid CNN-VIT and ViT models for medical image classification.

# tags:
# - Source Themes
# featured: true

links:
- name: Link
  url: https://ieeexplore.ieee.org/document/10635205
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

<!-- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

