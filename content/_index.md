---
title: 'Home'
date: 2025-11-10 # Current date
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # === 1. HERO BLOCK: School Name, Dates, Host ===
  - block: hero
    id: top
    content:
      title: ACM India Winter School on Edge AI
      text: |
        **28 DECEMBER 2025 to 4 JANUARY 2026**
        
        Hosted by **Indian Institute of Science, Bengaluru**
      primary_action:
        text: Apply Now!
        url: '#contact'
        icon: calendar-days
      secondary_action:
        text: View Topics
        url: '#topics'
    design:
      css_class: "dark"
      background:
        color: "navy"
        image:
          filename: bg-triangles.svg # Keep the default background image or replace it
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false

  # === 2. ABOUT BLOCK: Description, Background, Software ===
  - block: markdown # <-- FIXED: Changed from 'blank' to 'markdown'
    id: about
    content:
      title: About the School
      text: |
        The **ACM India Winter School on Edge AI** will provide an in-depth overview of software platforms, hardware systems, and AI models and algorithms for efficient deployment on accelerated and classic edge devices. The program will cover topics such as edge computing architectures and accelerators, co-optimization techniques of edge systems and ML models for performance, power and accuracy, federated learning frameworks, and the deployment of AI, generative AI/LLM models and AI agents at the edge for practical and IoT applications such as smart mobility and smart agriculture. Through lectures, hands-on sessions, and expert talks, participants will gain practical skills to design, implement, and optimize intelligent edge systems for diverse real-world applications.
        
        ### Recommended Background / Prior Courses
        * Introductory course on Data science, Machine learning, or AI
        * Basics of Computer Systems
        * Embedded systems and IoT programming
        
        ### Specific Software to be Used
        * **Python 3** (scikit-learn, TensorFlow, Keras, LiteRT, PyTorch Edge, ExecuTorch)
        * **Jetpack SDK**
        * **MicroPython**
    design:
      spacing:
        padding: ["3rem", 0, "3rem", 0]
        
  # === 3. TOPICS BLOCK ===
  - block: features
    id: topics
    content:
      title: Key Topics
      # Remove generic description text
      text: |
        The winter school covers foundational and advanced aspects of Edge AI.
      items:
        - name: Foundations of IoT, Accelerated Edge Computing and Edge AI
          icon: microchip
        - name: Tiny and Embedded Machine Learning
          icon: cpu
        - name: Model Optimization and Acceleration for Edge AI
          icon: rocket
        - name: Edge AI Platforms, Frameworks, and Deployment Pipelines
          icon: code-fork
        - name: Federated Learning and Distributed Training for Edge Devices
          icon: users-gear
        - name: Neuromorphic Computing and Brain-Inspired Architectures
          icon: brain
        - name: Generative AI and LLM at the Edge
          icon: magic-wand
        - name: Agentic AI on the Edge
          icon: robot
        - name: Security, Privacy, and Responsible AI in Edge Systems
          icon: lock
        - name: Benchmarking, Profiling, and Performance Evaluation of Edge AI Systems
          icon: chart-bar
        - name: Edge AI for Drones/UAVs, IoT, Smart Cities, and Industrial Applications
          icon: drone
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      columns: 3 # Display topics in 3 columns

  # === 4. SPEAKERS BLOCK ===
  - block: people
    id: speakers
    content:
      title: Invited Speakers
      # Display all authors in the 'speaker' folder
      filters:
        folders:
          - speaker
    design:
      # Display speakers as a grid of cards (optional setting)
      view: compact

  # === 5. COORDINATORS BLOCK ===
  - block: people
    id: coordinators
    content:
      title: Coordinators
      # Display all authors in the 'coordinator' folder
      filters:
        folders:
          - coordinator
    design:
      columns: 2
      view: compact
      css_class: "bg-gray-100 dark:bg-gray-900"

  # === 6. VENUE/LOCATION BLOCK ===
  - block: contact
    id: venue
    content:
      title: Venue & Dates
      address:
        street: CV Raman Avenue
        city: Bangalore
        postcode: 560012
        country: India
        country_code: IN
      # Dates are in the text
      text: |
        The Winter School will be held at:
        **Indian Institute of Science (IISc)**, Bengaluru
        
        Dates: **28 DECEMBER 2025 to 4 JANUARY 2026**
      # Enable Map View
      map:
        provider: 'leaflet'
        api_key: ''
        zoom: 15
    design:
      # Use a background image or map to make the section stand out
      background:
        image: 
          filename: 'map.png' # Placeholder for a map image or use actual map provider
          size: cover
          position: center

  # === 7. CONTACT BLOCK ===
  - block: contact
    id: contact
    content:
      title: Contact Us
      email: samy@iisc.ac.in # FIXED: Removed quotes/apostrophes
      # Contact form is optional - use external form link if needed
      # form:
      #   provider: netlify
      #   formspree:
      #     id: ''
      #   netlify:
      #     # Enable Netlify form?
      #     enable: true
      #     api_token: ''
      text: |
        Please direct all academic and logistical inquiries to the Coordinators listed below.
        
        **Pandarasamy Arjunan (Local & Academic Coordinator)**
        Email: samy@iisc.ac.in
        
        **Yogesh Simmhan (Local & Academic Coordinator)**
        Email: simmhan@iisc.ac.in
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"

  # === 8. Simple Footer CTA (Optional) ===
  - block: cta-card
    id: application
    content:
      title: Ready to join the future of Edge AI?
      text: Apply now for the ACM India Winter School 2025.
      button:
        text: Apply Today
        url: '#contact' # Link to the contact/application section
    design:
      card:
        css_class: "bg-primary-300"
---