# 🎓 EduConnect

> **Projects • People • Possibilities**  
> *Find the right people, projects, and opportunities in your academic journey.*  
> *Learn. Collaborate. Grow together.*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

---

## 📖 Overview

**EduConnect** is a modern, responsive web application and mobile-first experience crafted for academic networking, collaborative project discovery, and talent matchmaking. It seamlessly connects **Students**, **Teachers & Professors**, and **Organizations** into a unified ecosystem for learning, mentoring, and building innovative projects together.

The application features a complete **7-page onboarding and discovery flow**, built with 100% fidelity to design mockups, custom scalable SVG character illustrations, interactive state controls, and video player feed integrations.

---

## ✨ Features & Screen Architecture

### 📱 1. Onboarding Landing (`Page 1`)
- **Branding Header**: Mortarboard graduation cap emblem with **EduConnect** logo and `"Skip"` navigation.
- **Hero Headline**: *"Find the right people, projects, and opportunities in your academic journey."*
- **Vector Artwork**: 
  - 3 floating category badges: 💡 *Ideas & Innovation*, 👥 *People & Teaming*, 📋 *Notes & Checklist*.
  - Character group illustration: Student pointing to laptop, peer collaborator at computer, mentor with tablet, and potted office plant.
  - Stacked blue books with spine labels: **Learn**, **Build**, **Connect**.
- **Pagination**: 4-dot onboarding step indicator.
- **Action**: Primary `"Get Started →"` CTA button and quick `"Sign In"` authentication link.

### 👥 2. Role Selection (`Page 2`)
- **Step Progress**: Step 2 of 5 progress indicator.
- **Interactive Role Cards**:
  - 🎓 **I am a Student**: For learners seeking mentors, study partners, and project teams.
  - 👩‍🏫 **I am a Teacher / Professor**: For educators wanting to mentor, research, and collaborate.
  - 🏛️ **I am part of an Organization**: For universities, companies, and NGOs looking for student talent.
- **State Selection**: Dynamic border highlights and background tint selection.

### 📝 3. User Details (`Page 3`)
- **Visuals**: Vector student illustration with backpack and books.
- **Dropdown Controls**:
  - 🎓 *What is your field of study?* (Computer Science, Engineering, Business, Medicine, Arts).
  - 📅 *What year are you in?* (Freshman, Sophomore, Junior, Senior, Postgraduate/PhD).
- **Goal Checkboxes**: Multi-select goals (*Find a mentor*, *Join a project*, *Learn new skills*, *Find study partners*, *Explore research opportunities*, *Other*).
- **Tagline**: *"🌱 Small steps. A brighter you."*

### 💡 4. Topic Interests (`Page 4`)
- **Visuals**: Vector artwork of student with glasses thinking with lightbulb.
- **12 Selectable Topic Chips**: 
  - 🤖 AI / Machine Learning
  - `</>` Web Development
  - 📊 Data Science
  - 🛡️ Cybersecurity
  - 🤖 Robotics
  - 💼 Business
  - 🎨 Design
  - 🍃 Environment & Sustainability
  - 💙 Health & Medicine
  - 👥 Social Impact
  - 🎓 Education
  - `...` Other
- **Profile Callout Card**: 🧭 Settings indicator for updating preferences later.
- **Tagline**: *"🌱 Explore. Learn. Connect."*

### 📋 5. Final Details (`Page 5`)
- **Visuals**: Character with tablet and clipboard illustration.
- **Involvement Checkboxes**: Icon-badged multi-select options (`👥 Teachers`, `👥 Teammates`, `💼 Internships`, `📅 Events`, `🎓 Academic support`).
- **Availability Selector**: 🕒 Weekly commitment dropdown (*1-5 hrs*, *5-10 hrs*, *10+ hrs/week*).
- **Organization Outreach Toggle**: 🏛️ Interactive toggle switch card permitting institutional contact.
- **Tagline**: *"🌱 You're one step closer to new opportunities!"*

### 🤝 6. Engagement & Contacts (`Page 6`)
- **Visuals**: Thoughtful student with lightbulb artwork.
- **Engagement Goals**: Multi-select checkboxes (*Find talented students*, *Post projects*, *Collaborate with teachers*, *Host internships*, *Promote events*).
- **Contact Form**: Clean text inputs for optional contact person name (👤) and email (✉️).
- **Information Badge**: ℹ️ Privacy protection notice.
- **Tagline**: *"🌱 Together for a brighter tomorrow."*

### 🚀 7. Main Dashboard & Project Feed (`Page 7`)
- **Top Sticky Header**:
  - Dual-leaf sprout brand logo & solid navy **EduConnect** title.
  - 🔔 Notification bell icon.
  - User profile avatar with subtle ring.
- **Navigation Tabs**: **Projects** (active pill tab in `#EDEBFE` with `#4C39F8` underline), **People**, **For You**, plus Search 🔍.
- **Filter Chips**: Horizontal scrollable sub-category chips (*All* [active in `#4C39F8`], *AI/Tech*, *Sustainability*, *Health*, *Startups*).
- **Project Cards**:
  - **Card 1 ("Autonomous Campus Rover")**:
    - High-resolution rover vehicle media preview.
    - Top badges: `★ Featured` pill badge and interactive heart toggle button.
    - Title: *"Autonomous Campus Rover"* & subtitle: *"Building a self-navigating rover for campus delivery using computer vision and embedded systems."*
    - Tech tags: `Robotics`, `AI`, `Embedded Systems` (styled in `#E0E4FE` with `#3525D3` text).
    - Author info: **Daniel Kim** (*Mechanical Engineering*) with avatar.
    - Social stats: `👥 12` collaborators and `💬 5` discussions.
  - **Card 2 ("AI for Ocean Clean-Up")**:
    - High-resolution ocean sea turtle media preview with bookmark ribbon badge.
    - Title: *"AI for Ocean Clean-Up"* & subtitle: *"Using computer vision to detect and classify ocean waste from underwater footage."*
    - Tech tags: `AI`, `Sustainability`, `Computer Vision`.
- **Fixed 5-Item Bottom Navigation**:
  - 🏠 **Home** (active electric indigo `#4C39F8`)
  - 💬 **Messages**
  - ➕ **Add**
  - 🦘 **Kangaroo**
  - 👤 **Profile**

---

## 🎛️ Dual View Modes & Developer Controls

Included at the top of the app is a responsive toolbar allowing you to test:
1. **P1 – Feed Buttons**: Jump directly to any screen in single-screen mobile mode.
2. **"Show All" Mode**: Stacks all 7 screens top-to-bottom simultaneously on one continuous scrollable view so you can review the entire user journey without hiding any page.
3. **"Frame" Toggle**: Toggles between a realistic mobile phone device container and an expanded full-width responsive view.

---

## 🎨 Design Tokens & Palette

| Token | Hex Value | Usage |
|---|---|---|
| **Electric Violet / Indigo** | `#4C39F8` | Page 7 active chip, tab underline, brand accents |
| **Primary Blue** | `#1665F5` | Onboarding primary buttons, active tabs, brand accents |
| **Dark Navy / Slate** | `#0F172A` / `#0D1B3E` | Primary headings, brand titles, text |
| **Pill Background** | `#EDEBFE` | Page 7 active "Projects" pill tab |
| **Topic Chip Background** | `#E0E4FE` | Page 7 project tag chips (text `#3525D3`) |
| **Accent Green** | `#22C55E` | Plant vector artwork, motivational taglines |
| **Muted Slate** | `#64748B` / `#7E8BA0` | Body subtitles, unselected labels, borders |
| **Background Blue** | `#F0F7FF` | Highlighted selection cards, chips, badges |

### Typography
- **Primary Body & Headings**: `'Plus Jakarta Sans', sans-serif`
- **Handwritten Accents & Taglines**: `'Caveat', cursive`

---

## 📁 Repository Structure

```plaintext
educonnect/
├── assets/                  # High-resolution cropped assets (rover, turtle, avatars, logos)
├── index.html               # Complete 7-page standalone web application
├── styles.css               # Custom layout, animations, and typography styles
├── README.md                # Project documentation and feature breakdown
└── .gitignore               # Git ignore rules
```

---

## ⚡ Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/ranjeetkumarguptabro-maker/educonnect.git
cd educonnect
```

### 2. Run locally
Since EduConnect is built with pure web standards (HTML5, Tailwind CSS, Vanilla JS), you can open it directly in any web browser without needing a build step:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

Or run with a lightweight local web server:

```bash
# Python 3
python3 -m http.server 8000

# Node.js
npx serve .
```

Then visit [http://localhost:8000](http://localhost:8000) in your browser.

---

## 👤 Author

**Ranjeet Kumar Gupta**
- GitHub: [@ranjeetkumarguptabro-maker](https://github.com/ranjeetkumarguptabro-maker)

---

## 📄 License

This project is licensed under the MIT License. Feel free to use and adapt it for academic and collaboration platforms!
