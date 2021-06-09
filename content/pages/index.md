---
title: Home
sections:
  - type: hero_section
    title: 'Hi, I’m Pras. I am a Software Engineer and I love writing code.'
    subtitle: I hope to share my knowledge with the community whilst learning everyday.
    actions:
      - label: Contact Me
        url: /contact
        style: primary
    image: /images/new-pras.jpg
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: grid_section
    title: Versent
    subtitle: Who I work for
    align: center
    grid_items:
      - image_alt: Logo 1
        image_align: center
      - image: /images/Logo-Light@3x.png
        image_alt: Logo 2
        image_align: center
        content_align: center
      - image_alt: Logo 3
        image_align: center
      - image_alt: Logo 4
        image_align: center
      - image_alt: Logo 5
        image_align: center
      - image_alt: Logo 6
        image_align: center
      - image_alt: Logo 7
        image_align: center
      - image_alt: Logo 8
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
  - type: form_section
    content: >
      ## Let's talk


      If you would like more about me or if you would like to learn/share or
      just chat about new technologies, feel free to contact me :)
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: secondary
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Stackbit Personal Theme
  description: The preview of the Personal theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
