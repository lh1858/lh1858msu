---
title: "Neural network-based multi-task learning for inpatient flow classification and length of stay prediction"
authors:
- admin
- Sreenath Chalil Madathil
- Mohammad T. Khasawneh
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "021-09-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.asoc.2021.107483"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Applied Soft Computing, (108)"
publication_short: ""

abstract: Inpatient unit resources are among the most expensive and valuable resources for healthcare organizations. Inpatient resources such as room, bed, and medical devices can be more efficiently managed if we can predict inpatient flow and length of stay (LOS) before admission and inpatient bed assignment  [1]. Patient LOS prediction has been researched individually using classical machine learning methods, such as linear regression, regression trees, random forest, and neural networks for a long time. Inpatient LOS and flow share many common features in training predictive models because both are closely related to relevant features such as recovery status and surgery types. Besides, these two tasks are closely related. For example, a patient with a more complex inpatient flow tends to have a longer LOS. This paper is the first comprehensive study that links them together as multi-tasks and develops an artificial neural network-based multi-task learning model (ANNML) for mixed types of task prediction in inpatient LOS and flow identification. The constructed multi-task learning model was tested on a real-life dataset collected from a large hospital in New York City and compared with four single-task learning models. The results show that ANNML can use the most relevant features to achieve a better prediction accuracy for both task types and has less overfitting and testing variance than single-task learning models.

# Summary. An optional shortened abstract.
highlights: Proposes an ANN-based MTL model for predicting inpatient flow and LOS simultaneously. The proposed MTL model works for mixed tasks including regression and classification. Describes a systematic method to collect and clean datasets of inpatient flow. Tests the proposed methodology on a real-life dataset from a large hospital in NY. Compares results of the proposed MTL models with equivalent single-task models.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://doi.org/10.1016/j.asoc.2021.107483
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
