<!-- haseeba-f · github profile readme -->
<div align="center">
Show Image
Show Image
Show Image
Show Image
</div>

<p align="center">🌸 · · · · · · · · · · · · · · · · · · · · 🌸</p>

✦ who dis
<table>
<tr>
<td width="58%" valign="top">
yaml# ══ haseeba.yaml ══════════════════════════

name:      "Haseeba Faiza"
college:   "MLRIT Hyderabad · CS Data Science"
year:      2nd  →  graduating 2028
cgpa:      8.6

roles:
  ◈  Full Stack Developer
  ◈  AI / ML Engineer
  ◈  Hackathon Builder

frontend:  [ React, Tailwind, GSAP ]
backend:   [ FastAPI, Express.js ]
ml:        [ TensorFlow, Scikit-learn, Keras, Pandas ]
db:        [ PostgreSQL, MySQL ]
languages: [ Python, Java, SQL ]
ai_llm:    [ Groq API, LangChain ]
tools:     [ Git, Streamlit, Railway ]

currently:
  → CNNs · RNNs · LSTMs
  → Agentic AI systems
  → Docker · Cloud

big_win:   "Top 10 / 220+ @ SUDHEE 2026 🏆"
vibe:      "vibe-code boilerplate, own the core 😤"
endgame:   "build products · start companies 🚀"
</td>
<td width="42%" align="center" valign="middle">
<img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" width="160" alt="cat coding"/>
<br/>
Show Image
Show Image
Show Image
</td>
</tr>
</table>

<p align="center">🌸 · · · · · · · · · · · · · · · · · · · · 🌸</p>

✦ tech stack
<div align="center">
Tools🤖 AI / MLShow Image Show Image Show Image Show Image Show Image⚡ FrontendShow Image Show Image Show Image💬 LanguagesShow Image Show Image🔧 BackendShow Image Show Image🗄️ DatabaseShow Image Show Image🧠 AI / LLMShow Image Show Image🛠️ ToolsShow Image Show Image Show Image📦 LearningShow Image
</div>

<p align="center">🌸 · · · · · · · · · · · · · · · · · · · · 🌸</p>

✦ shipped projects
<div align="center">
<table>
<tr>
<td align="center" width="33%">
🏦 Customer Churn Prediction
ANN predicting bank churn · live & deployed
Show Image
Show Image
Show Image
</td>
<td align="center" width="33%">
⚖️ LegalShe
AI legal assistant · built for women
Show Image
Show Image
Show Image
</td>
<td align="center" width="33%">
🏙️ AI Civic Issue Reporting
🏆 Top 10 @ SUDHEE 2026 · 220+ teams
Show Image
Show Image
Show Image
</td>
</tr>
<tr>
<td align="center" width="33%">
📊 Trader Sentiment Analysis
Bitcoin Fear/Greed × Hyperliquid behavior
Show Image
Show Image
Show Image
</td>
<td align="center" width="33%">
🤖 Jarvis Clap Automation
double-clap → launches apps in real time
Show Image
Show Image
Show Image
</td>
<td align="center" width="33%">
⚡ GSAP Energy Drink Site
scroll-triggered animations · landing page
Show Image
Show Image
Show Image
</td>
</tr>
</table>
</div>

<p align="center">🌸 · · · · · · · · · · · · · · · · · · · · 🌸</p>

✦ sakura catcher 🌸 · mini game

GitHub READMEs can't run JavaScript — host this on GitHub Pages and play it live!

<details>
<summary><b>🎮 deploy in 3 steps</b></summary>

Create a repo called sakura-game on your GitHub
Drop the index.html below into it
Go to Settings → Pages → deploy from main branch

Then link to it from your README:
markdown[![🌸 Play Sakura Catcher](https://img.shields.io/badge/🌸_Play_Sakura_Catcher-FF6EB4?style=for-the-badge)](https://Haseeba-f.github.io/sakura-game)
html<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8"/>
<title>sakura catcher · haseeba</title>
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{background:#0d0010;display:flex;flex-direction:column;align-items:center;justify-content:center;min-height:100vh;font-family:monospace;color:#ffd6ec}
h1{color:#ff6eb4;font-size:24px;margin-bottom:8px;letter-spacing:2px}
p{color:#ff9dd2;font-size:12px;margin-bottom:16px}
canvas{border:1px solid #ff6eb433;border-radius:12px;display:block}
.ui{display:flex;gap:24px;margin:12px 0;font-size:13px}
.ui span{color:#ffb3d9}
.ui b{color:#ff6eb4}
button{margin:8px;padding:8px 20px;background:#ff6eb415;border:1px solid #ff6eb455;color:#ff9dd2;border-radius:20px;font-family:monospace;font-size:12px;cursor:pointer;letter-spacing:1px}
button:hover{background:#ff6eb433}
#msg{color:#ff85c2;font-size:12px;margin-top:8px;height:20px}
</style>
</head>
<body>
<h1>🌸 sakura catcher</h1>
<p>catch 🌸 · dodge ⚡ · by haseeba</p>
<canvas id="c" width="520" height="320"></canvas>
<div class="ui">
  <span>score: <b id="sc">0</b></span>
  <span>lives: <b id="lv">❤️❤️❤️</b></span>
  <span>level: <b id="lvl">1</b></span>
</div>
<div><button onclick="start()">▶ start</button><button onclick="reset()">↺ reset</button></div>
<div id="msg">click start to play!</div>
<script>
const cv=document.getElementById('c'),ctx=cv.getContext('2d');
let running=false,score=0,lives=3,level=1,frame=0,items=[];
let bx=230,bw=60;
cv.addEventListener('mousemove',e=>{const r=cv.getBoundingClientRect();bx=Math.max(0,Math.min(460,(e.clientX-r.left)-bw/2))});
cv.addEventListener('touchmove',e=>{e.preventDefault();const r=cv.getBoundingClientRect();bx=Math.max(0,Math.min(460,(e.touches[0].clientX-r.left)-bw/2))},{passive:false});
function drawBg(){ctx.fillStyle='#0a000d';ctx.fillRect(0,0,520,320);ctx.strokeStyle='#ff6eb415';ctx.lineWidth=0.5;for(let x=0;x<520;x+=40){ctx.beginPath();ctx.moveTo(x,0);ctx.lineTo(x,320);ctx.stroke()}for(let y=0;y<320;y+=40){ctx.beginPath();ctx.moveTo(0,y);ctx.lineTo(520,y);ctx.stroke()}}
function drawBasket(){ctx.fillStyle='#ff6eb4';ctx.beginPath();ctx.roundRect(bx,295,bw,14,4);ctx.fill()}
function spawn(){const bad=Math.random()<(0.2+level*0.04);items.push({x:Math.random()*460+20,y:-20,e:bad?'⚡':'🌸',bad,s:2+level*0.4+Math.random()*1.5,r:0,rs:(Math.random()-.5)*0.08})}
function upd(){frame++;if(frame%Math.max(10,28-level*3)===0)spawn();items=items.filter(it=>{it.y+=it.s;it.r+=it.rs;if(it.y>320){if(!it.bad){lives--;upUI()}return false}const cx=it.x+12,cy=it.y+12;if(cy>295&&cy<310&&cx>bx&&cx<bx+bw){if(it.bad){lives--;upUI()}else{score+=10*level;document.getElementById('sc').textContent=score;if(score>0&&score%(80*level)===0){level++;document.getElementById('lvl').textContent=level}}if(lives<=0){end();return false}return false}return true})}
function drw(){drawBg();items.forEach(it=>{ctx.save();ctx.translate(it.x+12,it.y+12);ctx.rotate(it.r);ctx.font='22px serif';ctx.textAlign='center';ctx.textBaseline='middle';ctx.fillText(it.e,0,0);ctx.restore()});drawBasket()}
function loop(){if(!running)return;upd();drw();requestAnimationFrame(loop)}
function upUI(){document.getElementById('lv').textContent='❤️'.repeat(Math.max(0,lives));document.getElementById('lvl').textContent=level}
function start(){if(running)return;running=true;document.getElementById('msg').textContent='move mouse to catch 🌸 · dodge ⚡';loop()}
function reset(){running=false;score=0;lives=3;level=1;items=[];frame=0;document.getElementById('sc').textContent=0;document.getElementById('msg').textContent='click start to play!';upUI();drawBg();drawBasket()}
function end(){running=false;document.getElementById('msg').textContent='game over! '+score+' pts · level '+level+' 🌸'}
drawBg();drawBasket();
</script>
</body>
</html>
</details>

<p align="center">🌸 · · · · · · · · · · · · · · · · · · · · 🌸</p>

✦ github stats
<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=Haseeba-f&show_icons=true&hide_border=true&bg_color=1a0010&title_color=FF6EB4&icon_color=FF85C2&text_color=FFB3D9&ring_color=FF6EB4&border_radius=16&count_private=true" />
&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Haseeba-f&layout=compact&hide_border=true&bg_color=1a0010&title_color=FF6EB4&text_color=FFB3D9&border_radius=16&langs_count=6" />
<br/><br/>
<img src="https://github-profile-trophy.vercel.app/?username=Haseeba-f&theme=radical&no-frame=true&no-bg=false&margin-w=8&column=4" />
</div>

✦ wins
diff+ 🏆  Top 10 / 220+ teams — SUDHEE 2026 National Hackathon @ CBIT
+ 🤝  Co-organized Ignitia 2K26 — 200+ participants, ₹20K prize pool
+ 🚀  3+ deployed ML + Full Stack projects — live and working
+ 📊  End-to-end Hyperliquid × Bitcoin Fear/Greed analysis
+ 🤖  Built AI Civic Reporting System from scratch in hackathon hours
+ 🎓  CGPA 8.6 · CS Data Science · MLRIT Hyderabad

<p align="center">🌸 · · · · · · · · · · · · · · · · · · · · 🌸</p>
<div align="center">
<img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" width="55"/>
"build in public · learn out loud · ship fast"
— haseeba faiza · 2nd year · already dangerous 🔥
Show Image
Show Image
Show Image
</div>
<!--
**Haseeba-f/Haseeba-f** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
