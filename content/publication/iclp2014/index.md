---
title: 'Adaptive MCMC-based inference in probabilistic logic programs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Arun Nampally
  - C. R. Ramakrishnan

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2014-03-24T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.1403.6036'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Technical Communications of the 30th International Conference on Logic Programming*
publication_short: In *ICLP 2014*

abstract: Probabilistic Logic Programming (PLP) languages enable programmers to specify systems that com- bine logical models with statistical knowledge. The inference problem, to determine the probability of query answers in PLP, is intractable in general, thereby motivating the need for approximate techniques. In this paper, we present a technique for approximate inference of conditional probabilities for PLP queries. It is an Adaptive Markov Chain Monte Carlo (MCMC) technique, where the distribution from which samples are drawn is modified as the Markov Chain is explored. In particular, the distribution is progressively modified to increase the likelihood that a generated sample is consistent with evidence. In our context, each sample is uniquely characterized by the outcomes of a set of random variables. Inspired by reinforcement learning, our technique propagates rewards to random variable/outcome pairs used in a sample based on whether the sample was consistent or not. The cumulative rewards of each outcome is used to derive a new “adapted distribution” for each random variable. For a sequence of samples, the distributions are progressively adapted after each sample. For a query with “Markovian evaluation structure”, we show that the adapted distribution of samples converges to the query’s conditional proba- bility distribution. For Markovian queries, we present a modified adaptation process that can be used in adaptive MCMC as well as adaptive independent sampling. We empirically evaluate the effectiveness of the adaptive sampling methods for queries with and without Markovian evaluation structure.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1403.6036.pdf'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}} -->
<!-- Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software. -->
<!-- {{% /callout %}} -->

<!-- {{% callout note %}} -->
<!-- Create your slides in Markdown - click the _Slides_ button to check out the example. -->
<!-- {{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
