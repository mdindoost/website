---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Recent Experience
subtitle: Please refer to my [curriculum vitae](uploads/cv.pdf) for more information.

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant
    company: New Jersey Institute of Technology
    company_url: 'https://www.njit.edu/'
    company_logo:
    location: New Jersey
    date_start: '2020-09-01'
    date_end: '2025-05-31'
    description: Designed, implemented, and optimized parallel algorithms and specialized data structures in Chapel for high-performance graph and data analytics within the revolutionary Arachne extension to the Arkouda analytics framework, significantly advancing capabilities in large-scale exploratory graph analytics. Led comprehensive research initiatives from rigorous literature reviews to advanced algorithm design, efficient parallel implementations, and systematic performance tuning on distributed computing architectures. This ground-breaking work culminated in my dissertation titled "On the Design of a Framework for Large-Scale Exploratory Graph Analytics", with peer-reviewed research outcomes published in prestigious venues including IEEE’s High Performance Extreme Computing Conference (HPEC), IEEE’s International Parallel and Distributed Processing Symposium (IPDPS), IEEE’s International Conference on High Performance Computing, Data, and Analytics (HiPC), MDPI’s Algorithms journal, and Nature’s Scientific Reports journal.
  
  - title: Chapel Programming Language Intern
    company: Hewlett Packard Enterprise (HPE)
    company_url: 'https://chapel-lang.org/'
    company_logo:
    location:
    date_start: '2024-06-01'
    date_end: '2024-08-31'
    description: Benchmarked high-performance distributed and parallel graph generation and breadth-first search (BFS) implementations in Chapel against the Graph500 benchmark suite utilizing optimized C with MPI, identifying key performance bottlenecks in irregular memory access and network communication. Presented detailed findings and actionable recommendations to the Chapel development team and HPE’s High-Performance Computing Advanced Development Organization, advocating enhancements in runtime support for atomic operations and improved communication aggregation libraries. Integrated optimized Chapel implementations into the Arachne graph analytics framework, achieving up to a 76x speedup in distributed BFS performance compared to Arachne’s original implementation.

  - title: Data Science Intern
    company: Chubb Insurance
    company_url: 'https://www.chubb.com/us-en/'
    company_logo:
    location: New Jersey
    date_start: '2020-06-01'
    date_end: '2020-08-01'
    description: Applied advanced machine learning classification techniques specifically tailored for textual data to enhance advertising relevance by accurately modeling user context. Developed expertise in key Python libraries including Scikit-Learn, Pandas, NumPy, TensorFlow, and Keras, and created a robust API to streamline text classification workflows, seamlessly integrating database-driven data sources to deliver actionable insights directly to Chubb Insurance’s sales teams. Managed code development and version control using Chubb’s enterprise GitHub environment, employing Agile methodologies and regularly presenting weekly progress updates and analytical insights to supervisors and the broader data science team.

  - title: Research Assistant
    company: William Paterson University (WPU)
    company_url: 'https://www.njit.edu/'
    company_logo:
    location: New Jersey
    date_start: '2017-09-01'
    date_end: '2020-05-31'
    description: Researched academic literature on cryptography and feedback carry shift registers (FCSRs), calculating the periods of AND-FCSR stream ciphers and developing a brute-force C++ program for XOR-FCSR analysis. Evaluated bitstream randomness using the NIST pseudorandom number generator statistical test suite within a UNIX environment, compiling and visually analyzing the results with Excel, and presenting positive findings at the 2019 Explorations Conference at WPU. Employed machine learning algorithms—including min-max normalization, k-means clustering, k-nearest neighbors (KNN), and linear regression—to predict software performance in digital signal processors, transitioning the analysis pipeline from Excel and R into Python using SciKit and Pandas libraries. Managed research communication through a SharePoint site, ensuring accurate data by comparing, updating, and consolidating outdated files.

design:
  columns: '2'
---
