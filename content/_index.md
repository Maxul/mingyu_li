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
        about: 'About Me'
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
        1. **2026-09**: Xianglin and Jiayin have won the 2nd and 3rd prize in ACM SIGOPS Student Research Competition Undergraduate 2026. Congratulations to Xianglin and Jiayin!
        2. **2026-03**: *ZENO* is accepted by OSDI 2026. Congratulations to Wenxuan and Zhanbo!
        3. **2026-01**: *DMI* is accepted by EuroSys 2026. Congratulations to Yuan!
        4. **2025-09**: Zhenyuan has won the 1st prize in ACM SIGOPS Student Research Competition Undergraduate 2025. Congratulations to Zhenyuan!
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Students'
      text: |
        **Current Students**
        - Yuan Wang (PhD, co-advised) — LLM-OS Co-design
        - Zhanbo Wang (PhD, co-advised) — Embodied AIOS

        - Wenxuan Huang (Master) — Confidential Databases
        - Zhenyuan Yang (Master) — GPU Systems 🏆 SIGOPS SRC 1st Prize
        - Shicheng Deng (Master) — Mobile Systems
        
        - Xianglin Zeng (Undergrad) — LLM-OS Co-design 🏆 SIGOPS SRC 2nd Prize
        - Jiayin Chen (Undergrad) — Confidential Databases🏆 SIGOPS SRC 3rd Prize
---
