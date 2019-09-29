---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Going Deeper into Embedding Learning for Video Object Segmentation"
authors: [Zongxin Yang, Peike Li, Qianyu Feng, Yunchao Wei, Yi Yang]
date: 2019-09-29T10:46:33+10:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-09-29T10:46:33+10:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Computer Vision Workshop (ICCVW) 2019"
publication_short: ""

abstract: "In  this  paper,  we  investigate  the  principles  of  consis-tent  training,  between  given  reference  and  predicted  se-quence,  for better embedding learning of semi-supervisedvideo object segmentation.  To accurately segment the tar-get  objects  given  the  mask  at  the  first  frame,  we  realizethat  the  expected  feature  embeddings  of  any  consecutiveframes  should  satisfy  the  following  properties: 1)globalconsistency in terms of both foreground object(s) and back-ground; 2)robust local consistency under a various objectmoving rate; 3)environment consistency between the train-ing and inference process; 4)receptive consistency betweenthe  receptive  fields  of  network  and  the  variable  scales  ofobjects;5)sampling consistency between foreground andbackground pixels to avoid training bias.  With the princi-ples in mind,  we carefully design a simple pipeline to liftboth accuracy and efficiency for video object segmentationeffectively. With the ResNet-101 as the backbone, our singlemodel achieves a J&F score of 81.0% on the validation setof Youtube-VOS benchmark without any bells and whistles.By applying multi-scale & flip augmentation at the testingstage, the accuracy can be further boosted to 82.4%. Codewill be made available."

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
