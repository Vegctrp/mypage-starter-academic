---
title: '複数の参照訳を考慮したニューラル機械翻訳モデルの学習手法 (main author)'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:
  - 'main author'

date: '2023-03-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *言語処理学会第29回年次大会*
publication_short: In *NLP2023*

abstract: 文の翻訳では訳者や文脈などの条件により異なる訳文が期待され，機械翻訳タスクのベンチマークに用いられる対訳コーパス内にも一つの原文に複数の参照訳が対応している例が多く存在する．一方で既存の機械翻訳モデルの学習手法ではこうしたコーパス内の構造は明示的には用いられない．そこで本研究では，コーパス内の原文が複数の参照訳を持っているという情報を，機械翻訳モデルの学習に明示的に用いる手法を提案する．評価実験において，提案手法を用いて学習したモデルは旧来の最尤誤差損失のみを用いたモデルに劣る結果となったが，提案手法が文レベル最適輸送損失を用いて学習するモデルの性能向上には寄与することが示された．

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Program of NLP2023
  url: https://www.anlp.jp/proceedings/annual_meeting/2023/#P10-4

url_pdf: 'https://www.anlp.jp/proceedings/annual_meeting/2023/pdf_dir/P10-4.pdf'
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


