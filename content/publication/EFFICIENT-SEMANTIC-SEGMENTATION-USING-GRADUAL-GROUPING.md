+++
title = "Efficient Semantic Segmentation using Gradual Grouping"

# Date first published.
date = "2018-07-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Nikitha Vallurapalli<sup>1</sup>", "Sriharsha Annamaneni<sup>1</sup>", "Girish Varma<sup>1</sup>", "C V Jawahar<sup>1</sup>", "Manu Mathew", "Soyeb Nagori" ]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In IEEE Embeded Vision Workshop, CVPR'18"
publication_short = "In CVPR"

# Abstract and optional shortened version.
abstract = "Deep CNNs for semantic segmentation have high memory and run time requirements. Various approaches have been proposed to make CNNs efficient like grouped, shuffled, depth-wise separable convolutions. We study the effectiveness of these techniques on a real-time semantic segmentation architecture like ERFNet for improving runtime by iver 5X. We apply these techniques to CNN layers partially or fully and evaluate the testing accuracies on Cityscapes dataset. We obtain accuracy vs parameters/FLOPs trade offs, giving accuracy scores for models that can run under specified runtime budgets. *We further propose a novel training procedure which starts out with a dense convolution but gradually evolves towards a grouped convolution. We show that our proposed training method and efficient architecture design can improve accuracies by over 8% with depthwise separable convolutions applied on the encoder of ERFNet and attaching a light weight decoder. This results in a model which has a 5X improvement in FLOPs while only suffering a 4% degradatioon in accuracy with respect to ERFNet*"
abstract_short = "We further propose a novel training procedure which starts out with a dense convolution but gradually evolves towards a grouped convolution. We show that our proposed training method and efficient architecture design can improve accuracies by over 8% with depthwise separable convolutions applied on the encoder of ERFNet and attaching a light weight decoder. This results in a model which has a 5X improvement in FLOPs while only suffering a 4% degradatioon in accuracy with respect to ERFNet"

# Featured image thumbnail (optional)
image_preview = "1.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = "pdf/Paper1.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "https://drive.google.com/file/d/16WnXJbOaqgd6MPw6cvo923DYyhdeN6j_/view?usp=sharing"
url_video = ""
url_poster = "https://drive.google.com/file/d/1NnO7Zd_IF4mXSIhZZVZVDwslxWU79XSQ/view?usp=sharing"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "1.png"
#caption = "My caption 😄"

+++
