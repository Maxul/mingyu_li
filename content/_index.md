---
# Leave the homepage title empty to use the site title
title: 'Mingyu Li CV'
summary: ''
date: 2026-10-08
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: rounded # Options: circle (default), square, rounded
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
    design:
      view: citation
  - block: markdown
    content:
      title: 'News'
      subtitle: ''
      text: |-
        1. Xianglin and Jiayin have won the 2nd and 3rd prize in ACM SIGOPS Student Research Competition Undergradate 2026. Congratulations to Xianglin and Jiayin!
        2. *ZENO* is is accepted by OSDI 2026. Congratulations to Wenxuan and Zhanbo!
        3. *DMI* is is accepted by EuroSys 2026. Congratulations to Yuan!
    design:
      columns: '1'
---
