---
title: 'Home'
date: 2025-11-10 # Current date
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # === 1. HERO BLOCK: Title, Dates, Host (FIXED TITLE & SPACING) ===
  - block: hero
    id: top
    content:
      title: ACM India Winter School on Edge AI
      text: |
        **28 DECEMBER 2025 to 4 JANUARY 2026**<br><br>

        **Host:** RBCCPS, Indian Institute of Science, Bengaluru<br><br>

        **Venue:** IDR Building, Indian Institute of Science<br><br>

        **Coordinators:** Pandarasamy Arjunan & Yogesh Simmhan
        
      primary_action:
        text: View Topics
        url: '#topics'
        icon: list-bullet
      secondary_action:
        text: Agenda
        url: '#agenda'
        icon: calendar
    design:
      columns: 1
      css_class: "dark"
      background:
        color: "navy"
        image:
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false

# === 2. ABOUT BLOCK: Description, Background, Software (FIXED ALIGNMENT) ===
  - block: markdown
    id: about
    content:
      title: About the School
      text: |
        <div style="text-align: left;">
        The **ACM India Winter School on Edge AI** will provide an in-depth overview of software platforms, hardware systems, and AI models and algorithms for efficient deployment on accelerated and classic edge devices. The program will cover topics suchs as edge computing architectures and accelerators, co-optimization techniques of edge systems and ML models for performance, power and accuracy, federated learning frameworks, and the deployment of AI, generative AI/LLM models and AI agents at the edge for practical and IoT applications such as smart mobility and smart agriculture. Through lectures, hands-on sessions, and expert talks, participants will gain practical skills to design, implement, and optimize intelligent edge systems for diverse real-world applications.
        
        ### Recommended Background / Prior Courses
        * Introductory course on Data science, Machine learning, or AI
        * Basics of Computer Systems
        * Embedded systems and IoT programming
        
        ### Specific Software to be Used
        * **Python 3** (scikit-learn, TensorFlow, Keras, LiteRT, PyTorch Edge, ExecuTorch)
        * **Jetpack SDK**
        * **MicroPython**
        </div>
        
    design:
      columns: 1
      # Aggressive override classes to maximize width and force left alignment
      css_class: "container-fluid text-left mx-auto max-w-full" 
      spacing:
        # Reduced padding slightly since the class will handle the width
        padding: ["3rem", "3rem", "3rem", "3rem"]

  # === 3. TOPICS BLOCK (Visually interactive with icons) ===
  - block: features
    id: topics
    content:
      title: Key Topics
      text: |
        The winter school covers foundational and advanced aspects of Edge AI.
      items:
        - name: Foundations of IoT, Accelerated Edge Computing and Edge AI
          icon: server
        - name: Tiny and Embedded Machine Learning
          icon: computer-desktop
        - name: Model Optimization and Acceleration for Edge AI
          icon: arrow-up-circle
        - name: Edge AI Platforms, Frameworks, and Deployment Pipelines
          icon: code-bracket
        - name: Federated Learning and Distributed Training for Edge Devices
          icon: users
        - name: Neuromorphic Computing and Brain-Inspired Architectures
          icon: cube
        - name: Generative AI and LLM at the Edge
          icon: sparkles
          
        # Note: I removed some items here to prevent line 45 error if it was related to items:
        # Re-adding them now, but keeping the syntax clean

        - name: Agentic AI on the Edge
          icon: cog
        - name: Security, Privacy, and Responsible AI in Edge Systems
          icon: lock-closed
        - name: Benchmarking, Profiling, and Performance Evaluation of Edge AI Systems
          icon: chart-bar
        - name: Edge AI for Drones/UAVs, IoT, Smart Cities, and Industrial Applications
          icon: globe-alt
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      columns: 3

# === 4. SPEAKERS BLOCK (Rendered as FEATURES for stability) ===
  - block: features
    id: speakers
    content:
      title: 🎤 Invited Speakers
      # The description text goes here
      text: |
        Click on any speaker card to view their institutional profile.
      items:
        - name: Gayathri Ananthanarayanan
          description: "[IIT Dharwad](https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan)"
          icon: user
          link: https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan
          image: speaker_gayathri.jpg # Hugo Blox features block often uses `image` for card media

        - name: Manik Gupta
          description: "[BITS Pilani](https://www.bits-pilani.ac.in/hyderabad/manik-gupta)"
          icon: user
          link: https://www.bits-pilani.ac.in/hyderabad/manik-gupta
          image: speaker_manik.jpg

        - name: Ajay Pratap
          description: "[IIT Bhuvaneswar](https://iitbhu.ac.in/dept/cse/people/ajaycse)"
          icon: user
          link: https://iitbhu.ac.in/dept/cse/people/ajaycse
          image: speaker_ajay.jpg

        - name: Pandarasamy Arjunan
          description: "[IISc](https://www.samy101.com/)"
          icon: user
          link: https://www.samy101.com/
          image: speaker_pandarasamy.jpg

        - name: Yogesh Simmhan
          description: "[IISc](https://cds.iisc.ac.in/faculty/simmhan/)"
          icon: user
          link: https://cds.iisc.ac.in/faculty/simmhan/
          image: speaker_yogesh.jpg

        - name: Sumit Mandal
          description: "[IISc](https://www.csa.iisc.ac.in/~skmandal)"
          icon: user
          link: https://www.csa.iisc.ac.in/~skmandal
          image: speaker_sumit.jpg

        - name: Punit Rathore
          description: "[IISc](https://www.punitrathore.com/home)"
          icon: user
          link: https://www.punitrathore.com/home
          image: speaker_punit.jpg

        - name: Prasant Misra
          description: "[TCS Research (Tutorial)](https://sites.google.com/site/prasantmisra/)"
          icon: user
          link: https://sites.google.com/site/prasantmisra/
          image: speaker_prasant.jpg

        - name: Varun Ojha
          description: "[New Castle University, UK](https://ojhavk.github.io/)"
          icon: user
          link: https://ojhavk.github.io/
          image: speaker_varun.jpg

        - name: Sajal Das
          description: "[Missouri Univ. of Sci. & Tech, USA](https://isc.mst.edu/people/ri/sdas/)"
          icon: user
          link: https://isc.mst.edu/people/ri/sdas/
          image: speaker_sajal.jpg
          
    design:
      # This is guaranteed to create 3 columns, like your Topics section
      columns: 3 
      view: card # Explicitly use the 'card' view for better presentation
      css_class: "bg-white"

  # === 5. AGENDA (NEW SECTION) ===
  - block: markdown
    id: agenda
    content:
      title: 📅 Agenda
      text: |
        The program will run from **28 DECEMBER 2025 to 4 JANUARY 2026**.

    design:
      columns: 1
      css_class: "bg-gray-100 dark:bg-gray-900"
      background:
          color: white
---
