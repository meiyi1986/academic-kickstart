+++
# Project title.
title = "Large Scale Global Optimisation"
weight = 3
math = true

# Date this page was created.
date = 2019-02-21T00:00:00

# Project summary to display on homepage.
summary = """
Design effective divide-and-conquer algorithms to solve large scale global optimisation.
"""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = [""]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

  # Show image only in page previews?
  preview_only = true
+++

Most real-world optimisation problems are very large. For example, in a vehicle routing problem, there can be thousands of customers to be served. In addition, these problems have many local optima, and it is easy to be trapped into poor local optima.

Large scale global optimisation is a very challenging problem that seeks for the "global optimum" in a very large search space. Although evolutionary computation algorithms have shown premise in solving the hard optimisation problems, their performance is usually restricted into small or medium problem sizes. When the problem size grows large, the performance of the algorithms can deteriorate rapidly ("curse of dimensionality").

To address this challenge, we aim to develop novel divide-and-conquer approaches to reduce the search space without excluding the promising solutions. We have achieved success on the benchmark functions and real-world applications such as the arc routing problem, travelling thief problem, and warehouse layout design.

