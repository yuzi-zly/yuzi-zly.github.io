---
title: 'INFUSE: Towards Efficient Context Consistency by Incremental-Concurrent Check Fusion'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Huiyan Wang
  - Chang Xu
  - Ping Yu

# Author notes (optional)
author_notes:

date: '2023-03-18T00:00:00Z'
doi: '10.1109/ICSME55016.2022.00025'

# Schedule page publish date (NOT publication's date).
publishDate: '2022'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In 2022 IEEE International Conference on Software Maintenance and Evolution
publication_short: In ICSME'22

abstract: Nowadays applications are getting increasingly attractive by being capable of adapting their behaviors based on their understanding to running environments (a.k.a. contexts). However, such capability can be subject to illness or even unexpected crash, when contexts, for suffering environmental noises, become inaccurate or even conflict with each other. Fortunately, various constraint checking techniques have been proposed to validate contexts against consistency constraints, in order to guard context consistency for applications in a timely manner. However, with the growth of environmental dynamics and context volume, it is getting more and more challenging to check context consistency in time. In this paper, we propose a novel approach, INFuse, to soundly fuse together two lines of techniques, namely, incremental checking and concurrent checking, for efficient constraint checking. Realizing such check fusion has to address the challenges rising from the gap between the micro analysis for reusable elements in incremental checking and the macro collection of parallel tasks in concurrent checking. INFuse solves the challenges by automatically deciding maximal concurrent boundaries for context changes under checking (i.e., what-correctness problem), and soundly fusing incremental and concurrent checking for context consistency (i.e., how-correctness problem), with theoretical guarantees. Our experimental evaluation with real-world data shows that INFuse could improve constraint checking efficiency by 18.6x–171.1x, as compared with existing state-of-the-art techniques.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/infuse/infuse.pdf'
url_code: 'https://github.com/yuzi-zly/INFUSE'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
url_slides: 'publication/infuse/slides.pdf'
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
