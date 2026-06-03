---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Department of Interfaces and Colloids

        Institute of Physical Chemistry
    
        Bulgarian Academy of Sciences
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Design, characterization and optimization of complex liquid media and nanostructured materials for applications in medicine, pharmacy, cosmetics, food             and oil industries and for environmental protection:
        - investigation the properties of adsorption layers of liquid phase boundaries thin liquid films (foams, emulsions and wetting)
        - wetting phenomena, determination of the three-phase contact parameters
        - correlation composition/properties/stability of foams and emulsions
        - electro-optical phenomena in colloidal systems, electrical, optical properties and stability of the dispersed particles
        - structure and properties of aqueous solutions of low molecular surfactants, lipids, synthetic and natural polymers, proteins
        - optimizing the composition of the "intelligent" liquid mixtures of heat-sensitive and biocompatible components
        - optimization of complex liquid compositions for transfer and release of drugs for the diagnosis and treatment of pulmonary immaturity in neonates
        - "self-repairing" hybrid protective coatings
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
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
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
