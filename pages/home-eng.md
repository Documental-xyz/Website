---
standalone: true
title: Home-ENG
slug: homeeng
projeto: Landing Page
pageSettings:
  language: en
  link_pt_br: home
  link_en: '#'
  link_es: '#'
  animations: enable_all
  direction: left
  seoTitle: homepage documental
  seoDescription: Homepage da plataforma documental.xyz
  seoKeywords:
    - keyword: documental
    - keyword: documental.xyz
    - keyword: agência autônoma
    - keyword: autônoma advocacy
  seoImage: ''
pageTheme:
  primaryColor: ''
  secondaryColor: '#ffffff'
  highlightColor: '#005aa9'
  auxiliaryColor: '#000000'
  displayFont: https://fonts.googleapis.com/css2?family=Roboto&display=swap
  textFont: https://fonts.googleapis.com/css2?family=Roboto&display=swap
  spacingPatterns:
    - name: default
      mobile: 10px
      tablet: 10px
      desktop: 10px
pageInclude: null
modules:
  - type: MapBox
    style: mapbox://styles/studio-autonoma/cmdgcs27u019101sa29ytbsps
    token: pk.eyJ1Ijoic3R1ZGlvLWF1dG9ub21hIiwiYSI6ImNtY3V2d3dtMTA0ZXgycnB4OW01cjlqb2QifQ.3NMaRt1maLlqTv6nlVqVHA
    centerLng: '10.706'
    centerLat: '29.771'
    zoom: '1.40'
    bearing: '0'
    pitch: '0'
    layers: ''
    columnAlign: left
    floatingText: false
    views: []
components:
  - type: Group
    id: Capa
    shortTitle: Documental
    longTitle: Documental
    description: ''
    showInMenu: true
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Custom
    customBgColor: '#005aa9ff'
    backgroundMedia:
      - type: backgroundVideo
        videoSrc: /uploads/usar-esse.mp4
    overlay: ''
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: ImageBlock
              wideImage: false
              src: /uploads/documental.png
              alt: ''
              description: ''
        column2:
          components:
            - type: Spacer
              desktop: 200px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '## **Open-source platform for building and publishing stories with data and multimedia cartographies**'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '#### DOCUMENTAL is a tool developed to strengthen human, territorial and environmental rights in the public sphere, harnessing the power of new digital media'
  - type: Group
    id: Why use Documental?
    shortTitle: Why use Documental?
    longTitle: ''
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '## **The power of data visualization in the hands of activists, communities and civil-society organizations for the defense of human and environmental rights**'
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '##### Through an easy-to-use app with an intuitive interface, DOCUMENTAL brings together complex sets of information – data, texts, photos, videos, satellite imagery, maps – into geolocated digital stories. Developed primarily for social movements and civil-society organizations, DOCUMENTAL is free and requires no advanced programming knowledge.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Button
              link:
                url: '#Downloads'
                target: _self
                text: Download the DOCUMENTAL app
              icon: ''
              size: ''
            - type: Spacer
              desktop: 25px
              tablet: ''
              mobile: ''
            - type: Button
              link:
                url: /docs
                target: _self
                text: Installation and use guide
              icon: ''
              size: ''
  - type: Group
    id: What is the platform's goal?
    shortTitle: What is the platform's goal?
    longTitle: ''
    description: ''
    showInMenu: true
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: '#005aa9ff'
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/captura-de-tela-2026-08-19-as-12.10.11.png
    overlay: ''
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: "# **What is the platform's goal?**"
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '##### Designed as an instrument for the defense of human and environmental rights, DOCUMENTAL is an open-source tool for social movements, civil-society organizations, journalists and researchers to document and communicate local stories to global audiences in an engaging and visually striking way.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### In a landscape of information overload and disinformation, bringing together verified and georeferenced data is increasingly important in the context of public and media advocacy.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: "##### The platform seeks to strengthen civil society's capacity to investigate and document violations committed by states and corporations, empowering local actors to communicate their stories through new technologies of data visualization and mapping — thereby broadening public debate on social and environmental justice."
  - type: Group
    id: Projects made with DOCUMENTAL
    shortTitle: Projects made with DOCUMENTAL
    longTitle: ''
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '# **Projects made with DOCUMENTAL**'
        column2:
          components:
            - type: Spacer
              desktop: 10px
              tablet: ''
              mobile: ''
      - type: CardsCall
        cardsCallArr:
          - link:
              url: https://documental.xyz/nhanderekoa/
              target: ''
              customTarget: ''
            img:
              src: /uploads/imagem-jaragua_original-copiar.jpg
              alt: ''
            title: Nhanderekoa
            text: Cartography of the Guarani Indigenous Land of Jaraguá. Defense, care and reparation grounded in the Guarani way of life. A partnership between researchers and leaders of the Jaraguá Indigenous Land, Autônoma , Chão Coletivo and Plataforma Práticas Espaciais (Escola da Cidade).
          - link:
              url: https://documental.xyz/expulsions/
              target: ''
              customTarget: ''
            img:
              src: /uploads/captura-de-tela-2026-08-18-as-16.08-copiar.jpg
              alt: ''
            title: Expulsions
            text: Investigation into the human and environmental rights violations resulting from the implementation of a large-scale mining project in the Ecuadorian Amazon. Carried out through a partnership between Autônoma and Forensic Architecture.
      - type: CardsCall
        cardsCallArr:
          - link:
              url: https://memoriadaterra.org/
              target: ''
              customTarget: ''
            img:
              src: /uploads/usaressamemoria.jpg
              alt: ''
            title: Memory of the Earth
            text: Mapping of the Xavante Archaeological Complex through 3D modeling, satellite image analysis and walks with elders, for the defense and preservation of their territory.
          - link:
              url: https://documental.xyz/territorios-de-excecao/
              target: ''
              customTarget: ''
            img:
              src: /uploads/captura-de-tela-2026-08-18-as-16.07-copiar.jpg
              alt: ''
            title: Territories of Exception
            text: Mapping and analysis of the use of helicopters as shooting platforms in police operations in the favelas of Rio de Janeiro. A partnership between Autônoma, MediaLab and Redes da Maré.
      - type: Spacer
        desktop: 100px
        tablet: ''
        mobile: ''
  - type: Group
    id: How does the platform work?
    shortTitle: How does the platform work?
    longTitle: ''
    description: ''
    showInMenu: true
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/memoria-capa.jpg
    overlay: ''
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '# **How does the platform work?**'
            - type: Spacer
              desktop: 20px
              tablet: 20px
              mobile: 20px
            - type: Button
              link:
                url: '#Downloads'
                target: _blank
                text: Download the DOCUMENTAL app
              icon: ''
              size: wide
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '##### DOCUMENTAL combines scrollytelling – a web-design technique for creating multimedia stories that unfold as the user scrolls through the page – with navigation through georeferenced data in a GIS system.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: "##### The platform assembles the content and controls the scroll dynamics, integrating data visualization into interactive maps. With easily customizable parameters, it allows full control over the content's design, offering a powerful resource to create visual stories in a wide range of formats."
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### Editing happens through an intuitive, easy-to-use app: in it you create your account, set up your workspace, and edit the project for online publication.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### The app was designed to work even without a direct internet connection, expanding access for communities in areas without stable connectivity.'
  - type: Group
    id: DOCUMENTAL is free software
    shortTitle: DOCUMENTAL is free software
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '## DOCUMENTAL is free software: it has no installation or update costs, and can be used, copied, modified and redistributed without restrictions.'
        column2:
          components: []
  - type: Group
    id: How to publish with DOCUMENTAL
    shortTitle: How to publish with DOCUMENTAL
    longTitle: ''
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '# **How to publish with DOCUMENTAL**'
            - type: Spacer
              desktop: 20px
              tablet: 20px
              mobile: 20px
            - type: Text
              hasDropCap: false
              content: "##### DOCUMENTAL's code is on GitHub. From there, you choose how to put your story online:"
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Timeline
              components:
                - type: TimelineBullet
                  text: 1. GitHub Pages
                  content: '###### For simple stories, you publish using GitHub Pages without needing a server.'
                - type: Spacer
                  desktop: 50px
                  tablet: ''
                  mobile: ''
                - type: TimelineBullet
                  text: 2. On your own server.
                  content: "###### Copy the code from GitHub and install the platform on your organization's server, with full control over the data."
                - type: Spacer
                  desktop: 50px
                  tablet: ''
                  mobile: ''
                - type: TimelineBullet
                  text: 3. On our server
                  content: '###### Your project can use the platform on our server. The DOCUMENTAL project offers infrastructure and technical support for implementing and using the platform for social movements and organizations defending human and environmental rights. Projects can be submitted at documental@autonoma.xyz.'
        column2:
          components:
            - type: Spacer
              desktop: 150px
              tablet: ''
              mobile: ''
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: GitHub
                    text: Open source and free to use. Download the code from our repository and install DOCUMENTAL on your server.
                    link:
                      url: https://github.com/Documental-xyz/
                      target: _blank
                      customTarget: ''
                      text: Access the repository
                    icon: ''
                - Card:
                    type: Card
                    title: Installation and use guide
                    text: Complete documentation on how to install and use DOCUMENTAL, with detailed, step-by-step information.
                    link:
                      url: /docs
                      target: _blank
                      customTarget: ''
                      text: Access the documentation
                    icon: ''
                - Card:
                    type: Card
                    title: License
                    text: DOCUMENTAL's terms of use.
                    link:
                      url: /licenca
                      target: _blank
                      customTarget: ''
                      text: View the license
                    icon: ''
  - type: Group
    id: Join the community
    shortTitle: Join the community
    longTitle: ''
    description: ''
    showInMenu: true
    animations: true
    txtColor: Secondary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '# **Join the community**'
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '##### DOCUMENTAL is maintained by an open community. Take part: ask questions, share experiences and ways of doing, suggest improvements, translate, or contribute to development.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Button
              link:
                url: https://github.com/Documental-xyz/Core/issues
                target: _blank
                text: Get involved
              icon: ''
              size: ''
  - type: Group
    id: Downloads
    shortTitle: Downloads
    longTitle: ''
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '# Downloads'
        column2:
          components: []
      - type: Cards
        cardsArr:
          - Card:
              type: Card
              title: Linux
              text: Download the Desktop app for Linux x64 in AppImage format.
              link:
                url: https://github.com/Documental-xyz/App-Desktop/releases/download/v0.91.0/Documental-0.91.0.AppImage
                target: _blank
                customTarget: ''
                text: Download the app for Linux
              icon: ''
          - Card:
              type: Card
              title: Windows
              text: Download the Desktop app installer for Windows x64.
              link:
                url: https://github.com/Documental-xyz/App-Desktop/releases/download/v0.91.0/Documental-Setup-0.91.0.exe
                target: _blank
                customTarget: ''
                text: Download the app for Windows
              icon: ''
          - Card:
              type: Card
              title: MacOSX
              text: Download the Desktop app for macOS x64 in .dmg format.
              link:
                url: https://github.com/Documental-xyz/App-Desktop/releases/download/v0.91.0/Documental-0.91.0.dmg
                target: _blank
                customTarget: ''
                text: Download the app for Mac
              icon: ''
          - Card:
              type: Card
              title: Other versions
              text: For other formats and versions of the app, visit the GitHub releases tab.
              link:
                url: https://github.com/Documental-xyz/App-Desktop/releases/
                target: _blank
                customTarget: ''
                text: Access here
              icon: ''
      - type: Spacer
        desktop: 100px
        tablet: ''
        mobile: ''
  - type: Group
    id: Documentação
    shortTitle: Documentation
    longTitle: ''
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '# Documentation'
        column2:
          components: []
      - type: Cards
        cardsArr:
          - Card:
              type: Card
              title: GitHub
              text: Open source and free to use. Download the code from our repository and install DOCUMENTAL on your server.
              link:
                url: https://github.com/Documental-xyz/
                target: _blank
                customTarget: ''
                text: Access here
              icon: ''
          - Card:
              type: Card
              title: Installation and use guide
              text: Complete documentation on how to install and use DOCUMENTAL, with detailed, step-by-step information.
              link:
                url: /docs
                target: _blank
                customTarget: ''
                text: Access here
              icon: ''
          - Card:
              type: Card
              title: License
              text: DOCUMENTAL's terms of use.
              link:
                url: /licenca
                target: _blank
                customTarget: ''
                text: Access here
              icon: ''
      - type: Spacer
        desktop: 100px
        tablet: ''
        mobile: ''
  - type: Group
    id: About DOCUMENTAL
    shortTitle: About DOCUMENTAL
    longTitle: ''
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '##### DOCUMENTAL is developed by Agência Autônoma: cidades, territórios e direitos, a spatial justice laboratory at FAU-UnB, and by MediaLab (UFRJ).'
        column2:
          components:
            - type: InnerColumns
              column1:
                components:
                  - type: Text
                    hasDropCap: false
                    content: |-
                      **Direction** Paulo Tavares e Fernanda Bruno

                      **Coordination** Paula Marujo

                      **Implementation** Julia Veras
              column2:
                components:
                  - type: Text
                    hasDropCap: false
                    content: |-
                      **Front-end** **Development** atonal.studio 

                      **Programming and app development** Thiago Paixão
            - type: Spacer
              desktop: 50px
              tablet: 25px
              mobile: 25px
            - type: Text
              hasDropCap: false
              content: '**The** [**first version of the platform**](http://v1.documental.xyz) was developed in 2019 with the participation of researchers and designers Marlus Araújo, Adriano Belisário and Rafael Bantu.'
            - type: LogosGroup
              logos:
                - image: /uploads/logo_autonoma_advocacia_BLACK.png
                  link:
                    url: https://www.advocacia.autonoma.xyz/
                    target: ''
                    customTarget: ''
                    title: ''
                - image: /uploads/logo-novo-medialab_escuro-1.png
                  link:
                    url: https://medialabufrj.net/
                    target: ''
                    customTarget: ''
                    title: ''
---
