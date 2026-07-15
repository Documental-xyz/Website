---
standalone: true
title: Nhanderekoa
slug: nhanderekoa
projeto: Nhanderekoa
pageSettings:
  language: pt-BR
  link_pt_br: nhanderekoa
  link_en: nhanderekoa-en
  link_es: nhanderekoa-es
  animations: enable_all
  direction: left
  seoTitle: ''
  seoDescription: ''
  seoKeywords: []
  seoImage: ''
pageTheme:
  primaryColor: '#000000'
  secondaryColor: '#14882a'
  highlightColor: '#ffffff'
  auxiliaryColor: '#484848'
  displayFont: ''
  textFont: ''
  spacingPatterns:
    - name: Padrão
      mobile: '10'
      tablet: '11'
      desktop: '12'
modules:
  - type: MapBox
    style: mapbox://styles/studio-autonoma/cmeh5enc900ni01s488ll9iq1
    token: pk.eyJ1Ijoic3R1ZGlvLWF1dG9ub21hIiwiYSI6ImNtY3V2d3dtMTA0ZXgycnB4OW01cjlqb2QifQ.3NMaRt1maLlqTv6nlVqVHA
    centerLng: '-46.782'
    centerLat: '-23.461'
    zoom: '13.26'
    bearing: '0'
    pitch: '0'
    layers: |-
      ti-jaragua
      camada-cor
      satelite
    columnAlign: center
    floatingText: false
    views:
      - id: map1_ti
        centerLng: '-46.782'
        centerLat: '-23.461'
        zoom: '13.26'
        mobileZoom: '11.70'
        duration: '3000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          aldeias-jaragua
          pe-jaragua
          memoria-guarani
          camada-cor
          satelite
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#fb8f13'
            typeIcon: outlined
            iconFill: false
            text: Pontos de Memória Indígena
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Limite do Parque Estadual Jaraguá
      - id: map1_ytu
        centerLng: '-46.754'
        centerLat: '-23.465'
        zoom: '16.96'
        mobileZoom: '16.00'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          aldeias-jaragua-label[nome_aldei==Ytu]
          aldeias-jaragua[nome_aldei==Ytu]
          pe-jaragua
          camada-cor
          satelite
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Limite do Parque Estadual Jaraguá
      - id: map1_pyau
        centerLng: '-46.753'
        centerLat: '-23.465'
        zoom: '16.80'
        mobileZoom: '15.80'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          aldeias-jaragua-label[nome_aldei==Pyau]
          aldeias-jaragua[nome_aldei==Pyau]
          pe-jaragua
          satelite
          camada-cor
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Limite do Parque Estadual Jaraguá
      - id: map1_itakupe
        centerLng: '-46.763'
        centerLat: '-23.446'
        zoom: '15.60'
        mobileZoom: '14.60'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          aldeias-jaragua-label[nome_aldei==Itakupe]
          aldeias-jaragua[nome_aldei==Itakupe]
          pe-jaragua
          satelite
          camada-cor
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Limite do Parque Estadual Jaraguá
      - id: map1_itawera
        centerLng: '-46.755'
        centerLat: '-23.464'
        zoom: '16.97'
        mobileZoom: '15.60'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          aldeias-jaragua-label[nome_aldei==Itawera]
          aldeias-jaragua[nome_aldei==Itawera]
          pe-jaragua
          satelite
          camada-cor
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Limite do Parque Estadual Jaraguá
      - id: map1_itaendy
        centerLng: '-46.778'
        centerLat: '-23.462'
        zoom: '15.94'
        mobileZoom: '15.00'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          aldeias-jaragua[nome_aldei==Itaendy]
          aldeias-jaragua-label[nome_aldei==Itaendy]
          pe-jaragua
          satelite
          camada-cor
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Limite do Parque Estadual Jaraguá
      - id: map1_yvypora
        centerLng: '-46.756'
        centerLat: '-23.466'
        zoom: '16.40'
        mobileZoom: '15.40'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          aldeias-jaragua-label[nome_aldei==Yvy Porã]
          aldeias-jaragua[nome_aldei==Yvy Porã]
          pe-jaragua
          satelite
          camada-cor
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Limite do Parque Estadual Jaraguá
      - id: map1_pindomirim
        centerLng: '-46.780'
        centerLat: '-23.450'
        zoom: '15.81'
        mobileZoom: '14.80'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          aldeias-jaragua-label[nome_aldei==Pindó Mirim]
          aldeias-jaragua[nome_aldei==Pindó Mirim]
          pe-jaragua
          satelite
          camada-cor
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Limite do Parque Estadual Jaraguá
      - id: map1_mirim
        centerLng: '-46.753'
        centerLat: '-23.461'
        zoom: '16.38'
        mobileZoom: '15.40'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          aldeias-jaragua-label[nome_aldei==Tekoa Mirim]
          aldeias-jaragua[nome_aldei==Tekoa Mirim]
          pe-jaragua
          satelite
          camada-cor
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Limite do Parque Estadual Jaraguá
      - id: map1_kaaguymirim
        centerLng: '-46.753'
        centerLat: '-23.460'
        zoom: '16.53'
        mobileZoom: '15.50'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          aldeias-jaragua-label[nome_aldei==Ka'aguy Mirim]
          aldeias-jaragua[nome_aldei==Ka'aguy Mirim]
          pe-jaragua
          satelite
          camada-cor
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Limite do Parque Estadual Jaraguá
      - id: map1_fimti
        centerLng: '-46.765'
        centerLat: '-23.461'
        zoom: '13.26'
        mobileZoom: '13.26'
        duration: '3000'
        bearing: '0'
        pitch: '0'
        layers: ti-jaragua
        title: ''
        notes: ''
        items: []
      - id: map2_jaraguasptudo
        centerLng: '-46.850'
        centerLat: '-23.500'
        zoom: '9.92'
        mobileZoom: '7.70'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          pateo-collegio
          capela-barueri
          estacao-jaragua
          afonso-sardinha
          muros-jaragua
          vestigios-mineracao
          exploracao-ouro-sp
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: true
            text: Patrimônio colonial
          - icon: circle
            colorIcon: '#d28fef37'
            typeIcon: outlined
            iconFill: true
            text: Áreas de exploração do ouro em São Paulo
      - id: map2_pateo
        centerLng: '-46.634'
        centerLat: '-23.548'
        zoom: '16.20'
        mobileZoom: '15.20'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          pateo-collegio-area
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: true
            text: Patrimônio colonial
      - id: map2_barueri
        centerLng: '-46.785'
        centerLat: '-23.505'
        zoom: '11.41'
        mobileZoom: '9.50'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          pateo-collegio
          pateo-collegio-label
          capela-barueri
          capela-barueri-label
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: true
            text: Patrimônio colonial
      - id: map2_ourojaragua
        centerLng: '-46.769'
        centerLat: '-23.456'
        zoom: '13.04'
        mobileZoom: '11.50'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          afonso-sardinha
          afonso-sardinha-label
          muros-jaragua
          muros-jaragua-label
          vestigios-mineracao
          vestigios-label
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Patrimônio colonial
      - id: map2_jaraguasp
        centerLng: '-46.850'
        centerLat: '-23.500'
        zoom: '9.92'
        mobileZoom: '7.50'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          exploracao-ouro-sp
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: true
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#d28fef37'
            typeIcon: outlined
            iconFill: true
            text: Áreas de exploração do ouro em São Paulo
      - id: map2_fim
        centerLng: '-46.765'
        centerLat: '-23.461'
        zoom: '13.52'
        mobileZoom: '13.52'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: ti-jaragua
        title: ''
        notes: ''
        items: []
      - id: map3_jaragua
        centerLng: '-46.789'
        centerLat: '-23.460'
        zoom: '13.26'
        mobileZoom: '11.50'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          aldeias-jaragua
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
      - id: map3_set2013
        centerLng: '-46.753'
        centerLat: '-23.460'
        zoom: '13.26'
        mobileZoom: '12.26'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          locais-manifestacoes[fid==1]
          texto-locais[fid==1]
          ti-jaragua
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Local do ato
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
      - id: map3_out2013
        centerLng: '-46.702'
        centerLat: '-23.511'
        zoom: '11.40'
        mobileZoom: '9.50'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          locais-manifestacoes[fid==1]
          texto-locais[fid==1]
          trajetos-atos[num==1]
          marca-trajetos[num==1]
          areas-protestos[tag==1]
          ti-jaragua
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: true
            text: Terra Indígena Jaraguá
      - id: map3_2013zoom
        centerLng: '-46.656'
        centerLat: '-23.573'
        zoom: '13.74'
        mobileZoom: '12.74'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          trajetos-atos[num==1]
          marca-trajetos[num==1]
          adds-2013
          adds-2013-label
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Trajeto do ato
      - id: map3_abr2014
        centerLng: '-46.646'
        centerLat: '-23.565'
        zoom: '13.27'
        mobileZoom: '11.50'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          areas-protestos[tag==2]
          legenda-areas[tag==2]
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Local do ato
      - id: map3_masp2014
        centerLng: '-46.646'
        centerLat: '-23.565'
        zoom: '13.27'
        mobileZoom: '11.50'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          areas-protestos[tag==2]
          legenda-areas[tag==2]
          trajetos-atos[num==2]
          marca-trajetos[num==2]
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Trajeto do protesto
      - id: map3_2014assembleia
        centerLng: '-46.646'
        centerLat: '-23.565'
        zoom: '13.27'
        mobileZoom: '11.50'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          assembleia
          label-assembleia
          areas-protestos[tag==2]
          legenda-areas[tag==2]
          trajetos-atos[num==2]
          marca-trajetos[num==2]
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Local do ato
      - id: map3_2016
        centerLng: '-46.658'
        centerLat: '-23.560'
        zoom: '15.23'
        mobileZoom: '14.20'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          locais-manifestacoes[fid==2]
          texto-locais[fid==2]
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Local do ato
      - id: map3_anulacao
        centerLng: '-46.702'
        centerLat: '-23.511'
        zoom: '11.40'
        mobileZoom: '9.30'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          antenas-ocupacao
          texto-ocupacao 
          texto-locais[fid==3]
          locais-manifestacoes[fid==3]
          ti-jaragua
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#0e9013ff'
            typeIcon: outlined
            iconFill: true
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Local do ato
      - id: map3_2020
        centerLng: '-46.752'
        centerLat: '-23.467'
        zoom: '14.46'
        mobileZoom: '12.46'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          locais-manifestacoes[fid==5]
          texto-locais[fid==5]
          ti-jaragua
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#0e9013ff'
            typeIcon: outlined
            iconFill: true
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Local do ato
      - id: map3_bloqueio
        centerLng: '-46.702'
        centerLat: '-23.507'
        zoom: '11.40'
        mobileZoom: '9.20'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          label-pejaragua-antenas
          label-pejaragua-bloqueio
          pejaragua-bloqueioband
          locais-manifestacoes[fid==8]
          texto-locais[fid==8]
          ti-jaragua
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#0e9013ff'
            typeIcon: outlined
            iconFill: true
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Local do ato
      - id: map3_julho2021
        centerLng: '-46.658'
        centerLat: '-23.559'
        zoom: '14.11'
        mobileZoom: '13.11'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          marca-trajetos[num==3]
          trajetos-atos[num==3]
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Trajeto percorrido
      - id: map3_junho22
        centerLng: '-46.655'
        centerLat: '-23.574'
        zoom: '13.80'
        mobileZoom: '12.00'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          trajetos-atos[num==7]
          marca-trajetos[num==7]
          adds-2013
          adds-2013-label
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Trajeto percorrido
      - id: map3_ago2022
        centerLng: '-46.636'
        centerLat: '-23.549'
        zoom: '14.97'
        mobileZoom: '13.97'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          trajetos-atos[num==5]
          marca-trajetos[num==5]
          adds-2022
          adds-2022-label
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Trajeto percorrido
      - id: map3_novomaio
        centerLng: '-46.761'
        centerLat: '-23.461'
        zoom: '13.51'
        mobileZoom: '12.00'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          leg-caminhada
          caminhada-vida
          locais-manifestacoes[fid==9]
          texto-locais[fid==9]
          ti-jaragua
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#0e9013ff'
            typeIcon: outlined
            iconFill: true
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Local do ato
      - id: map3_teatro
        centerLng: '-46.638'
        centerLat: '-23.546'
        zoom: '14.88'
        mobileZoom: '13.88'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          locais-manifestacoes[fid==11]
          texto-locais[fid==11]
          adds-2022[label==Theatro Municipal]
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#c8094f'
            typeIcon: outlined
            iconFill: false
            text: Local do ato
      - id: map4_jaragua
        centerLng: '-46.782'
        centerLat: '-23.461'
        zoom: '13.26'
        mobileZoom: '12.00'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          pe-jaragua
          aldeias-jaragua
          memoria-guarani
          afonso-sardinha
          estacao-jaragua
          muros-jaragua
          complexo-turistico
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: circle
            colorIcon: '#fb8f13'
            typeIcon: outlined
            iconFill: false
            text: Lugares de memória Guarani
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#c15aed'
            typeIcon: outlined
            iconFill: false
            text: Patrimônio colonial
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Parque Estadual do Jaraguá
          - icon: circle
            colorIcon: '#d28fef60'
            typeIcon: outlined
            iconFill: true
            text: Área do núcleo turístico do Jaraguá
      - id: map4_afonsosardinha
        centerLng: '-46.758'
        centerLat: '-23.462'
        zoom: '16.57'
        mobileZoom: '15.00'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          pe-jaragua
          complexo-turistico
          aldeias-jaragua
          afonso-sardinha-label
          afonso-sardinha-zoom
        title: ''
        notes: ''
        items:
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#c15aed'
            typeIcon: outlined
            iconFill: false
            text: Patrimônio colonial
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Parque Estadual do Jaraguá
          - icon: circle
            colorIcon: '#d28fef60'
            typeIcon: outlined
            iconFill: true
            text: Área do núcleo turístico do Jaraguá
      - id: map4_jaraguaestacao
        centerLng: '-46.769'
        centerLat: '-23.460'
        zoom: '13.15'
        mobileZoom: '12.00'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          pe-jaragua
          complexo-turistico
          aldeias-jaragua
          afonso-sardinha-label
          afonso-sardinha
          estacao-jaragua-label
          estacao-jaragua
          muros-jaragua-label
          muros-jaragua
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#c15aed'
            typeIcon: outlined
            iconFill: false
            text: Patrimônio colonial
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Parque Estadual do Jaraguá
          - icon: circle
            colorIcon: '#d28fef60'
            typeIcon: outlined
            iconFill: true
            text: Área do núcleo turístico do Jaraguá
      - id: map4_pedreira
        centerLng: '-46.765'
        centerLat: '-23.447'
        zoom: '15.50'
        mobileZoom: '14.50'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          pe-jaragua
          complexo-turistico
          aldeias-jaragua
          aldeias-jaragua-label[nome_aldei==Itakupe]
          muros-jaragua-label
          muros-jaragua
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#c15aed'
            typeIcon: outlined
            iconFill: false
            text: Patrimônio colonial
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Parque Estadual do Jaraguá
      - id: map5_jaragua
        centerLng: '-46.780'
        centerLat: '-23.460'
        zoom: '13.45'
        mobileZoom: '12.00'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          pe-jaragua
          complexo-turistico
          aldeias-jaragua
          memoria-guarani
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: circle
            colorIcon: '#fb8f13'
            typeIcon: outlined
            iconFill: false
            text: Lugares de memória Guarani
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Parque Estadual do Jaraguá
          - icon: circle
            colorIcon: '#d28fef60'
            typeIcon: outlined
            iconFill: true
            text: Área do núcleo turístico do Jaraguá
      - id: map5_cacicajandira
        centerLng: '-46.753'
        centerLat: '-23.465'
        zoom: '16.30'
        mobileZoom: '14.80'
        duration: '4000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          pe-jaragua
          aldeias-jaragua
          memoria-guarani
          memoria-guarani-label
          ato-memoria-label
          complexo-turistico
          afonso-sardinha
          estacao-jaragua
          muros-jaragua
        title: ''
        notes: ''
        items:
          - icon: circle
            colorIcon: '#66ea5d'
            typeIcon: outlined
            iconFill: false
            text: Tekoas
          - icon: circle
            colorIcon: '#fb8f13'
            typeIcon: outlined
            iconFill: false
            text: Lugares de memória Guarani
          - icon: show_chart
            colorIcon: '#1b9613'
            typeIcon: outlined
            iconFill: false
            text: Terra Indígena Jaraguá
          - icon: circle
            colorIcon: '#c15aed'
            typeIcon: outlined
            iconFill: false
            text: Patrimônio colonial
          - icon: show_chart
            colorIcon: '#9b16d4'
            typeIcon: outlined
            iconFill: false
            text: Parque Estadual do Jaraguá
          - icon: circle
            colorIcon: '#d28fef60'
            typeIcon: outlined
            iconFill: true
            text: Área do núcleo turístico do Jaraguá
components:
  - type: Include
    slug: nhanderekoa2
  - type: Include
    slug: nhanderekoa3
---
