---
title: 'Talks'
date: 2024-08-06
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: collection
    id: papers
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: papers
    content:
      title: Preprints
      text: ""
      filters:
        folders:
          - preprint
        exclude_featured: false
    design:
      view: citation  
---