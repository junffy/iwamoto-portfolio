---
title: 'Daisy-chained Systolic Array and Reconfigurable Memory Space for Narrow Memory Bandwidth'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Renyuan Zhang
  - Yasuhiko Nakashima

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2019'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: A paradigm shift toward edge computing infrastructures that prioritize small footprint and scalable/easy-to-estimate performance is increasing. In this paper, we propose the following to improve the footprint and the scalability of systolic arrays (1) column multithreading for reducing the number of physical units and maintaining the performance even for back-to-back floating-point accumulations; (2) a cascaded peer-to-peer AXI bus for a scalable multichip structure and an intra-chip parallel local memory bus for low latency; (3) multilevel loop control in any unit for reducing the startup overhead and adaptive operation shifting for efficient reuse of local memories. We designed a systolic array with a single column × 64 row configuration with Verilog HDL, evaluated the frequency and the performance on an FPGA attached to a ZYNQ system as an AXI slave device, and evaluated the area with a TSMC 28nm library and memory generator and identified the following (1) the execution speed of a matrix multiplication/a convolution operation/a light-field depth extraction, whose size larger than the capacity of the local memory, is 6.3× / 9.2× / 6.6× compared with a similar systolic array (EMAX); (2) the estimated speed with a 4-chip configuration is 19.6× / 16.0× / 8.5×; (3) the size of a single-chip is 8.4 mm2 (0.31× of EMAX) and the basic performance per area is 2.4×.

# Summary. An optional shortened abstract.
abstruct: ''

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.jstage.jst.go.jp/article/transinf/E103.D/3/E103.D_2019EDP7144/_pdf/-char/ja'
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
  caption: 
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---



