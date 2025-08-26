<div align="center">

<!-- Header animado com glassmorphism -->
<svg width="100%" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#764ba2;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f093fb;stop-opacity:1" />
    </linearGradient>
    <filter id="blur">
      <feGaussianBlur in="SourceGraphic" stdDeviation="3"/>
    </filter>
  </defs>
  
  <!-- Background glass effect -->
  <rect width="100%" height="100%" rx="20" fill="url(#grad1)" opacity="0.1" filter="url(#blur)"/>
  <rect width="100%" height="100%" rx="20" fill="none" stroke="url(#grad1)" stroke-width="2" opacity="0.3"/>
  
  <!-- Animated particles -->
  <circle r="3" fill="#58A6FF" opacity="0.6">
    <animateMotion dur="10s" repeatCount="indefinite">
      <path d="M 50,50 Q 150,50 250,150 T 450,150"/>
    </animateMotion>
  </circle>
  
  <circle r="2" fill="#764ba2" opacity="0.8">
    <animateMotion dur="8s" repeatCount="indefinite">
      <path d="M 100,150 Q 200,50 400,100 T 600,50"/>
    </animateMotion>
  </circle>
  
  <circle r="4" fill="#f093fb" opacity="0.4">
    <animateMotion dur="12s" repeatCount="indefinite">
      <path d="M 200,100 Q 300,150 500,80 T 700,120"/>
    </animateMotion>
  </circle>
  
  <!-- Main text -->
  <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" 
        font-family="SF Pro Display, -apple-system, system-ui" font-size="28" font-weight="600" fill="#E6EDF3">
    Davi Santiago
  </text>
  
  <text x="50%" y="65%" dominant-baseline="middle" text-anchor="middle" 
        font-family="SF Mono, Monaco, monospace" font-size="14" fill="#58A6FF" opacity="0.8">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="3s" repeatCount="indefinite"/>
    🔬 Python • IA • Automação
  </text>
  
  <text x="50%" y="78%" dominant-baseline="middle" text-anchor="middle" 
        font-family="SF Mono, Monaco, monospace" font-size="12" fill="#7C3AED" opacity="0.7">
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="4s" repeatCount="indefinite"/>
    💡 Building solutions for real problems
  </text>
</svg>

<br>

<!-- Status cards com hover effect -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/🎓-Cesar_School-4A90E2?style=for-the-badge&labelColor=0D1117&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyIDNMMjEgN1Y5SDNWN0wxMiAzWiIgZmlsbD0iIzU4QTZGRIILZ2yaDiAhcGF0aD0iTTMgMTlWMTFIMTlWMTlIM1oiIGZpbGw9IiM1OEE2RkYiLz4KPC9zdmc+"/>
  <img src="https://img.shields.io/badge/🎓-Cesar_School-4A90E2?style=for-the-badge&labelColor=f8f9fa&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyIDNMMjEgN1Y5SDNWN0wxMiAzWiIgZmlsbD0iIzU4QTZGRIILZ2yaDiAhcGF0aD0iTTMgMTlWMTFIMTlWMTlIM1oiIGZpbGw9IiM1OEE2RkYiLz4KPC9zdmc+" alt="School"/>
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/📍-Recife,_PE-FF6B6B?style=for-the-badge&labelColor=0D1117"/>
  <img src="https://img.shields.io/badge/📍-Recife,_PE-FF6B6B?style=for-the-badge&labelColor=f8f9fa" alt="Location"/>
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/🌐-Live_Portfolio-4ECDC4?style=for-the-badge&labelColor=0D1117"/>
  <img src="https://img.shields.io/badge/🌐-Live_Portfolio-4ECDC4?style=for-the-badge&labelColor=f8f9fa" alt="Portfolio"/>
</picture>

</div>

---

<div align="center">

<!-- Tech stack com animações CSS inline -->
<svg width="100%" height="120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      .tech-icon { 
        transition: all 0.3s ease;
        cursor: pointer;
      }
      .tech-icon:hover { 
        transform: translateY(-5px) scale(1.1);
        filter: drop-shadow(0 10px 20px rgba(88, 166, 255, 0.3));
      }
      .tech-text {
        font-family: 'SF Pro Display', -apple-system, system-ui;
        font-size: 12px;
        font-weight: 500;
      }
      .glow {
        animation: glow 2s ease-in-out infinite alternate;
      }
      @keyframes glow {
        from { filter: drop-shadow(0 0 5px rgba(88, 166, 255, 0.5)); }
        to { filter: drop-shadow(0 0 20px rgba(88, 166, 255, 0.8)); }
      }
    </style>
  </defs>
  
  <!-- Python -->
  <g class="tech-icon" transform="translate(80, 20)">
    <circle r="25" fill="#3776AB" opacity="0.1" class="glow"/>
    <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" x="-15" y="-15" width="30" height="30"/>
    <text x="0" y="45" text-anchor="middle" fill="#E6EDF3" class="tech-text">Python</text>
  </g>
  
  <!-- AI/ML -->
  <g class="tech-icon" transform="translate(250, 20)">
    <circle r="25" fill="#FF6F00" opacity="0.1" class="glow"/>
    <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" x="-15" y="-15" width="30" height="30"/>
    <text x="0" y="45" text-anchor="middle" fill="#E6EDF3" class="tech-text">AI & ML</text>
  </g>
  
  <!-- Automation -->
  <g class="tech-icon" transform="translate(420, 20)">
    <circle r="25" fill="#2E8B57" opacity="0.1" class="glow"/>
    <path d="M-10,-10 L10,-10 L10,10 L-10,10 Z" fill="#2E8B57"/>
    <path d="M-5,-5 L0,0 L-5,5 M0,0 L5,0" stroke="#fff" stroke-width="2" fill="none"/>
    <text x="0" y="45" text-anchor="middle" fill="#E6EDF3" class="tech-text">Automation</text>
  </g>
  
  <!-- Git -->
  <g class="tech-icon" transform="translate(590, 20)">
    <circle r="25" fill="#F05032" opacity="0.1" class="glow"/>
    <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" x="-15" y="-15" width="30" height="30"/>
    <text x="0" y="45" text-anchor="middle" fill="#E6EDF3" class="tech-text">Git</text>
  </g>
</svg>

</div>

---

<!-- Stats section com layout moderno -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=daviscpr2&show_icons=true&theme=tokyonight&hide_border=true&border_radius=20&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9&ring_color=58A6FF&custom_title=📊%20GitHub%20Analytics"/>
  <img src="https://github-readme-stats.vercel.app/api?username=daviscpr2&show_icons=true&theme=default&hide_border=true&border_radius=20&bg_color=ffffff&title_color=2d3748&icon_color=4A90E2&text_color=4a5568&ring_color=4A90E2&custom_title=📊%20GitHub%20Analytics" alt="GitHub Stats"/>
</picture>

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com?user=daviscpr2&theme=tokyonight&hide_border=true&border_radius=20&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF&dates=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&sideLabels=C9D1D9"/>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=daviscpr2&theme=default&hide_border=true&border_radius=20&background=ffffff&ring=4A90E2&fire=FF6B6B&currStreakLabel=2d3748&dates=4a5568&currStreakNum=2d3748&sideNums=4a5568&sideLabels=4a5568" alt="GitHub Streak"/>
</picture>

</div>

---

<!-- Project showcase com efeito 3D -->
<div align="center">

<svg width="100%" height="40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#667eea"/>
      <stop offset="50%" style="stop-color:#764ba2"/>  
      <stop offset="100%" style="stop-color:#f093fb"/>
    </linearGradient>
  </defs>
  <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" 
        font-family="SF Pro Display, -apple-system" font-size="20" font-weight="700" 
        fill="url(#titleGrad)">
    🎯 Featured Work
  </text>
</svg>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=daviscpr2&repo=Organizador-De-Arquivos-Py&theme=tokyonight&hide_border=true&border_radius=20&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&icon_color=58A6FF"/>
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=daviscpr2&repo=Organizador-De-Arquivos-Py&theme=default&hide_border=true&border_radius=20&bg_color=ffffff&title_color=2d3748&text_color=4a5568&icon_color=4A90E2" alt="Featured Project"/>
</picture>

</div>

---

<!-- Connect section com glassmorphism -->
<div align="center">

<svg width="100%" height="80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="glass">
      <feGaussianBlur in="SourceGraphic" stdDeviation="2"/>
      <feOffset dx="2" dy="2" result="offset"/>
    </filter>
  </defs>
  
  <rect x="20%" y="10" width="60%" height="60" rx="15" 
        fill="rgba(88, 166, 255, 0.1)" stroke="rgba(88, 166, 255, 0.3)" 
        stroke-width="1" filter="url(#glass)"/>
        
  <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" 
        font-family="SF Pro Display, -apple-system" font-size="16" font-weight="600" fill="#58A6FF">
    🔗 Let's Connect
  </text>
</svg>

<a href="https://portfolio-davi-santiago.vercel.app">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/🌐_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white&labelColor=58A6FF"/>
    <img src="https://img.shields.io/badge/🌐_Portfolio-4A90E2?style=for-the-badge&logo=vercel&logoColor=white&labelColor=000" alt="Portfolio"/>
  </picture>
</a>
&nbsp;
<a href="https://linkedin.com/in/davi-santiago-a94284334">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/💼_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=000"/>
    <img src="https://img.shields.io/badge/💼_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=000" alt="LinkedIn"/>
  </picture>
</a>
&nbsp;
<a href="mailto:daviscpr2@email.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/📧_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000"/>
    <img src="https://img.shields.io/badge/📧_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000" alt="Email"/>
  </picture>
</a>

<!-- Academic profile redirect -->
<br><br>
<a href="https://github.com/DaviSantiago01">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/📚_Academic_Work-764ba2?style=for-the-badge&logo=github&logoColor=white&labelColor=000"/>
    <img src="https://img.shields.io/badge/📚_Academic_Work-764ba2?style=for-the-badge&logo=github&logoColor=white&labelColor=000" alt="Academic Profile"/>
  </picture>
</a>

</div>

---

<!-- Footer com wave animation -->
<div align="center">

<svg width="100%" height="60" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
  <defs>
    <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:0.6"/>
      <stop offset="50%" style="stop-color:#764ba2;stop-opacity:0.4"/>  
      <stop offset="100%" style="stop-color:#f093fb;stop-opacity:0.6"/>
    </linearGradient>
  </defs>
  
  <path d="M0,60 Q300,0 600,60 T1200,60 V120 H0 V60" fill="url(#waveGrad)">
    <animateTransform attributeName="transform" type="translate" 
                      values="-1200 0;0 0;-1200 0" dur="20s" repeatCount="indefinite"/>
  </path>
  
  <path d="M0,80 Q300,20 600,80 T1200,80 V120 H0 V80" fill="url(#waveGrad)" opacity="0.5">
    <animateTransform attributeName="transform" type="translate" 
                      values="0 0;1200 0;0 0" dur="25s" repeatCount="indefinite"/>
  </path>
</svg>

![Profile Views](https://komarev.com/ghpvc/?username=daviscpr2&color=58A6FF&style=flat-square&label=views)

</div>
