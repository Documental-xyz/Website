---
standalone: true
title: Nhanderekoa Parte 2
slug: nhanderekoa2
projeto: Nhanderekoa
pageInclude:
  mainSlug: nhanderekoa
components:
  - type: Group
    id: home
    shortTitle: home
    longTitle: home
    description: título e resumo
    showInMenu: true
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia:
      - type: backgroundVideo
        videoSrc: /uploads/video_01_picojaragua.mp4
    overlay: ''
    components:
      - type: ColumnSticky
        txtColor: '#ffffffff'
        bgColor: ''
        paddingTop: true
        paddingBottom: true
        layout: text-bigger
        title: NHANDEREKOA
        components:
          - type: Spacer
            desktop: 800px
            tablet: 800px
            mobile: 200px
          - type: Text
            hasDropCap: false
            content: '#### **cartografias da resistência territorial e da reparação ambiental Guarani na Terra Indígena Jaraguá**'
          - type: Spacer
            desktop: 500px
            tablet: 500px
            mobile: 100px
          - type: Text
            hasDropCap: false
            content: |-
              ###### Após um ciclo de mobilizações históricas que tomaram São Paulo – Terra Indígena – entre 2013 e 2025, a TI Jaraguá foi finalmente reconhecida como território de posse ancestral Guarani. 

              ###### Elaborada em colaboração com xeramõi e xejaryi, xondaros e xondarias, professores, lideranças e ativistas Guarani, esta plataforma apresenta uma cartografia da atual configuração da TI Jaraguá no momento de sua demarcação física, em setembro de 2025.  

              ###### Combinando análise de dados geoespaciais, cartografias participativas, entrevistas e documentação de arquivo, traça um panorama histórico das práticas espaciais das comunidades Guarani para a defesa, o cuidado, e a reparação das florestas do Jaraguá.

              ######
          - type: Spacer
            desktop: 200px
            tablet: 200px
            mobile: 100px
  - type: Group
    id: parte_1_nhanderekoa
    shortTitle: parte 1 - nhanderekoa
    longTitle: nhanderekoa
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
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                A Terra Indígena Guarani do Jaraguá preserva os últimos fragmentos de Mata Atlântica na cidade de São Paulo, um dos biomas brasileiros mais devastados desde a colonização europeia. 

                Além de ser uma reserva florestal de fundamental importância ambiental e climática para a metrópole paulista, onde áreas verdes são notoriamente escassas, o Jaraguá é um território de imenso valor espiritual e cultural para as comunidades indígenas que aí vivem desde tempos imemoriais. 

                _Ka’aguy_ – a mata, a floresta – é uma paisagem saturada de história e memória, o patrimônio vivo dos ancestrais (humanos e não-humanos) dos povos Guarani.
            - type: ImageBlock
              wideImage: true
              src: /uploads/imagem_pico_jaragua_stillvideo_small.jpg
              alt: ''
              description: Pico do Jaraguá em São Paulo, Terra Indígena Guarani
        column2:
          components:
            - type: Spacer
              wideImage: true
              src: /uploads/imagem_XX_mata.jpg
              alt: ''
              description: mata do jaraguá
              desktop: 100px
              tablet: 100px
              mobile: 100px
            - type: Pullquote
              content: Os xeramoi sempre dizem que os elementos da cultura guarani estão inseridos justamente no ka’aguy, “a mata”, “a floresta”. Para nós ka’aguy é como se fosse o nosso irmão mais velho, por que a floresta faz com que o nosso modo de vida seja feita do jeito certo, porque todos os ensinamentos estão lá.
              txtColor: '#18af1aff'
              bgColor: '#18af1aff'
              byline: – Jurandir Tupã Jekupe Mirim
  - type: Map
    id: mapa_ti_jaragua
    shortTitle: mapa - ti jaragua
    longTitle: mapa - ti jaragua
    description: ''
    showInMenu: false
    animations: true
    txtColor: Highlight
    bgColor: Primary
    components:
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: map1_ti
      - type: Spacer
        desktop: 200px
        tablet: 200px
        mobile: 300px
      - type: Text
        hasDropCap: false
        content: |-
          #### TERRA INDÍGENA JARAGUÁ

          A Terra Indígena Jaraguá é um território localizado na cidade de São Paulo, tradicionalmente habitado pelo povo Guarani Mbya. A área reconhecida e demarcada pelo Estado Brasileiro abrange 532 hectares, a maior parte ainda cobertos de Mata Atlântica. Atualmente, a Terra Indígena Jaraguá conta com nove Tekoas (aldeias).
      - type: Spacer
        desktop: 800px
        tablet: 800px
        mobile: 900px
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: map1_ytu
      - type: Text
        hasDropCap: false
        content: |-
          ##### TEKOA YTU

          Retomada e fundação: década de 1960

          Uma das mais antigas tekoas, a tekoa Ytu, “Aldeia da Cachoeira”, foi fundada pela família de Joaquim Augusto Martim e Jandira Augusto Martim, primeira Cacica da Terra Indígena Jaraguá. O nome se refere ao Ribeirão das Lavras que chega à _Tekoa_ por meio de uma pequena cachoeira. Cobrindo um perímetro de certa de 1.8 hectares, foi demarcada em 1987.
      - type: Spacer
        desktop: 500px
        tablet: 500px
        mobile: 600px
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: map1_pyau
      - type: Spacer
        hasDropCap: false
        content: |-
          ##### TEKOA PYAU

          Retomada e fundação: década de 1990

          Segunda _Tekoa _a ser formada no processo histórico de retomada, a _Tekoa Pyau_ (Aldeia Nova) é, atualmente, a que tem maior densidade populacional na TI. Cercada pela Rodovia dos Bandeirantes e pela Rua Comendador de Matos, enfrenta barreiras físicas por essas infraestruturas que bloqueiam sua continuidade territorial e afetam, historicamente, áreas de coleta, caça e cultivo.
        desktop: 500px
        tablet: 500px
        mobile: 600px
      - type: Text
        hasDropCap: false
        content: |-
          ##### TEKOA PYAU

          Retomada e fundação: década de 1990

          A tekoa Pyau, traduzido como “aldeia nova”, é a segunda tekoa do processo histórico de retomada da TI. Hoje é a comunidade com maior densidade populacional da terra indígena. A tekoa está cercada pela Rodovia dos Bandeirantes e pela Rua Comendador de Matos, infraestruturas que bloqueiam sua continuidade territorial e afetaram historicamente áreas de coleta, caça e cultivo.
        desktop: 500px
        tablet: 500px
        mobile: 600px
      - type: Spacer
        wideImage: false
        src: /uploads/img_tekoa_pyau_natalicio.jpg
        alt: ''
        description: O mestre dos saberes Natalício Karaí em frente do seu jardim medicinal.
        desktop: 50px
        tablet: 50px
        mobile: 50px
      - type: ImageBlock
        wideImage: true
        src: /uploads/img_tekoa_pyau_natalicio.jpg
        alt: ''
        description: O mestre dos saberes Natalício Karaí em frente do seu jardim medicinal na Tekoa Pyau.
        desktop: 300px
        tablet: 300px
        mobile: 400px
      - type: Spacer
        txtColor: ''
        bgColor: ''
        desktop: 300px
        tablet: 300px
        mobile: 400px
        mapView: map1_itakupe
      - type: MapView
        txtColor: ''
        bgColor: ''
        desktop: 500px
        tablet: 500px
        mobile: 600px
        mapView: map1_itakupe
      - type: Spacer
        hasDropCap: false
        content: |-
          ##### TEKOA ITAKUPE

          Retomada e fundação: 2005

          Situada no extremo norte da TI, a _Tekoa Itakupe_, que pode ser traduzida como “Aldeia Atrás da Pedra”, recebe esse nome por estar do outro lado do Pico do Jaraguá, próxima de suas formações rochosas. Essa área é habitada por comunidades Guarani desde as primeiras retomadas, que aconteceram nas décadas de 1950 e 1960. Fundada em 2014, hoje é formada por três núcleos habitacionais.
        desktop: 500px
        tablet: 500px
        mobile: 600px
      - type: Text
        hasDropCap: false
        content: |-
          ##### TEKOA ITAKUPE

          Retomada e fundação: 2005

          Situada no extremo norte da TI Jaraguá, a área onde está a Tekoa Itakupe é utilizada pelas comunidades Guarani desde as primeiras retomadas nos anos 1950 e 1960. Fundada em 2014, hoje é formada por três núcleos. Por estar localizada do outro lado do Pico do Jaraguá, próxima de suas formações rochosas, foi nomeada de Itakupe, que pode ser traduzido como “atrás da pedra”.
      - type: Spacer
        txtColor: ''
        bgColor: ''
        desktop: 500px
        tablet: 500px
        mobile: 600px
        mapView: map1_itawera
      - type: MapView
        txtColor: ''
        bgColor: ''
        desktop: 500px
        tablet: 500px
        mobile: 600px
        mapView: map1_itawera
      - type: Spacer
        desktop: 500px
        tablet: 500px
        mobile: 600px
      - type: Text
        hasDropCap: false
        content: |-
          ##### TEKOA ITAWERA

          Retomada e fundação: 2014

          Fundada pela Cacica Ara Poty (Maria) em 2014, a Tekoa Itawera recuperou uma área antes destinada ao descarte de lixo. Hoje, a comunidade se dedica à recuperação ambiental e cultural, com ações como o reflorestamento com espécies nativas, o cultivo de alimentos tradicionais como o milho Guarani, bem como um vasto trabalho de artesanato. O nome da tekoa pode ser traduzido como “pedra reluzente”.
        wideImage: false
        src: /uploads/img_tekoa_itawera_cacica_maria.jpg
        alt: ''
        description: A cacica Maria Ara Poty confeccionando artesanato em sua casa na Tekoa Itawera, recuperada de um grande depósito de lixo.
      - type: Spacer
        desktop: 50px
        tablet: 50px
        mobile: 50px
      - type: ImageBlock
        wideImage: false
        src: /uploads/img_tekoa_itawera_cacica_maria.jpg
        alt: ''
        description: A cacica Maria Ara Poty confeccionando artesanato em sua casa na Tekoa Itawera, recuperada de um grande depósito de lixo.
        txtColor: ''
        bgColor: ''
        mapView: map1_itaendy
      - type: Spacer
        desktop: 300px
        tablet: 300px
        mobile: 400px
      - type: MapView
        hasDropCap: false
        content: |-
          ##### TEKOA ITAENDY

          Retomada e fundação: 2017


          Desde sua retomada em 2017, a _Tekoa Itaendy_ (Aldeia da Pedra Amarela) promove práticas de manutenção da biodiversidade, como o reflorestamento com espécies nativas, o plantio de roças com alimentos tradicionais e a reintrodução e criação de espécies de abelhas nativas.
        txtColor: ''
        bgColor: ''
        mapView: map1_itaendy
      - type: Spacer
        desktop: 500px
        tablet: 500px
        mobile: 600px
      - type: Text
        hasDropCap: false
        content: |-
          ##### TEKOA ITAENDY

          Retomada e fundação: 2017

          Desde sua retomada em 2017, a Tekoa Itaendy, “aldeia da pedra amarela”, vem promovendo práticas de manutenção da biodiversidade como o reflorestamento com espécies nativas, plantio de roças com alimentos tradicionais, bem como a reintrodução e criação de espécies de abelhas nativas.
      - type: Spacer
        desktop: 500px
        tablet: 500px
        mobile: 600px
    columnAlign: right
    floatingText: true
  - type: Map
    id: mapa_ti_jaragua_2
    shortTitle: mapa - ti jaragua 2
    longTitle: mapa - ti jaragua 2
    description: ''
    showInMenu: false
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Primary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: MapView
        txtColor: ''
        bgColor: ''
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                _Nhanderekoa_ – “o lugar onde vivemos”, “o lugar onde o nosso modo de vida acontece”, “onde nossa cultura vive” – é o título atribuído ao mapa. Ele expressa como o território do Jaraguá e seus animais, plantas e espíritos são parte integrante da forma como os Guarani entendem seus modos de habitar e viver, tendo a floresta como extensão de uma moradia compartilhada entre seres humanos e não-humanos em redes de cuidado e reciprocidade.

                A Terra Indígena Jaraguá é uma ==área localizada em São Paulo, Brasil, habitada pelo povo Guarani Mbya==. Inicialmente demarcada com apenas 1,7 hectare, sendo a menor do Brasil, de acordo com o Instituto Socioambiental, ela teve sua área ampliada para 532 hectares após anos de luta e reivindicação da comunidade indígena. A área demarcada agora inclui oito tekoas Guarani Mbya, reconhecidas pelo governo. 

                A ampliação da Terra Indígena Jaraguá representa um avanço importante na luta por direitos territoriais dos povos indígenas, especialmente considerando a situação de vulnerabilidade enfrentada pelas comunidades devido à falta de espaço e à pressão urbana. A demarcação da área visa garantir a preservação do modo de vida Guarani Mbya, seus costumes e tradições, além de proteger a biodiversidade da Mata Atlântica presente na região.
            - type: ImageBlock
              wideImage: false
              src: /uploads/imagem jaragua_color edited.jpg
              alt: ''
              description: ''
        column2:
          components: []
        mapView: map1_yvypora
      - type: Spacer
        desktop: 500px
        tablet: 500px
        mobile: 600px
      - type: Text
        hasDropCap: false
        content: |-
          ##### TEKOA YVY PORÃ

          Retomada e fundação: 2018

          Assim como Itawera, Yvy Porã se estabeleceu em uma área antigamente destinada ao descarte de lixo urbano, situada no pé das matas do Pico do Jaraguá. Ao longo dos anos, a tekoa tornou-se importante referência de práticas ecológicas de des-poluição, recuperação e manutenção da Mata Atlântica. Yvy Porã, traduzido como “terra boa” ou “terra bela”, também é uma referência de práticas de recuperação de diversas espécies nativas de abelhas, como a jate’i (jatai), considerada sagrada.
        desktop: 500px
        tablet: 500px
        mobile: 600px
      - type: Spacer
        desktop: 50px
        tablet: 50px
        mobile: 50px
      - type: ImageBlock
        wideImage: false
        src: /uploads/img_tekoa_yvy_pora_marcioabelhas.jpg
        alt: ''
        description: Márcio Wera Mirim, responsável por cuidar do enorme meliponário da Tekoa Yvy Porã.
      - type: Spacer
        desktop: 300px
        tablet: 300px
        mobile: 400px
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: map1_pindomirim
      - type: Spacer
        desktop: 500px
        tablet: 500px
        mobile: 400px
      - type: Text
        hasDropCap: false
        content: |-
          ##### TEKOA PINDÓ MIRIM

          Retomada e fundação: 2023

          Uma das tekoas mais recentes da TI, Pindó Mirim foi retomada em 2023. Situada no extremo noroeste da área demarcada, a comunidade vem desenvolvendo um forte trabalho de reparação ambiental, com foco na regeneração das áreas de Mata Atlântica afetadas pela construção do Rodoanel e plantações de eucaliptos. Destaca-se o reflorestamento com mais de 1500 mudas de árvores nativas e 300 mudas de árvores frutíferas.
      - type: Spacer
        desktop: 50px
        tablet: 50px
        mobile: 50px
      - type: ImageBlock
        wideImage: false
        src: /uploads/img_tekoa_pindo_mirim_daniel.jpg
        alt: ''
        description: Daniel Wera Mirim mostrando os remanescentes de plantações de eucalipito na Tekoa Pindó Mirim.
      - type: Spacer
        desktop: 300px
        tablet: 300px
        mobile: 400px
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: map1_mirim
      - type: Spacer
        desktop: 500px
        tablet: 500px
        mobile: 400px
      - type: Text
        hasDropCap: false
        content: |-
          ##### TEKOA MIRIM

          Retomada e fundação: 2023

          Tekoa Mirim, chamada “pequena aldeia”, está localizada ao lado da Tekoa Pyau. Assim como outros núcleos habitacionais, seus moradores têm desenvolvido várias práticas de cuidado e reparação do território. Destaca-se o plantio de mudas nativas, frutíferas e hortaliças ao longo do caminho que beira a Rodovia dos Bandeirantes, conectando a Tekoa Pyau à Tekoa Mirim e à Ka’aguy Mirim.
      - type: Spacer
        desktop: 50px
        tablet: 50px
        mobile: 50px
      - type: ImageBlock
        wideImage: false
        src: /uploads/img_tekoa_mirim_marcio.jpg
        alt: ''
        description: Marcio Wera Mirim e seu grande roçado em frente a Rodovia dos Bandeirantes na Tekoa Mirim.
      - type: Spacer
        desktop: 300px
        tablet: 300px
        mobile: 400px
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: map1_kaaguymirim
      - type: Spacer
        desktop: 500px
        tablet: 500px
        mobile: 600px
      - type: Text
        hasDropCap: false
        content: |-
          ##### TEKOA KA'AGUY MIRIM

          Retomada e fundação: 2024

          A Tekoa Ka’aguy Mirim é outra retomada adjacente à Tekoa Pyau. Com o nome de “pequena floresta”, situa-se no limite da Terra Indígena, entre a Rodovia dos Bandeirantes e a Rua Antônio Cardoso Nogueira. A tekoa é considerada por seus moradores como um importante ponto de cuidado de espécies nativas medicinais presentes neste local, motivo que impulsionou a retomada da área.
      - type: Spacer
        desktop: 500px
        tablet: 500px
        mobile: 600px
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: map1_fimti
    columnAlign: left
    floatingText: true
  - type: Group
    id: parte_1_texto_2
    shortTitle: parte 1 - texto 2
    longTitle: parte 1 - texto 2
    description: ''
    showInMenu: false
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
        columnsAlign: 66-33
        column1:
          components:
            - type: VideoEmbed
              hasDropCap: true
              content: |-
                _Nhanderekoa_ – “o lugar onde vivemos”, “o lugar onde o nosso modo de vida acontece”, “onde nossa cultura vive” – é o título atribuído ao mapa. Ele expressa como o território do Jaraguá e seus animais, plantas e espíritos são parte integrante da forma como os Guarani entendem seus modos de habitar e viver, tendo a floresta como extensão de uma moradia compartilhada entre seres humanos e não-humanos em redes de cuidado e reciprocidade.

                A Terra Indígena Jaraguá é uma ==área localizada em São Paulo, Brasil, habitada pelo povo Guarani Mbya==. Inicialmente demarcada com apenas 1,7 hectare, sendo a menor do Brasil, de acordo com o Instituto Socioambiental, ela teve sua área ampliada para 532 hectares após anos de luta e reivindicação da comunidade indígena. A área demarcada agora inclui oito tekoas Guarani Mbya, reconhecidas pelo governo. 

                A ampliação da TI representa um avanço importante na luta por direitos territoriais dos povos indígenas, especialmente considerando a situação de vulnerabilidade enfrentada pelas comunidades devido à falta de espaço e à pressão urbana. A demarcação da área visa garantir a preservação do modo de vida Guarani Mbya, seus costumes e tradições, além de proteger a biodiversidade da Mata Atlântica presente na região.
              wideVideo: true
              videoUrl: https://player.vimeo.com/video/1106060903?
              videoCaption: Trecho da entrevista com Jurandir Tupã Jekupe Mirim sobre o significado da Ka'aguy (floresta) para a cultura Guarani.
            - type: Text
              hasDropCap: true
              content: |-
                _Nhanderekoa_ – “o lugar onde vivemos”, “o lugar onde o nosso modo de vida acontece”, “onde nossa cultura vive” – é o título atribuído à estas cartografias e mapeamentos.

                _Nhanderekoa_ expressa como o território do Jaraguá e seus animais, plantas e espíritos são parte integrante da forma como os Guarani entendem seus modos de habitar e viver, tendo a floresta como extensão de uma moradia compartilhada entre seres humanos e não-humanos em redes de cuidado e reciprocidade.

                Por décadas, as comunidades Guarani vêm resistindo e lutando pelo reconhecimento de suas terras ancestrais e pela preservação de suas florestas sagradas no Jaraguá.
              wideImage: false
              src: /uploads/imagem jaragua_color edited.jpg
              alt: ''
              description: ''
            - type: ImageBlock
              wideImage: true
              src: /uploads/img_tekoa_yvy_pora_casa.jpg
              alt: ''
              description: Na Tekoa Yvy Porã, as casas se misturam com a floresta, formando parte do mesmo sistema ecológico.
        column2:
          components:
            - type: Pullquote
              content: A mata para nós tem uma inteligência, tudo funciona de uma forma que uma liga a outra, os animais são importante pro ka'aguy e para nós, as árvores, as ervas... tudo tem uma conexão. Para nós não é simplesmente a mata. É o nosso irmão, é um membro do nosso povo. Como se fossem espíritos conectados, um depende do outro.
              txtColor: ''
              bgColor: ''
              byline: Jurandir Tupã Jekupe Mirim
            - type: Spacer
              desktop: 300px
              tablet: 300px
              mobile: 100px
  - type: Group
    id: parte_2_colonizacao_do_jaragua
    shortTitle: parte 2 - colonizacao do Jaragua
    longTitle: Da Invasão ao Parque
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/imagem_02_pateodocolegio.jpg
    overlay: light
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        components:
          - type: Text
            hasDropCap: true
            content: |-
              Como mostra o Mapa Etno-Histórico de Curt Nimuendajú (1944), o território ancestral Guarani se estende desde a fronteira do estado do Paraná com o Paraguai, a Argentina e a Bolívia, até o Espírito Santo, passando por Mato Grosso do Sul, São Paulo e Rio de Janeiro. Os ancestrais Guarani caminhavam, e os Guarani de hoje seguem caminhando, por todo este território, que chamam de Yvyrupa, “o leito da terra”.	

              ![img curt](/uploads/arqueological-remains_07.jpg "Recorte do mapa Ethno Histórico desenhado por Curt Nimuendaju em 1944")

              Com a invasão europeia, assim como aconteceu em outros territórios indígenas, os territórios Guarani foram brutalmente reconfigurados por deslocamentos forçados e extermínios. 

              Em São Paulo, após a criação do aldeamento do Pateo do Collegio em 1554, as populações tupi-guarani que habitavam a região foram submetidas a sistemáticas políticas de confinamento e escravização. 

              Marco fundante da cidade, o Pateo do Collegio irradiou a colonização sobre o Jaraguá, uma das primeiras regiões onde os Europeus exploraram ouro no Brasil Colônia. O Jaraguá passa então a ser alvo da exploração de bandeirantes, e assim é continuamente despovoado de seus habitantes nativos.
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### parte II

                ## Da Invasão ao Parque: a colonização do Jaraguá

                ## (1554 – 1960)
        column2:
          components: []
  - type: Group
    id: parte_2_texto_1
    shortTitle: parte 2 - texto 1
    longTitle: parte 2 - texto 1
    description: ''
    showInMenu: false
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        txtColor: ''
        bgColor: ''
        paddingTop: false
        paddingBottom: false
        components:
          - type: Text
            hasDropCap: true
            content: |-
              Como mostra o Mapa Etno-Histórico de Curt Nimuendajú (1944), o território ancestral Guarani se estende desde a fronteira do estado do Paraná com o Paraguai, a Argentina e a Bolívia, até o Espírito Santo, passando por Mato Grosso do Sul, São Paulo e Rio de Janeiro. Os ancestrais Guarani caminhavam, e os Guarani de hoje seguem caminhando, por todo este território, que chamam de Yvyrupa, “o leito da terra”.	

              ![img curt](/uploads/arqueological-remains_07.jpg "Recorte do mapa Ethno Histórico desenhado por Curt Nimuendaju em 1944")

              Com a invasão europeia, assim como aconteceu em outros territórios indígenas, os territórios Guarani foram brutalmente reconfigurados por deslocamentos forçados e extermínios. 

              Em São Paulo, após a criação do aldeamento do Pateo do Collegio em 1554, as populações tupi-guarani que habitavam a região foram submetidas a sistemáticas políticas de confinamento e escravização. 

              Marco fundante da cidade, o Pateo do Collegio irradiou a colonização sobre o Jaraguá, uma das primeiras regiões onde os Europeus exploraram ouro no Brasil Colônia. O Jaraguá passa então a ser alvo da exploração de bandeirantes, e assim é continuamente despovoado de seus habitantes nativos.
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: true
              content: Conforme mostra o Mapa Etno-Histórico elaborado pelo etnólogo Curt Nimuendajú (1944), o território ancestral Guarani se estende desde a fronteira do estado do Paraná com o Paraguai, a Argentina e a Bolívia, até o estado do Espírito Santo, passando por Mato Grosso do Sul, São Paulo e Rio de Janeiro. Também existem terras Guarani nos estados de Tocantins e Pará.  Os ancestrais Guarani caminhavam, e os Guarani de hoje seguem caminhando, por todo o território, que chamam de Yvyrupa, “o leito da terra”, nas palavras do professor Jurandir Tupã Jekupe Mirim.
            - type: ImageBlock
              wideImage: false
              src: /uploads/imagem_03_mapacurt.png
              alt: mapa curt
              description: 'Recorte do Mapa Etno-Histórico de Curt Nimuendajú (1944), mostrando a amplitude do território Guarani (Fonte: Biblioteca Digital Curt Nimuendaju).'
            - type: Text
              hasDropCap: true
              content: |-
                Com a invasão europeia, assim como aconteceu em outros territórios indígenas, os territórios Guarani foram brutalmente reconfigurados por deslocamentos forçados e extermínios. 

                Em São Paulo, após a criação do aldeamento do Pateo do Collegio em 1554, as populações tupi-guarani que habitavam a região foram submetidas a sistemáticas políticas de confinamento e escravização.  

                Marco fundante da cidade, o Pateo do Collegio irradiou a colonização sobre o Jaraguá, uma das primeiras regiões onde os europeus exploraram ouro no Brasil Colônia. O Jaraguá passa então a ser alvo da exploração de bandeirantes, e assim é continuamente despovoado de seus habitantes nativos.
        column2:
          components:
            - type: Pullquote
              content: Yvyrupa seria “território”. Mas o território, para muitas pessoas, é somente a terra, o espaço. Para nós o território vai além. Ele nos lembra o leito, o leito do nosso corpo, o leito do nosso modo de viver.
              txtColor: ''
              bgColor: ''
              byline: – Jurandir Tupã Jekupe Mirim.
            - type: Spacer
              desktop: 400px
              tablet: 400px
              mobile: 100px
            - type: ImageBlock
              wideImage: true
              src: /uploads/gravura_exploracao_ouro_jaragua.jpg
              alt: Gravura retratando a extração de ouro no Jaraguá, circa séc. 18
              description: 'Gravura retratando a extração de ouro no Jaraguá, circa século XVIII. Fonte: John Mawe, Travels in the interior of Brazil, 1812.'
        mapView: resistencia_intro
    columnAlign: right
    floatingText: false
  - type: Map
    id: mapa_1_colonizacao
    shortTitle: mapa 1 - colonizacao
    longTitle: mapa 1 - colonizacao
    description: ''
    showInMenu: false
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Primary
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: MapView
        txtColor: ''
        bgColor: ''
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: ImageBlock
              wideImage: true
              src: /uploads/imagem_07_jurandircafe.jpg
              alt: ''
              description: O professor Jurandir Tupã Jekupe Mirim mostra uma planta de café nas florestas da T.I. Jaraguá, remanescente das plantações dos séculos XVIII e XIX, quando a região funcionava como uma grande propriedade agrícola.
        column2:
          components:
            - type: Text
              hasDropCap: true
              content: Com a exaustão do ouro em São Paulo e a descoberta das minas em Goiás e Minas Gerais, a área do Pico do Jaraguá transforma-se numa enorme propriedade agrícola. Durante o século XIX, seguindo a expansão da economia cafeeira paulista, a chamada “Fazenda Jaraguá” torna-se uma grande produtora de café, e vastas áreas de Mata Atlântica são arrasadas. Espécies de café remanescentes destas plantações são encontradas até hoje por toda TI.
            - type: Spacer
              desktop: 150px
              tablet: 150px
              mobile: 150px
        mapView: map2_jaraguasptudo
      - type: Spacer
        desktop: 600px
        tablet: 900px
        mobile: 700px
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: map2_pateo
      - type: Text
        hasDropCap: false
        content: Em 1554 funda-se o povoado de São Paulo dos Campos de Piratininga, futura cidade de São Paulo, onde hoje encontra-se o Pateo do Collegio.
      - type: Spacer
        desktop: 50px
        tablet: 50px
        mobile: 50px
      - type: ImageBlock
        wideImage: false
        src: /uploads/palácio-do-governo-de-são-paulo-debret_1827.jpg
        alt: ''
        description: Pintura do Pateo do Collegio, por Jean-Baptiste Debret, quando o edifício servia como Palácio do Governo de São Paulo em 1827.
      - type: Spacer
        desktop: 600px
        tablet: 600px
        mobile: 700px
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: map2_barueri
      - type: Text
        hasDropCap: false
        content: Em 1560, ao sul do Pico do Jaraguá, na região de Barueri, José de Anchieta mandou erguer outro aldeamento para concentração e catequização dos indígenas.
      - type: Spacer
        desktop: 50px
        tablet: 50px
        mobile: 50px
      - type: ImageBlock
        wideImage: false
        src: /uploads/capela_nsra_da_escada_2.jpg
        alt: ''
        description: 'Capela de Nossa Senhora da Escada, ponto central do Aldeamento de Barueri. As ruínas da capela original, datada do século XVI, foram encontradas em 2003 e logo restauradas (Foto: Victor Hugo Mori/Vitruvius).'
        txtColor: ''
        bgColor: ''
      - type: Spacer
        desktop: 600px
        tablet: 600px
        mobile: 700px
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: map2_ourojaragua
      - type: Text
        hasDropCap: false
        content: Pouco depois, em 1597, o bandeirante Afonso Sardinha encontra ouro na região do Jaraguá. Estabelece uma grande propriedade na área com a construção de um complexo Casa Grande – Senzala ao pé do morro.
        txtColor: ''
        bgColor: ''
      - type: Spacer
        desktop: 50px
        tablet: 50px
        mobile: 50px
      - type: ImageBlock
        wideImage: false
        src: /uploads/casa_afonso_sardinha.jpg
        alt: ''
        description: O complexo Casa Grande-Senzala construído por Afonso Sardinha é hoje o principal patrimônio do Parque Estadual do Jaraguá.
        txtColor: ''
        bgColor: ''
      - type: Spacer
        desktop: 300px
        tablet: 300px
        mobile: 400px
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: map2_jaraguasp
      - type: Spacer
        desktop: 800px
        tablet: 800px
        mobile: 800px
    columnAlign: right
    floatingText: true
  - type: Group
    id: parte_2_texto_2
    shortTitle: parte 2 - texto 2
    longTitle: parte 2 - texto 2
    description: ''
    showInMenu: false
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
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                Com a exaustão do ouro em São Paulo e a descoberta das minas em Goiás e Minas Gerais, a área do Pico do Jaraguá transforma-se numa enorme propriedade agrícola. Durante o século XIX, seguindo a expansão da economia cafeeira paulista, a chamada “Fazenda Jaraguá” torna-se uma grande produtora de café, e vastas áreas de Mata Atlântica são arrasadas. 

                Espécies de café remanescentes destas plantações são encontradas até hoje por toda TI.
              wideImage: true
              src: /uploads/imagem_07_jurandircafe.jpg
              alt: ''
              description: O professor Jurandir Tupã Jekupe Mirim mostra uma planta de café nas florestas da TI, remanescente das plantações dos séculos XVIII e XIX, quando a região funcionava como uma grande propriedade agrícola.
            - type: Spacer
              hasDropCap: false
              content: |-
                ##### A CRIAÇÃO DO PARQUE DO JARAGUÁ

                Na década de 1940, com o declínio da atividade cafeeira, a Fazenda Jaraguá é adquirida pelo município de São Paulo e torna-se propriedade estatal. Em 1946, a propriedade passa a ser administrada pelo Serviço Florestal do município.  

                Por esta época, na primeira metade do século XX, o Jaraguá continuava sendo um lugar habitado pelos Guarani através dos caminhos que conectavam o Paraná e o Mato Grosso do Sul até o Vale do Ribeira e o litoral paulista.

                Em 1961, no contexto do estabelecimento das primeiras reservas florestais nacionais, cria-se o Parque Estadual do Jaraguá, que pela primeira vez garante algum nível de proteção ambiental aos remanescentes de Mata Atlântica no Pico do Jaraguá.
              desktop: 100px
              tablet: 100px
              mobile: 100px
            - type: Text
              hasDropCap: false
              content: |-
                ##### A CRIAÇÃO DO PARQUE DO JARAGUÁ

                Na década de 1940, com o declínio da atividade cafeeira, a Fazenda Jaraguá é adquirida pelo município de São Paulo e torna-se propriedade estatal. Em 1946, a propriedade passa a ser administrada pelo Serviço Florestal do município.  

                Por esta época, na primeira metade do século XX, o Jaraguá continuava sendo um lugar habitado pelos Guarani através dos caminhos que conectavam o Paraná e o Mato Grosso do Sul até o Vale do Ribeira e o litoral paulista.

                Em 1961, no contexto do estabelecimento das primeiras reservas florestais nacionais, cria-se o Parque Estadual do Jaraguá, que pela primeira vez garante algum nível de proteção ambiental aos remanescentes de Mata Atlântica no Pico do Jaraguá.
              wideImage: false
              src: /uploads/imagem_05_mapadoPEJ.jpg
              alt: ''
              description: 'Mapa dos limites do Parque Estadual do Jaraguá apresentado no Processo de Tombamento do CONDEPHAAT de 1978. A área hachurada em amarelo ao lado direito, destinada à criação do complexo turístico do parque, coincide com a área da Tekoa Ytu, estabelecida entre três lagoas ao pé do morro. (Fonte: CONDEPHAAT).'
            - type: ImageBlock
              hasDropCap: false
              content: |-
                Ao proteger as florestas do Jaraguá dentro dos parâmetros ambientalistas tradicionais, o Parque Estadual acabou não apenas cerceando o uso das matas pelas comunidades Guarani, mas também foi um modo de apagar a presença indígena da região, definindo a área como uma grande reserva ecológica homogênea, vazia e inabitada.   

                Em paralelo, São Paulo vive um rápido processo de urbanização. Entre 1940 e 1948 é construída a rodovia Anhanguera nas margens do Território Guarani do Jaraguá, e em 1955 é construído o linhão de transmissão Anhangabaú-Jundiaí sobre o pico do morro. Estas grandes infraestruturas de transporte e energia inter-urbanas abrem caminho para a voraz especulação imobiliária que se daria nas décadas seguintes, principalmente com o regime militar depois do golpe de 1964.
              wideImage: false
              src: /uploads/imagem_05_mapadoPEJ.jpg
              alt: ''
              description: 'Mapa dos limites do Parque Estadual do Jaraguá apresentado no Processo de Tombamento do CONDEPHAAT de 1978. A área hachurada em amarelo ao lado direito, destinada à criação do complexo turístico do parque, coincide com a área da Tekoa Ytu, estabelecida entre três lagoas ao pé do morro. (Fonte: CONDEPHAAT).'
            - type: Text
              hasDropCap: false
              content: |-
                Ao proteger as florestas do Jaraguá dentro dos parâmetros ambientalistas tradicionais, o Parque Estadual acabou não apenas cerceando o uso das matas pelas comunidades Guarani, mas também foi um modo de apagar a presença indígena da região, definindo a área como uma grande reserva ecológica homogênea, vazia e inabitada.   

                Em paralelo, São Paulo vive um rápido processo de urbanização. Entre 1940 e 1948 é construída a rodovia Anhanguera nas margens do Território Guarani do Jaraguá, e em 1955 é construído o linhão de transmissão Anhangabaú-Jundiaí sobre o pico do morro. Estas grandes infraestruturas de transporte e energia inter-urbanas abrem caminho para a voraz especulação imobiliária que se daria nas décadas seguintes, principalmente com o regime militar depois do golpe de 1964.
        column2:
          components:
            - type: ImageBlock
              wideImage: true
              src: /uploads/imagem_07_jurandircafe.jpg
              alt: ''
              description: O professor Jurandir Tupã Jekupe Mirim mostra uma planta de café nas florestas da TI Jaraguá, remanescente das plantações do século e XIX, quando a região funcionava como uma grande propriedade agrícola.
              desktop: 150px
              tablet: 150px
              mobile: 150px
            - type: Spacer
              desktop: 900px
              tablet: 900px
              mobile: 100px
            - type: ImageBlock
              wideImage: true
              src: /uploads/imagem_18_mapa_anhanguera.jpg
              alt: ''
              description: 'Planta da Via Anhanguera, década de 40 (Fonte: Arquivo Biblioteca do Departamento de Estradas e Rodagens).'
  - type: Group
    id: parte_3_retomada_do_jaragua
    shortTitle: parte 3 - retomada do jaragua
    longTitle: A Retomada do Jaraguá
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/imagem_06_picojaragua.jpg
    overlay: light
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
              content: |-
                ###### parte III

                ## A Retomada do Jaraguá

                ## (1800 - 1961)
        column2:
          components: []
  - type: Group
    id: parte_3_texto_1
    shortTitle: parte 3 - texto 1
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        wideImage: false
        src: /uploads/imagem_31_analise_foto_aerea_verde.jpg
        alt: asd
        description: Análise de imagem aerofotogramétrica de 1954, onde é possível identificar a área onde foi estabelecida a Tekoa Ytu, próxima de fontes de água ao pé do morro do Jaraguá. Alterações na estrutura da mata indicam a possível presença de assentamentos Guarani na região anteriores a 1960-1961, quando a Tekoa Ytu, considerada a primeira retomada do Jaraguá, é estabelecida definitivamente.
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                No arco do século XIX ao início do século XX, ocorrem grandes migrações Guarani da região fronteiriça do Paraná e do Mato Grosso do Sul para o estado de São Paulo.

                Como identificado por Curt Nimuendajú, nos anos 1810, 1820 e 1870, e possivelmente em outros períodos do século XIX, registram-se migrações de grupos Guarani vindos da região do Iguatemi, na fronteira entre o Paraná e o Mato Grosso. Em 1910, sabe-se da migração de outro grande grupo Guarani vindo da região fronteiriça Brasil-Paraguai-Argentina para a região de Itariri no Vale do Ribeira, atual Terra Indígena Itariri. Entre 1923 e 1946 registram-se sucessivas migrações de grupos Guarani vindos do sul do Brasil para o estado de São Paulo, assentando-se principalmente no litoral.

                Estes últimos grupos formam a geração imediatamente anterior de vários moradores das TIs Jaraguá e Tenondé Porã na cidade de São Paulo. Entre eles está a cacica Jandira, fundadora da Tekoa Ytu no início dos anos 1960, primeira tekoa da retomada do Jaraguá. 

                Após a criação do Serviço de Proteção aos Índios (SPI) em 1910, os povos Guarani são alvo de uma política sistemática de aldeamentos. No estado de São Paulo, o SPI busca concentrar as famílias Guarani no Posto Indígena do Bananal em Itanhaém, no litoral, e no Posto Indígena de Araribá, no interior, despovoando a cidade de São Paulo da presença Guarani.  

                Com sua resistência ancestral, fugindo dos aldeamentos, algumas famílias iniciam retomadas na cidade de São Paulo no Jaraguá e na região de Parelheiros, atuais TI Jaraguá e TI Tenondé Porã.
        column2:
          components:
            - type: Spacer
              desktop: 200px
              tablet: 200px
              mobile: 100px
            - type: ImageBlock
              wideImage: true
              src: /uploads/imagem_08_spi.jpg
              alt: ''
              description: Imagem histórica do “aldeamentos” Guarani do Serviço de Proteção aos Índios (SPI) na região do Rio Itariri, no Vale do Ribeira (Imagem do acervo particular de João Emílio Gerodetti).
  - type: Group
    id: parte_3_analise_foto_aerea
    shortTitle: parte 3 - analise foto aerea
    longTitle: parte 3 - analise foto aerea
    description: ''
    showInMenu: false
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: ImageBlock
        wideImage: false
        src: /uploads/imagem_31_analise_foto_aerea_verde.jpg
        alt: asd
        description: Análise de imagem aerofotogramétrica de 1954, onde é possível identificar a área onde foi estabelecida a Tekoa Ytu, próxima de fontes de água ao pé do morro do Jaraguá. Alterações na estrutura da mata indicam a possível presença de assentamentos Guarani na região anteriores a 1960-1961, quando a Tekoa Ytu, considerada a primeira retomada do Jaraguá, é estabelecida definitivamente.
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                Nos anos 1950, expulso pelo SPI do aldeamento de Bananal, a família de André Samuel dos Santos, liderança Tupi-Guarani perseguida pelo Estado como “rebelde” conforme mostram documentos do SPI, inicia a retomada das florestas do Jaraguá. Entre 1960 e 1961, o casal de caciques Jandira e Joaquim migra do litoral para o Jaraguá, onde erguem uma tekoa ao lado de uma fonte de água ao pé do morro. 

                A retomada recebe o nome de Tekoa Ytu, “aldeia da cachoeira”. Desde então, as florestas do Jaraguá passam a ser um grande refúgio, abrigando famílias Guarani vindas de várias regiões do Brasil.
            - type: VideoEmbed
              wideVideo: true
              videoUrl: https://www.youtube.com/embed/80MJwqZdOss?si=wQDvXQFFAxlw8f15
              videoCaption: Entrevista histórica com a Cacica Jandira, matriarca da Terra Indígena Jaraguá em São Paulo (realizado em 1992 pelo VideoFAU da Faculdade de Arquitetura e Urbanismo da USP).
        column2:
          components:
            - type: Spacer
              desktop: 200px
              tablet: 200px
              mobile: 200px
            - type: ImageBlock
              wideImage: true
              src: /uploads/imagem_08_spi.jpg
              alt: ''
              description: Imagem histórica do “aldeamentos” Guarani do Serviço de Proteção aos Índios (SPI) na região do Rio Itariri, no Vale do Ribeira (Imagem do acervo particular de João Emílio Gerodetti).
  - type: Group
    id: parte_3_texto_2
    shortTitle: parte 3 - texto 2
    longTitle: parte 3 - texto 2
    description: ''
    showInMenu: false
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        wideImage: false
        src: /uploads/imagem_31_analise_foto_aerea_verde.jpg
        alt: asd
        description: Análise de imagem aerofotogramétrica de 1954, onde é possível identificar a área onde foi estabelecida a Tekoa Ytu, próxima de fontes de água ao pé do morro do Jaraguá. Alterações na estrutura da mata indicam a possível presença de assentamentos Guarani na região anteriores a 1960-1961, quando a Tekoa Ytu, considerada a primeira retomada do Jaraguá, é estabelecida definitivamente.
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                Nos anos 1950, expulso pelo SPI do aldeamento de Bananal, a família de André Samuel dos Santos –  liderança Tupi-Guarani perseguida pelo Estado como “rebelde”, conforme atestam documentos do SPI – inicia a retomada das florestas do Jaraguá. Entre 1960 e 1961, o casal de caciques Jandira e Joaquim migra do litoral para o Jaraguá, onde erguem uma tekoa ao lado de uma fonte de água ao pé do morro. 

                A retomada recebe o nome de Tekoa Ytu, “aldeia da cachoeira”. Desde então, as florestas do Jaraguá passam a ser um grande refúgio, abrigando famílias Guarani vindas de várias regiões do Brasil.
            - type: VideoEmbed
              wideVideo: true
              videoUrl: https://www.youtube.com/embed/80MJwqZdOss?si=wQDvXQFFAxlw8f15
              videoCaption: Entrevista histórica com a Cacica Jandira, matriarca da Terra Indígena Jaraguá em São Paulo (realizado em 1992 pelo VideoFAU da Faculdade de Arquitetura e Urbanismo da USP).
        column2:
          components: []
  - type: Group
    id: parte_4_ditadura_deslocamentos_e_desmatamento
    shortTitle: parte 4 - Ditadura, Deslocamentos e Desmatamento
    longTitle: Ditadura, Deslocamentos e Desmatamento
    description: bloco título
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/imagem_09_itaipu.jpg
    overlay: light
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
              content: |-
                ###### **parte IV**

                ## **Ditadura, Deslocamentos Forçados & Desmatamento**

                ## **(1964 – 1984)**
        column2:
          components: []
  - type: Group
    id: parte_4_texto_1
    shortTitle: parte 4 - texto 01
    longTitle: ''
    description: ''
    showInMenu: false
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
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                Seguindo a lógica desenvolvimentista dos anos 1960 e 1970, o período da ditadura militar é marcado por investimentos em mega infraestruturas e pelo planejamento autoritário. 

                Na cidade de São Paulo, realizam-se grandes obras urbanas e rodoviárias, como a Rodovia dos Bandeirantes, que atinge diretamente o território ancestral Guarani do Jaraguá. O Pico do Jaraguá é designado para receber torres de antenas de comunicação, e são concedidas terras para o Grupo Bandeirantes, a TV Globo, a Fundação Padre Anchieta (TV Cultura) e o Exército. Em 1972 é construído um grande complexo turístico no parque.

                Na esteira destas obras, a especulação imobiliária e a urbanização expandem-se vertiginosamente nas margens de São Paulo, avançando sobre as florestas do Jaraguá. As décadas entre 1960 e 1980 registram altos índices de desmatamento na franja da zona norte da cidade, com o adensamento de bairros como Jaraguá e Pirituba.
            - type: ImageBlock
              wideImage: true
              src: /uploads/imagem_11_bandeirantesconstrucao.jpg
              alt: ''
              description: 'Obras da construção da Rodovia dos Bandeirantes na região do Pico do Jaraguá ( Fonte: Arquivo FGV CPDOC) Rodovia dos Bandeirantes na região do Pico do Jaraguá (Fonte: CPDOC FGV).'
        column2:
          components:
            - type: Spacer
              desktop: 100px
              tablet: 100px
              mobile: 100px
            - type: ImageBlock
              wideImage: true
              src: /uploads/imagem_10_bandeirantes.jpg
              alt: Inauguração da Rodovia dos Bandeirantes com a presença do ditador General Ernesto Geisel (Arquivo FGV CPDOC).
              description: Inauguração da Rodovia dos Bandeirantes com a presença do ditador General Ernesto Geisel (Arquivo FGV CPDOC).
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components: []
        column2:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                Ao passo que os “grandes empreendimentos” da ditadura militar avançavam Brasil afora, os povos indígenas eram reprimidos pelo regime e seus direitos sistematicamente violados. 

                Como mostra o relatório da [Comissão Nacional da Verdade](https://cnv.memoriasreveladas.gov.br/images/pdf/relatorio/Volume%202%20-%20Texto%205.pdf), no contexto dos planos de desenvolvimento nacional, inúmeras comunidades indígenas foram submetidas a transferências e remoções forçadas executadas por agentes de estado para abrir terras para obras de infraestrutura.

                É o caso da construção da Usina Hidrelétrica de Itaipu no centro do território ancestral Guarani no Oeste do Paraná. O imenso lago artificial de Itaipu inundou dezenas de tekoas, e várias famílias Guarani foram forçadas a deixar suas terras, algumas migrando para São Paulo. 

                Ao mesmo tempo, lideranças indígenas eram perseguidas pelo Estado por seu ativismo político pela defesa dos territórios, ou tornavam-se alvo de milícias ruralistas, como no caso do grande líder guarani-ñadeva Marçal de Souza. Um dos precursores das lutas guarani pela recuperação e reconhecimento de seus territórios ancestrais, Marçal de Souza, Tupã-Y, foi assassinado por pistoleiros no Mato Grosso do Sul em novembro de 1983.
            - type: VideoEmbed
              wideVideo: true
              videoUrl: https://www.youtube.com/embed/Z3HS2j2acX4?si=ZylorkTY5cZrXczI
              videoCaption: 'Entrevista histórica com Marçal de Souza, liderança Guarani assassinada em 1983 (Fonte: Povos Indígenas no Brasil - Youtube).'
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: ImageBlock
              wideImage: true
              src: /uploads/edit_mapaguaranisul_documental_2.png
              alt: ''
              description: 'Mapa das tekoas inundadas e forçosamente removidas da região do lago artificial de Itaipu (Fonte: agência autônoma e CGY).'
        column2:
          components: []
  - type: Group
    id: parte_5_retorno_a_democracia_e_demarcacao_da_tekoa_ytu
    shortTitle: parte 5 - Retorno a Democracia & Demarcacao da Tekoa Ytu
    longTitle: Retorno a Democracia e Demarcacao da Tekoa Ytu
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/imagem_13_constituinte.jpg
    overlay: light
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
              content: |-
                ###### parte V

                ## Retorno à Democracia & Demarcação da Tekoa Ytu

                ## (1984 – 1989)
        column2:
          components: []
  - type: Group
    id: parte_5_texto_1
    shortTitle: parte 5 - texto 1
    longTitle: ''
    description: ''
    showInMenu: false
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
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                A resistência dos povos indígenas desempenhou um papel protagonista na derrocada do regime militar e no retorno à democracia nos anos 1980.

                Sob pressão do movimento indígena, a Constituição de 1988 reconhece o direito dos povos originários a seus territórios ancestrais, sendo esses direitos anteriores à própria criação do Estado brasileiro. A Constituição também garante a proteção da organização social, costumes, línguas, crenças e tradições dos povos indígenas.

                Neste contexto, assim como outros territórios e movimentos populares, o Jaraguá passa por um processo de crescente organização política e reclame de direitos. 

                Pressionada pelo movimento indígena, em 1984 – ano do movimento “Diretas Já” – a FUNAI procede com regularização de algumas terras indígenas no Estado de São Paulo, incluindo uma pequena parte da Terra Indígena Jaraguá correspondente à Tekoa Ytu, demarcada em 1987. 

                Ainda que representassem avanços democráticos, estas demarcações eram claramente insuficientes, especialmente no caso da TI Jaraguá, onde a área demarcada abrangia apenas o perímetro de 1.8 hectares do núcleo habitacional da Tekoa Ytu. Deste modo, a demarcação ignorava a extensão territorial do uso tradicional das matas que mantém o _nhandereko_, o modo de habitar Guarani.
              wideImage: false
              src: /uploads/imagem_16_logo_mata_atlantica_unesco.jpg
              alt: Selo da Reserva da Biosfera - UNESCO
              description: Selo da Reserva da Biosfera - UNESCO.
            - type: ImageBlock
              wideImage: true
              src: /uploads/imagem_29_area_demarcada_1987.jpg
              alt: asd
              description: Mapa assinalando a área demarcada em 1987, circunscrita ao núcleo habitacional da Tekoa Ytu, em comparação com a área reconhecida da TI Jaraguá atualmente.
        column2:
          components:
            - type: Spacer
              hasDropCap: true
              content: |-
                Em paralelo, no arco entre os assassinatos de Marçal de Souza e Chico Mendes em 1983-1984, e a realização do encontro internacional ECO-92 promovido pelas Nações Unidas no Rio de Janeiro em 1992, a pauta ambiental consolida-se internacionalmente e no Brasil. 

                Em 1994 o Parque Estadual do Jaraguá é reconhecido pela UNESCO como Patrimônio da Humanidade, na categoria de Reserva da Biosfera, passando a integrar o Cinturão Verde da Cidade de São Paulo.

                 Assim como na criação do Parque Estadual em 1961, tais medidas protetivas ambientalistas muitas vezes entram em conflito com o direito das comunidades Guarani ao seu território ancestral, impedindo-as de usufruir dos recursos naturais das florestas dentro do perímetro do Parque, que hoje encontra-se totalmente cercado.
              desktop: 100px
              tablet: 100px
              mobile: 100px
            - type: ImageBlock
              wideImage: true
              src: /uploads/imagem_14_constituinte_02.jpg
              alt: asd
              description: 'À frente na bancada, da esquerda para a direita: Teseya Panará, Kanhõc Kayapó, Raoni Mētyktire e Tutu Pombo Kayapó, dentre outros, ocupam auditório da liderança do PMDB nas negociações do capítulo dos indígenas na Constituinte em 1988 (Fonte: Beto Ricardo/ISA).'
  - type: Group
    id: parte_5_texto_2
    shortTitle: parte 5 - texto 2
    longTitle: ''
    description: ''
    showInMenu: false
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
            - type: ImageBlock
              hasDropCap: false
              content: |-
                ###### parte VI

                ## Resistência, Luta & Demarcação

                ## (1990 - 2025)
              wideImage: false
              src: /uploads/imagem_16_logo_mata_atlantica_unesco.jpg
              alt: Selo da Reserva da Biosfera - UNESCO
              description: Selo da Reserva da Biosfera - UNESCO
        column2:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                Em paralelo, no arco entre os assassinatos de Marçal de Souza e Chico Mendes em 1983-1984, e a realização do encontro internacional ECO-92 promovido pelas Nações Unidas no Rio de Janeiro em 1992, a pauta ambiental consolida-se internacionalmente e no Brasil. 

                Em 1994 o Parque Estadual do Jaraguá é reconhecido pela UNESCO como Patrimônio da Humanidade, na categoria de Reserva da Biosfera, passando a integrar o Cinturão Verde da Cidade de São Paulo.

                 Assim como na criação do Parque Estadual em 1961, tais medidas protetivas ambientalistas muitas vezes entram em conflito com o direito das comunidades Guarani ao seu território ancestral, impedindo-as de usufruir dos recursos naturais das florestas dentro do perímetro do Parque, que hoje encontra-se totalmente cercado.
              desktop: 100px
              tablet: 100px
              mobile: 100px
            - type: ImageBlock
              wideImage: true
              src: /uploads/imagem_30_cinturao_verde.jpg
              alt: asd
              description: Mapa da área norte do Cinturão Verde da Cidade de São Paulo. As florestas da TI Jaraguá são as mais preservadas do cinturão.
  - type: Group
    id: parte_6_reconhecimento_luta_e_demarcacao
    shortTitle: parte 6 - reconhecimento luta e demarcacao
    longTitle: Reconhecimento, luta e demarcação
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/imagem_16_ocupacao_antena.jpg
    overlay: light
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
              content: |-
                ###### **parte VI**

                ## **Reconhecimento, Luta & Demarcação**

                ## **(1990 – 2025)**
              wideImage: false
              src: /uploads/imagem_16_logo_mata_atlantica_unesco.jpg
              alt: Selo da Reserva da Biosfera - UNESCO
              description: Selo da Reserva da Biosfera - UNESCO.
              desktop: 300px
              tablet: 300px
              mobile: 300px
        column2:
          components: []
  - type: Group
    id: parte_6_texto_1
    shortTitle: parte 6 - texto 1
    longTitle: parte 6 - texto 1
    description: ''
    showInMenu: false
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: ''
    components:
      - type: Columns
        txtColor: ''
        bgColor: ''
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                Com a volta da democracia após vinte anos de ditadura militar, as comunidades Guarani passam a expandir as retomadas no Jaraguá. Na década de 1990, as lideranças Karaí Poty (José Fernandes) e Eunice, filha da cacica Jandira, fundam a Tekoa Pyau, chamada “aldeia nova”. Nas décadas seguintes ocorrem várias retomadas: em 2005, a Tekoa Itakupe; entre 2016-2017, a Tekoa Itaendy; em 2018, a Tekoa Yvy Porã; e em 2023, as tekoas Pindó Mirim, Mirim, e Ka’aguy Mirim. 

                Estas retomadas acontecem em um contexto de crescente organização política dos povos Guarani a nível nacional. Em 2006 é criada a Comissão Guarany Yvurupa (CGY), organização que congrega coletivos dos povos Guarani nas regiões Sul e Sudeste do Brasil na luta pela terra. 

                A Terra Indígena Jaraguá cresce forte e fica cada vez mais populosa. Através da CGY e de suas bases, as lideranças Guarani pressionam pela demarcação de seus territórios.
              desktop: 300px
              tablet: 300px
              mobile: 300px
            - type: VideoEmbed
              wideImage: true
              src: /uploads/imagem_19_ocupacao_antena.jpg
              alt: asd
              description: 'Em protesto contra a anulação da demarcação da TI, entre os dias 14 e 16 de setembro, ativistas Guarani ocupam o Pico do Jaraguá e desativam as torres transmissoras, cortando o sinal de telefonia e televisão para uma vasta região da cidade de São Paulo (Fonte: Comissão Guarani Yvyrupa - CGY).'
              wideVideo: false
              videoUrl: https://www.youtube.com/embed/JCBOU4wQmR8?si=Ce5kuWAYhQyji6Wk
              videoCaption: '"Rodovia Rojoko - O dia em que fechamos a Bandeirantes”.   Video realizado pela CGY documentando o fechamento da Rodovia dos Bandeirantes por ativistas Guarani em 26 de Setembro de 2013. O protesto pede a demarcação das TIs Jaraguá e Tenondé Porã, e o cancelamento   da Proposta de Emenda a Constituição 215/2000, que visava transferir do Poder Executivo para o Congresso Nacional a competência para a demarcação de terras indígenas e quilombolas (Fonte: CGY).'
        column2:
          components: []
        mapView: resistencia_intro
    columnAlign: right
    floatingText: false
---
