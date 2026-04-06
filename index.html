# AI-for-Thesis
<!DOCTYPE html>
<html lang="cs">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AI Asistent — Smart Cities DP</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;1,300&family=Outfit:wght@200;300;400;500&display=swap');
 
*, *::before, *::after { margin:0; padding:0; box-sizing:border-box; }
 
:root {
  --bg:    #06101e;
  --bg2:   #0a1628;
  --blue1: #4fc3f7;
  --blue2: #81d4fa;
  --teal:  #26c6da;
  --white: #e8f4fd;
  --muted: #5b8fa8;
  --bdr:   rgba(79,195,247,0.18);
  --card:  rgba(10,22,40,0.9);
}
 
html, body { height:100%; }
 
body {
  background: var(--bg);
  color: var(--white);
  font-family: 'Outfit', sans-serif;
  font-weight: 300;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
 
canvas#bgc {
  position: fixed; inset:0; z-index:0; pointer-events:none;
}
 
/* NAV */
nav {
  position: relative; z-index:10;
  display: flex; justify-content:space-between; align-items:center;
  padding: 1.2rem 2.5rem;
  background: rgba(6,16,30,0.8);
  backdrop-filter: blur(20px);
  border-bottom: 1px solid var(--bdr);
  flex-shrink:0;
}
.nav-logo {
  font-family:'Cormorant Garamond',serif;
  font-size:1rem; color:var(--blue1); letter-spacing:.1em;
}
.nav-sub { font-size:.6rem; color:var(--muted); letter-spacing:.25em; text-transform:uppercase; }
 
/* MAIN */
main {
  position:relative; z-index:10;
  flex:1;
  display:flex;
  flex-direction:column;
  max-width: 860px;
  width:100%;
  margin: 0 auto;
  padding: 2rem 1.5rem 1rem;
  gap: 1.5rem;
}
 
/* INTRO */
.intro {
  text-align:center;
  padding: 1.5rem 0 .5rem;
}
.intro h1 {
  font-family:'Cormorant Garamond',serif;
  font-size:clamp(1.8rem,4vw,3rem);
  font-weight:300; line-height:1.1;
  margin-bottom:.8rem;
}
.intro h1 em { font-style:italic; color:var(--blue1); }
.intro p {
  font-size:.82rem; color:var(--muted); line-height:1.8;
  max-width:500px; margin:0 auto;
}
 
/* QUICK QUESTIONS */
.quick-wrap {
  display:flex; flex-wrap:wrap; gap:.5rem; justify-content:center;
}
.q-chip {
  font-size:.65rem; letter-spacing:.08em;
  padding:.4rem .9rem;
  border:1px solid var(--bdr);
  color:var(--muted);
  border-radius:20px;
  cursor:pointer;
  transition: border-color .3s, color .3s;
  background: transparent;
  font-family:'Outfit',sans-serif;
}
.q-chip:hover { border-color:var(--blue1); color:var(--blue1); }
 
/* CHAT */
.chat-wrap {
  flex:1;
  display:flex;
  flex-direction:column;
  gap:.75rem;
  overflow-y:auto;
  padding-right:.25rem;
  min-height:200px;
  max-height:calc(100vh - 420px);
}
 
.chat-wrap::-webkit-scrollbar { width:4px; }
.chat-wrap::-webkit-scrollbar-thumb { background:var(--bdr); border-radius:2px; }
 
.msg {
  display:flex;
  gap:.75rem;
  max-width:100%;
  animation: msgIn .4s ease;
}
@keyframes msgIn { from{opacity:0;transform:translateY(8px);} to{opacity:1;transform:translateY(0);} }
 
.msg.user { flex-direction:row-reverse; }
 
.msg-avatar {
  width:32px; height:32px; border-radius:50%;
  display:flex; align-items:center; justify-content:center;
  font-size:.75rem; flex-shrink:0;
  border: 1px solid var(--bdr);
}
.msg.user .msg-avatar { background:rgba(79,195,247,.12); color:var(--blue1); }
.msg.ai .msg-avatar   { background:rgba(38,198,218,.12); color:var(--teal); }
 
.msg-bubble {
  max-width:78%;
  padding:.8rem 1rem;
  border-radius:2px;
  font-size:.83rem;
  line-height:1.85;
  border: 1px solid var(--bdr);
}
.msg.user .msg-bubble {
  background:rgba(79,195,247,.08);
  border-color:rgba(79,195,247,.2);
  text-align:right;
}
.msg.ai .msg-bubble {
  background: var(--card);
}
 
.msg-bubble strong { color:var(--blue2); font-weight:500; }
.msg-bubble em     { font-style:italic; color:var(--teal); }
 
/* typing indicator */
.typing-dots { display:flex; gap:4px; padding:.3rem 0; }
.typing-dots span {
  width:6px; height:6px; border-radius:50%;
  background:var(--muted);
  animation:dot 1.2s ease-in-out infinite;
}
.typing-dots span:nth-child(2){animation-delay:.2s;}
.typing-dots span:nth-child(3){animation-delay:.4s;}
@keyframes dot{0%,80%,100%{transform:scale(.6);opacity:.4;}40%{transform:scale(1);opacity:1;}}
 
/* INPUT */
.input-area {
  display:flex;
  gap:.6rem;
  background: var(--card);
  border:1px solid var(--bdr);
  border-radius:2px;
  padding:.6rem .8rem;
  flex-shrink:0;
}
.input-area:focus-within {
  border-color:rgba(79,195,247,.4);
}
 
#userInput {
  flex:1;
  background:transparent;
  border:none;
  outline:none;
  color:var(--white);
  font-family:'Outfit',sans-serif;
  font-size:.85rem;
  font-weight:300;
  resize:none;
  line-height:1.5;
  max-height:120px;
  min-height:36px;
}
#userInput::placeholder { color:var(--muted); opacity:.6; }
 
#sendBtn {
  background:rgba(79,195,247,.12);
  border:1px solid rgba(79,195,247,.25);
  color:var(--blue1);
  width:36px; height:36px; border-radius:2px;
  cursor:pointer;
  display:flex; align-items:center; justify-content:center;
  flex-shrink:0;
  transition:background .2s;
  align-self:flex-end;
}
#sendBtn:hover { background:rgba(79,195,247,.22); }
#sendBtn svg { width:16px; height:16px; }
#sendBtn:disabled { opacity:.35; cursor:default; }
 
/* footer note */
.foot-note {
  text-align:center;
  font-size:.58rem;
  color:var(--muted);
  opacity:.5;
  padding-bottom:1rem;
  flex-shrink:0;
}
</style>
</head>
<body>
 
<canvas id="bgc"></canvas>
 
<nav>
  <div>
    <div class="nav-logo">Smart Cities AI</div>
    <div class="nav-sub">Bc. Martin Beránek · ČZU Praha 2026</div>
  </div>
  <div style="font-size:.6rem;color:var(--muted);text-align:right;line-height:1.6;">
    Politiky a strategie EU<br>pro podporu Smart Cities
  </div>
</nav>
 
<main>
  <div class="intro">
    <h1>Zeptej se na <em>svoji</em><br>diplomovou práci</h1>
    <p>AI asistent zná celý obsah tvé DP. Ptej se na cokoliv — definice, srovnání ČR vs. Francie, metodiku, závěry…</p>
  </div>
 
  <div class="quick-wrap" id="quickWrap">
    <button class="q-chip">Co je Smart City?</button>
    <button class="q-chip">Jaký je rozdíl ČR vs. Francie?</button>
    <button class="q-chip">Co je France 2030?</button>
    <button class="q-chip">Co je Lab2051?</button>
    <button class="q-chip">Jaká jsou doporučení práce?</button>
    <button class="q-chip">Co jsou regulační pískoviště?</button>
    <button class="q-chip">Jaká je metodika práce?</button>
    <button class="q-chip">Co je index dotační závislosti?</button>
  </div>
 
  <div class="chat-wrap" id="chat"></div>
 
  <div class="input-area">
    <textarea id="userInput" placeholder="Napiš otázku k diplomové práci…" rows="1"></textarea>
    <button id="sendBtn" title="Odeslat">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <line x1="22" y1="2" x2="11" y2="13"></line>
        <polygon points="22 2 15 22 11 13 2 9 22 2"></polygon>
      </svg>
    </button>
  </div>
 
  <div class="foot-note">AI odpovídá pouze z obsahu tvé diplomové práce · Bc. Martin Beránek 2026</div>
</main>
 
<script>
/* ══ BACKGROUND BUBBLES ══ */
(function(){
  const c=document.getElementById('bgc'),ctx=c.getContext('2d');
  let W,H,balls=[];
  function resize(){W=c.width=innerWidth;H=c.height=innerHeight;}
  resize(); addEventListener('resize',()=>{resize();init();});
  function rnd(a,b){return a+Math.random()*(b-a);}
  function init(){
    balls=[];
    const n=Math.floor(W*H/22000);
    for(let i=0;i<n;i++){
      const r=rnd(1.5,14);
      balls.push({x:rnd(0,W),y:rnd(0,H),r,vx:rnd(-.08,.08),vy:rnd(-.12,.04),a:rnd(.03,.18),ph:rnd(0,Math.PI*2),sp:rnd(.004,.012),hue:rnd(190,220),depth:rnd(.2,1)});
    }
  }
  let f=0;
  function draw(){
    ctx.clearRect(0,0,W,H); f++;
    balls.forEach(b=>{
      b.x+=b.vx*b.depth; b.y+=b.vy*b.depth;
      if(b.x<-20)b.x=W+20; if(b.x>W+20)b.x=-20;
      if(b.y<-20)b.y=H+20; if(b.y>H+20)b.y=-20;
      const p=b.a+Math.sin(f*b.sp+b.ph)*.05;
      const sz=b.r*b.depth;
      const g=ctx.createRadialGradient(b.x-sz*.3,b.y-sz*.3,sz*.1,b.x,b.y,sz);
      g.addColorStop(0,`hsla(${b.hue},90%,85%,${p*1.4})`);
      g.addColorStop(.4,`hsla(${b.hue},80%,65%,${p})`);
      g.addColorStop(1,`hsla(${b.hue},70%,40%,0)`);
      ctx.beginPath(); ctx.arc(b.x,b.y,sz,0,Math.PI*2);
      ctx.fillStyle=g; ctx.fill();
    });
    requestAnimationFrame(draw);
  }
  init(); draw();
})();
 
/* ══ THESIS KNOWLEDGE BASE ══ */
const THESIS_CONTEXT = `
Toto jsou klíčové informace z diplomové práce "Politiky a strategie EU pro podporu Smart Cities" od Bc. Martina Beránka (ČZU Praha, PEF, Katedra ekonomiky, vedoucí doc. Ing. Karel Tomšík Ph.D., 2026):
 
ABSTRAKT:
Práce se věnuje komparativní analýze systémů veřejné správy a regionálních politik zaměřených na podporu konceptu Smart Cities. Hlavním cílem je vyhodnotit efektivnost institucionálních rámců a investičních strategií v kontextu digitální transformace měst, se zvláštním zřetelem na srovnání České republiky a Francie. Zatímco český model je charakteristický vysokou dotační závislostí na evropských fondech a plošným rozdělováním prostředků, francouzský plán France 2030 sází na suverénní národní financování, strategickou selektivitu a dlouhodobou technologickou suverenitu. Výsledky analýzy poukazují na administrativní rigiditu českého modelu a pomalou dynamiku reálného dopadu investic na městskou infrastrukturu. V závěru jsou formulovány návrhy: zřízení národního mediátora pro inovace po vzoru Lab2051, legislativní ukotvení inkubační fáze projektů a zavedení regulačních pískovišť.
 
KLÍČOVÁ SLOVA: Česká republika, digitální transformace, Francie 2030, investiční strategie, Lab2051, regionální rozvoj, regulační pískoviště, Smart City, technologická suverenita, veřejná správa.
 
DEFINICE SMART CITY:
Smart City není město v tradičním smyslu. Představuje inteligentní městský prostor, který užívá pokročilé technologie a inovace ke zlepšení kvality života obyvatel, zefektivnění služeb i udržitelnému rozvoji. Jde o integrovanou strategii rozvoje města, která synergicky propojuje digitální technologie, datovou analytiku, principy udržitelnosti a moderní způsoby řízení (governance). Primárním cílem není implementace technologie samotné, ale její využití pro zvyšování kvality života občanů.
 
6 PILÍŘŮ SMART CITY: Smart Economy (konkurenceschopnost, inovace, ICT), Smart People (lidskocentrický přístup, digitální gramotnost), Smart Governance (datově podložené rozhodování, participace), Smart Mobility (udržitelná doprava, dekarbonizace), Smart Living (kvalita života, sdílená ekonomika), Smart Building (otevřené datové standardy, digitální dvojčata).
 
HISTORICKÝ VÝVOJ:
- 2010: Smart region Vrchlabí (Grid4EU) - první pilotní Smart Grid v ČR
- 2011: Průmyslová platforma "Smart Cities and Communities"
- 2012: Evropské inovační partnerství o chytrých městech (EIP-SCC)
- 2015: "Modrožlutá kniha" města Písek - první komplexní koncepce Smart City v ČR
 
ZÁKLADNÍ POJMY:
- Digital Twins: virtuální model města pro simulaci dopadů rozhodnutí
- Open Data: veřejná data v otevřených strojově čitelných formátech
- Smart Governance: transformace řízení od hierarchických k participativním procesům (Quadruple Helix: veřejná správa, soukromý sektor, akademická sféra, občané)
- IoT: "nervový systém" chytrých měst - síť senzorů sbírající data v reálném čase
- Interoperabilita: schopnost systémů vzájemně komunikovat, klíčová podmínka Smart City
 
METODIKA PRÁCE:
Kombinace sekundární komparace dat a vícekriteriální komparativní analýzy. Čtyři vlastní kvantitativní ukazatele:
1. Index investiční intenzity na obyvatele (I_pop) = Celkové veřejné investice / Počet obyvatel
2. Index dotační závislosti (D_z) = Investice z fondů EU / Celkové veřejné investice (hodnota blízká 1 = úplná závislost)
3. Pákový efekt veřejných investic (L) = Mobilizovaný soukromý kapitál / Veřejná investice
4. Index implementační efektivnosti (E_imp) = Reálně proplacené prostředky / Právně zasmluvněné prostředky
Dále industrializační ROI = (Hodnota lokální produkce + Ušetřené náklady na dovoz) / Státní dotace
 
PROČ FRANCIE?
France 2030 je první francouzský národní investiční program s explicitně definovanými kvantitativními cíli. Je financován z národních zdrojů (54 mld. EUR), nikoli z fondů EU. Jde o dlouhodobou strukturální strategii zaměřenou na technologickou suverenitu. Tvoří přirozený kontrapunkt k českému modelu závislému na kohezní politice EU.
 
FRANCE 2030 - FRANCOUZSKÝ MODEL:
- Suverénní národní financování (54 mld. EUR z národních zdrojů)
- Strategická selektivita investic (ne plošné rozdělování)
- Lab2051: specializovaná instituce - národní mediátor pro inovace
- Vertikální integrace inovací: od výzkumu k regionální industrializaci
- Sektorová dekarbonizace urbanismu
- Podpora emerging players a startupů v oblasti Smart City
- "Démonstrateurs de la ville durable" - živé laboratoře
- PNRR synergie evropských a národních zdrojů
 
ČESKÁ REPUBLIKA - MODEL:
- Vysoká dotační závislost na evropských fondech
- Plošné rozdělování finančních prostředků
- Administrativní rigidita
- Fragmentace investic
- Pomalá dynamika reálného dopadu investic na infrastrukturu
- Omezená schopnost mobilizovat soukromý kapitál
- Strategický rámec: Smart Česko
- Financování Smart Cities v ČR v období 2021-2027: Program DIGITAL
- Riziko "dotační past roku 2026" - ukončení dotačních cyklů
 
KOMPARATIVNÍ ANALÝZA:
Strukturální rozdíly: zatímco ČR je charakterizována vysokou závislostí na EU dotacích, Francie staví na národní finanční autonomii, strategické selektivitě a aktivním odstraňování legislativních bariér. Česká republika čelí riziku spojenému s ukončením dotačních cyklů po roce 2026.
 
LEGISLATIVNÍ RÁMEC ČR:
- Zákon č. 365/2000 Sb. - informační systémy veřejné správy
- Zákon č. 12/2020 Sb. - právo na digitální služby
- Zákon č. 264/2025 Sb. - kybernetická bezpečnost
- Vyhláška č. 315/2021 Sb. - cloud computing ve veřejné správě
- Zákon č. 110/2019 Sb. - zpracování osobních údajů
- Zákon č. 128/2000 Sb. - o obcích
 
TECHNOLOGIE:
- Big Data: 6V (objem, rychlost, rozmanitost, důvěryhodnost, suverenita, veřejná hodnota)
- AI Watch: 686 případů užití AI v EU, 38% plně integrováno, 58% využívá strojové učení
- Cloud: model pay-as-you-go, SaaS/PaaS pro e-government
- IoT: prediktivní údržba infrastruktury, snižování provozních nákladů
 
STRATEGICKÁ DOPORUČENÍ PRO ČR:
1. Zřízení národního mediátora pro inovace po vzoru francouzského Lab2051
2. Legislativní ukotvení inkubační fáze projektů
3. Zavedení regulačních pískovišť pro bezpečné testování inovativních řešení v reálném urbanizovaném prostředí
4. Reforma rozdělování EU fondů - od plošnosti ke strategické selektivitě
5. Transformace role státu z pouhého distributora dotací na aktivního architekta inovačního ekosystému
 
VÝSLEDKY A DISKUSE:
Syntéza zjištění: "Administrativní past vs investiční tah" - dotační závislost je hrozbou roku 2026 a výzvou pro programové období 2028+. Analýza institucionálního rámce a alokační efektivnosti investičních zdrojů ukazuje na strukturální rozdíly.
 
STRUKTURA PRÁCE:
1. Úvod
2. Cíl práce a metodika (2.1 Cíl, 2.2 Metodika)
3. Teoretická východiska (konceptuální vymezení, pilíře, governance, technologie, ekonomické rámce, financování, udržitelný rozvoj, bezpečnost, bariéry)
4. Vlastní práce (France 2030, mechanismus řízení, technologická suverenita, financování, komparativní analýza, praktická aplikace)
5. Výsledky a diskuse
6. Závěr
7. Seznam použitých zdrojů
8. Seznam tabulek a zkratek
`;
 
/* ══ CHAT LOGIC ══ */
const chatEl    = document.getElementById('chat');
const inputEl   = document.getElementById('userInput');
const sendBtn   = document.getElementById('sendBtn');
const quickWrap = document.getElementById('quickWrap');
 
let history = [];
 
function addMsg(role, text) {
  const div = document.createElement('div');
  div.className = 'msg ' + (role === 'user' ? 'user' : 'ai');
  const avatar = role === 'user' ? 'Ty' : 'AI';
  div.innerHTML = `
    <div class="msg-avatar">${avatar}</div>
    <div class="msg-bubble">${text}</div>
  `;
  chatEl.appendChild(div);
  chatEl.scrollTop = chatEl.scrollHeight;
  return div;
}
 
function addTyping() {
  const div = document.createElement('div');
  div.className = 'msg ai';
  div.id = 'typing';
  div.innerHTML = `
    <div class="msg-avatar">AI</div>
    <div class="msg-bubble"><div class="typing-dots"><span></span><span></span><span></span></div></div>
  `;
  chatEl.appendChild(div);
  chatEl.scrollTop = chatEl.scrollHeight;
  return div;
}
 
function formatResponse(text) {
  return text
    .replace(/\*\*(.*?)\*\*/g, '<strong>$1</strong>')
    .replace(/\*(.*?)\*/g, '<em>$1</em>')
    .replace(/\n/g, '<br>');
}
 
async function sendMessage(text) {
  if (!text.trim()) return;
 
  // Hide quick chips after first message
  quickWrap.style.display = 'none';
 
  addMsg('user', text);
  inputEl.value = '';
  inputEl.style.height = 'auto';
  sendBtn.disabled = true;
 
  const typing = addTyping();
 
  history.push({ role: 'user', content: text });
 
  try {
    const response = await fetch('https://api.anthropic.com/v1/messages', {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify({
        model: 'claude-sonnet-4-20250514',
        max_tokens: 1000,
        system: `Jsi AI asistent diplomové práce. Odpovídáš VÝHRADNĚ na základě obsahu níže uvedené diplomové práce. Pokud odpověď není v práci, řekni to. Odpovídej česky, stručně a přehledně. Používej tučné písmo pro klíčové pojmy. Neodpovídej na otázky mimo rámec diplomové práce.
 
OBSAH DIPLOMOVÉ PRÁCE:
${THESIS_CONTEXT}`,
        messages: history
      })
    });
 
    const data = await response.json();
    typing.remove();
 
    const reply = data.content?.[0]?.text || 'Omlouvám se, nepodařilo se získat odpověď.';
    history.push({ role: 'assistant', content: reply });
    addMsg('ai', formatResponse(reply));
 
  } catch (err) {
    typing.remove();
    addMsg('ai', 'Chyba při připojení k AI. Zkontroluj připojení k internetu.');
    history.pop();
  }
 
  sendBtn.disabled = false;
  inputEl.focus();
}
 
// Send button
sendBtn.addEventListener('click', () => sendMessage(inputEl.value));
 
// Enter key (Shift+Enter = new line)
inputEl.addEventListener('keydown', e => {
  if (e.key === 'Enter' && !e.shiftKey) {
    e.preventDefault();
    sendMessage(inputEl.value);
  }
});
 
// Auto-resize textarea
inputEl.addEventListener('input', () => {
  inputEl.style.height = 'auto';
  inputEl.style.height = Math.min(inputEl.scrollHeight, 120) + 'px';
});
 
// Quick chips
quickWrap.querySelectorAll('.q-chip').forEach(chip => {
  chip.addEventListener('click', () => sendMessage(chip.textContent));
});
 
// Welcome message
setTimeout(() => {
  addMsg('ai', 'Ahoj! Jsem AI asistent tvé diplomové práce o Smart Cities. Znám celý její obsah — definice, metodiku, srovnání ČR vs. Francie, závěry i doporučení. <strong>Na co se chceš zeptat?</strong>');
}, 500);
</script>
</body>
</html>
