---
title: 'The generations of classical correlations via quantum schemes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhenyu Chen
  - Lijinzhi Lin
  - Xiaodie Lin
  - Zhaohui Wei
  - Penghui Yao

# Author notes (optional)
author_notes:
  - 'Alphabetical ordering'

date: '2024-04-19T00:00:00Z'
doi: '10.1109/TIT.2024.3391341'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-19T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Information Theory*
publication_short: In *IEEE TIT*

abstract: Suppose two separated parties, Alice and Bob, share a bipartite quantum state or a classical correlation called a
seed, and they try to generate a target classical correlation by performing local quantum or classical operations on the seed, i.e., any communications are not allowed. We consider the following fundamental problem about this setting: whether Alice and Bob can use a given seed to generate a target classical correlation. We show that this problem has rich mathematical structures. Firstly, we prove that even if the seed is a pure bipartite state, the above decision problem is already NP-hard and a similar conclusion can also be drawn when the seed is also a classical correlation, implying that this problem is hard to solve generally. Furthermore, we prove that when the seed is a pure quantum state, solving the problem is equivalent to finding out whether the target classical correlation has some diagonal form of positive semi-definite factorizations that matches the seed pure state, revealing an interesting connection between the current problem and optimization theory. Based on this observation and other insights, we give several necessary conditions where the seed pure state has to satisfy to generate the target classical correlation, and it turns out that these conditions can also be generalized to the case that the seed is a mixed quantum state. Lastly, since diagonal forms of positive semi-definite factorizations play a crucial role in solving the problem, we develop an algorithm that can compute them for an arbitrary classical correlation, which has decent performance on the cases we test.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Correlation generation
  - Local state transformation
  - PSD-rank
  - Diagonal form of PSD factorization

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  # - example
  []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
