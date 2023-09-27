---
title: 'Motion Robust High-Speed Light-weighted Object Detection with Event Camera'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bingde Liu
  - Chang Xu
  - Wen Yang
  - Huai Yu
  - Lei Yu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'

date: '2023-04-26T15:15:24Z'
doi: '10.1109/TIM.2023.3269780'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-26T15:15:24Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Instrumentation and Measurement
publication_short: IEEE TIM

abstract: The event camera asynchronously produces the event stream with a high temporal resolution, discarding redundant visual information and bringing new possibilities for moving object detection. Nevertheless, the existing object detectors cannot make the most of the spatial-temporal asynchronous nature and high temporal resolution of the event stream. For one thing, existing methods fail to consider objects with different velocities relative to the event camera’s motion, resulting from the global synchronized time window with the whole spatial slice. For another, most of the existing methods rely on heavy models and boost the detection performance with low frame rates, failing to utilize the high temporal resolution characteristic of the event stream. In this work, we propose a motion robust and high-speed detection pipeline which better leverages the event data. First, we design an event stream representation called temporal active focus (TAF), which efficiently utilizes the spatial-temporal asynchronous event stream, constructing event tensors robust to object motions. Then, we propose a module called the bifurcated folding module (BFM), which encodes the rich temporal information in the TAF tensor at the input layer of the detector. Following this, we design a high-speed lightweight detector called agile event detector (AED) plus a simple but effective data augmentation method, to enhance the detection accuracy and reduce the model’s parameter. Experiments on two typical real-scene event camera object detection datasets show that our method is competitive in terms of accuracy, efficiency, and the number of parameters. By classifying objects into multiple motion levels based on the optical flow density metric, we further illustrated the robustness of our method for objects with different velocities relative to the camera. The codes and trained models are available at https://github.com/HarmoniaLeo/FRLW-EvD .

# Summary. An optional shortened abstract.
summary: We design a high-speed lightweight detector called Agile Event Detector (AED), an event stream representation tensor called Temporal Active Focus (TAF) and a module called the Bifurcated Folding Module (BFM), to accurately detect objects with the event camera at high speed with the robustness of different motion speeds. 

tags: ['Event Camera', 'Object Detection', 'Deep Learning']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: IEEE Xplore
  url: https://ieeexplore.ieee.org/abstract/document/10109007

url_pdf: 'https://arxiv.org/pdf/2208.11602.pdf'
url_code: 'https://github.com/HarmoniaLeo/FRLW-EvD'
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
