---
layout: home
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/header.jpg
    background_image_opacity: 65
    content: |+
      # Реальная Мощь Мотора



    actions:
      - title: Смотреть все товары
        url: /store
        arrow: true
        style: primary
      - title: lorem-ipsum
        url: lorem-ipsum
        style: primary
        arrow: false
        type: action
  - type: featured_products_section
    section_id: best_sellers_section
    title: 'шие товары, по мнению пользЛучователей.'
    icon: true
    light_title: true
    featured_products:
      - products/plant1.md
      - products/plant3.md
      - products/plant5.md
      - products/plant7.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - category/bigplants.md
      - category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    title: Testimonials
    testimonials:
      - author:
          name: John Dope
          location: 'Colorado, USA'
        text: >-
          I didn't know the Snipcart guys were into herbs as well! How beautiful
          is that Planty theme. I'm going to launch a killer JAMstack e-commerce
          store using this for sure.
      - author:
          name: Major Payne
          location: 'VA, USA'
        text: >-
          Well I'll be d*mned. These plants really ARE greener than any of my
          recruits.
  - type: promotion_section
    section_id: promotion_section
    title: A new home interior for summer
    subtitle: from $149.99
    image: images/promo.jpg
    background_image: images/leaf.svg
    cta:
      title: Discover
      url: /store
      style: secondary
      arrow: true
  - section_id: lorem-ipsum
    headline: lorem-ipsum
    subtitle: >-
      ## Lorem ipsum


      Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
      eiusmod tempor incididunt ut labore et dolore magna aliqua.


      - Lorem ipsum

      - dolor sit amet
    type: header_section
---
