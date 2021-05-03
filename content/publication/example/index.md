---
title: "Training for Multi-resolution Inference Using Reusable Quantization Terms"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Bradley McDanel
- H.T. Kung
- Xin Dong

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *26th ACM International Conference on Architectural Support for Programming Languages and Operating Systems*
publication_short: In *ASPLOS*

abstract: Low-resolution Low-resolution uniform quantization (e.g., 4-bit bitwidth) for both Deep Neural Network (DNN) weights and data has emerged as an important technique for efficient inference. Departing from conventional quantization with a fixed resolution, we describe a novel training approach to support inference at multiple resolutions by reusing a single set of quantization terms. The proposed approach streamlines the training and supports dynamic selection of resolution levels during inference. We evaluate the method on a diverse range of applications including multiple CNNs on ImageNet, an LSTM on Wikitext-2, and YOLO-v5 on COCO. We show that models resulting from our multi-resolution training can support up to 10 resolutions with only a moderate performance reduction (e.g., < 1%) compared to training them individually. Lastly, using an FPGA, we compare our multi-resolution multiplier-accumulator (mMAC) against other conventional MAC designs and evaluate the inference performance.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
