---
title: 'Numerical geometric acoustics: An eikonal-based approach for modeling sound propagation in 3D environments'
authors:
  - Samuel F Potter
  - Maria K Cameron
  - Ramani Duraiswami

date: '2023-08-01T00:00:00Z'
#doi: 'https://doi.org/10.48550/arXiv.2402.05119'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-8-01'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

abstract: We present algorithms for solving high-frequency acoustic scattering problems in complex domains. The eikonal and transport partial differential equations from the WKB/geometric optic approximation of the Helmholtz equation are solved recursively to generate boundary conditions for a tree of eikonal/transport equation pairs, describing the phase and amplitude of a geometric optic wave propagating in a complicated domain, including reflection and diffraction. Edge diffraction is modeled using the uniform theory of diffraction. For simplicity, we limit our attention to domains with piecewise linear boundaries and a constant speed of sound. The domain is discretized into a conforming tetrahedron mesh. For the eikonal equation, we extend the jet marching method to tetrahedron meshes. Hermite interpolation enables second order accuracy for the eikonal and its gradient and first order accuracy for its Hessian, computed using cell averaging. To march the eikonal on an unstructured mesh, we introduce a new method of rejecting unphysical updates by considering Lagrange multipliers and local visibility. To handle accuracy degradation near caustics, we introduce several fast Lagrangian initialization algorithms. We store the dynamic programming plan uncovered by the marcher in order to propagate auxiliary quantities along characteristics. We introduce an approximate origin function which is computed using the dynamic programming plan, and whose 1/2-level set approximates the geometric optic shadow and reflection boundaries. We also use it to propagate geometric spreading factors and unit tangent vector fields needed to compute the amplitude and evaluate the high-frequency edge diffraction coefficient. We conduct numerical tests on a semi-infinite planar wedge to evaluate the accuracy of our method. We also show an example with a more realistic building model with challenging architectural features. Finally, we demonstrate a simple approach to extending the method to handle nonconstant speeds of sound by modifying the semi-Lagrangian updates to account for a varying speed.

# Summary. An optional shortened abstract.
summary:

tags:
  - Source Themes
featured: false

links:
  - name: Link
    url: https://www.sciencedirect.com/science/article/abs/pii/S0021999123002061
    
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

