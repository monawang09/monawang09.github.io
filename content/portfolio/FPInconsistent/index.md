---
title: "FP-Inconsistent: Detecting Evasive Bots using Browser Fingerprint Inconsistencies"
authors:
- Hari Venugopalan
- Shaoor Munir
- Shuaib Ahmed
- admin
- Samuel T. King
- Zubair Shafiq
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-06-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "In Submittion to ACM Internet Measurement Conference 2025"
publication_short: "In Submittion to *IMC 2025*"

# abstract: To systematically investigate evasive bots, we deploy a honey site incorporating two anti-bot services (DataDome and BotD) and solicit bot traffic from 20 different bot services that purport to sell “realistic and undetectable traffic.” Across half a million requests from 20 different bot services on our honey site, we find an average evasion rate of 52.93% against DataDome and 44.56% evasion rate against BotD.

# Summary. An optional shortened abstract.
summary: To systematically investigate evasive bots, we deploy a honey site incorporating two anti-bot services and solicit bot traffic from 20 different bot services that purport to sell “realistic and undetectable traffic.” 

tags:
- Security
- Fingerprint
- Large-scale Analysis
featured: true 

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2406.07647v1
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
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

As browser fingerprinting is increasingly being used for bot detection, bots have started altering their fingerprints for evasion. We conduct the first large-scale evaluation of evasive bots to investigate whether and how altering fingerprints helps bots evade detection. To systematically investigate evasive bots, we deploy a honey site incorporating two anti-bot services (DataDome and BotD) and solicit bot traffic from 20 different bot services that purport to sell “realistic and undetectable traffic.” Across half a million requests from 20 different bot services on our honey site, we find an average evasion rate of 52.93% against DataDome and 44.56% evasion rate against BotD. Our comparison of fingerprint attributes from bot services that evade each anti-bot service individually as well as bot services that evade both shows that bot services indeed alter different browser fingerprint attributes for evasion. Further, our analysis reveals the presence of inconsistent fingerprint attributes in evasive bots. Given evasive bots seem to have difficulty in ensuring consistency in their fingerprint attributes, we propose a data-driven approach to discover rules to detect such inconsistencies across space (two attributes in a given browser fingerprint) and time (a single attribute at two different points in time). These rules, which can be readily deployed by anti-bot services, reduce the evasion rate of evasive bots against DataDome and BotD by 48.11% and 44.95% respectively.
