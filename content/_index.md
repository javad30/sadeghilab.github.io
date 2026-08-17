---
title: "Microbial Adaptation & Evolution Lab"
summary: "MAE Lab at Brandon University"
date: 2026-08-16
type: landing

sections:
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |-
        <div style="text-align: center; max-width: 800px; margin: 0 auto; padding: 2rem 0;">
          <img src="/media/logo.png" alt="Sadeghi Lab Logo" style="width: 280px; max-width: 100%; height: auto; margin: 0 auto 1.5rem auto; display: block; filter: drop-shadow(0 4px 12px rgba(0,0,0,0.08));">
          <h1 style="font-size: 2.25rem; font-weight: 800; margin-bottom: 0.75rem; color: var(--tw-prose-headings);">Microbial Adaptation &amp; Evolution Lab</h1>
          <p style="font-size: 1.15rem; line-height: 1.6; color: var(--tw-prose-body); margin-bottom: 1.5rem;">
            Investigating the genomic, ecological, and evolutionary mechanisms driving microbial communities and plant-microbiome interactions under environmental change.
          </p>
          <div style="display: flex; gap: 1rem; justify-content: center; flex-wrap: wrap;">
            <a href="/people/" style="display: inline-block; padding: 0.6rem 1.4rem; background-color: #0b2545; color: #ffffff; border-radius: 9999px; text-decoration: none; font-weight: 600;">Meet Our Team</a>
            <a href="mailto:sadeghij@brandonu.ca" style="display: inline-block; padding: 0.6rem 1.4rem; border: 1.5px solid #0b2545; color: #0b2545; border-radius: 9999px; text-decoration: none; font-weight: 600;">Contact &amp; Join Us</a>
          </div>
        </div>
    design:
      columns: "1"

  - block: markdown
    content:
      title: "🔬 Research Directions"
      subtitle: "Department of Biology | Brandon University"
      text: |-
        Our research investigates how environmental stressors shape microbial diversity, functional potential, and host symbiosis.

        - **Microbial Evolution & Stress Adaptation:** Resolving phenotypic and genomic adaptation in changing ecosystems.
        - **Plant-Microbiome Interactions:** Deciphering root- and soil-associated microbial dynamics.
        - **Genomics & Bioinformatics:** Integrating metagenomics and high-throughput sequencing pipelines.

        We welcome inquiries from prospective honours students, MSc researchers, and postdocs!
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