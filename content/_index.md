---
title: ''
summary: 'Machine learning researcher for robust physiological time-series modeling, wearables, sleep, and health AI.'
date: 2026-06-04
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: small
        shape: circle
  - block: markdown
    content:
      title: 'Research and R&D Focus'
      subtitle: ''
      text: |-
        I work on machine learning methods for physiological data in real-world conditions, where models face subject variability, device differences, domain shifts, multimodal sensing constraints, and noisy labels.

        My PhD uses sleep as a central testbed, but the broader goal is robust health AI: systems that can be evaluated fairly, transferred across datasets, and used with physiological signals collected outside ideal laboratory settings.

        I am especially interested in future industrial R&D roles around wearable sensing, health AI, physiological time series, multimodal modeling, and research-to-code execution.
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: Selected Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
  - block: collection
    id: papers
    content:
      title: Selected Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
  - block: markdown
    id: service
    content:
      title: 'Teaching, Supervision, and Service'
      subtitle: ''
      text: |-
        Teaching assistant for Deep Learning and Machine Learning courses serving 300+ students. Co-supervised 2 MSc and 4 BSc theses.

        Academic service includes reviewing for npj Digital Medicine, ICML, IEEE BHI, ACM IMWUT, and additional journals and conferences.
    design:
      columns: '1'
  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |-
        For professional contact, use the email and profile links in the header. This site intentionally avoids publishing phone number or private address.
    design:
      columns: '1'
---
