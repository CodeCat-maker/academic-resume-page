---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Tom Wang
      username: admin
    design:
      css_style: ""
      background:
        image:
          filename: mountains.png
          size: contain
          position: bottom
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
        - title: Product Manager Intern
          company: Tianjin Jinminjia Technology Co., Ltd.
          location: China
          date_start: "2023-03-01"
          date_end: "2023-08-01"
          description: |2-
              I serve as a Product Management Associate within a dynamic tech environment. My primary role involves spearheading innovative strategies and enhancements for our company's WeChat Mini Programs and web applications. I act as a pivotal liaison between the front-end and back-end engineering teams, ensuring seamless collaboration and alignment of our tech goals. Moreover, I play a crucial role in guiding our product's developmental trajectory, consistently providing valuable insights and constructive feedback during critical development phases.
        - title: Real-time Communication System Development Intern
          company: Tianjin Null Pointer Technology Co., Ltd.
          location: China
          date_start: "2022-11-01"
          date_end: "2023-03-31"
          description: |2-
            - Collaborate in the design and development of real-time communication modules using Java and Vue.js.
            - Leverage Java's multithreading capabilities and Vue's reactive data-binding features for optimal user experience.
            - Engage in MVC architecture optimization, RESTful API integration, and WebSocket implementations for seamless data transfer.
            - Participate in code reviews, ensuring modular and maintainable code adhering to best practices.
        - title: User Preference Analysis Intern
          company: Tianjin Ladder Technology Co., Ltd.
          location: China
          date_start: "2022-01-01"
          date_end: "2022-03-31"
          description: |2-
            - Python: Numpy、Pandas
            - Data Visualization: Matplotlib
            - Machine Learning: Scikit-learn and TensorFlow.
    design:
      columns: "4"
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: "Accomplish&shy;ments"
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://dasai.lanqiao.cn/
          date_end: ""
          date_start: "2021-06-25"
          description: C++ Algorithm Group National Excellence Award
          organization: lanqiao
          organization_url: https://dasai.lanqiao.cn/
          title: 12th LanQiao Cup Programming Algorithm Contest
          url: https://dasai.lanqiao.cn/
        - certificate_url: https://dasai.lanqiao.cn/
          date_end: ""
          date_start: "2021-05-25"
          description: C++ Algorithm Group Tianjin Province First-Class Prize
          organization: lanqiao
          organization_url: https://dasai.lanqiao.cn/
          title: 12th LanQiao Cup Programming Algorithm Contest
          url: https://dasai.lanqiao.cn/
        - certificate_url: https://dasai.lanqiao.cn/
          date_end: ""
          date_start: "2020-11-01"
          description: C++ Algorithm Group Tianjin Province Second-Class Prize
          organization: lanqiao
          organization_url: https://dasai.lanqiao.cn/
          title: 11th LanQiao Cup Programming Algorithm Contest
          url: https://dasai.lanqiao.cn/
    design:
      columns: "2"
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ""
  #     text: ""
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: "2"
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
          tag: "*"
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: "1"
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
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
      columns: "2"
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: Tom.wang.cn@outlook.com
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: "2"
---
