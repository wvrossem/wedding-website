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
          text: <section class="text-2xl tracking-tight text-pretty"><div class="flex justify-between items-center w-full py-2 text-lg"><span class="flex-1 text-center">반로셈 <br />히슬랭</span><span class="flex-1 text-center">故 리켄달 <br />린다</span><span class="flex-1 text-center font-semibold">차남</span><span class="flex-1 text-center">워우터</span></div><hr /><div class="flex justify-between items-center w-full py-2 text-lg"><span class="flex-1 text-center">故 김판태</span><span class="flex-1 text-center">최소영</span><span class="flex-1 text-center font-semibold">자녀</span><span class="flex-1 text-center">수진</span></div><br/><p></p><br/><p>🗓️ 2025년 04월 26일 토요일 오후 12시</p><br/><p>📍 부천한옥체험마을</p><br /> <p>💕 <b>전통혼례</b> 방식으로 본식과 폐백을 올립니다</p></section>
          feature_icon: chevron-right
          features:
            # - ":spiral_calendar: 2025년 04월 26일 오후 12시"
            # - ":round_pushpin: 부천한옥체험마을"
          # Upload image to `assets/media/` and reference the filename here
          image: photoshoot/CHU_0666.jpg
        - title: 부천한옥체험마을 장소
          text: '<section class="text-2xl tracking-tight text-pretty"><p>📍 경기도 부천시 길주로1 (상동&nbsp;529-2)</p></br><p>🚗 주차할 수 있습니다.</p><br/><p><img src="/media/icons/custom/navermap.ico" alt="🇳" class="w-6 h-6 inline-block align-middle"/> 네이버 지도: <a href="https://naver.me/5Bcqqp9i" target="_blank" rel="noopener">https://naver.me/5Bcqqp9i</a></p><br/><p><img src="/media/icons/custom/kakaomap.ico" alt="🇰" class="w-6 h-6 inline-block align-middle"/> 카카오맵: <a href="https://place.map.kakao.com/26093115" target="_blank" rel="noopener">https://place.map.kakao.com/26093115</a></p>'
          feature_icon: chevron-right
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
          text: <span class="text-2xl font-bold tracking-tight text-pretty"> 부천시에 있을 것입니다. 추후 안내 예정.</span>
          feature_icon: chevron-right
          features:
            # - 추후 안내 예정.
          # Upload image to `assets/media/` and reference the filename here
          image: galbitang3.jpg
        - title: 💌 마음을 전하는 곳
          text: '<div class="text-2xl tracking-tight text-pretty"><p>소중한 축하의 마음을 전해주셔서 진심으로 감사합니다. 직접 축의금을 전달하기 어려우신 분들을 위해 아래 계좌 정보를 안내드립니다. 따뜻한 마음과 함께 행복을 나누겠습니다. 💖</p><br/><div class="text-2xl"><p><b>신부</b>:<br/> 우리 1002-549-098231 김수진</p><br/><p><b>신부측 어머니</b>:<br/> 국민 648425-96-104849 최소영</p><br/><p><b>신랑</b>:<br/> 우리 1002-865-277361 Wouter&nbsp;Van&nbsp;Rossem</p></div></div>'
          feature_icon: chevron-right
          image: wijdan-mq-H5yiRXDUkto-unsplash.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"  
  - block: cta-image-paragraph
    id: details
    content:
      items:
        - title: 전통혼례안내
          text: ""
          feature_icon: chevron-right
          features:
          - "**초자례**(醮字禮) **초녀례**(醮女禮): 신랑(신부)이 장가들기 위해 자기 집을 떠나기전 조상에게 고하 고 부모의 교훈을 받으며 떳떳한 장부로써 지아비의 역할을 다 할 것을 서약하는 것이다. 신랑의 복장은 관복을 입고 관대를 두르며, 사도를 쓰고 목화를 신는다. 신부의 복장은 녹색저고리와 붉은 치마를 입은 다음 위 에 원삼을 입고 족두리를 쓴다."
          - "**전안례**(奠雁禮): 신랑이 신부의 집에 원앙같이 살겠음을 다짐해 기러기를 드리는 의식."
          - "**교배례**(交拜禮): 신랑과 신부가 처음으로 만나 맞절로 인사하는 의식."
          - "**서 천지례**(誓 天地禮): 신랑과 신부가 천지신명에게 서약하는 의식. "
          - "**서 배우례**(誓 配偶禮): 신랑과 신부가 배우자에게 서약하고, 그 서약을 받아들이는 의식."
          - "**근배례**(巹杯禮): 하나의 박이 두 개의 바가지로 나뉘었다가 원자리로 돌아와 하나가 되 었음을 선언하는 의식."
          image: ceremony-kr.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-white-100 dark:bg-gray-900"  
  - block: gallery-block
    id: gallery 
    content:
      title: "Photo Gallery"
      folder: "media/gallery/*.{jpg}"
---
