---
title: 'Home'
date: 2024-09-20
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero-with-stats
    content:
      title: Evolving Individuality 2024
      text: |
        <img src="logo.png" alt="Logo" style="width: 200px; height: auto;">
      details: "Dec 2 - 4, 2024"
      primary_action:
        text: Register
        mailto: graham.thomas@mq.edu.au
        icon: ticket
      items:
        - name: "Speakers"
          description: "22"
        - name: "Attendees"
          description: "25"
        - name: "Venue"
          description: "Macquarie University"
        - name: "Location"
          description: "Sydney"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "bg-gradient-to-r from-rose-100 to-teal-100"
#      background:
#        color: ""
#        image: logo.png
#          # Add your image background to `assets/media/`.
#          filename: "logo.png"
#          filters:
#            brightness: 1.0
  - block: countdown
    content:
      title: ""
      text: ""
      text_after: ""
      date: '2024-12-02'
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-500"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: THE YEAR’S CAN’T-MISS EVENT FOR AI COLLABORATION
          text: AI Summit is coming home to San Francisco. Join us at AI Summit 2024 to explore all the cutting-edge innovation the data cloud has to offer.
          # Upload image to `assets/media/` and reference the filename here
          image: Macquarie Photo.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: people
    id: speakers
    content:
      title: Speakers
      text: ""
      user_groups: ['Speakers']
    design:
      show_role: true
      show_social: true
      show_interests: false
  - block: markdown
    id: agenda
    content:
      title: Agenda
      text: |
        **DAY 1**
        {style="padding-top: 2rem"}
        {{< table path="schedule.csv" header="true" >}}
        
        **DAY 2**
        {style="padding-top: 2rem"}

        {{< table path="schedule.csv" header="true" >}}
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
