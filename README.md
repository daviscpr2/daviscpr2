<div align="center">

<!-- SVG Custom com animações 3D e efeitos modernos -->
<svg width="800" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="modernGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#2563EB;stop-opacity:1" >
        <animate attributeName="stop-color" values="#2563EB;#7C3AED;#EC4899;#2563EB" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#1E293B;stop-opacity:1" />
    </linearGradient>
    
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge> 
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    
    <filter id="shadow3d">
      <feDropShadow dx="5" dy="5" stdDeviation="3" flood-color="#000" flood-opacity="0.3"/>
    </filter>
  </defs>
  
  <!-- Fundo com efeito de partículas -->
  <rect width="800" height="200" fill="url(#modernGradient)" rx="20"/>
  
  <!-- Partículas animadas -->
  <circle r="2" fill="#fff" opacity="0.8">
    <animate attributeName="cx" values="0;800;0" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="50;150;50" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle r="1.5" fill="#fff" opacity="0.6">
    <animate attributeName="cx" values="800;0;800" dur="10s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="80;120;80" dur="7s" repeatCount="indefinite"/>
  </circle>
  <circle r="3" fill="#fff" opacity="0.4">
    <animate attributeName="cx" values="400;600;400" dur="12s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="30;170;30" dur="8s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Texto principal com efeito 3D -->
  <text x="400" y="80" text-anchor="middle" fill="#fff" font-family="Inter, system-ui" font-size="48" font-weight="700" filter="url(#shadow3d)">
    Davi Santiago
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </text>
  
  <!-- Subtítulo com efeito de typing -->
  <text x="400" y="120" text-anchor="middle" fill="#E2E8F0" font-family="Inter, system-ui" font-size="20" font-weight="400">
    <tspan>
      Python • AI • Automation • Future
      <animate attributeName="fill" values="#E2E8F0;#60A5FA;#E2E8F0" dur="2s" repeatCount="indefinite"/>
    </tspan>
  </text>
  
  <!-- Linha decorativa animada -->
  <line x1="200" y1="150" x2="600" y2="150" stroke="#60A5FA" stroke-width="2" filter="url(#glow)">
    <animate attributeName="stroke-dasharray" values="0,400;400,400;400,0;0,400" dur="4s" repeatCount="indefinite"/>
  </line>
  
  <!-- Efeito de cubo 3D rotativo -->
  <g transform="translate(100, 50)">
    <polygon points="0,0 30,0 35,5 5,5" fill="#2563EB" opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" values="0;360" dur="8s" repeatCount="indefinite"/>
    </polygon>
    <polygon points="30,0 30,30 35,35 35,5" fill="#1E40AF" opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" values="0;360" dur="8s" repeatCount="indefinite"/>
    </polygon>
    <polygon points="0,0 0,30 30,30 30,0" fill="#3B82F6" opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" values="0;360" dur="8s" repeatCount="indefinite"/>
    </polygon>
  </g>
  
  <!-- Cubo 3D espelhado do outro lado -->
  <g transform="translate(670, 130)">
    <polygon points="0,0 30,0 35,5 5,5" fill="#7C3AED" opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" values="360;0" dur="10s" repeatCount="indefinite"/>
    </polygon>
    <polygon points="30,0 30,30 35,35 35,5" fill="#6D28D9" opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" values="360;0" dur="10s" repeatCount="indefinite"/>
    </polygon>
    <polygon points="0,0 0,30 30,30 30,0" fill="#8B5CF6" opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" values="360;0" dur="10s" repeatCount="indefinite"/>
    </polygon>
  </g>
</svg>

<!-- Divisor com efeito de onda responsiva -->
<svg width="100%" height="60" viewBox="0 0 800 60" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <defs>
    <linearGradient id="waveGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#2563EB;stop-opacity:0.8" />
      <stop offset="50%" style="stop-color:#7C3AED;stop-opacity:0.6" />
      <stop offset="100%" style="stop-color:#EC4899;stop-opacity:0.8" />
    </linearGradient>
  </defs>
  <path d="M0,30 Q200,10 400,30 T800,30 L800,60 L0,60 Z" fill="url(#waveGradient)">
    <animate attributeName="d" values="M0,30 Q200,10 400,30 T800,30 L800,60 L0,60 Z;M0,30 Q200,50 400,30 T800,30 L800,60 L0,60 Z;M0,30 Q200,10 400,30 T800,30 L800,60 L0,60 Z" dur="4s" repeatCount="indefinite"/>
  </path>
</svg>

</div>

---

## **🚀 Sobre mim**

<div align="center">

<!-- Card personalizado com efeitos CSS via SVG -->
<svg width="600" height="200" xmlns="http://www.w3.org/2000/svg">
  <foreignObject x="0" y="0" width="600" height="200">
    <div xmlns="http://www.w3.org/1999/xhtml" style="
      background: linear-gradient(135deg, #0F172A 0%, #1E293B 50%, #334155 100%);
      border-radius: 20px;
      padding: 30px;
      color: white;
      font-family: 'Inter', system-ui;
      box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
      border: 1px solid rgba(59, 130, 246, 0.3);
      position: relative;
      overflow: hidden;
    ">
      <!-- Efeito de brilho animado -->
      <div style="
        position: absolute;
        top: -50%;
        left: -50%;
        width: 200%;
        height: 200%;
        background: linear-gradient(45deg, transparent 30%, rgba(59, 130, 246, 0.1) 50%, transparent 70%);
        animation: shine 3s infinite;
        pointer-events: none;
      "></div>
      
      <div style="position: relative; z-index: 1;">
        <h3 style="margin: 0 0 15px 0; color: #60A5FA; font-size: 24px; font-weight: 700;">
          🔬 Estudante de Python, IA e Automação
        </h3>
        <p style="margin: 8px 0; font-size: 16px; color: #CBD5E1;">💡 Criando soluções para problemas reais</p>
        <p style="margin: 8px 0; font-size: 16px; color: #CBD5E1;">📌 Sempre aprendendo, sempre construindo</p>
        <div style="margin-top: 20px; display: flex; gap: 20px; justify-content: center; flex-wrap: wrap;">
          <span style="background: rgba(59, 130, 246, 0.2); padding: 8px 16px; border-radius: 25px; font-size: 14px; border: 1px solid #3B82F6;">🎓 Cesar School</span>
          <span style="background: rgba(124, 58, 237, 0.2); padding: 8px 16px; border-radius: 25px; font-size: 14px; border: 1px solid #7C3AED;">📍 Recife, PE</span>
        </div>
      </div>
    </div>
  </foreignObject>
</svg>

</div>

---

## **🛠️ Tech Stack Ultra-Moderna**

<div align="center">

<!-- Grid de tecnologias com efeitos hover 3D -->
<svg width="700" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="hover3d">
      <feDropShadow dx="0" dy="10" stdDeviation="5" flood-color="#2563EB" flood-opacity="0.4"/>
    </filter>
    <linearGradient id="techGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1E293B"/>
      <stop offset="100%" style="stop-color:#334155"/>
    </linearGradient>
  </defs>
  
  <!-- Python -->
  <g transform="translate(50, 50)">
    <rect width="80" height="80" rx="20" fill="url(#techGradient)" filter="url(#hover3d)" stroke="#3776AB" stroke-width="2">
      <animate attributeName="y" values="0;-5;0" dur="2s" repeatCount="indefinite" begin="0s"/>
    </rect>
    <text x="40" y="45" text-anchor="middle" fill="#3776AB" font-size="32" font-weight="bold">Py</text>
    <text x="40" y="105" text-anchor="middle" fill="#E2E8F0" font-size="12" font-family="Inter">Python</text>
  </g>
  
  <!-- TensorFlow -->
  <g transform="translate(200, 50)">
    <rect width="80" height="80" rx="20" fill="url(#techGradient)" filter="url(#hover3d)" stroke="#FF6F00" stroke-width="2">
      <animate attributeName="y" values="0;-5;0" dur="2s" repeatCount="indefinite" begin="0.5s"/>
    </rect>
    <text x="40" y="45" text-anchor="middle" fill="#FF6F00" font-size="32" font-weight="bold">TF</text>
    <text x="40" y="105" text-anchor="middle" fill="#E2E8F0" font-size="12" font-family="Inter">TensorFlow</text>
  </g>
  
  <!-- Git -->
  <g transform="translate(350, 50)">
    <rect width="80" height="80" rx="20" fill="url(#techGradient)" filter="url(#hover3d)" stroke="#F05032" stroke-width="2">
      <animate attributeName="y" values="0;-5;0" dur="2s" repeatCount="indefinite" begin="1s"/>
    </rect>
    <text x="40" y="45" text-anchor="middle" fill="#F05032" font-size="32" font-weight="bold">Git</text>
    <text x="40" y="105" text-anchor="middle" fill="#E2E8F0" font-size="12" font-family="Inter">Git</text>
  </g>
  
  <!-- VS Code -->
  <g transform="translate(500, 50)">
    <rect width="80" height="80" rx="20" fill="url(#techGradient)" filter="url(#hover3d)" stroke="#007ACC" stroke-width="2">
      <animate attributeName="y" values="0;-5;0" dur="2s" repeatCount="indefinite" begin="1.5s"/>
    </rect>
    <text x="40" y="45" text-anchor="middle" fill="#007ACC" font-size="28" font-weight="bold">VS</text>
    <text x="40" y="105" text-anchor="middle" fill="#E2E8F0" font-size="12" font-family="Inter">VS Code</text>
  </g>
  
  <!-- Conexões animadas entre tecnologias -->
  <line x1="130" y1="90" x2="200" y2="90" stroke="#60A5FA" stroke-width="2" opacity="0.6">
    <animate attributeName="stroke-dasharray" values="0,70;70,70" dur="2s" repeatCount="indefinite"/>
  </line>
  <line x1="280" y1="90" x2="350" y2="90" stroke="#60A5FA" stroke-width="2" opacity="0.6">
    <animate attributeName="stroke-dasharray" values="0,70;70,70" dur="2s" repeatCount="indefinite" begin="0.5s"/>
  </line>
  <line x1="430" y1="90" x2="500" y2="90" stroke="#60A5FA" stroke-width="2" opacity="0.6">
    <animate attributeName="stroke-dasharray" values="0,70;70,70" dur="2s" repeatCount="indefinite" begin="1s"/>
  </line>
</svg>

</div>

---

## **📊 GitHub Analytics Futurísticas**

<div align="center">

<!-- Container responsivo para stats com modo escuro/claro otimizado -->
<picture>
  <source 
    srcset="https://github-readme-stats.vercel.app/api?username=daviscpr2&show_icons=true&theme=tokyonight&bg_color=0D1117&text_color=C9D1D9&icon_color=58A6FF&title_color=58A6FF&border_color=21262D&hide_border=true&border_radius=15&custom_title=⚡+GitHub+Analytics&include_all_commits=true&count_private=true"
    media="(prefers-color-scheme: dark)"
  />
  <img 
    src="https://github-readme-stats.vercel.app/api?username=daviscpr2&show_icons=true&theme=default&bg_color=FFFFFF&text_color=24292F&icon_color=2563EB&title_color=2563EB&border_color=D0D7DE&hide_border=true&border_radius=15&custom_title=⚡+GitHub+Analytics&include_all_commits=true&count_private=true"
    alt="GitHub Stats"
  />
</picture>

<br><br>

<!-- Streak stats com design futurístico -->
<picture>
  <source 
    srcset="https://github-readme-streak-stats.herokuapp.com?user=daviscpr2&theme=tokyonight&background=0D1117&border=21262D&stroke=C9D1D9&ring=58A6FF&fire=FF6B6B&currStreakNum=C9D1D9&sideNums=C9D1D9&currStreakLabel=8B949E&sideLabels=8B949E&dates=8B949E&hide_border=true&border_radius=15"
    media="(prefers-color-scheme: dark)"
  />
  <img 
    src="https://github-readme-streak-stats.herokuapp.com?user=daviscpr2&theme=default&background=FFFFFF&border=D0D7DE&stroke=24292F&ring=2563EB&fire=DC2626&currStreakNum=24292F&sideNums=656D76&currStreakLabel=656D76&sideLabels=656D76&dates=656D76&hide_border=true&border_radius=15"
    alt="GitHub Streak"
  />
</picture>

<br><br>

<!-- Activity Graph com design moderno -->
<picture>
  <source 
    srcset="https://github-readme-activity-graph.vercel.app/graph?username=daviscpr2&theme=tokyo-night&bg_color=0D1117&color=C9D1D9&line=58A6FF&point=58A6FF&area=true&area_color=58A6FF&hide_border=true&radius=15"
    media="(prefers-color-scheme: dark)"
  />
  <img 
    src="https://github-readme-activity-graph.vercel.app/graph?username=daviscpr2&theme=minimal&bg_color=FFFFFF&color=24292F&line=2563EB&point=2563EB&area=true&area_color=2563EB&hide_border=true&radius=15"
    alt="Activity Graph"
  />
</picture>

<br><br>

<!-- Languages com layout futurístico -->
<picture>
  <source 
    srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=daviscpr2&layout=donut-vertical&theme=tokyonight&bg_color=0D1117&text_color=C9D1D9&title_color=58A6FF&border_color=21262D&hide_border=true&border_radius=15&langs_count=8&custom_title=🚀+Languages+Universe"
    media="(prefers-color-scheme: dark)"
  />
  <img 
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=daviscpr2&layout=donut-vertical&theme=default&bg_color=FFFFFF&text_color=24292F&title_color=2563EB&border_color=D0D7DE&hide_border=true&border_radius=15&langs_count=8&custom_title=🚀+Languages+Universe"
    alt="Top Languages"
  />
</picture>

</div>

---

## **🎯 Projetos em Destaque Futurístico**

<div align="center">

<!-- Card de projeto com efeito hover 3D customizado -->
<svg width="600" height="150" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="projectGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1E293B"/>
      <stop offset="50%" style="stop-color:#334155"/>
      <stop offset="100%" style="stop-color:#475569"/>
    </linearGradient>
    <filter id="projectGlow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge> 
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <rect width="580" height="130" x="10" y="10" rx="20" fill="url(#projectGradient)" 
        stroke="#2563EB" stroke-width="2" filter="url(#projectGlow)">
    <animate attributeName="stroke-width" values="2;4;2" dur="3s" repeatCount="indefinite"/>
  </rect>
  
  <!-- Ícone animado -->
  <circle cx="60" cy="75" r="25" fill="#2563EB" opacity="0.8">
    <animate attributeName="r" values="25;30;25" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="60" y="82" text-anchor="middle" fill="white" font-size="24">📁</text>
  
  <!-- Conteúdo do projeto -->
  <text x="110" y="50" fill="#60A5FA" font-size="20" font-weight="bold" font-family="Inter">
    🚀 Organizador de Arquivos Python
  </text>
  <text x="110" y="75" fill="#CBD5E1" font-size="14" font-family="Inter">
    Automação inteligente para organização de arquivos
  </text>
  <text x="110" y="95" fill="#94A3B8" font-size="12" font-family="Inter">
    Python • Automação • File Management • AI
  </text>
  
  <!-- Botão de ação futurístico -->
  <rect x=
