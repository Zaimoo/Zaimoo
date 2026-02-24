<p align="center">
<svg width="100%" height="280" viewBox="0 0 1200 280" xmlns="http://www.w3.org/2000/svg">

  <!-- Background -->
  <rect width="1200" height="280" fill="#0b0f19"/>

  <!-- Grid Pattern -->
  <defs>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#1f2937" stroke-width="1"/>
    </pattern>
    <!-- Glow -->
    <filter id="softGlow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Animated Grid -->
  <rect width="1200" height="280" fill="url(#grid)" opacity="0.25">
    <animateTransform 
      attributeName="transform"
      type="translate"
      from="0 0"
      to="40 40"
      dur="18s"
      repeatCount="indefinite"/>
  </rect>

  <!-- Floating Code Snippets -->
  <text x="150" y="60" font-family="JetBrains Mono" font-size="14" fill="#38bdf8" opacity="0.4">
    const build = () => scale();
    <animate attributeName="y" values="60;40;60" dur="10s" repeatCount="indefinite"/>
  </text>

  <text x="850" y="90" font-family="JetBrains Mono" font-size="14" fill="#38bdf8" opacity="0.3">
    supabase.auth.session()
    <animate attributeName="y" values="90;120;90" dur="12s" repeatCount="indefinite"/>
  </text>

  <text x="300" y="220" font-family="JetBrains Mono" font-size="14" fill="#38bdf8" opacity="0.3">
    flutter run --release
    <animate attributeName="y" values="220;200;220" dur="11s" repeatCount="indefinite"/>
  </text>

  <!-- Accent Pulse Line -->
  <line x1="250" y1="200" x2="950" y2="200"
        stroke="#38bdf8"
        stroke-width="2"
        opacity="0.6">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="3s" repeatCount="indefinite"/>
  </line>

  <!-- Name (Cinematic Fade-In) -->
  <text x="600" y="130"
        text-anchor="middle"
        font-family="JetBrains Mono, monospace"
        font-size="44"
        fill="#ffffff"
        letter-spacing="3"
        opacity="0"
        filter="url(#softGlow)">
    Rey Cezar Tigley
    <animate attributeName="opacity" from="0" to="1" dur="2s" fill="freeze"/>
  </text>

  <!-- Subtitle -->
  <text x="600" y="170"
        text-anchor="middle"
        font-family="JetBrains Mono, monospace"
        font-size="18"
        fill="#38bdf8"
        letter-spacing="4"
        opacity="0">
    FULL-STACK • MOBILE DEVELOPER
    <animate attributeName="opacity" from="0" to="1" dur="3s" fill="freeze"/>
  </text>

</svg>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=18&duration=3000&pause=1000&color=64B5F6&center=true&vCenter=true&width=700&lines=Full-Stack+Web+%26+Mobile+Developer;Flutter+%7C+Firebase+%7C+Dart;Next.js+%7C+Supabase+%7C+TypeScript;Building+Scalable+%26+Purposeful+Systems+%F0%9F%9A%80" />
</p>

<p align="center">
  <a href="mailto:reycezartigley@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>&nbsp;
  <a href="https://www.linkedin.com/in/rctigley"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"/></a>&nbsp;
  <a href="https://github.com/Zaimoo"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>&nbsp;
  <a href="https://facebook.com/rctigley"><img src="https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white"/></a>&nbsp;
  <a href="https://instagram.com/rczvt_"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white"/></a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=Zaimoo&label=Profile+Views&color=0d2137&style=flat-square"/>
</p>

---

## About Me

I'm a **BS Information Systems** student based in the **Philippines**, passionate about building meaningful, scalable software for real-world problems. My work spans mobile apps, full-stack web platforms, and intelligent systems — with a strong focus on clean architecture, system optimization, and user-centered design.

- 📱 Building mobile experiences with **Flutter & Firebase**
- 🌐 Engineering full-stack web apps using **Next.js, Supabase & TypeScript**
- 🗺️ Currently developing a tourism & mobility platform for Iligan City
- 🔍 Interested in smart systems, geospatial UX, and design thinking methodologies

## 🎧 Now Playing

[![spotify-github-profile](https://spotify-github-profile.kittinanx.com/api/view?uid=9ca2xq33um7vpssfseb56lf5g&cover_image=true&theme=novatorem&show_offline=false&background_color=121212&interchange=false&profanity=false&bar_color=53b14f&bar_color_cover=true)](https://github.com/kittinan/spotify-github-profile)
---

## 🛠 Tech Stack

**Frontend & Mobile**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

**Backend & BaaS**

![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore-FF6F00?style=flat-square&logo=firebase&logoColor=white)

---

## 📌 Featured Projects

### 🗺️ TourEase *(Ongoing Thesis)*
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square)&nbsp;![Type](https://img.shields.io/badge/Type-Thesis-blueviolet?style=flat-square)&nbsp;![Platform](https://img.shields.io/badge/Platform-Mobile-blue?style=flat-square)

> A design thinking-driven mobile application for exploring tourist destinations in **Iligan City**, featuring an interactive map with real-time routing and destination discovery.

**Highlights:** UX-centered design process · Geospatial routing · Local tourism integration  
**Tech Stack:** Flutter · Firebase · Google Maps API · Dart

---

### 🛺 TriGoRide
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square)&nbsp;![Type](https://img.shields.io/badge/Type-Personal%20Project-orange?style=flat-square)&nbsp;![Platform](https://img.shields.io/badge/Platform-Mobile-blue?style=flat-square)

> A **ride-hailing platform** built specifically for tricycle drivers and commuters — bridging the gap in local transportation through a purpose-built mobile experience.

**Highlights:** Real-time driver matching · Booking flow · Driver & rider interfaces  
**Tech Stack:** Flutter · Firebase · Firestore

---

### 🎓 OJT Company Recommendation System
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)&nbsp;![Type](https://img.shields.io/badge/Type-Academic-blueviolet?style=flat-square)&nbsp;![Platform](https://img.shields.io/badge/Platform-Web-informational?style=flat-square)

> A smart profile-based recommendation engine that intelligently matches students with OJT companies based on skills, preferences, and compatibility scores.

**Highlights:** Recommendation algorithm · Profile matching · Admin dashboard  
**Tech Stack:** Next.js · Supabase · TypeScript · Tailwind CSS

---

### 📐 Quest for Calculus
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)&nbsp;![Type](https://img.shields.io/badge/Type-Academic-blueviolet?style=flat-square)&nbsp;![Platform](https://img.shields.io/badge/Platform-Mobile-blue?style=flat-square)

> A **gamified mobile quiz app** that makes calculus engaging through level-based progression, instant feedback, and achievement tracking.

**Highlights:** Gamification mechanics · Progress tracking · Interactive problem sets  
**Tech Stack:** Flutter · Firebase

---

### 🏪 Inventory & POS Integration System
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)&nbsp;![Type](https://img.shields.io/badge/Type-Personal%20Project-orange?style=flat-square)&nbsp;![Platform](https://img.shields.io/badge/Platform-Web-informational?style=flat-square)

> An integrated sales and inventory management platform designed to synchronize point-of-sale transactions with stock data in real time.

**Highlights:** Real-time sync · Transaction logging · Inventory alerts  
**Tech Stack:** PHP · MySQL

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Zaimoo&theme=tokyonight&hide_border=true&border_radius=8" width="49%"/>
  <img src="https://github-readme-stats.vercel.app/api?username=Zaimoo&show_icons=true&theme=tokyonight&hide_border=true&border_radius=8&count_private=true" width="49%"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Zaimoo&theme=tokyo-night&hide_border=true&radius=8" width="98%"/>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:0d2137,100:0a0f1e&height=120&section=footer"/>
</p>
