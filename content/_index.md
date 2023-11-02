---
# Leave the homepage title empty to use the site title
title: 
date: 2023-10-24
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
        - name: R / R shiny
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: R Markdown
          description: 85%
          icon: markdown
          icon_pack: fab
        - name: Statistics
          description: 80%
          icon: chart-line
          icon_pack: fas
        - name: Data analysis
          description: 70%
          icon: chart-simple
          icon_pack: fas
        - name: Data visualization
          description: 70%
          icon: chart-pie
          icon_pack: fas
        - name: Machine learning
          description: 50%
          icon: brain
          icon_pack: fas
        - name: SQL
          description: 65%
          icon: database
          icon_pack: fas
        - name: Python
          description: 50%
          icon: python
          icon_pack: fab
        - name: Git
          description: 70%
          icon: git
          icon_pack: fab
        - name: Overleaf
          description: 85%
          icon: leaf
          icon_pack: fas
        - name: Microsoft office
          description: 90%
          icon: microsoft
          icon_pack: fab
        - name: Playing football & Sport Analytics
          description: 85%
          icon: futbol
          icon_pack: fas
  - block: experience
    content:
      title: Experiences
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Organizer
          company: R-Ladies Paris
          company_url: 'https://www.meetup.com/fr-FR/rladies-paris/'
          company_logo: org-x
          location: Paris
          date_start: '2022-09-01'
          date_end: ''
          description: |2-
          
            * Help organize conferences and workshops using the **R language**.
            * Make posters, communicate and publish our events and materials (recordings, code, slides) on our social networks.
            * Contact and host speakers and trainers to promote the use of the R language worldwide.
        - title: Data Scientist & Business Modeler
          company: BVA Xsight
          company_url: 'https://www.bva.fr/'
          company_logo: org-gc
          location: Paris
          date_start: '2022-11-07'
          date_end: ''
          description: |2-
              
              * **Analysing** : **Marketing Mix Modeling**, **ROI** Market Research : quantify the past and future effects of decisions, **estimate** the value of intangible assets.
              * **Modelling** : 3-dimensional modeling: mathematical to connect all the factors that explain business performance, financial to arbitrate, and visual to collaborate and mediate.
              * **Deploying and visualization** : Business Viz, dashboarding and presentation. 
              
        - title: Data Scientist
          company: Rte
          company_url: 'https://www.rte-france.com/'
          company_logo: org-x
          location: Paris
          date_start: '2022-04-04'
          date_end: '2022-10-31'
          description: |2-
          
            * Creation of **SQL** queries to extract data from various department databases.
            * Processing and analysis of data required to improve the 'planning process'.
            * Creation, publication and documentation of an interactive dashboard using **R Shiny**.
            * Classification of 'energy works' and accuracy of consumption using machine learning algorithms with **python**.
            
        - title: Statistician trainer
          company: World Health Organization
          company_url: 'https://www.who.int/fr'
          company_logo: org-x
          location: Tunisia
          date_start: '2021-08-01'
          date_end: '2021-08-10'
          description: |2-
          
              * Animating the practical part of the training session for managers of the National Road Safety Observatory.
              * Application using **R**, **descriptive statistics** and **inferential statistics**.
        - title: Data mining researcher 
          company: Laboratoire GREYC - University of Caen Normandie
          company_url: 'https://www.greyc.fr/'
          company_logo: org-x
          location: Caen, France
          date_start: '2021-03-01'
          date_end: '2021-08-31'
          description: |2-
          
              * **Tactical analysis** of team sports data : Implementation of an algorithm based on **dynamic graphs** to identify styles of play by detecting **frequent patterns** among players in collective sports.
             * Applying the algorithm to data from the Qatar 2015 **handball world cup**.
             * Participation in the editing of a **research paper**.
             
        - title: Active member
          company: R-Ladies Tunis
          company_url: 'https://www.meetup.com/rladies-tunis/'
          company_logo: org-x
          location: Tunisia
          date_start: '2021-01-31'
          date_end: '2021-08-01'
          description: |2-
          
            * Help organize conferences and workshops using the **R language**.
            * Make posters, communicate and publish our events and materials (recordings, code, slides) on our social networks.
            * Contact and host speakers and trainers to promote the use of the R language worldwide.
            
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
        - certificate_url: https://drive.google.com/file/d/1rdOTFYRiYp1RFRUhLfbmRq5SQd7BHT_o/view?usp=sharing
          date_end: ''
          date_start: '2021-08-17'
          description: 'Animating the practical part of the training session for managers of the National Road Safety Observatory using statistics and R programming.'
          organization: Word Health Organization
          organization_url: https://www.who.int/
          title: Statistics in the service of road safety
          url: ''
        - certificate_url: https://drive.google.com/file/d/13zrgBWyMPHHSJ2ljrFCzqh57cUbktxEa/view?usp=sharing
          date_end: ''
          date_start: '2020-01-01'
          description: 
          organization: Datacamp
          organization_url: https://www.datacamp.com/
          title: Introduction to Deep Learning with Keras
          url: 
        - certificate_url: https://drive.google.com/file/d/1TSfk4O4QYgH7J4IL_k3ayRyITr4QBM2z/view?usp=sharing
          date_end: '2022-12-16'
          date_start: '2020-12-16'
          description: ''
          organization: ETS
          organization_url: https://www.etsglobal.org/fr/fr
          title: 'TOEIC'
          url: 'https://www.etsglobal.org/fr/fr'
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
        - name: R 
          tag: R 
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: talks
    content:
      title: Previous & Recent Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: collection
    id: pub
    content:
      title: Papers
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: compact
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'

---
