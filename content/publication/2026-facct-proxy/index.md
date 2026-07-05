---
title: 'Classifying by Proxy: Explainable and Reproducible Ensemble of Proxy Tasks for Child Sexual Abuse Imagery Classification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Clara Ernesto
  - Carlos Caetano 
  - Sandra Avila
  - João Macedo
  - admin
  - Leo Sampaio Ferraz Ribeiro

year: 2026
date: '2026-06-25T00:00:00Z'
doi: '10.1145/3805689.3806745'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In 2026 ACM Conference on Fairness, Accountability, and Transparency
publication_short: In FAccT '26

abstract: Child Sexual Abuse Imagery (CSAI) classification systems are needed solutions for lessening the psychological impacts often felt by law enforcement agents responsible for evaluating these materials and for efficient removal of these materials from the web. However, due to the nature of the task, researching and developing such systems is not a trivial endeavor. The images are highly sensitive, and the related datasets are under restrictive access regimes, which means most studies in the area are not reproducible or distributable and are therefore hard to compare and validate. More concerning still, most models for this task today lack an aspect often desired by law enforcement agents: explainability. In this paper, we apply an ensemble of Proxy Tasks — tasks that correlate to CSAI classification — yielding improvements in reproducibility, explainability, and security for distribution. This concept is applied for the first time to real CSAI, with a novel selection of relevant Proxy Tasks (selected from the CSAI literature) and training adaptations to the original framework. Our final model achieves competitive results, yielding 91.9% balanced accuracy on the RCPD dataset with the best Proxy Task combination. We furthermore contrast these results with the best-in-class representation learning model, DINO, and show that our ensemble improves accuracy and provides explanations for its classification results, a feature that a single deep learning model can seldom provide.

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

url_pdf: 'https://dl.acm.org/doi/epdf/10.1145/3805689.3806745'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
