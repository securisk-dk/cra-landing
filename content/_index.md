---
title: "Home"
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Konformität zum Cyber Resilience Act
      text: Wir helfen Ihnen dabei, Ihre Produkte und Dokumentationen konform zu aktuellen EU-Cybersicherheitsrichtlinien zu gestalten.
      primary_action:
        text: Fragen Sie uns an!
        url: "mailto:david@fluela-solutions.com"
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
          filename: cra-bg.png
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
          description: Regulierungen wie der CRA fordern eine umfassende Risikoanalyse als Bestandteil Ihrer technischen Dokumentation. Wir unterstützen Sie bei der Analyse und erstellen gemeinsam mit Ihnen die notwendigen Unterlagen – schnell, präzise und konform.
        - name: Sicherheitskonzept
          icon: shield-check
          description: Cybersicherheit muss während des gesamten Produktlebenszyklus berücksichtigt werden. Wir helfen Ihnen, Ihr Produkt sicher zu gestalten, und empfehlen wirksame Maßnahmen, um Risiken nachhaltig zu minimieren.
        - name: Monitoring
          icon: computer-desktop
          description: Der sichere Betrieb Ihres Produkts endet nicht mit der Markteinführung. Regulierungen verlangen kontinuierliches Monitoring und die Meldung von Sicherheitsvorfällen. Wir entwickeln maßgeschneiderte Lösungen, die den Betrieb sicher und regelkonform halten.
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Risikoanalyse
          text: Risiko = Auswirkung x Angriffsfläche
          feature_icon: check
          features:
            - "Wir bieten Ihnen eine präzise und systematische Risikobewertung für Ihr Produkt."
            - "**Auswirkungen:** Welche Daten könnten gefährdet sein? Welche Folgen hätte das für Bereiche wie Sicherheit, Datenschutz, Geschäftsbetrieb oder rechtliche Anforderungen?"
            - "**Angriffsfläche:** Wie einfach wäre ein Angriff? Gibt es eine Online-Schnittstelle? Ist ein Angriff aus der Ferne möglich, oder erfordert er physischen Zugriff?"
          image: risk.png
          button:
            text: Lassen Sie uns loslegen
            url: mailto:david@fluela-solutions.com
        - title: Technische Dokumentation
          text: Wir übernehmen die Erstellung Ihrer risikobezogenen Dokumentation.
          feature_icon: check
          features:
            - "Auf Basis der Risikoanalyse erstellen wir eine CRA-konforme Dokumentation für Ihr Produkt."
            - "Sie können sich ganz auf die Weiterentwicklung und Vermarktung Ihres Produktes konzentrieren."
          image: doc.png
          button:
            text: Jetzt anfragen
            url: mailto:david@fluela-solutions.com

    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Optionally, add a note under the Call-To-Action button
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
      username: mike
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
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
