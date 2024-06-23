---
title: '大規模言語モデルを活用したソフトウェア設計書自動レビュー手法の検討 (co-author)'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:
  - 'co-author'

date: '2023-11-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *第215回ソフトウェア工学研究発表会*
publication_short: In *SIG-SE215*

abstract: In recent years, the technology of Large Language Models (LLM) has advanced and their application has rapidly spread across various industries. Against this background, attempts have been made to utilize these models in the field of software engineering as well. In this study, we explored a new approach to automate the review process of software design documents by using LLM. We first conducted a case study on design document reviews based on actual design documents used in software development, and identified the issues specific to the use of LLM in the review of software design documents. Among the issues identified, this study focused on developing new techniques to make LLM comprehend complex software design documents that include table data. We then evaluated the consistency of design items and descriptions across different design documents. Our results confirmed that LLM can be utilized to review and identify inconsistencies in software design documents.

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Program of SIG-SE215
  url: https://www.ipsj.or.jp/kenkyukai/event/se215.html
- name: 情報処理学会電子図書館
  url:  https://ipsj.ixsq.nii.ac.jp/ej/index.php?active_action=repository_view_main_item_detail&page_id=13&block_id=8&item_id=230483&item_no=1

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

大規模言語モデル（LLM）技術の発展に伴い，様々な業界でその活用が急速に普及している．このような背景の下，ソフトウェア工学の分野でも，これらのモデルの活用が試みられている．本研究では，LLM を活用してソフトウェア設計書のレビュー工程を自動化する新たなアプローチの検討を行った．まずソフトウェア開発の現場で実際に使用されている設計書を基に，設計書レビューのケーススタディを行いながら，LLM を活用する場合における課題の抽出を行った．抽出した課題のうち，今回は特に LLM に表データを含む複雑な設計書を理解させる方法について新たに技術開発を行い，設計書間における設計項目や記述内容の整合性の観点で評価実験を行った．その結果，設計書間の不整合箇所について LLM を活用する事でレビュー指摘が可能である事を確認した．