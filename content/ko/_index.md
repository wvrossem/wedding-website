---
title: '초대장'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: "수진 & 워우터"
      text: 저희 결혼식에 초대합니다
      primary_action:
        text: '2025년 04월 27일'
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
        - title: 저희 결혼식에 초대합니다
          text: 귀한 시간을 내주셔서 축하해 주시면 감사하겠습니다.
          feature_icon: paper-airplane
          features:
            - "결혼식 날짜: 2025년 04월 27일 오후 2시"
            - "장소 위치: 낙성대전통혼례식장"
          # Upload image to `assets/media/` and reference the filename here
          image: bg-picture.jpg
        - title: 장소
          text: ""
          feature_icon: paper-airplane
          features:
            - "장소 위치: 낙성대전통혼례식장 (서울 관악구 낙성대로 77 봉천동 227)"
            - "네이버 지도: https://naver.me/Fk5sfp2s"
            # - "More details will be provided soon"
          # Upload image to `assets/media/` and reference the filename here
          image: nakseongdae.jpg
        # - title: 장소에 가는 방법
          # text: 추후 안내 예정
          # feature_icon: paper-airplane
          # features:
          # Upload image to `assets/media/` and reference the filename here
          # image: south-korea-map.png
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"     
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-card
    id: rsvp
    content:
      title: 결혼 초대에 응답하시거나 더 많은 정보를 원하시면
      text: 수진에게 문자 메시지를 보내거나 전화해 주세요
      # button:
      #   text: Get Started
      #   url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
