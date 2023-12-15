---
title: 'Home'
date: 2023-10-24
type: landing
sections:
  - block: biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Read my latest paper on LLMs
          icon: arxiv
          url: https://arxiv.org/abs/2304.01852
        - text: Watch my new YouTube video to achieve 20x productivity
          icon: youtube
          url: https://youtube.com
        - text: Connect with me on LinkedIn
          icon: linkedin
          url: https://linkedin.com
  - block: hero
    content:
      title: Hugo Blox
      text: Build your site with blocks 🧱
      primary_action:
        text: Get Started
        url: https://example.com
        icon: sparkles
      secondary_action:
        text: Read the docs
        url: https://example.com
      announcement:
        text: Announcing the release of version 1.
        link:
          text: Read more
          url: https://example.com
  - block: markdown
    content:
      title: My title
      subtitle: My subtitle
      text: dede
      dede

  - block: collection
    content:
      filters:
        folders:
          - post
  - block: skills
    content:
      title: Skills
      text: 'voici un texte'
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '2'
---
