---
standalone: true
title: teste-workshops
slug: teste-workshops
projeto: teste-workshops
pageSettings:
  language: pt-BR
  link_pt_br: '#'
  link_en: '#'
  link_es: '#'
  animations: enable_all
  direction: left
  seoTitle: ''
  seoDescription: ''
  seoKeywords: []
  seoImage: ''
pageTheme:
  primaryColor: ''
  secondaryColor: '#ffffff'
  highlightColor: '#3a7e7d'
  auxiliaryColor: '#f09124'
  displayFont: '"https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&display=swap" rel="stylesheet"'
  textFont: https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Manrope:wght@200..800&family=Outfit:wght@100..900&display=swap" rel="stylesheet
  spacingPatterns:
    - name: '200'
      mobile: 200px
      tablet: 200px
      desktop: 200px
pageInclude: null
modules:
  - type: MapBox
    style: pk.eyJ1Ijoic3R1ZGlvLWF1dG9ub21hIiwiYSI6ImNtY3V2d3dtMTA0ZXgycnB4OW01cjlqb2QifQ.3NMaRt1maLlqTv6nlVqVHA
    token: mapbox://styles/studio-autonoma/cmsz20c6j009y01s0c0zx2bbz
    centerLng: '-46.769'
    centerLat: '-23.461'
    zoom: '13.06'
    bearing: '0'
    pitch: '0'
    layers: ti-jaragua
    columnAlign: left
    floatingText: false
    views:
      - id: mapview_1
        centerLng: '-46.677'
        centerLat: '-23.520'
        zoom: '9.64'
        mobileZoom: ''
        duration: '2000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          pateo-collegio
          capela-barueri
          exploracao-ouro-sp
        title: ''
        notes: ''
        items: []
      - id: mapview_2
        centerLng: '-23.548'
        centerLat: '-46.633'
        zoom: '16.39'
        mobileZoom: ''
        duration: '2000'
        bearing: '0'
        pitch: '0'
        layers: pateo-collegio-area
        title: ''
        notes: ''
        items: []
components:
  - type: Group
    id: capa_1
    shortTitle: capa_1
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: true
              content: '# Teste Geostory Witness'
        column2:
          components:
            - type: Spacer
              desktop: 150px
              tablet: 150px
              mobile: 150px
            - type: Text
              hasDropCap: false
              content: '#### Aqui você vai aprender a desenhar sua geo-história na plataforma Documental, combinando mapas, textos, vídeos, imagens e outros conjuntos de dados para contar histórias locais a audiências globais.'
  - type: Group
    id: capa_2
    shortTitle: capa_2
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: ColumnSticky
        txtColor: '#ffffffff'
        bgColor: '#3a7e7dff'
        paddingTop: true
        paddingBottom: true
        layout: text-bigger
        title: Teste Geostory Witness
        components:
          - type: Spacer
            desktop: 250px
            tablet: 250px
            mobile: 250px
          - type: Text
            hasDropCap: false
            content: '##### Aqui você vai aprender a desenhar sua geo-história na plataforma Documental, combinando mapas, textos, vídeos, imagens e outros conjuntos de dados para contar histórias locais a audiências globais.'
  - type: Map
    id: map1
    shortTitle: colonial heritage
    longTitle: Colonial Heritage
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    bgColor: Secundary
    components:
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: mapview_1
      - type: Spacer
        desktop: 800px
        tablet: 800px
        mobile: 400px
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: mapview_2
      - type: Spacer
        desktop: 800px
        tablet: 800px
        mobile: 400px
    columnAlign: right
    floatingText: true
---
