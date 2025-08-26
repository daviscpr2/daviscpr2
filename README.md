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
      <stop
