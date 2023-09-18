---
# Leave the homepage title empty to use the site title
title:
date: 2023-03-18
type: landing

sections:
  - block: v1/about
    id: about
    content:
      username: admin 
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ph.D. Student
          company: SPAR Group, Computer Science and Technology, Nanjing University (NJU)
          company_url: 'https://cs.nju.edu.cn/ics/spar/index.html'
          # company_logo: org-x
          location: Nanjing, Jiangsu, China
          date_start: '2021-09-01'
          date_end: ''
          description: Under the supervision of Assistant Researcher [Huiyan Wang](http://www.why.ink:8080/) and Prof. [Chang Xu](https://cs.nju.edu.cn/changxu/index.htm).
        - title: Undergraduate Student
          company: Kuang Yaming Honors School, Nanjing University (NJU)
          company_url: 'https://dii.nju.edu.cn/main.htm'
          # company_logo: org-gc
          location: Nanjing, Jiangsu, China
          date_start: '2017-09-01'
          date_end: '2021-06-19'
          # description: |2-
          #     Responsibilities include:

          #     * Analysing
          #     * Modelling
          #     * Deploying
    design:
      columns: '1'
  - block: collection
    id: publication
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '1'
      view: citation
  - block: accomplishments
    content:
      title: Honors & Awards
      subtitle: ''
      text: ''
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: '2006'
      # Accomplishments.
      #   Add/remove as many `items` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: The Elite Scholarship Second Class (博士研究生英才奖学金二等奖)
          date_start: '2022-12-31'
          organization: Nanjing University, China
        - title: President Scholarship for Doctoral Students (博士研究生校长特别奖学金)
          date_start: "2021-12-31"
          organization: Nanjing University, China
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: markdown
    content:
      title: Teaching
      text: |-
        - 2023 Spring, TA, Principles and Techniques of Compiler (taught by Prof. Chang Xu)
        - 2022 Spring, TA, Principles and Techniques of Compiler (taught by Prof. Chang Xu)
    design:
      columns: '1'
  # - block: portfolio
  #   id: presentations
  #   content:
  #     title: Presentations
  #     filters:
  #       folders:
  #         - presentation
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       # - name: All
  #       #   tag: '*'
  #       - name: Paper Symposium
  #         tag: Paper Symposium
  #       - name: Other
  #         tag: Other
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: list
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     # text: |-
  #     #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
  #     email: zly@smail.nju.edu.cn
  #     # phone: 888 888 88 88
  #     # appointment_url: 'https://calendly.com'
  #     # address:
  #     #   street: 450 Serra Mall
  #     #   city: Stanford
  #     #   region: CA
  #     #   postcode: '94305'
  #     #   country: United States
  #     #   country_code: US
  #     # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     contact_links:
  #       - icon: qq
  #         icon_pack: fab
  #         name: 835575882
  #       - icon: weixin
  #         icon_pack: fab
  #         name: yuziyaojiayou
  #       - icon: github
  #         icon_pack: fab
  #         name: yuzi-zly
  #         link: https://github.com/yuzi-zly
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     # form:
  #     #   provider: netlify
  #     #   formspree:
  #     #     id:
  #     #   netlify:
  #     #     # Enable CAPTCHA challenge to reduce spam?
  #     #     captcha: false
  #   design:
  #     columns: '1'
---
