---
title: 'Invitation'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: "Sujin & Wouter"
      text: Invite You to their Wedding Celebration
      primary_action:
        text: 'On April 26-27, 2025'
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
        - title: We invite you to our wedding celebration
          text: Join our celebration on 26-27 April, 2025 in South Korea.
          feature_icon: paper-airplane
          features:
            - "Dates: 26-27 April, 2025"
            - "Venue: TBC, South Korea"
          # Upload image to `assets/media/` and reference the filename here
          image: bg-picture.jpg
        - title: Venue & Accomodation
          text: "Join us at a picturesque countryside venue with accommodation support provided."
          feature_icon: paper-airplane
          features:
            - "Location: South Korea"
            - "More details will be provided soon"
          # Upload image to `assets/media/` and reference the filename here
          image: hanok-hotel.jpeg
        - title: Getting to the venue
          text: We are excited to celebrate with you in South Korea! Here’s some helpful information for your journey planning. More details coming soon.
          feature_icon: paper-airplane
          features:
            - "Step 1: Travel to South Korea, via Incheon International Airport (ICN), the main airport serving Seoul. Be here a day or two in advance."
            - "Step 2: From Incheon International Airport to Seoul. Via rail, airport limousine bus, or taxi."
            - "Step 3: Getting to the Wedding Venue. We’ll arrange a meeting point for group transportation to the venue."
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
      title: To respond to our wedding invite or get more details
      text: Message or call Sujin or Wouter
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
