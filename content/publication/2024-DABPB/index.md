---
title: 'VF2-PS: Parallel and Scalable Subgraph Monomorphism in Arachne'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mohammad Dindoost
  - admin
  - Sounak Bagchi
  - Palina Pauliuchenka
  - Zhihui Du
  - David A. Bader

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-09-01T00:00:00Z'
# doi: 

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *The 28th Annual IEEE High Performance Extreme Computing Conferenc*
publication_short: In *HPEC 24*

abstract: This paper introduces a novel, parallel, and scalable implementation of the VF2 algorithm for subgraph monomorphism developed in the high-productivity language Chapel. Efficient graph analysis in large and complex network datasets is crucial across numerous scientific domains. We address this need through our enhanced VF2 implementation, widely utilized in subgraph matching, and integrating it into Arachne—a Python-accessible, open-source, large-scale graph analysis framework. Leveraging the parallel computing capabilities of modern hardware architectures, our implementation achieves significant performance improvements. Benchmarks on synthetic and real-world datasets, including social, communication, and neuroscience networks, demonstrate speedups of up to 97X on 128 cores, compared to existing Python-based tools like NetworkX and DotMotif, which do not exploit parallelization. Our results on large-scale graphs demonstrate scalability and efficiency, establishing it as a viable tool for subgraph monomorphism, the backbone of numerous graph analytics such as motif counting and enumeration. Arachne, including our VF2 implementation, can be found on GitHub at https://github.com/Bears-R-Us/arkouda-njit.

# Summary. An optional shortened abstract.
# summary:

# tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Buy
#   url: https://www.taylorfrancis.com/books/edit/10.1201/9781003033707/massive-graph-analytics-david-bader

# url_pdf:
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: ''
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   -

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides:
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
