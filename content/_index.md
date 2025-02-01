---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Rede Brasileira de Naturalistas
      image:
        filename: welcome.png
      text: |
        <br>
        
        A **Rede Brasileira de Naturalistas** é um coletivo de brasileiros dedicados a apoiar e promover o iNaturalist no Brasil. Dessa forma, queremos promover um maior contato e apreciação dos brasileiros por nossa natureza, assim como sustentar o avanço de estudos acadêmicos utilizando a plataforma para sistemática, ecologia e conservação.  
  
  - block: collection
    content:
      title: Últimas Notícias
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
   
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Conheça os membros →" %}}
    design:
      columns: '1'
---
