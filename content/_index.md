---
title: "Microbial Adaptation & Evolution Lab"
summary: "MAE Lab at Brandon University"
date: 2026-08-16
type: landing

sections:
  - block: hero
    content:
      title: "Microbial Adaptation & Evolution Lab"
      text: "Investigating the genomic, ecological, and evolutionary mechanisms driving microbial communities and plant-microbiome interactions under environmental change."
      image:
        filename: ""
      cta:
        label: "Meet Our Team"
        url: "/people/"
      cta_alt:
        label: "Contact Us"
        url: "mailto:sadeghij@brandonu.ca"
    design:
      background:
        gradient_mesh:
          enable: true

  - block: markdown
    content:
      title: "🔬 Research Directions"
      subtitle: "Department of Biology | Brandon University"
      text: |-
        Our research investigates how environmental stressors shape microbial diversity, functional potential, and host symbiosis.

        - **Microbial Evolution & Stress Adaptation:** Resolving phenotypic and genomic adaptation in changing ecosystems.
        - **Plant-Microbiome Interactions:** Deciphering root- and soil-associated microbial dynamics.
        - **Genomics & Bioinformatics:** Integrating metagenomics and high-throughput sequencing pipelines.

        We welcome inquiries from prospective honours, MSc students, and postdoctoral researchers!
    design:
      columns: "1"

  - block: collection
    id: papers
    content:
      title: "Recent Publications"
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: news
    content:
      title: "Lab News"
      page_type: blog
      count: 3
    design:
      view: card
---