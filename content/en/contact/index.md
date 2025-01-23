---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        For any inquiries, you can contact us via email. We will respond to your request
        within a maximum of 48 hours. If you do not receive our reply within this time,
        please check the Spam folder in your inbox.
      email: retornna@unizar.es
      phone: +34 666 666 666
      address:
        street: María de Luna
        city: Zaragoza
        region: 
        postcode: '50018'
        country: Spain
        country_code: ES
      coordinates:
        latitude: '41.683213'
        longitude: '-0.88857'
      directions: Ada Byron Building, Floor 1
      office_hours:
        - 'Monday to Friday'
        - 'Morning: 09:00 to 14:00'
        - 'Afternoon: 16:00 to 20:00'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
