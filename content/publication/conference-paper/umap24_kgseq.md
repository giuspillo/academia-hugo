---
title: "Improving Transformer-based Sequential Conversational Recommendations through Knowledge Graph Embeddings"
authors:
- Alessandro Petruzzelli
- Alessandro Francesco Maria Martina
- admin
- Cataldo Musto
- Marco de Gemmis
- Pasquale Lops
- Giovanni Semeraro
date: "2024-06-22T00:00:00Z"
doi: "10.1145/3627043.3659565"

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

abstract: Conversational Recommender Systems (CRS) have recently drawn attention due to their capacity of delivering personalized recommendations through multi-turn natural language interactions. In this paper, we fit into this research line and we introduce a Knowledge-Aware Sequential Conversational Recommender System (KASCRS) that exploits transformers and knowledge graph embeddings to provide users with recommendations in a conversational setting. In particular, KASCRS is able to predict a suitable recommendation based on the elements that are mentioned in a conversation between a user and a CRS. To do this, we design a model that (i) encodes each conversation as a sequence of entities that are mentioned in the dialogue (i.e., items and properties), and (ii) is trained on a cloze task, that is to say, it learns to predict the final element in the sequence - that corresponds to the item to be recommended - based on the information it has previously seen. The model has two main hallmarks; first, we exploit Transformers and self-attention to capture the sequential dependencies that exist among the entities that are mentioned in the training dialogues, in a way similar to session-based recommender systems [25]. Next, we used knowledge graphs (KG) to improve the quality of the representation of the elements mentioned in each sequence. Indeed, we exploit knowledge graph embeddings techniques to pre-train the representation of items and properties, and we fed the input layer of our architecture with the resulting embeddings. In this way, KASCRS integrates both knowledge from the KGs as well as the dependencies and the co-occurrences emerging from conversational data, resulting in a more accurate representation of users and items. Our experiments confirmed this intuition, since KASCRS overcame several state-of-the-art baselines on two different datasets.

summary: This paper introduces a Knowledge-Aware Sequential Conversational Recommender System (KASCRS) that provides personalized recommendations through multi-turn natural language interactions. KASCRS uses transformers and knowledge graph embeddings to predict suitable recommendations based on conversation content. The model encodes each conversation as a sequence of mentioned entities (items and properties) and is trained to predict the final item in the sequence using a cloze task. Key features include leveraging transformers and self-attention to capture sequential dependencies, and using knowledge graph embeddings to pre-train representations of items and properties. This integration enhances the accuracy of user and item representations. Experiments demonstrated that KASCRS outperformed several state-of-the-art baselines on two datasets.


featured: false

links:
- name: PDF
  url: https://dl.acm.org/doi/pdf/10.1145/3627043.3659565
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