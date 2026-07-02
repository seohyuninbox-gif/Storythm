<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Book a meeting · Shannon Kim</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --ink:#1A1917;
  --muted:#6B7280;
  --border:#E5E3DF;
  --bg:#F5F3EE;
  --white:#FFFFFF;
  --indigo:#4F46E5;
  --indigo-hover:#4338CA;
  --indigo-bg:#EEF2FF;
  --indigo-border:#C7D2FE;
  --radius:10px;
}
body{font-family:'Inter',system-ui,sans-serif;background:var(--bg);color:var(--ink);min-height:100vh;display:flex;flex-direction:column}

/* ── Header ── */
header{background:var(--white);border-bottom:1px solid var(--border);padding:0 2rem;height:58px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:10}
.logo{font-family:'DM Serif Display',Georgia,serif;font-size:18px;color:var(--ink);letter-spacing:-.01em}
.logo em{font-style:normal;color:var(--indigo)}
.header-note{font-size:12px;color:var(--muted)}

/* ── Page ── */
main{flex:1;display:flex;align-items:flex-start;justify-content:center;padding:2.5rem 1.5rem}

/* ── Card ── */
.card{background:var(--white);border:1px solid var(--border);border-radius:16px;width:100%;max-width:820px;overflow:hidden;box-shadow:0 2px 20px rgba(0,0,0,.05)}
.card-header{padding:1.75rem 2rem;border-bottom:1px solid var(--border)}
.card-header h1{font-family:'DM Serif Display',Georgia,serif;font-size:28px;font-weight:400;margin-bottom:6px;letter-spacing:-.02em}
.meta{display:flex;align-items:center;gap:10px;flex-wrap:wrap}
.chip{background:var(--indigo-bg);color:var(--indigo);font-size:11px;font-weight:600;letter-spacing:.04em;text-transform:uppercase;padding:3px 9px;border-radius:20px}

/* ── Step bar ── */
.stepbar{display:flex;gap:4px;padding:0 2rem;height:3px;margin-bottom:0}
.stepbar-wrap{padding:10px 2rem 0;border-bottom:1px solid var(--border)}
.sp{height:3px;border-radius:2px;flex:1;background:var(--border);transition:background .3s}
.sp.active{background:var(--indigo)}
.sp.done{background:var(--indigo-border)}

/* ── Two-panel layout ── */
.panels{display:grid;grid-template-columns:1fr 1fr;min-height:380px}
.panel{padding:1.75rem 2rem}
.panel-left{border-right:1px solid var(--border)}
.sec{font-size:10px;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--muted);margin-bottom:14px}

/* ── Calendar ── */
.cal-nav{display:flex;align-items:center;justify-content:space-between;margin-bottom:14px}
.cal-mo{font-size:14px;font-weight:600;color:var(--ink)}
.nav-btn{background:none;border:1px solid var(--border);border-radius:7px;width:28px;height:28px;cursor:pointer;color:var(--muted);display:flex;align-items:center;justify-content:center;font-size:15px;transition:border-color .15s}
.nav-btn:hover{border-color:#9CA3AF;color:var(--ink)}
.nav-btn:disabled{opacity:.3;cursor:default;pointer-events:none}
.cal-grid{display:grid;grid-template-columns:repeat(7,1fr);gap:2px}
.dh{text-align:center;font-size:11px;font-weight:600;color:var(--muted);padding:5px 0}
.dc{aspect-ratio:1;display:flex;align-items:center;justify-content:center;border-radius:7px;font-size:13px;color:#D1CFC9;position:relative;transition:all .12s}
.dc.avail{color:var(--ink);cursor:pointer}
.dc.avail:hover{background:var(--indigo-bg);color:var(--indigo)}
.dc.active{background:var(--indigo);color:#fff;font-weight:600}
.dc.has-sel{font-weight:600}
.dc.has-sel::after{content:'';position:absolute;bottom:3px;left:50%;transform:translateX(-50%);width:4px;height:4px;border-radius:50%;background:var(--indigo)}
.dc.active.has-sel::after{background:rgba(255,255,255,.7)}

/* ── Time slots ── */
.no-date{text-align:center;padding:2.5rem 1rem;color:var(--muted)}
.no-date svg{width:32px;height:32px;margin:0 auto 12px;display:block;opacity:.35}
.no-date p{font-size:13px;line-height:1.6}
.slot-list{display:flex;flex-direction:column;gap:8px;margin-bottom:14px}
.slot-card{border:1.5px solid var(--border);border-radius:var(--radius);padding:13px 14px;cursor:pointer;display:flex;align-items:center;gap:12px;transition:all .15s;background:var(--white)}
.slot-card:hover{border-color:var(--indigo-border)}
.slot-card.sel{border-color:var(--indigo);background:var(--indigo-bg)}
.chk{width:18px;height:18px;border-radius:5px;border:1.5px solid var(--border);flex-shrink:0;display:flex;align-items:center;justify-content:center;transition:all .15s;background:var(--white)}
.slot-card.sel .chk{background:var(--indigo);border-color:var(--indigo)}
.chk-mark{display:none;width:5px;height:8px;border:2px solid #fff;border-top:none;border-left:none;transform:rotate(45deg) translate(-1px,-1px)}
.slot-card.sel .chk-mark{display:block}
.slot-time{font-size:14px;font-weight:500;color:var(--ink);transition:color .15s}
.slot-dur{font-size:12px;color:var(--muted)}
.slot-card.sel .slot-time{color:var(--indigo)}
.slot-card.sel .slot-dur{color:#818CF8}
.add-more-row{padding-top:2px}
.add-more{background:none;border:none;color:var(--indigo);font-size:13px;font-weight:500;cursor:pointer;font-family:inherit;padding:0;display:flex;align-items:center;gap:4px}
.add-more:hover{color:var(--indigo-hover)}
.add-more:disabled{opacity:.4;cursor:default}

/* ── Basket ── */
.basket{margin-top:1.25rem;padding-top:1.25rem;border-top:1px solid var(--border)}
.basket-title{font-size:11px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:var(--muted);margin-bottom:10px}
.basket-list{display:flex;flex-direction:column;gap:6px}
.basket-item{background:#F9F8F6;border:1px solid var(--border);border-radius:8px;padding:9px 12px;display:flex;align-items:flex-start;gap:10px}
.basket-content{flex:1}
.basket-date{font-size:12px;font-weight:600;color:var(--ink)}
.basket-slots{font-size:12px;color:var(--muted);margin-top:2px;line-height:1.5}
.del-btn{background:none;border:none;color:var(--muted);cursor:pointer;padding:0;font-size:14px;opacity:.6;line-height:1;flex-shrink:0;margin-top:1px}
.del-btn:hover{color:#EF4444;opacity:1}

/* ── Form step ── */
.form-wrap{padding:1.75rem 2rem}
.booking-summary{background:#F9F8F6;border:1px solid var(--border);border-radius:var(--radius);padding:14px 16px;margin-bottom:1.5rem}
.bs-title{font-size:12px;font-weight:600;color:var(--muted);margin-bottom:8px;text-transform:uppercase;letter-spacing:.06em}
.bs-item{display:flex;gap:8px;font-size:13px;color:var(--ink);padding:3px 0}
.bs-dot{color:var(--indigo);margin-top:1px;flex-shrink:0}
.fi{margin-bottom:16px}
.fi label{display:block;font-size:12px;font-weight:600;color:var(--muted);margin-bottom:6px}
.fi input,.fi textarea{width:100%;border:1.5px solid var(--border);border-radius:8px;padding:10px 13px;font-size:14px;font-family:'Inter',sans-serif;color:var(--ink);background:#FAFAF8;outline:none;transition:border .15s,background .15s}
.fi input:focus,.fi textarea:focus{border-color:var(--indigo);background:var(--white);box-shadow:0 0 0 3px var(--indigo-bg)}
.fi textarea{resize:none;height:78px}
.fi-row{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.btn-row{display:flex;gap:10px;align-items:center;margin-top:4px}
.btn-p{background:var(--indigo);color:#fff;border:none;border-radius:8px;padding:11px 22px;font-size:14px;font-weight:500;cursor:pointer;font-family:inherit;transition:background .15s;white-space:nowrap}
.btn-p:hover{background:var(--indigo-hover)}
.btn-p:disabled{opacity:.45;cursor:default}
.btn-g{background:none;border:1.5px solid var(--border);color:var(--muted);border-radius:8px;padding:10px 18px;font-size:14px;cursor:pointer;font-family:inherit;transition:all .15s}
.btn-g:hover{border-color:#9CA3AF;color:var(--ink)}

/* ── Result ── */
.result-wrap{padding:3.5rem 2rem;text-align:center}
.result-icon{font-size:52px;margin-bottom:18px}
.result-title{font-family:'DM Serif Display',Georgia,serif;font-size:26px;font-weight:400;margin-bottom:10px;color:var(--ink)}
.result-msg{font-size:14px;color:var(--muted);line-height:1.8;max-width:380px;margin:0 auto 24px}
.result-items{display:flex;flex-direction:column;gap:8px;max-width:420px;margin:0 auto 28px;text-align:left}
.ri{padding:11px 14px;border-radius:8px;font-size:13px;line-height:1.5;display:flex;gap:10px;align-items:flex-start}
.ri.ok{background:#F0FDF4;border:1px solid #BBF7D0;color:#166534}
.ri.fail{background:#FFF7ED;border:1px solid #FED7AA;color:#92400E}
.ri-icon{flex-shrink:0;margin-top:1px}

/* ── Loading spinner ── */
.spin{display:inline-block;width:14px;height:14px;border:2px solid rgba(255,255,255,.35);border-top-color:#fff;border-radius:50%;animation:spin .6s linear infinite;vertical-align:middle;margin-right:6px}
@keyframes spin{to{transform:rotate(360deg)}}

/* ── Footer ── */
footer{text-align:center;padding:1.5rem;font-size:12px;color:var(--muted)}

/* ── Mobile ── */
@media(max-width:600px){
  .panels{grid-template-columns:1fr}
  .panel-left{border-right:none;border-bottom:1px solid var(--border)}
  .card-header h1{font-size:22px}
  .fi-row{grid-template-columns:1fr}
  main{padding:1.5rem 1rem}
}
</style>
</head>
<body>

<header>
  <div class="logo">Shannon <em>Kim</em></div>
  <div class="header-note">Jul 16 – Aug 16 · KST</div>
</header>

<main>
  <div class="card" id="card">

    <div class="card-header">
      <h1>Book a meeting</h1>
      <div class="meta">
        <span class="chip">2 hours per session</span>
        <span class="chip">Tue · Thu · Sat · Sun only</span>
        <span class="chip">Korea Standard Time</span>
      </div>
    </div>

    <div class="stepbar-wrap" id="stepbar-wrap">
      <div class="stepbar" id="stepbar"></div>
    </div>

    <div id="content"></div>

  </div>
</main>

<footer>Powered by Google Calendar — slots update in real time</footer>

<script>
const SLOTS=[
  {id:'a',label:'10:00 AM – 12:00 PM',start:'10:00',end:'12:00'},
  {id:'b',label:'1:00 PM – 3:00 PM',start:'13:00',end:'15:00'},
  {id:'c',label:'3:30 PM – 5:30 PM',start:'15:30',end:'17:30'}
];
const ALLOWED=new Set([0,2,4,6]);
const MONTHS=['January','February','March','April','May','June','July','August','September','October','November','December'];
const DAYS=['Su','Mo','Tu','We','Th','Fr','Sa'];

let step=1,calY=2026,calM=6,activeDate=null;
let selections={};
let form={name:'',email:'',notes:''};
let loading=false,results=[];

function dateKey(d){return`${d.getFullYear()}-${d.getMonth()}-${d.getDate()}`}
function selectable(d){
  if(!d) return false;
  const c=new Date(d.getFullYear(),d.getMonth(),d.getDate());
  return c>=new Date(2026,6,16)&&c<=new Date(2026,7,16)&&ALLOWED.has(d.getDay());
}
function fmtDate(d){return d.toLocaleDateString('en-US',{weekday:'short',month:'short',day:'numeric'})}
function fmtDateLong(d){return d.toLocaleDateString('en-US',{weekday:'long',month:'long',day:'numeric'})}
function totalSlots(){return Object.values(selections).reduce((s,v)=>s+v.slots.size,0)}

function renderStepbar(){
  const sb=document.getElementById('stepbar');
  sb.innerHTML=[1,2,3].map(s=>`<div class="sp${s===step?' active':s<step?' done':''}"></div>`).join('');
}

function renderCal(){
  const first=new Date(calY,calM,1).getDay();
  const days=new Date(calY,calM+1,0).getDate();
  const cells=[];
  for(let i=0;i<first;i++) cells.push(null);
  for(let d=1;d<=days;d++) cells.push(new Date(calY,calM,d));
  const canPrev=!(calY===2026&&calM===6);
  const canNext=!(calY===2026&&calM===7);
  return`<div class="cal-nav">
    <button class="nav-btn" id="prev" ${!canPrev?'disabled':''}>&#8249;</button>
    <span class="cal-mo">${MONTHS[calM]} ${calY}</span>
    <button class="nav-btn" id="next" ${!canNext?'disabled':''}>&#8250;</button>
  </div>
  <div class="cal-grid">
    ${DAYS.map(d=>`<div class="dh">${d}</div>`).join('')}
    ${cells.map(d=>{
      if(!d) return'<div class="dc"></div>';
      const av=selectable(d);
      const key=dateKey(d);
      const isActive=activeDate&&dateKey(activeDate)===key;
      const hasSel=selections[key]&&selections[key].slots.size>0;
      return`<div class="dc${av?' avail':''}${isActive?' active':''}${hasSel?' has-sel':''}" data-ts="${d.getTime()}">${d.getDate()}</div>`;
    }).join('')}
  </div>`;
}

function renderSlots(){
  if(!activeDate) return`<div class="no-date">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><rect x="3" y="4" width="18" height="18" rx="2"/><path d="M16 2v4M8 2v4M3 10h18"/></svg>
    <p>Pick a date on the calendar<br>to see available times</p>
  </div>`;
  const key=dateKey(activeDate);
  const selSet=(selections[key]&&selections[key].slots)||new Set();
  return`<div class="sec">${fmtDateLong(activeDate)}</div>
  <div class="slot-list">
    ${SLOTS.map(s=>`<div class="slot-card${selSet.has(s.id)?' sel':''}" data-slot="${s.id}">
      <div class="chk"><div class="chk-mark"></div></div>
      <div><div class="slot-time">${s.label}</div><div class="slot-dur">2-hour session · KST</div></div>
    </div>`).join('')}
  </div>`;
}

function renderBasket(){
  const entries=Object.values(selections).filter(v=>v.slots.size>0);
  if(!entries.length) return'';
  return`<div class="basket">
    <div class="basket-title">Selected (${totalSlots()} slot${totalSlots()>1?'s':''})</div>
    <div class="basket-list">
      ${entries.map(e=>{
        const key=dateKey(e.date);
        const slotLabels=[...e.slots].map(id=>SLOTS.find(s=>s.id===id).label).join('<br>');
        return`<div class="basket-item">
          <div class="basket-content">
            <div class="basket-date">${fmtDate(e.date)}</div>
            <div class="basket-slots">${slotLabels}</div>
          </div>
          <button class="del-btn" data-key="${key}" title="Remove">✕</button>
        </div>`;
      }).join('')}
    </div>
  </div>`;
}

function renderStep1(){
  return`<div class="panels">
    <div class="panel panel-left">
      <div class="sec">Choose dates</div>
      ${renderCal()}
    </div>
    <div class="panel">
      ${renderSlots()}
      ${renderBasket()}
    </div>
  </div>
  <div style="padding:1.25rem 2rem;border-top:1px solid var(--border);display:flex;justify-content:flex-end">
    <button class="btn-p" id="to2" ${totalSlots()===0?'disabled':''}>
      Continue with ${totalSlots()||''} slot${totalSlots()!==1?'s':''} &#8250;
    </button>
  </div>`;
}

function buildSummaryItems(){
  return Object.values(selections).filter(v=>v.slots.size>0).map(e=>{
    return[...e.slots].map(sid=>{
      const slot=SLOTS.find(s=>s.id===sid);
      return`<div class="bs-item"><span class="bs-dot">·</span><span><strong>${fmtDate(e.date)}</strong> &nbsp;${slot.label}</span></div>`;
    }).join('');
  }).join('');
}

function renderStep2(){
  return`<div class="form-wrap">
    <div class="booking-summary">
      <div class="bs-title">Your selected times</div>
      ${buildSummaryItems()}
    </div>
    <div class="fi-row">
      <div class="fi"><label>First name</label><input id="f-fname" placeholder="First" value="${form.fname||''}"></div>
      <div class="fi"><label>Last name</label><input id="f-lname" placeholder="Last" value="${form.lname||''}"></div>
    </div>
    <div class="fi"><label>Email address</label><input id="f-email" type="email" placeholder="you@example.com" value="${form.email}"></div>
    <div class="fi"><label>What's this meeting about? <span style="font-weight:400;color:#9CA3AF">(optional)</span></label>
    <textarea id="f-notes" placeholder="Brief topic, agenda, or anything useful to know…">${form.notes}</textarea></div>
    <div class="btn-row">
      <button class="btn-p" id="book" ${loading?'disabled':''}>${loading?'<span class="spin"></span>Booking…':'Confirm all meetings'}</button>
      <button class="btn-g" id="back2">&#8249; Back</button>
    </div>
  </div>`;
}

function renderStep3(){
  const allOk=results.every(r=>r.booked);
  const anyOk=results.some(r=>r.booked);
  return`<div class="result-wrap">
    <div class="result-icon">${allOk?'🎉':anyOk?'⚠️':'❌'}</div>
    <div class="result-title">${allOk?'You\'re all set!':anyOk?'Partially booked':'Something went wrong'}</div>
    <p class="result-msg">${allOk?`All meetings are confirmed. Calendar invites will be sent to <strong>${form.email}</strong>.`:anyOk?'Some slots were booked — see details below.':'Please try again or choose different times.'}</p>
    <div class="result-items">
      ${results.map(r=>`<div class="ri ${r.booked?'ok':'fail'}">
        <span class="ri-icon">${r.booked?'✓':'✕'}</span>
        <span><strong>${fmtDate(r.date)}</strong> · ${r.slot.label}<br><span style="opacity:.75;font-size:12px">${r.message||''}</span></span>
      </div>`).join('')}
    </div>
    ${!allOk?`<button class="btn-p" id="retry">Try again</button>`:''}
  </div>`;
}

function render(){
  renderStepbar();
  const c=document.getElementById('content');
  if(step===1) c.innerHTML=renderStep1();
  else if(step===2) c.innerHTML=renderStep2();
  else c.innerHTML=renderStep3();
  bind();
}

function bind(){
  const q=id=>document.getElementById(id);
  if(q('prev')) q('prev').onclick=()=>{if(!(calY===2026&&calM===6)){calM--;if(calM<0){calM=11;calY--;}render();}};
  if(q('next')) q('next').onclick=()=>{if(!(calY===2026&&calM===7)){calM++;if(calM>11){calM=0;calY++;}render();}};

  document.querySelectorAll('.dc.avail').forEach(el=>{
    el.onclick=()=>{activeDate=new Date(parseInt(el.dataset.ts));render();};
  });

  document.querySelectorAll('.slot-card').forEach(el=>{
    el.onclick=()=>{
      if(!activeDate) return;
      const key=dateKey(activeDate);
      if(!selections[key]) selections[key]={date:activeDate,slots:new Set()};
      const sid=el.dataset.slot;
      if(selections[key].slots.has(sid)) selections[key].slots.delete(sid);
      else selections[key].slots.add(sid);
      if(selections[key].slots.size===0) delete selections[key];
      render();
    };
  });

  document.querySelectorAll('.del-btn').forEach(el=>{
    el.onclick=()=>{delete selections[el.dataset.key];render();};
  });

  if(q('to2')) q('to2').onclick=()=>{step=2;render();};
  if(q('back2')) q('back2').onclick=()=>{step=1;render();};
  if(q('retry')) q('retry').onclick=()=>{step=1;selections={};activeDate=null;results=[];render();};

  // Form inputs — preserve on re-render
  ['f-fname','f-lname','f-email','f-notes'].forEach(id=>{
    const el=q(id);
    if(el) el.oninput=e=>{
      const key=id.replace('f-','');
      form[key]=e.target.value;
      // update continue button state
      const btn=q('book');
      if(btn) btn.disabled=loading||!form.fname||!form.lname||!form.email;
    };
  });

  if(q('book')){
    // Restore values after render
    if(q('f-fname')) q('f-fname').value=form.fname||'';
    if(q('f-lname')) q('f-lname').value=form.lname||'';
    if(q('f-email')) q('f-email').value=form.email||'';
    if(q('f-notes')) q('f-notes').value=form.notes||'';
    q('book').disabled=loading||!form.fname||!form.lname||!form.email;
    q('book').onclick=book;
  }
}

async function book(){
  loading=true;render();
  const entries=[];
  Object.values(selections).filter(v=>v.slots.size>0).forEach(e=>{
    [...e.slots].forEach(sid=>entries.push({date:e.date,slot:SLOTS.find(s=>s.id===sid)}));
  });

  const guestName=`${form.fname} ${form.lname}`.trim();
  const bookings=entries.map(e=>{
    const ds=e.date.toISOString().split('T')[0];
    return{date:e.date,slot:e.slot,start:`${ds}T${e.slot.start}:00+09:00`,end:`${ds}T${e.slot.end}:00+09:00`};
  });

  const prompt=`Shannon Kim's visitor wants to book ${bookings.length} meeting(s).

Visitor: ${guestName} <${form.email}>
Notes: ${form.notes||'None'}

Meetings to book:
${bookings.map((b,i)=>`${i+1}. ${fmtDateLong(b.date)}, ${b.slot.label} KST\n   Start: ${b.start}\n   End: ${b.end}`).join('\n')}

For each meeting:
1. Check Shannon's primary Google Calendar for conflicts in that window.
2. If free, create an event titled "Meeting with ${guestName}", add ${form.email} as a guest, include the notes in the description.
3. Process all ${bookings.length} meeting(s).

Return ONLY a JSON array, one object per meeting in order:
[{"booked":true/false,"conflict":true/false,"message":"brief status"}]`;

  try{
    const res=await fetch('https://api.anthropic.com/v1/messages',{
      method:'POST',
      headers:{'Content-Type':'application/json'},
      body:JSON.stringify({
        model:'claude-sonnet-4-6',
        max_tokens:2000,
        system:'You are Shannon Kim\'s calendar assistant. Always respond ONLY with valid JSON, no markdown, no preamble.',
        messages:[{role:'user',content:prompt}],
        mcp_servers:[{type:'url',url:'https://calendarmcp.googleapis.com/mcp/v1',name:'gcal'}]
      })
    });
    const data=await res.json();
    const text=data.content.filter(b=>b.type==='text').map(b=>b.text).join('');
    const parsed=JSON.parse(text.replace(/```json|```/g,'').trim());
    results=bookings.map((b,i)=>({...b,...parsed[i]}));
  }catch(e){
    results=bookings.map(b=>({...b,booked:false,message:'Unable to book — please try again.'}));
  }
  loading=false;step=3;render();
}

render();
</script>
</body>
</html>
