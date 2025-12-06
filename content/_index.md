<style>
.schedule-table {
  width: 100%;
  border-collapse: collapse;
  margin-bottom: 25px;
  font-size: 14px;
}
.schedule-table th,
.schedule-table td {
  border: 1px solid #999;
  padding: 4px 6px;
  vertical-align: top;
}
.schedule-table th {
  background: #f0f0f0;
  font-weight: bold;
}
.schedule-table tr:nth-child(even) td {
  background: #fafafa;
}
</style>

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

        **Host:** <a href="https://cps.iisc.ac.in/">Robert Bosch Center for Cyber Physical Systems (RBCCPS)</a> & <a href="https://cds.iisc.ac.in/">Department of Computational and Data Sciences (CDS).</a> <br><br>

        **Venue:** CDS building, Indian Institute of Science (IISc), Bengaluru.<br><br>

        **Coordinators:** <a href="https://www.samy101.com/">Pandarasamy Arjunan</a> & 
        <a href="https://cds.iisc.ac.in/faculty/simmhan/">Yogesh Simmhan.</a>
        
        <div style="margin-top: 30px; text-align: center;">
          <img src="IISC.png" 
               alt="ACM India Logo" 
               style="max-height: 200px; max-width: 120%; display: inline-block;">
        </div>
        
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

  # === 2. ABOUT BLOCK: Description, Background, Software (WIDER & JUSTIFIED VIA CUSTOM CSS) ===
  - block: markdown
    id: about
    content:
      title: About the School
      text: |
        <p style="text-align: justify;">
        
        The **<a href="https://india.acm.org/education/acm-india-winter-schools-2025/">ACM India Winter School on Edge AI</a>** will provide an in-depth overview of software platforms, hardware systems, and AI models and algorithms for efficient deployment on accelerated and classic edge devices. The program will cover topics suchs as edge computing architectures and accelerators, co-optimization techniques of edge systems and ML models for performance, power and accuracy, federated learning frameworks, and the deployment of AI, generative AI/LLM models and AI agents at the edge for practical and IoT applications suchs as smart mobility and smart agriculture. Through lectures, hands-on sessions, and expert talks, participants will gain practical skills to design, implement, and optimize intelligent edge systems for diverse real-world applications.
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

  # === 4. SPEAKERS BLOCK (3-COLUMN GRID WITH VERTICAL SPACING, WIDTH OVERRIDDEN VIA CUSTOM CSS) ===
  - block: markdown
    id: speakers
    content:
      title: Speakers
      text: |
        <div style="display: flex; flex-wrap: wrap; justify-content: center; text-align: center; max-width: 1200px; margin: 0 auto;">
        
        <div style="width: 30%; min-width: 180px; margin: 40px 10px;"> 
          <a href="https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan">
            <img src="speaker_gayathri.jpg" alt="Photo of Gayathri Ananthanarayanan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Gayathri Ananthanarayanan</strong><br/>IIT Dharwad</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://www.bits-pilani.ac.in/hyderabad/manik-gupta">
            <img src="speaker_manik.jpg" alt="Photo of Manik Gupta" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Manik Gupta</strong><br/>BITS Pilani</p>
        </div>
        
        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://iitbhu.ac.in/dept/cse/people/ajaycse">
            <img src="speaker_ajay.jpg" alt="Photo of Ajay Pratap" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Ajay Pratap</strong><br/>IIT Bhuvaneswar</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://www.samy101.com/">
            <img src="speaker_pandarasamy.jpg" alt="Photo of Pandarasamy Arjunan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Pandarasamy Arjunan</strong><br/>IISc</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://cds.iisc.ac.in/faculty/simmhan/">
            <img src="speaker_yogesh.jpg" alt="Photo of Yogesh Simmhan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Yogesh Simmhan</strong><br/>IISc</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://www.csa.iisc.ac.in/~skmandal">
            <img src="speaker_sumit.jpg" alt="Photo of Sumit Mandal" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Sumit Mandal</strong><br/>IISc</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://www.punitrathore.com/home">
            <img src="speaker_punit.jpg" alt="Photo of Punit Rathore" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Punit Rathore</strong><br/>IISc</p>
        </div>
        
        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://sites.google.com/site/prasantmisra/">
            <img src="speaker_prasant.jpg" alt="Photo of Prasant Misra" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Prasant Misra</strong><br/>TCS Research</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://ojhavk.github.io/">
            <img src="speaker_varun.jpg" alt="Photo of Varun Ojha" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Varun Ojha</strong><br/>New Castle University, UK</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://isc.mst.edu/people/ri/sdas/">
            <img src="speaker_sajal.jpg" alt="Photo of Sajal Das" alt="Photo of Sajal Das" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Sajal Das</strong><br/>Missouri Univ. of Sci. & Tech, USA</p>
        </div>
        
        </div>
        
    design:
      view: compact
      columns: 1

  # === 5. PROGRAMS (NEW SECTION) ===
  - block: markdown
    id: programs
    content:
      title: Programs
      text: |
        The program will run from **28 DECEMBER 2025 to 4 JANUARY 2026**.

        ## DAY 1 - 28th Dec 2025
        | Time | Event | Location |
        | :--- | :--- | :--- |
        | 9am | Coffee | Canteen |
        | 10am | Edge AI | Room 1 |
        | 11am | Talk on XYZ | Room 2 |
        | 12pm | Lunch | Canteen |
        | 1pm | Hands-on Session | Lab A |
        | 3pm | Break | Canteen |
        | 3:30pm | Invited Talk | Room 1 |
        | 5pm | End of Day 1 | |

        ---

        ## DAY 2 - 29th Dec 2025
        | Time | Event | Location |
        | :--- | :--- | :--- |
        | 9am | Coffee | Canteen |
        | 10am | Edge AI | Room 1 |
        | 11am | Talk on ABC | Room 2 |
        | 12pm | Lunch | Canteen |
        | 1pm | Hands-on Session | Lab B |
        | 3pm | Break | Canteen |
        | 3:30pm | Invited Talk | Room 1 |
        | 5pm | End of Day 2 | |
        
    design:
      columns: 1
      css_class: "bg-gray-100 dark:bg-gray-900" 
      background:
        color: white

## Program

<!-- Day-1 -->
### Day-1, 28-Dec-2024
<table class="schedule-table">
<thead>
<tr><th>Time</th><th>Speaker</th><th>Title</th></tr>
</thead>
<tbody>
<tr><td>9:00 – 10:00 AM</td><td>Vijay Janappa Reddi (Harvard University)</td><td>—</td></tr>
<tr><td>10:00 – 11:00 AM</td><td>Chetan Singh Thakur (IISc)</td><td>—</td></tr>
<tr><td>11:15 AM – 12:45 PM</td><td>Chetan Singh Thakur (IISc)</td><td>—</td></tr>
<tr><td>2:00 – 3:30 PM</td><td>Samy (IISc)</td><td>Tiny ML Lab</td></tr>
<tr><td>4:00 – 5:30 PM</td><td>Samy (IISc)</td><td>Tiny ML Lab</td></tr>
<tr><td>5:30 – 7:00 PM</td><td>Samy (IISc)</td><td>Tiny ML Lab</td></tr>
</tbody>
</table>

<br>

<!-- Day-2 -->
### Day-2, 29-Dec-2024
<table class="schedule-table">
<thead>
<tr><th>Time</th><th>Speaker</th><th>Title</th></tr>
</thead>
<tbody>
<tr><td>9:00 – 10:00 AM</td><td>Sumit Kumar Mandal (IISc)</td><td>—</td></tr>
<tr><td>10:00 – 11:00 AM</td><td>Gayathri Ananthanarayanan (IIT Dharwad)</td><td>—</td></tr>
<tr><td>11:15 AM – 12:45 PM</td><td>Gayathri Ananthanarayanan (IIT Dharwad)</td><td>—</td></tr>
<tr><td>2:00 – 3:30 PM</td><td>Samy (IISc)</td><td>Embedded Computer Vision</td></tr>
<tr><td>4:00 – 5:30 PM</td><td>Samy (IISc)</td><td>Embedded Computer Vision</td></tr>
<tr><td>5:30 – 7:00 PM</td><td>Samy (IISc)</td><td>Embedded Computer Vision</td></tr>
</tbody>
</table>

<br>

<!-- Day-3 -->
### Day-3, 30-Dec-2024
<table class="schedule-table">
<thead>
<tr><th>Time</th><th>Speaker</th><th>Title</th></tr>
</thead>
<tbody>
<tr><td>9:00 – 10:00 AM</td><td>Yogesh (IISc)</td><td>—</td></tr>
<tr><td>10:00 – 11:00 AM</td><td>Yogesh (IISc)</td><td>—</td></tr>
<tr><td>11:15 AM – 12:45 PM</td><td>Prashanti (AMD)</td><td>—</td></tr>
<tr><td>2:00 – 3:30 PM</td><td>Yogesh (IISc)</td><td>ML on Edge Accelerators</td></tr>
<tr><td>4:00 – 5:30 PM</td><td>Yogesh (IISc)</td><td>ML on Edge Accelerators</td></tr>
<tr><td>5:30 – 7:00 PM</td><td>Yogesh (IISc)</td><td>ML on Edge Accelerators</td></tr>
</tbody>
</table>

<br>

<!-- Day-4 -->
### Day-4, 31-Dec-2024
<table class="schedule-table">
<thead>
<tr><th>Time</th><th>Speaker</th><th>Title</th></tr>
</thead>
<tbody>
<tr><td>9:00 – 10:00 AM</td><td>Yogesh (IISc)</td><td>—</td></tr>
<tr><td>10:00 – 11:00 AM</td><td>Yogesh (IISc)</td><td>—</td></tr>
<tr><td>11:15 AM – 12:45 PM</td><td>Yogesh (IISc)</td><td>FL on Edge</td></tr>
<tr><td>2:00 – 3:30 PM</td><td>Varun (New Castle)</td><td>—</td></tr>
<tr><td>4:00 – 5:30 PM</td><td>Varun (New Castle)</td><td>—</td></tr>
<tr><td>5:30 – 7:00 PM</td><td>Yogesh (IISc)</td><td>FL on Edge</td></tr>
</tbody>
</table>

<br>

<!-- Day-5 -->
### Day-5, 01-Jan-2025
<table class="schedule-table">
<thead>
<tr><th>Time</th><th>Speaker</th><th>Title</th></tr>
</thead>
<tbody>
<tr><td>9:00 – 10:00 AM</td><td>Samy (IISc)</td><td>—</td></tr>
<tr><td>10:00 – 11:00 AM</td><td>Sumit Kumar Mandal (IISc)</td><td>—</td></tr>
<tr><td>11:15 AM – 12:45 PM</td><td>Prasant Misra (IISc & TCS)</td><td>—</td></tr>
<tr><td>2:00 – 3:30 PM</td><td>Punit (IISc)</td><td>—</td></tr>
<tr><td>4:00 – 5:30 PM</td><td>Samy (IISc)</td><td>Gen AI at Edge</td></tr>
<tr><td>5:30 – 7:00 PM</td><td>Samy (IISc)</td><td>Gen AI at Edge</td></tr>
</tbody>
</table>

<br>

<!-- Day-6 -->
### Day-6, 02-Jan-2025
<table class="schedule-table">
<thead>
<tr><th>Time</th><th>Speaker</th><th>Title</th></tr>
</thead>
<tbody>
<tr><td>9:00 – 10:00 AM</td><td>Sajal (Missouri)</td><td>—</td></tr>
<tr><td>10:00 – 11:00 AM</td><td>Manik Gupta (BITS Pilani)</td><td>—</td></tr>
<tr><td>11:15 AM – 12:45 PM</td><td>Manik Gupta (BITS Pilani)</td><td>—</td></tr>
<tr><td>2:00 – 3:30 PM</td><td>Manik Gupta (BITS Pilani)</td><td>IoT Analytics</td></tr>
<tr><td>4:00 – 5:30 PM</td><td>MATLAB</td><td>—</td></tr>
<tr><td>5:30 – 7:00 PM</td><td>Reserved (Qualcomm)</td><td>—</td></tr>
</tbody>
</table>

<br>

<!-- Day-7 -->
### Day-7, 03-Jan-2025
<table class="schedule-table">
<thead>
<tr><th>Time</th><th>Speaker</th><th>Title</th></tr>
</thead>
<tbody>
<tr><td>9:00 – 10:00 AM</td><td>Archan Misra (SMU)</td><td>—</td></tr>
<tr><td>10:00 – 11:00 AM</td><td>Ajay Pratap (IIT Bhu)</td><td>—</td></tr>
<tr><td>11:15 AM – 12:45 PM</td><td>Ajay Pratap (IIT Bhu)</td><td>—</td></tr>
<tr><td>2:00 – 3:30 PM</td><td>Arm</td><td>—</td></tr>
<tr><td>4:00 – 5:30 PM</td><td>Hackathon</td><td>—</td></tr>
<tr><td>5:30 – 7:00 PM</td><td>Hackathon</td><td>—</td></tr>
</tbody>
</table>

<br>

<!-- Day-8 -->
### Day-8, 04-Jan-2025
<table class="schedule-table">
<thead>
<tr><th>Time</th><th>Speaker</th><th>Title</th></tr>
</thead>
<tbody>
<tr><td>9:00 – 10:00 AM</td><td>Hackathon</td><td>—</td></tr>
<tr><td>10:00 – 11:00 AM</td><td>Hackathon</td><td>—</td></tr>
<tr><td>11:15 AM – 12:45 PM</td><td>Hackathon</td><td>—</td></tr>
<tr><td>2:00 – 3:30 PM</td><td>Hackathon</td><td>—</td></tr>
<tr><td>4:00 – 5:30 PM</td><td>Hackathon</td><td>Demo / Presentation</td></tr>
<tr><td>5:30 – 7:00 PM</td><td>Certificate Distribution</td><td>Closing</td></tr>
</tbody>
</table>

    

# === 6. LOGISTICS AND MAPS (NEW SECTION) ===
  - block: markdown
    id: venue
    content:
      title: Venue
      text: |
        This Program is hosted at the **CDS building, Indian Institute of Science (IISc), Bengaluru**.
        
        ### Location and Access
        * **Location:** The IISc campus is easily accessible from all parts of Bengaluru. The nearest metro station is **Yeshwanthpur**.
        * **Venue Map:** The CDS building is located near the main administrative block. <a href="https://maps.app.goo.gl/Sygki6ResDbrqMEy9">
          <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="location-dot" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512" data-fa-i2svg="" style="display: inline-block; height: 1em; margin-left: 0.5em;"><path fill="currentColor" d="M168.3 499.2C116.1 435 0 279.4 0 192C0 85.96 85.96 0 192 0C298 0 384 85.96 384 192C384 279.4 267 435 215.7 499.2C203.4 514.5 180.6 514.5 168.3 499.2H168.3zM192 256C227.3 256 256 227.3 256 192C256 156.7 227.3 128 192 128C156.7 128 128 156.7 128 192C128 227.3 156.7 256 192 256z"></path></svg> Click Here
          </a>
        
        ### Key Contacts
        
        If you have any logistical or academic questions regarding the Winter School, please contact the coordinators:
        * **Pandarasamy Arjunan:** <a href="mailto:samy@iisc.ac.in">samy@iisc.ac.in</a>
        * **Yogesh Simmhan:** <a href="mailto:simmhan@iisc.ac.in">simmhan@iisc.ac.in</a>
        
    design:
      columns: 1
      css_class: "" 
      background:
        color: white
      spacing:
        padding: ["6rem","0","6rem","0"]

  # === 7. SPONSORS / SUPPORTED BY (NEW SECTION WITH LOGOS) ===
  - block: markdown
    id: sponsors
    content:
      title: Supported By
      text: |
        <div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 30px; margin-top: 30px;">
        
          <a href="https://india.acm.org/" target="_blank">
            <img src="acm-logo.png" alt="ACM India Council" style="max-height: 100px; width: auto;">
          </a>
          
          <a href="https://www.iisc.ac.in/" target="_blank">
            <img src="iisc_logo.png" alt="IISc" style="max-height: 100px; width: auto;">
          </a>

          <a href="https://rbccps.org/" target="_blank">
            <img src="rbccps-logo.png" alt="RBCCPS" style="max-height: 100px; width: auto;">
          </a>

          <a href="https://artpark.in/" target="_blank">
            <img src="ARTPARK-logo.png" alt="ARTPARK" style="max-height: 100px; width: auto;">
          </a>
          
          <a href="https://cds.iisc.ac.in/" target="_blank">
            <img src="cds_logo.png" alt="CDS" style="max-height: 100px; width: auto;">
          </a>

        </div>
        
    design:
      columns: 1
      css_class: "bg-gray-100 dark:bg-gray-900"
      background:
        color: white
      spacing:
        padding: ["3rem","0","3rem","0"]
---
