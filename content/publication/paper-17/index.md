---
title: 'Towards fast and convenient end-to-end HRTF personalization'
authors:
  - Bowen Zhi
  - Dmitry Zotkin
  - Ramani Duraiswami


date: '2022-05-23T00:00:00Z'
#doi: 'https://doi.org/10.48550/arXiv.2402.05119'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-23'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

abstract: Incorporating individualized head-related transfer functions (HRTFs) into a high fidelity sound engine can further improve the perceived quality and realism of binaurally-rendered spatial audio. Traditional methods to measure individual HRTFs tend to be cumbersome, expensive and require physical access to the subject. To address these issues, we develop a convolutional neural network model that, given a single photo of an ear, predicts pinna landmarks that can be used to extract anthropometric features commonly used for HRTF personalization, and match to a database of subjects whose HRTFs and pictures are available. We propose and evaluate a system utilizing this model to generate an individualized HRTF using a minimal set of easily obtainable measurements; single photographs of both ears, as well as head and ear scale for matching interaural time difference (ITD). To extend the reach of our database we employ ideas from Kendall shape theory to match ears non-dimensionally, match all ears to right ears, and make corresponding changes to the database HRIRs. We also apply HAT models to the HRIRs to provide better matching.

# Summary. An optional shortened abstract.
summary:

tags:
  - Source Themes
featured: false

links:
  - name: Link
    url: https://ieeexplore.ieee.org/abstract/document/9746315
    
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9746315'

#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  #focal_point: ''
  #preview_only: false 

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

