```aura width=860 height=220
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter',
  position: 'relative', overflow: 'hidden', borderRadius: 18,
  border: '1px solid rgba(139,92,246,0.35)'
}}>
  <style>
    {`
      @keyframes driftLeft {
        0%, 100% { transform: translateX(0px); opacity: 0.7; }
        50% { transform: translateX(300px); opacity: 1; }
      }
      @keyframes driftRight {
        0%, 100% { transform: translateX(0px); opacity: 0.65; }
        50% { transform: translateX(-250px); opacity: 1; }
      }
      @keyframes pulse {
        0%, 100% { transform: scale(1); opacity: 0.8; }
        50% { transform: scale(1.25); opacity: 0.45; }
      }
      #purple-glow { animation: driftLeft 9s ease-in-out infinite; }
      #blue-glow { animation: driftRight 12s ease-in-out infinite; }
      #cyan-glow { animation: pulse 7s ease-in-out infinite; }
    `}
  </style>

  <svg width="860" height="220" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="purple" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(139,35,255,0.75)" />
        <stop offset="72%" stopColor="rgba(139,35,255,0)" />
      </radialGradient>
      <radialGradient id="blue" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(50,90,255,0.62)" />
        <stop offset="72%" stopColor="rgba(50,90,255,0)" />
      </radialGradient>
      <radialGradient id="cyan" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,210,255,0.45)" />
        <stop offset="72%" stopColor="rgba(0,210,255,0)" />
      </radialGradient>
    </defs>
    <ellipse id="purple-glow" cx="170" cy="230" rx="280" ry="205" fill="url(#purple)" />
    <ellipse id="blue-glow" cx="650" cy="225" rx="260" ry="190" fill="url(#blue)" />
    <ellipse id="cyan-glow" cx="500" cy="230" rx="170" ry="145" fill="url(#cyan)" />
  </svg>

  <div style={{
    position: 'absolute', left: 50, top: 54, width: 112, height: 112,
    borderRadius: 56, background: 'linear-gradient(135deg, #8b5cf6, #00d4ff)',
    display: 'flex', alignItems: 'center', justifyContent: 'center'
  }}>
    <img
      src={(github && github.user && github.user.avatarUrl) || 'https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png'}
      width={102} height={102} style={{ borderRadius: 51 }}
    />
  </div>

  <div style={{ display: 'flex', flexDirection: 'column', marginLeft: 190, gap: 10, zIndex: 10 }}>
    <div style={{ display: 'flex', fontSize: 42, fontWeight: 800, color: '#ffffff', letterSpacing: '-1px' }}>
      {(github && github.user && (github.user.name || github.user.login)) || 'Siwasith'}
    </div>
    <div style={{ display: 'flex', fontSize: 16, color: 'rgba(220,210,255,0.85)' }}>
      Developer · Builder · Open Source Explorer
    </div>
    <div style={{ display: 'flex', gap: 8, marginTop: 5 }}>
      {['Java', 'Kotlin', 'Python', 'JavaScript'].map(function(tag) {
        return (
          <div key={tag} style={{
            display: 'flex', padding: '5px 13px', borderRadius: 20,
            background: 'rgba(99,55,210,0.22)', border: '1px solid rgba(139,92,246,0.45)',
            color: '#ddd6fe', fontSize: 12, fontWeight: 600
          }}>{tag}</div>
        );
      })}
    </div>
  </div>
</div>
```

<p align="center">
  <img src="terminal.gif" width="800" alt="Siwasith terminal introduction" />
</p>

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Kotlin-%230095D5.svg?logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/Python-3670A0?logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/JavaScript-%23323330.svg?logo=javascript&logoColor=%23F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Spring-%236DB33F.svg?logo=spring&logoColor=white" alt="Spring" />
  <img src="https://img.shields.io/badge/Git-%23F05033.svg?logo=git&logoColor=white" alt="Git" />
</p>

<p align="center">
  <img src="https://iconic-api.onrender.com/dark/java" width="52" alt="Java icon" />
  <img src="https://iconic-api.onrender.com/dark/kotlin" width="52" alt="Kotlin icon" />
  <img src="https://iconic-api.onrender.com/dark/python" width="52" alt="Python icon" />
  <img src="https://iconic-api.onrender.com/dark/js" width="52" alt="JavaScript icon" />
</p>

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Siwasith&show_icons=true&theme=tokyonight&hide_border=true" alt="Siwasith's GitHub stats" />
</p>

## 🚀 Contribution Space Shooter

<p align="center">
  <img src="game.gif" alt="Siwasith's GitHub Space Shooter" />
</p>

