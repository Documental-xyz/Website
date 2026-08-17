---
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
  highlightColor: '#3c8bc8'
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
    customBgColor: '#1691c5ff'
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/capa_projeto_memoria-da-terra.png
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
              content: '## uma plataforma digital de livre uso e código aberto para criação e publicação de narrativas cartográficas multimídia'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: A Documental apoia investigações baseadas em dados geoespaciais sobre violações de direitos humanos, territoriais e ambientais, para fins de advocacia e reparação histórica.
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Button
              link:
                url: '#Downloads'
                target: _self
                text: Baixar App
              icon: ''
              size: ''
            - type: Spacer
              desktop: 25px
              tablet: ''
              mobile: ''
            - type: Button
              link:
                url: /docs
                target: _blank
                text: Guia de Instalação e Uso
              icon: ''
              size: ''
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
        paddingTop: true
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '# Por que usar a Documental?'
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '##### Organizar dados no espaço e no tempo traz força, clareza e credibilidade a uma investigação. Com uma interface intuitiva, a Documental combina código, imagem e cartografia para transformar conjuntos complexos de dados – textos, fotos, vídeos, imagens de satélite e mapas – em narrativas visuais interativas, em que episódios de violência aparecem como evidências conectadas, e não como casos isolados.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### Desenhada para a realidade de movimentos sociais e organizações de defesa de direitos, a Documental é gratuita e não exige conhecimento técnico avançado: qualquer pessoa pode criar e publicar uma investigação visual, sem saber programar.'
  - type: Group
    id: Destaque
    shortTitle: Destaque
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
      - type: Column
        paddingTop: false
        paddingBottom: false
        components:
          - type: Text
            hasDropCap: false
            content: '### Documental é um software livre: não tem custos de instalação ou atualização, e pode ser usado, copiado, estudado, modificado e redistribuído sem quaisquer restrições.'
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
              content: '# Qual o objetivo da plataforma?'
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '##### Pensada como instrumento de defesa de direitos humanos e ambientais, a Documental opera como uma ferramenta open-source para que movimentos sociais, organizações civis e jornalistas documentem e comuniquem histórias locais a audiências globais, de forma envolvente e visualmente impactante.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### Em um cenário de excesso de informação e desinformação, reunir dados verificados e referenciados é cada vez mais importante. A plataforma busca fortalecer a capacidade da sociedade civil de investigar e documentar violações cometidas por Estados e corporações, empoderando atores locais para comunicarem suas histórias através de novas tecnologias de visualização e mapeamento de dados, e ampliando o debate públicos sobre justiça social e ambiental.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: ''
  - type: Group
    id: Projetos realizados com a plataforma
    shortTitle: Projetos realizados com a plataforma
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
              content: '# Projetos realizados com a plataforma'
        column2:
          components:
            - type: Spacer
              desktop: 10px
              tablet: ''
              mobile: ''
      - type: CardsCall
        cardsCallArr:
          - link:
              url: https://v1.documental.xyz/pt/alter-ameacada
              target: ''
              customTarget: ''
            img:
              src: /uploads/alter-do-chao-azul.png
              alt: ''
            title: Alter do Chão Ameaçada
            text: Mapeamento por satélite do território Borari em Santarém (PA) contra a especulação imobiliária, pela demarcação da Terra Indígena.
          - link:
              url: https://documental.xyz/territorios-de-excecao/
              target: ''
              customTarget: ''
            img:
              src: /uploads/territorios-de-excecao-azul.png
              alt: ''
            title: Territórios de Exceção
            text: Investigação sobre helicópteros como plataforma de disparos da polícia nas favelas do Rio, com dados, campo e arquitetura forense em 3D.
      - type: CardsCall
        cardsCallArr:
          - link:
              url: https://documental.xyz/expulsions/
              target: ''
              customTarget: ''
            img:
              src: /uploads/expulsion-san-marcos-azul.png
              alt: ''
            title: Expulsões
            text: 'Mineração na Cordilheira do Condor (Amazônia equatoriana): despossessão de povos indígenas, desmatamento e destruição de sítios arqueológicos.'
          - link:
              url: https://documental.xyz/nhanderekoa/
              target: ''
              customTarget: ''
            img:
              src: /uploads/imagem_16_ocupacao_antena-azul.png
              alt: ''
            title: Nhanderekoa
            text: 'Cartografia da Terra Indígena Guarani do Jaraguá (SP) na sua demarcação: defesa, cuidado e reparação da floresta.'
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
              content: '# Como a plataforma funciona?'
            - type: Spacer
              desktop: 20px
              tablet: 20px
              mobile: 20px
            - type: Button
              link:
                url: '#Downloads'
                target: _blank
                text: Baixar o aplicativo da Documental
              icon: ''
              size: wide
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '##### Aberta e totalmente customizável, você adapta ao seu projeto sem precisar de programação avançada.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### Ela combina scrollytelling – técnica de web design para criar histórias multimídia que se desenrolam à medida que o usuário percorre a página – com a navegação em dados GIS (Sistema de Informação Geográfica). Na interface, você monta os conteúdos e controla a dinâmica do scroll, integrados à visualização de dados em mapas interativos.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### Com parâmetros facilmente customizáveis, a plataforma permite que o usuário tenha total controle sobre o design do conteúdo, oferecendo um recurso poderoso para criar narrativas visuais nos mais diversos formatos.'
            - type: Spacer
              desktop: 50px
              tablet: ''
              mobile: ''
            - type: Text
              hasDropCap: false
              content: '##### A edição acontece no nosso aplicativo: nele você cria seu usuário, monta o ambiente de trabalho e edita o projeto mesmo sem internet, o que amplia o acesso a comunidades isoladas ou a quem não tem uma conexão contínua ou estável.'
  - type: Group
    id: 3 formas de publicar
    shortTitle: 3 formas de publicar
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
              content: '# Como começar: 3 formas de publicar'
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
                  content: '###### Seu projeto pode utilizar a plataforma em nosso servidor, sem necessidade de instalação. Oferecemos infraestrutura e suporte técnico para a implementação e utilização da plataforma para movimentos sociais e entidades de defesa de direitos humanos e ambientais. Projetos podem ser submetidos através do email autonoma@autonoma.xyz.'
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
                    text: Código aberto e livre para uso. Baixe o código no nosso repositório e instale a Documental no seu servidor.
                    link:
                      url: https://github.com/Documental-xyz/
                      target: _blank
                      customTarget: ''
                      text: Acesse o repositório
                    icon: ''
                - Card:
                    type: Card
                    title: Guia de instalação e uso
                    text: Documentação completa de como instalar e usar a Documental, com informações detalhadas e passo a passo.
                    link:
                      url: /docs
                      target: _blank
                      customTarget: ''
                      text: Acessar a documentação
                    icon: ''
                - Card:
                    type: Card
                    title: Licença
                    text: Termos de uso da Documental
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
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: '# Faça parte da comunidade'
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '##### A Documental é mantida por uma comunidade aberta. Participe: tire dúvidas, troque experiências e formas de fazer, faça sugestão de melhorias, traduza ou contribua com o desenvolvimento.'
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
                text: Baixar o app
              icon: ''
          - Card:
              type: Card
              title: Windows
              text: Download do instalador do app versão Desktop para Windows x64.
              link:
                url: https://github.com/Documental-xyz/App-Desktop/releases/download/v0.90.0/Documental-Setup-0.90.0.exe
                target: _blank
                customTarget: ''
                text: Acesse aqui
              icon: ''
          - Card:
              type: Card
              title: MacOSX
              text: Download do app versão Desktop para MacOSX x64 no formato .dmg
              link:
                url: https://github.com/Documental-xyz/App-Desktop/releases/download/v0.90.0/Documental-0.90.0.dmg
                target: _blank
                customTarget: ''
                text: Acesse aqui
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
              text: Código aberto e livre para uso. Baixe o código no nosso repositório e instale a Documental no seu servidor.
              link:
                url: https://github.com/Documental-xyz/
                target: _blank
                customTarget: ''
                text: Acesse aqui
              icon: ''
          - Card:
              type: Card
              title: Guia de instalação e uso
              text: Documentação completa de como instalar e usar a Documental, com informações detalhadas e passo a passo.
              link:
                url: /docs
                target: _blank
                customTarget: ''
                text: Acesse aqui
              icon: ''
          - Card:
              type: Card
              title: Licença
              text: Termos de uso da Documental
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
      - type: Column
        paddingTop: false
        paddingBottom: false
        components:
          - type: Text
            hasDropCap: false
            content: '##### A plataforma web Documental é desenvolvida pela agência autônoma: cidades territórios e direitos, laboratório de justiça espacial da FAU-UnB e pelo MediaLab (UFRJ)'
          - type: Spacer
            desktop: 20px
            tablet: 20px
            mobile: 20px
          - type: LogosGroup
            logos:
              - image: /uploads/autonoma-black-redim.png
                link:
                  url: https://autonoma.xyz
                  target: _blank
                  customTarget: ''
                  title: Autonoma
              - image: /uploads/media-lab-novo-logo.png
                link:
                  url: https://medialabufrj.net
                  target: _blank
                  customTarget: ''
                  title: Media Lab UFRJ
---
