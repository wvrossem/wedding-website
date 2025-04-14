---
title: 'Uitnodiging'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: ""
      text: ""
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark min-h-screen"
      background:
        image:
          # Name of image in `assets/media/`.
          filename: photoshoot/invitation2-border3.png
          # Apply image filters?
          # filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            # brightness: 0.5
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: contain
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
  - block: cta-image-paragraph
    id: invitation
    content:
      items:
        - title: Wij nodigen jullie uit voor ons bruiloftsfeest.
          text: Vier met ons mee op 26 April, 2025 in Zuid-Korea.
          feature_icon: chevron-right
          features:
            - "Datum en tijdstip: **Zaterdag, 26 April, 2025 - 12h00**"
            - "Plaats: **Bucheon Hanok Village**"
          # Upload image to `assets/media/` and reference the filename here
          image: photoshoot/CHU_0666.jpg
        - title: Plaats van huwelijksceremonie
          text: ""
          feature_icon: chevron-right
          features:
            - "**Locatie**: 부천한옥체험마을 (**Bucheon Hanok Village**)"
            - "**Adres**: 경기도 부천시 길주로1 (상동 529-2)"
            - "**Metro stop**: Seoul Metro Line 7, Stop 삼산체육관 (757, Samsan Gymnasium), volg de uitgang Exit 5"
            - "**Google Maps**: https://maps.app.goo.gl/N2yqpSjp6s9qMFAp6 (Let op: Google Maps werkt niet goed in Zuid-Korea.)"
            - "**Naver Maps**: https://naver.me/5Bcqqp9i"
            - "**Kakao Maps**: https://place.map.kakao.com/26093115"
          # Upload image to `assets/media/` and reference the filename here
          image: bucheon-hanok-village/SSI_20210128120855_V.jpg
  - block: cta-image-paragraph
    id: tips
    content:
      items:
        - title: Receptie
          text: ""
          feature_icon: chevron-right
          features:
            - "De lunch wordt in buffetstijl geserveerd direct na de ceremonie op dezelfde locatie."
            - "Tijd: Na de huwelijksceremonie (rond 13u30)"
            - "Locatie: Bucheon Hanok Village"
          # Upload image to `assets/media/` and reference the filename here
          image: 8095743451_afdc95d75b_o.jpg
          button:
            text: "Wat staat er op het menu? Bekijk het menu (PDF)"
            url: catering-menu-buffet.pdf
            icon_pack: hero
            icon: document
        - title: Dress Code
          text: ""
          feature_icon: chevron-right
          features:
            - "👔 **Westerse Kleding**: Je hoeft geen pak mee te nemen als dat ongemakkelijk is voor je reis—maar je mag er gerust één dragen! Een nette, casual outfit met een vleugje formaliteit is prima."
            - "👘 **Koreaanse Hanbok**: Wij en sommige van onze gasten zullen traditionele Koreaanse hanboks dragen, maar het is optioneel voor gasten om er één te dragen. Als je er een wilt, zijn populaire verhuurbedrijven voor buitenlanders in de buurt van Bukchon Hanok Village en Gyeongbokgung Station in Seoel—overweeg om van vrijdag tot zondag te huren en vraag om een trouw-hanbok. Er zijn ook verhuurbedrijven in Bucheon, dichtbij de locatie, maar sommige zijn iets meer premium."
          # Upload image to `assets/media/` and reference the filename here
          image: winged-jedi-hgwbEL9Yn90-unsplash.jpg
        - title: "Geschenken"
          text: "Jouw aanwezigheid is het mooiste cadeau; bedankt voor je liefde en steun! In Korea is het gebruikelijk om een geld als cadeau te geven op bruiloften. Als je wilt, kun je een storting doen op onze bankrekening om ons te helpen onze toekomst samen op te bouwen."
          feature_icon: chevron-right
          features:
            - "Naam: **Wouter Van Rossem**" 
            - "Account nummer (IBAN): **BE89 0015 3168 7085**"
            - "BIC: **GEBABEBB**"
            - "Bank name: **BNP Paribas Fortis**"
          # Upload image to `assets/media/` and reference the filename here
          image: wijdan-mq-H5yiRXDUkto-unsplash.jpg
        - title: Reistips en voorafgaande ontmoeting
          text: We zijn enthousiast om met jullie te vieren in Zuid-Korea! Hier is wat handige informatie voor je reisplanning. Meer details volgen snel.
          feature_icon: chevron-right
          features:
            - "Reis naar Zuid-Korea: via de Incheon International Airport (ICN), de belangrijkste luchthaven die Seoul bedient. Kom een dag of twee van tevoren."
            - "We verblijven in een hotel in de buurt van Bucheon Hanok Village. Je kan ons daar al ontmoeten en accommodatie in de buurt te boeken, bijvoorbeeld in The Koryo Hotel of Hotel Polaris in Bucheon-si."
            - "Naar de trouwlocatie: De trouwlocatie is bereikbaar met het openbaar vervoer. (Seoul Metro Line 7, Stop 삼산체육관 (757, Samsan Gymnasium), Exit 5)"
          # Upload image to `assets/media/` and reference the filename here
          image: map-bucheon.png
        - title: Nuttige apps
          text: "Hier zijn enkele nuttige apps voor het navigeren door Korea, zoek ze op in de app store van je apparaat"
          feature_icon: chevron-right
          features:
            - "📍 **Navigatie**: *Naver Map*, De beste kaart-app voor Korea, met nauwkeurige routebeschrijvingen en informatie over het openbaar vervoer."
            - "🗣️ **Vertaling**: *Papago* of *Google Translate*, Beiden werken goed voor algemene vertalingen en tekstherkenning via afbeeldingen. Papago is gespecialiseerd in Koreaanse vertalingen en daardoor soms beter."
            - "🚖 **Taxi**: *Kakao T*, De populairste taxi-app in Korea. Taxi's zijn betaalbaar, en je kunt gemakkelijk een rit aanvragen met je bestemming al ingesteld, wat zorgt voor een zorgeloze ervaring."
          image: fikri-rasyid-HGLCvGWujGE-unsplash.jpg
  - block: cta-image-paragraph
    id: details
    content:
      items:
        - title: Ceremonie uitleg
          text: "Afbeelding van https://www.gwanakcyw.or.kr:6015/?c=user&mcd=gkd0002"
          feature_icon: chevron-right
          features:
          - "1 - Pre-wedding performances: Voor de bruiloft wordt de sfeer in de trouwzaal verhoogd en wordt de aankomende bruiloft aangekondigd. Er zijn optredens van pungmul, nabal, enz."
          - "2 - Entree van de bruidegom: De bruidegom komt binnen om zijn bruid te begroeten."
          - "3 - Jeonan-rye: Dit is een voorbeeld van de bruidegom die met zijn schoonvader naar het huis van de bruid gaat en een gans aan de moeder van de bruid geeft. De gans is een symbool van een belofte om de relatie voor de rest van het leven te behouden zodra een relatie is gevormd. Vroeger werd een levende gans gebruikt, maar tegenwoordig wordt in plaats daarvan een houten gans gebruikt."
          - "4 - Kyobae-rye: Na de Jeonan-rye ceremonie begroeten de bruidegom en de bruid elkaar voor het eerst in de uitnodigingshal, en de bruidegom en de bruid buigen voor elkaar. Met deze Gyobae ceremonie beloven de bruidegom en de bruid samen te leven voor honderd jaar."
          - "5 - Hapgeun-rye: Hapgeun-rye is een ceremonie waarbij alcohol in een beker en een kalebas wordt gegoten en apart wordt gedronken. De kalebas was oorspronkelijk één en werd in tweeën verdeeld, waarna de twee weer één worden, wat de eenheid van het paar symboliseert."
          - "6 - Groeten van de bruid en bruidegom: Na de huwelijksceremonie zijn alle formaliteiten van de huwelijksceremonie voorbij. De bruid en bruidegom drukken hun dankbaarheid uit naar de gasten die hen kwamen bezoeken."
          - "7 - Madang-nori: De felicitaties, inclusief een felicitatiesperformance die is voorbereid door de vrienden van de bruidegom en bruid, samen met samulnori en feestelijke dansen, zullen allemaal samen worden uitgevoerd."
          - "8 - Fotografie: Het maken van herinneringsfoto’s met familie, vrienden en kennissen."
          - "9 - Pyebaek: We verplaatsen ons naar een kamer om de schoonouders en familieleden te begroeten."
          image: ceremony-kr.jpg 
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: gallery-block
    id: gallery 
    content:
      title: "Photo Gallery"
      folder: "media/gallery/*.{jpg}"
---
