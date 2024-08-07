---
title: "Knowledge-aware Recommendations Based on Neuro-Symbolic Graph Embeddings and First-Order Logical Rules"
authors:
- admin
- Cataldo Musto
- Marco de Gemmis
- Pasquale Lops
- Giovanni Semeraro
date: "2022-09-14T00:00:00Z"
doi: "10.1145/3604915.3608840"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *RecSys '22 - Proceedings of the 16th ACM Conference on Recommender Systems*
publication_short: In *RecSys '22*

abstract: In this paper, we present a knowledge-aware recommendation framework based on neuro-symbolic graph embeddings that encode first-order logical (FOL) rules. In particular, our workflow starts from a knowledge graph (KG) encoding user preferences (based on explicit ratings [13]) and item properties. Next, knowledge-aware recommendation are obtained through the combination of three modules (i) a rule learner, that extracts FOL rules from the KG; (ii) a graph embedding module, that learns the embeddings of users and items based on the triples of the KG and the FOL rules previously extracted; (iii) a recommendation module that uses the embeddings to feed a deep learning architecture. In the experimental session, we evaluate the effectiveness of our strategy on two datasets and the results show that the combination of KG embeddings and FOL rules led to an improvement in the accuracy and in the novelty of the recommendations.

summary: This paper introduces a knowledge-aware recommendation framework utilizing neuro-symbolic graph embeddings that encode first-order logical (FOL) rules. The process begins with a knowledge graph (KG) that captures user preferences through explicit ratings and item properties. The recommendation framework consists of three main modules (i) a rule learner that extracts FOL rules from the KG, (ii) a graph embedding module that learns embeddings of users and items based on KG triples and the extracted FOL rules, and (iii) a recommendation module that uses these embeddings to feed a deep learning architecture. Experimental results on two datasets indicate that integrating KG embeddings with FOL rules enhances both the accuracy and novelty of the recommendations.


featured: false

links:
- name: PDF
  url: https://dl.acm.org/doi/pdf/10.1145/3523227.3551484
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