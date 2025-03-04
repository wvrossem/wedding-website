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
      title: ""
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark min-h-screen flex flex-col"
      background:
        image:
          # Name of image in `assets/media/`.
          filename: photoshoot/invitation2-border3.png 
          # Apply image filters?
          # filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            # brightness: 0
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: contain
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
  - block: cta-image-paragraph
    id: details
    content:
      items:
        - title: 저희 결혼식에 초대합니다
          # text: <span class="text-xl font-bold tracking-tight text-pretty"> 귀한 시간을 내주셔서 축하해 주시면 감사하겠습니다.</span>
          feature_icon: chevron-right
          features:
            - ":spiral_calendar: 2025년 04월 26일 오후 12시"
            - ":round_pushpin: 부천한옥체험마을"
          # Upload image to `assets/media/` and reference the filename here
          image: photoshoot/CHU_0666.jpg
          classes: "text-6xl font-bold tracking-tight text-pretty"
        - title: 부천한옥체험마을 장소
          text: ""
          feature_icon: chevron-right
          features:
            - ":round_pushpin: 경기도 부천시 길주로1 (상동 529-2)"
            - ":car: 주차할 수 있습니다."
            - "네이버 지도: https://naver.me/5Bcqqp9i"
            - "카카오맵: https://place.map.kakao.com/26093115"
          # Upload image to `assets/media/` and reference the filename here
          image: bucheon-hanok-village/SSI_20210128120855_V.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-white-100 dark:bg-gray-900"
  - block: cta-image-paragraph
    id: details
    content:
      items:
        - title: 결혼식 식사
          text: <span class="text-xl font-bold tracking-tight text-pretty"> 부천시에 있을 것입니다. 추후 안내 예정.</span>
          feature_icon: chevron-right
          features:
            - 추후 안내 예정.
          # Upload image to `assets/media/` and reference the filename here
          image: galbitang3.jpg
        - title: 💌 마음을 전하는 곳
          text: <span class="text-2xl font-bold tracking-tight text-pretty"> 소중한 축하의 마음을 전해주셔서 진심으로 감사합니다. 직접 축의금을 전달하기 어려우신 분들을 위해 아래 계좌 정보를 안내드립니다. 따뜻한 마음과 함께 행복을 나누겠습니다. 💖</span>
          feature_icon: chevron-right
          features:
            - "혼주 (예금주: 최소영)"
            - "국민은행 648425-96-104849"
          image: wijdan-mq-H5yiRXDUkto-unsplash.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: gallery-block
    id: gallery 
    content:
      title: "Photo Gallery"
      folder: "media/gallery/*.{jpg}"
---
