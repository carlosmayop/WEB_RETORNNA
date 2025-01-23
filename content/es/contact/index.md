---
title: Contacto
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contacto
      text: |-
        Para cualquier consulta, puedes contactarnos a través de nuestro correo electrónico. Responderemos a tu solicitud en un plazo máximo de 48 horas. Si no recibes nuestra respuesta en ese tiempo, por favor revisa la carpeta de Spam en tu bandeja de entrada.
      email: retornna@unizar.es
      phone: +34 666 666 666
      address:
        street: María de Luna
        city: Zaragoza
        region: 
        postcode: '50018'
        country: España
        country_code: ES
      coordinates:
        latitude: '41.683213'
        longitude: '-0.88857'
      directions: Edificio Ada Byron, Planta 1
      office_hours:
        - 'Lunes a viernes'
        - 'Mañanas: 9:00 a 14:00'
        - 'Tardes: 16:00 to 20:00'
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
        provider: formspree
        formspree:
          id: movjqwbv
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
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
