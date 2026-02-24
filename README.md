<p align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 280" width="900" height="280">
    <defs>
      <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#050d1a"/>
        <stop offset="50%" style="stop-color:#091628"/>
        <stop offset="100%" style="stop-color:#0a1f3d"/>
      </linearGradient>
      <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#64b5f6">
          <animate attributeName="stop-color" values="#64b5f6;#90caf9;#42a5f5;#64b5f6" dur="4s" repeatCount="indefinite"/>
        </stop>
        <stop offset="50%" style="stop-color:#90caf9">
          <animate attributeName="stop-color" values="#90caf9;#42a5f5;#64b5f6;#90caf9" dur="4s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" style="stop-color:#42a5f5">
          <animate attributeName="stop-color" values="#42a5f5;#64b5f6;#90caf9;#42a5f5" dur="4s" repeatCount="indefinite"/>
        </stop>
      </linearGradient>
      <linearGradient id="gridFade" x1="0%" y1="0%" x2="0%" y2="100%">
        <stop offset="0%" style="stop-color:#1a3a5c;stop-opacity:0"/>
        <stop offset="40%" style="stop-color:#1a3a5c;stop-opacity:0.5"/>
        <stop offset="100%" style="stop-color:#1a3a5c;stop-opacity:0"/>
      </linearGradient>
      <linearGradient id="scanGrad" x1="0%" y1="0%" x2="0%" y2="100%">
        <stop offset="0%" style="stop-color:#64b5f6;stop-opacity:0"/>
        <stop offset="50%" style="stop-color:#64b5f6;stop-opacity:0.08"/>
        <stop offset="100%" style="stop-color:#64b5f6;stop-opacity:0"/>
      </linearGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="3.5" result="coloredBlur"/>
        <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
      <filter id="softglow">
        <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
        <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
      <filter id="nameglow">
        <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
        <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
    </defs>
    <!-- Background -->
    <rect width="900" height="280" fill="url(#bg)"/>
    <!-- Scanning line that sweeps top to bottom -->
    <rect x="0" y="0" width="900" height="60" fill="url(#scanGrad)">
      <animateTransform attributeName="transform" type="translate" from="0,-60" to="0,280" dur="5s" repeatCount="indefinite"/>
    </rect>
    <!-- Perspective grid lines - horizontal, fade in -->
    <g stroke="url(#gridFade)" stroke-width="0.8">
      <line x1="0" y1="160" x2="900" y2="160" opacity="0">
        <animate attributeName="opacity" values="0;0.18" dur="1.2s" begin="0.3s" fill="freeze"/>
      </line>
      <line x1="0" y1="185" x2="900" y2="185" opacity="0">
        <animate attributeName="opacity" values="0;0.18" dur="1.2s" begin="0.5s" fill="freeze"/>
      </line>
      <line x1="0" y1="210" x2="900" y2="210" opacity="0">
        <animate attributeName="opacity" values="0;0.18" dur="1.2s" begin="0.7s" fill="freeze"/>
      </line>
      <line x1="0" y1="235" x2="900" y2="235" opacity="0">
        <animate attributeName="opacity" values="0;0.18" dur="1.2s" begin="0.9s" fill="freeze"/>
      </line>
      <line x1="0" y1="260" x2="900" y2="260" opacity="0">
        <animate attributeName="opacity" values="0;0.18" dur="1.2s" begin="1.1s" fill="freeze"/>
      </line>
    </g>
    <!-- Perspective grid lines - converging vertical, fade in -->
    <g stroke="#1e5080" stroke-width="0.7">
      <line x1="450" y1="155" x2="0"   y2="280" opacity="0"><animate attributeName="opacity" values="0;0.12" dur="1s" begin="0.2s" fill="freeze"/></line>
      <line x1="450" y1="155" x2="100" y2="280" opacity="0"><animate attributeName="opacity" values="0;0.12" dur="1s" begin="0.3s" fill="freeze"/></line>
      <line x1="450" y1="155" x2="200" y2="280" opacity="0"><animate attributeName="opacity" values="0;0.12" dur="1s" begin="0.4s" fill="freeze"/></line>
      <line x1="450" y1="155" x2="300" y2="280" opacity="0"><animate attributeName="opacity" values="0;0.12" dur="1s" begin="0.5s" fill="freeze"/></line>
      <line x1="450" y1="155" x2="400" y2="280" opacity="0"><animate attributeName="opacity" values="0;0.12" dur="1s" begin="0.6s" fill="freeze"/></line>
      <line x1="450" y1="155" x2="500" y2="280" opacity="0"><animate attributeName="opacity" values="0;0.12" dur="1s" begin="0.6s" fill="freeze"/></line>
      <line x1="450" y1="155" x2="600" y2="280" opacity="0"><animate attributeName="opacity" values="0;0.12" dur="1s" begin="0.5s" fill="freeze"/></line>
      <line x1="450" y1="155" x2="700" y2="280" opacity="0"><animate attributeName="opacity" values="0;0.12" dur="1s" begin="0.4s" fill="freeze"/></line>
      <line x1="450" y1="155" x2="800" y2="280" opacity="0"><animate attributeName="opacity" values="0;0.12" dur="1s" begin="0.3s" fill="freeze"/></line>
      <line x1="450" y1="155" x2="900" y2="280" opacity="0"><animate attributeName="opacity" values="0;0.12" dur="1s" begin="0.2s" fill="freeze"/></line>
    </g>
    <!-- Twinkling stars -->
    <g fill="#ffffff">
      <circle cx="42"  cy="22"  r="1">  <animate attributeName="opacity" values="0.6;0.1;0.8;0.3;0.6"  dur="3.1s" repeatCount="indefinite"/></circle>
      <circle cx="130" cy="55"  r="0.8"><animate attributeName="opacity" values="0.4;0.9;0.2;0.5;0.4"  dur="4.7s" repeatCount="indefinite"/></circle>
      <circle cx="780" cy="18"  r="1.2"><animate attributeName="opacity" values="0.7;0.2;0.9;0.4;0.7"  dur="2.9s" repeatCount="indefinite"/></circle>
      <circle cx="860" cy="60"  r="0.8"><animate attributeName="opacity" values="0.4;0.8;0.1;0.6;0.4"  dur="5.3s" repeatCount="indefinite"/></circle>
      <circle cx="670" cy="30"  r="1">  <animate attributeName="opacity" values="0.5;0.1;0.7;0.3;0.5"  dur="3.8s" repeatCount="indefinite"/></circle>
      <circle cx="310" cy="40"  r="0.7"><animate attributeName="opacity" values="0.4;0.9;0.3;0.7;0.4"  dur="6.1s" repeatCount="indefinite"/></circle>
      <circle cx="520" cy="15"  r="1">  <animate attributeName="opacity" values="0.6;0.2;0.8;0.1;0.6"  dur="4.2s" repeatCount="indefinite"/></circle>
      <circle cx="200" cy="70"  r="0.6"><animate attributeName="opacity" values="0.3;0.7;0.1;0.5;0.3"  dur="5.6s" repeatCount="indefinite"/></circle>
      <circle cx="820" cy="90"  r="0.9"><animate attributeName="opacity" values="0.5;0.1;0.8;0.3;0.5"  dur="3.4s" repeatCount="indefinite"/></circle>
      <circle cx="70"  cy="110" r="0.7"><animate attributeName="opacity" values="0.3;0.8;0.2;0.6;0.3"  dur="4.9s" repeatCount="indefinite"/></circle>
      <circle cx="740" cy="75"  r="1.1"><animate attributeName="opacity" values="0.6;0.2;0.9;0.4;0.6"  dur="3.7s" repeatCount="indefinite"/></circle>
      <circle cx="380" cy="25"  r="0.8"><animate attributeName="opacity" values="0.5;0.1;0.7;0.2;0.5"  dur="5.0s" repeatCount="indefinite"/></circle>
    </g>
    <!-- Bracket { — slides in from left -->
    <text font-family="monospace" font-size="72" fill="#1a4a7a" font-weight="bold" opacity="0">
      <animate attributeName="opacity" values="0;0.35" dur="0.6s" begin="0.8s" fill="freeze"/>
      <animateTransform attributeName="transform" type="translate" from="-40,0" to="0,0" dur="0.6s" begin="0.8s" fill="freeze"/>
      <tspan x="52" y="148">{</tspan>
    </text>
    <!-- Bracket } — slides in from right -->
    <text font-family="monospace" font-size="72" fill="#1a4a7a" font-weight="bold" opacity="0">
      <animate attributeName="opacity" values="0;0.35" dur="0.6s" begin="0.8s" fill="freeze"/>
      <animateTransform attributeName="transform" type="translate" from="40,0" to="0,0" dur="0.6s" begin="0.8s" fill="freeze"/>
      <tspan x="820" y="148">}</tspan>
    </text>
    <!-- Rule above name — expands from center -->
    <line x1="450" y1="88" x2="450" y2="88" stroke="#1e5f99" stroke-width="0.8" opacity="0.6">
      <animate attributeName="x1" values="450;200" dur="0.7s" begin="1.0s" fill="freeze"/>
      <animate attributeName="x2" values="450;700" dur="0.7s" begin="1.0s" fill="freeze"/>
    </line>
    <!-- Label above name — fades in -->
    <text x="450" y="82" font-family="monospace" font-size="10" fill="#4a90c4" text-anchor="middle" letter-spacing="4" opacity="0">
      <animate attributeName="opacity" values="0;0.8" dur="0.8s" begin="1.1s" fill="freeze"/>
      // FULL-STACK · MOBILE · SYSTEMS
    </text>
    <!-- Main name — fades + rises in, then pulses glow -->
    <text x="450" y="148" font-family="Georgia, serif" font-size="54" fill="url(#nameGrad)" text-anchor="middle" font-weight="bold" filter="url(#nameglow)" letter-spacing="2" opacity="0">
      <animate attributeName="opacity" values="0;1" dur="1s" begin="1.3s" fill="freeze"/>
      <animateTransform attributeName="transform" type="translate" from="0,12" to="0,0" dur="1s" begin="1.3s" fill="freeze"/>
      Rey Cezar Tigley
    </text>
    <!-- Rule below name — expands from center -->
    <line x1="450" y1="162" x2="450" y2="162" stroke="#1e5f99" stroke-width="0.8" opacity="0.6">
      <animate attributeName="x1" values="450;200" dur="0.7s" begin="1.6s" fill="freeze"/>
      <animate attributeName="x2" values="450;700" dur="0.7s" begin="1.6s" fill="freeze"/>
    </line>
    <!-- Subtitle — fades in -->
    <text x="450" y="192" font-family="monospace" font-size="13.5" fill="#64b5f6" text-anchor="middle" letter-spacing="1" opacity="0">
      <animate attributeName="opacity" values="0;0.9" dur="0.8s" begin="1.9s" fill="freeze"/>
      Flutter  ·  Next.js  ·  Supabase  ·  Firebase  ·  TypeScript
    </text>
    <!-- Tagline — fades in -->
    <text x="450" y="222" font-family="Georgia, serif" font-size="12" fill="#7bafd4" text-anchor="middle" font-style="italic" opacity="0">
      <animate attributeName="opacity" values="0;0.75" dur="0.8s" begin="2.2s" fill="freeze"/>
      Building scalable systems with purpose — Iligan City, PH
    </text>
    <!-- Bottom full rule -->
    <line x1="0" y1="270" x2="900" y2="270" stroke="#1e5f99" stroke-width="1.5" opacity="0.4" filter="url(#softglow)"/>
    <!-- Bottom center accent — expands and pulses -->
    <line x1="450" y1="270" x2="450" y2="270" stroke="#64b5f6" stroke-width="2" filter="url(#glow)">
      <animate attributeName="x1" values="450;320" dur="0.6s" begin="2.4s" fill="freeze"/>
      <animate attributeName="x2" values="450;580" dur="0.6s" begin="2.4s" fill="freeze"/>
      <animate attributeName="opacity" values="0.8;0.3;0.8" dur="3s" begin="3s" repeatCount="indefinite"/>
    </line>
    <!-- Corner TL — draws in -->
    <polyline points="18,42 18,18 42,18" fill="none" stroke="#2a6fa8" stroke-width="1.5" opacity="0"
      stroke-dasharray="50" stroke-dashoffset="50">
      <animate attributeName="stroke-dashoffset" values="50;0" dur="0.5s" begin="0.4s" fill="freeze"/>
      <animate attributeName="opacity" values="0;0.6" dur="0.1s" begin="0.4s" fill="freeze"/>
    </polyline>
    <!-- Corner TR — draws in -->
    <polyline points="858,18 882,18 882,42" fill="none" stroke="#2a6fa8" stroke-width="1.5" opacity="0"
      stroke-dasharray="50" stroke-dashoffset="50">
      <animate attributeName="stroke-dashoffset" values="50;0" dur="0.5s" begin="0.5s" fill="freeze"/>
      <animate attributeName="opacity" values="0;0.6" dur="0.1s" begin="0.5s" fill="freeze"/>
    </polyline>
    <!-- Corner BL — draws in -->
    <polyline points="18,238 18,262 42,262" fill="none" stroke="#2a6fa8" stroke-width="1.5" opacity="0"
      stroke-dasharray="50" stroke-dashoffset="50">
      <animate attributeName="stroke-dashoffset" values="50;0" dur="0.5s" begin="0.6s" fill="freeze"/>
      <animate attributeName="opacity" values="0;0.6" dur="0.1s" begin="0.6s" fill="freeze"/>
    </polyline>
    <!-- Corner BR — draws in -->
    <polyline points="858,262 882,262 882,238" fill="none" stroke="#2a6fa8" stroke-width="1.5" opacity="0"
      stroke-dasharray="50" stroke-dashoffset="50">
      <animate attributeName="stroke-dashoffset" values="50;0" dur="0.5s" begin="0.7s" fill="freeze"/>
      <animate attributeName="opacity" values="0;0.6" dur="0.1s" begin="0.7s" fill="freeze"/>
    </polyline>
  </svg>
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

---

## 🔨 Currently Building

| Project | Status | What I'm working on |
|---|---|---|
| 🗺️ **TourEase** | 🟡 In Progress | Interactive map, geospatial routing & destination UI for Iligan City |
| 🛺 **TriGoRide** | 🟡 In Progress | Ride-hailing MVP — driver matching & booking flow |

---

## 🎧 Now Playing

<p align="center">
  <a href="https://spotify-github-profile.kittinan.dev/redirect?uid=YOUR_SPOTIFY_UID">
    <img src="https://spotify-github-profile.kittinan.dev/api?uid=YOUR_SPOTIFY_UID&cover_image=true&theme=novatorem&show_offline=false&background_color=0d1117&interchange=false&bar_color=64b5f6&bar_color_cover=true" alt="Spotify Now Playing" />
  </a>
</p>

> ⚙️ **To activate:** Visit [spotify-github-profile.kittinan.dev](https://spotify-github-profile.kittinan.dev), log in with Spotify, copy your UID, and replace both instances of `YOUR_SPOTIFY_UID` above with it.

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
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 80" width="900" height="80">
    <defs>
      <linearGradient id="footerBg" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#050d1a"/>
        <stop offset="50%" style="stop-color:#091628"/>
        <stop offset="100%" style="stop-color:#050d1a"/>
      </linearGradient>
      <filter id="fglow">
        <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
        <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
    </defs>
    <rect width="900" height="80" fill="url(#footerBg)"/>
    <!-- Top accent -->
    <line x1="0" y1="1" x2="900" y2="1" stroke="#1e5f99" stroke-width="1" opacity="0.35"/>
    <line x1="310" y1="1" x2="590" y2="1" stroke="#64b5f6" stroke-width="2" opacity="0.7" filter="url(#fglow)"/>
    <!-- Corner marks -->
    <polyline points="18,14 18,32 36,32" fill="none" stroke="#2a6fa8" stroke-width="1.2" opacity="0.5"/>
    <polyline points="882,14 882,32 864,32" fill="none" stroke="#2a6fa8" stroke-width="1.2" opacity="0.5"/>
    <!-- Tagline -->
    <text x="450" y="38" font-family="monospace" font-size="10" fill="#4a90c4" text-anchor="middle" letter-spacing="3" opacity="0.7">// BUILT WITH PURPOSE · ILIGAN CITY, PH</text>
    <text x="450" y="58" font-family="Georgia, serif" font-size="11" fill="#3a7ab8" text-anchor="middle" font-style="italic" opacity="0.5">Rey Cezar Tigley · github.com/Zaimoo</text>
  </svg>
</p>
