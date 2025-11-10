---
title: 'Home'
date: 2025-11-10 # Current date
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # === 1. HERO BLOCK: Title, Dates, Host ===
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
          filename: 'bg-triangles.svg'
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false

  ---
  # === 2. ABOUT BLOCK: Description, Background (Distinct Color) ===
  - block: markdown
    id: about
    content:
      title: About the School
      text: |
        The **ACM India Winter School on Edge AI** will provide an in-depth overview of software platforms, hardware systems, and AI models and algorithms for efficient deployment on accelerated and classic edge devices. The program will cover topics such as edge computing architectures and accelerators, co-optimization techniques of edge systems and ML models for performance, power and accuracy, federated learning frameworks, and the deployment of AI, generative AI/LLM models and AI agents at the edge for practical and IoT applications such as smart mobility and smart agriculture. Through lectures, hands-on sessions, and expert talks, participants will gain practical skills to design, implement, and optimize intelligent edge systems for diverse real-world applications.
    design:
      css_class: ""
      background:
        color: white

  ---
  # === 3. TOPICS BLOCK (Visually interactive with icons - Distinct Color) ===
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

  ---
  # === 4. SPEAKERS BLOCK (Using 'people' block for 3-column layout) ===
  - block: people
    id: speakers
    content:
      title: 🎤 Invited Speakers
      text: |
        *Additional speakers being invited from Industries.*
      items:
        - name: Gayathri Ananthanarayanan
          role: IIT Dharwad
          image: 'speaker_gayathri.jpg'
          url: 'https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan'
        - name: Manik Gupta
          role: BITS Pilani
          image: 'speaker_manik.jpg'
          url: 'https://www.bits-pilani.ac.in/hyderabad/manik-gupta'
        - name: Ajay Pratap
          role: IIT Bhuvaneswar
          image: 'speaker_ajay.jpg'
          url: 'https://iitbhu.ac.in/dept/cse/people/ajaycse'
        - name: Pandarasamy Arjunan
          role: IISc
          image: 'speaker_pandarasamy.jpg'
          url: 'https://www.samy101.com/'
        - name: Yogesh Simmhan
          role: IISc
          image: 'speaker_yogesh.jpg'
          url: 'https://cds.iisc.ac.in/faculty/simmhan/'
        - name: Sumit Mandal
          role: IISc
          image: 'speaker_sumit.jpg'
          url: 'https://www.csa.iisc.ac.in/~skmandal'
        - name: Punit Rathore
          role: IISc
          image: 'speaker_punit.jpg'
          url: 'https://www.punitrathore.com/home'
        - name: Prasant Misra
          role: TCS Research
          image: 'speaker_prasant.jpg'
          url: 'https://sites.google.com/site/prasantmisra/'
        - name: Varun Ojha
          role: New Castle University, UK
          image: 'speaker_varun.jpg'
          url: 'https://ojhavk.github.io/'
        - name: Sajal Das
          role: Missouri Univ. of Sci. & Tech, USA
          image: 'speaker_sajal.jpg'
          url: 'https://isc.mst.edu/people/ri/sdas/'

    design:
      css_class: ""
      show_role: true
      show_social: false
      columns: 3

  ---
  # === 5. AGENDA (Distinct Color and Table) ===
  - block: markdown
    id: agenda
    content:
      title: 📅 Agenda
      text: |
        The program will run from **28 DECEMBER 2025 to 4 JANUARY 2026**.

        | Date | Time | Topic/Event | Speaker |
        | :--- | :--- | :--- | :--- |
        | Day 1 (Dec 28) | 9:00 - 10:30 | Inauguration & Keynote | Coordinator Team |
        | Day 1 (Dec 28) | 10:45 - 12:30 | Foundations of Edge AI | Speaker 1 |
        | Day 8 (Jan 4) | 14:00 - 16:00 | Hands-on Lab: LLMs on Edge | Team TBD |
        | Day 8 (Jan 4) | 16:00 - 17:00 | Closing Ceremony | Coordinator Team |

        *Note: This is a placeholder agenda. The full detailed agenda will be updated soon.*

    design:
      columns: 1
      css_class: "bg-green-100 dark:bg-green-900"
      background:
        color: '#f0fff0'
---

Assuming the environment issue is resolved, what part of the page content would you like to refine next?
