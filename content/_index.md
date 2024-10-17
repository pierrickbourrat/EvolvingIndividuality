---
title: 'Home'
date: 2024-09-20
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: countdown
    content:
      title: ""
      text: ""
      text_after: ""
      date: '2024-12-02'
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]  
  - block: hero-with-stats
    content:
      text: "![Logo](logo3.png)"
      details: "Dec 2 - 4, 2024"
      additional_text: "Macquarie University"
      primary_action:
        text: Register
        url: mailto:graham.thomas@mq.edu.au?subject=Evolving%20Individuality%20conference%20registration
        icon: ticket
      items:
#        - name: "Speakers"
#          description: "22"
#        - name: "Attendees"
#          description: "25"
#        - name: "Venue"
#          description: "Macquarie University"
#        - name: "Location"
#          description: "Sydney"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "bg-gradient-to-r from-rose-100 to-teal-100 text-center"
#      background:
 #       color: ""
 #       image: bkg.png
  #        # Add your image background to `assets/media/`.
  #        filename: "assets/media/bkg.png"
  #        filters:
  #          brightness: 1.0
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: About
          text: This conference seeks to bring together biologists and philosophers of biology to discuss biological individuality from an evolutionary perspective, encompassing topics from the origins of life and complex organisms to the emergence of animal cognition.
          
          # Upload image to `assets/media/` and reference the filename here
          image: Macquarie Photo.jpg
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"    
  - block: people
    id: speakers
    content:
      title: Speakers
      text: ""
      user_groups: ['Speakers']
    design:
      show_role: true
      show_social: false
      show_interests: false
  - block: organisers
    id: organisers
    content:
      title: Organisers
      text: ""
      user_groups: ['Organisers']
    design:
      show_role: true
      show_social: false
      show_interests: false
      css_class: "bg-gray-100 dark:bg-gray-900"
#  - block: markdown
#    id: program
#    content:
#      title: Program
#      text: |
#        **DAY 1**
#        {style="padding-top: 2rem"}
#        {{< table path="schedule.csv" header="true" >}}
#        
#        **DAY 2**
#        {style="padding-top: 2rem"}
#
#        {{< table path="schedule.csv" header="true" >}}
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: Location
          text: MGSM Hotel. 99 Talavera Rd, Macquarie Park NSW 2113
          
          # Upload image to `assets/media/` and reference the filename here
          image: executive conference centre.jpg
          image: map.png
    design:
      # Section background color (CSS class)
  - block: logos
    content:
      title: "Sponsors"
      text: "Thanks to the following for making this event possible"
      # Image path relative to assets/media/ folder
      logo_folder: 'sponsors/'
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""      
---
