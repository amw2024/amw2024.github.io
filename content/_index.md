---
# Leave the homepage title empty to use the site title
title: 'General Information'
date: 2022-10-24
type: landing

sections:

  - block: markdown
    content:
      title: |-
        <p style="margin-top:200px;"></p> 
        AMW 2024
    
        👉 <mark>[**Workshop Proceedings**](https://ceur-ws.org/Vol-3954/)</mark> 👈
        { style="text-align:center;" }
    
      subtitle: 
      text: |-

        16th ALBERTO MENDELZON INTERNATIONAL WORKSHOP  
        ON **FOUNDATIONS OF DATA MANAGEMENT**  
        { style="text-align:center;" }

        September 30th - October 4th , 2024   
        { style="text-align:center;" }

        Mexico City, Mexico
        { style="text-align:center;" }



    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'      
      background:
        # gradient_end: '#1976d2'
        # gradient_start: '#004ba0'
        text_color_light: true
        image: 
          # Name of image in `assets/media/`.
          filename: with-us-you-ll-visit.jpg       
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.45
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: false     


  - block: markdown
    content:
      title: DEI Disclaimer
      text: |-
        The AMW community believes that diversity and culture of support encourage retention and attraction of talent, promote diversity of thought and perspective, and help make the scientific community more flexible and responsive in times of change. For these reasons, AMW 2024 participates in the [Database Community Diversity, Equity and Inclusion (DEI) initiative](https://dbdni.github.io/) aiming to guide researchers in our community to adopt a more inclusive mindset. For more information see the [AMW 2024 DEI statement](/dei).

    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1' 

  - block: markdown
    id: about
    content:
      title: About AMW
      subtitle: Int. Workshop & Summer School
      text: |-
        Since 2006, the **Alberto Mendelzon International Workshop on Foundations of Data Management (AMW)** brings together top researchers from all over the world, creating the opportunity to discuss and spread research results around the areas of Data Management and the Web.

        The co-located **AMW Summer School** provides an opportunity for Latin American students (graduate and undergraduate), researchers, and practitioners, to interact with top researchers from all over the world, promoting collaboration, learning and teaching in a friendly environment.

        AMW is a way to honour the memory of [Alberto Mendelzon](https://en.wikipedia.org/wiki/Alberto_O._Mendelzon), by promoting research ties with Latin America.

        {{< figure src="alberto-mendelzon.jpg" >}}

    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2' 

  
  - block: markdown
    id: dates
    design:
      columns: '2' 
    content:
      title: Dates
      subtitle: School & Workshop
      text: |-

        | Events                 |  Dates |
        |:----------|:------|
        | **School**        |   `30 September - 1 October 2024` |
        | **Workshop**      |   `2-4 October 2024` |


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: ''
      # Contact details - edit or remove options as needed
      email: amw2024news@groups.google.com
      
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: "@amw2024news"
          link: 'https://twitter.com/amw2024news'

      # Automatically link email and phone or display them just as text?
      autolink: true
      
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'


  - block: markdown
    id: sponsors
    design:
      columns: '2' 
    content:
      title: Sponsors
      subtitle: 
      text: |-

        <div class="logos">

          <a href="https://www.vldb.org" target="_blank" rel="noopener noreferrer" title="VLDB Endowment">
            <img src="/uploads/logos/vldb.gif">
          </a>

          <a href="https://www.acm.org" target="_blank" rel="noopener noreferrer" title="Association for Computing Machinery">
            <img src="/uploads/logos/acm.svg" width="152px" height="150px" style="max-width: 85%; height: auto">
          </a>    

        </div>


        <div class="logos">

          <a href="https://mx.ambafrance.org" target="_blank" rel="noopener noreferrer" title="Ambassade de France au Mexique">
            <img src="/uploads/logos/ambassade-france.svg" width="152px" height="150px" style="max-width: 75%; height: auto;">
          </a>

          <a href="https://www.cpe.fr" target="_blank" rel="noopener noreferrer" title="CPE Lyon Graduate School of Engineering">
            <img src="/uploads/logos/cpe.svg" width="152px" height="150px" style="max-width: 100%; height: auto;">
          </a>          

        </div>


        <div class="logos">

          <a href="https://ceur-ws.org" target="_blank" rel="noopener noreferrer" title="CEUR Workshop Proceedings">
            <img src="/uploads/logos/ceur-ws.png" width="300px" height="150px" style="max-width: 75%; height: auto;">
          </a>

        </div>


---
