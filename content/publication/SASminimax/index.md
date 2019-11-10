---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Minimax Approach to Sensor Fusion for Intrusion Detection"
authors: ["Matthew Pugh"]
date: 2015-03-21T18:39:50-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-10-21T18:39:50-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Sensor Applications Symposium"
publication_short: ""

abstract: "The goal of sensor fusion is to combine the information obtained by various sensors to make better decisions. By better, it is meant that the sensor fusion algorithm provides, for example, better detectability or lower false alarm rates compared to decisions based upon a single sensor. This work is motivated by combining the data gathered by multiple passive infrared (PIR) sensors to detect intrusions into a room. Optimal decision theoretic approaches typically include statistical models for both the background (non-event) data, and intrusion (event) data. Concurrent work by the author has shown that by appropriately processing multiple PIR data streams, a statistic can be computed which has a known distribution on the background data. If the distribution of the statistic during an event is known, optimal decision procedures could be derived to perform sensor fusion. It is shown, however, that it is difficult to statistically model the event data. This paper thus focuses on using minimax theory to derive the worst-case event distribution for minimizing Bayes risk. Because of this, using the minimax distribution as a surrogate for the unknown true distribution of the event data provides a lower bound on risk performance. The minimax formulation is very general and will be used to consider loss functions, the probability of intrusions events and consider nonbinary decisions."

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
url_slides: "Minimax_Presentation.pdf"
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
