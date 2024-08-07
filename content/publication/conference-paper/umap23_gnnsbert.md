---
title: "Combining Graph Neural Networks and Sentence Encoders for Knowledge-aware Recommendations"
authors:
- admin
- Cataldo Musto
- Marco Polignano
- Pasquale Lops
- Marco de Gemmis
- Giovanni Semeraro
date: "2023-06-18T00:00:00Z"
doi: "10.1145/3565472.3592965"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *UMAP '23 - Proceedings of the 31st ACM Conference on User Modeling, Adaptation and Personalization*
publication_short: In *UMAP '23*

abstract: In this paper, we present a strategy to provide users with knowledge-aware recommendations based on the combination of graph neural networks and sentence encoders. In particular, our approach relies on the intuition that different data sources (i.e., structured data available in a knowledge graph and unstructured data, such as textual content) provide complementary information and can equally contribute to learn an accurate item representation. Accordingly, we first exploited graph neural networks to encode both collaborative features, such as the interactions between users and items, and structured properties of the items. Next, we used a sentence encoder that relies on transformers to learn a representation based on textual content describing the items. Finally, these embeddings are combined by exploiting a deep neural network where both self-attention and cross-attention mechanisms are used to learn the relationships between the initial embeddings and to further refine the representation. Such a neural network provides as output a prediction of users’ interest in the items, which is used to return a top-k recommendation list. In the experimental evaluation, we carried out an experiment against two datasets, and the results showed that our approach overcame several competitive baselines.

summary: The paper presents a method for knowledge-aware recommendations by combining graph neural networks (GNNs) and sentence encoders. We expolited structured data from knowledge graphs and unstructured textual content to learn accurate user and item representations. GNNs encode collaborative features and item properties, while a sentence encoder encodes textual descriptions. These embeddings are merged using a deep neural network with self-attention and cross-attention mechanisms to refine representations. The model predicts user interest to generate a top-k recommendation list, and experiments show this approach outperforms several competitive baselines.


featured: true

links:
- name: PDF
  url: https://dl.acm.org/doi/pdf/10.1145/3565472.3592965
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
  caption: 'Our architecture'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
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