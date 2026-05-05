<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no"/>
<meta name="apple-mobile-web-app-capable" content="yes"/>
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent"/>
<title>pink assassins · class plan</title>
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Sans:opsz,wght@9..40,300;9..40,400;9..40,500;9..40,600&display=swap" rel="stylesheet"/>

<!-- Firebase via CDN -->

<script src="https://www.gstatic.com/firebasejs/10.12.0/firebase-app-compat.js"></script>

<script src="https://www.gstatic.com/firebasejs/10.12.0/firebase-firestore-compat.js"></script>

<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
:root{
  --bg:#f0efed;--surface:#f7f6f4;--panel:#ebebea;
  --border:#d8d7d5;--border2:#c8c7c5;
  --stone:#8a8a88;--ink:#1a1a1a;--ink-lt:#4a4a48;
  --putty:#9a9a98;--red:#b33a2d;--white:#fafafa;
}
html,body{width:100%;height:100%;overflow:hidden;background:var(--bg);}
body{font-family:'DM Sans',sans-serif;color:var(--ink);}
#app{width:100vw;height:100vh;display:flex;overflow:hidden;}
.screen{display:none;width:100%;height:100%;}
.screen.active{display:flex;}

.wordmark{font-family:'DM Serif Display',serif;font-style:italic;color:var(--ink);line-height:1;}
.wordmark.lg{font-size:58px;letter-spacing:-1px;}
.wordmark.sm{font-size:13px;color:var(--stone);letter-spacing:0;margin-bottom:6px;}
.eyebrow,.lbl{font-size:9px;font-weight:600;letter-spacing:2.5px;text-transform:uppercase;color:var(--stone);display:block;}
.lbl-xs{font-size:8.5px;font-weight:600;letter-spacing:1.5px;text-transform:uppercase;color:var(--stone);}
.hero-title{font-family:'DM Serif Display',serif;font-size:32px;font-style:italic;line-height:1.1;text-transform:lowercase;}
.dur-pill{display:inline-block;margin-top:6px;background:#222;border-radius:100px;padding:3px 12px;font-size:9px;font-weight:600;letter-spacing:1.5px;text-transform:uppercase;color:#777;}
.back-lnk{background:none;border:none;cursor:pointer;font-family:'DM Sans',sans-serif;font-size:11px;color:var(--stone);padding:0;}
.btn-pill-inv{padding:5px 13px;background:transparent;border:1px solid #3a3a3a;border-radius:100px;font-family:'DM Sans',sans-serif;font-size:10px;font-weight:600;color:#999;cursor:pointer;}
.btn-dark-full{width:100%;padding:10px;background:rgba(255,255,255,0.08);color:#ccc;border:1px solid #444;border-radius:8px;font-family:'DM Sans',sans-serif;font-size:12px;font-weight:600;letter-spacing:.5px;cursor:pointer;}
.btn-outline-full{width:100%;padding:9px;background:var(--panel);border:1px solid var(--border);border-radius:8px;font-family:'DM Sans',sans-serif;font-size:12px;font-weight:600;color:var(--ink);cursor:pointer;}
.btn-outline-full:disabled{opacity:.3;cursor:not-allowed;}
.inp{width:100%;padding:8px 10px;background:var(--panel);border:1px solid var(--border);border-radius:7px;font-family:'DM Sans',sans-serif;font-size:12px;color:var(--ink);outline:none;height:36px;}
.dark-inp{width:100%;padding:8px 10px;background:#222;border:1px solid #3a3a3a;border-radius:7px;font-family:'DM Sans',sans-serif;font-size:12px;color:#ddd;outline:none;height:36px;}
.dark-inp:focus{border-color:#555;}
.ta{width:100%;padding:8px 10px;background:var(--panel);border:1px solid var(--border);border-radius:7px;font-family:'DM Sans',sans-serif;font-size:12px;color:var(--ink);outline:none;resize:vertical;line-height:1.5;}
.ta::placeholder{color:var(--stone);opacity:.6;}
.panel{padding:22px 24px;display:flex;flex-direction:column;gap:16px;height:100%;overflow-y:auto;}
.field-block{display:flex;flex-direction:column;gap:7px;}

/* sync */
.sync-bar{display:flex;align-items:center;gap:6px;font-size:10px;color:#555;margin-top:8px;}
.sync-dot{width:7px;height:7px;border-radius:50%;flex-shrink:0;background:#555;}
.sync-dot.ok{background:#4a9d6f;}
.sync-dot.err{background:#b33a2d;}
.sync-dot.busy{background:#c4a44a;animation:pulse 1s infinite;}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.4}}

/* HOME */
#home{flex-direction:row;}
.home-left{width:300px;flex-shrink:0;background:var(--ink);padding:44px 36px;display:flex;flex-direction:column;justify-content:flex-end;gap:10px;}
.home-left .wordmark{color:var(--surface);}
.home-tagline{font-size:10px;letter-spacing:2.5px;text-transform:uppercase;color:#555;}
.home-left-nav{display:flex;flex-direction:column;gap:8px;margin-top:24px;}
.home-nav-btn{background:none;border:none;cursor:pointer;font-family:'DM Sans',sans-serif;font-size:11px;font-weight:600;letter-spacing:1.5px;text-transform:uppercase;color:#555;text-align:left;padding:6px 0;border-bottom:1px solid #2a2a2a;transition:color .12s;}
.home-nav-btn.active{color:#aaa;}
.home-right{flex:1;background:var(--surface);display:flex;flex-direction:column;overflow:hidden;}
.home-tab-content{flex:1;overflow-y:auto;padding:36px 40px;}
.home-plans-grid{display:flex;gap:36px;}
.home-col{flex:1;display:flex;flex-direction:column;gap:14px;}
.tmpl-tile{background:var(--white);border:1px solid var(--border);border-radius:10px;padding:18px 20px;cursor:pointer;display:flex;flex-direction:column;gap:4px;transition:all .15s;}
.tmpl-tile:hover{border-color:var(--border2);background:var(--panel);}
.tmpl-day{font-family:'DM Serif Display',serif;font-size:26px;font-style:italic;color:var(--ink);}
.tmpl-time{font-size:11px;color:var(--stone);}
.tmpl-dur{margin-top:5px;font-size:9px;font-weight:600;letter-spacing:1.5px;text-transform:uppercase;color:var(--putty);}
.saved-row{display:flex;justify-content:space-between;align-items:center;background:var(--white);border:1px solid var(--border);border-radius:10px;padding:12px 15px;cursor:pointer;transition:all .15s;margin-bottom:9px;}
.saved-row:hover{border-color:var(--border2);}
.saved-day{font-family:'DM Serif Display',serif;font-size:15px;font-style:italic;}
.saved-date{font-size:10px;color:var(--stone);margin-top:2px;}
.del-btn{background:none;border:none;cursor:pointer;color:var(--stone);font-size:11px;padding:4px 8px;border-radius:5px;}
.del-btn:hover{color:var(--red);}
.no-data{font-size:12px;color:var(--stone);font-style:italic;padding:8px 0;}

/* ANALYTICS */
.analytics-title{font-family:'DM Serif Display',serif;font-size:22px;font-style:italic;color:var(--ink);margin-bottom:4px;}
.analytics-sub{font-size:11px;color:var(--stone);margin-bottom:14px;}
.lesson-tabs{display:flex;gap:8px;margin-bottom:20px;}
.lesson-tab{padding:7px 18px;border:1px solid var(--border);border-radius:100px;font-family:'DM Sans',sans-serif;font-size:11px;font-weight:600;color:var(--stone);cursor:pointer;background:transparent;}
.lesson-tab.active{background:var(--ink);border-color:var(--ink);color:white;}
.att-table{width:100%;border:1px solid var(--border);border-radius:10px;overflow:hidden;margin-bottom:20px;}
.att-hd{display:grid;grid-template-columns:120px 1fr 70px 60px;background:var(--panel);padding:7px 14px;border-bottom:1px solid var(--border);}
.att-hd span,.stunt-hd-row span{font-size:8px;font-weight:600;letter-spacing:1.5px;text-transform:uppercase;color:var(--stone);}
.att-row{display:grid;grid-template-columns:120px 1fr 70px 60px;padding:8px 14px;border-top:1px solid var(--border);align-items:center;}
.att-dots{display:flex;gap:4px;flex-wrap:wrap;}
.att-dot{width:10px;height:10px;border-radius:50%;}
.stunt-block{background:var(--white);border:1px solid var(--border);border-radius:10px;overflow:hidden;margin-bottom:10px;}
.stunt-block-hd{display:flex;justify-content:space-between;padding:9px 14px;background:var(--panel);border-bottom:1px solid var(--border);}
.stunt-hd-row{display:grid;grid-template-columns:100px 55px 55px 1fr 55px;gap:8px;padding:5px 14px;background:var(--panel);}
.stunt-ath-row{display:grid;grid-template-columns:100px 55px 55px 1fr 55px;gap:8px;align-items:center;padding:6px 14px;border-top:1px solid var(--border);}
.hit-bar-wrap{background:var(--border);border-radius:100px;height:5px;overflow:hidden;}
.hit-bar{height:100%;border-radius:100px;background:var(--ink);}
.totals-card{border:1px solid var(--border);border-radius:10px;overflow:hidden;margin-bottom:16px;}
.totals-hd{display:grid;grid-template-columns:100px 70px 70px 1fr 60px;gap:8px;padding:6px 14px;background:var(--panel);border-bottom:1px solid var(--border);}
.totals-hd span{font-size:8px;font-weight:600;letter-spacing:1.5px;text-transform:uppercase;color:var(--stone);}
.totals-row{display:grid;grid-template-columns:100px 70px 70px 1fr 60px;gap:8px;align-items:center;padding:7px 14px;border-top:1px solid var(--border);}

/* BUILDER */
#builder{flex-direction:row;}
.builder-left{width:290px;flex-shrink:0;background:var(--ink);overflow-y:auto;}
.builder-right{flex:1;background:var(--surface);overflow-y:auto;}
.builder-left .lbl,.builder-left .lbl-xs,.builder-left .back-lnk{color:#555;}
.builder-left .back-lnk:hover{color:#999;}
.prog-track{height:4px;background:#2a2a2a;border-radius:100px;overflow:hidden;}
.prog-fill{height:100%;border-radius:100px;transition:width .3s;}
.prog-meta{display:flex;justify-content:space-between;font-size:10px;color:#666;}
.prog-meta .red{color:var(--red);font-weight:600;}
.cat-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:5px;}
.cat-chip{background:var(--panel);border:1px solid var(--border);border-radius:7px;padding:8px 4px;font-family:'DM Sans',sans-serif;font-size:10px;color:var(--ink-lt);cursor:pointer;display:flex;flex-direction:column;align-items:center;gap:3px;text-align:center;line-height:1.2;transition:all .12s;}
.cat-chip.sel{background:var(--white);border-color:var(--ink);color:var(--ink);font-weight:600;}
.cat-ic{font-size:12px;color:var(--putty);}
.bsec{border:1px solid var(--border);border-radius:8px;padding:11px;display:flex;flex-direction:column;gap:9px;background:var(--white);margin-bottom:9px;}
.bsec-top{display:flex;justify-content:space-between;align-items:center;}
.bsec-left{display:flex;align-items:center;gap:7px;}
.bsec-num{font-family:'DM Serif Display',serif;font-size:17px;font-style:italic;color:var(--putty);}
.bsec-lbl{font-size:12px;font-weight:600;color:var(--ink);}
.bsec-actions{display:flex;gap:4px;}
.ic-btn{width:25px;height:25px;background:var(--panel);border:1px solid var(--border);border-radius:5px;cursor:pointer;font-size:9px;color:var(--stone);display:flex;align-items:center;justify-content:center;}
.ic-btn:disabled{opacity:.2;cursor:not-allowed;}
.ic-btn.danger{color:var(--red);}
.tchips{display:flex;flex-wrap:wrap;gap:4px;}
.tchip{background:var(--panel);border:1px solid var(--border);border-radius:5px;padding:3px 8px;font-family:'DM Sans',sans-serif;font-size:10px;color:var(--ink-lt);cursor:pointer;}
.tchip.sel{background:var(--ink);border-color:var(--ink);color:white;font-weight:600;}

/* PLAN */
#plan{flex-direction:row;}
.plan-sidebar{width:240px;flex-shrink:0;background:var(--ink);overflow-y:auto;}
.plan-sidebar .lbl{color:#555;}
.plan-main{flex:1;background:var(--bg);overflow-y:auto;}
.plan-inner{padding:20px 24px 80px;display:flex;flex-direction:column;gap:12px;}
.sidebar-top{display:flex;justify-content:space-between;align-items:center;}
.attend-list{display:flex;flex-direction:column;gap:3px;margin-top:6px;}
.attend-item{display:flex;align-items:center;gap:8px;padding:5px 9px;border-radius:5px;cursor:pointer;user-select:none;border:1px solid transparent;}
.attend-item.on{background:#1e1e1e;border-color:#2e2e2e;}
.tick{width:15px;height:15px;border:1.5px solid #3a3a3a;border-radius:3px;display:flex;align-items:center;justify-content:center;font-size:8px;color:#666;font-weight:700;flex-shrink:0;}
.attend-item.on .tick{border-color:#555;color:#999;}
.aname{font-size:11px;color:#777;}
.attend-item.on .aname{color:#bbb;}
.plan-block{background:var(--surface);border:1px solid var(--border);border-radius:10px;overflow:hidden;}
.plan-block-hd{display:flex;justify-content:space-between;align-items:center;padding:9px 15px;background:var(--panel);border-bottom:1px solid var(--border);}
.blk-left{display:flex;align-items:center;gap:9px;}
.blk-num{font-family:'DM Serif Display',serif;font-size:18px;font-style:italic;color:var(--border2);}
.blk-title{font-size:13px;font-weight:600;color:var(--ink);}
.dur-tag{font-size:9px;font-weight:600;letter-spacing:1.5px;text-transform:uppercase;color:var(--stone);background:var(--white);border:1px solid var(--border);border-radius:100px;padding:3px 10px;}
.plan-block-body{display:flex;flex-direction:column;}
.plan-field{padding:9px 15px;border-bottom:1px solid var(--border);}
.plan-field:last-child{border-bottom:none;}
.plan-field-lbl{font-size:8px;font-weight:600;letter-spacing:2px;text-transform:uppercase;color:var(--stone);margin-bottom:5px;}
.detail-text{font-size:12px;color:var(--ink-lt);line-height:1.5;}
.stunt-tbl{border:1px solid var(--border);border-radius:6px;overflow:hidden;}
.stunt-tbl-hd{display:grid;grid-template-columns:1fr 72px 72px;padding:5px 10px;background:var(--panel);border-bottom:1px solid var(--border);}
.stunt-tbl-hd span{font-size:8px;font-weight:600;letter-spacing:1.5px;text-transform:uppercase;color:var(--stone);text-align:center;}
.stunt-tbl-hd span:first-child{text-align:left;}
.stunt-tbl-row{display:grid;grid-template-columns:1fr 72px 72px;align-items:center;padding:5px 10px;border-top:1px solid var(--border);}
.sname{font-size:12px;color:var(--ink);}
.stunt-inp{width:60px;padding:4px 6px;background:var(--panel);border:1px solid var(--border);border-radius:5px;font-family:'DM Sans',sans-serif;font-size:13px;font-weight:600;color:var(--ink);text-align:center;outline:none;display:block;margin:0 auto;}
.plan-ta{width:100%;padding:7px 10px;background:var(--surface);border:1px solid var(--border);border-radius:7px;font-family:'DM Sans',sans-serif;font-size:12px;color:var(--ink);outline:none;resize:vertical;line-height:1.5;}
.plan-ta::placeholder{color:var(--stone);opacity:.6;}
.end-mark{text-align:center;padding:28px;font-size:9px;letter-spacing:2.5px;text-transform:uppercase;color:var(--border);}
</style>

</head>
<body>
<div id="app">

  <!-- HOME -->

  <div id="home" class="screen active">
    <div class="home-left">
      <div style="flex:1"></div>
      <div class="wordmark lg">pink<br/>assassins</div>
      <div class="home-tagline">class plan generator</div>
      <div class="home-left-nav">
        <button class="home-nav-btn active" onclick="homeTab('plans',this)">plans</button>
        <button class="home-nav-btn" onclick="homeTab('analytics',this)">analytics</button>
      </div>
      <div class="sync-bar">
        <div class="sync-dot busy" id="home-sync-dot"></div>
        <span id="home-sync-label">connecting...</span>
      </div>
    </div>
    <div class="home-right">
      <div id="tab-plans" class="home-tab-content">
        <div class="home-plans-grid">
          <div class="home-col">
            <span class="eyebrow">new plan</span>
            <div class="tmpl-tile" onclick="startBuilder('monday')">
              <span class="tmpl-day">monday</span>
              <span class="tmpl-time">4:00 pm – 5:45 pm</span>
              <span class="tmpl-dur">105 min</span>
            </div>
            <div class="tmpl-tile" onclick="startBuilder('wednesday')">
              <span class="tmpl-day">wednesday</span>
              <span class="tmpl-time">7:00 pm – 9:00 pm</span>
              <span class="tmpl-dur">120 min</span>
            </div>
          </div>
          <div class="home-col">
            <span class="eyebrow">saved plans</span>
            <div id="saved-list"><div class="no-data">Connecting to cloud...</div></div>
          </div>
        </div>
      </div>
      <div id="tab-analytics" class="home-tab-content" style="display:none">
        <div id="analytics-content"></div>
      </div>
    </div>
  </div>

  <!-- BUILDER -->

  <div id="builder" class="screen">
    <div class="builder-left">
      <div class="panel">
        <button class="back-lnk" onclick="goHome()">← back</button>
        <div>
          <div class="wordmark sm" style="color:#555">pink assassins</div>
          <h1 class="hero-title" id="b-title" style="color:#f7f6f4;white-space:pre-line"></h1>
          <div style="font-size:11px;color:#666;margin-top:3px" id="b-time"></div>
        </div>
        <div class="field-block">
          <label class="lbl">class date</label>
          <input type="date" class="dark-inp" id="b-date" oninput="onDateChange()"/>
          <div style="font-size:10px;color:#666;margin-top:2px" id="b-date-prev"></div>
        </div>
        <div class="field-block">
          <label class="lbl">time allocated</label>
          <div class="prog-track"><div class="prog-fill" id="b-prog" style="width:0%"></div></div>
          <div class="prog-meta"><span id="b-used">0 min</span><span id="b-total"></span></div>
        </div>
        <button class="btn-dark-full" onclick="savePlan()">save plan</button>
        <div class="sync-bar">
          <div class="sync-dot" id="builder-sync-dot"></div>
          <span id="builder-sync-label"></span>
        </div>
      </div>
    </div>
    <div class="builder-right">
      <div class="panel">
        <div class="field-block">
          <label class="lbl">add section</label>
          <div class="cat-grid" id="cat-grid"></div>
          <button class="btn-outline-full" id="add-sec-btn" onclick="addSection()" disabled>add to plan</button>
        </div>
        <div class="field-block" id="sections-wrap" style="display:none">
          <label class="lbl">plan order</label>
          <div id="sections-list"></div>
        </div>
      </div>
    </div>
  </div>

  <!-- PLAN -->

  <div id="plan" class="screen">
    <div class="plan-sidebar">
      <div class="panel">
        <div class="sidebar-top">
          <button class="back-lnk" style="color:#666" onclick="goHome()">← back</button>
          <button class="btn-pill-inv" onclick="editPlan()">edit</button>
        </div>
        <div>
          <div class="wordmark sm" style="color:#555">pink assassins</div>
          <h1 class="hero-title" id="p-title" style="color:#f7f6f4;font-size:28px;white-space:pre-line"></h1>
          <div style="font-size:11px;color:#666;margin-top:3px" id="p-time"></div>
          <div style="font-size:10px;color:#777;margin-top:2px" id="p-date"></div>
          <div class="dur-pill" id="p-dur"></div>
        </div>
        <div>
          <div class="lbl" style="margin-bottom:8px">attendance</div>
          <div class="attend-list" id="attend-list"></div>
        </div>
        <div class="sync-bar">
          <div class="sync-dot" id="plan-sync-dot"></div>
          <span id="plan-sync-label"></span>
        </div>
      </div>
    </div>
    <div class="plan-main">
      <div class="plan-inner" id="plan-sections"></div>
    </div>
  </div>

</div>
<script>
/* ─── FIREBASE INIT ─── */
firebase.initializeApp({
  apiKey: "AIzaSyDXpwLB28me7B3n5wG3coWF3QtQ0JSNBPo",
  authDomain: "pink-assassins.firebaseapp.com",
  projectId: "pink-assassins",
  storageBucket: "pink-assassins.firebasestorage.app",
  messagingSenderId: "941908531651",
  appId: "1:941908531651:web:dc1c60ae3843219f5ac576",
});
const db = firebase.firestore();
const plansCol = db.collection("plans");

/* ─── CONSTANTS ─── */
const ATHLETES = [“Mia”,“Phoenix”,“Addi”,“Makayla”,“Ruby”,“Ada”,“Airlie”];
const CATEGORIES = [
{id:“conditioning”,        label:“Conditioning”,        icon:“◈”},
{id:“stunt1”,              label:“1st Stunt”,           icon:“★”,stunt:true},
{id:“stunt2”,              label:“2nd Stunt”,           icon:“★”,stunt:true},
{id:“tosses”,              label:“Tosses”,              icon:“◉”},
{id:“jumps”,               label:“Jumps”,               icon:“◆”},
{id:“standing_tumbling”,   label:“Standing Tumbling”,   icon:“◎”},
{id:“running_tumbling”,    label:“Running Tumbling”,    icon:“▷”},
{id:“pyramid”,             label:“Pyramid”,             icon:“▲”},
{id:“end_dance”,           label:“End Dance”,           icon:“◐”},
{id:“routine_cleaning”,    label:“Routine Cleaning”,    icon:“✦”},
{id:“section_run_throughs”,label:“Section Run Throughs”,icon:“↺”},
];
const TIMES = [5,10,15,20,25,30,35,40,45,60];
const TEMPLATES = {
monday:    {id:“monday”,    display:“Monday”,    time:“4:00 pm – 5:45 pm”,duration:105},
wednesday: {id:“wednesday”, display:“Wednesday”, time:“7:00 pm – 9:00 pm”, duration:120},
};

/* ─── STATE ─── */
let plansCache = [];
let currentTemplateId = null;
let currentPlanId = null;
let pickedCat = null;
let sections = [];
let saveTimer = null;
let currentHomeTab = “plans”;
let analyticsLesson = “all”;
let unsubscribe = null;

/* ─── HELPERS ─── */
function uid(){return Date.now().toString(36)+Math.random().toString(36).slice(2);}
function nextWeekday(n){const d=new Date();const diff=(n-d.getDay()+7)%7||7;d.setDate(d.getDate()+diff);return d.toISOString().split(“T”)[0];}
function fmtDate(s){if(!s)return””;return new Date(s+“T12:00:00”).toLocaleDateString(“en-AU”,{weekday:“long”,day:“numeric”,month:“long”,year:“numeric”});}
function fmtDateShort(s){if(!s)return”—”;return new Date(s+“T12:00:00”).toLocaleDateString(“en-AU”,{day:“numeric”,month:“short”,year:“numeric”});}
function escHtml(s){return String(s).replace(/&/g,”&”).replace(/</g,”<”).replace(/>/g,”>”).replace(/”/g,”"”);}
function showScreen(id){document.querySelectorAll(”.screen”).forEach(s=>s.classList.remove(“active”));document.getElementById(id).classList.add(“active”);}
function setSyncDot(ctx,state,label){
const dot=document.getElementById(ctx+”-sync-dot”);
const lbl=document.getElementById(ctx+”-sync-label”);
if(!dot||!lbl)return;
dot.className=“sync-dot “+(state===“ok”?“ok”:state===“err”?“err”:state===“busy”?“busy”:””);
lbl.textContent=label||””;
}
function getPlan(id){return plansCache.find(p=>p.id===id)||null;}

/* ─── FIREBASE LIVE SYNC ─── */
function startLiveSync(){
setSyncDot(“home”,“busy”,“connecting…”);
unsubscribe = plansCol.orderBy(“updated_at”,“desc”).onSnapshot(snap=>{
plansCache = snap.docs.map(d=>d.data());
setSyncDot(“home”,“ok”,“live sync on”);
renderSaved();
if(currentHomeTab===“analytics”) renderAnalytics();
}, err=>{
console.error(err);
setSyncDot(“home”,“err”,“connection failed”);
});
}

async function dbSave(plan){
plan.updated_at = new Date().toISOString();
await plansCol.doc(plan.id).set(plan);
}
async function dbDelete(id){
await plansCol.doc(id).delete();
}

/* ═══ HOME ═══ */
function homeTab(tab,btn){
currentHomeTab=tab;
document.querySelectorAll(”.home-nav-btn”).forEach(b=>b.classList.remove(“active”));
if(btn)btn.classList.add(“active”);
document.getElementById(“tab-plans”).style.display=tab===“plans”?“block”:“none”;
document.getElementById(“tab-analytics”).style.display=tab===“analytics”?“block”:“none”;
if(tab===“analytics”)renderAnalytics();
}

function goHome(){showScreen(“home”);renderSaved();}

function renderSaved(){
const list=document.getElementById(“saved-list”);
if(!plansCache.length){list.innerHTML=’<div class="no-data">No saved plans yet.</div>’;return;}
const sorted=[…plansCache].filter(p=>p.date).sort((a,b)=>b.date.localeCompare(a.date));
const undated=plansCache.filter(p=>!p.date);
list.innerHTML=[…sorted,…undated].map(p=>{
const t=TEMPLATES[p.templateId]||{};
return`<div class="saved-row" onclick="openPlan('${p.id}')"> <div> <div class="saved-day">${escHtml(t.display||p.templateId)}</div> <div class="saved-date">${p.date?fmtDate(p.date):"no date set"}</div> </div> <button class="del-btn" onclick="deletePlan(event,'${p.id}')">✕</button> </div>`;
}).join(””);
}

async function deletePlan(e,id){
e.stopPropagation();
if(!confirm(“Delete this plan?”))return;
await dbDelete(id);
}

/* ═══ ANALYTICS ═══ */
function renderAnalytics(){
const el=document.getElementById(“analytics-content”);
if(!plansCache.length){el.innerHTML=’<div class="no-data" style="padding:20px 0">No plans yet. Generate some class plans to see analytics here.</div>’;return;}
const filtered=analyticsLesson===“all”?plansCache:plansCache.filter(p=>p.templateId===analyticsLesson);
const sorted=[…filtered].filter(p=>p.date).sort((a,b)=>a.date.localeCompare(b.date));

el.innerHTML=`
<div class="analytics-title">analytics</div>
<div class="analytics-sub" style="margin-bottom:20px">tracking attendance & stunt performance over time</div>
<div class="lesson-tabs">
<div class=“lesson-tab${analyticsLesson===“all”?” active”:””}” onclick=“setAnalyticsLesson(‘all’)”>all lessons</div>
<div class=“lesson-tab${analyticsLesson===“monday”?” active”:””}” onclick=“setAnalyticsLesson(‘monday’)”>monday</div>
<div class=“lesson-tab${analyticsLesson===“wednesday”?” active”:””}” onclick=“setAnalyticsLesson(‘wednesday’)”>wednesday</div>
</div>

```
<div class="analytics-title">stunt group attendance</div>
<div class="analytics-sub">${sorted.length} lesson${sorted.length!==1?"s":""} tracked</div>
${renderAttTable(sorted)}

<div class="analytics-title">1st stunt performance</div>
<div class="analytics-sub">attempts & hit % per lesson</div>
${renderStuntPerLesson(sorted,"stunt1")}

<div class="analytics-title" style="margin-top:20px">2nd stunt performance</div>
<div class="analytics-sub">attempts & hit % per lesson</div>
${renderStuntPerLesson(sorted,"stunt2")}

<div class="analytics-title" style="margin-top:20px">overall stunt totals</div>
<div class="analytics-sub">combined across all selected lessons</div>
${renderStuntTotals(filtered,"stunt1","1st Stunt")}
${renderStuntTotals(filtered,"stunt2","2nd Stunt")}
```

`;
}

function setAnalyticsLesson(val){analyticsLesson=val;renderAnalytics();}

function renderAttTable(sorted){
if(!sorted.length)return’<div class="no-data">No data yet.</div>’;
return`<div class="att-table"> <div class="att-hd"><span>athlete</span><span>lessons</span><span>sessions</span><span>rate</span></div> ${ATHLETES.map(name=>{ const present=sorted.filter(p=>p.attendance&&p.attendance[name]).length; const pct=sorted.length?Math.round((present/sorted.length)*100):0; const dots=sorted.map(p=>`<div class=“att-dot” style=“background:${p.attendance&&p.attendance[name]?”#1a1a1a”:”#d8d7d5”}” title=”${fmtDateShort(p.date)}”></div>`).join(""); return`<div class="att-row">
<span style="font-size:12px;font-weight:500">${name}</span>
<div class="att-dots">${dots}</div>
<span style="font-size:11px;color:var(--stone);text-align:right">${present}/${sorted.length}</span>
<span style="font-size:12px;font-weight:600;text-align:right">${pct}%</span>
</div>`;
}).join(””)}

  </div>`;
}

function renderStuntPerLesson(sorted,stuntId){
const sp=sorted.filter(p=>p.sections&&p.sections.some(s=>s.categoryId===stuntId));
if(!sp.length)return’<div class="no-data">No data yet.</div>’;
return sp.map(plan=>{
const t=TEMPLATES[plan.templateId]||{};
const sec=plan.sections.find(s=>s.categoryId===stuntId);
if(!sec||!sec.stuntData)return””;
return`<div class="stunt-block"> <div class="stunt-block-hd"> <span style="font-family:'DM Serif Display',serif;font-size:14px;font-style:italic">${fmtDateShort(plan.date)}</span> <span style="font-size:9px;font-weight:600;letter-spacing:1.5px;text-transform:uppercase;color:var(--stone)">${t.display||""}</span> </div> <div class="stunt-hd-row"><span>athlete</span><span>att.</span><span>hits</span><span>rate</span><span>%</span></div> ${ATHLETES.map(name=>{ const d=sec.stuntData[name]||{}; const att=parseInt(d.attempts)||0; const hits=parseInt(d.hits)||0; const pct=att>0?Math.round((hits/att)*100):null; return`<div class="stunt-ath-row">
<span style="font-size:12px;font-weight:500">${name}</span>
<span style="font-size:12px;color:var(--stone)">${att||”—”}</span>
<span style="font-size:12px;color:var(--stone)">${hits||”—”}</span>
<div class="hit-bar-wrap"><div class="hit-bar" style="width:${pct||0}%"></div></div>
<span style="font-size:11px;font-weight:700;text-align:right">${pct!==null?pct+”%”:”—”}</span>
</div>`; }).join("")} </div>`;
}).join(””);
}

function renderStuntTotals(plans,stuntId,label){
const rp=plans.filter(p=>p.sections&&p.sections.some(s=>s.categoryId===stuntId));
if(!rp.length)return`<div class="no-data">${label}: no data yet.</div>`;
return`<div class="totals-card"> <div style="padding:10px 14px;background:var(--ink);color:var(--surface);font-size:10px;font-weight:600;letter-spacing:2px;text-transform:uppercase">${label}</div> <div class="totals-hd"><span>athlete</span><span>total att.</span><span>total hits</span><span>rate</span><span>%</span></div> ${ATHLETES.map(name=>{ let ta=0,th=0; rp.forEach(plan=>{const sec=plan.sections.find(s=>s.categoryId===stuntId);if(sec&&sec.stuntData&&sec.stuntData[name]){ta+=parseInt(sec.stuntData[name].attempts)||0;th+=parseInt(sec.stuntData[name].hits)||0;}}); const pct=ta>0?Math.round((th/ta)*100):null; return`<div class="totals-row">
<span style="font-size:12px;font-weight:500">${name}</span>
<span style="font-size:12px;color:var(--stone)">${ta||”—”}</span>
<span style="font-size:12px;color:var(--stone)">${th||”—”}</span>
<div class="hit-bar-wrap"><div class="hit-bar" style="width:${pct||0}%"></div></div>
<span style="font-size:11px;font-weight:700;text-align:right">${pct!==null?pct+”%”:”—”}</span>
</div>`;
}).join(””)}

  </div>`;
}

/* ═══ BUILDER ═══ */
function startBuilder(templateId,existingPlan){
currentTemplateId=templateId;
const t=TEMPLATES[templateId];
if(existingPlan){
currentPlanId=existingPlan.id;
sections=JSON.parse(JSON.stringify(existingPlan.sections||[]));
document.getElementById(“b-date”).value=existingPlan.date||””;
}else{
currentPlanId=uid();
sections=[];
document.getElementById(“b-date”).value=nextWeekday(templateId===“monday”?1:3);
}
pickedCat=null;
document.getElementById(“b-title”).textContent=templateId+”\nclass plan”;
document.getElementById(“b-time”).textContent=t.time;
document.getElementById(“b-total”).textContent=t.duration+” min total”;
setSyncDot(“builder”,””,””);
renderCatGrid();renderBuilderSections();updateTimebar();
showScreen(“builder”);
}

function onDateChange(){
const v=document.getElementById(“b-date”).value;
document.getElementById(“b-date-prev”).textContent=v?fmtDate(v):””;
updateTimebar();
if(v)autoSave();
}

function updateTimebar(){
const t=TEMPLATES[currentTemplateId];
const total=sections.reduce((s,x)=>s+(parseInt(x.duration)||0),0);
const pct=Math.min((total/t.duration)*100,100);
const over=total>t.duration;
const fill=document.getElementById(“b-prog”);
fill.style.width=pct+”%”;fill.style.background=over?”#b33a2d”:”#9a9a98”;
const used=document.getElementById(“b-used”);
used.textContent=total+” min”;used.className=over?“red”:””;
}

function renderCatGrid(){
document.getElementById(“cat-grid”).innerHTML=CATEGORIES.map(c=>
`<div class="cat-chip${pickedCat===c.id?" sel":""}" onclick="pickCat('${c.id}')"> <span class="cat-ic">${c.icon}</span><span>${c.label}</span> </div>`).join(””);
document.getElementById(“add-sec-btn”).disabled=!pickedCat;
}
function pickCat(id){pickedCat=(pickedCat===id)?null:id;renderCatGrid();}

function addSection(){
if(!pickedCat)return;
const cat=CATEGORIES.find(c=>c.id===pickedCat);
const sec={id:uid(),categoryId:pickedCat,duration:10,details:””,comments:””};
if(cat&&cat.stunt)sec.stuntData=Object.fromEntries(ATHLETES.map(n=>[n,{attempts:””,hits:””}]));
sections.push(sec);pickedCat=null;
renderCatGrid();renderBuilderSections();updateTimebar();
}
function removeSection(id){sections=sections.filter(s=>s.id!==id);renderBuilderSections();updateTimebar();}
function moveSection(i,d){const n=[…sections];[n[i],n[i+d]]=[n[i+d],n[i]];sections=n;renderBuilderSections();}
function setSectionDuration(id,val){const s=sections.find(s=>s.id===id);if(s)s.duration=val;renderBuilderSections();updateTimebar();}
function setSectionDetails(id,val){const s=sections.find(s=>s.id===id);if(s)s.details=val;}

function renderBuilderSections(){
const wrap=document.getElementById(“sections-wrap”);
const list=document.getElementById(“sections-list”);
if(!sections.length){wrap.style.display=“none”;return;}
wrap.style.display=“flex”;
list.innerHTML=sections.map((s,i)=>{
const cat=CATEGORIES.find(c=>c.id===s.categoryId)||{};
return`<div class="bsec"> <div class="bsec-top"> <div class="bsec-left"> <span class="bsec-num">${String(i+1).padStart(2,"0")}</span> <span class="cat-ic">${cat.icon||""}</span> <span class="bsec-lbl">${cat.label||""}</span> </div> <div class="bsec-actions"> <button class="ic-btn" onclick="moveSection(${i},-1)"${i===0?" disabled":""}>▲</button> <button class="ic-btn" onclick="moveSection(${i},1)"${i===sections.length-1?" disabled":""}>▼</button> <button class="ic-btn danger" onclick="removeSection('${s.id}')">✕</button> </div> </div> <div class="field-block"> <span class="lbl-xs">duration</span> <div class="tchips">${TIMES.map(t=>`<button class=“tchip${s.duration===t?” sel”:””}” onclick=“setSectionDuration(’${s.id}’,${t})”>${t}m</button>`).join("")}</div> </div> <div class="field-block"> <span class="lbl-xs">breakdown / details</span> <textarea class="ta" rows="2" placeholder="focus points, sequences..." oninput="setSectionDetails('${s.id}',this.value)">${escHtml(s.details||"")}</textarea> </div> </div>`;
}).join(””);
}

function buildPlanObj(){
return{
id:currentPlanId,
templateId:currentTemplateId,
date:document.getElementById(“b-date”).value,
sections:JSON.parse(JSON.stringify(sections)),
attendance:getPlan(currentPlanId)?.attendance||{},
};
}

async function autoSave(){
const plan=buildPlanObj();
setSyncDot(“builder”,“busy”,“saving…”);
try{await dbSave(plan);setSyncDot(“builder”,“ok”,“saved”);}
catch(e){console.error(e);setSyncDot(“builder”,“err”,“save failed”);}
}

async function savePlan(){
const plan=buildPlanObj();
setSyncDot(“builder”,“busy”,“saving…”);
try{
await dbSave(plan);
setSyncDot(“builder”,“ok”,“saved”);
openPlan(plan.id);
}catch(e){console.error(e);setSyncDot(“builder”,“err”,“save failed”);}
}

/* ═══ PLAN VIEW ═══ */
function openPlan(id){
// get freshest from cache
const plan=getPlan(id)||plansCache.find(p=>p.id===id);
if(!plan)return;
currentPlanId=id;
const t=TEMPLATES[plan.templateId]||{};
document.getElementById(“p-title”).textContent=`${(t.display||"").toLowerCase()}\nclass plan`;
document.getElementById(“p-time”).textContent=t.time||””;
document.getElementById(“p-date”).textContent=plan.date?fmtDate(plan.date):””;
const total=plan.sections.reduce((s,x)=>s+(parseInt(x.duration)||0),0);
document.getElementById(“p-dur”).textContent=`${total} min · ${t.duration} min total`;
setSyncDot(“plan”,“ok”,””);
renderAttendance(plan);
renderPlanSections(plan);
showScreen(“plan”);
}

function renderAttendance(plan){
document.getElementById(“attend-list”).innerHTML=ATHLETES.map(name=>{
const on=!!(plan.attendance&&plan.attendance[name]);
return`<div class="attend-item${on?" on":""}" onclick="toggleAttend('${name}')"> <span class="tick">${on?"✓":""}</span> <span class="aname">${name}</span> </div>`;
}).join(””);
}

async function toggleAttend(name){
const plan=getPlan(currentPlanId);if(!plan)return;
plan.attendance=plan.attendance||{};
plan.attendance[name]=!plan.attendance[name];
setSyncDot(“plan”,“busy”,“saving…”);
try{await dbSave(plan);setSyncDot(“plan”,“ok”,“saved”);}
catch{setSyncDot(“plan”,“err”,“save failed”);}
renderAttendance(plan);
}

function renderPlanSections(plan){
document.getElementById(“plan-sections”).innerHTML=plan.sections.map((sec,i)=>{
const cat=CATEGORIES.find(c=>c.id===sec.categoryId)||{};
let html=`<div class="plan-block"> <div class="plan-block-hd"> <div class="blk-left"> <span class="blk-num">${String(i+1).padStart(2,"0")}</span> <span class="cat-ic" style="font-size:11px;color:var(--putty)">${cat.icon||""}</span> <span class="blk-title">${cat.label||""}</span> </div> <span class="dur-tag">${sec.duration} min</span> </div> <div class="plan-block-body">`;
if(sec.details)html+=`<div class="plan-field"><div class="plan-field-lbl">breakdown</div><div class="detail-text">${escHtml(sec.details)}</div></div>`;
if(cat.stunt){
html+=`<div class="plan-field"><div class="plan-field-lbl">stunt tracking</div> <div class="stunt-tbl"> <div class="stunt-tbl-hd"><span>athlete</span><span>attempts</span><span>hits</span></div> ${ATHLETES.map(name=>`<div class="stunt-tbl-row">
<span class="sname">${name}</span>
<input type=“number” min=“0” class=“stunt-inp” placeholder=”—”
value=”${escHtml(String(sec.stuntData&&sec.stuntData[name]?sec.stuntData[name].attempts||””:””))}”
oninput=“updateStunt(’${sec.id}’,’${name}’,‘attempts’,this.value)”/>
<input type=“number” min=“0” class=“stunt-inp” placeholder=”—”
value=”${escHtml(String(sec.stuntData&&sec.stuntData[name]?sec.stuntData[name].hits||””:””))}”
oninput=“updateStunt(’${sec.id}’,’${name}’,‘hits’,this.value)”/>
</div>`).join("")} </div></div>`;
}
html+=`<div class="plan-field"><div class="plan-field-lbl">comments</div> <textarea class="plan-ta" rows="2" placeholder="notes from practice..." oninput="updateComment('${sec.id}',this.value)">${escHtml(sec.comments||"")}</textarea> </div></div></div>`;
return html;
}).join(””)+`<div class="end-mark">— end of plan —</div>`;
}

function scheduleCloudSave(){
clearTimeout(saveTimer);
saveTimer=setTimeout(async()=>{
const plan=getPlan(currentPlanId);if(!plan)return;
setSyncDot(“plan”,“busy”,“saving…”);
try{await dbSave(plan);setSyncDot(“plan”,“ok”,“saved”);}
catch{setSyncDot(“plan”,“err”,“save failed”);}
},1200);
}

function updateComment(secId,val){
const plan=getPlan(currentPlanId);if(!plan)return;
const s=plan.sections.find(s=>s.id===secId);if(s)s.comments=val;
scheduleCloudSave();
}
function updateStunt(secId,name,field,val){
const plan=getPlan(currentPlanId);if(!plan)return;
const s=plan.sections.find(s=>s.id===secId);if(!s)return;
s.stuntData=s.stuntData||{};
s.stuntData[name]=s.stuntData[name]||{attempts:””,hits:””};
s.stuntData[name][field]=val;
scheduleCloudSave();
}
function editPlan(){const plan=getPlan(currentPlanId);if(!plan)return;startBuilder(plan.templateId,plan);}

/* ─── INIT ─── */
startLiveSync();
</script>

</body>
</html>
