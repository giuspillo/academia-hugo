---
title: "Harnessing distributional semantics to build context-aware justifications for recommender systems"
authors:
- Cataldo Musto
- admin
- Giovanni Semeraro
date: "2023-09-25T00:00:00Z"
doi: "10.1007/s11257-023-09382-x"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*User Modeling and User-Adapted Interaction*"
publication_short: "UMUAI"

abstract: This paper introduces a methodology to generate review-based natural language justifications supporting personalized suggestions returned by a recommender system. The hallmark of our strategy lies in the fact that natural language justifications are adapted to the different contextual situations in which the items will be consumed. In particular, our strategy relies on the following intuition. Just like the selection of the most suitable item is influenced by the contexts of usage, a justification that supports a recommendation should vary as well. As an example, depending on whether a person is going out with her friends or her family, a justification that supports a restaurant recommendation should include different concepts and aspects. Accordingly, we designed a pipeline based on distributional semantics models to generate a vector space representation of each context. Such a representation, which relies on a term-context matrix, is used to identify the most suitable review excerpts that discuss aspects that are particularly relevant for a certain context. The methodology was validated by means of two user studies, carried out in two different domains (i.e., movies and restaurants). Moreover, we also analyzed whether and how our justifications impact on the perceived transparency of the recommendation process and allow the user to make more informed choices. As shown by the results, our intuitions were supported by the user studies.

# Summary. An optional shortened abstract.
summary: This paper presents a methodology for generating review-based natural language justifications to support personalized recommendations. The approach adapts justifications to various contextual situations in which items will be used. The intuition is that justifications should vary with the context, such as different reasons for recommending a restaurant depending on whether a person is going out with friends or family. A pipeline based on distributional semantics models generates vector space representations of each context using a term-context matrix to identify suitable review excerpts. Validated through user studies in movies and restaurants, the methodology improved perceived transparency and helped users make more informed choices, confirming the initial intuitions.

featured: true

links:
- name: "PDF"
  url: "https://link.springer.com/content/pdf/10.1007/s11257-023-09382-x.pdf"
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

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

