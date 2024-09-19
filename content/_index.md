---
title: 'Home'
date: 2024-09-19
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero-with-stats
    content:
      title: Evolving Individuality 2024
      text: ""
      details: "Dec 2 - 4, 2024)"
      primary_action:
        text: Email to Register
        url: mailto: graham.thomas@mq.edu.au
        icon: ticket
      items:
        - name: "Speakers"
          description: ""
        - name: "Attendees"
          description: ""
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
#        image:
#          # Add your image background to `assets/media/`.
#          filename: ""
#          filters:
#            brightness: 1.0
  - block: countdown
    content:
      title: 
      text: 
      text_after: 
      date: '2024-02-12 09:00:00'
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
          image: city-daniel-abadia.jpg
        - title: DISCOVER
          text: Discover the latest in AI, GenAI, application development and much more.
          # Upload image to `assets/media/` and reference the filename here
          image: conference-headway-F2KRf_QfCqw.jpg
        - title: HEAR FROM LEADERS REDEFINING THE AI LANDSCAPE
          text: Hear valuable insights from data and AI experts and business leaders, while discovering the limitless possibilities of data, AI and application collaboration for your organization.
          # Upload image to `assets/media/` and reference the filename here
          image: round-table-evangeline-shaw-xRlI-L-kvrw.jpg
          button:
            text: Get Tickets
            url: https://www.eventbrite.com/
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
    id: program
    content:
      title: Program
      text: |
        **DAY 1**
        {style="padding-top: 2rem"}
        {{< table path="schedule.csv" header="true" >}}
        
        **DAY 2**
        {style="padding-top: 2rem"}

        {{< table path="schedule.csv" header="true" >}}
  - block: logos
    content:
      title: "Sponsors Making This Possible"
      text: "Thanks to the following sponsors for making this incredible event possible!"
      # Image path relative to assets/media/ folder
      logo_folder: 'sponsors/'
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
  - block: Register
    content:
      title: "Email to Register"
      text: "As there are limited spaces available, please register to attend"
      text_cta: "Register 🔥"
      button:
        text: "Register"
      convertkit:
        form_id: ''
        msg_registered: "Thank you. We will be in touch shortly."
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
