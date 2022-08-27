---
title: 'Motion Robust High-Speed Light-weighted Object Detection with Event Camera'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bingde Liu

# Author notes (optional)
author_notes:
  - 'Equal contribution'

date: '2022-08-24T15:15:24Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-04T15:15:24Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: The event camera produces a large dynamic range event stream with a very high temporal resolution discarding redundant visual information, thus bringing new possibilities for object detection tasks. However, the existing methods of applying the event camera to object detection tasks using deep learning methods still have many problems. First, existing methods cannot take into account objects with different velocities relative to the motion of the event camera due to the global synchronized time window and temporal resolution. Second, most of the existing methods rely on large parameter neural networks, which implies a large computational burden and low inference speed, thus contrary to the high temporal resolution of the event stream. In our work, we design a high-speed lightweight detector called Agile Event Detector (AED) with a simple but effective data augmentation method. Also, we propose an event stream representation tensor called Temporal Active Focus (TAF), which takes full advantage of the asynchronous generation of event stream data and is robust to the motion of moving objects. It can also be constructed without much time-consuming. We further propose a module called the Bifurcated Folding Module (BFM) to extract the rich temporal information in the TAF tensor at the input layer of the AED detector. We conduct our experiments on two typical real-scene event camera object detection datasets the complete Prophesee GEN1 Automotive Detection Dataset and the Prophesee 1 MEGAPIXEL Automotive Detection Dataset with partial annotation. Experiments show that our method is competitive in terms of accuracy, speed, and the number of parameters simultaneously. Also by classifying the objects into multiple motion levels based on the optical flow density metric, we illustrated the robustness of our method for objects with different velocities relative to the camera.

# Summary. An optional shortened abstract.
summary: We design a high-speed lightweight detector called Agile Event Detector (AED), an event stream representation tensor called Temporal Active Focus (TAF) and a module called the Bifurcated Folding Module (BFM), to accurately detect objects with the event camera at high speed with the robustness of different motion speeds. 

tags: ['Event Camera', 'Object Detection', 'Deep Learning']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2208.11602.pdf'
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
