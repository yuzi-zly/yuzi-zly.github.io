---
title: 'Minimizing Link Generation in Constraint Checking for Context Inconsistency Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chuyang Chen
  - Huiyan Wang
  - admin
  - Chang Xu
  - Ping Yu

# Author notes (optional)
author_notes:

date: '2022-11-03T00:00:00Z'
doi: '10.1109/ISSRE55969.2022.00013'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-03T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 2022 IEEE 33rd International Symposium on Software Reliability Engineering
publication_short: ISSRE

abstract: Adaptive applications rely on conditions about their environments (or contexts) to deliver smart services, e.g., location-aware services. Due to inherent noises in environmental sensing and interpretation, there is an increasing demand for guarding the consistency of contexts to avoid application misbehavior, and at the same time minimizing the guarding cost. Existing work has tried to reduce the cost by speeding up the kernel constraint checking module inside the consistency guarding process. Most efforts have been spent on reusing previous checking results or checking constraints in parallel, while leaving untouched one central problem of link generation, the step that consumes a substantially large part of the total time cost for explaining why constraints have been violated. In this paper, we propose a novel technique, MG, to automatically identify and remove redundant link generation, without harming any checking result. We show that MG is sound (always checking correctly) and complete (removing all redundancy). Our experiments with synthesized and real-world consistency constraints reported that compared with existing work, MG achieved significant efficiency improvements on the link generation (tens to hundreds times speedup), and could reduce the total constraint checking time up to 45.4%.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/mg/ISSRE22.pdf'
# url_code: 'https://github.com/yuzi-zly/INFUSE'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: 'publication/infuse/slides.pdf'
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

share: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'featured.jpg'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
