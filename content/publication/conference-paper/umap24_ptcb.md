---
title: "Evaluating Content-based Pre-Training Strategies for a Knowledge-aware Recommender System based on Graph Neural Networks"
authors:
- admin
- Francesco Bottalico
- Cataldo Musto
- Marco de Gemmis
- Pasquale Lops
- Giovanni Semeraro
date: "2024-06-22T00:00:00Z"
doi: "10.1145/3627043.3659548"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *UMAP '24 - Proceedings of the 32nd ACM Conference on User Modeling, Adaptation and Personalization*
publication_short: In *UMAP '24*

abstract: In this paper, we introduce a Knowledge-aware Recommender System (KARS) based on Graph Neural Networks that exploit pre-trained content-based embeddings to improve the representation of users and items. Our approach relies on the intuition that textual features can describe the items in the catalog from a different point of view, so they are worth to be exploited to provide users with more accurate recommendations. Accordingly, we used encoding techniques to learn a pre-trained representation of the items in the catalogue based on textual content, and we used these embeddings to feed the input layer of a KARS based on GCNs. In this way, the GCN is able to encode both the knowledge coming from the unstructured content and the structured knowledge provided by the KG (ratings and item descriptive properties). As shown in our experiments, the exploitation of pre-trained embeddings improves the predictive accuracy of the KARS, which overcomes all the baselines we considered in several experimental settings.

summary: This paper introduces a Knowledge-aware Recommender System (KARS) using Graph Neural Networks (GNNs) that leverage pre-trained content-based embeddings to enhance user and item representations. By utilizing textual features to provide a different perspective on catalog items, the system aims to deliver more accurate recommendations. Pre-trained item representations based on textual content are used as input for the GNN-based KARS, allowing it to integrate both unstructured content and structured knowledge from the knowledge graph. Experiments show that incorporating pre-trained embeddings significantly improves predictive accuracy, outperforming all baselines in various settings.


featured: false

links:
- name: PDF
  url: https://dl.acm.org/doi/pdf/10.1145/3627043.3659548
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