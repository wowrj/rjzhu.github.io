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
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: LAB Rotation
          company: 'Chemistry Department'
          company_url: ''
          company_logo: ''
          location: Boston University
          date_start: '2025-09-08'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Computational Biophysics
        - title: Research Practice
          company: Supervisor:Fei Xia (NYU-ECNU Center for Computational Chemistry)
          company_url: ''
          company_logo: ''
          location: East China Normal University (Shanghai, China)
          date_start: '2021-09-30'
          date_end: '2025-08-30'
          description: |2-
              Responsibilities include:

              * Computational Chemistry
              * Coarse-Grained Force Field
              * Coarse-Grained Modelling and Simulation
        - title: Summer Research Program
          company: Supervisor:Jing Huang
          company_url: ''
          company_logo: ''
          location: Westlake University (Hangzhou, China)
          date_start: '2024-07-30'
          date_end: '2024-08-30'
          description: |2-
              Responsibilities include:

              * Protein Pocket Alignment
              * Protein Surface Fingerprint
    design:
      columns: '1'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplishments & Awards'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2023-09-01'
          description: ''
          icon: ''
          organization: Shanghai Municipal Education Commission
          organization_url: 
          title: |2-
              17th Shanghai College Students' Chemistry Experiment Innovation Design Competition 

              Special Prize (Top 1)
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2023-11-25'
          description: ''
          icon: top_en.jpg
          organization: China Society for Industrial and Applied Mathematics
          organization_url: ''
          title: |2-
              Contemporary Undergraduate Mathematical Contest in Modeling

              Second Prize (Top 3%)
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2024-07-14'
          description: ''
          icon: 
          organization: Shanghai Municipal Education Commission
          organization_url: 
          title: |2-
              18th Shanghai College Students' Chemistry Experiment Competition 

              Special Prize (Top 1)
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2023-09-01'
          description: ''
          icon: ''
          organization: East China Normal University
          organization_url: 
          title: |2-
              9th ECNU Undergraduate Innovation and Entrepreneurship Academic Forum

              Outstanding Report Award
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2022-10-01'
          description: ''
          icon: ''
          organization: Ministry of Education of P.R.China
          organization_url: 
          title: National Scholarship for Undergraduate Students
        - certificate_url: ''
          date_end: ''
          date_start: '2024-10-01'
          description: ''
          icon: ''
          organization: Ministry of Education of P.R.China
          organization_url: 
          title: National Scholarship for Undergraduate Students
        - certificate_url: ''
          date_end: ''
          date_start: '2023-10-01'
          description: ''
          icon: ''
          organization: East China Normal University
          organization_url: 
          title: Special Scholarship for Outstanding Students of ECNU
        - certificate_url: ''
          date_end: ''
          date_start: '2021-12-01'
          description: ''
          icon: ''
          organization: Chinese Mathematical Society
          organization_url: 
          title: |2-
              13th Chinese Mathematics Competitions (Preliminary Round)

              First Prize
        - certificate_url: ''
          date_end: ''
          date_start: '2025-05-01'
          description: ''
          icon: ''
          organization: Shanghai Municipal Commission of Education
          organization_url: 
          title: Outstanding Graduates in Shanghai
        - certificate_url: ''
          date_end: ''
          date_start: '2025-06-30'
          description: ''
          icon: ''
          organization: East China Normal University
          organization_url: 
          title: Outstanding Undergraduate Thesis of East China Normal University

    design:
      columns: '1'
  - block: collection
    id: pub
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
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Contact me.
      # Contact (add or remove contact options as necessary)
      email: rjzhu811@gmail.com
      address:
        street: 590 Commonwealth Ave.
        city: Boston
        region: MA
        postcode: '02215'
        country: United States
        country_code: US
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '42.3481'
        longitude: '-71.1004'
      contact_links:
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true

---
