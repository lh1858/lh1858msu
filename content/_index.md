---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Python
          description: 90%
          icon: camera-retro
          icon_pack: fas
        - name: MATLAB
          description: 90%
          icon: camera-retro
          icon_pack: fas
        - name: CPLEX
          description: 90%
          icon: camera-retro
          icon_pack: fas
        - name: Tableau
          description: 90%
          icon: camera-retro
          icon_pack: fas
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
        - title: Faculty of Department of Marketing, Quantitative Analysis & Business Law
          company: Mississippi State University
          company_url: ''
          company_logo: org-gc
          location: Starkville, MS
          date_start: '2021-06-01'
          date_end: ''
          description: |2-
              Taught both online and face-to-face courses include:

              * Business Decision Analysis
              * Statistical Analysis and Business Decisions 
              * International Logistics
              * International Supply Chain Management 
        - title: Assistant Professor of Public Health Department
          company: University of Arkansas of Medical Science
          company_url: ''
          company_logo: org-x
          location: Little Rock, AR
          date_start: '2021-01-01'
          date_end: '2021-06-01'
          description: Taught data mining in healthcare.
        - title: Research Associate of Department of Strategic Operations and Implementation
          company: Mount Sinai Health System
          company_url: ''
          company_logo: org-x
          location: Manhattan, NY
          date_start: '2017-03-01'
          date_end: '2019-07-01'
          description: |2-
              Conducted continuous improvement projects for various healthcare departments among seven hospital campuses, my responsibilities include:

              * Clean and analyze clinical data using Excel, Minitab, Access, and Python
              * Devise optimization tools (Excel Solver) and simulation models (Simio) to enhance scheduling accuracy and process efficiencies
              * Developed reports/dashboards (Excel/Access) to track clinical performance
        - title: Lean Six Sigma Program Teaching Assistant
          company: State University of New York at Binghamton
          company_url: ''
          company_logo: org-gc
          location: Binghamton, NY
          date_start: '2016-01-01'
          date_end: '2020-12-01'
          description: Facilitated over 20 Lean Six Sigma Yellow Belt, Green Belt, and Black Belt programs for both industries and academic organizations. The program sizes range from 9 to 152.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.citiprogram.org/verify/?we8be31e4-f93d-461e-82f7-835f52fc0cb8-40892293
          date_end: '2024-02-01'
          date_start: '2021-02-01'
          description: ''
          organization: CITI Program
          organization_url: https://www.citiprogram.org
          title: Social/Behavioral Research Course 
          url: ''
        - certificate_url: https://www.binghamton.edu/watson/continuing-education/lean-six-sigma/blackbelt.html
          date_end: ''
          date_start: '2021-01-01'
          description: ''
          organization: The State University of New York at Binghamton   
          organization_url: https://www.binghamton.edu/watson/
          title: Lean Six Sigma Black Belt Certified
          url: ''
        - certificate_url: https://www.ccel.msstate.edu/faculty/workshops/#
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: Mississippi State University
          organization_url: https://www.ccel.msstate.edu/faculty/workshops/
          title: MSU Community-Engaged Learning Faculty Fellowship
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#     # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
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
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
  #    subtitle:
  #    text: |-
  #     Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: lhe@business.msstate.edu
      phone: 662 325 05 40
      # appointment_url: 'https://calendly.com'
      address:
        street: 75 B. S. Hood Rd  
        city:  Mississippi State
        region: MS
        postcode: '39762'
        country: United States
        country_code: US
   #   directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
   #   office_hours:
   #     - 'Monday 10:00 to 13:00'
   #    - 'Wednesday 09:00 to 10:00'
      contact_links:
     #  - icon: twitter
     #     icon_pack: fab
     #     name: DM Me
     #     link: 'https://twitter.com/Twitter'
     #   - icon: skype
     #     icon_pack: fab
     #     name: Skype Me
     #     link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: WebEx Me
          link: 'https://msstate.webex.com/meet/lh1858'
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
