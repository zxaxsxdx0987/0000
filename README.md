[index.html](https://github.com/user-attachments/files/31815125/index.html)
# 0000<!doctype html>
<html lang="zh-Hant">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover" />
<meta name="theme-color" content="#111827" />
<meta name="description" content="澳門 9/5–9/8 互動旅遊行程" />
<title>澳門四天三夜｜旅伴共享行程</title>
<style>
:root{--bg:#f4f6f8;--card:#fff;--text:#172033;--muted:#667085;--line:#e6e8ec;--accent:#111827;--accent2:#2563eb;--good:#12a150;--warn:#f59e0b;--shadow:0 10px 28px rgba(16,24,40,.08);--r:20px}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:linear-gradient(180deg,#eef2f6 0,#f7f8fa 240px,#f4f6f8 100%);font-family:-apple-system,BlinkMacSystemFont,"Segoe UI","Noto Sans TC","PingFang TC","Microsoft JhengHei",sans-serif;color:var(--text)}
button,input{font:inherit}.wrap{max-width:980px;margin:auto;padding:20px 16px 48px}
.hero{background:linear-gradient(135deg,#111827,#24324a);color:#fff;border-radius:28px;padding:24px 22px;box-shadow:var(--shadow);position:relative;overflow:hidden}.hero:after{content:"";position:absolute;width:220px;height:220px;border-radius:50%;right:-80px;top:-80px;background:rgba(255,255,255,.08)}
.kicker{font-size:13px;letter-spacing:.08em;opacity:.78}.hero h1{margin:7px 0 8px;font-size:clamp(28px,7vw,48px);line-height:1.08}.hero p{margin:0;opacity:.86}.hero-actions{display:flex;gap:10px;flex-wrap:wrap;margin-top:18px;position:relative;z-index:1}.btn{border:0;border-radius:12px;padding:11px 14px;cursor:pointer;font-weight:700;transition:.18s;display:inline-flex;align-items:center;gap:7px}.btn:active{transform:translateY(1px)}.btn.light{background:#fff;color:#111827}.btn.ghost{background:rgba(255,255,255,.11);color:#fff;border:1px solid rgba(255,255,255,.18)}
.summary{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin:14px 0}.stat{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:13px;box-shadow:0 6px 18px rgba(16,24,40,.04)}.stat strong{display:block;font-size:21px}.stat span{font-size:12px;color:var(--muted)}
.toolbar{position:sticky;top:8px;z-index:10;background:rgba(247,248,250,.88);backdrop-filter:blur(12px);padding:8px 0;margin:4px 0 12px}.toolbar-inner{display:flex;gap:8px;overflow:auto}.day-btn{white-space:nowrap;border:1px solid var(--line);background:#fff;color:var(--muted);padding:10px 13px;border-radius:999px;cursor:pointer;font-weight:700}.day-btn.active{background:var(--accent);color:#fff;border-color:var(--accent)}
.day{margin:14px 0 18px;scroll-margin-top:76px}.day-head{display:flex;justify-content:space-between;align-items:end;gap:12px;margin-bottom:10px}.day-title{font-size:23px;font-weight:850}.day-sub{color:var(--muted);font-size:13px;margin-top:2px}.progress{width:140px;min-width:110px}.progress-label{display:flex;justify-content:space-between;color:var(--muted);font-size:11px;margin-bottom:4px}.bar{height:7px;background:#e7ebef;border-radius:99px;overflow:hidden}.bar > i{display:block;height:100%;background:var(--good);border-radius:99px;width:0%}
.item{background:var(--card);border:1px solid var(--line);border-radius:18px;box-shadow:0 5px 18px rgba(16,24,40,.035);margin:9px 0;overflow:hidden}.item-main{display:flex;gap:11px;padding:14px}.check{width:22px;height:22px;flex:0 0 22px;margin-top:1px;accent-color:var(--good)}.content{min-width:0;flex:1}.topline{display:flex;justify-content:space-between;gap:10px;align-items:start}.name{font-weight:800;line-height:1.45}.type{font-size:11px;border-radius:999px;padding:4px 8px;white-space:nowrap;background:#eef2ff;color:#3347a0}.type.food{background:#fff6e5;color:#9a6700}.type.spot{background:#ecfdf3;color:#16733a}.type.transport{background:#eef6ff;color:#1855a5}.notes{color:var(--muted);font-size:13px;line-height:1.6;margin:6px 0 0}.subitems{margin:8px 0 0;padding:0;list-style:none;display:grid;gap:6px}.subitems li{font-size:13px;padding-left:3px;color:#354052}.subitems li:before{content:"•";margin-right:7px;color:var(--accent2)}.item-foot{border-top:1px solid #f0f1f3;padding:10px 14px;display:flex;gap:7px;flex-wrap:wrap}.map{color:#175cd3;background:#eff6ff}.time{color:#6941c6;background:#f4f3ff}.mini{font-size:12px;padding:7px 10px;border-radius:9px;border:0;cursor:pointer;font-weight:700}.transport-box{margin-top:8px;background:#f8fafc;border:1px solid #e7ebef;border-radius:12px;padding:9px 10px;font-size:12px;line-height:1.65}.transport-main{font-weight:800}.transport-sub{color:var(--muted)}.transport-taxi{color:#8a5a00}.transport-bus{color:#1855a5}.transport-lrt{color:#5b3aa8}.transport-free{color:#16733a}.transport-walk{color:#475467}
.item.done{opacity:.63}.item.done .name{text-decoration:line-through}.empty{color:var(--muted);text-align:center;padding:20px}.footer{color:var(--muted);font-size:12px;text-align:center;margin-top:24px;line-height:1.7}.notice{background:#fff7ed;border:1px solid #fed7aa;color:#9a3412;border-radius:14px;padding:11px 13px;font-size:12px;margin-top:12px}
.modal-backdrop{position:fixed;inset:0;background:rgba(16,24,40,.48);display:none;align-items:end;justify-content:center;z-index:30}.modal-backdrop.show{display:flex}.modal{background:#fff;width:min(680px,100%);border-radius:24px 24px 0 0;padding:18px;max-height:88vh;overflow:auto}.modal h2{margin:0 0 8px}.modal p{color:var(--muted);font-size:13px;line-height:1.6}.row{display:flex;gap:8px;align-items:center;margin:10px 0}.row input{flex:1;border:1px solid var(--line);padding:10px 12px;border-radius:10px}.modal-actions{display:flex;gap:8px;justify-content:flex-end;flex-wrap:wrap;margin-top:14px}.close{background:#f2f4f7;border:0}.toast{position:fixed;left:50%;bottom:22px;transform:translateX(-50%) translateY(20px);background:#111827;color:#fff;padding:10px 14px;border-radius:999px;font-size:13px;opacity:0;pointer-events:none;transition:.25s;z-index:50}.toast.show{opacity:1;transform:translateX(-50%) translateY(0)}
@media(max-width:700px){.summary{grid-template-columns:repeat(2,1fr)}.progress{width:105px}.day-head{align-items:center}.hero{padding:21px 18px}.wrap{padding:12px 12px 42px}.name{font-size:15px}}
@media(min-width:701px){.day-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px}.day-grid .item{margin:0}.day-grid .item-wide{grid-column:1/-1}}
</style>
</head>
<body>
<div class="wrap">
  <header class="hero">
    <div class="kicker">MACAU TRIP · 2026 / 09 / 05 — 09 / 08</div>
    <h1>澳門四天三夜<br>旅伴共享行程 🇲🇴</h1>
    <p>吃吃喝喝 × 景點散步 × 買伴手禮｜大家可以各自勾選完成項目</p>
    <div class="hero-actions">
      <button class="btn light" id="shareBtn">🔗 分享行程</button>
      <button class="btn ghost" id="resetBtn">↺ 重設我的勾選</button>
    </div>
  </header>

  <div class="summary" id="summary"></div>
  <nav class="toolbar"><div class="toolbar-inner" id="dayNav"></div></nav>
  <main id="trip"></main>
  <div class="notice">📌 小提醒：這份 HTML 是「無需登入」版本；每位旅伴的勾選紀錄會保存在自己的裝置上。按「分享行程」即可把完整行程網址傳給大家。若之後想做到「所有人的勾選即時同步」，需要再接 Firebase / Supabase 之類的雲端資料庫。<br>🚌 交通策略：短距離以步行、跨區優先找免費接駁或輕軌；不方便或多人同行就直接搭的士。澳門公共巴士現金票價一般為 MOP 6。</div>
  <div class="footer">行程版本：2026/09/03 建立｜交通建議依 2026 年官方／公開資料整理，實際班次與接駁以當日公告為準｜地圖按鈕會開啟 Google Maps 搜尋</div>
</div>

<div class="modal-backdrop" id="modalBackdrop">
  <section class="modal">
    <h2>分享這趟澳門行程</h2>
    <p>把下面網址傳到 LINE 群組、Messenger 或其他旅伴群組即可。網址會包含目前的行程資料，勾選狀態不會共享。</p>
    <div class="row"><input id="shareUrl" readonly /></div>
    <div class="modal-actions"><button class="btn close" id="closeModal">關閉</button><button class="btn light" id="copyBtn">複製網址</button></div>
  </section>
</div>
<div class="toast" id="toast"></div>

<script>
const trip = [
 {day:'Day 1',date:'9/5 六',title:'抵達澳門・老城區散步・澳門旅遊塔',items:[
  {t:'搭乘 NX3497 抵達澳門機場，前往 YOHO 金銀島酒店寄放行李',type:'交通',tag:'transport',map:'YOHO金銀島酒店 澳門',transport:'計程車',transportClass:'taxi',transportNote:'最省事；機場直接到飯店，約 15–20 分鐘。機場搭的士另有 MOP 8 附加費。'},
  {t:'陳光記飯店',type:'正餐・午餐',tag:'food',map:'陳光記飯店 澳門',transport:'步行／的士',transportClass:'walk',transportNote:'市區短距離優先步行；剛下飛機、同行多人或天氣熱時改搭的士。'},
  {t:'議事亭前地 → 大三巴牌坊 → 戀愛巷',type:'景點',tag:'spot',map:'議事亭前地 澳門',notes:'老城區步行路線，可一路拍照、散步。',subs:['議事亭前地','大三巴牌坊','戀愛巷'],transport:'步行',transportClass:'walk',transportNote:'景點集中，直接一路走最順，不建議短距離搭車。'},
  {t:'瑪嘉烈蛋撻店',type:'點心',tag:'food',map:'瑪嘉烈蛋撻店 澳門',transport:'步行／的士',transportClass:'walk',transportNote:'看上一站位置決定；市中心移動以步行為主，天氣熱可改的士。'},
  {t:'英記餅家史諾比主題店',type:'點心・伴手禮',tag:'food',map:'英記餅家史諾比主題店 澳門',transport:'步行',transportClass:'walk',transportNote:'老城區內順路採買。'},
  {t:'錦記牛雜',type:'點心',tag:'food',map:'錦記牛雜 澳門',transport:'步行',transportClass:'walk',transportNote:'小吃巡迴以步行最方便。'},
  {t:'酥富匙 千層牛肉酥',type:'點心',tag:'food',map:'酥富匙 千層牛肉酥 澳門',transport:'步行',transportClass:'walk',transportNote:'與老城區小吃路線一起安排。'},
  {t:'鉅記手信',type:'伴手禮',tag:'food',map:'鉅記手信 澳門',transport:'步行',transportClass:'walk',transportNote:'逛街途中順手買，避免提著戰利品長距離搭車。'},
  {t:'返回 YOHO 金銀島酒店辦理入住・回房休息・放置戰利品',type:'住宿',tag:'transport',map:'YOHO金銀島酒店 澳門',transport:'步行／的士',transportClass:'walk',transportNote:'東西多建議直接的士；飯店就在亞馬喇前地一帶，公共交通非常方便。'},
  {t:'澳門旅遊塔',type:'景點',tag:'spot',map:'澳門旅遊塔',notes:'澳門地標；搭乘高速電梯至觀景台，安排夕陽與夜景。',transport:'公車 9A／32 或的士',transportClass:'bus',transportNote:'旅遊塔有 9A、32 等巴士可到；夕陽時段想省轉車時間，建議直接的士。'},
  {t:'贏到粥',type:'正餐・晚餐',tag:'food',map:'贏到粥 澳門',transport:'的士優先',transportClass:'taxi',transportNote:'晚餐時段多人同行，直接的士通常最省時間。'}
 ]},
 {day:'Day 2',date:'9/6 日',title:'威尼斯人・巴黎人・氹仔官也街',items:[
  {t:'世紀咖啡',type:'早餐',tag:'food',map:'世紀咖啡 澳門',transport:'步行',transportClass:'walk',transportNote:'飯店周邊步行最省事。'},
  {t:'澳門威尼斯人 & 巴黎人（巴黎鐵塔）',type:'景點',tag:'spot',map:'澳門威尼斯人 澳門',notes:'安排室內拍照、逛商場與巴黎鐵塔。',transport:'免費接駁優先／公車 25B・26A',transportClass:'free',transportNote:'優先查看當日娛樂場免費接駁；若無合適班次，再搭 25B、26A 等公共巴士。接駁班次與上車資格依當日官方安排。'},
  {t:'誠昌飯店',type:'正餐・午餐',tag:'food',map:'誠昌飯店 澳門',transport:'步行／的士',transportClass:'walk',transportNote:'若在威尼斯人／巴黎人附近，依實際位置步行或多人直接的士。'},
  {t:'官也街 & 龍環葡韻',type:'景點・吃點心',tag:'spot',map:'官也街 澳門',subs:['官也街逛街吃小吃','龍環葡韻散步拍照'],transport:'步行＋輕軌／公車',transportClass:'lrt',transportNote:'官也街與龍環葡韻適合步行串聯；官也街附近可搭多條巴士，排角站也是可利用的輕軌站。'},
  {t:'大利來記',type:'點心隨手買',tag:'food',map:'大利來記 官也街 澳門',transport:'步行',transportClass:'walk',transportNote:'官也街行程內直接步行。'},
  {t:'澤賢記雞蛋仔',type:'點心隨手買',tag:'food',map:'澤賢記雞蛋仔 澳門',transport:'步行',transportClass:'walk',transportNote:'官也街周邊以步行最順。'},
  {t:'安德魯餅店',type:'點心隨手買',tag:'food',map:'安德魯餅店 澳門',transport:'步行／的士',transportClass:'walk',transportNote:'若是官也街附近分店可步行；若特別要去路環門市，建議改搭的士。'}
 ]},
 {day:'Day 3',date:'9/7 一',title:'牛奶公司・teamLab・金光大道',items:[
  {t:'義順牛奶公司',type:'早餐',tag:'food',map:'義順牛奶公司 澳門',transport:'步行',transportClass:'walk',transportNote:'先在市區吃早餐最省時間。'},
  {t:'teamLab 超自然空間',type:'景點',tag:'spot',map:'teamLab 超自然空間 澳門',transport:'輕軌至路氹東站＋步行／的士',transportClass:'lrt',transportNote:'優先考慮輕軌；目前氹仔線包含路氹東站。若同行多人或不想走路，直接的士。'},
  {t:'附近逛街吃午餐',type:'正餐・午餐',tag:'food',notes:'午餐先不指定，依 teamLab 周邊實際體力與想吃的決定。',transport:'步行',transportClass:'walk',transportNote:'就在 teamLab／路氹商場周邊解決，避免再跨區。'},
  {t:'金光大道購物、影匯之星 8 字摩天輪',type:'景點',tag:'spot',map:'影匯之星 8 字摩天輪 澳門',notes:'購物＋拍照＋搭乘 8 字摩天輪。',transport:'步行＋輕軌／的士',transportClass:'lrt',transportNote:'都在路氹區時以步行＋輕軌為主；戰利品多或腳累就搭短程的士。'},
  {t:'福龍葡國餐廳',type:'正餐・晚餐',tag:'food',map:'福龍葡國餐廳 澳門',transport:'的士優先',transportClass:'taxi',transportNote:'晚餐直接搭的士，減少等車與轉車。'}
 ]},
 {day:'Day 4',date:'9/8 二',title:'媽閣廟・漁人碼頭・回程',items:[
  {t:'早餐（待定）',type:'早餐',tag:'food',transport:'步行',transportClass:'walk',transportNote:'建議找飯店附近早餐，保留回程緩衝。'},
  {t:'媽閣廟',type:'景點',tag:'spot',map:'媽閣廟 澳門',transport:'輕軌至媽閣站＋步行／的士',transportClass:'lrt',transportNote:'輕軌氹仔線目前包含媽閣站；若從飯店出發距離近或同行多人，也可直接的士。'},
  {t:'龍華茶樓',type:'正餐・午餐',tag:'food',map:'龍華茶樓 澳門',transport:'的士優先',transportClass:'taxi',transportNote:'媽閣逛完直接的士，省去轉車。'},
  {t:'澳門漁人碼頭',type:'景點',tag:'spot',map:'澳門漁人碼頭',transport:'公車 1A／3／10／32 等，或的士',transportClass:'bus',transportNote:'漁人碼頭官方列有多條巴士路線；若要準時回飯店取行李，建議的士。'},
  {t:'16:00 返回 YOHO 金銀島酒店取行李，搭計程車至機場（約 15 分鐘）',type:'交通',tag:'transport',map:'YOHO金銀島酒店 澳門',time:'16:00',transport:'計程車',transportClass:'taxi',transportNote:'最後一段不建議省車資；請預留塞車與機場報到時間。'},
  {t:'16:45 抵達機場，辦理 BR3498 登機；18:35 起飛',type:'交通・回程',tag:'transport',map:'澳門國際機場',time:'16:45',transport:'機場報到',transportClass:'taxi',transportNote:'抵達後直接辦理登機、安檢與候機。'}
 ]}
];

const KEY='macauTripChecked_v1';
let checked=JSON.parse(localStorage.getItem(KEY)||'{}');
const el=id=>document.getElementById(id);
function save(){localStorage.setItem(KEY,JSON.stringify(checked)); render();}
function mapUrl(q){return 'https://www.google.com/maps/search/?api=1&query='+encodeURIComponent(q);}
function render(){
  let total=0,done=0;
  el('dayNav').innerHTML='';
  trip.forEach((d,di)=>{
    const btn=document.createElement('button'); btn.className='day-btn'+(di===0?' active':''); btn.textContent=d.day+' · '+d.date; btn.onclick=()=>{document.querySelectorAll('.day-btn').forEach(x=>x.classList.remove('active'));btn.classList.add('active');document.getElementById('d'+di).scrollIntoView({behavior:'smooth',block:'start'});}; el('dayNav').appendChild(btn);
  });
  el('trip').innerHTML='';
  trip.forEach((d,di)=>{
    const section=document.createElement('section'); section.className='day'; section.id='d'+di;
    const count=d.items.length, dc=d.items.filter((_,ii)=>checked[di+'-'+ii]).length; total+=count; done+=dc;
    section.innerHTML=`<div class="day-head"><div><div class="day-title">${d.day} · ${d.date}</div><div class="day-sub">${d.title}</div></div><div class="progress"><div class="progress-label"><span>完成度</span><span>${dc}/${count}</span></div><div class="bar"><i style="width:${count?dc/count*100:0}%"></i></div></div></div>`;
    const grid=document.createElement('div'); grid.className='day-grid';
    d.items.forEach((item,ii)=>{
      const key=di+'-'+ii, doneIt=!!checked[key]; const card=document.createElement('article'); card.className='item'+(doneIt?' done':'')+(item.subs?' item-wide':'');
      card.innerHTML=`<div class="item-main"><input class="check" type="checkbox" ${doneIt?'checked':''} aria-label="完成 ${item.t}"><div class="content"><div class="topline"><div class="name">${item.t}</div><span class="type ${item.tag||''}">${item.type}</span></div>${item.notes?`<div class="notes">${item.notes}</div>`:''}${item.subs?`<ul class="subitems">${item.subs.map(s=>`<li>${s}</li>`).join('')}</ul>`:''}${item.transport?`<div class="transport-box"><div class="transport-main transport-${item.transportClass||'walk'}">🚌 推薦交通：${item.transport}</div><div class="transport-sub">${item.transportNote||''}</div></div>`:''}</div></div><div class="item-foot">${item.time?`<span class="mini time">⏰ ${item.time}</span>`:''}${item.map?`<button class="mini map" data-map="${item.map}">📍 開啟地圖</button>`:''}</div>`;
      card.querySelector('.check').addEventListener('change',e=>{checked[key]=e.target.checked;save();});
      const mb=card.querySelector('[data-map]'); if(mb)mb.addEventListener('click',()=>window.open(mapUrl(mb.dataset.map),'_blank','noopener'));
      grid.appendChild(card);
    }); section.appendChild(grid); el('trip').appendChild(section);
  });
  el('summary').innerHTML=`<div class="stat"><strong>${trip.length}</strong><span>天數</span></div><div class="stat"><strong>${total}</strong><span>行程項目</span></div><div class="stat"><strong>${done}</strong><span>我已完成</span></div><div class="stat"><strong>${total?Math.round(done/total*100):0}%</strong><span>我的完成率</span></div>`;
}
function toast(msg){const t=el('toast');t.textContent=msg;t.classList.add('show');clearTimeout(window._toast);window._toast=setTimeout(()=>t.classList.remove('show'),1800)}
el('shareBtn').onclick=async()=>{
  const isLocal = location.protocol === 'file:' || location.origin === 'null';
  if(isLocal){
    el('shareUrl').value='請先發布到 GitHub Pages；發布後這裡會自動顯示可分享的公開網址。';
    el('copyBtn').textContent='複製說明';
    el('modalBackdrop').classList.add('show');
    return;
  }
  const url = location.origin + location.pathname;
  el('shareUrl').value=url;
  el('copyBtn').textContent='複製網址';
  if(navigator.share){
    try{ await navigator.share({title:'澳門四天三夜｜旅伴共享行程 🇲🇴',text:'9/5–9/8 澳門旅遊行程',url}); return; }catch(e){}
  }
  el('modalBackdrop').classList.add('show');
};
el('closeModal').onclick=()=>el('modalBackdrop').classList.remove('show');
el('modalBackdrop').addEventListener('click',e=>{if(e.target===el('modalBackdrop'))el('modalBackdrop').classList.remove('show')});
el('copyBtn').onclick=async()=>{
  const text=el('shareUrl').value;
  try{await navigator.clipboard.writeText(text);toast(location.protocol==='file:'?'已複製說明！':'已複製分享網址！')}
  catch(e){el('shareUrl').select();document.execCommand('copy');toast(location.protocol==='file:'?'已複製說明！':'已複製分享網址！')}
};
el('resetBtn').onclick=()=>{if(confirm('只會清除你這台裝置上的完成勾選，不會影響其他旅伴。要重設嗎？')){checked={};save();toast('已重設你的勾選')}};
render();
</script>
</body>
</html>
