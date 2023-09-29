---
title: "Constraint-Based Inference in Probabilistic Logic Programs"
authors:
- Arun Nampally
- Timothy Zhang
- C. R. Ramakrishnan
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2018-08-10T00:00:00Z"
doi: "https://doi.org/10.1017/S1471068418000273"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-08-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Theory and Practice of Logic Programming, 18(3-4)"
publication_short: "TPLP"

abstract: Probabilistic Logic Programs (PLPs) generalize traditional logic programs and allow the encoding of models combining logical structure and uncertainty. In PLP, inference is performed by summarizing the possible worlds which entail the query in a suitable data structure, and using this data structure to compute the answer probability. Systems such as ProbLog, PITA, etc., use propositional data structures like explanation graphs, BDDs, SDDs, etc., to represent the possible worlds. While this approach saves inference time due to substructure sharing, there are a number of problems where a more compact data structure is possible. We propose a data structure called Ordered Symbolic Derivation Diagram (OSDD) which captures the possible worlds by means of constraint formulas. We describe a program transformation technique to construct OSDDs via query evaluation, and give procedures to perform exact and approximate inference over OSDDs. Our approach has two key properties. Firstly, the exact inference procedure is a generalization of traditional inference, and results in speedup over the latter in certain settings. Secondly, the approximate technique is a generalization of likelihood weighting in Bayesian Networks, and allows us to perform sampling-based inference with lower rejection rate and variance. We evaluate the effectiveness of the proposed techniques through experiments on several problems.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.cambridge.org/core/services/aop-cambridge-core/content/view/AB5ED7E94AE807A38F18AA7F71BFD7F9/S1471068418000273a.pdf/constraint-based-inference-in-probabilistic-logic-programs.pdf'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
# slides: example
---

<!-- {{% callout note %}} -->
<!-- Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software. -->
<!-- {{% /callout %}} -->

<!-- {{% callout note %}} -->
<!-- Create your slides in Markdown - click the *Slides* button to check out the example. -->
<!-- {{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
