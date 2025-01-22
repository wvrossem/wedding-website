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
        text: 'On April 26, 2025, Bucheon Hanok Village'
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
          text: Join our celebration on 26 April, 2025 in South Korea.
          feature_icon: paper-airplane
          features:
            - "Dates: Saturday, 26 April, 2025 - 12h00"
            - "Wedding Ceremony Venue: Bucheon Hanok Village"
            - "Google Maps: https://maps.app.goo.gl/N2yqpSjp6s9qMFAp6"
          # Upload image to `assets/media/` and reference the filename here
          image: bg-picture.jpg
        - title: Wedding ceremony venue
          text: ""
          feature_icon: paper-airplane
          features:
            - "Date and time: Saturday, 26 April, 2025 - 12h00"
            - "Location: 부천한옥체험마을 (Bucheon Hanok Village)"
            - "Address: 경기도 부천시 길주로1 (상동 529-2)"
            - "Metro stop: Seoul Metro Line 7, Stop 삼산체육관 (757, Samsan Gymnasium)"
            - "Google Maps: https://maps.app.goo.gl/N2yqpSjp6s9qMFAp6"
            - "Naver Maps: https://naver.me/5Bcqqp9i"
            - "Kakao Maps: https://place.map.kakao.com/26093115"
          # Upload image to `assets/media/` and reference the filename here
          image: bucheon-hanok-village/korea-tourism.png
        - title: Wedding reception
          text: ""
          feature_icon: paper-airplane
          features:
            - "The wedding reception will take place immediately after the ceremony."
            - "Date and time: After the wedding ceremony"
            - "Location: To be confirmed"
          # Upload image to `assets/media/` and reference the filename here
          image: 8095743451_afdc95d75b_o.jpg
        - title: Travel tips and pre-meeting
          text: We are excited to celebrate with you in South Korea! Here’s some helpful information for your journey planning.
          feature_icon: paper-airplane
          features:
            - "Travel to South Korea: via Incheon International Airport (ICN), the main airport serving Seoul. Be here a day or two in advance."
            - "We will be staying in a hotel near the Bucheon Hanok Village. Feel free to meet us there and book accommodation in the neighborhood."
            - "You can also easily get to Bucheon Hanok Village by subway from central Seoul—approximately an hour away (Seoul Metro Line 7, Stop 삼산체육관 (757, Samsan Gymnasium))."
            - "Hanbok rentals (traditional Korean clothing) are available near the Bucheon Hanok Village or in central Seoul. We’ll be wearing them, but they’re completely optional. More information will be provided soon!"
          image: map-bucheon.png
        - title: Ceremony details
          text: "Image from https://www.gwanakcyw.or.kr:6015/?c=user&mcd=gkd0002"
          feature_icon: chevron-right
          features:
          - "1 - Pre-wedding performances: Before the wedding, it raises the mood of the wedding hall and announces the upcoming wedding. There are performances of pungmul, nabal, etc."
          - "2 - Groom’s entrance: The groom enters to greet his bride."
          - "3 - Jeonan-rye: This is an example of the groom arriving at the bride's house with his father-in-law and giving a goose to the bride's mother. The goose is a symbol of a promise to maintain a relationship for the rest of one's life once a relationship is formed. In the past, a live goose was used, but these days, a wooden goose is used instead."
          - "4 - Kyobae-rye: After the Jeonan-rye ceremony, the groom and bride greet each other for the first time at the invitation hall, and the groom and bride bow to each other. With this Gyobae ceremony, the groom and bride promise to live together for a hundred years."
          - "5 - Hapgeun-rye: Hapgeun-rye is a ceremony where alcohol is poured into a cup and a gourd and drunk separately. The gourd was originally one and divided into two, and the two become one again, symbolizing the unity of the couple."
          - "6 - Greetings from the bride and groom: After the wedding ceremony, all the formalities of the wedding ceremony are over. The bride and groom express their gratitude to the guests who came to see them."
          - "7 - Madang-nori: The congratulatory performances, including a congratulatory performance prepared by the groom and bride's friends, along with samulnori and celebratory dances, will all be performed together."
          - "8 - Photography: Taking commemorative photos with family, relatives, and friends."
          - "9 - Pyebaek: We move to a room to greet the in-laws and relatives."
          image: ceremony-kr.jpg
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
