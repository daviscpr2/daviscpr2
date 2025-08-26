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
