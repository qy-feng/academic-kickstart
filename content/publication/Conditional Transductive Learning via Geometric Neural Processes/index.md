---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Conditional Transductive Learning via Geometric Neural Processes"
authors: [Qianyu Feng, Pingbo Pan, Alexander Hauptmann, Yi Yang]
date: 2020-12-20T10:46:33+10:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-20T10:46:33+10:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Preprint"
publication_short: ""

abstract: "Contemporary data-driven methods are typically fed with large-scale data samples which limits their applicability in small data regimes. On the contrary, neural processes can efficiently fit the observed data to model the data distribution. However, it is nontrivial for most existing neural process methods to perceive the relativity in the data samples. Here we propose Geometric Neural Processes (GNP), a new class of neural processes which incorporates the geometric information of data samples. Different from existing works, GNP benefits from the data structure for transductive learning using a graph representation. Specifically, GNP first computes the distance of a target point to its neighbors, and then learns a non-linear distance-weighted aggregation scheme over the conditional points. In order to enhance the reliability and compactness of the representation, we borrow the spirit of the information bottleneck. Capturing both the node features and the geometric features of point samples w.r.t. the given context, GNP is more inductive, scalable and robust to the data uncertainty. We demonstrate the stability and versatility of the proposed method for data interpolation, achieving state-of-the-art performance on multifold tasks, including regression, image completion and motion generation.
"

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
