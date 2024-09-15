---
# Display name
title: Michael Benedikt

# Name pronunciation (optional)
# name_pronunciation: ""

# Full name (for SEO)
first_name: Michael
last_name: Benedikt

order: 1

user_groups: ["Keynotes"]

# # Status emoji
# status:
#   icon: ☕️

# Is this the primary user of the site?
superuser: false

# Role/position/tagline
role: Professor of Computer Science

# Organizations/Affiliations to show in About widget
organizations:
  - name: Oxford University
    url: https://www.cs.ox.ac.uk
  # - name: Northeastern University  
  

# Short bio (displayed in user profile at end of posts)
# bio: My research interests include distributed robotics, mobile computing and programmable matter.

# # Interests to show in About widget
# interests:
#   - Artificial Intelligence
#   - Computational Linguistics
#   - Information Retrieval

# # Education to show in About widget
# education:
#   courses:
#     - course: PhD in Artificial Intelligence
#       institution: Stanford University
#       year: 2012
#     - course: MEng in Artificial Intelligence
#       institution: Massachusetts Institute of Technology
#       year: 2009
#     - course: BSc in Artificial Intelligence
#       institution: Massachusetts Institute of Technology
#       year: 2008

# # Skills
# # For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
# skills:
#   - name: Technical
#     items:
#       - name: Python
#         description: ''
#         percent: 80
#         icon: python
#         icon_pack: fab
#       - name: Data Science
#         description: ''
#         percent: 100
#         icon: chart-line
#         icon_pack: fas
#       - name: SQL
#         description: ''
#         percent: 40
#         icon: database
#         icon_pack: fas
#   - name: Hobbies
#     color: '#eeac02'
#     color_border: '#f0bf23'
#     items:
#       - name: Hiking
#         description: ''
#         percent: 60
#         icon: person-hiking
#         icon_pack: fas
#       - name: Cats
#         description: ''
#         percent: 100
#         icon: cat
#         icon_pack: fas
#       - name: Photography
#         description: ''
#         percent: 80
#         icon: camera-retro
#         icon_pack: fas

# # Social/Academic Networking
# # For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
# #   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
# #   form "mailto:your-email@example.com" or "/#contact" for contact widget.
social:
  # - icon: envelope
  #   icon_pack: fas
  #   link: 'mailto:raldeco@unam.mx'
#   - icon: twitter
#     icon_pack: fab
#     link: https://twitter.com/amw2024news
#     label: Follow us on Twitter
#     display:
#       header: true
#   - icon: graduation-cap # Alternatively, use `google-scholar` icon from `ai` icon pack
#     icon_pack: fas
#     link: https://scholar.google.co.uk/citations?user=sIwtMXoAAAAJ
#   - icon: github
#     icon_pack: fab
#     link: https://github.com/gcushen
  # - icon: linkedin
  #   icon_pack: fab
  #   link: https://www.linkedin.com/in/rocio-aldeco/
#   # Link to a PDF of your resume/CV.
#   # To use: copy your resume to `static/uploads/resume.pdf`, enable `ai` icons in `params.yaml`,
#   # and uncomment the lines below.
#   - icon: cv
#     icon_pack: ai
#     link: uploads/resume.pdf

# Highlight the author in author lists? (true/false)
highlight_name: true
---

## Keynote Talk 

### Verification of Graph Learning Models and Analysis of Query Languages 

Graph neural networks (GNNs) are the predominant architectures for a variety of learning tasks on graphs. Like other modern machine learning models, their success is accompanied by many fundamental concerns. Can we understand what exactly  a trained model does? Can we have confidence that a trained model will not do anything bad? In this talk we will give one of the first approaches to verifying GNNs. We will work using the static analysis of techniques of database theory. Many of our results work by converting the GNN into a logic, and then showing that we can analyze the logic. This translation is useful not only for verification, but for explanation of the behavior of GNNs.

The work reported here is joint with Chia-Hsuan Lu, Boris Motik, and Tony Tan ([Decidability of Graph Neural Networks via Logical Characterizations](https://web3.arxiv.org/abs/2404.18151)), it is closely related to work of Barcelo, Kostylev, Monet, Reutter, and Silva from ICLR 2020 ([The Logical Expressiveness of Graph Neural Networks](https://openreview.net/forum?id=r1lZ7AEKvB)), and also to prior work on analysis of logics on graphs with arithmetic ([On two-variable guarded fragment logic with expressive local Presburger constraints](https://arxiv.org/abs/2206.13731); [Two Variable Logic with Ultimately Periodic Counting](https://epubs.siam.org/doi/10.1137/22M1504792)). The talk will be in the same spirit as the AMW summer school course on analysis of GNNs via query languages: but there will be no dependency between the two, and no overlap in the results.



### Bio

Michael Benedikt is a professor at Oxford University's computer science department, and a fellow of University College Oxford. He came to Oxford after a decade in US industrial research laboratories, including a position as Distinguished Member of Technical Staff at Bell Laboratories. He has worked extensively in computational logic, finite model theory, verification, and data management, and specializes in the interaction between these topics. He has been a keynote in past meetings on mathematical logic, computational logic, description logics, and databases. He has co-authored papers receiving best paper awards and test-of-time awards in major conferences within databases and theoretical computer science, and he has served as the program chair of both the ACM Principles of Database Systems conference (2012) and the International Conference on Database Theory (2017). He currently holds an Established Career Fellowship from the UK's Engineering and Physical Science's Research Council, and serves on the steering committees for the Association for Symbolic Logic, the European Association for Theoretical Computer Science, and the International Conference on Database Theory.