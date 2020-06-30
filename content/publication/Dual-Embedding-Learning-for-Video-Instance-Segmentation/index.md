---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Dual Embedding Learning for Video Instance Segmentation"
authors: [Qianyu Feng, Zongxin Yang, Peike Li, Yunchao Wei, Yi Yang]
date: 2019-09-29T10:46:33+10:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-09-29T10:46:33+10:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Computer Vision (ICCV) Workshop 2019"
publication_short: ""

abstract: ""

# Summary. An optional shortened abstract.
summary: "In this paper, we propose a novel framework to gener-ate high-quality segmentation results in a two-stage style,aiming at video instance segmentation task which requiressimultaneous  detection,  segmentation  and  tracking  of  in-stances. To address this multi-task efficiently, we opt to firstselect high-quality detection proposals in each frame.  Thecategories of the proposals are calibrated with the globalcontext of video.  Then, each selected proposal is extendedtemporally by a bi-directional Instance-Pixel Dual-Tracker(IPDT) which synchronizes the tracking on both instance-level  and  pixel-level.   The  instance-level  module  concen-trates on distinguishing the target instance from other ob-jects while the pixel-level module focuses more on the lo-cal feature of the instance.  Our proposed method achieveda  competitive  result  of  mAP  45.0%  on  the  Youtube-VOSdataset, ranking the 3rd in Track 2 of the 2nd Large-scaleVideo Object Segmentation Challenge."

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

url_pdf: https://openaccess.thecvf.com/content_ICCVW_2019/papers/YouTube-VOS/Feng_Dual_Embedding_Learning_for_Video_Instance_Segmentation_ICCVW_2019_paper.pdf
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
