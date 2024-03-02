---
title: 'Recursive computation of the multipole expansions of layer potential integrals over simplices for efficient fast multipole accelerated boundary elements'
authors:
  - Shoken Kaneko
  - Nail A. Gumerov
  - Ramani Duraiswami

date: '2023-08-01T00:00:00Z'
#doi: 'https://doi.org/10.48550/arXiv.2402.05119'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-8-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

abstract: In boundary element methods (BEM) in R3, matrix elements and right hand sides are typically computed via analytical or numerical quadrature of the layer potential multiplied by some function over line, triangle and tetrahedral volume elements. When the problem size gets large, the resulting linear systems are often solved iteratively via Krylov subspace methods, with fast multipole methods (FMM) used to accelerate the matrix vector products needed. When FMM acceleration is used, most entries of the matrix never need be computed explicitly - they are only needed in terms of their contribution to the multipole expansion coefficients. We propose a new fast method - Quadrature to Expansion (Q2X) - for the analytical generation of the multipole expansion coefficients produced by the integral expressions for single and double layers on surface triangles; charge distributions over line segments and over tetrahedra in the volume; so that the overall method is well integrated into the FMM, with controlled error. The method is based on the O(1) per moment cost recursive computation of the moments. The method is developed for boundary element methods involving the Laplace Green's function in R3. The derived recursions are first compared against classical quadrature algorithms, and then integrated into FMM accelerated boundary element and vortex element methods. Numerical tests are presented and discussed.

# Summary. An optional shortened abstract.
summary:

tags:
  - Source Themes
featured: false

links:
  - name: Link
    url: https://www.sciencedirect.com/science/article/abs/pii/S0021999123002139
    
#url_pdf: ' '

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

