---
# Leave the homepage title empty to use the site title
title: Katie Auchettl
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: <br><br><br><br><br><br><br><br>
      # text: My research focuses on understanding the physical processes and observational signatures related to the extreme death of stars, and how these processes influence, and are influenced by their surrounding environment. In particular, I use space- and ground-based instruments to study tidal disruption events, black holes, supernovae, and their diffuse and compact objects.
      #  I am a member of the <a href="https://astro.physics.unimelb.edu.au/" target="_blank">Uni Melbourne Astrophysics Group</a> and a Chief Investigator of the <a href="https://www.ozgrav.org/" target="_blank">ARC Center of Excellence OzGrav 2</a>.
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: true
          

  - block: experience
    id: employment
    content:
      title: Employment
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Associate Professor in Astrophysics
          company: University of Melbourne
          company_url: 'https://astro.physics.unimelb.edu.au/'
          company_logo: unimelb
          location: Melbourne, Australia
          date_start: '2023-01-01'
          date_end: ''
          description: 
        - title: Senior Lecturer in Astrophysics
          company: University of Melbourne
          company_url: 'https://astro.physics.unimelb.edu.au/'
          company_logo: unimelb
          location: Melbourne, Australia
          date_start: '2020-06-01'
          date_end: '2022-12-31'
          description: 
        - title: Assistant Adjunct Professor
          company: University of California Santa Cruz
          company_url: 'https://www.ucsc.edu/'
          company_logo: UCSC2
          location: Santa Cruz, California, USA
          date_start: '2019-01-01'
          date_end: ''
          description: 
        - title: Assistant Professor
          company: DARK Cosmology Center & Niels Bohr Institute, University of Copenhagen
          company_url: 'https://dark.nbi.ku.dk/'
          company_logo: unicph
          location: Copenhagen, Denmark
          date_start: '2018-09-01'
          date_end: '2020-05-31'
          description: 
        - title: CCAP Postdoctoral Fellow
          company: The Center for Astro-particle Physics and Cosmology, The Ohio State University
          company_url: 'https://ccapp.osu.edu/'
          company_logo: OSU
          location: Columbus, Ohio, USA
          date_start: '2015-08-01'
          date_end: '2018-08-31'
          description:
    design:
      columns: '2'
#   - block: experience
#    id: education
#    content:
#     title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#       items:
#        - title: PhD in Physics
#          company: Monash University
#          company_url: 'https://www.monash.edu/'
#          company_logo: MonashUniversity-inverted
#          location: Melbourne, Australia
#          date_start: '2012-08-01'
#          date_end: '2015-07-31'
 #         description: 
 #       - title: MSc in Physics (Perimeter Scholars International)
 #         company: University of Waterloo & Perimeter Institute for Theoretical Physics
 #         company_url: 'https://perimeterinstitute.ca/psi-masters-program'
 #         company_logo: UWaterloo
 #         location: Waterloo, Ontario, Canada
 #         date_start: '2011-10-01'
 #         date_end: '2012-09-30'
#          description: 
#        - title: BSc (Honors) in Physics and Mathematics
#          company: Monash University
#          company_url: 'https://www.monash.edu/'
#          company_logo: MonashUniversity-inverted
#          location: Melbourne, Australia
#          date_start: '2007-10-01'
#          date_end: '2010-09-30'
#          description:
#    design:
#      columns: '2'
#      background:
#      color: 'red' -->
  - block: markdown
    content:
     title: Research
     text: My research focuses on understanding the physical processes and observational signatures related to the extreme death of stars, and how these processes influence, and are influenced by their surrounding environment. In particular, I use space- and ground-based instruments to study tidal disruption events, black holes, supernovae, and their diffuse and compact objects. <br><br> You can find all my publications on <a href="https://scholar.google.com/citations?user=zTzMlEEAAAAJ&hl=en" target="_blank">Google Scholar</a>.
    design:
     columns: '2' 
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      #  You can send me an email using the following form:
      # Contact (add or remove contact options as necessary)
      email: katie[dot]auchettl[at]unimelb[dot]edu[dot]au
 #     address:
 #       street: Office 311, Swanston St & Tin Alley
 #       city: Parkville
 #       region: VIC
 #       postcode: '3052'
 #       country: Australia
  #      country_code: AU
 #     directions: <a href="https://maps.unimelb.edu.au/dir?pointB=659833" target="_blank">see directions</a>
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
      #    # Enable CAPTCHA challenge to reduce spam?
      #    captcha: true
    design:
      columns: '2'
---
