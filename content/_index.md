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

# === 4. SPEAKERS BLOCK (STABLE MARKDOWN LIST with External Images) ===
  - block: markdown
    id: speakers
    content:
      title: 🎤 Invited Speakers
      text: |
        *Instructions: Please replace 'EXTERNAL_URL_X' with the public link to the speaker's photo.*
        
        ### Group 1
        
        | Speaker | Affiliation | Profile |
        | :--- | :--- | :--- |
        | ![Gayathri Ananthanarayanan](EXTERNAL_URL_1) **[G. Ananthanarayanan](https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan)** | IIT Dharwad | [View Profile] |
        | ![Manik Gupta](EXTERNAL_URL_2) **[Manik Gupta](https://www.bits-pilani.ac.in/hyderabad/manik-gupta)** | BITS Pilani | [View Profile] |
        | ![Ajay Pratap](EXTERNAL_URL_3) **[Ajay Pratap](https://iitbhu.ac.in/dept/cse/people/ajaycse)** | IIT Bhuvaneswar | [View Profile] |
        | ![Pandarasamy Arjunan](EXTERNAL_URL_4) **[P. Arjunan](https://www.samy101.com/)** | IISc | [View Profile] |
        | ![Yogesh Simmhan](EXTERNAL_URL_5) **[Yogesh Simmhan](https://cds.iisc.ac.in/faculty/simmhan/)** | IISc | [View Profile] |

        ### Group 2
        
        | Speaker | Affiliation | Profile |
        | :--- | :--- | :--- |
        | ![Sumit Mandal](EXTERNAL_URL_6) **[Sumit Mandal](https://www.csa.iisc.ac.in/~skmandal)** | IISc | [View Profile] |
        | ![Punit Rathore](EXTERNAL_URL_7) **[Punit Rathore](https://www.punitrathore.com/home)** | IISc | [View Profile] |
        | ![Prasant Misra](EXTERNAL_URL_8) **[Prasant Misra](https://sites.google.com/site/prasantmisra/)** | TCS Research (Tutorial) | [View Profile] |
        | ![Varun Ojha](EXTERNAL_URL_9) **[Varun Ojha](https://ojhavk.github.io/)** | New Castle University, UK | [View Profile] |
        | ![Sajal Das](EXTERNAL_URL_10) **[Sajal Das](https://isc.mst.edu/people/ri/sdas/)** | Missouri Univ. of Sci. & Tech, USA | [View Profile] |

        ---
        
        *Additional speakers being invited from Industries.*

    design:
      columns: 1

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
