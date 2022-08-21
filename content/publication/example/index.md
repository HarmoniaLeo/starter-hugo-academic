---
title: 'Learning the Trading Algorithm in Simulated Markets with Non-stationary Continuum Bandits'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bingde Liu

# Author notes (optional)
author_notes:
  - 'Equal contribution'

date: '2022-08-04T22:06:25Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-04T22:06:25Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: The basic Multi-Armed Bandits (MABs) problem is trying to maximize the rewards obtained from bandits with different unknown probability distributions of payoff for pulling different arms, given that only a finite number of attempts can be made. When studying trading algorithms in the market, we are looking at one of the most complex variants of MABs problems, namely the Non-stationary Continuum Bandits (NCBs) problem. The Bristol Stock Exchange (BSE) is a simple simulation of an electronic financial exchange based on a continuous double auction running via a limit order book. The market can be populated by automated trader agents with different trading algorithms. Within them, the PRSH algorithm embodies some basic ideas for solving NCBs problems. However, it faces the difficulty to adjust hyperparameters and adapt to changes in complex market conditions. We propose a new algorithm called PRB, which solves Continuum Bandits problem by Bayesian optimization, and solves Non-stationary Bandits problem by a novel “bandit-over-bandit” framework. With BSE, we use as many kinds of trader agents as possible to simulate the real market environment under two different market dynamics. We then examine the optimal hyperparameters of the PRSH algorithm and the PRB algorithm under different market dynamics respectively. Finally, by having trader agents using both algorithms trade in the market at the same time, we demonstrate that the PRB algorithm has better performance than the PRSH algorithm under both market dynamics. In particular, we perform rigorous hypothesis testing on all experimental results to ensure their correctness. 

# Summary. An optional shortened abstract.
summary: We propose a new algorithm called PRB, which solves Continuum Bandits problem by Bayesian optimization, and solves Non-stationary Bandits problem by a novel “bandit-over-bandit” framework.

tags: ['Multi-Armed Bandits', 'Market Simulation', 'Non-stationary bandits', 'Continuum bandits', 'Softmax Epsilon-Greedy', 'Bayesian optimization', 'Hypothesis test' ]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2208.02901.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
