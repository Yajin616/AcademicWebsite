---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    content:
      title: Education and Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Assistant of Technology
          company: China Blue Seed Industry Institute (Qingdao), Ocean University of China
          company_url: ''
          location: Qingdao, China
          date_start: '2023-07-01'
          date_end: ''
        - title: MEng in Biology and Medicine (Bioengineering)
          company: Sanya Oceanography Institution, Ocean University of China
          company_url: 'http://soi.ouc.edu.cn'
          location: Sanya, China
          date_start: '2020-09-01'
          date_end: '2023-06-01'
        - title: BEng in Environmental Engineering
          company: Shanghai University of Engineering and Technology, College of Chemistry and Chemical Engineering
          company_url: 'https://www.sues.edu.cn/'
          location: Shanghai, China
          date_start: '2015-09-01'
          date_end: '2019-06-01'
    design:
      columns: '3'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: xuyajin@stu.ouc.edu.cn
      appointment_url: 'https://calendly.com'
      address:
        street: No. 62 Fuzhou South Road
        city: Qingdao
        region: Shandong
        postcode: '266073'
        country: China
        country_code: CHN
      directions: Marine Geology Research Institute Park
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
      columns: '2'
---
