---
title: Contact
date: 2026-02-09

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Welcome to join us!

        BISG-Robotics group is a creative, open, and internationally attractive research center with a strong background and expertise in computer vision and robotics at the University of Oulu. The team can use the top computing resources of the Finnish National and European Computing Centers (LUMI, Puhti, and Mahti), including high-performance ten-thousand GPU clusters such as A100, V100, and AMD MI250X, to support large-scale AI research. The team has different kinds of robotic platforms (e.g., Unitree G1) and sensors (e.g., Ouster LiDAR, Velodyne LiDAR, and Intel RealSense Depth Cameras) to support the development of advanced robots. The team provides sufficient funding annually to support travel, visits, and participation in various academic conferences.

        Additionally, Finland has maintained its position as the world's happiest country for several consecutive years due to its high level of social support, excellent natural environment, and international friendly atmosphere.
      email: antti.tikanmaki@oulu.fi
      phone: +358 40 5551386
      address:
        street: Linnanmaa Campus
        city: Oulu
        region: Pohjois-Pohjanmaa
        postcode: '90570'
        country: Finland
        # country_code: US
      coordinates:
        latitude: '65.059'
        longitude: '25.467'
      directions: Enter Building E1 and take the stairs to Office TS390 on Floor 3
      office_hours:
        - 'Monday 9:00 to 14:00'
        - 'Wednesday 09:00 to 10:00'
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
          filename: welcome.jpg
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
