---
standalone: true
title: Home
slug: home
projeto: Landing Page
pageSettings:
  language: pt-BR
  link_pt_br: '#'
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
    shortTitle: Capa
    longTitle: Home
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
              content: '## **plataforma open source para construção e publicação de histórias com dados e cartografias multimídia**'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '#### **DOCUMENTAL é uma ferramenta desenvolvida para fortalecer direitos humanos, territoriais e ambientais na esfera pública utilizando o poder das novas mídias digitais.**'
  - type: Group
    id: Por que usar a Documental?
    shortTitle: Por que usar a Documental?
    longTitle: ''
    description: ''
    showInMenu: false
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
              content: '## O poder da visualização de dados nas mãos de ativistas, comunidades e organizações civis para a defesa de direitos humanos e ambientais'
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '##### Através de um aplicativo de fácil manipulação e interface intuitiva, DOCUMENTAL permite combinar um conjuntos complexos de informações – dados, textos, fotos, vídeos, imagens de satélite, mapas – em histórias digitais geolocalizadas. Desenvolvida principalmente para movimentos sociais e organizações civis, DOCUMENTAL é gratuita e não exige conhecimentos de programação complexos.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Button
              link:
                url: '#Downloads'
                target: _self
                text: Baixar app DOCUMENTAL
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
                text: Guia de Instalação e uso
              icon: ''
              size: ''
  - type: Group
    id: Qual o objetivo da plataforma?
    shortTitle: Qual o objetivo da plataforma?
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
              content: '# Qual o objetivo da plataforma?'
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '##### Desenhada como instrumento de defesa de direitos humanos e ambientais, DOCUMENTAL é uma ferramenta open-source para que movimentos sociais, organizações civis, jornalistas e pesquisadores documentem e comuniquem histórias locais para audiências globais de forma envolvente e visualmente impactante.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### Em um cenário de excesso de informação e desinformação, reunir dados verificados e georreferenciados é cada vez mais importante.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### A plataforma busca fortalecer a capacidade da sociedade civil de investigar e documentar violações cometidas por Estados e corporações, empoderando atores locais para comunicarem suas histórias através de novas tecnologias de visualização e mapeamento de dados, e ampliando o debate públicos sobre justiça social e ambiental.'
  - type: Group
    id: Projetos realizados com a DOCUMENTAL
    shortTitle: Projetos realizados com a DOCUMENTAL
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
              content: '# Projetos realizados com a DOCUMENTAL'
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
            text: Cartografia da Terra Indígena Guarani do Jaraguá. Defesa, cuidado e reparação pelo modo de vida guarani. Uma parceria entre pesquisadores e líderes da TI Jaraguá, Agência Autônoma, Chão Coletivo e Plataforma Práticas Espaciais (Escola da Cidade).
          - link:
              url: https://documental.xyz/expulsions/
              target: ''
              customTarget: ''
            img:
              src: /uploads/captura-de-tela-2026-08-18-as-16.08-copiar.jpg
              alt: ''
            title: Expulsões
            text: Investigação sobre violações de direitos humanos e ambientais decorrentes da implantação de um megaprojeto de mineração na Amazônia equatoriana. Realizado através da parceria entre a Agência Autônoma e o Forensic Architecture.
      - type: CardsCall
        cardsCallArr:
          - link:
              url: https://memoriadaterra.org/
              target: ''
              customTarget: ''
            img:
              src: /uploads/usaressamemoria.jpg
              alt: ''
            title: Memória da Terra
            text: Mapeamento do Complexo Arqueológico Xavante através de modelagem 3D, análise de imagens de satélite e caminhadas com anciãos, pela defesa e preservação de seu território.
          - link:
              url: https://documental.xyz/territorios-de-excecao/
              target: ''
              customTarget: ''
            img:
              src: /uploads/captura-de-tela-2026-08-18-as-16.07-copiar.jpg
              alt: ''
            title: Territórios de Exceção
            text: Mapeamento e análise do uso de helicópteros como plataforma de disparos em ações policiais nas favelas do Rio de Janeiro. Uma parceria entre agência autônoma, MediaLab e Redes da Maré.
      - type: Spacer
        desktop: 100px
        tablet: ''
        mobile: ''
  - type: Group
    id: Como a plataforma funciona?
    shortTitle: Como a plataforma funciona?
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
              content: '# Como a plataforma funciona?'
            - type: Spacer
              desktop: 20px
              tablet: 20px
              mobile: 20px
            - type: Button
              link:
                url: '#Downloads'
                target: _blank
                text: Baixar app DOCUMENTAL
              icon: ''
              size: wide
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '##### DOCUMENTAL combina _scrollytelling_ – técnica de _web design_ para criar histórias multimídia que se desenrolam à medida que o usuário percorre a página – com a navegação em dados georreferenciados em sistema GIS.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### A plataforma monta os conteúdos e controla a dinâmica do _scroll_, integrando visualização de dados em mapas interativos. Com parâmetros facilmente customizáveis, a plataforma permite total controle sobre o design do conteúdo, oferecendo um recurso poderoso para criar histórias visuais nos mais diversos formatos.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### A edição acontece através de um aplicativo intuitivo e de fácil utilização: nele você cria seu usuário, monta o ambiente de trabalho, e edita o projeto para publicação online.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### O aplicativo foi desenhado para funcionar mesmo sem conexão direta com a internet, ampliando o acesso a comunidades em áreas sem conexão estável.'
  - type: Group
    id: Documental é software livre
    shortTitle: Documental é software livre
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
              content: '## Documental é software livre: não tem custos de instalação ou atualização, e pode ser usada, copiada, modificada e redistribuída sem restrições.'
        column2:
          components: []
  - type: Group
    id: Como publicar com a DOCUMENTAL
    shortTitle: Como publicar com a DOCUMENTAL
    longTitle: ''
    description: ''
    showInMenu: false
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
              content: '# **Como publicar com a DOCUMENTAL**'
            - type: Spacer
              desktop: 20px
              tablet: 20px
              mobile: 20px
            - type: Text
              hasDropCap: false
              content: |-
                ##### O código da DOCUMENTAL está no GitHub. A partir dele, você escolhe como colocar sua história no ar:

                #####
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Timeline
              components:
                - type: TimelineBullet
                  text: 1. GitHub Pages
                  content: '###### Para histórias simples, você publica de forma gratuita usando o próprio GitHub Pages, sem precisar de servidor.'
                - type: Spacer
                  desktop: 50px
                  tablet: ''
                  mobile: ''
                - type: TimelineBullet
                  text: 2. No seu próprio servidor
                  content: '###### Copie o código do GitHub e instale a plataforma no servidor da sua organização, com controle total sobre os dados.'
                - type: Spacer
                  desktop: 50px
                  tablet: ''
                  mobile: ''
                - type: TimelineBullet
                  text: 3. Em nosso servidor
                  content: '###### Seu projeto pode utilizar a plataforma em nosso servidor, sem necessidade de instalação. Oferecemos infraestrutura e suporte técnico para a implementação e utilização da plataforma para movimentos sociais e entidades de defesa de direitos humanos e ambientais. Projetos podem ser submetidos através do email documental@autonoma.xyz.'
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
                    text: Código aberto e livre para uso. Baixe o código no nosso repositório e instale a DOCUMENTAL no seu servidor.
                    link:
                      url: https://github.com/Documental-xyz/
                      target: _blank
                      customTarget: ''
                      text: Acessar o repositório
                    icon: ''
                - Card:
                    type: Card
                    title: Guia de instalação e uso
                    text: Documentação completa de como instalar e usar a DOCUMENTAL, com informações detalhadas e passo a passo.
                    link:
                      url: /docs
                      target: _blank
                      customTarget: ''
                      text: Acessar a documentação
                    icon: ''
                - Card:
                    type: Card
                    title: Licença
                    text: Termos de uso da DOCUMENTAL.
                    link:
                      url: /licenca
                      target: _blank
                      customTarget: ''
                      text: Ver a licença
                    icon: ''
  - type: Group
    id: Faça parte da comunidade
    shortTitle: Faça parte da comunidade
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
              content: '# Faça parte da comunidade'
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '##### A Documental é mantida por uma comunidade aberta. Participe: tire dúvidas, troque experiências e formas de fazer, faça sugestões de melhorias, traduza ou contribua com o desenvolvimento.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Button
              link:
                url: https://github.com/Documental-xyz/Core/issues
                target: _blank
                text: Participe
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
              text: Download do app versão Desktop para Linux x64 no formato AppImage.
              link:
                url: https://github.com/Documental-xyz/App-Desktop/releases/download/v0.90.0/Documental-0.90.0.AppImage
                target: _blank
                customTarget: ''
                text: Baixar o app para Linux
              icon: ''
          - Card:
              type: Card
              title: Windows
              text: Download do instalador do app versão Desktop para Windows x64.
              link:
                url: https://github.com/Documental-xyz/App-Desktop/releases/download/v0.90.0/Documental-Setup-0.90.0.exe
                target: _blank
                customTarget: ''
                text: Baixar o app para Windows
              icon: ''
          - Card:
              type: Card
              title: MacOSX
              text: Download do app versão Desktop para MacOSX x64 no formato .dmg
              link:
                url: https://github.com/Documental-xyz/App-Desktop/releases/download/v0.90.0/Documental-0.90.0.dmg
                target: _blank
                customTarget: ''
                text: Baixar o app para Mac
              icon: ''
          - Card:
              type: Card
              title: Outras versões
              text: Para outros formatos e versões de download do app, acesse a aba releases GitHub.
              link:
                url: https://github.com/Documental-xyz/App-Desktop/releases/
                target: _blank
                customTarget: ''
                text: Acesse aqui
              icon: ''
      - type: Spacer
        desktop: 100px
        tablet: ''
        mobile: ''
  - type: Group
    id: Documentação
    shortTitle: Documentação
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
              content: '# Documentação'
        column2:
          components: []
      - type: Cards
        cardsArr:
          - Card:
              type: Card
              title: GitHub
              text: Código aberto e livre para uso. Baixe o código no nosso repositório e instale a DOCUMENTAL no seu servidor.
              link:
                url: https://github.com/Documental-xyz/
                target: _blank
                customTarget: ''
                text: Acesse aqui
              icon: ''
          - Card:
              type: Card
              title: Guia de instalação e uso
              text: Documentação completa de como instalar e usar a DOCUMENTAL, com informações detalhadas e passo a passo.
              link:
                url: /docs
                target: _blank
                customTarget: ''
                text: Acesse aqui
              icon: ''
          - Card:
              type: Card
              title: Licença
              text: Termos de uso da DOCUMENTAL.
              link:
                url: /licenca
                target: _blank
                customTarget: ''
                text: Acesse aqui
              icon: ''
      - type: Spacer
        desktop: 100px
        tablet: ''
        mobile: ''
  - type: Group
    id: Créditos
    shortTitle: Créditos
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
              content: '#### A DOCUMENTAL é desenvolvida pela agência autônoma: cidades territórios e direitos – laboratório de justiça espacial da FAU-UnB, e pelo MediaLab (UFRJ).'
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### Direção: Paulo Tavares e Fernanda Bruno

                ###### Coordenação: Paula Marujo

                ###### Implementação: Julia Veras

                ###### Desenvolvimento front-end: atonal.studio 

                ###### Desenvolviment backend e app: Thiago Paixão 

                ###### A [primeira versão da plataforma](http://v1.documental.xyz) foi desenvolvida em 2019 com a participação dos pesquisadores e designers Marlus Araújo, Adriano Belisário e Rafael Bantu
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
