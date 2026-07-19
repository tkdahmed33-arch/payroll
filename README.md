<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Strategy HR Solutions Payroll | إدارة الموارد البشرية</title>
<link rel="icon" href="https://i.ibb.co/PswRPkzY/Chat-GPT-Image-Jun-28-2026-11-03-05-PM.jpg">
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;500;600;700;800;900&family=El+Messiri:wght@600;700;800&display=swap" rel="stylesheet">
<style>
/* ===== الأنماط (نفسها، لم تتغير) ===== */
:root {
  --primary: #EB0705;
  --primary-dark: #A80000;
  --gold: #C9A84C;
  --gold-light: #E8D5A0;
  --gold-dark: #A68B3C;
  --bg-light: #F5F7FA;
  --bg-dark: #0E121E;
  --card-light: rgba(255, 255, 255, 0.92);
  --card-dark: rgba(18, 24, 42, 0.96);
  --text-light: #0A0E1A;
  --text-dark: #F0F4FA;
  --sub-light: #3D4559;
  --sub-dark: #B0BCD0;
  --border-light: rgba(235, 7, 5, 0.10);
  --border-dark: rgba(235, 7, 5, 0.20);
  --sh-light: 0 12px 40px rgba(0,0,0,0.05), 0 4px 16px rgba(0,0,0,0.02);
  --sh-dark: 0 16px 48px rgba(0,0,0,0.7), 0 6px 20px rgba(0,0,0,0.4);
  --r: 20px;
  --r2: 12px;
  --transition: 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94);
}
body.dark {
  --bg: var(--bg-dark);
  --card: var(--card-dark);
  --text: var(--text-dark);
  --sub: var(--sub-dark);
  --border: var(--border-dark);
  --sh: var(--sh-dark);
}
body:not(.dark) {
  --bg: var(--bg-light);
  --card: var(--card-light);
  --text: var(--text-light);
  --sub: var(--sub-light);
  --border: var(--border-light);
  --sh: var(--sh-light);
}
*{margin:0;padding:0;box-sizing:border-box}
body{
  font-family:'Cairo',sans-serif;
  background: var(--bg);
  color:var(--text);
  min-height:100vh;
  transition: background var(--transition), color var(--transition);
  overflow-x:hidden;
  -webkit-font-smoothing:antialiased;
  position:relative;
}
canvas#bg {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 0;
  pointer-events: none;
  opacity: 0.65;
}
body::before {
  content: '';
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 0;
  pointer-events: none;
  background: 
    radial-gradient(ellipse at 20% 50%, rgba(235, 7, 5, 0.04) 0%, transparent 60%),
    radial-gradient(ellipse at 80% 20%, rgba(201, 168, 76, 0.03) 0%, transparent 50%);
}
.toggle-wrap {
  position: fixed;
  top: 24px;
  left: 24px;
  z-index: 200;
  display: flex;
  align-items: center;
  gap: 10px;
  direction: ltr;
  background: var(--card);
  padding: 5px 14px 5px 8px;
  border-radius: 60px;
  border: 1px solid var(--border);
  box-shadow: var(--sh);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  transition: all var(--transition);
}
.toggle-label {
  font-size: 13px;
  font-weight: 700;
  color: var(--gold);
  opacity: 0.8;
}
.toggle-wrap:hover .toggle-label { opacity: 1; }
.toggle {
  width: 56px;
  height: 30px;
  border-radius: 40px;
  cursor: pointer;
  background: linear-gradient(135deg, #FFD966, #F0B429);
  box-shadow: 0 0 20px rgba(235, 7, 5, 0.15);
  border: 1px solid rgba(255,255,255,0.15);
  position: relative;
  transition: all var(--transition);
  flex-shrink: 0;
}
.toggle:hover { transform: scale(1.04); }
body.dark .toggle {
  background: linear-gradient(135deg, #1A1A3A, #0A0A20);
  box-shadow: 0 0 20px rgba(235, 7, 5, 0.15);
  border-color: rgba(255,255,255,0.06);
}
.knob {
  position: absolute;
  top: 3px;
  left: 3px;
  width: 22px;
  height: 22px;
  border-radius: 50%;
  background: radial-gradient(circle at 35% 30%, #FFFDF5, #F5E6C8 80%);
  box-shadow: 0 2px 12px rgba(0,0,0,0.12);
  transition: transform 0.4s cubic-bezier(0.34, 1.2, 0.64, 1), background 0.4s;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 13px;
  color: #EB0705;
}
body.dark .knob {
  transform: translateX(26px);
  background: radial-gradient(circle at 35% 30%, #B0B8D0, #141430 80%);
  color: #FFD966;
}
.knob-icon { transition: transform 0.3s; }
body.dark .knob-icon { transform: rotate(25deg); }

.app{
  position:relative;
  z-index:10;
  min-height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  padding:40px 20px;
}
.card{
  background: var(--card);
  backdrop-filter: blur(16px);
  -webkit-backdrop-filter: blur(16px);
  border: 1px solid var(--border);
  border-radius: var(--r);
  box-shadow: var(--sh);
  transition: transform 0.3s, border-color 0.3s, box-shadow 0.3s;
  overflow: hidden;
}
.card-hover:hover{
  transform: translateY(-4px);
  border-color: var(--gold);
  box-shadow: 0 0 60px rgba(235, 7, 5, 0.10), var(--sh);
}
.btn{
  font-family:'Cairo',sans-serif;
  cursor:pointer;
  border:none;
  font-weight:700;
  transition:all 0.3s;
  display:inline-flex;
  align-items:center;
  justify-content:center;
  gap:8px;
  border-radius:50px;
  padding:12px 28px;
  font-size:14px;
  letter-spacing:0.3px;
}
.btn-p{
  background: linear-gradient(135deg, #EB0705, #A80000);
  color:#fff;
  box-shadow:0 6px 24px rgba(235, 7, 5, 0.30);
}
.btn-p:hover{
  transform:translateY(-2px);
  filter:brightness(1.08);
  box-shadow:0 10px 36px rgba(235, 7, 5, 0.45);
}
.btn-p:disabled{opacity:0.5;cursor:not-allowed;transform:none}
.btn-g{
  background: transparent;
  border: 1.5px solid var(--border);
  color: var(--text);
}
.btn-g:hover{
  background: rgba(235, 7, 5, 0.05);
  border-color: var(--gold);
  color: var(--gold);
}
.btn-d{
  background: rgba(235, 7, 5, 0.08);
  color: #EB0705;
  border: 1px solid rgba(235, 7, 5, 0.15);
}
.btn-d:hover{background: rgba(235, 7, 5, 0.16);}
.btn-s{
  background: rgba(34,197,94,0.08);
  color:#22C55E;
  border:1px solid rgba(34,197,94,0.12);
}
.btn-s:hover{background:rgba(34,197,94,0.16);}

.inp{
  width:100%;
  padding:14px 18px;
  background: var(--card);
  border:1.5px solid var(--border);
  border-radius:var(--r2);
  color:var(--text);
  font-family:'Cairo',sans-serif;
  font-size:14px;
  transition:border-color 0.3s, box-shadow 0.3s;
}
.inp:focus{
  outline:none;
  border-color: var(--primary);
  box-shadow: 0 0 0 4px rgba(235, 7, 5, 0.10);
}
select.inp{cursor:pointer;appearance:none}
textarea.inp{resize:vertical;min-height:70px}

.overlay{
  position:fixed;
  inset:0;
  background:rgba(0,0,0,0.55);
  backdrop-filter:blur(12px);
  -webkit-backdrop-filter:blur(12px);
  z-index:300;
  display:flex;
  align-items:center;
  justify-content:center;
  padding:16px;
  animation:fIn 0.2s ease;
}
.modal{
  background: var(--card);
  backdrop-filter: blur(24px);
  -webkit-backdrop-filter: blur(24px);
  border: 1px solid var(--border);
  border-radius: var(--r);
  padding:36px 32px;
  width:100%;
  max-width:750px;
  max-height:92vh;
  overflow-y:auto;
  box-shadow: 0 40px 100px rgba(0,0,0,0.40);
  animation:sUp 0.3s ease;
}
.tbl{
  width:100%;
  border-collapse:collapse;
  text-align:right;
  font-size:13px;
}
.tbl th{
  padding:16px 14px;
  background: rgba(235, 7, 5, 0.05);
  color: var(--primary);
  font-size:12px;
  font-weight:800;
  border-bottom: 2px solid rgba(235, 7, 5, 0.12);
  white-space:nowrap;
  text-transform:uppercase;
  letter-spacing:0.5px;
}
.tbl td{
  padding:14px 14px;
  border-bottom:1px solid var(--border);
  font-size:13px;
  vertical-align:middle;
  word-break:break-word;
}
.tbl tbody tr:hover{ background: rgba(235, 7, 5, 0.03); }
.tbl-wrap{overflow-x:auto;-webkit-overflow-scrolling:touch;}
.tbl-wrap table{min-width:600px;}

.badge{
  display:inline-flex;
  align-items:center;
  gap:6px;
  padding:5px 16px;
  border-radius:99px;
  font-size:11px;
  font-weight:700;
  white-space:nowrap;
}
.b-in{background:rgba(34,197,94,0.10);color:#16A34A;border:1px solid rgba(34,197,94,0.12);}
.b-out{background:rgba(235,7,5,0.08);color:#EB0705;border:1px solid rgba(235,7,5,0.12);}
.b-dept{background:rgba(235,7,5,0.06);color:#EB0705;padding:4px 14px;border-radius:99px;font-size:11px;font-weight:700;border:1px solid rgba(235,7,5,0.08);}

.stat{
  display:flex;
  flex-direction:column;
  align-items:center;
  gap:6px;
  padding:22px 12px;
  border-radius:var(--r2);
  border:1px solid var(--border);
  background: var(--card);
  backdrop-filter: blur(8px);
  transition:border-color 0.3s, box-shadow 0.3s;
}
.stat:hover{
  border-color: var(--gold);
  box-shadow: 0 0 30px rgba(235, 7, 5, 0.06);
}
.stat-n{font-family:'El Messiri',serif;font-size:34px;font-weight:700;line-height:1.2;}
.stat-l{font-size:11px;color:var(--sub);font-weight:600;text-transform:uppercase;letter-spacing:1px;}

.av{
  border-radius:50%;
  display:flex;
  align-items:center;
  justify-content:center;
  color:#fff;
  font-weight:700;
  flex-shrink:0;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

::-webkit-scrollbar{width:5px;height:5px}
::-webkit-scrollbar-track{background:transparent}
::-webkit-scrollbar-thumb{background:var(--primary);border-radius:99px}

@keyframes spin{100%{transform:rotate(360deg)}}
@keyframes spinR{100%{transform:rotate(-360deg)}}
@keyframes fIn{from{opacity:0}to{opacity:1}}
@keyframes sUp{from{opacity:0;transform:translateY(30px) scale(0.96)}to{opacity:1;transform:translateY(0) scale(1)}}
@keyframes fadeUp{from{opacity:0;transform:translateY(20px)}to{opacity:1;transform:translateY(0)}}
.fu{animation:fadeUp 0.5s ease both}

.div{border:none;border-top:1px solid var(--border);margin:20px 0}

.acc-head{
  padding:20px 24px;
  cursor:pointer;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:12px;
  user-select:none;
  transition:background 0.2s;
  border-radius:var(--r) var(--r) 0 0;
}
.acc-head:hover{background:rgba(235,7,5,0.03);}
.acc-body{overflow:hidden;max-height:0;transition:max-height 0.5s cubic-bezier(0.25,0.46,0.45,0.94);}
.acc-body.open{max-height:3000px;}
.acc-body-inner{border-top:1px solid var(--border);padding:20px 24px 24px;}

.tpl-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(170px,1fr));gap:12px;}
.tpl-btn{
  padding:16px 12px;
  border-radius:var(--r2);
  font-family:'Cairo',sans-serif;
  font-size:13px;
  font-weight:700;
  cursor:pointer;
  border:1.5px dashed var(--border);
  background:transparent;
  display:flex;
  flex-direction:column;
  align-items:center;
  gap:6px;
  transition:all 0.3s;
  text-align:center;
  color:var(--sub);
  line-height:1.4;
}
.tpl-btn:hover{
  background:rgba(235,7,5,0.04);
  border-color:var(--gold);
  color:var(--text);
}
.tpl-btn.sel{
  background:rgba(235,7,5,0.06);
  border-color:var(--primary);
  color:var(--primary);
}

.g2{display:grid;grid-template-columns:1fr 1fr;gap:16px;}
.g2 .full{grid-column:1/-1;}
@media(max-width:520px){.g2{grid-template-columns:1fr}.g2 .full{grid-column:1/-1}}

.brand-head{
  display:flex;
  align-items:center;
  gap:18px;
  margin-bottom:32px;
  flex-wrap:wrap;
}
.brand-head img{
  width:54px;
  height:54px;
  border-radius:50%;
  border: 2px solid var(--gold);
  object-fit:cover;
  box-shadow: 0 0 30px rgba(235, 7, 5, 0.12);
  flex-shrink:0;
}
.brand-head .brand-text h1{
  font-family:'El Messiri',serif;
  font-size:26px;
  font-weight:800;
  margin:0 0 2px;
  color: var(--text);
  letter-spacing: -0.5px;
}
.brand-head .brand-text h1 span{ color: var(--primary); }
.brand-head .brand-text p{
  margin:0;
  font-size:12px;
  color:var(--sub);
  font-weight:600;
  letter-spacing:2px;
  text-transform:uppercase;
}
.brand-actions{display:flex;gap:12px;margin-right:auto;flex-wrap:wrap;}

.feature-cta {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  font-size: 13px;
  font-weight: 700;
  padding: 8px 24px;
  border-radius: 99px;
  border: 1px solid;
  transition: all 0.3s;
}
body:not(.dark) .feature-cta {
  color: var(--primary);
  background: rgba(235, 7, 5, 0.08);
  border-color: rgba(235, 7, 5, 0.20);
}
body.dark .feature-cta {
  color: #FFFFFF !important;
  background: rgba(235, 7, 5, 0.15);
  border-color: rgba(255, 255, 255, 0.15);
}
.feature-cta:hover {
  transform: translateX(-4px);
  opacity: 0.9;
}

#toast{
  position:fixed;
  bottom:32px;
  left:50%;
  transform:translateX(-50%) scale(0.95);
  padding:16px 36px;
  border-radius:60px;
  font-family:'Cairo',sans-serif;
  font-weight:700;
  font-size:14px;
  z-index:999;
  transition:opacity 0.4s, transform 0.4s;
  white-space:nowrap;
  box-shadow:0 12px 40px rgba(0,0,0,0.12);
  border:1px solid rgba(255,255,255,0.08);
  opacity:0;
  pointer-events:none;
}
#toast.show{opacity:1;pointer-events:auto;transform:translateX(-50%) scale(1);}
#toast.success{background:linear-gradient(135deg,#16A34A,#0D7A34);color:#fff;}
#toast.error{background:linear-gradient(135deg,#DC2626,#991B1B);color:#fff;}

@media(max-width:640px){
  .brand-head .brand-text h1{font-size:20px;}
  .brand-head img{width:44px;height:44px;}
  .modal{padding:24px 18px;}
  .stat-n{font-size:28px;}
  .toggle-wrap{top:14px;left:14px;padding:4px 12px 4px 6px;}
  .toggle{width:50px;height:28px;}
  .knob{width:20px;height:20px;top:2px;left:2px;font-size:12px;}
  body.dark .knob{transform:translateX(22px);}
  .toggle-label{font-size:12px;}
  .app{padding:20px 10px;}
}
@media(max-width:420px){
  .brand-actions .btn{font-size:12px;padding:8px 14px;}
  .tbl td,.tbl th{padding:8px 8px;font-size:12px;}
  .tbl-wrap table{min-width:460px;}
}
.text-sub{color:var(--sub);}
.text-pr{color:var(--primary);}
.fw-700{font-weight:700;}
</style>
</head>
<body>

<canvas id="bg"></canvas>

<div class="toggle-wrap">
    <span class="toggle-label">☀</span>
    <div class="toggle" onclick="toggleDark()">
        <div class="knob">
            <span class="knob-icon">☀</span>
        </div>
    </div>
    <span class="toggle-label">🌙</span>
</div>

<div class="app">
    <div id="root" style="width:100%;max-width:960px;"></div>
</div>

<div id="toast"></div>

<script>
/* ============================================================
   الكود الرئيسي – مُصَحَّح مع إخفاء رسالة التحميل الأولية
   ============================================================ */

const GAS = 'https://script.google.com/macros/s/AKfycbywClwX-QUuIpdKIImFQL3yoRGplLeegWDqIWcKWyHSif-CfqDtVPnvvY5bbuSvi-jYIA/exec';

var S = {
  view: 'login',
  pass: null,
  employees: [],
  categories: [],
  expandedCat: null,
  selectedEmp: null,
  modal: null,
  loadingPolicies: false,
  loadingEmps: false,
  _item: {v:'',p:'',r:''},
  addItemCat: null,
  _empForm: {},
  _newCatName: '',
  _empQ: '', _empSF: 'الكل', _empDF: 'الكل',
  toastTimer: null,
  previewTemplate: null,
  selectedItems: {},
  allowances: [],
  allowanceValues: {},
  jobs: [],
  departments: [],
  administrations: [],
  dropdownsLoaded: false,
  dropdownsLoading: false,
  dropdownsError: false
};

/* ============================================================
   CANVAS – نجوم + شهب (نفس السابق)
   ============================================================ */
(function(){
  var c = document.getElementById('bg');
  var ctx = c.getContext('2d');
  var W, H;
  var stars = [];
  var meteors = [];
  var lastSpawnTime = 0;

  function createStars() {
    var isDark = document.body.classList.contains('dark');
    var count = isDark ? 220 : 160;
    stars = [];
    for (var i = 0; i < count; i++) {
      var brightness = 0.3 + Math.random() * 0.7;
      var col;
      var r = Math.random();
      if (isDark) {
        if (r < 0.2) col = '255,200,180';
        else if (r < 0.5) col = '255,235,180';
        else col = '200,220,255';
      } else {
        if (r < 0.3) col = '20,20,25';
        else if (r < 0.6) col = '40,40,50';
        else col = '60,60,75';
      }
      stars.push({
        x: Math.random() * W,
        y: Math.random() * H,
        r: 0.3 + Math.random() * 1.8,
        baseAlpha: brightness * (isDark ? 0.9 : 0.5),
        alpha: 0,
        twinkleSpeed: 0.003 + Math.random() * 0.02,
        phase: Math.random() * Math.PI * 2,
        col: col
      });
    }
  }

  function spawnMeteor() {
    var isDark = document.body.classList.contains('dark');
    var threshold = isDark ? 0.6 : 0.8;
    if (Math.random() > threshold) return;
    var angle = Math.PI / 4 + Math.random() * Math.PI / 5;
    var speed = 6 + Math.random() * 16;
    var x = Math.random() * W * 1.1 - W * 0.05;
    var y = Math.random() * H * 0.15;
    var len = 70 + Math.random() * 150;
    var life = 40 + Math.random() * 90;
    var isGold = Math.random() > 0.4;
    meteors.push({
      x: x, y: y,
      vx: Math.cos(angle) * speed,
      vy: Math.sin(angle) * speed,
      len: len,
      life: life,
      maxLife: life,
      width: 1.8 + Math.random() * 3.5,
      alpha: 0.8 + Math.random() * 0.2,
      col: isGold ? '255,215,120' : '255,100,80'
    });
  }

  function resize() {
    W = c.width = window.innerWidth;
    H = c.height = window.innerHeight;
    createStars();
  }
  window._resizeCanvas = resize;
  window.addEventListener('resize', resize);
  resize();

  function draw(time) {
    ctx.clearRect(0, 0, W, H);
    stars.forEach(function(s) {
      s.phase += s.twinkleSpeed;
      s.alpha = s.baseAlpha * (0.5 + 0.5 * Math.sin(s.phase));
      ctx.beginPath();
      ctx.arc(s.x, s.y, s.r, 0, Math.PI * 2);
      ctx.fillStyle = 'rgba(' + s.col + ',' + s.alpha + ')';
      ctx.fill();
      if (s.r > 1.3) {
        ctx.shadowColor = 'rgba(' + s.col + ',' + (s.alpha * 0.15) + ')';
        ctx.shadowBlur = 10;
        ctx.fill();
        ctx.shadowBlur = 0;
      }
    });

    for (var i = meteors.length - 1; i >= 0; i--) {
      var m = meteors[i];
      m.x += m.vx;
      m.y += m.vy;
      m.life--;
      if (m.life <= 0 || m.x > W + 100 || m.y > H + 100) {
        meteors.splice(i, 1);
        continue;
      }
      var progress = 1 - (m.life / m.maxLife);
      var alpha = m.alpha * (1 - progress * 0.5);
      var tailLen = m.len * (0.6 + 0.4 * (1 - progress));
      var gradTail = ctx.createLinearGradient(
        m.x, m.y,
        m.x - m.vx * 0.15 * tailLen,
        m.y - m.vy * 0.15 * tailLen
      );
      gradTail.addColorStop(0, 'rgba(' + m.col + ',' + alpha + ')');
      gradTail.addColorStop(0.2, 'rgba(' + m.col + ',' + (alpha * 0.6) + ')');
      gradTail.addColorStop(1, 'rgba(' + m.col + ',0)');
      ctx.beginPath();
      ctx.moveTo(m.x, m.y);
      ctx.lineTo(m.x - m.vx * 0.15 * tailLen, m.y - m.vy * 0.15 * tailLen);
      ctx.strokeStyle = gradTail;
      ctx.lineWidth = m.width * (0.7 + 0.3 * (1 - progress));
      ctx.lineCap = 'round';
      ctx.stroke();
      ctx.shadowColor = 'rgba(' + m.col + ',' + (alpha * 0.4) + ')';
      ctx.shadowBlur = 40;
      ctx.beginPath();
      ctx.arc(m.x, m.y, m.width * 0.9, 0, Math.PI * 2);
      ctx.fillStyle = 'rgba(255,255,255,' + (alpha * 0.9) + ')';
      ctx.fill();
      ctx.shadowBlur = 0;
    }

    if (time - lastSpawnTime > 500 + Math.random() * 1000) {
      spawnMeteor();
      lastSpawnTime = time;
    }
    requestAnimationFrame(draw);
  }

  draw(0);

  var origToggle = toggleDark;
  toggleDark = function() {
    origToggle();
    if (window._resizeCanvas) window._resizeCanvas();
    var icon = document.querySelector('.knob-icon');
    if(icon) icon.textContent = document.body.classList.contains('dark') ? '☾' : '☀';
  };
  window.toggleDark = toggleDark;
})();

/* ===== التوابع الأساسية ===== */
function toggleDark(){
  document.body.classList.toggle('dark');
  localStorage.setItem('dk',document.body.classList.contains('dark')?'1':'');
  var icon = document.querySelector('.knob-icon');
  if(icon) icon.textContent = document.body.classList.contains('dark') ? '☾' : '☀';
}
if(localStorage.getItem('dk')) document.body.classList.add('dark');
setTimeout(function(){
  var icon = document.querySelector('.knob-icon');
  if(icon) icon.textContent = document.body.classList.contains('dark') ? '☾' : '☀';
}, 50);

var _cbN=0;
function gas(params,cb){
  var name='__cb'+Date.now()+'_'+(++_cbN);
  var qs=Object.keys(params).map(function(k){
    var v = params[k];
    if (v !== null && typeof v === 'object') v = JSON.stringify(v);
    return encodeURIComponent(k)+'='+encodeURIComponent(v);
  }).join('&');
  var sc=document.createElement('script');
  sc.src=GAS+'?'+qs+'&callback='+name;
  var t=setTimeout(function(){cleanup();cb&&cb({error:'timeout'});},20000);
  function cleanup(){delete window[name];sc.parentNode&&sc.parentNode.removeChild(sc);clearTimeout(t);}
  window[name]=function(d){cleanup();cb&&cb(d);};
  sc.onerror=function(){cleanup();cb&&cb({error:'network'});};
  document.body.appendChild(sc);
}

function toast(msg,ok){
  var el=document.getElementById('toast');
  if(!el) return;
  el.textContent=msg;
  el.className='show '+(ok===false?'error':'success');
  clearTimeout(S.toastTimer);
  S.toastTimer=setTimeout(function(){el.className='';},2800);
}

function render(){
  var root=document.getElementById('root');
  if(S.view==='login')         root.innerHTML=renderLogin();
  else if(S.view==='main')     root.innerHTML=renderMain();
  else if(S.view==='policy')   root.innerHTML=renderPolicy();
  else if(S.view==='employees')root.innerHTML=renderEmployees();
  renderModal();
}

/* ===== واجهة الدخول ===== */
function renderLogin(){
  return '<div class="fu" style="max-width:440px;margin:0 auto;width:100%;">'
  +'<div style="text-align:center;margin-bottom:32px;">'
  +'<div style="position:relative;width:130px;height:130px;margin:0 auto 18px;display:flex;align-items:center;justify-content:center;">'
  +'<div style="position:absolute;width:120px;height:120px;border-radius:50%;border:1px solid rgba(235,7,5,.20);animation:spin 12s linear infinite;"></div>'
  +'<div style="position:absolute;width:108px;height:108px;border-radius:50%;border:1.5px dashed rgba(235,7,5,.10);animation:spinR 18s linear infinite;"></div>'
  +'<img src="https://i.ibb.co/PswRPkzY/Chat-GPT-Image-Jun-28-2026-11-03-05-PM.jpg" style="width:76px;height:76px;border-radius:50%;border:3px solid rgba(255,255,255,.9);box-shadow:0 0 50px rgba(235,7,5,.25);object-fit:cover;position:relative;z-index:2;">'
  +'</div>'
  +'<h1 style="font-family:\'El Messiri\',serif;font-size:38px;font-weight:800;margin:0 0 4px;color:var(--text);">Strategy<span style="color:var(--primary);">.</span></h1>'
  +'<p style="font-size:11px;letter-spacing:4px;color:var(--sub);text-transform:uppercase;margin:0;font-weight:600;">HR SOLUTIONS</p>'
  +'</div>'
  +'<div class="card" style="padding:40px 36px;border-color:var(--primary);">'
  +'<h2 style="font-size:18px;font-weight:700;margin:0 0 28px;text-align:center;color:var(--primary);">🔐 دخول الموارد البشرية</h2>'
  +'<input class="inp" id="passIn" type="password" placeholder="أدخل كلمة المرور" style="text-align:center;font-size:16px;letter-spacing:3px;border-color:var(--primary);" onkeydown="if(event.key===\'Enter\')doLogin();">'
  +'<div id="passErr" style="color:var(--primary);font-size:13px;text-align:center;display:none;font-weight:700;margin-top:14px;">⚠️ كلمة المرور غير صحيحة</div>'
  +'<button class="btn btn-p" id="loginBtn" onclick="doLogin()" style="padding:14px;font-size:15px;width:100%;margin-top:20px;">'+(S.pass===null?'جارٍ التحميل...':'دخول')+'</button>'
  +'</div>'
  +'<p style="text-align:center;margin-top:24px;font-size:12px;color:var(--sub);letter-spacing:1px;">Strategy HR Solutions © '+new Date().getFullYear()+'</p>'
  +'</div>';
}

function doLogin(){
  if(S.pass===null)return;
  var inp=document.getElementById('passIn');
  if(!inp)return;
  if(inp.value.trim()===S.pass){S.view='main';render();}
  else document.getElementById('passErr').style.display='block';
}

/* ===== الصفحة الرئيسية ===== */
function renderMain(){
  var logoUrl = 'https://i.ibb.co/PswRPkzY/Chat-GPT-Image-Jun-28-2026-11-03-05-PM.jpg';
  return '<div class="fu" style="width:100%;">'
  +'<div class="brand-head">'
  +'<img src="'+logoUrl+'">'
  +'<div class="brand-text"><h1>Strategy<span>.</span></h1><p>HR Solutions</p></div>'
  +'<div class="brand-actions">'
  +'<button class="btn btn-g" onclick="doLogout()" style="padding:8px 20px;font-size:13px;">🚪 خروج</button>'
  +'</div></div>'
  +'<div style="background:linear-gradient(135deg,#EB0705,#8B0000);border-radius:var(--r);padding:32px 36px;margin-bottom:32px;display:flex;align-items:center;justify-content:space-between;gap:16px;box-shadow:0 16px 48px rgba(235,7,5,.20);border:1px solid rgba(235,7,5,0.12);">'
  +'<div><h2 style="color:#fff;margin:0 0 6px;font-size:22px;font-weight:800;font-family:\'El Messiri\',serif;">أهلاً بك في نظام Strategy HR Solutions</h2><p style="color:rgba(255,255,255,.85);margin:0;font-size:14px;">إدارة الموظفين واللوائح التنظيمية من منصة واحدة احترافية</p></div>'
  +'<img src="'+logoUrl+'" style="width:64px;height:64px;border-radius:50%;border:2px solid rgba(255,255,255,0.3);object-fit:cover;flex-shrink:0;">'
  +'</div>'
  +'<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(270px,1fr));gap:24px;">'
  +featureCard('📋','اللوائح التنظيمية','أضف وعدّل بنود الجزاءات والعقوبات','#EB0705','showPolicy()')
  +featureCard('👥','قاعدة بيانات الموظفين','أضف موظفين جدد وتتبع حالتهم','#1A2A4A','showEmployees()')
  +'</div></div>';
}

function featureCard(icon,title,desc,color,fn){
  return '<div class="card card-hover" style="padding:40px 28px;text-align:center;cursor:pointer;border-color:'+color+'40;" onclick="'+fn+'">'
  +'<div style="width:76px;height:76px;border-radius:50%;background:'+color+'10;border:2px solid '+color+'30;display:flex;align-items:center;justify-content:center;margin:0 auto 20px;font-size:36px;box-shadow:0 0 30px '+color+'15;">'+icon+'</div>'
  +'<h3 style="font-size:20px;font-weight:700;margin:0 0 12px;font-family:\'El Messiri\',serif;color:var(--text);">'+title+'</h3>'
  +'<p style="font-size:14px;color:var(--sub);margin:0 0 24px;line-height:1.8;">'+desc+'</p>'
  +'<div class="feature-cta">فتح ←</div>'
  +'</div>';
}

function doLogout(){S.view='login';render();}

/* ============================================================
   دالة استخراج العمر والنوع
   ============================================================ */
function extractAgeAndGender(nationalId) {
  var id = nationalId.trim();
  if (id.length !== 14 || !/^\d{14}$/.test(id)) {
    return { age: null, gender: null, valid: false };
  }
  var centuryDigit = parseInt(id.charAt(0));
  var century = (centuryDigit === 2) ? 1900 : (centuryDigit === 3 ? 2000 : 1900);
  var year = parseInt(id.substring(1, 3));
  var month = parseInt(id.substring(3, 5)) - 1;
  var day = parseInt(id.substring(5, 7));
  var fullYear = century + year;
  var birthDate = new Date(fullYear, month, day);
  var now = new Date();
  var age = now.getFullYear() - birthDate.getFullYear();
  var m = now.getMonth() - birthDate.getMonth();
  if (m < 0 || (m === 0 && now.getDate() < birthDate.getDate())) {
    age--;
  }
  var genderDigit = parseInt(id.charAt(12));
  var gender = (genderDigit % 2 === 0) ? 'أنثى' : 'ذكر';
  return { age: age, gender: gender, valid: true };
}

/* ============================================================
   ★★★ جلب القوائم من الشيت (مع إمكانية الكتم) ★★★
   ============================================================ */
// <<<<<<< تعديل: إضافة معامل silent لمنع عرض الرسائل
function loadDropdownData(silent) {
  return new Promise(function(resolve) {
    S.dropdownsLoading = true;
    S.dropdownsError = false;
    gas({ action: 'getDropdownData' }, function(res) {
      S.dropdownsLoading = false;
      if (res && res.jobs && res.departments && res.administrations) {
        S.jobs = res.jobs.filter(function(item){ return item && item.trim() !== ''; });
        S.departments = res.departments.filter(function(item){ return item && item.trim() !== ''; });
        S.administrations = res.administrations.filter(function(item){ return item && item.trim() !== ''; });
        S.dropdownsLoaded = true;
        if (!silent) {
          toast('✅ تم تحميل البيانات من الشيت', true);
        }
      } else {
        S.jobs = ['مدير', 'نائب مدير', 'محاسب', 'موظف استقبال', 'أمين مخزن'];
        S.departments = ['الإدارة', 'المبيعات', 'التسويق', 'المحاسبة', 'الموارد البشرية', 'تقنية المعلومات', 'خدمة العملاء', 'المستودع', 'الإنتاج', 'أخرى'];
        S.administrations = ['الإدارة العامة', 'الإدارة المالية', 'الإدارة التجارية', 'إدارة الموارد البشرية', 'إدارة التقنية', 'إدارة العمليات'];
        S.dropdownsLoaded = true;
        S.dropdownsError = true;
        if (!silent) {
          toast('⚠️ لم نتمكن من جلب البيانات من الشيت، نستخدم قوائم افتراضية', false);
        }
      }
      resolve();
    });
  });
}

function loadAllowances() {
  return new Promise(function(resolve) {
    gas({ action: 'getAllowances' }, function(res) {
      if (res && res.allowances) {
        S.allowances = res.allowances.filter(function(item){ return item && item.trim() !== ''; });
      } else {
        S.allowances = ['بدل نقل', 'بدل سكن', 'بدل غذاء', 'بدل تدريب', 'بدل خطر'];
      }
      resolve();
    });
  });
}

/* ============================================================
   TEMPLATES (نفسها)
   ============================================================ */
var TEMPLATES = [
  {
    name: 'لائحة جزاءات التأخير',
    icon: '⏰',
    col: '#F59E0B',
    items: [
      { violation: 'التأخير عن موعد بدء العمل دون عذر مقبول (أقل من 30 دقيقة)', punishment: 'إنذار شفهي + خصم أجر الساعة', repeat: 'إنذار كتابي + خصم نصف يوم' },
      { violation: 'التأخير عن موعد بدء العمل دون عذر مقبول (أكثر من 30 دقيقة)', punishment: 'خصم أجر يوم + إنذار كتابي', repeat: 'خصم 3 أيام + إيقاف العلاوة الدورية' },
      { violation: 'التأخير المتكرر (3 مرات فأكثر شهرياً)', punishment: 'خصم يومين + إنذار رسمي', repeat: 'خصم 5 أيام + الحرمان من البدلات' },
      { violation: 'التأخير عن الاجتماعات الرسمية أو المهام الحرجة', punishment: 'خصم يوم + إنذار شديد', repeat: 'خصم 3 أيام + إحالة للتحقيق' }
    ]
  },
  {
    name: 'لائحة الغياب والانقطاع',
    icon: '📅',
    col: '#EF4444',
    items: [
      { violation: 'الغياب يوم واحد دون عذر مقبول', punishment: 'خصم أجر اليوم + إنذار كتابي', repeat: 'خصم 3 أيام + إنذار رسمي' },
      { violation: 'الغياب المتواصل لمدة 3 أيام دون إشعار', punishment: 'خصم أسبوع + إنذار شديد', repeat: 'فصل تأديبي (المادة 80)' },
      { violation: 'الانقطاع عن العمل لمدة تزيد عن 15 يوماً دون عذر', punishment: 'فصل من الخدمة (المادة 69)', repeat: 'لا يوجد (فصل نهائي)' },
      { violation: 'عدم الالتزام بمواعيد الحضور والانصراف بشكل متكرر', punishment: 'إنذار كتابي + خصم يوم', repeat: 'خصم 3 أيام + إيقاف العلاوة' }
    ]
  },
  {
    name: 'لائحة السلوك الوظيفي',
    icon: '🤝',
    col: '#8B5CF6',
    items: [
      { violation: 'استخدام ألفاظ غير لائقة أو مشاجرة مع الزملاء', punishment: 'إنذار كتابي + خصم يوم', repeat: 'خصم 3 أيام + إحالة للتحقيق' },
      { violation: 'استخدام الهاتف المحمول أثناء ساعات العمل (بدون إذن)', punishment: 'تنبيه شفهي', repeat: 'إنذار كتابي + خصم نصف يوم' },
      { violation: 'عدم احترام التسلسل الهرمي أو مخالفة تعليمات المشرف', punishment: 'إنذار رسمي + خصم يوم', repeat: 'خصم 3 أيام + الحرمان من الترقية' },
      { violation: 'نشر معلومات كاذبة أو مسيئة عن المؤسسة أو الزملاء', punishment: 'فصل تأديبي فوري', repeat: 'إحالة للنيابة العامة' }
    ]
  },
  {
    name: 'لائحة الجزاءات التأديبية',
    icon: '⚖️',
    col: '#EC4899',
    items: [
      { violation: 'إهمال جسيم في أداء المهام الموكلة', punishment: 'إنذار كتابي + خصم يوم', repeat: 'خصم 3 أيام + إيقاف العلاوة' },
      { violation: 'ارتكاب خطأ مهني أدى إلى خسائر مادية', punishment: 'خصم 5 أيام + إنذار شديد', repeat: 'فصل تأديبي مع إمكانية التعويض' },
      { violation: 'التلاعب بالتقارير أو المستندات الرسمية', punishment: 'فصل فوري + إحالة للتحقيق', repeat: 'إحالة للنيابة' },
      { violation: 'الاعتداء اللفظي أو الجسدي على المشرفين أو الزملاء', punishment: 'فصل تأديبي فوري', repeat: 'إحالة للجهات المختصة' }
    ]
  },
  {
    name: 'لائحة العمل الإضافي',
    icon: '💼',
    col: '#06B6D4',
    items: [
      { violation: 'رفض العمل الإضافي المطلوب دون عذر قانوني', punishment: 'إنذار كتابي + خصم نصف يوم', repeat: 'خصم يومين + إنذار رسمي' },
      { violation: 'التقاعس أو عدم الإنجاز في ساعات العمل الإضافي', punishment: 'خصم أجر الساعات + تنبيه', repeat: 'خصم يوم + إنذار' },
      { violation: 'الانسحاب من العمل الإضافي دون إشعار مسبق', punishment: 'إنذار رسمي + خصم يوم', repeat: 'خصم 3 أيام + إحالة للتحقيق' },
      { violation: 'التأخير عن بدء العمل الإضافي (أكثر من 15 دقيقة)', punishment: 'تنبيه', repeat: 'إنذار كتابي + خصم نصف يوم' }
    ]
  },
  {
    name: 'لائحة المكافآت والحوافز',
    icon: '🏆',
    col: '#10B981',
    items: [
      { violation: 'الإنجاز المتميز في المشاريع أو المهام', punishment: 'مكافأة مالية (نسبة من الإنجاز)', repeat: 'ترقية أو علاوة استثنائية' },
      { violation: 'الالتزام الكامل بالمواعيد لمدة 3 أشهر متتالية', punishment: 'شهادة تقدير + مكافأة 5%', repeat: 'مكافأة 10% + ترقية' },
      { violation: 'تقديم مبادرات إيجابية تخدم المؤسسة', punishment: 'حافز مادي + شهادة شكر', repeat: 'ترقية أو علاوة سنوية' },
      { violation: 'العمل الجماعي المتميز وحل الأزمات', punishment: 'مكافأة فريق + إشادة رسمية', repeat: 'حوافز إضافية + ترقية' }
    ]
  },
  {
    name: 'لائحة الإجازات',
    icon: '🌴',
    col: '#3B82F6',
    items: [
      { violation: 'طلب إجازة دون استيفاء الإجراءات النظامية', punishment: 'رفض الطلب + تنبيه', repeat: 'إنذار كتابي + خصم يوم' },
      { violation: 'تجاوز مدة الإجازة المصرح بها (أكثر من يومين)', punishment: 'خصم الأيام الزائدة + إنذار', repeat: 'خصم مضاعف + إيقاف الإجازات القادمة' },
      { violation: 'الإجازة المرضية دون تقديم تقرير طبي معتمد', punishment: 'اعتبارها إجازة عادية (غير مدفوعة)', repeat: 'إنذار رسمي + خصم الأيام' },
      { violation: 'تقديم طلب إجازة بعد بدء الإجازة أو في وقت متأخر', punishment: 'رفض الطلب أو خصم يوم', repeat: 'إنذار كتابي + الحرمان من الإجازات المدفوعة' }
    ]
  },
  {
    name: 'لائحة أمن المعلومات',
    icon: '🔒',
    col: '#6366F1',
    items: [
      { violation: 'مشاركة بيانات الدخول (كلمة المرور) مع الغير', punishment: 'إنذار كتابي + تغيير كلمة المرور', repeat: 'خصم يوم + إيقاف الصلاحيات' },
      { violation: 'تصفح مواقع إلكترونية غير مصرح بها أثناء العمل', punishment: 'تنبيه + حجب المواقع', repeat: 'إنذار رسمي + خصم نصف يوم' },
      { violation: 'محاولة اختراق أو الوصول غير المصرح به للأنظمة', punishment: 'فصل فوري + إحالة للتحقيق', repeat: 'إحالة للنيابة العامة' },
      { violation: 'ترك الأجهزة مفتوحة أو عدم قفل الشاشة عند الغياب', punishment: 'إنذار', repeat: 'إنذار كتابي + خصم يوم' }
    ]
  }
];

function tplFor(name){
  var found = TEMPLATES.find(function(t){ return t.name === name; });
  return found || { icon: '📋', col: '#EB0705', items: [] };
}

/* ===== قوالب مع اختيار البنود ===== */
function quickAddCat(name){
  var template = TEMPLATES.find(function(t){ return t.name === name; });
  if (!template) {
    S.loadingPolicies = true;
    render();
    gas({action:'addPolicyItem', category:name, violation:'(بند تجريبي)', punishment:'-', repeat:'-'}, function(){
      loadPolicies();
      S.expandedCat = name;
    });
    return;
  }
  S.selectedItems = {};
  template.items.forEach(function(item, idx){
    S.selectedItems[idx] = true;
  });
  S.previewTemplate = name;
  S.modal = 'previewTemplate';
  render();
}

function confirmAddTemplateItems(name){
  var template = TEMPLATES.find(function(t){ return t.name === name; });
  if (!template) { closeModal(); return; }
  var selected = [];
  template.items.forEach(function(item, idx){
    if (S.selectedItems[idx]) {
      selected.push(item);
    }
  });
  if (selected.length === 0) {
    toast('⚠️ لم تختر أي بند', false);
    return;
  }
  closeModal();
  S.loadingPolicies = true;
  render();
  var total = selected.length;
  var done = 0;
  var hasError = false;
  selected.forEach(function(item){
    gas({
      action: 'addPolicyItem',
      category: name,
      violation: item.violation,
      punishment: item.punishment,
      repeat: item.repeat || '—'
    }, function(res){
      done++;
      if (res.error) hasError = true;
      if (done === total) {
        toast(hasError ? '⚠️ بعض البنود لم تُضف' : '✅ تم إضافة ' + total + ' بند', !hasError);
        loadPolicies();
        S.expandedCat = name;
      }
    });
  });
}

function renderModalPreviewTemplate(){
  var name = S.previewTemplate;
  var template = TEMPLATES.find(function(t){ return t.name === name; });
  if (!template) { closeModal(); return ''; }

  var itemsHtml = '';
  template.items.forEach(function(item, idx){
    var checked = S.selectedItems[idx] !== false ? 'checked' : '';
    itemsHtml += '<tr>'
      +'<td style="width:4%;"><input type="checkbox" class="item-checkbox" data-idx="'+idx+'" '+checked+' style="width:18px;height:18px;cursor:pointer;accent-color:#EB0705;"></td>'
      +'<td style="font-weight:600;width:32%;">'+esc(item.violation)+'</td>'
      +'<td style="color:#EB0705;font-weight:700;width:32%;">'+esc(item.punishment)+'</td>'
      +'<td style="color:#A68B3C;font-weight:600;width:32%;">'+esc(item.repeat || '—')+'</td>'
    +'</tr>';
  });

  return '<div class="overlay" onclick="closeModal()"><div class="modal" onclick="event.stopPropagation();" style="max-width:700px;">'
  +'<div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:6px;">'
  +'<h3 style="font-size:20px;font-weight:800;color:var(--primary);font-family:\'El Messiri\',serif;">'+template.icon+' معاينة القالب</h3>'
  +'<button class="btn btn-g" onclick="selectAllItems(true)" style="padding:4px 14px;font-size:12px;">✅ تحديد الكل</button>'
  +'<button class="btn btn-g" onclick="selectAllItems(false)" style="padding:4px 14px;font-size:12px;">⬜ إلغاء الكل</button>'
  +'</div>'
  +'<p style="margin:0 0 16px;font-size:14px;color:var(--sub);">اللائحة: <strong style="color:var(--text);">'+esc(template.name)+'</strong></p>'
  +'<div style="background:rgba(235,7,5,0.03);border-radius:var(--r2);border:1px solid var(--border);overflow:hidden;">'
  +'<div class="tbl-wrap"><table class="tbl"><thead><tr><th style="width:4%;">اختيار</th><th style="width:32%;">المخالفة</th><th style="width:32%;">العقوبة</th><th style="width:32%;">التكرار</th></tr></thead><tbody>'
  +itemsHtml
  +'</tbody></table></div></div>'
  +'<p style="margin-top:10px;font-size:12px;color:var(--sub);text-align:center;">✔ اختر البنود التي تريد إضافتها، ثم اضغط "إضافة المختار"</p>'
  +'<div style="display:flex;gap:12px;margin-top:16px;">'
  +'<button class="btn btn-p" onclick="confirmAddTemplateItems(\''+esc(name)+'\')" style="flex:1;padding:12px;font-size:14px;">✅ إضافة المختار ('+template.items.length+' بند)</button>'
  +'<button class="btn btn-g" onclick="closeModal()" style="padding:12px 24px;font-size:14px;">✖ إلغاء</button>'
  +'</div>'
  +'</div></div>';
}

function selectAllItems(select){
  var checkboxes = document.querySelectorAll('.item-checkbox');
  checkboxes.forEach(function(cb, idx){
    cb.checked = select;
    S.selectedItems[idx] = select;
  });
  var total = checkboxes.length;
  var selectedCount = select ? total : 0;
  var btn = document.querySelector('.modal .btn-p');
  if (btn) {
    btn.textContent = '✅ إضافة المختار (' + selectedCount + ' بند)';
  }
}

document.addEventListener('change', function(e){
  if (e.target && e.target.classList.contains('item-checkbox')) {
    var idx = parseInt(e.target.dataset.idx);
    S.selectedItems[idx] = e.target.checked;
    var checkboxes = document.querySelectorAll('.item-checkbox');
    var total = checkboxes.length;
    var selectedCount = 0;
    checkboxes.forEach(function(cb){
      if (cb.checked) selectedCount++;
    });
    var btn = document.querySelector('.modal .btn-p');
    if (btn) {
      btn.textContent = '✅ إضافة المختار (' + selectedCount + ' بند)';
    }
  }
});

/* ============================================================
   دوال اللوائح والموظفين (المُصَحَّحَة)
   ============================================================ */
function renderPolicy(){
  var html='<div class="fu" style="width:100%;">'
  +'<div class="brand-head">'
  +'<img src="https://i.ibb.co/PswRPkzY/Chat-GPT-Image-Jun-28-2026-11-03-05-PM.jpg">'
  +'<div class="brand-text"><h1>Strategy<span>.</span></h1><p>HR Solutions</p></div>'
  +'<div class="brand-actions">'
  +'<button class="btn btn-g" onclick="S.view=\'main\';render();">← العودة</button>'
  +'<button class="btn btn-p" onclick="openNewCat()">+ لائحة جديدة</button>'
  +'</div></div>';

  if(S.loadingPolicies){
    html+='<div class="card" style="padding:60px;text-align:center;"><div style="font-size:40px;margin-bottom:16px;">⏳</div><p style="color:var(--sub);">جارٍ تحميل اللوائح...</p></div>';
  } else if(S.categories.length===0){
    html+='<div class="card" style="padding:36px;">'
    +'<p style="text-align:center;color:var(--sub);margin-bottom:28px;">لا توجد لوائح بعد — اختر من القوالب الجاهزة</p>'
    +'<div class="tpl-grid">';
    TEMPLATES.forEach(function(t){
      html+='<button class="tpl-btn" onclick="quickAddCat(\''+t.name+'\')"><span style="font-size:28px;">'+t.icon+'</span>'+t.name+'</button>';
    });
    html+='</div></div>';
  } else {
    S.categories.forEach(function(cat,ci){
      var t=tplFor(cat.name);
      var isOpen=S.expandedCat===cat.name;
      html+='<div class="card" style="margin-bottom:18px;overflow:hidden;'+(isOpen?'border-color:'+t.col+'50;':'')+'">'
      +'<div class="acc-head" onclick="toggleCat(\''+encodeURIComponent(cat.name)+'\')">'
      +'<div style="display:flex;align-items:center;gap:14px;">'
      +'<div style="width:46px;height:46px;border-radius:12px;background:'+t.col+'10;border:1px solid '+t.col+'25;display:flex;align-items:center;justify-content:center;font-size:22px;flex-shrink:0;">'+t.icon+'</div>'
      +'<div><p style="margin:0;font-weight:700;font-size:16px;font-family:\'El Messiri\',serif;">'+esc(cat.name)+'</p>'
      +'<p style="margin:0;font-size:12px;color:var(--sub);">'+cat.items.length+' بند</p></div>'
      +'</div>'
      +'<div style="display:flex;align-items:center;gap:10px;">'
      +'<button class="btn btn-p" onclick="event.stopPropagation();openNewItem(\''+encodeURIComponent(cat.name)+'\')" style="padding:6px 18px;font-size:12px;">+ بند</button>'
      +'<span style="color:var(--gold);transition:transform 0.3s;display:inline-block;transform:'+(isOpen?'rotate(180deg)':'none')+';">▼</span>'
      +'</div></div>'
      +'<div class="acc-body'+(isOpen?' open':'')+'"><div class="acc-body-inner">';
      if(cat.items.length===0){
        html+='<p style="padding:20px 0;color:var(--sub);text-align:center;margin:0;">لا يوجد بنود — اضغط "+ بند"</p>';
      } else {
        html+='<div class="tbl-wrap"><table class="tbl"><thead><tr><th style="width:4%;">#</th><th style="width:34%;">المخالفة</th><th style="width:28%;">العقوبة</th><th style="width:28%;">التكرار</th><th style="width:6%;"></th></tr></thead><tbody>';
        cat.items.forEach(function(item,idx){
          html+='<tr><td style="color:var(--sub);font-size:11px;font-weight:700;">'+(idx+1)+'</td>'
          +'<td style="font-weight:600;">'+esc(item.violation)+'</td>'
          +'<td style="color:#EB0705;font-weight:700;">'+esc(item.punishment)+'</td>'
          +'<td style="color:#A68B3C;font-weight:600;">'+(item.repeat?esc(item.repeat):'—')+'</td>'
          +'<td><button class="btn btn-d" onclick="deletePolicyItem(\''+item.id+'\')" style="padding:4px 10px;font-size:12px;border-radius:8px;">🗑</button></td></tr>';
        });
        html+='</tbody></table></div>';
      }
      html+='</div></div></div>';
    });
    var remaining=TEMPLATES.filter(function(t){return !S.categories.find(function(c){return c.name===t.name;});});
    if(remaining.length>0){
      html+='<div style="margin-top:14px;"><p style="font-size:13px;color:var(--sub);margin-bottom:12px;">قوالب جاهزة للإضافة:</p><div class="tpl-grid">';
      remaining.forEach(function(t){
        html+='<button class="tpl-btn" onclick="quickAddCat(\''+t.name+'\')" style="border-color:'+t.col+'40;color:var(--sub);"><span style="font-size:24px;">'+t.icon+'</span>'+t.name+'</button>';
      });
      html+='</div></div>';
    }
  }
  html+='</div>';
  return html;
}

function toggleCat(enc){S.expandedCat=(S.expandedCat===decodeURIComponent(enc)?null:decodeURIComponent(enc));render();}

function loadPolicies(){
  S.loadingPolicies=true;render();
  gas({action:'getPolicies'},function(r){
    S.loadingPolicies=false;
    S.categories=r.categories||[];
    render();
  });
}

function showPolicy(){S.view='policy';loadPolicies();}

function deletePolicyItem(id){
  if(!confirm('حذف هذا البند؟'))return;
  gas({action:'deletePolicyItem',id:id},function(){loadPolicies();});
}

function openNewCat(){S.modal='newCat';S._newCatName='';render();}
function openNewItem(enc){S.modal='newItem';S.addItemCat=decodeURIComponent(enc);S._item={v:'',p:'',r:''};render();}

/* ============================================================
   دوال الموظفين – المُصَحَّحَة (باستخدام employeeCode)
   ============================================================ */
function renderEmployees(){
  var emps = S.employees;
  var q = (S._empQ||'').toLowerCase();
  var sf = S._empSF||'الكل';
  var df = S._empDF||'الكل';
  var filtered = emps.filter(function(e){
    var mQ = !q || (e.name+' '+e.job+' '+e.department+' '+e.nationalId+' '+e.employeeCode+' '+e.administration).toLowerCase().includes(q);
    var mS = sf==='الكل' || e.status===sf;
    var mD = df==='الكل' || e.department===df;
    return mQ && mS && mD;
  });
  var active = emps.filter(function(e){ return e.status==='داخل العمل'; }).length;
  var inactive = emps.length - active;
  var usedDepts = ['الكل'].concat(emps.map(function(e){ return e.department; }).filter(function(d,i,a){ return d && a.indexOf(d)===i; }));

  var html = '<div class="fu" style="width:100%;">'
    +'<div class="brand-head">'
    +'<img src="https://i.ibb.co/PswRPkzY/Chat-GPT-Image-Jun-28-2026-11-03-05-PM.jpg">'
    +'<div class="brand-text"><h1>Strategy<span>.</span></h1><p>HR Solutions</p></div>'
    +'<div class="brand-actions">'
    +'<button class="btn btn-g" onclick="S.view=\'main\';render();">← العودة</button>'
    +'<button class="btn btn-p" onclick="openAddEmp()">+ موظف جديد</button>'
    +'</div></div>'
    +'<div style="display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-bottom:24px;">'
    +'<div class="stat" style="border-color:#6366F120;"><div style="font-size:22px;">👥</div><div class="stat-n" style="color:#6366F1;">'+emps.length+'</div><div class="stat-l">إجمالي الموظفين</div></div>'
    +'<div class="stat" style="border-color:#22C55E20;"><div style="font-size:22px;">✅</div><div class="stat-n" style="color:#22C55E;">'+active+'</div><div class="stat-l">داخل العمل</div></div>'
    +'<div class="stat" style="border-color:#EB070520;"><div style="font-size:22px;">⏸</div><div class="stat-n" style="color:#EB0705;">'+inactive+'</div><div class="stat-l">خارج العمل</div></div>'
    +'</div>'
    +'<div style="display:flex;gap:12px;margin-bottom:20px;flex-wrap:wrap;">'
    +'<input class="inp" id="empQ" placeholder="🔍 ابحث بالاسم، الكود، أو الرقم القومي..." value="'+(S._empQ||'')+'" oninput="S._empQ=this.value;render();" style="flex:1 1 200px;">'
    +'<select class="inp" style="flex:0 0 auto;width:auto;min-width:135px;" onchange="S._empSF=this.value;render();">'
    +'<option value="الكل"'+(sf==='الكل'?' selected':'')+'>الكل — الحالة</option>'
    +'<option value="داخل العمل"'+(sf==='داخل العمل'?' selected':'')+'>داخل العمل</option>'
    +'<option value="خارج العمل"'+(sf==='خارج العمل'?' selected':'')+'>خارج العمل</option>'
    +'</select>'
    +'<select class="inp" style="flex:0 0 auto;width:auto;min-width:140px;" onchange="S._empDF=this.value;render();">';
  usedDepts.forEach(function(d){ html += '<option value="'+d+'"'+(df===d?' selected':'')+'>'+(d==='الكل'?'الكل — القسم':d)+'</option>'; });
  html += '</select></div>';

  if(S.loadingEmps){
    html += '<div class="card" style="padding:60px;text-align:center;"><p style="color:var(--sub);">⏳ جارٍ التحميل...</p></div>';
  } else {
    html += '<div class="card" style="overflow:hidden;">';
    if(filtered.length===0){
      html += '<div style="padding:56px;text-align:center;"><div style="font-size:44px;margin-bottom:16px;">'+(emps.length===0?'👤':'🔍')+'</div>'
        +'<p style="color:var(--sub);margin:0;font-size:16px;">'+(emps.length===0?'لا يوجد موظفون — أضف موظفاً جديداً':'لا توجد نتائج')+'</p></div>';
    } else {
      html += '<div class="tbl-wrap" style="max-height:64vh;overflow-y:auto;"><table class="tbl"><thead style="position:sticky;top:0;z-index:5;"><tr><th style="width:3%;">#</th><th style="width:10%;">الكود</th><th style="width:16%;">الاسم</th><th style="width:14%;">الوظيفة</th><th style="width:12%;">القسم</th><th style="width:12%;">الإدارة</th><th style="width:10%;">الحالة</th><th style="width:12%;">الراتب</th></tr></thead><tbody>';
      filtered.forEach(function(emp, idx){
        var code = emp.name.charCodeAt(0)*37%360;
        var avColor = 'hsl('+code+',60%,55%)';
        var total = emp.totalSalary || 0;
        html += '<tr onclick="selectEmp(\''+encodeURIComponent(emp.employeeCode)+'\')">'
          +'<td style="color:var(--sub);font-size:11px;font-weight:700;">'+(idx+1)+'</td>'
          +'<td style="font-weight:700;color:var(--primary);">'+esc(emp.employeeCode||'—')+'</td>'
          +'<td><div style="display:flex;align-items:center;gap:10px;"><div class="av" style="width:36px;height:36px;background:'+avColor+';font-size:14px;">'+emp.name.charAt(0)+'</div><span style="font-weight:700;">'+esc(emp.name)+'</span></div></td>'
          +'<td style="color:var(--sub);">'+esc(emp.job||'')+'</td>'
          +'<td>'+(emp.department?'<span class="b-dept">'+esc(emp.department)+'</span>':'')+'</td>'
          +'<td style="color:var(--sub);">'+esc(emp.administration||'')+'</td>'
          +'<td><span class="badge '+(emp.status==='داخل العمل'?'b-in':'b-out')+'">'+(emp.status==='داخل العمل'?'● داخل':'○ خارج')+'</span></td>'
          +'<td style="font-weight:700;color:var(--primary);">'+Number(total).toLocaleString()+' ج.م</td>'
          +'</tr>';
      });
      html += '</tbody></table></div>';
    }
    html += '</div>';
  }
  html += '</div>';
  return html;
}

function loadEmployees(){
  S.loadingEmps = true;
  render();
  gas({ action: 'getEmployees' }, function(r){
    S.loadingEmps = false;
    if (r && r.employees) {
      S.employees = r.employees;
    } else {
      S.employees = [];
      toast('⚠️ فشل جلب الموظفين', false);
    }
    render();
  });
}

function showEmployees(){ S.view='employees'; loadEmployees(); }

function selectEmp(enc){
  var employeeCode = decodeURIComponent(enc);
  S.selectedEmp = S.employees.find(function(e){ return e.employeeCode === employeeCode; }) || null;
  S.modal = 'empDetail';
  render();
}

function openAddEmp(){
  if (!S.dropdownsLoaded && !S.dropdownsLoading) {
    toast('⏳ جارٍ تحميل البيانات من الشيت...', true);
    loadDropdownData().then(function(){ openAddEmp(); });
    return;
  }
  if (S.dropdownsLoading) {
    toast('⏳ جارٍ التحميل، انتظر قليلاً...', true);
    return;
  }
  if (S.dropdownsError) {
    toast('⚠️ استخدام قوائم افتراضية مؤقتة', false);
  }

  S.modal = 'addEmp';
  S._empForm = {
    employeeCode: '', name: '', job: '', department: '', administration: '',
    status: 'داخل العمل', hireDate: '', phone: '', email: '', notes: '',
    nationalId: '', governorate: '', basicSalary: 0, allowances: {}
  };
  S.allowanceValues = {};
  loadAllowances().then(function(){
    S.allowances.forEach(function(allowName){
      S.allowanceValues[allowName] = 0;
    });
    renderModal();
  }).catch(function(){
    if (S.allowances.length === 0) {
      S.allowances = ['بدل نقل', 'بدل سكن', 'بدل غذاء', 'بدل تدريب', 'بدل خطر'];
      S.allowances.forEach(function(allowName){
        S.allowanceValues[allowName] = 0;
      });
    }
    renderModal();
  });
}

function saveEmployee(){
  var employeeCode = document.getElementById('fEmployeeCode') ? document.getElementById('fEmployeeCode').value.trim() : '';
  var name = document.getElementById('fN') ? document.getElementById('fN').value.trim() : '';
  var job = document.getElementById('fJob') ? document.getElementById('fJob').value : '';
  var department = document.getElementById('fDept') ? document.getElementById('fDept').value : '';
  var administration = document.getElementById('fAdmin') ? document.getElementById('fAdmin').value : '';
  var status = document.getElementById('fStatus') ? document.getElementById('fStatus').value : 'داخل العمل';
  var hireDate = document.getElementById('fHire') ? document.getElementById('fHire').value : '';
  var phone = document.getElementById('fPhone') ? document.getElementById('fPhone').value.trim() : '';
  var email = document.getElementById('fEmail') ? document.getElementById('fEmail').value.trim() : '';
  var notes = document.getElementById('fNotes') ? document.getElementById('fNotes').value.trim() : '';
  var nationalId = document.getElementById('fNationalId') ? document.getElementById('fNationalId').value.trim() : '';
  var governorate = document.getElementById('fGovernorate') ? document.getElementById('fGovernorate').value.trim() : '';
  var basicSalary = parseFloat(document.getElementById('fBasicSalary') ? document.getElementById('fBasicSalary').value : 0) || 0;

  if(!name){ toast('⚠️ الاسم مطلوب', false); return; }
  if(!employeeCode){ toast('⚠️ كود الموظف مطلوب', false); return; }
  if(nationalId && nationalId.length !== 14) {
    toast('⚠️ الرقم القومي يجب أن يكون 14 رقم', false);
    return;
  }

  var ageInfo = { age: null, gender: null, valid: true };
  if (nationalId) {
    ageInfo = extractAgeAndGender(nationalId);
    if (!ageInfo.valid) {
      toast('⚠️ الرقم القومي غير صحيح', false);
      return;
    }
  }

  var allowances = {};
  S.allowances.forEach(function(allowName){
    var val = parseFloat(document.getElementById('allow_'+allowName) ? document.getElementById('allow_'+allowName).value : 0) || 0;
    allowances[allowName] = val;
  });

  var totalAllowances = Object.values(allowances).reduce(function(a,b){ return a + b; }, 0);
  var totalSalary = basicSalary + totalAllowances;

  var empData = {
    employeeCode: employeeCode,
    name: name,
    job: job,
    department: department,
    administration: administration,
    status: status,
    hireDate: hireDate,
    phone: phone,
    email: email,
    notes: notes,
    nationalId: nationalId,
    governorate: governorate,
    basicSalary: basicSalary,
    allowances: allowances,
    gender: ageInfo.gender || '',
    age: ageInfo.age || '',
    totalSalary: totalSalary
  };

  closeModal();
  S.loadingEmps = true;
  render();
  gas({ action: 'addEmployee', ...empData }, function(res){
    S.loadingEmps = false;
    toast(res.error ? '⚠️ فشل الحفظ' : '✅ تم إضافة الموظف', !res.error);
    loadEmployees();
  });
}

function renderModalEmpDetail(){
  var emp = S.selectedEmp;
  if(!emp) return '';
  var code = emp.name.charCodeAt(0)*37%360;
  var rows = [
    {l:'كود الموظف', v:emp.employeeCode||'—', i:'🆔'},
    {l:'الرقم القومي', v:emp.nationalId||'—', i:'🪪'},
    {l:'محافظة السكن', v:emp.governorate||'—', i:'🏠'},
    {l:'النوع', v:emp.gender||'—', i:'👤'},
    {l:'العمر', v:emp.age ? emp.age + ' سنة' : '—', i:'🎂'},
    {l:'الوظيفة', v:emp.job||'—', i:'💼'},
    {l:'القسم', v:emp.department||'—', i:'🏢'},
    {l:'الإدارة', v:emp.administration||'—', i:'📋'},
    {l:'الراتب الأساسي', v:emp.basicSalary ? Number(emp.basicSalary).toLocaleString() + ' ج.م' : '—', i:'💰'},
    {l:'إجمالي الراتب', v:emp.totalSalary ? Number(emp.totalSalary).toLocaleString() + ' ج.م' : '—', i:'💵'},
    {l:'تاريخ التعيين', v:emp.hireDate||'—', i:'📅'},
    {l:'رقم الهاتف', v:emp.phone||'—', i:'📞'},
    {l:'البريد الإلكتروني', v:emp.email||'—', i:'📧', full:true},
    {l:'ملاحظات', v:emp.notes||'—', i:'📝', full:true}
  ];
  var allowancesHtml = '';
  if (emp.allowances && typeof emp.allowances === 'object') {
    var allowKeys = Object.keys(emp.allowances);
    if (allowKeys.length > 0) {
      allowancesHtml = '<div style="background:var(--card);border-radius:var(--r2);padding:14px 16px;border:1px solid var(--border);margin-top:8px;">'
        +'<p style="margin:0 0 6px;font-size:11px;color:var(--sub);font-weight:700;">📋 البدلات</p>';
      allowKeys.forEach(function(key){
        allowancesHtml += '<div style="display:flex;justify-content:space-between;font-size:13px;padding:2px 0;border-bottom:1px dashed var(--border);">'
          +'<span>'+esc(key)+'</span>'
          +'<span style="font-weight:600;">'+Number(emp.allowances[key]).toLocaleString()+' ج.م</span>'
          +'</div>';
      });
      allowancesHtml += '</div>';
    }
  }

  var infoHtml = '<div class="g2" style="margin-bottom:20px;">';
  rows.forEach(function(r){
    infoHtml += '<div'+(r.full?' class="full"':'')+' style="background:var(--card);border-radius:var(--r2);padding:14px 16px;border:1px solid var(--border);">'
      +'<p style="margin:0 0 4px;font-size:11px;color:var(--sub);font-weight:700;letter-spacing:0.5px;">'+r.i+' '+r.l+'</p>'
      +'<p style="margin:0;font-size:14px;font-weight:600;">'+esc(r.v)+'</p></div>';
  });
  infoHtml += '</div>';
  if (allowancesHtml) infoHtml += allowancesHtml;

  var isIn = emp.status === 'داخل العمل';
  var statusBtnText = isIn ? 'تحويل لخارج' : 'تحويل لداخل';
  var statusBtnClass = isIn ? 'btn-d' : 'btn-s';
  return '<div class="overlay" onclick="closeModal()"><div class="modal" onclick="event.stopPropagation();">'
    +'<div style="display:flex;align-items:center;gap:16px;margin-bottom:24px;">'
    +'<div class="av" style="width:64px;height:64px;background:hsl('+code+',60%,55%);font-size:26px;box-shadow:0 6px 24px rgba(0,0,0,.10);">'+emp.name.charAt(0)+'</div>'
    +'<div><h3 style="margin:0 0 4px;font-size:20px;font-weight:800;font-family:\'El Messiri\',serif;">'+esc(emp.name)+'</h3>'
    +'<p style="margin:0;font-size:13px;color:var(--sub);">'+esc(emp.job||'')+(emp.department?' — '+esc(emp.department):'')+(emp.administration?' — '+esc(emp.administration):'')+'</p></div>'
    +'</div>'
    +'<div style="background:'+(isIn?'rgba(34,197,94,.05)':'rgba(235,7,5,.05)')+';border-radius:var(--r2);padding:16px 20px;margin-bottom:20px;display:flex;align-items:center;justify-content:space-between;gap:12px;border:1px solid '+(isIn?'rgba(34,197,94,.12)':'rgba(235,7,5,.12)')+';">'
    +'<div><p style="margin:0 0 4px;font-size:11px;color:var(--sub);font-weight:700;">الحالة الحالية</p>'
    +'<span class="badge '+(isIn?'b-in':'b-out')+'" style="font-size:13px;">'+(isIn?'داخل العمل':'خارج العمل')+'</span></div>'
    +'<button class="btn '+statusBtnClass+'" onclick="toggleEmpStatus()" style="padding:8px 20px;font-size:12px;border-radius:var(--r2);">'+statusBtnText+'</button>'
    +'</div>'
    +infoHtml
    +'<div style="display:flex;gap:12px;">'
    +'<button class="btn btn-g" onclick="closeModal()" style="flex:1;padding:12px;font-size:13px;">إغلاق</button>'
    +'<button class="btn btn-d" onclick="deleteEmp()" style="padding:12px 24px;font-size:13px;border-radius:var(--r2);">🗑 حذف</button>'
    +'</div></div></div>';
}

function toggleEmpStatus(){
  var emp = S.selectedEmp;
  if(!emp) return;
  var newStatus = (emp.status === 'داخل العمل') ? 'خارج العمل' : 'داخل العمل';
  var confirmMsg = (newStatus === 'خارج العمل') ?
    'هل أنت متأكد من نقل الموظف "' + emp.name + '" إلى خارج العمل؟' :
    'هل أنت متأكد من نقل الموظف "' + emp.name + '" إلى داخل العمل؟';
  if(!confirm(confirmMsg)) return;
  closeModal();
  S.loadingEmps = true;
  render();
  gas({ action: 'updateEmployeeStatus', employeeCode: emp.employeeCode, newStatus: newStatus }, function(res){
    S.loadingEmps = false;
    if (res.error) {
      toast('⚠️ فشل النقل: ' + res.error, false);
    } else {
      toast('✅ تم نقل الموظف إلى ' + newStatus, true);
      loadEmployees();
    }
  });
}

function deleteEmp(){
  var emp = S.selectedEmp;
  if(!emp || !confirm('هل تريد حذف الموظف "'+emp.name+'"؟')) return;
  closeModal();
  S.loadingEmps = true;
  render();
  gas({ action: 'deleteEmployee', employeeCode: emp.employeeCode }, function(res){
    S.loadingEmps = false;
    if (res.error) {
      toast('⚠️ فشل الحذف: ' + res.error, false);
    } else {
      toast('✅ تم حذف الموظف', true);
      loadEmployees();
    }
  });
}

/* ============================================================
   دوال المودالات
   ============================================================ */
function renderModal(){
  var el = document.getElementById('modal-host');
  if(!el){ el = document.createElement('div'); el.id='modal-host'; document.body.appendChild(el); }
  if(!S.modal){ el.innerHTML=''; return; }
  if(S.modal==='newCat')          el.innerHTML=renderModalNewCat();
  else if(S.modal==='newItem')    el.innerHTML=renderModalNewItem();
  else if(S.modal==='addEmp')     el.innerHTML=renderModalAddEmp();
  else if(S.modal==='empDetail')  el.innerHTML=renderModalEmpDetail();
  else if(S.modal==='previewTemplate') el.innerHTML=renderModalPreviewTemplate();
}

function closeModal(){ S.modal = null; render(); }

function renderModalNewCat(){
  var tplBtns='';
  TEMPLATES.forEach(function(t){
    var sel=(S._newCatName===t.name);
    tplBtns+='<button class="tpl-btn'+(sel?' sel':'')+'" onclick="S._newCatName=\''+t.name+'\';renderModal();document.getElementById(\'newCatInp\').value=\''+t.name+'\';" style="border-color:'+t.col+(sel?'\';color:'+t.col:'')+'40;">'
      +'<span style="font-size:24px;">'+t.icon+'</span>'+t.name+'</button>';
  });
  return '<div class="overlay" onclick="closeModal()"><div class="modal" onclick="event.stopPropagation();">'
    +'<h3 style="margin:0 0 16px;font-size:18px;font-weight:800;color:var(--primary);font-family:\'El Messiri\',serif;">📋 اسم اللائحة الجديدة</h3>'
    +'<p style="font-size:13px;color:var(--sub);margin-bottom:14px;">اختر من القوالب الجاهزة أو اكتب اسماً مخصصاً</p>'
    +'<div class="tpl-grid" style="margin-bottom:20px;">'+tplBtns+'</div>'
    +'<hr class="div">'
    +'<label style="font-size:13px;font-weight:700;display:block;margin-bottom:8px;">اسم مخصص</label>'
    +'<input class="inp" id="newCatInp" placeholder="مثال: لائحة الرواتب والبدلات" value="'+(S._newCatName||'')+'" oninput="S._newCatName=this.value;">'
    +'<div style="display:flex;gap:12px;margin-top:22px;">'
    +'<button class="btn btn-p" onclick="saveNewCat()" style="flex:1;padding:12px;font-size:14px;">إضافة اللائحة</button>'
    +'<button class="btn btn-g" onclick="closeModal()" style="padding:12px 24px;font-size:14px;">إلغاء</button>'
    +'</div></div></div>';
}

function saveNewCat(){
  var name = (S._newCatName||'').trim();
  if(!name) return;
  closeModal();
  gas({ action: 'addPolicyItem', category: name, violation: '(بند تجريبي — يمكن تعديله)', punishment: '-', repeat: '-' }, function(){
    loadPolicies();
    S.expandedCat = name;
  });
}

function renderModalNewItem(){
  var t = tplFor(S.addItemCat||'');
  return '<div class="overlay" onclick="closeModal()"><div class="modal" onclick="event.stopPropagation();">'
    +'<h3 style="margin:0 0 4px;font-size:18px;font-weight:800;color:var(--primary);font-family:\'El Messiri\',serif;">'+t.icon+' إضافة بند جديد</h3>'
    +'<p style="margin:0 0 24px;font-size:13px;color:var(--sub);">'+esc(S.addItemCat||'')+'</p>'
    +'<div style="display:flex;flex-direction:column;gap:16px;">'
    +'<div><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">المخالفة <span style="color:var(--primary);">*</span></label>'
    +'<input class="inp" id="iV" placeholder="مثال: التأخير عن مواعيد العمل" value="'+esc(S._item&&S._item.v?S._item.v:'')+'" oninput="S._item.v=this.value;"></div>'
    +'<div><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">العقوبة</label>'
    +'<input class="inp" id="iP" placeholder="مثال: إنذار كتابي أو خصم يوم" value="'+esc(S._item&&S._item.p?S._item.p:'')+'" oninput="S._item.p=this.value;"></div>'
    +'<div><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">في حالة التكرار</label>'
    +'<input class="inp" id="iR" placeholder="مثال: خصم 3 أيام" value="'+esc(S._item&&S._item.r?S._item.r:'')+'" oninput="S._item.r=this.value;"></div>'
    +'</div>'
    +'<div style="display:flex;gap:12px;margin-top:24px;">'
    +'<button class="btn btn-p" onclick="savePolicyItem()" style="flex:1;padding:12px;font-size:14px;">حفظ البند</button>'
    +'<button class="btn btn-g" onclick="closeModal()" style="padding:12px 24px;font-size:14px;">إلغاء</button>'
    +'</div></div></div>';
}

function savePolicyItem(){
  var v = (S._item&&S._item.v) || document.getElementById('iV').value;
  var p = (S._item&&S._item.p) || document.getElementById('iP').value;
  var r = (S._item&&S._item.r) || document.getElementById('iR').value;
  if(!v.trim()) return;
  var cat = S.addItemCat;
  closeModal();
  gas({ action: 'addPolicyItem', category: cat, violation: v, punishment: p, repeat: r }, function(res){
    toast(res.error ? '⚠️ فشل الحفظ' : '✅ تم حفظ البند', !res.error);
    loadPolicies();
    S.expandedCat = cat;
  });
}

/* ============================================================
   مودال إضافة موظف – مع قوائم من الشيت
   ============================================================ */
function renderModalAddEmp(){
  var f = S._empForm || {};
  var jobOpts = '<option value="">اختر الوظيفة</option>';
  if (S.jobs && S.jobs.length > 0) {
    S.jobs.forEach(function(job){
      jobOpts += '<option value="'+esc(job)+'"'+(f.job===job?' selected':'')+'>'+esc(job)+'</option>';
    });
  } else {
    jobOpts += '<option value="">لا توجد بيانات</option>';
  }
  var deptOpts = '<option value="">اختر القسم</option>';
  if (S.departments && S.departments.length > 0) {
    S.departments.forEach(function(dept){
      deptOpts += '<option value="'+esc(dept)+'"'+(f.department===dept?' selected':'')+'>'+esc(dept)+'</option>';
    });
  } else {
    deptOpts += '<option value="">لا توجد بيانات</option>';
  }
  var adminOpts = '<option value="">اختر الإدارة</option>';
  if (S.administrations && S.administrations.length > 0) {
    S.administrations.forEach(function(admin){
      adminOpts += '<option value="'+esc(admin)+'"'+(f.administration===admin?' selected':'')+'>'+esc(admin)+'</option>';
    });
  } else {
    adminOpts += '<option value="">لا توجد بيانات</option>';
  }

  var allowancesHtml = '';
  S.allowances.forEach(function(allowName){
    var val = S.allowanceValues[allowName] || 0;
    allowancesHtml += '<div style="display:flex;gap:10px;align-items:center;margin-bottom:6px;">'
      +'<label style="font-size:13px;font-weight:600;width:120px;">'+esc(allowName)+'</label>'
      +'<input class="inp" type="number" id="allow_'+esc(allowName)+'" value="'+val+'" step="0.01" style="flex:1;" onchange="S.allowanceValues[\''+esc(allowName)+'\']=parseFloat(this.value)||0; updateTotalSalary();">'
      +'</div>';
  });

  return '<div class="overlay" onclick="closeModal()"><div class="modal" onclick="event.stopPropagation();" style="max-width:750px;">'
    +'<h3 style="margin:0 0 24px;font-size:20px;font-weight:800;color:var(--primary);font-family:\'El Messiri\',serif;">👤 إضافة موظف جديد</h3>'
    +'<div class="g2">'
    +'<div class="full"><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">كود الموظف <span style="color:var(--primary);">*</span></label>'
    +'<input class="inp" id="fEmployeeCode" placeholder="مثال: EMP-001" value="'+esc(f.employeeCode||'')+'" oninput="S._empForm.employeeCode=this.value;"></div>'
    +'<div class="full"><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">الاسم الكامل <span style="color:var(--primary);">*</span></label><input class="inp" id="fN" placeholder="محمد أحمد" value="'+esc(f.name||'')+'" oninput="S._empForm.name=this.value;"></div>'
    +'<div><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">الوظيفة</label><select class="inp" id="fJob" onchange="S._empForm.job=this.value;">'+jobOpts+'</select></div>'
    +'<div><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">القسم</label><select class="inp" id="fDept" onchange="S._empForm.department=this.value;">'+deptOpts+'</select></div>'
    +'<div><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">الإدارة</label><select class="inp" id="fAdmin" onchange="S._empForm.administration=this.value;">'+adminOpts+'</select></div>'
    +'<div><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">الحالة</label><select class="inp" id="fStatus" onchange="S._empForm.status=this.value;"><option value="داخل العمل">داخل العمل</option><option value="خارج العمل">خارج العمل</option></select></div>'
    +'<div><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">تاريخ التعيين</label><input class="inp" type="date" id="fHire" value="'+(f.hireDate||'')+'" onchange="S._empForm.hireDate=this.value;"></div>'
    +'<div><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">رقم الهاتف</label><input class="inp" id="fPhone" placeholder="05xxxxxxxx" value="'+esc(f.phone||'')+'" oninput="S._empForm.phone=this.value;"></div>'
    +'<div class="full"><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">البريد الإلكتروني</label><input class="inp" type="email" id="fEmail" placeholder="example@company.com" value="'+esc(f.email||'')+'" oninput="S._empForm.email=this.value;"></div>'
    +'<div class="full"><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">ملاحظات</label><textarea class="inp" id="fNotes" placeholder="أي ملاحظات إضافية..." oninput="S._empForm.notes=this.value;">'+esc(f.notes||'')+'</textarea></div>'
    +'</div>'
    +'<hr class="div">'
    +'<div class="g2">'
    +'<div class="full"><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">الرقم القومي (14 رقم)</label>'
    +'<input class="inp" id="fNationalId" placeholder="مثال: 29901011234567" maxlength="14" value="'+esc(f.nationalId||'')+'" oninput="this.value=this.value.replace(/\\D/g,\'\').slice(0,14); S._empForm.nationalId=this.value; extractFromNationalId();">'
    +'<div id="ageGenderDisplay" style="font-size:13px;color:var(--sub);margin-top:4px;"></div>'
    +'</div>'
    +'<div><label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">محافظة السكن</label>'
    +'<input class="inp" id="fGovernorate" placeholder="القاهرة" value="'+esc(f.governorate||'')+'" oninput="S._empForm.governorate=this.value;"></div>'
    +'</div>'
    +'<div style="margin-top:16px;">'
    +'<label style="font-size:13px;font-weight:700;display:block;margin-bottom:6px;">الراتب الأساسي</label>'
    +'<input class="inp" type="number" id="fBasicSalary" placeholder="0" step="0.01" value="'+(f.basicSalary||0)+'" onchange="S._empForm.basicSalary=parseFloat(this.value)||0; updateTotalSalary();">'
    +'</div>'
    +'<div style="margin-top:16px;">'
    +'<label style="font-size:13px;font-weight:700;display:block;margin-bottom:8px;">البدلات</label>'
    +'<div style="background:var(--card);border-radius:var(--r2);padding:12px 16px;border:1px solid var(--border);">'
    +allowancesHtml
    +'</div>'
    +'<div style="display:flex;justify-content:space-between;font-weight:700;font-size:16px;margin-top:10px;padding:8px 12px;background:rgba(235,7,5,0.05);border-radius:var(--r2);">'
    +'<span>إجمالي الراتب</span>'
    +'<span id="totalSalaryDisplay" style="color:var(--primary);">0 ج.م</span>'
    +'</div>'
    +'</div>'
    +'<div style="display:flex;gap:12px;margin-top:24px;">'
    +'<button class="btn btn-p" onclick="saveEmployee()" style="flex:1;padding:12px;font-size:14px;">💾 حفظ الموظف</button>'
    +'<button class="btn btn-g" onclick="closeModal()" style="padding:12px 24px;font-size:14px;">إلغاء</button>'
    +'</div></div></div>';
}

/* ===== دوال مساعدة ===== */
function extractFromNationalId() {
  var id = document.getElementById('fNationalId') ? document.getElementById('fNationalId').value : '';
  var display = document.getElementById('ageGenderDisplay');
  if (!display) return;
  if (id.length === 14 && /^\d{14}$/.test(id)) {
    var info = extractAgeAndGender(id);
    if (info.valid) {
      display.innerHTML = '👤 النوع: '+info.gender+' | 🎂 العمر: '+info.age+' سنة';
      display.style.color = 'var(--text)';
    } else {
      display.innerHTML = '⚠️ الرقم غير صحيح';
      display.style.color = 'var(--primary)';
    }
  } else {
    display.innerHTML = '';
  }
}

function updateTotalSalary() {
  var basic = parseFloat(document.getElementById('fBasicSalary') ? document.getElementById('fBasicSalary').value : 0) || 0;
  var totalAllow = 0;
  S.allowances.forEach(function(allowName){
    var val = parseFloat(document.getElementById('allow_'+allowName) ? document.getElementById('allow_'+allowName).value : 0) || 0;
    totalAllow += val;
  });
  var total = basic + totalAllow;
  var display = document.getElementById('totalSalaryDisplay');
  if (display) {
    display.textContent = total.toLocaleString() + ' ج.م';
  }
}

function esc(s){ return String(s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;'); }

// ============================================================
//  ★★★ التحميل الأولي – في الخلفية بدون رسائل ★★★
// ============================================================
// <<<<<<< تعديل: تحميل القوائم بصمت (silent = true)
loadDropdownData(true).catch(function(e){
  console.error('فشل تحميل البيانات من الشيت:', e);
  S.dropdownsLoaded = true;
  S.dropdownsError = true;
});

// باقي التهيئة (كلمة المرور وعرض الصفحة)
render();
gas({ action: 'getPassword' }, function(r){ S.pass = r.password || ''; render(); });
</script>
</body>
</html>
