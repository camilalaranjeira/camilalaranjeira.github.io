---
title: 'Seeing without Looking: Analysis Pipeline for Child Sexual Abuse Datasets'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - João Macedo
  - Sandra Avila
  - Jefersson A. dos Santos
  

year: 2022
date: '2022-06-20T00:00:00Z'
doi: 'https://doi.org/10.1145/3531146.3534636'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In ACM conference on fairness, accountability, and transparency (FAccT 2022)
publication_short: In FAccT 2022

abstract: The online sharing and viewing of Child Sexual Abuse Material (CSAM) are growing fast, such that human experts can no longer handle the manual inspection. However, the automatic classification of CSAM is a challenging field of research, largely due to the inaccessibility of target data that is — and should forever be — private and in sole possession of law enforcement agencies. To aid researchers in drawing insights from unseen data and safely providing further understanding of CSAM images, we propose an analysis template that goes beyond the statistics of the dataset and respective labels. It focuses on the extraction of automatic signals, provided both by pre-trained machine learning models, e.g., object categories and pornography detection, as well as image metrics such as luminance and sharpness. Only aggregated statistics of sparse signals are provided to guarantee the anonymity of children and adolescents victimized. The pipeline allows filtering the data by applying thresholds to each specified signal and provides the distribution of such signals within the subset, correlations between signals, as well as a bias evaluation. We demonstrated our proposal on the Region-based annotated Child Pornography Dataset (RCPD), one of the few CSAM benchmarks in the literature, composed of over 2000 samples among regular and CSAM images, produced in partnership with Brazil’s Federal Police. Although noisy and limited in several senses, we argue that automatic signals can highlight important aspects of the overall distribution of data, which is valuable for databases that can not be disclosed. Our goal is to safely publicize the characteristics of CSAM datasets, encouraging researchers to join the field and perhaps other institutions to provide similar reports on their benchmarks.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
#   - Large Language Models

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://facctconference.org/static/pdfs_2022/facct22-3534636.pdf'
url_code: 'https://github.com/camilalaranjeira/seeing_without_looking'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://drive.google.com/file/d/1MjYDpvyBMzTO_HEGDsUqNDx4kwe5RcFw/view?usp=share_link'
url_source: ''
url_video: 'https://drive.google.com/file/d/103GsHA_cQAxZRfkpAEsaGY6OE2qL0Y7C/view?usp=share_link'

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
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
