<div align="center">

<!-- Header 3D com glassmorphism -->
<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="glass" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#2563EB;stop-opacity:0.1"/>
      <stop offset="50%" style="stop-color:#1E40AF;stop-opacity:0.05"/>
      <stop offset="100%" style="stop-color:#1D4ED8;stop-opacity:0.1"/>
    </linearGradient>
    <filter id="blur" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur in="SourceGraphic" stdDeviation="3"/>
    </filter>
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Glass background with 3D effect -->
  <rect width="760" height="160" x="20" y="20" rx="20" fill="url(#glass)" 
        stroke="rgba(37, 99, 235, 0.2)" stroke-width="1" filter="url(#blur)"/>
  <rect width="760" height="160" x="20" y="20" rx="20" fill="none" 
        stroke="rgba(37, 99, 235, 0.3)" stroke-width="2"/>
  
  <!-- 3D Floating particles -->
  <circle r="4" fill="#2563EB" opacity="0.6" filter="url(#glow)">
    <animateMotion dur="15s" repeatCount="indefinite">
      <path d="M50,50 C200,30 300,150 450,100 C600,50 700,120 750,80 C700,40 500,160 300,120 C100,80 50,50 50,50"/>
    </animateMotion>
    <animate attributeName="r" values="4;8;4" dur="3s" repeatCount="indefinite"/>
  </circle>
  
  <circle r="3" fill="#1E40AF" opacity="0.8" filter="url(#glow)">
    <animateMotion dur="12s" repeatCount="indefinite">
      <path d="M100,120 C250,140 400,60 550,110 C700,160 650,90 480,70 C300,50 150,90 100,120"/>
    </animateMotion>
    <animate attributeName="opacity" values="0.8;0.3;0.8" dur="4s" repeatCount="indefinite"/>
  </circle>
  
  <circle r="2" fill="#3B82F6" opacity="0.4" filter="url(#glow)">
    <animateMotion dur="18s" repeatCount="indefinite">
      <path d="M750,140 C600,120 400,80 250,130 C100,180 150,100 350,90 C550,80 700,110 750,140"/>
    </animateMotion>
  </circle>
  
  <!-- Main text with 3D shadow effect -->
  <text x="400" y="90" text-anchor="middle" 
        font-family="Inter, -apple-system, BlinkMacSystemFont, sans-serif" 
        font-size="32" font-weight="700" fill="#1F2937" opacity="0.1"
        transform="translate(2,2)">Davi Santiago</text>
  <text x="400" y="90" text-anchor="middle" 
        font-family="Inter, -apple-system, BlinkMacSystemFont, sans-serif" 
        font-size="32" font-weight="700" fill="#FFFFFF" filter="url(#glow)">
    Davi Santiago
    <animate attributeName="fill" values="#FFFFFF;#E5E7EB;#FFFFFF" dur="3s" repeatCount="indefinite"/>
  </text>
  
  <!-- Subtitle with typing effect simulation -->
  <text x="400" y="125" text-anchor="middle" 
        font-family="JetBrains Mono, monospace" 
        font-size="16" font-weight="500" fill="#2563EB" opacity="0.9">
    🔬 Python • IA • Automação
    <animate attributeName="opacity" values="0.9;0.4;0.9" dur="2s" repeatCount="indefinite"/>
  </text>
  
  <text x="400" y="150" text-anchor="middle" 
        font-family="JetBrains Mono, monospace" 
        font-size="14" font-weight="400" fill="#6B7280">
    💡 Criando soluções para problemas reais
  </text>
</svg>

</div>

---

## **🚀 Sobre mim**

<table width="100%">
<tr>
<td width="60%">

🔬 **Estudante de Python, IA e Automação**  
💡 **Criando soluções para problemas reais**  
📌 **Sempre aprendendo, sempre construindo**

- 🎓 Estudante na **Cesar School**
- 📍 **Recife, PE - Brasil**
- 🌐 Portfolio: **[portfolio-davi-santiago.vercel.app](https://portfolio-davi-santiago.vercel.app)**
- 📚 **A maior parte dos meus projetos está no meu usuário da Cesar School:** **[DaviSantiago01](https://github.com/DaviSantiago01)**

</td>
<td width="40%" align="center">

<!-- 3D Cube Animation -->
<svg width="120" height="120" viewBox="0 0 120 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="face1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#2563EB"/>
      <stop offset="100%" style="stop-color:#1E40AF"/>
    </linearGradient>
    <linearGradient id="face2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1E40AF"/>
      <stop offset="100%" style="stop-color:#1D4ED8"/>
    </linearGradient>
    <linearGradient id="face3" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1D4ED8"/>
      <stop offset="100%" style="stop-color:#2563EB"/>
    </linearGradient>
  </defs>
  
  <g transform="translate(60,60)">
    <!-- Cube faces with 3D effect -->
    <polygon points="-25,-25 25,-25 25,25 -25,25" fill="url(#face1)" stroke="#FFFFFF" stroke-width="1" opacity="0.9">
      <animateTransform attributeName="transform" type="rotate" values="0;360" dur="10s" repeatCount="indefinite"/>
    </polygon>
    <polygon points="25,-25 40,-40 40,10 25,25" fill="url(#face2)" stroke="#FFFFFF" stroke-width="1" opacity="0.7">
      <animateTransform attributeName="transform" type="rotate" values="0;360" dur="10s" repeatCount="indefinite"/>
    </polygon>
    <polygon points="-25,-25 -10,-40 40,-40 25,-25" fill="url(#face3)" stroke="#FFFFFF" stroke-width="1" opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" values="0;360" dur="10s" repeatCount="indefinite"/>
    </polygon>
  </g>
</svg>

</td>
</tr>
</table>

---

## **🛠️ Tech Stack**

<div align="center">

<!-- 3D Tech Icons com hover effect -->
<svg width="400" height="100" viewBox="0 0 400 100" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="shadow" x="-50%" y="-50%" width="200%" height="200%">
      <feDropShadow dx="3" dy="6" stdDeviation="3" flood-color="#000000" flood-opacity="0.3"/>
    </filter>
    <linearGradient id="iconBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#F8FAFC"/>
      <stop offset="100%" style="stop-color:#E2E8F0"/>
    </linearGradient>
  </defs>
  
  <!-- Python -->
  <g transform="translate(50, 50)">
    <circle r="25" fill="url(#iconBg)" stroke="#2563EB" stroke-width="2" filter="url(#shadow)">
      <animate attributeName="r" values="25;28;25" dur="3s" repeatCount="indefinite"/>
    </circle>
    <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" 
           x="-15" y="-15" width="30" height="30">
      <animateTransform attributeName="transform" type="rotate" values="0 0 0;360 0 0" dur="8s" repeatCount="indefinite"/>
    </image>
  </g>
  
  <!-- TensorFlow -->
  <g transform="translate(150, 50)">
    <circle r="25" fill="url(#iconBg)" stroke="#2563EB" stroke-width="2" filter="url(#shadow)">
      <animate attributeName="r" values="25;28;25" dur="4s" repeatCount="indefinite"/>
    </circle>
    <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" 
           x="-15" y="-15" width="30" height="30">
      <animateTransform attributeName="transform" type="scale" values="1;1.2;1" dur="3s" repeatCount="indefinite"/>
    </image>
  </g>
  
  <!-- Git -->
  <g transform="translate(250, 50)">
    <circle r="25" fill="url(#iconBg)" stroke="#2563EB" stroke-width="2" filter="url(#shadow)">
      <animate attributeName="r" values="25;28;25" dur="5s" repeatCount="indefinite"/>
    </circle>
    <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" 
           x="-15" y="-15" width="30" height="30">
      <animateTransform attributeName="transform" type="rotate" values="0 0 0;-360 0 0" dur="12s" repeatCount="indefinite"/>
    </image>
  </g>
  
  <!-- VS Code -->
  <g transform="translate(350, 50)">
    <circle r="25" fill="url(#iconBg)" stroke="#2563EB" stroke-width="2" filter="url(#shadow)">
      <animate attributeName="r" values="25;28;25" dur="6s" repeatCount="indefinite"/>
    </circle>
    <image href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" 
           x="-15" y="-15" width="30" height="30">
      <animateTransform attributeName="transform" type="rotate" values="0 0 0;360 0 0" dur="15s" repeatCount="indefinite"/>
    </image>
  </g>
</svg>

</div>

---

## **📊 GitHub Stats**

<div align="center">

<!-- Stats com glassmorphism background -->
<svg width="100%" height="40" viewBox="0 0 600 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="statsBg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#2563EB;stop-opacity:0.1"/>
      <stop offset="50%" style="stop-color:#1E40AF;stop-opacity:0.05"/>
      <stop offset="100%" style="stop-color:#2563EB;stop-opacity:0.1"/>
    </linearGradient>
  </defs>
  <rect width="100%" height="40" rx="20" fill="url(#statsBg)" stroke="rgba(37, 99, 235, 0.2)" stroke-width="1"/>
  <text x="50%" y="50%" text-anchor="middle" dominant-baseline="middle" 
        font-family="Inter, sans-serif" font-size="16" font-weight="600" fill="#2563EB">
    📊 GitHub Analytics
  </text>
</svg>

<br><br>

<picture>
  <source 
    srcset="https://github-readme-stats.vercel.app/api?username=daviscpr2&show_icons=true&theme=dark&bg_color=0d1117&text_color=e6edf3&icon_color=2563eb&title_color=f0f6fc&border_color=30363d&hide_border=true&border_radius=15&custom_title=GitHub+Stats"
    media="(prefers-color-scheme: dark)"
  />
  <img 
    src="https://github-readme-stats.vercel.app/api?username=daviscpr2&show_icons=true&theme=default&bg_color=ffffff&text_color=24292f&icon_color=2563eb&title_color=24292f&border_color=d1d9e0&hide_border=true&border_radius=15&custom_title=GitHub+Stats"
    alt="GitHub Stats"
  />
</picture>

<br><br>

<picture>
  <source 
    srcset="https://github-readme-streak-stats.herokuapp.com?user=daviscpr2&theme=dark&background=0d1117&border=30363d&stroke=e6edf3&ring=2563eb&fire=58a6ff&currStreakNum=f0f6fc&sideNums=e6edf3&currStreakLabel=7d8590&sideLabels=7d8590&dates=7d8590&hide_border=true&border_radius=15"
    media="(prefers-color-scheme: dark)"
  />
  <img 
    src="https://github-readme-streak-stats.herokuapp.com?user=daviscpr2&theme=default&background=ffffff&border=d1d9e0&stroke=24292f&ring=2563eb&fire=f56565&currStreakNum=24292f&sideNums=656d76&currStreakLabel=656d76&sideLabels=656d76&dates=656d76&hide_border=true&border_radius=15"
    alt="GitHub Streak"
  />
</picture>

<br><br>

<picture>
  <source 
    srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=daviscpr2&layout=compact&theme=dark&bg_color=0d1117&text_color=e6edf3&title_color=f0f6fc&border_color=30363d&hide_border=true&border_radius=15&langs_count=6"
    media="(prefers-color-scheme: dark)"
  />
  <img 
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=daviscpr2&layout=compact&theme=default&bg_color=ffffff&text_color=24292f&title_color=24292f&border_color=d1d9e0&hide_border=true&border_radius=15&langs_count=6"
    alt="Top Languages"
  />
</picture>

</div>

---

## **🎯 Projetos em Destaque**

<div align="center">

<picture>
  <source 
    srcset="https://github-readme-stats.vercel.app/api/pin/?username=daviscpr2&repo=Organizador-De-Arquivos-Py&theme=dark&bg_color=0d1117&text_color=e6edf3&icon_color=2563eb&title_color=f0f6fc&border_color=30363d&hide_border=true&border_radius=15"
    media="(prefers-color-scheme: dark)"
  />
  <img 
    src="https://github-readme-stats.vercel.app/api/pin/?username=daviscpr2&repo=Organizador-De-Arquivos-Py&theme=default&bg_color=ffffff&text_color=24292f&icon_color=2563eb&title_color=24292f&border_color=d1d9e0&hide_border=true&border_radius=15"
    alt="Organizador de Arquivos"
  />
</picture>

</div>

---

## **🔗 Conecte-se comigo**

<div align="center">

<!-- Connection buttons with 3D effect -->
<svg width="400" height="80" viewBox="0 0 400 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="btnGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#3B82F6"/>
      <stop offset="100%" style="stop-color:#2563EB"/>
    </linearGradient>
    <filter id="btnShadow">
      <feDropShadow dx="2" dy="4" stdDeviation="2" flood-color="#000000" flood-opacity="0.25"/>
    </filter>
  </defs>
  
  <rect x="50" y="20" width="80" height="30" rx="15" fill="url(#btnGrad)" filter="url(#btnShadow)">
    <animate attributeName="y" values="20;18;20" dur="3s" repeatCount="indefinite"/>
  </rect>
  <text x="90" y="38" text-anchor="middle" font-family="Inter, sans-serif" font-size="12" font-weight="600" fill="white">Portfolio</text>
  
  <rect x="160" y="20" width="80" height="30" rx="15" fill="url(#btnGrad)" filter="url(#btnShadow)">
    <animate attributeName="y" values="20;18;20" dur="4s" repeatCount="indefinite"/>
  </rect>
  <text x="200" y="38" text-anchor="middle" font-family="Inter, sans-serif" font-size="12" font-weight="600" fill="white">LinkedIn</text>
  
  <rect x="270" y="20" width="80" height="30" rx="15" fill="url(#btnGrad)" filter="url(#btnShadow)">
    <animate attributeName="y" values="20;18;20" dur="5s" repeatCount="indefinite"/>
  </rect>
  <text x="310" y="38" text-anchor="middle" font-family="Inter, sans-serif" font-size="12" font-weight="600" fill="white">Email</text>
</svg>

<br>

<a href="https://portfolio-davi-santiago.vercel.app">
<img src="https://img.shields.io/badge/🌐_Portfolio-2563EB?style=for-the-badge&logo=vercel&logoColor=white&labelColor=000000" alt="Portfolio"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/davi-santiago-a94284334">
<img src="https://img.shields.io/badge/💼_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=000000" alt="LinkedIn"/>
</a>
&nbsp;
<a href="mailto:daviscpr2@email.com">
<img src="https://img.shields.io/badge/📧_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000000" alt="Email"/>
</a>

<br><br>

<a href="https://github.com/DaviSantiago01">
<img src="https://img.shields.io/badge/📚_Academic_Profile-1F2937?style=for-the-badge&logo=github&logoColor=white&labelColor=2563EB" alt="Academic Profile"/>
</a>

</div>

---

<div align="center">

<!-- Footer with wave animation -->
<svg width="100%" height="60" viewBox="0 0 400 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="wave" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#2563EB;stop-opacity:0.3"/>
      <stop offset="50%" style="stop-color:#1E40AF;stop-opacity:0.1"/>
      <stop offset="100%" style="stop-color:#2563EB;stop-opacity:0.3"/>
    </linearGradient>
  </defs>
  
  <path d="M0,30 Q100,10 200,30 T400,30 V60 H0 V30" fill="url(#wave)">
    <animateTransform attributeName="transform" type="translate" values="-400 0;0 0;-400 0" dur="8s" repeatCount="indefinite"/>
  </path>
</svg>

<img src="https://komarev.com/ghpvc/?username=daviscpr2&color=2563eb&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views"/>

</div>
