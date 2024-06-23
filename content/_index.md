---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: 2006-01
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Researcher
          company: Fujitsu Limited.
          company_url: ''
          company_logo: 
          location: 
          date_start: '2023-04-01'
          date_end: ''
          description: Research NLP at Artificial Intelligence Lab.
    design:
      columns: '2'
  - block: experience
    content:
      title: Internships
      date_format: 2006-01
      items:
        - title: Internship(Microservice Development)
          company: Money Forward,Inc.
          company_url: ''
          company_logo: 
          location: 
          date_start: '2021-09-15'
          date_end: '2021-09-24'
          description: Microservice Development by Golang
        - title: Internship(Natural Language Processing Course)
          company: FORCIA, Inc.
          company_url: ''
          company_logo: 
          location: 
          date_start: '2021-08-16'
          date_end: '2021-08-20'
          description: Automatic tagging of products using natural language processing https://blog.altair626.work/2021summer_forcia/
        - title: Internship(Data Science Cource)
          company: GMO Internet Group, Inc. 次世代システム研究室(Next Generation Systems Laboratory)
          company_url: ''
          company_logo: 
          location: 
          date_start: '2020-08-20'
          date_end: '2020-09-04'
          description: Improving ad-tech performance using advertising service logs
        - title: Researcher Intern
          company: FOVE inc.
          company_url: ''
          company_logo: 
          location: 
          date_start: '2018-12-12'
          date_end: '2019-04-22'
          description: Improving eye tracking
    design:
      columns: '2'
  - block: experience
    content:
      title: History
      date_format: 2006-01
      items:
        - title: worker
          company: 
          company_url: ''
          company_logo: 
          location: 
          date_start: '2023-04-01'
          date_end: ''
          description: 
        - title: 東京工業大学(Tokyo Institute of Technology)
          company: 
          company_url: ''
          company_logo: 
          location: 
          date_start: '2017-04-01'
          date_end: '2023-03-31'
          description: |2-
            * 5類
            * Bachelor: Department of Computer Science, School of Computing
            * Master: Artificial Intelligence Course, Department of Computer Science, School of Computing
        - title: 開成高校(Kaisei Senior High School)
          company: 
          company_url: ''
          company_logo: 
          location: 
          date_start: '2014-04-01'
          date_end: '2017-03-31'
          description: 
        - title: 神奈川県横浜市生まれ
          company: 
          company_url: ''
          company_logo: 
          location: 
          date_start: '1998-06-26'
          date_end: ''
          description: 
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Qualifications'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: 2006-01
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: ''
          date_start: '2017-11-15'
          description: ''
          icon: 
          organization: 
          organization_url: 
          title: 応用情報技術者 (Applied Information Technology Engineer)
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2018-03-09'
          description: ''
          icon: 
          organization: 
          organization_url: 
          title: 危険物取扱者 乙種1,3,4類 (Hazardous Materials Engineer ClassB-Group1,3,4)
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2023-06-30'
          description: ''
          icon: 
          organization: 
          organization_url: 
          title: 第三種電気主任技術者 (The Third Class Electric Chief Engineer)
          url: ''
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: 2006-01
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.youtube.com/watch?v=8VOi8Uy86qU
          date_end: ''
          date_start: '2020-09-19'
          description: '東工大デジタル創作同好会traPにてオンライン開催 資料:https://drive.google.com/file/d/1rtMVKDOR1DbzYTfwx5a__q8Vpu2VfFYi/view?usp=sharing'
          icon: 
          organization: 
          organization_url: 
          title: CTF Crypto講習会 2020
          url: ''
        - certificate_url: https://www.youtube.com/watch?v=CjhewAoX6-k
          date_end: ''
          date_start: '2020-06-28'
          description: '東工大デジタル創作同好会traPにてオンライン開催'
          icon: 
          organization: 
          organization_url: 
          title: CTF講習会 introduction 2020
          url: ''
        - certificate_url: https://atcoder.jp/contests/jsc2019-final
          date_end: ''
          date_start: '2019-09-29'
          description: '予選211位、決勝125位/197人'
          icon: 
          organization: 
          organization_url: 
          title: AtCoder 第一回日本最強プログラマー学生選手権決勝進出
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2019-07-01'
          description: 'チーム参加 108位'
          icon: 
          organization: 
          organization_url: 
          title: ICPC2019国内予選
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2018-12-01'
          description: 'チーム参加 578点・20位'
          icon: 
          organization: 
          organization_url: 
          title: ICTトラブルシューティングコンテスト(ICTSC)2018 二次予選
          url: ''
        - certificate_url: https://gist.github.com/Vegctrp/304467af12e950eab8cfd136c47e3260
          date_end: '2023-03-31'
          date_start: '2017-04-01'
          description: ''
          icon: 
          organization: 
          organization_url: 
          title: 大学/大学院取得単位(github gist)
          url: ''
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Self-Learnings'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: 2006-01
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: '2021-03-17'
          date_start: '2021-02-15'
          description: ''
          icon: 
          organization: 
          organization_url: 
          title: 圏論をやりました
          url: 'https://wiki.altair626.work/studies/math/Category_wa'
        - certificate_url: 
          date_end: '2020-07-01'
          date_start: '2020-04-01'
          description: ''
          icon: 
          organization: 
          organization_url: 
          title: 言語処理100本ノック 2020年版
          url: 'https://github.com/Vegctrp/nlp100_2020'
        - certificate_url: 
          date_end: '2021-06-04'
          date_start: '2020-03-31'
          description: ''
          icon: 
          organization: 
          organization_url: 
          title: 雪江代数2を完走しました
          url: 'https://wiki.altair626.work/studies/math/RingTheory'
        - certificate_url: 
          date_end: '2019-09-01'
          date_start: '2019-08-01'
          description: ''
          icon: 
          organization: 
          organization_url: 
          title: 画像処理100本ノック
          url: 'https://github.com/Vegctrp/pic100knock'
        - certificate_url: 
          date_end: '2019-08-01'
          date_start: '2017-04-01'
          description: ''
          icon: 
          organization: 
          organization_url: 
          title: 言語処理100本ノック 2015
          url: 'https://github.com/Vegctrp/lang100knock'
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: m-keisuke[at]fujitsu.com / kmiyazaki626[at]gmail.com 
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Veg_ctrp'
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
