---
title: Contato
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Entre em Contato
      text: |-
        Outras Formas de Contatos disponiveis para tirar duvidas sobre a grade curricular e o curso 
      email: dpa@unicap.br
      phone: '+55(81)2119-4000'
      address:
        street: Rua do Príncipe, 526 - Boa Vista - Recife, PE
        city: Recife
        region: PE
        postcode: '50050-900'
        country: Brasil
        country_code: BR
      coordinates:
        latitude: '-8.05774'
        longitude: '-34.88439'
      directions: Entre pela entrada do bloco G,se encaminhe para o bloco A,suba o 1 andar e encontro o laboratorio do Loyola
      office_hours:
        - 2ª a 6ª – 8h às 21h
        - Sábados - 8h às 12h
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
