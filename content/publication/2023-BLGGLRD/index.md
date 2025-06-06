---
title: 'Triangle Counting Through Cover-Edges'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - David A. Bader
  - Fuhuan Li
  - Anya Ganeshan
  - Ahmet Gundogdu
  - Jason Lew
  - admin

# Author notes (optional)
author_notes:
   - 'Student Innovation Award'

date: '2023-09-01T00:00:00Z'
doi: '10.1109/HPEC58863.2023.10363498'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *The 27th Annual IEEE High Performance Extreme Computing Conferenc*
publication_short: In *HPEC 23*

abstract: Counting and finding triangles in graphs is often used in real-world analytics to characterize cohesiveness and identify communities in graphs. In this paper, we propose the novel concept of a cover-edge set that can be used to find triangles more efficiently. We use a breadth-first search (BFS) to quickly generate a compact cover-edge set. Novel sequential and parallel triangle counting algorithms are presented that employ cover-edge sets. The sequential algorithm avoids unnecessary triangle-checking operations, and the parallel algorithm is communication-efficient. The parallel algorithm can asymptotically reduce communication on massive graphs such as from real social networks and synthetic graphs from the Graph500 Benchmark. In our estimate from massive-scale Graph500 graphs, our new parallel algorithm can reduce the communication on a scale 36 graph by 1156x and on a scale 42 graph by 2368x.

# Summary. An optional shortened abstract.
# summary:

# tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Buy
#   url: https://www.taylorfrancis.com/books/edit/10.1201/9781003033707/massive-graph-analytics-david-bader

url_pdf: content/publication/2023-BLGGLRD/2023-BLGGLRD.pdf
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
