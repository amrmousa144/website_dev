---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  # ## ---------------------------------------------------------About Me----------------------------------------------------------------##

  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

# # ## ---------------------------------------------------------Skills----------------------------------------------------------------##
#   - block: skills
#     content:
#       title: Skills
#       text: ''
#       # Choose a user to display skills from (a folder name within `content/authors/`)
#       username: admin
#     design:
#       columns: '1'

## ---------------------------------------------------Working Experience----------------------------------------------------------##
  - block: experience
    id: experience
    content:
      title: Working Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Senior Research and Development Engineer
          company: Virtual Vehicle Research GmbH
          company_url: https://www.virtual-vehicle.at/
          company_logo: org-vif
          location: Graz, Austria
          date_start: '2021-10-01'
          date_end: ''
          description: |2-
              Key projects include:
              * **Developing robust RL-based locomotion policy for legged robots:**
                
                Using Meta-Reinforcement Learning to develop a locomotion policy for the quadruped robot -Unitree Go1- to be able to robustly navigate different environments for survival and rescue missions.

              * **RL-based Energy Management Strategy for P2-PHEVs:**

                Implementing a novel A3C agent that outperformed the existing rule-based control strategy and was integrated into the vehicle HCU for testing in HiL and ViL. The project resulted in two publications and a patent.

        - title: Advanced Controls Development Engineer
          company: AVL List GmbH
          company_url: 'https://www.avl.com/en'
          company_logo: org-avl
          location: Graz, Austria
          date_start: '2021-03-01'
          date_end: '2023-07-31'
          description: |2-
              Key projects include:

              * **Adaptive interiors control with a German OEM - Project Lead:**

                Developing an imitation learning RL agent that learns and predicts the driver preferences based on the driver mood, driving behavior and vehicle situation.
                          
              * **RL-based Thermal Management for Battery Electric Vehicles:**

                Improving the vehicle energy consumption by utilizing the heat sources to meet the cabin comfort requirements, powertrain, and battery optimal efficiencies.

              [See Employer Letter](https://drive.google.com/open?id=1LOuu-PRXv-745h496Ujr3wIAzBil7iRN&usp=drive_fs)

        - title: Research and Development Support Engineer
          company: HILTI BU Installation Systems
          company_url: 'https://www.hilti.com/'
          company_logo: org-hilti
          location:  Vienna, Austria
          date_start: '2020-03-01'
          date_end: '2021-09-30'
          description: |2-
              Supporting the R&D team on product design and development with focus on CAD, FEA, Product Testing, and Agile Development.  
              [See Employer Letter](https://drive.google.com/open?id=1LSFIotAK-0Mzvm5mdlpbm9OowFTY2LKN&usp=drive_fs)

    design:
      columns: '2'

## ------------------------------------------------------------Honors--------------------------------------------------------------##

  - block: accomplishments
    id: honors
    content:
      title: 'Honors'
      subtitle:
      date_format: Jan 2006
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2023-04-01'
          description: |2-
            Recipient of the FH INNOVATION award, securing 2nd place for the outstanding master's thesis in the Engineering department. 
            Watch the [VIDEO](https://youtu.be/8RY6lNvgess) and read the news [ARTICLE here](https://www.fh-ooe.at/campus-wels/die-fakultaet/aktuelles/innovationaward-fh-wels/).
          icon: org-fh
          organization: FH Oberösterreich
          organization_url: https://www.fh-ooe.at/campus-wels/die-fakultaet/aktuelles/innovationaward-fh-wels/
          title: FH INNOVATION award 2023 - 2nd place 
          url: ''

        - certificate_url: ''
          date_end: ''
          date_start: '2018-07-01'
          description: |2-
            Fully funded scholarship to study Engineering Management Master’s degree at Arizona State University by Alghurair Foundation
          icon: org-ghurir
          organization: Alghurair Foundation
          organization_url: https://www.alghurairfoundation.org/ar/past-programs/
          title: Fully funded scholarship - ASU's Master's degree
          url: ''

        - certificate_url: ''
          date_end: ''
          date_start: '2016-07-01'
          description: |2-
            Winning the Technical Innovation award for developing LabVIEW monitoring station and advanced onboard sensors suite to optimize velocity and monitor critical meausrements during the race. Watch our [video here](https://youtu.be/ZiALjtvFcME).
          icon: org-ghec
          organization:  Global Hybrid Car Challenge
          organization_url: http://egypt.globalhechallenge.org/pages/About.php
          title: Technical Innovation award - Global Hybrid Car Challenge 2016
          url: ''

        - certificate_url: ''
          date_end: ''
          date_start: '2013-09-01'
          description: |2-
            Fully funded scholarship to study the Aerospace Engineering Bachelor's degree at Zewail City
          icon: org-zewail
          organization: Zewail City of Science and Technology
          organization_url: https://www.zewailcity.edu.eg/
          title: Fully funded scholarship - Zewail City's Bachelor's degree
          url: ''
    design:
      columns: '2'
      view: card

## ----------------------------------------------------Featured Publications-----------------------------------------------------------##
  - block: collection
    id: featured_publications
    content:
      title: Featured Publications
      text: |-
        {{% callout note %}}
        This is a list of the featured publications only. 
        
        Quickly discover relevant content by [filtering all the publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'

# ## ---------------------------------------------------- Publications------------------------------------------------------------##

#   - block: collection
#     id: publications
#     content:
#       title: Publications
#       text: |-
#         {{% callout note %}}
#         Quickly discover relevant content by [filtering publications](./publication/).
#         {{% /callout %}}

#         [See all publications here!](./publication/)
#       filters:
#         folders:
#           - publication
#         exclude_featured: false

#     design:
#       columns: '2'


## ------------------------------------------------------Certificates--------------------------------------------------------------##

  - block: accomplishments
    id: certificates
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Certificates'
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
          date_start: '2021-04-25'
          description: |2-
            - [**Reinforcement Learning Specialization** - University of Alberta](https://www.coursera.org/account/accomplishments/specialization/certificate/VZTJA2L5CDDR)
            - [**Intro to Self-Driving Cars Specialization** - University of Toronto](https://www.coursera.org/account/accomplishments/certificate/ZDV5JFGEEEFS)
            - [**Neural Networks and Deep Learning** - DeepLearning.AI](https://www.coursera.org/account/accomplishments/certificate/DFPKMC8JEMM6)
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Mutiple Specializations and Courses
          url: ''
          
        - certificate_url: https://cv.virtualtester.com/qr/?b=SLDWRKS&i=C-TJPGH6LRV2
          date_end: ''
          date_start: '2020-07-01'
          description: ''
          icon: org-dassault
          organization: Dassault Systems
          organization_url: ''
          title: Certified SOLIDWORKS Associate (CSWA–Mechanical Design)
          url: https://cv.virtualtester.com/qr/?b=SLDWRKS&i=C-TJPGH6LRV2

        - certificate_url: ''
          date_end: ''
          date_start: '2017-08-01'
          description: ''
          icon: org-egyptair
          organization: EgyptAir Maintenace and Engineering
          organization_url: https://www.egyptair.com
          title: Aircraft Maintenance Internship Certificate
          url: ''

        - certificate_url: ''
          date_end: ''
          date_start: '2017-02-01'
          description: ''
          icon: org-bmw
          organization: Bavarian Auto Manufacturing Group
          organization_url: https://www.bmw-egypt.com
          title: Operation Management Internship Certificate
          url: ''
    design:
      columns: '2'

## --------------------------------------------------------Recent Posts----------------------------------------------------------------##
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
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
  #     columns: '2'

## ------------------------------------------------------------Selected Projects--------------------------------------------------------------##

  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Selected Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
    # design:
    #   # Choose how many columns the section has. Valid values: '1' or '2'.
    #   columns: '2'

## ----------------------------------------------------------Gallery-------------------------------------------------------------##
    
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: 'Highlighted imagery capturing moments from conferences and academic gatherings'
      text: |-
        {{< gallery album="demo" >}}
        <iframe width="560" height="315" src="https://www.youtube.com/embed/ZiALjtvFcME" frameborder="0" allowfullscreen></iframe>

    design:
      columns: '1'


# ## ------------------------------------------------------------Talks--------------------------------------------------------------------##

#     design:
#       columns: '2'
#       view: citation
#   - block: collection
#     id: talks
#     content:
#       title: Talks
#       filters:
#         folders:
#           - event

# ## -----------------------------------------------------Popular Topics----------------------------------------------------------------##

#     design:
#       columns: '2'
#       view: compact
#   - block: tag_cloud
#     content:
#       title: Popular Topics
    # design:
    #   columns: '2'

## ---------------------------------------------------------Contact------------------------------------------------------------------##

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        
      # Contact (add or remove contact options as necessary)
      email: amr.mousa@postgrad.manchester.ac.uk
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: Alliance Manchester Business School, Booth Street West
        city: Manchester
        region: ''
        postcode: 'M15 6PB, United Kingdom'
        country: United Kingdom
        country_code: UK
      # directions:  and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '53.468822'
        longitude: '-2.238084'  
      contact_links:
        # - icon: orcid
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
      # # Automatically link email and phone or display as text?
      # autolink: true
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: true
    design:
      columns: '2'
---
