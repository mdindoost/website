---
title: 'Arachne: An Open-Source Framework for Interactive Massive-Scale Graph Analytics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - David A. Bader

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-05-16T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-14T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE International Parallel and Distributed Processing Symposium*
publication_short: In *IPDPS 23*

abstract: Massive-scale analytics is an emerging field that integrates the power of high-performance computing and mathematical modeling to extract key insights and information from data sets that can be as large as petabytes and beyond. Productivity in massive-scale analytics entails quick interpretation of results through easy-to-use systems, while also adhering to design principles that combine high-performance computing and user-friendly simplicity. However, data scientists often encounter challenges, especially with graph analytics, which require the analysis of complex data from various domains, such as the natural and social sciences. To address this issue, we introduce Arachne, a system that enhances accessibility and usability in massive-scale graph analytics. Arachne offers novel algorithms and implementations of graph kernels for efficient data analysis, such as connected components, breadth-first search, triangle counting, k-truss, among others. The algorithms are integrated into a backend server written in Chapel and can be accessed through a Python application programming interface (API). Arachne delivers high performance in the shared-memory versions of its algorithms, and we have assessed its capabilities with the Friendster social network that is comprised of 1,806,067,135 edges and 65,608,366 vertices. Arachne's backend server is compatible with Linux supercomputers, is easy to set up, and can be utilized through either Python scripts or Jupyter notebooks, which makes it a desirable tool for data scientists who have access to highly performing Linux compute clusters. In this poster we present an overview of the algorithms we have implemented into Arachne and, if applicable, the algorithmic novelties introduced for each of them. We provide results in the format of execution times and discuss the much-needed improvements in communication overheads for our implementations. Further, we discuss improvements to our graph data structure to store extra information such as node labels, edge relationships, and node and edge properties. Arachne is built as an extension to Arkouda and allows for graphs to be generated from Arkouda dataframes. The open-source code for Arachne can be found at https://github.com/Bears-R-Us/arkouda-njit.

# Summary. An optional shortened abstract.
# summary:

# tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Buy
#   url: https://www.taylorfrancis.com/books/edit/10.1201/9781003033707/massive-graph-analytics-david-bader

url_pdf: content/publication/2023-IPDPS_phd_forum/2023-IPDPS_phd_forum.pdf
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
