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
      text: Wir helfen Ihnen dabei, Ihre Produkte und Dokumentationen konform zu aktuellen EU IT-Sicherheitsrichtlinien zu gestalten. 
      primary_action:
        text: Fragen Sie uns an!
        url: 'mailto:david@fluela-solutions.com'
        icon: rocket-launch
      secondary_action:
        text: Über uns
        url: /#about
      announcement:
        text: "Der CRA wurde final von der EU verabschiedet! Ist mein Produkt betroffen?"
        link:
          text: "Erfahren Sie mehr."
          url: "/blog/cyber-resilience-act/"
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
    id: solutions 
    content:
      title: Unsere Lösungen
      text: Full-Cycle Security-Lösungen für Ihr Hardware- oder Softwareprodukt. Konzentrieren Sie sich auf Ihr Kerngeschäft.
  
      items:
        - name: Risikoanalyse
          icon: magnifying-glass
          description: Regulierungen wie der CRA verlangen eine Risikoanalyse als Bestandteil der technischen Dokumentation Ihres Produkts. Wir unterstützen Sie bei der Durchführung der Analyse und der Erstellung der entsprechenden Dokumentation.
        - name: Sicherheitskonzept
          icon: shield-check
          description: Die Regulierungen verlangen zudem die Berücksichtigung von Cybersicherheit während des gesamten Produktlebenszyklus. Wir unterstützen Sie gerne dabei, Ihr Produkt sicher zu gestalten und beraten Sie zu wirksamen Maßnahmen, die Sicherheitsrisiken minimieren.
        - name: Monitoring
          icon: computer-desktop
          description: Regulierungen schreiben außerdem vor, den Sicherheitszustand Ihres Produkts während des Betriebs zu überprüfen und Sicherheitsvorfälle zu melden. Wir entwickeln gerne gemeinsam mit Ihnen Lösungen, um den sicheren Betrieb Ihres Produkts zu beurteilen.
  - block: resume-biography
    id: about
    # content:
    #   # The user's folder name in `content/authors/`
    #   username: mike
    #   # Show a call-to-action button under your biography? (optional)
    #   # To link to a file, upload it to your `static/uploads/` folder
    # design:
    #   banner:
    #     # Upload a cover image to `assets/media/` folder and reference its filename here (optional)
    #     filename: 'coffee'
    #   biography:
    #     # Customize the CSS style of your biography text (optional)
    #     style: ''
    content:
      username: david
    design:
      background: 
---
