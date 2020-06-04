+++
# Project title.
title = "CRISPR"

# Date this page was created.
date = 2019-02-14T00:00:00

# Project summary to display on homepage.
summary = "New method that uses CRISPR-cas9 to specifically cut the host 18S rRNA gene and reveals host-associated eukaryotic microbiomes"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["microbiome", "methodology", "CRISPR"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "example-slides"

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/kevinzhong2006"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "Photo by rawpixel on Unsplash"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

Micro-eukaryotic community characterization using deep-amplicons sequencing has been a routine technique in microbiome study in examining health, discovering pathogens, and addressing ecological and evolutionary questions in field of marine biology. A main challenge lies in reducing eukaryotic host signature when using universal 18S rRNA gene markers that capture conservative regions of eukaryotes. Various Polymerase chain reaction (PCR) manipulation in tandem with host-specific blocking primers can be used. However, blocking primers usually target within the universal primers, which could reduce the phylogenetic resolution due to such short fragment, and its application is limited to certain host range. Hence, we report a versatile method that use laboratory-designed and synthesized guiding RNA (gRNA) to guide CRISPR-cas9 to cut specifically the host 18S rDNA, but not microeukaryotes. As a result, the protists and fungal 18S amplicons could be enriched in the sequencing data. This method, termed as CRISPR-Cas Selective Amplicon Sequencing (CCSAS), adds a promising tool to study eukaryotic microbiomes of complex system, offering a broad implication in pathogens diagnosis, symbiotic study, microbiome therapy, etc. 

This CRISPR work is part of "The shellfish gene" project funded by [The Gordon and Betty Moore Foundation](https://www.foundationguide.org/foundations-trust/gordon-betty-moore-foundation/) during year 2017 - 2021, with aime to investigate the eukaryotic microbiome associated to pacific oysters to understand the microbial causis of high mortality of osyter spates in hatchy in BC. The CRISPR work lead to one R packages, a gRNA-target-site database, and two articles publications. 


