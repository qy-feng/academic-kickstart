---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning Geometric Stereo-Representation from Single-View with Mutual Information Maximization"
authors: [Qianyu Feng, Yawei Luo, Keyang Luo, Yi Yang]
date: 2020-11-20T10:46:33+10:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-20T10:46:33+10:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Preprint"
publication_short: ""

abstract: "From a cardinal view to subtle observation, it is easy for humans to grasp the essential information with intentions. However, it is hard to fulfill the delicate tasks, e.g., segmentation, 3D reconstruction, with only a global representation. In this work, we show the potential of reconstructing a shape with only a single view of an object. Previous methods tackle this problem with the adversarial learning of the global feature of images and the volumetric shapes, which might lead to high-entangled representation. Our method, Max-Info Domain-Adaptive (MIDA) Network, investigates the leverage of the local structure by estimating and maximizing the mutual information with the global representation and thus enhance its distinctiveness. Further on, with the knowledge from the priors, we can learn a distribution with desired characteristics, a.k.a., 3D shape in our case, to better control the local and global representation from the single-view image for reconstructing its shape. We show that with the maximization of mutual information between local structure and the global embeddings, our model is robust against the noise from the background and also more expressive in building the 3D shapes. It is also demonstrated that the proposed method outperforms the state-of-the-art methods by a large margin on several datasets, with IoU score of 0.292 on Pix3D and 0.349 on PASCAL 3D+.
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
