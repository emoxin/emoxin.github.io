---
title: "Contrastive learning of subject-invariant EEG representations for cross-subject emotion recognition"
authors:
- Xinke Shen, Xianggen Liu
- admin
- Dan Zhang, Sen Song
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-04-04"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-04"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Affective Computing*"
publication_short: ""

abstract: "EEG signals have been reported to be informative and reliable for emotion recognition in recent years. However, the inter-subject variability of emotion-related EEG signals still poses a great challenge for the practical applications of EEG-based emotion recognition. Inspired by recent neuroscience studies on inter-subject correlation, we proposed a Contrastive Learning method for Inter-Subject Alignment (CLISA) to tackle the cross-subject emotion recognition problem. Contrastive learning was employed to minimize the inter-subject differences by maximizing the similarity in EEG signkal representations across subjects when they received the same emotional stimuli in contrast to different ones. Specifically, a convolutional neural network was applied to learn inter-subject aligned spatiotemporal representations from EEG time series in contrastive learning. The aligned representations were subsequently used to extract differential entropy features for emotion classification. CLISA achieved state-of-the-art cross-subject emotion recognition performance on our THU-EP dataset with 80 subjects and the publicly available SEED dataset with 15 subjects. It could generalize to unseen subjects or unseen emotional stimuli in testing. Furthermore, the spatiotemporal representations learned by CLISA could provide insights into the neural mechanisms of human emotion processing."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
# #   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
