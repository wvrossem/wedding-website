---
title: 'Huwelijksuitnodiging'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: "Sujin & Wouter"
      text: Nodigen jullie uit voor hun huwelijksfeest
      primary_action:
        text: 'Op 26 en 27 april, 2025'
        url: '#details'
        icon: chevron-double-down
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark min-h-screen"
      background:
        image:
          # Name of image in `assets/media/`.
          filename: bg-ducks3.jpg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.5
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: bottom
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
  - block: cta-image-paragraph
    id: details
    content:
      items:
        - title: Wij nodigen jullie uit voor ons bruiloftsfeest.
          text: Vier met ons mee op 26 en 27 April, 2025 in Zuid-Korea.
          feature_icon: paper-airplane
          features:
            - "Datum: 26 en 27 april, 2025"
            - "Plaats: Zuid-Korea"
          # Upload image to `assets/media/` and reference the filename here
          image: bg-picture.jpg
        - title: Plaats & Accommodatie
          text: "Vier met ons mee op een prachtige locatie. "
          feature_icon: paper-airplane
          features:
            - "Plaats: South Korea"
            - "We geven binnenkort meer info!"
          # Upload image to `assets/media/` and reference the filename here
          image: hanok-hotel.jpeg
        - title: Hoe naar de locatie te komen
          text: We zijn enthousiast om met jullie te vieren in Zuid-Korea! Hier is wat handige informatie voor je reisplanning. Meer details volgen snel.
          feature_icon: paper-airplane
          features:
            - "Stap 1: Reis naar Zuid-Korea, via de Incheon International Airport (ICN), de belangrijkste luchthaven voor Seoel. Kom een dag of twee van tevoren."
            - "Stap 2: Van Incheon International Airport naar Seoul. Per trein, luchthavenlimousinebus, of taxi."
            - "Stap 3: Naar de trouwlocatie. We regelen een verzamelpunt voor groepsvervoer naar de locatie."
          # Upload image to `assets/media/` and reference the filename here
          image: bg-ko-wedding.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"     
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-card
    id: rsvp
    content:
      title: Om te reageren op onze uitnodiging of voor meer details
      text: Neem contact op met Wouter voor meer details.
      # button:
      #   text: Get Started
      #   url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
