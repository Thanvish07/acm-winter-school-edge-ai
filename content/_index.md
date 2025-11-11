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
    design:
      columns: 1
      css_class: "dark text-left" # FIX: Preserving 'text-left' for left-alignment
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
        <p style="text-align: justify; max-width: 1000px; margin: 0 auto;">
        
        The **ACM India Winter School on Edge AI** will provide an in-depth overview of software platforms, hardware systems, and AI models and algorithms for efficient deployment on accelerated and classic edge devices. The program will cover topics suchs as edge computing architectures and accelerators, co-optimization techniques of edge systems and ML models for performance, power and accuracy, federated learning frameworks, and the deployment of AI, generative AI/LLM models and AI agents at the edge for practical and IoT applications such as smart mobility and smart agriculture. Through lectures, hands-on sessions, and expert talks, participants will gain practical skills to design, implement, and optimize intelligent edge systems for diverse real-world applications.
        </p>
    design:
      columns: 1
      spacing:
        padding: ["6rem","0","6rem","0"]

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

# === 4. SPEAKERS BLOCK (Custom HTML/CSS for Circular Grid Layout - FINAL) ===
  - block: markdown
    id: speakers
    content:
      title: 🎤 Invited Speakers
      text: |
        <div style="display: flex; flex-wrap: wrap; justify-content: center; text-align: center; max-width: 1200px; margin: 0 auto;">
        
        <div style="width: 30%; min-width: 180px; margin: 10px;"> 
          <a href="https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan">
            <img src="speaker_gayathri.jpg" alt="Photo of Gayathri Ananthanarayanan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Gayathri Ananthanarayanan</strong><br/>IIT Dharwad</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 10px;">
          <a href="https://www.bits-pilani.ac.in/hyderabad/manik-gupta">
            <img src="speaker_manik.jpg" alt="Photo of Manik Gupta" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Manik Gupta</strong><br/>BITS Pilani</p>
        </div>
        
        <div style="width: 30%; min-width: 180px; margin: 10px;">
          <a href="https://iitbhu.ac.in/dept/cse/people/ajaycse">
            <img src="speaker_ajay.jpg" alt="Photo of Ajay Pratap" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Ajay Pratap</strong><br/>IIT Bhuvaneswar</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 10px;">
          <a href="https://www.samy101.com/">
            <img src="speaker_pandarasamy.jpg" alt="Photo of Pandarasamy Arjunan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Pandarasamy Arjunan</strong><br/>IISc</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 10px;">
          <a href="https://cds.iisc.ac.in/faculty/simmhan/">
            <img src="speaker_yogesh.jpg" alt="Photo of Yogesh Simmhan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Yogesh Simmhan</strong><br/>IISc</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 10px;">
          <a href="https://www.csa.iisc.ac.in/~skmandal">
            <img src="speaker_sumit.jpg" alt="Photo of Sumit Mandal" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Sumit Mandal</strong><br/>IISc</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 10px;">
          <a href="https://www.punitrathore.com/home">
            <img src="speaker_punit.jpg" alt="Photo of Punit Rathore" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Punit Rathore</strong><br/>IISc</p>
        </div>
        
        <div style="width: 30%; min-width: 180px; margin: 10px;">
          <a href="https://sites.google.com/site/prasantmisra/">
            <img src="speaker_prasant.jpg" alt="Photo of Prasant Misra" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Prasant Misra</strong><br/>TCS Research</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 10px;">
          <a href="https://ojhavk.github.io/">
            <img src="speaker_varun.jpg" alt="Photo of Varun Ojha" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Varun Ojha</strong><br/>New Castle University, UK</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 10px;">
          <a href="https://isc.mst.edu/people/ri/sdas/">
            <img src="speaker_sajal.jpg" alt="Photo of Sajal Das" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Sajal Das</strong><br/>Missouri Univ. of Sci. & Tech, USA</p>
        </div>
        
        </div>
        
        ---
        
        *Additional speakers being invited from Industries.*
        
    design:
      view: compact
      columns: 1

# === 5. PROGRAMS (NEW SECTION) ===
  - block: markdown
    id: programs
    content:
      title: 📅 Programs
      text: |
        The program will run from **28 DECEMBER 2025 to 4 JANUARY 2026**.

    design:
      columns: 1
      css_class: "bg-gray-100 dark:bg-gray-900"
      background:
        color: white
---
