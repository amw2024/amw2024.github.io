---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:

  - block: markdown
    content:
      title: |-
        <p style="margin-top:200px;"></p> 
        AMW 2024   
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
    id: important-dates
    content:
      title: Important Dates
      subtitle: 
      text: |-

        | Events                 |  Dates |
        |:----------|:------|
        | **School**        |   `30 September - 1 October 2024` |
        | **Workshop**      |   `2-4 October 2024` |

        </br>
        
        | Deadlines                  |  Dates |
        |:----------|:------|
        | **Abstracts**     |   `9 June 2024` &ensp; &ensp; ~~2 June 2024~~    |
        | **Paper**         |   `16 June 2024`   |
        | **Notifications** |   `30 July 2024`   |
        | **Camera-ready**  |   `28 August 2024` |




        

    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2' 


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


---
