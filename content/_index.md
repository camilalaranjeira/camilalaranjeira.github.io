---
# Leave the homepage title empty to use the site title
# title: "| Camila Laranjeira"
date: 2025-03-10
type: landing

design:
  # Default section spacing
  spacing: "5rem"

sections:
  - block: resume-bio-custom
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        # Choose colors such as from https://html-color-codes.info
        gradient_start: '#52b1c7'
        gradient_end: '#072669'
        # The gradient angle from 0-360 degrees
        gradient_angle: 180
        # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: true
  - block: collection
    # se quiser incluir filtro de pesquisa, esse foi o que melhor funcionou (sem funcionar)
    # https://github.com/HugoBlox/hugo-blox-builder/blob/main/modules/blox-bootstrap/layouts/section/publication.html
    id: papers
    content:
      title: Recent Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        exclude_featured: false
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: list
  - block: markdown
    id: teaching
    content:
      title: '📚 Teaching'
      subtitle: ''
      # <b> Instituto Federal de Minas Gerais <span style="color:#ea3578"> (IFMG)</span> </b> <br>
      #   A <br> <br>
      text: '
        <b> Universidade Federal de Minas Gerais <span style="color:#ea3578">(UFMG)</span> </b> <br>
        Introdução a Programação de Computadores (2018.2, 2019.1)  <br>
        Algoritmos e Estruturas de Dados I (2018.2)  <br>
        Programação e Desenvolvimento de Software II (2022.2) <br> <br>

        <b> Pontifícia Universidade Católica de Minas Gerais <span style="color:#ea3578">(PUC-MG)</span> </b> <br>
        Inteligência Artificial (2022.1) <br>
        Introdução a Computação (2022.1) <br> 
        Programação e Desenvolvimento de Software I (2022.1) <br> <br>

        <b> <span style="color:#ea3578">Alura</span> </b> <br>
       [Deep Learning com PyTorch](https://www.alura.com.br/formacao-deep-learning-pytorch) <br>
          1. [Introdução a Redes Neurais](https://www.alura.com.br/curso-online-pln-deep-learning) <br>
          2. [Treinando uma Rede Neural](https://www.alura.com.br/curso-online-treinando-rede-neural-pytorch) <br>
          3. [Redes Neurais Convolucionais](https://www.alura.com.br/curso-online-cnn-redes-neurais-convolucionais-deep-learning-pytorch) <br>
          4. [Redes Neurais Recorrentes](https://www.alura.com.br/curso-online-rnn-redes-neurais-recorrentes-deep-learning-pytorch) 
        '
  - block: collection
    id: talks
    content:
      title: Talks, Podcasts, etc.
      count: 6
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 3
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    # demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Visit *Peixe Babel* on Youtube
      text: |-
        Sharing tech knowledge one bit at a time!<br>
        <u><a href="http://youtube.com/@CanalPeixeBabel" 
          style="color:#072669; text-decoration: none;" 
          onmouseover="this.style.color='#fff'" 
          onmouseout="this.style.color='#072669'">
          Click here to visit the channel
        </a></u>
        

        <div align="center">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/7epCIU2bjY4?si=b_Q6TQUbopj1Q67b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>

        You can also follow our updates on Instagram.
      button:
        text: Visit our Instagram
        url: https://instagram.com/canalpeixebabel/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-500"
        css_style: "dark"
      

  - block: markdown
    id: contact
    content:
      title: 'Contact'
      subtitle: ''
      text: |-
        <svg class="w-7 h-4.5 me-3.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20" style="display: inline; vertical-align: middle; margin-right: 5px;">
        <path d="M2.94 4.44A2 2 0 0 1 4.4 4h11.2a2 2 0 0 1 1.46.44L10 9.292 2.94 4.44ZM2 5.697V14a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V5.697l-7.292 4.86a1 1 0 0 1-1.416 0L2 5.697Z"/>
        </svg> mila.laranjeira (at) gmail.com

---
