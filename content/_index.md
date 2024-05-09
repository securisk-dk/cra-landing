---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Konformität zum Cyber Resilience Act
      text: 🔒 Wir helfen Ihnen dabei Ihre Produkte und Dokumentationen konform zu aktuellen EU IT-Sicherheitsrichtlinien zu gestalten. 🔒
      primary_action:
        text: Fragen Sie uns an!
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      secondary_action:
        text: Über uns
        url: /#about
      announcement:
        text: "Ist mein Produkt vom Cyber Resilience Act betroffen?"
        link:
          text: "Erfahren Sie mehr."
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  # - block: stats
  #   content:
  #     items:  
  #       - statistic: "1M+"
  #         description: |
  #           Websites built  
  #           with Hugo Blox
  #       - statistic: "10k+"
  #         description: |
  #           GitHub stars  
  #           since 2016
  #       - statistic: "3k+"
  #         description: |
  #           Discord community  
  #           for support
  #   design:
  #     # Section background color (CSS class)
  #     css_class: "bg-gray-100 dark:bg-gray-900"
  #     # Reduce spacing
  #     spacing:
  #       padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Unsere Lösungen
      text: Full-Cycle Cyber Security Lösungen für Ihr Hardware oder Software Produkt. Konzentrieren Sie sich auf Ihr Kerngeschäft.
  
      items:
        - name: Risikoanalyse
          icon: magnifying-glass
          description: Regularien wie der CRA schreiben eine Risikoanalyse als Teil der technischen Dokumentation Ihres Produkts vor. Wir helfen Ihnen bei der Durchführung der Analyse und der Erstellung der entsprechenden Dokumentation.
        - name: Sicherheitskonzept
          icon: shield-check
          description: Die Regularien schreiben weiterhin das Einbeziehen von Cybersicherheit während des gesamten Produktzyklus vor. Gerne helfen wir Ihnen dabei Ihr Produkt sicher zu gestalten und beraten zu wirksamen Maßnahmen, welche die Sicherheitsrisiken minimieren. 
        - name: Monitoring
          icon: computer-desktop
          description: Auch schreiben Regularien vor, dass Sie den Sicherheitszustands Ihres Produktes in Betrieb überprüfen und Sicherheitsvorfälle melden. Gerne entwickeln wir mit Ihnen gemeinsam Lösungen, wie Sie einen sicheren Betrieb Ihres Produktes beurteilen können. 
  - block: resume-biography
    id: about
    content:
      # The user's folder name in `content/authors/`
      username: mike
      # Show a call-to-action button under your biography? (optional)
      # To link to a file, upload it to your `static/uploads/` folder
    design:
      banner:
        # Upload a cover image to `assets/media/` folder and reference its filename here (optional)
        filename: 'coffee'
      biography:
        # Customize the CSS style of your biography text (optional)
        style: ''
        # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: resume-biography
    content:
      username: david
---
