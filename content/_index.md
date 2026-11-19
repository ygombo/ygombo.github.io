---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      # Follows the site's light/dark theme; light-mode styling is in layouts/partials/hooks/head-end/hero-theme.html
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: bg1.jpg
          filters:
            brightness: 0.3
          size: cover
          position: center
          parallax: false
  - block: speaker-card
    id: speaking
    content:
      username: admin
      title: "🎤 Yoshua's Speaker Profile"
      eyebrow: Speaker · AI & Robotics
      name: Yoshua Gombo, Ph.D.
      role: Co-Founder & CTO, Konstruksi.AI
      bio_title: Speaker Bio
      bio: |-
        Yoshua Gombo is a robotics engineer and the co-founder and CTO of [Konstruksi.AI](https://konstruksi.ai/), a Jakarta-based startup using AI and computer vision to monitor construction projects in real time. He holds a Ph.D. and M.S. in Mechanical Engineering from the University of Washington, where his research on decentralized control of cooperating robot teams was published in leading IEEE journals.

        A tech founder and researcher from Papua, Yoshua makes AI practical and approachable, from boardrooms to classrooms, and champions education for the next generation of Indonesian scholars.
      topics:
        - title: AI for Everyone
          description: Keynotes on AI literacy, prompt writing and AI in business and industry
        - title: Hands-on AI Workshops
          description: Practical sessions where teams put AI tools to work on real tasks
          link:
            text: See the 11 workshop modules
            url: /ai-workshop/
        - title: Robotics & AI Technical Classes
          description: Robot control, multi-robot systems and computer vision in practice
        - title: Education & Motivation
          description: My journey from Papua to a Ph.D. in the US, and why education opens doors worth chasing
      booking:
        - label: E
          text: gombo.yoshua@gmail.com
          url: mailto:gombo.yoshua@gmail.com
        - label: in
          text: linkedin.com/in/yoshua-gombo
          url: https://www.linkedin.com/in/yoshua-gombo/
      button:
        text: Invite me to speak
        url: mailto:gombo.yoshua@gmail.com?subject=Speaking%20invitation
      quote: My dream is to see humans and robots working together.
      credentials:
        - Ph.D. & M.S., Mechanical Engineering, University of Washington
        - Published in IEEE T-RO, IEEE/ASME T-MECH & IEEE RA-L
        - Co-Founder & CTO, Konstruksi.AI
        - Host, Ekskul Podcast
    design:
      spacing:
        padding: ["4rem", 0, "2rem", 0]
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My research focuses on enabling seamless cooperation among robots in multi-agent systems. I investigated a novel decentralized control approach called Delayed Self-Reinforcement (DSR). This method allows robots to achieve greater cohesion by leveraging their existing onboard information, thus reducing the need for additional communication.

        You can find more details in my publications. 😃
        
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      count: 0
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      count: 0
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 2
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Defended my dissertation in December 2023!
      text: |-
        In December 2023, I succesfully defended my dissertation which titled Reduced deformation transport of flexible objects using decentralized robot networks. 
      button:
        text: Read it here.
        url: https://www.proquest.com/openview/9f8f71e9bc9a295a35801e1d669d3a95/1?pq-origsite=gscholar&cbl=18750&diss=y
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
