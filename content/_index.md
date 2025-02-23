---
title: 'Home' # The title of the homepage
date: 2025-02-22 # The date the page was created
type: landing # The type of the page, used for layout purposes

design:
  # Default section spacing
  spacing: "6rem" # The default spacing between sections

sections:
  - block: hero # The hero section of the homepage
    content:
      title: ALTRADERX # The title displayed in the hero section
      text: Automate. Trade. Dominate. # The subtitle or tagline
      image: 
        filename: "logon.png"
      #primary_action:
        #text: Get Started # Text for the primary call-to-action button
        #url: https://hugoblox.com/templates/ # URL for the primary call-to-action button
        #icon: rocket-launch # Icon for the primary call-to-action button
      #secondary_action:
        #text: Read the docs # Text for the secondary call-to-action button
        #url: https://docs.hugoblox.com # URL for the secondary call-to-action button
      announcement:
        text: "COMING SOON!" # Announcement text
        #link:
          #text: "Read more" # Text for the announcement link
          #url: "/blog/" # URL for the announcement link
    design:
      spacing:
        padding: [0, 0, 0, 0] # Padding for the hero section
        margin: [0, 0, 0, 0] # Margin for the hero section
      # For full-screen, add `min-h-screen` below
      css_class: "dark" # CSS class for the hero section
      background:
        color: "navy" # Background color for the hero section
        image:
          # Add your image background to `assets/media/`
          filename: "bg-triangles.svg" # Background image filename
          filters:
            brightness: 0.5 # Brightness filter for the background image
  #- block: stats
  #  content:
  #    items:
  #      - statistic: "1M+" # Statistic value
  #        description: |
  #          Websites built  
  #          with Hugo Blox # Description for the statistic
  #      - statistic: "10k+" # Statistic value
  #        description: |
  #          GitHub stars  
  #          since 2016 # Description for the statistic
  #      - statistic: "3k+" # Statistic value
  #        description: |
  #          Discord community  
  #          for support # Description for the statistic
  #  design:
      # Section background color (CSS class)
  #    css_class: "bg-gray-100 dark:bg-gray-900" # CSS class for the stats section
      # Reduce spacing
  #    spacing:
  #      padding: ["1rem", 0, "1rem", 0] # Padding for the stats section
  - block: features # The features section of the homepage
    id: features # ID for the features section
    content:
      title: Features # Title for the features section
    #  text: Build your site with blocks 🧱 # Subtitle for the features section
      items:
        - name: Automated Trading # Feature name
          icon: bolt # Icon for the feature
          description: Fully hands-off trading with automatic trade execution, stop-loss, and take-profit management. # Description for the feature
        - name: Market Adaptive # Feature name
          icon: magnifying-glass # Icon for the feature
          description: Dynamically adjusts trading strategies based on real-time market conditions. # Description for the feature
        - name: Smart Order Execution # Feature name
          icon: sparkles # Icon for the feature
          description: Leverages limit, market, and stop orders to ensure the best possible trade execution. # Description for the feature
        - name: AI-Powered Optimization # Feature name
          icon: code-bracket # Icon for the feature
          description: Adapts several indicators and risk parameters to maximize profitability in any market condition. # Description for the feature
        - name: DeFi Ready # Feature name
          icon: star # Icon for the feature
          description: Integrated with decentralized platforms, ensuring full transparency and security. # Description for the feature
        - name: Low Latency # Feature name
          icon: rectangle-group # Icon for the feature
          description: Built with advanced technology for real-time price tracking and instant trade execution. # Description for the feature
  #- block: cta-image-paragraph
  #  id: solutions
  #  content:
  #    items:
  #      - title: Build your future-proof website # Title for the CTA section
  #        text: As easy as 1, 2, 3! # Text for the CTA section
  #        feature_icon: check # Icon for the CTA section
  #        features:
  #          - "Future-proof - edit your content in text files" # Feature for the CTA section
  #          - "Website is generated by a single app, Hugo" # Feature for the CTA section
  #          - "No JavaScript knowledge required" # Feature for the CTA section
          # Upload image to `assets/media/` and reference the filename here
  #        image: build-website.png # Image for the CTA section
  #        button:
  #          text: Get Started # Text for the CTA button
  #          url: https://hugoblox.com/templates/ # URL for the CTA button
  #      - title: Large Community # Title for the CTA section
  #        text: Join our large community on Discord - ask questions and get live responses # Text for the CTA section
  #        feature_icon: bolt # Icon for the CTA section
  #        features:
  #          - "Dedicated support channel" # Feature for the CTA section
  #          - "3,000+ users on Discord" # Feature for the CTA section
  #          - "Share your site and get feedback" # Feature for the CTA section
          # Upload image to `assets/media/` and reference the filename here
  #        image: coffee.jpg # Image for the CTA section
  #        button:
  #          text: Join Discord # Text for the CTA button
  #          url: https://discord.gg/z8wNYzb # URL for the CTA button
  #  design:
      # Section background color (CSS class)
  #    css_class: "bg-gray-100 dark:bg-gray-900" # CSS class for the CTA section
  #- block: testimonials
  #  content:
  #    title: "" # Title for the testimonials section
  #    text: "" # Text for the testimonials section
  #    items:
  #      - name: "Hugo Smith" # Name of the person giving the testimonial
  #        role: "Marketing Executive at X" # Role of the person giving the testimonial
          # Upload image to `assets/media/` and reference the filename here
  #        image: "testimonial-1.jpg" # Image for the testimonial
  #        text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!" # Text for the testimonial
  #  design:
  #    spacing:
  #      # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #      padding: ["6rem", 0, 0, 0] # Padding for the testimonials section
  #- block: cta-card
  #  content:
  #    title: Build your future-proof website # Title for the CTA card
  #    text: As easy as 1, 2, 3! # Text for the CTA card
  #    button:
  #      text: Get Started # Text for the CTA button
  #      url: https://hugoblox.com/templates/ # URL for the CTA button
  #  design:
  #    card:
        # Card background color (CSS class)
  #      css_class: "bg-primary-700" # CSS class for the CTA card
  #      css_style: "" # CSS style for the CTA card
---
