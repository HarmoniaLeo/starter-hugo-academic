---
title: 'Nonstationary Continuum-Armed Bandit Strategies for Automated Trading in a Simulated Financial Market'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bingde Liu
  - John Cartlidge

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'

date: '2023-06-26T22:06:25Z'
doi: '10.46354/i3m.2023.dhss.001'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-18T22:06:25Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
# publication: Proceedings of the 13th International Defence and Homeland Security Simulation Worskhop
# publication_short: DHSS 2023

abstract: We approach the problem of designing an automated trading strategy that can consistently profit by adapting to changing market conditions. This challenge can be framed as a Nonstationary Continuum-Armed Bandit (NCAB) problem. To solve the NCAB problem, we propose PRBO, a novel trading algorithm that uses Bayesian optimization and a ``bandit-over-bandit'' framework to dynamically adjust strategy parameters in response to market conditions. We use Bristol Stock Exchange (BSE) to simulate financial markets containing heterogeneous populations of automated trading agents and compare PRBO with PRSH, a reference trading strategy that adapts strategy parameters through stochastic hill-climbing. Results show that PRBO generates significantly more profit than PRSH, despite having fewer hyperparameters to tune. The code for PRBO and performing experiments is available online open-source (this https URL).

# Summary. An optional shortened abstract.
summary: We propose a new algorithm called PRB, which solves Continuum Bandits problem by Bayesian optimization, and solves Non-stationary Bandits problem by a novel “bandit-over-bandit” framework.

tags: ['Multi-Armed Bandits', 'Market Simulation', 'Non-stationary bandits', 'Continuum bandits', 'Softmax Epsilon-Greedy', 'Bayesian optimization', 'Hypothesis test' ]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Proceedings of the 13th  International Defense and Homeland Security Simulation Workshop DHSS
  url: https://www.cal-tek.eu/proceedings/i3m/2023/dhss/

url_pdf: 'https://www.cal-tek.eu/proceedings/i3m/2023/dhss/001/pdf.pdf'
url_code: 'https://github.com/HarmoniaLeo/PRZI-Bayesian-Optimisation'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: #'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
