---
theme: seriph
background: https://source.unsplash.com/collection/8747326/1920x1080
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  ## IT Student Portfolio Presentation
  A showcase of skills, projects, and achievements in Information Technology.
drawings:
  persist: false
css: unocss
---

# IT Student Portfolio
Journey Through Technology

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: image-right
image: https://source.unsplash.com/collection/8747326/1920x1080
---

# Technical Skills

- 💻 Programming Languages
  - Python, Java, JavaScript
  - HTML5, CSS3
- 🛠 Development Tools
  - Git, VS Code
  - Docker
- 🔧 System Administration
  - Linux/Unix
  - Network Configuration
- 📊 Database Management
  - SQL, MongoDB

---

# Academic Projects

```ts {all|2-3|4-5|6-7|all}
const projects = {
  webDev: "E-commerce Platform",
  description: "Built with React & Node.js",
  database: "Student Management System",
  stack: "Python & PostgreSQL",
  network: "Network Security Analysis",
  tools: "Wireshark & Nmap"
}
```

<arrow v-click="2" x1="400" y1="420" x2="230" y2="330" color="#564" width="3" arrowSize="1" />

---
layout: two-cols
---

# Certifications

<div class="mr-4">

- CompTIA A+
- AWS Cloud Practitioner
- Cisco CCNA (In Progress)
- Microsoft Azure Fundamentals

</div>

::right::

# Soft Skills

- Team Collaboration
- Problem Solving
- Project Management
- Technical Documentation
- Time Management

---
class: px-20
---

# Work Experience

<div class="grid grid-cols-2 gap-4">
<div>

### IT Help Desk Intern
- Technical support for 200+ users
- Hardware troubleshooting
- Network maintenance
- Ticket system management

</div>
<div>

### Student IT Assistant
- Lab maintenance
- Software installation
- User training
- Documentation

</div>
</div>

---
preload: false
---

# Future Goals

<div class="grid grid-cols-2 gap-4 mt-4">
<div v-motion :initial="{ x: -100 }" :enter="{ x: 0 }">

### Short Term
- Complete CCNA certification
- Internship at tech company
- Build portfolio website
- Learn cloud technologies

</div>
<div v-motion :initial="{ x: 100 }" :enter="{ x: 0 }">

### Long Term
- Full-stack developer role
- Master's in Cybersecurity
- Start tech blog
- Contribute to open source

</div>
</div>

---
layout: center
class: text-center
---

# Thank You!

Contact Information:
- 📧 student@email.com
- 💼 linkedin.com/in/student
- 🐙 github.com/student