---
title: 'On modeling context from objects with a long short-term memory for indoor scene recognition'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Anisio Lacerda
  - Erickson R Nascimento
  

year: 2019
date: '2019-10-28T00:00:00Z'
doi: '10.1109/SIBGRAPI.2019.00041'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Conference on Graphics, Patterns and Images (SIBGRAPI 2019)
publication_short: In SIBGRAPI 2019

abstract: Recognizing indoor scenes is still regarded an open challenge on the Computer Vision field. Indoor scenes can be well represented by their composing objects, which can vary in angle, appearance, besides often being partially occluded. Even though Convolutional Neural Networks are remarkable for image-related problems, the top performances on indoor scenes are from approaches modeling the intricate relationship of objects. Knowing that Recurrent Neural Networks were designed to model structure from a given sequence, we propose representing an image as a sequence of object-level information in order to feed a bidirectional Long Short-Term Memory network trained for scene classification. We perform a Many-to-Many training approach, such that each element outputs a scene prediction, allowing us to use each prediction to boost recognition. Our method outperforms RNN-based approaches on MIT67, an entirely indoor dataset, while also improved over the most successful methods through an ensemble of classifiers.

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

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8919780'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://drive.google.com/file/d/1x-Y2j8ta_3RGPqpDkyXfQsZA96TpKHen/view?usp=share_link'
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
