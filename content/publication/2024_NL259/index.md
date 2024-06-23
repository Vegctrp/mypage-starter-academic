---
title: 'ソフトウェア設計書群を外部知識源とする RAG のための検索性能改善の検討 (main author)'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:
  - 'main author'

date: '2024-03-10T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *第259回自然言語処理研究発表会*
publication_short: In *NL259*

abstract: In existing Retrieval-Augmented Generation(RAG) method, the top few results of the retrieval system are used, and the selection of information from these results is typically managed by a large-scale language model(LLM). However, in certain use cases, only the top result should be used as input for the LLM. For instance, when using complex, semi-structured software design documents as an external knowledge source, the LLM may struggle to comprehend and select from multiple document fragments. This can lead to incorrect answers if multiple results are used as input. In this study, we propose a method to improve the recall@1 performance in RAG that uses a group of software design documents as an external knowledge source. We interpret the search task as a multiple-choice question, with the top few fragments from the existing search system's results serving as the choices, and solve this problem using an LLM. We evaluated both the existing and the proposed method using a search task on a group of software design documents, measuring performance with the recall@1 metric.

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Program of NL259
  url: https://www.ipsj.or.jp/kenkyukai/event/nl259.html
- name: 情報処理学会電子図書館
  url: https://ipsj.ixsq.nii.ac.jp/ej/index.php?active_action=repository_view_main_item_detail&page_id=13&block_id=8&item_id=232881&item_no=1

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

従来の Retrieval-Augmented Generation（RAG）において，検索システムの結果は上位数件が採用され，検索システムの結果からの情報の取捨選択は大規模言語モデル（LLM）に行わせることが一般的である．しかし，ユースケースによっては検索結果として最上位の一件のみを LLM の入力に用いたい場合が存在する．長大かつ複雑に半構造化されたソフトウェア設計書の集まりを外部知識源とする場合，複数のソフトウェア設計書の断片を LLM が適切に理解して取捨選択を行うことは難しく，最上位の一件のみを入力に用いないと誤答につながることが考えられる．そこで本研究では，ソフトウェア設計書群を外部知識源とする RAG において，検索の recall@1 性能を向上させる手法を提案する．提案手法は，既存検索システムの検索結果である上位数件のソフトウェア設計書の断片を選択肢とする多肢選択式問題に帰着させ，LLM を用いて解くものである．実験では従来手法と提案手法を用いてソフトウェア設計書群からの検索タスクを実施し，recall@1 指標により手法を評価する．