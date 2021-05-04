---
title: "Term Quantization:Furthering Quantization at Run Time"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Sai Qian Zhang*
- H.T. Kung*
- Bradley McDanel*

# Author notes (optional)
#author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2020-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ACM/IEEE International Conference for High Performance Computing, Networking, Storage and Analysis (SC)*
publication_short: In *ACM/IEEE SC*

abstract: We present a novel technique, called Term Quantization (TQ), for furthering quantization at run time for improved computational efficiency of deep neural networks (DNNs) already quantized with conventional quantization methods. TQ operates on power-of-two terms in expressions of values. In computing a dot-product computation, TQ dynamically selects a fixed number of largest terms to use from values of the two vectors. By exploiting weight and data distributions typically present in DNNs, TQ has a minimal impact on DNN model performance (e.g., accuracy or perplexity). We use TQ to facilitate tightly synchronized processor arrays, such as systolic arrays, for efficient parallel processing. We evaluate TQ on an MLP for MNIST, multiple CNNs for ImageNet and an LSTM for Wikitext-2. We demonstrate significant reductions in inference computation costs (between 3-10×) compared to conventional uniform quantization for the same level of model performance.


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
  caption: ''
  focal_point: "none"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
