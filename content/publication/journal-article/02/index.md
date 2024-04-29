---
title: "A weighted distance-based approach with boosted decision trees for label ranking"
authors:
- Albano
- Sciandra
- Plaia


#author_notes:
#- "Equal contribution"
#- "Equal contribution"
#date: "2021-05-27T00:00:00Z"
doi: "https://doi.org/10.1016/j.eswa.2022.119000"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Expert Systems with Applications*"
# publication_short: ""

abstract: Label Ranking (LR) is an emerging non-standard supervised classification problem with practical applications in different research fields. The Label Ranking task aims at building preference models that learn to order a finite set of labels based on a set of predictor features. One of the most successful approaches to tackling the LR problem consists of using decision tree ensemble models, such as bagging, random forest, and boosting. However, these approaches, coming from the classical unweighted rank correlation measures, are not sensitive to label importance. Nevertheless, in many settings, failing to predict the ranking position of a highly relevant label should be considered more serious than failing to predict a negligible one. Moreover, an efficient classifier should be able to take into account the similarity between the elements to be ranked. The main contribution of this paper is to formulate, for the first time, a more flexible label ranking ensemble model which encodes the similarity structure and a measure of the individual label importance. Precisely, the proposed method consists of three item-weighted versions of the AdaBoost boosting algorithm for label ranking. The predictive performance of our proposal is investigated both through simulations and applications to three real datasets.

# Summary. An optional shortened abstract.
# summary: ...

tags:
- paper

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://journals.sagepub.com/doi/abs/10.1177/01655515221148369
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: https://www.sciencedirect.com/science/article/pii/S0957417422020188
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides:
---
