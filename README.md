<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>星盤識人學｜珮慈老師 · 6人小班 · 7/4開課</title>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+TC:wght@300;400;500;600;700;900&family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&display=swap" rel="stylesheet">
<style>
:root {
  --gold: #c9a96e;
  --gold-light: #e8d5b0;
  --purple-deep: #0f0520;
  --purple-mid: #1a0535;
  --purple-soft: #2d0d5c;
  --text-primary: #f0e6d3;
  --text-secondary: #d4c4a8;
  --text-dim: rgba(212,196,168,0.55);
}
*{box-sizing:border-box;margin:0;padding:0;}
html{scroll-behavior:smooth;}
body{background:var(--purple-deep);color:var(--text-primary);font-family:'Noto Serif TC',serif;line-height:1.8;overflow-x:hidden;}
body::before{content:'';position:fixed;inset:0;background-image:radial-gradient(1px 1px at 5% 8%,rgba(255,255,255,0.6) 0%,transparent 100%),radial-gradient(1px 1px at 15% 25%,rgba(201,169,110,0.4) 0%,transparent 100%),radial-gradient(1.5px 1.5px at 22% 55%,rgba(255,255,255,0.5) 0%,transparent 100%),radial-gradient(1px 1px at 35% 12%,rgba(255,255,255,0.4) 0%,transparent 100%),radial-gradient(1px 1px at 58% 72%,rgba(255,255,255,0.5) 0%,transparent 100%),radial-gradient(1px 1px at 75% 45%,rgba(201,169,110,0.35) 0%,transparent 100%),radial-gradient(1px 1px at 90% 32%,rgba(255,255,255,0.5) 0%,transparent 100%),radial-gradient(1px 1px at 42% 90%,rgba(255,255,255,0.4) 0%,transparent 100%),radial-gradient(1px 1px at 67% 18%,rgba(255,255,255,0.4) 0%,transparent 100%),radial-gradient(1px 1px at 12% 82%,rgba(255,255,255,0.3) 0%,transparent 100%);pointer-events:none;z-index:0;}
section{position:relative;z-index:1;}

/* URGENT BANNER */
.urgent-banner{background:linear-gradient(135deg,#8b1a1a,#c0392b);text-align:center;padding:12px 20px;font-size:14px;font-weight:700;letter-spacing:1px;color:#fff;position:relative;z-index:200;}
.urgent-banner span{color:#ffd700;}

/* NAV */
nav{position:fixed;top:36px;left:0;right:0;z-index:100;padding:16px 40px;display:flex;justify-content:space-between;align-items:center;background:rgba(15,5,32,0.92);backdrop-filter:blur(12px);border-bottom:1px solid rgba(201,169,110,0.15);}
.nav-brand{font-family:'Cormorant Garamond',serif;font-size:17px;color:var(--gold);letter-spacing:3px;}
.nav-cta{background:var(--gold);color:var(--purple-deep);padding:9px 24px;font-size:13px;font-weight:700;letter-spacing:1px;cursor:pointer;font-family:'Noto Serif TC',serif;text-decoration:none;transition:all 0.3s;border:none;}
.nav-cta:hover{transform:translateY(-1px);box-shadow:0 4px 20px rgba(201,169,110,0.4);}

/* HERO */
.hero{min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:160px 40px 80px;background:radial-gradient(ellipse at 30% 50%,rgba(45,13,92,0.8) 0%,transparent 60%);}
.hero-ring{position:absolute;border-radius:50%;border:1px solid rgba(201,169,110,0.08);top:50%;left:50%;transform:translate(-50%,-50%);pointer-events:none;}
.hero-tag{font-family:'Cormorant Garamond',serif;font-size:13px;letter-spacing:5px;color:var(--gold);margin-bottom:28px;opacity:0;animation:fadeUp 0.8s ease forwards 0.2s;}
.hero-main{font-size:clamp(24px,4vw,52px);font-weight:900;line-height:1.3;margin-bottom:20px;opacity:0;animation:fadeUp 0.8s ease forwards 0.4s;}
.hero-big-quote{font-family:'Cormorant Garamond',serif;font-size:clamp(36px,6.5vw,76px);font-style:italic;color:var(--gold);display:block;margin:10px 0;text-shadow:0 0 40px rgba(201,169,110,0.3);}
.hero-sub{font-size:17px;color:var(--text-secondary);max-width:580px;margin-bottom:14px;font-weight:300;line-height:2;opacity:0;animation:fadeUp 0.8s ease forwards 0.6s;}
.hero-urgency{display:inline-flex;align-items:center;gap:10px;background:rgba(139,26,26,0.3);border:1px solid rgba(255,80,80,0.4);padding:10px 22px;margin-bottom:32px;font-size:14px;color:#ff9999;letter-spacing:1px;opacity:0;animation:fadeUp 0.8s ease forwards 0.7s;}
.urgency-dot{width:8px;height:8px;border-radius:50%;background:#ff5555;flex-shrink:0;animation:blink 1.5s ease infinite;}
.hero-btn{display:inline-block;background:linear-gradient(135deg,var(--gold),#a07840);color:var(--purple-deep);font-size:16px;font-weight:700;padding:18px 52px;letter-spacing:2px;cursor:pointer;font-family:'Noto Serif TC',serif;text-decoration:none;transition:all 0.3s;border:none;opacity:0;animation:fadeUp 0.8s ease forwards 0.8s;}
.hero-btn:hover{transform:translateY(-2px);box-shadow:0 8px 30px rgba(201,169,110,0.4);}
.hero-note{font-size:12px;color:var(--text-dim);margin-top:12px;font-family:'Cormorant Garamond',serif;font-style:italic;opacity:0;animation:fadeUp 0.8s ease forwards 0.9s;}
.hero-scroll{position:absolute;bottom:32px;left:50%;transform:translateX(-50%);font-size:11px;letter-spacing:3px;color:var(--text-dim);font-family:'Cormorant Garamond',serif;animation:pulse 2s ease infinite;}

/* SHARED */
.section-label{font-family:'Cormorant Garamond',serif;font-size:12px;letter-spacing:5px;color:var(--gold);text-transform:uppercase;margin-bottom:14px;display:block;}
.section-title{font-size:clamp(22px,3.5vw,36px);font-weight:700;line-height:1.4;margin-bottom:36px;}
.gold-divider{width:80px;height:1px;background:linear-gradient(90deg,transparent,var(--gold),transparent);margin:0 auto;}
.reveal{opacity:0;transform:translateY(36px);transition:opacity 0.8s ease,transform 0.8s ease;}
.reveal.visible{opacity:1;transform:translateY(0);}
.inner{max-width:860px;margin:0 auto;}

/* STORY */
.story{padding:100px 40px;background:radial-gradient(ellipse at 60% 40%,rgba(45,13,92,0.5) 0%,transparent 60%);}
.story-text{font-size:18px;line-height:2.5;color:var(--text-secondary);font-family:'Cormorant Garamond',serif;border-left:2px solid rgba(201,169,110,0.3);padding-left:28px;margin:32px 0;}
.story-text strong{color:var(--text-primary);}
.story-text .gw{color:var(--gold);font-style:italic;}

/* PAIN */
.pain{padding:100px 40px;}
.pain-grid{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-top:36px;}
.pain-item{background:rgba(45,13,92,0.4);border:1px solid rgba(201,169,110,0.18);border-left:3px solid var(--gold);padding:18px 20px;font-size:15px;color:var(--text-secondary);line-height:1.9;}

/* DIFF */
.diff{padding:100px 40px;background:radial-gradient(ellipse at 30% 50%,rgba(45,13,92,0.4) 0%,transparent 60%);}
.diff-table{width:100%;border-collapse:collapse;margin-top:36px;table-layout:fixed;}
.diff-table th{padding:16px 24px;font-size:14px;letter-spacing:2px;font-family:'Cormorant Garamond',serif;}
.diff-table th:first-child{color:var(--text-dim);background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.08);}
.diff-table th:last-child{color:var(--purple-deep);background:var(--gold);}
.diff-table td{padding:14px 24px;font-size:14px;border-bottom:1px solid rgba(201,169,110,0.08);line-height:1.8;vertical-align:top;overflow-wrap:break-word;word-wrap:break-word;}
.diff-table td:first-child{color:var(--text-dim);background:rgba(255,255,255,0.02);border-right:1px solid rgba(255,255,255,0.08);}
.diff-table td:last-child{color:var(--text-primary);background:rgba(201,169,110,0.06);font-weight:600;word-break:keep-all;}
.diff-check{color:var(--gold);margin-right:8px;}

/* TEACHER */
.teacher{padding:100px 40px;}
.teacher-inner{max-width:860px;margin:0 auto;}
.teacher-layout{display:grid;grid-template-columns:320px 1fr;gap:60px;align-items:center;margin-top:36px;}
.teacher-photo-wrap{position:relative;}
.teacher-photo{width:100%;aspect-ratio:3/4;object-fit:cover;object-position:top;border:1px solid rgba(201,169,110,0.3);display:block;}
.teacher-photo-placeholder{width:100%;aspect-ratio:3/4;background:rgba(45,13,92,0.6);border:1px solid rgba(201,169,110,0.3);display:flex;flex-direction:column;align-items:center;justify-content:center;color:var(--text-dim);font-size:13px;gap:12px;}
.teacher-photo-frame{position:absolute;top:-8px;left:-8px;right:8px;bottom:8px;border:1px solid rgba(201,169,110,0.15);pointer-events:none;}
.teacher-name{font-size:28px;font-weight:900;color:var(--text-primary);margin-bottom:4px;}
.teacher-title{font-size:14px;color:var(--gold);letter-spacing:2px;margin-bottom:24px;font-family:'Cormorant Garamond',serif;}
.teacher-bio{font-size:15px;color:var(--text-secondary);line-height:2;margin-bottom:24px;}
.teacher-creds{list-style:none;}
.teacher-cred{display:flex;align-items:flex-start;gap:12px;padding:8px 0;border-bottom:1px solid rgba(201,169,110,0.08);font-size:14px;color:var(--text-secondary);}
.teacher-cred:last-child{border-bottom:none;}
.cred-dot{color:var(--gold);flex-shrink:0;margin-top:3px;}

/* CURRICULUM */
.curriculum{padding:100px 40px;background:radial-gradient(ellipse at 70% 50%,rgba(45,13,92,0.4) 0%,transparent 60%);}
.curr-grid{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-top:36px;}
.curr-card{background:rgba(15,5,32,0.8);border:1px solid rgba(201,169,110,0.2);padding:30px 26px;position:relative;overflow:hidden;transition:border-color 0.3s;}
.curr-card:hover{border-color:rgba(201,169,110,0.5);}
.curr-card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,transparent,var(--gold),transparent);}
.curr-day{font-family:'Cormorant Garamond',serif;font-size:12px;letter-spacing:4px;color:var(--gold);margin-bottom:8px;}
.curr-title{font-size:19px;font-weight:700;margin-bottom:6px;}
.curr-sub{font-size:12px;color:var(--gold);margin-bottom:14px;font-style:italic;font-family:'Cormorant Garamond',serif;}
.curr-items{list-style:none;font-size:13px;color:var(--text-dim);line-height:2.1;}
.curr-items li::before{content:'— ';color:var(--gold);}

/* TESTIMONIALS */
.testi-section{padding:100px 40px;}
.testi-grid{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-top:36px;}
.testi-card{border:1px solid rgba(201,169,110,0.18);padding:28px 26px;background:rgba(201,169,110,0.03);}
.testi-card.big{grid-column:1/-1;border-color:rgba(201,169,110,0.35);background:rgba(201,169,110,0.06);}
.testi-qmark{font-family:'Cormorant Garamond',serif;font-size:52px;color:rgba(201,169,110,0.2);line-height:0.5;margin-bottom:14px;}
.testi-text{font-size:14px;line-height:2;color:var(--text-primary);font-family:'Cormorant Garamond',serif;font-style:italic;margin-bottom:16px;}
.testi-hl{color:var(--gold);font-weight:700;font-style:normal;}
.testi-footer{display:flex;align-items:center;gap:12px;border-top:1px solid rgba(201,169,110,0.1);padding-top:12px;}
.testi-avatar{width:36px;height:36px;border-radius:50%;background:var(--purple-soft);border:1px solid rgba(201,169,110,0.3);display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:700;color:var(--gold);flex-shrink:0;}
.testi-name{font-size:12px;color:var(--gold);letter-spacing:1px;font-weight:700;}
.testi-role{font-size:11px;color:var(--text-dim);letter-spacing:1px;}

/* IG VIDEO */
.ig-section{padding:80px 40px;background:radial-gradient(ellipse at 50% 50%,rgba(45,13,92,0.4) 0%,transparent 60%);}
.ig-inner{max-width:560px;margin:0 auto;text-align:center;}
.ig-wrap{border:1px solid rgba(201,169,110,0.25);overflow:hidden;background:#000;margin-top:36px;}
.ig-wrap iframe{width:100%;min-height:600px;display:block;border:none;}

/* STATS */
.stats{padding:80px 40px;}
.stat-row{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:36px;}
.stat-box{text-align:center;padding:32px 16px;border:1px solid rgba(201,169,110,0.2);background:rgba(201,169,110,0.04);}
.stat-num{font-size:52px;font-weight:900;color:var(--gold);line-height:1;margin-bottom:8px;font-family:'Cormorant Garamond',serif;}
.stat-label{font-size:13px;color:var(--text-dim);line-height:1.7;}

/* PRICING */
.pricing{padding:100px 40px;text-align:center;}
.pricing-inner{max-width:640px;margin:0 auto;}
.price-box{border:1px solid rgba(201,169,110,0.5);padding:56px 44px;margin:36px 0;position:relative;background:radial-gradient(ellipse at 50% 0%,rgba(201,169,110,0.1) 0%,transparent 60%);}
.price-badge{position:absolute;top:-14px;left:50%;transform:translateX(-50%);background:#c0392b;color:#fff;font-size:12px;font-weight:700;letter-spacing:2px;padding:5px 24px;white-space:nowrap;}
.price-name{font-family:'Cormorant Garamond',serif;font-size:13px;letter-spacing:5px;color:var(--gold);margin-bottom:16px;}
.price-amount{font-size:72px;font-weight:900;color:var(--text-primary);line-height:1;margin-bottom:4px;}
.price-unit{font-size:14px;color:var(--text-dim);margin-bottom:6px;font-family:'Cormorant Garamond',serif;}
.price-per-day{font-size:13px;color:var(--gold);margin-bottom:28px;}
.price-urgency{background:rgba(139,26,26,0.2);border:1px solid rgba(255,80,80,0.3);padding:14px 20px;margin-bottom:24px;font-size:14px;color:#ff9999;display:flex;align-items:center;gap:10px;}
.price-highlight{background:rgba(201,169,110,0.1);border:1px solid rgba(201,169,110,0.3);padding:16px 20px;margin-bottom:28px;font-size:14px;color:var(--gold);line-height:2;text-align:left;}
.price-includes{text-align:left;margin-bottom:32px;}
.price-item{display:flex;align-items:flex-start;gap:12px;padding:10px 0;border-bottom:1px solid rgba(201,169,110,0.08);font-size:14px;color:var(--text-secondary);}
.price-item:last-child{border-bottom:none;}
.pi-check{color:var(--gold);flex-shrink:0;margin-top:2px;}
.price-btn{display:block;background:linear-gradient(135deg,var(--gold),#a07840);color:var(--purple-deep);font-size:16px;font-weight:700;padding:18px 48px;letter-spacing:2px;cursor:pointer;font-family:'Noto Serif TC',serif;text-decoration:none;transition:all 0.3s;text-align:center;margin-bottom:14px;border:none;width:100%;}
.price-btn:hover{transform:translateY(-2px);box-shadow:0 8px 30px rgba(201,169,110,0.4);}
.price-note{font-size:12px;color:var(--text-dim);}

/* FAQ */
.faq{padding:100px 40px;max-width:760px;margin:0 auto;}
.faq-item{border-bottom:1px solid rgba(201,169,110,0.15);padding:24px 0;cursor:pointer;}
.faq-q{display:flex;justify-content:space-between;align-items:center;font-size:15px;font-weight:600;color:var(--text-primary);gap:16px;}
.faq-icon{color:var(--gold);font-size:20px;flex-shrink:0;transition:transform 0.3s;}
.faq-a{font-size:14px;color:var(--text-dim);line-height:2;margin-top:12px;display:none;}
.faq-item.open .faq-a{display:block;}
.faq-item.open .faq-icon{transform:rotate(45deg);}

/* CTA FINAL */
.cta-final{padding:120px 40px;text-align:center;background:radial-gradient(ellipse at 50% 50%,rgba(45,13,92,0.7) 0%,transparent 70%);}
.cta-final-title{font-size:clamp(26px,4.5vw,50px);font-weight:900;line-height:1.4;margin-bottom:16px;}
.cta-final-title span{color:var(--gold);}
.cta-final-sub{font-size:16px;color:var(--text-dim);margin-bottom:14px;font-family:'Cormorant Garamond',serif;font-style:italic;}
.cta-final-urgency{font-size:14px;color:#ff9999;margin-bottom:36px;}
.cta-final-btn{display:block;background:linear-gradient(135deg,var(--gold),#a07840);color:var(--purple-deep);font-size:17px;font-weight:700;padding:20px 60px;letter-spacing:2px;cursor:pointer;font-family:'Noto Serif TC',serif;text-decoration:none;transition:all 0.3s;max-width:420px;margin:0 auto 16px;text-align:center;border:none;}
.cta-final-btn:hover{transform:translateY(-3px);box-shadow:0 12px 40px rgba(201,169,110,0.4);}
.cta-note{font-size:13px;color:var(--text-dim);}

footer{padding:36px;text-align:center;border-top:1px solid rgba(201,169,110,0.1);font-size:12px;color:var(--text-dim);letter-spacing:1px;}

@keyframes fadeUp{from{opacity:0;transform:translateY(28px);}to{opacity:1;transform:translateY(0);}}
@keyframes pulse{0%,100%{opacity:0.4;}50%{opacity:1;}}
@keyframes blink{0%,100%{opacity:0.5;}50%{opacity:1;}}

@media(max-width:680px){
  .urgent-banner{font-size:12px;padding:10px 14px;}
  nav{top:44px;padding:14px 18px;}
  .hero{padding:140px 20px 60px;}
  .pain-grid,.curr-grid,.testi-grid,.stat-row{grid-template-columns:1fr;}
  .testi-card.big{grid-column:auto;}
  .teacher-layout{grid-template-columns:1fr;gap:32px;}
  .teacher-photo-wrap{max-width:280px;margin:0 auto;}
  .diff-table{font-size:12px;}
  .diff-table th,.diff-table td{padding:10px 12px;}
  .price-box{padding:36px 20px;}
  .price-amount{font-size:56px;}
  section{padding-left:20px!important;padding-right:20px!important;}
}
</style>
</head>
<body>

<div class="urgent-banner">
  🔴 第四期 <span>7/4、7/5 即將開課</span> · 6人小班制 · 名額有限，報名從速
</div>

<nav>
  <div class="nav-brand">星盤識人學 · 珮慈老師</div>
  <a href="https://calendly.com/crystal-artian-academy/30min" class="nav-cta" target="_blank">預約免費諮詢</a>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-ring" style="width:580px;height:580px;"></div>
  <div class="hero-ring" style="width:400px;height:400px;"></div>
  <div class="hero-ring" style="width:220px;height:220px;"></div>
  <div class="hero-tag">⭐ 初階占星課程 · 第四期 · Crystal Artian Academy</div>
  <h1 class="hero-main">
    第一次看到自己的星盤<br>很多學生說的第一句話是
    <span class="hero-big-quote">「這是我嗎？」</span>
    不是猜測，是被<span style="color:var(--gold)">完整看見</span>的感覺
  </h1>
  <p class="hero-sub">珮慈老師帶你用自己的真實星盤<br>現場操作、現場讀懂——性格、事業、財運、感情一次全解</p>
  <div class="hero-urgency">
    <div class="urgency-dot"></div>
    7/4、7/5 開課 · 6人小班 · 剩餘名額有限
  </div>
  <a href="https://calendly.com/crystal-artian-academy/30min" class="hero-btn" target="_blank">立即預約免費諮詢</a>
  <p class="hero-note">預約諮詢完全免費 · 確認適合你再決定</p>
  <div class="hero-scroll">向下滾動 ↓</div>
</section>

<!-- STORY -->
<section class="story">
  <div class="inner reveal">
    <span class="section-label">為什麼學生會說「這是我嗎？」</span>
    <h2 class="section-title">因為星盤說出了<br>你自己都說不清楚的自己</h2>
    <div class="story-text">
      你可能看過很多星座文章，<strong>覺得描述跟自己完全對不上</strong>。<br><br>
      那是因為你只看了太陽星座——<br>
      而你的星盤裡，有 <strong>十顆行星、十二個宮位</strong>，每一個都在描述你人生的不同面向。<br><br>
      當學員第一次在課堂上，<strong>打開自己的真實星盤</strong>，<br>
      珮慈老師帶著一格一格讀，看到<span class="gw">「原來我在工作上總是這樣」</span>，<br>
      看到<span class="gw">「原來我在感情裡總是那樣」</span>，<br>
      看到<span class="gw">「原來我跟某些人合不來，星盤早就寫好了」</span>——<br><br>
      那個瞬間，很多人沉默，然後說：<strong>「哇，這就是我。」</strong>
    </div>
  </div>
</section>

<div class="gold-divider"></div>

<!-- PAIN -->
<section class="pain">
  <div class="inner reveal">
    <span class="section-label">你是否有這樣的困惑</span>
    <h2 class="section-title">看了很多星座文章<br>卻還是覺得「跟我不像」？</h2>
    <div class="pain-grid">
      <div class="pain-item">📍 只看太陽星座，覺得描述根本不像自己</div>
      <div class="pain-item">📍 想了解自己適合什麼工作，找不到方向</div>
      <div class="pain-item">📍 對占星很好奇，但越學越混亂，最後放棄</div>
      <div class="pain-item">📍 想看懂星盤，但那個圓圈對你來說像天書</div>
      <div class="pain-item">📍 跟某些人就是特別合不來，想知道為什麼</div>
      <div class="pain-item">📍 以前學過，背了一堆行星宮位，根本用不上</div>
    </div>
  </div>
</section>

<div class="gold-divider"></div>

<!-- DIFF -->
<section class="diff">
  <div class="inner reveal">
    <span class="section-label">這堂課跟市面上不一樣的地方</span>
    <h2 class="section-title">不是你聽我講<br>是我帶你當場操作</h2>
    <table class="diff-table">
      <tr>
        <th>一般占星課</th>
        <th>⭐ 星盤識人學</th>
      </tr>
      <tr>
        <td>老師講，你聽，回家自己摸索</td>
        <td><span class="diff-check">✦</span>現場打開你自己的星盤，帶你一格一格讀</td>
      </tr>
      <tr>
        <td>用範例星盤教學，跟你無關</td>
        <td><span class="diff-check">✦</span>用你的真實星盤，當場解讀你的人生</td>
      </tr>
      <tr>
        <td>幾十人大班，老師看不到你</td>
        <td><span class="diff-check">✦</span>6人小班 + 雙師資，每位學員都照顧得到</td>
      </tr>
      <tr>
        <td>背一堆行星宮位，不知道怎麼用</td>
        <td><span class="diff-check">✦</span>有邏輯的SOP，複雜星盤概念化繁為簡</td>
      </tr>
      <tr>
        <td>聽完不會，自己想辦法</td>
        <td><span class="diff-check">✦</span>不懂當場問，老師馬上解答，確保你真的會</td>
      </tr>
    </table>
  </div>
</section>

<div class="gold-divider"></div>

<!-- TEACHER -->
<section class="teacher">
  <div class="teacher-inner reveal">
    <span class="section-label">關於老師</span>
    <h2 class="section-title">為什麼是珮慈老師</h2>
    <div class="teacher-layout">
      <div class="teacher-photo-wrap">
        <!-- 
          ★ 換照片方式：
          把下面這行的 YOUR_PHOTO_URL 換成你照片的網址
          例如：https://crystalart.work/wp-content/uploads/你的照片.jpg
        -->
        <img
          src="https://i.ibb.co/G3WNhn8t/Gemini-Generated-Image-gvc20dgvc20dgvc2-1.png"
          alt="珮慈老師"
          class="teacher-photo"
          onerror="this.style.display='none';this.nextElementSibling.style.display='flex';"
        />
        <div class="teacher-photo-placeholder" style="display:none;">
          <span style="font-size:48px;">✦</span>
          <span>珮慈老師</span>
        </div>
        <div class="teacher-photo-frame"></div>
      </div>
      <div>
        <div class="teacher-name">珮慈老師</div>
        <div class="teacher-title">IARi 高階占星師 · Crystal Artian Academy 創辦人</div>
        <p class="teacher-bio">
          深耕身心靈領域四年，接觸無數客戶，最常被問的問題永遠離不開「感情、事業、人際」三大主題。<br><br>
          因此把星盤這套龐大複雜的命理系統，轉化成<strong style="color:var(--gold)">簡單、有邏輯、可以終身使用的判斷工具</strong>，讓每一個學員都能真正學會用、用得上。
        </p>
        <ul class="teacher-creds">
          <li class="teacher-cred"><span class="cred-dot">✦</span>IARi 認證高階占星師</li>
          <li class="teacher-cred"><span class="cred-dot">✦</span>初期創水晶品牌結合生命靈數，四月內創下10萬營收</li>
          <li class="teacher-cred"><span class="cred-dot">✦</span>用星盤篩選成員，助公司年營業額突破百萬</li>
          <li class="teacher-cred"><span class="cred-dot">✦</span>輔導客戶挑選合夥夥伴，避開上百萬合作地雷</li>
          <li class="teacher-cred"><span class="cred-dot">✦</span>協助 30+ 位客戶透過星盤諮詢找到適合轉職跑道</li>
          <li class="teacher-cred"><span class="cred-dot">✦</span>第一期學員100%升讀高階課程木曜星軌</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<div class="gold-divider"></div>

<!-- CURRICULUM -->
<section class="curriculum">
  <div class="inner reveal">
    <span class="section-label">課程內容</span>
    <h2 class="section-title">兩天，帶你從完全看不懂<br>到能解讀自己的整張星盤</h2>
    <div class="curr-grid">
      <div class="curr-card">
        <div class="curr-day">DAY 1 · 7/4</div>
        <div class="curr-title">個人性格篇</div>
        <div class="curr-sub">讀懂「你是誰」</div>
        <ul class="curr-items">
          <li>五大內行星落星座完整解讀</li>
          <li>太陽（自我）、月亮（內心需求）</li>
          <li>水星（思考溝通）、金星（愛情金錢）</li>
          <li>火星（行動力與雷點）</li>
          <li>群星格局：你此生的人生主線</li>
          <li>十大行星落十二宮位逐一解析</li>
        </ul>
      </div>
      <div class="curr-card">
        <div class="curr-day">DAY 2 · 7/5</div>
        <div class="curr-title">事業財運篇</div>
        <div class="curr-sub">讀懂「你的錢在哪裡」</div>
        <ul class="curr-items">
          <li>6宮職場宮：你適合的工作狀態</li>
          <li>10宮事業宮：你能走的長期方向</li>
          <li>2宮財帛宮：你的正財體質</li>
          <li>8宮：偏財與副業潛力</li>
          <li>飛宮技法：讓解讀更立體深入</li>
          <li>2、6、10宮綜合事業整合判讀</li>
        </ul>
      </div>
      <div class="curr-card">
        <div class="curr-day">加碼</div>
        <div class="curr-title">感情解讀篇</div>
        <div class="curr-sub">讀懂「你的感情模式」</div>
        <ul class="curr-items">
          <li>5宮：戀愛風格與吸引力</li>
          <li>7宮：婚姻伴侶特質</li>
          <li>月亮金星：內心真實的愛情需求</li>
          <li>戀愛機會從哪裡來</li>
        </ul>
      </div>
      <div class="curr-card">
        <div class="curr-day">加碼</div>
        <div class="curr-title">合盤比較盤</div>
        <div class="curr-sub">讀懂「你們為什麼這樣」</div>
        <ul class="curr-items">
          <li>他對你的影響是什麼</li>
          <li>吉星金木落宮：他為你帶來的好</li>
          <li>災星土冥落宮：為什麼你們老摩擦</li>
          <li>事業合盤 + 感情合盤解讀</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<div class="gold-divider"></div>

<!-- TESTIMONIALS -->
<section class="testi-section">
  <div class="inner reveal">
    <span class="section-label">學員真實見證</span>
    <h2 class="section-title">不是我說好<br>是她們說的</h2>
    <div class="testi-grid">

      <div class="testi-card big">
        <div class="testi-qmark">"</div>
        <p class="testi-text">後悔為什麼不是一開始就上了珮慈老師的課呢？！她真的把星盤的複雜變成極簡，利用她自己的邏輯思維去建構課程。我之前背得要死的什麼行星宮位，<span class="testi-hl">原來可以用對照的方式連貫，再套入自己的命盤運用，瞬間變得超級簡單。</span>順手要一個朋友的星盤來看，真的會覺得簡單到嚇爛欸，到底當初為甚走彎路呢？！</p>
        <div class="testi-footer">
          <div class="testi-avatar">J</div>
          <div><div class="testi-name">Jessie</div><div class="testi-role">汽廠老闆娘</div></div>
        </div>
      </div>

      <div class="testi-card">
        <div class="testi-qmark">"</div>
        <p class="testi-text">感謝老師的精闢解析！讓我看懂自己「整合資源」的天賦！<span class="testi-hl">星盤解析讓我確立了專業方向，更驚喜發現夥伴是自帶金庫的貴人！她的金星木星精準落入我的偏財宮，象徵帶來龐大資源與業績。</span></p>
        <div class="testi-footer">
          <div class="testi-avatar">怡</div>
          <div><div class="testi-name">怡瑄</div><div class="testi-role">金融業務總監</div></div>
        </div>
      </div>

      <div class="testi-card">
        <div class="testi-qmark">"</div>
        <p class="testi-text">老師的課真的很淺顯易懂，如果有學員不懂都可以提出來馬上解答。<span class="testi-hl">而且上課老師都會跟大家互動，藉此了解大家是不是真的吸收了，不會只顧著講課件。這堂課真的無敵超值！！！</span></p>
        <div class="testi-footer">
          <div class="testi-avatar">M</div>
          <div><div class="testi-name">Mia</div><div class="testi-role">金融業主管</div></div>
        </div>
      </div>

      <div class="testi-card">
        <div class="testi-qmark">"</div>
        <p class="testi-text">感受到珮慈老師真的超級用心在準備教學及講義，每一個環節也都很有耐心的講解，確保我們都有學會並理解。<span class="testi-hl">問答搶分很有趣，讓大家都更積極了，小班制也超棒超喜歡，每個同學都有照顧到。</span></p>
        <div class="testi-footer">
          <div class="testi-avatar">P</div>
          <div><div class="testi-name">PhiL</div><div class="testi-role">傳產製造業務</div></div>
        </div>
      </div>

      <div class="testi-card">
        <div class="testi-qmark">"</div>
        <p class="testi-text">把深奧的占星邏輯講得非常有條理且落地，<span class="testi-hl">實作練習時非常有耐心的開小視窗解盤，真的讓我大開眼界！</span>占星的世界！</p>
        <div class="testi-footer">
          <div class="testi-avatar">R</div>
          <div><div class="testi-name">Remi</div><div class="testi-role">行政專員</div></div>
        </div>
      </div>

      <div class="testi-card">
        <div class="testi-qmark">"</div>
        <p class="testi-text">上課過程中有更了解自己組成，<span class="testi-hl">會有「對欸、沒錯、原來是這樣」的感覺，好險當初有報到課程～</span>以前都是片段的聽網路上的解說，現在才真正懂了。</p>
        <div class="testi-footer">
          <div class="testi-avatar">E</div>
          <div><div class="testi-name">E</div><div class="testi-role">行政專員</div></div>
        </div>
      </div>

      <div class="testi-card">
        <div class="testi-qmark">"</div>
        <p class="testi-text">短短兩天，就能開始理解自己的盤，甚至慢慢說出方向與脈絡。<span class="testi-hl">在事業上雛型上也得到了明確的方向。</span></p>
        <div class="testi-footer">
          <div class="testi-avatar">俐</div>
          <div><div class="testi-name">俐雯</div><div class="testi-role">房產平面設計師</div></div>
        </div>
      </div>

      <div class="testi-card">
        <div class="testi-qmark">"</div>
        <p class="testi-text">手把手帶著的實戰練習，很建議一定要參與直播課，不用害怕講錯，<span class="testi-hl">老師會根據你的回應點出盲點並補充關鍵資訊，只要願意提出問題，都能被很好的解答。</span></p>
        <div class="testi-footer">
          <div class="testi-avatar">★</div>
          <div><div class="testi-name">學員回饋</div><div class="testi-role">第三期</div></div>
        </div>
      </div>

    </div>
  </div>
</section>

<div class="gold-divider"></div>

<!-- IG VIDEO -->
<section class="ig-section">
  <div class="ig-inner reveal">
    <span class="section-label">學員影片見證</span>
    <h2 class="section-title">聽聽她們親口說</h2>
    <div class="ig-wrap">
      <iframe src="https://www.instagram.com/p/DXAGlWaAtM9/embed/" allowfullscreen loading="lazy"></iframe>
    </div>
  </div>
</section>

<div class="gold-divider"></div>

<!-- STATS -->
<section class="stats">
  <div class="inner reveal">
    <span class="section-label">數字說話</span>
    <div class="stat-row">
      <div class="stat-box">
        <div class="stat-num">100%</div>
        <div class="stat-label">第一期學員<br>上完後全部升高階課</div>
      </div>
      <div class="stat-box">
        <div class="stat-num">6人</div>
        <div class="stat-label">小班制<br>雙師資照顧每位學員</div>
      </div>
      <div class="stat-box">
        <div class="stat-num">2天</div>
        <div class="stat-label">從零基礎<br>到能解讀自己的星盤</div>
      </div>
    </div>
  </div>
</section>

<div class="gold-divider"></div>

<!-- WHAT YOU GET -->
<section class="pricing">
  <div class="pricing-inner reveal">
    <span class="section-label">課程包含</span>
    <h2 class="section-title">報名後你會得到什麼</h2>
    <div class="price-box">
      <div class="price-badge">🔴 第四期 7/4、7/5 · 6人小班 · 名額有限</div>
      <div class="price-name">星盤識人學 · 一年會籍</div>

      <div class="price-highlight">
        ✦ 一年內所有初階開課場次，你都可以參加<br>
        ✦ 第一次沒聽懂？下一期繼續來，直到真的會為止<br>
        ✦ 時間不對？等下一次開課，名額永遠保留給你
      </div>

      <div class="price-includes">
        <div class="price-item"><span class="pi-check">✦</span>6人小班 · 現場帶你打開自己的真實星盤操作</div>
        <div class="price-item"><span class="pi-check">✦</span>雙師資陪伴 · 珮慈老師 + 珮如老師共同輔導</div>
        <div class="price-item"><span class="pi-check">✦</span>個人性格篇 + 事業財運篇完整教學</div>
        <div class="price-item"><span class="pi-check">✦</span>感情解讀 + 合盤比較盤加碼內容</div>
        <div class="price-item"><span class="pi-check">✦</span>一年內無限次複訓資格</div>
        <div class="price-item"><span class="pi-check">✦</span>完整實戰講義（飛宮解析 + 行星落宮速查表）</div>
        <div class="price-item"><span class="pi-check">✦</span>Skool 專屬學員社群</div>
      </div>

      <a href="https://calendly.com/crystal-artian-academy/30min" class="price-btn" target="_blank">📅 立即預約免費諮詢</a>
      <div class="price-note">預約完全免費 · 老師為你說明詳細方案 · 確認適合再決定</div>
    </div>
  </div>
</section>

<div class="gold-divider"></div>

<!-- FAQ -->
<section class="faq reveal">
  <span class="section-label">常見問題</span>
  <h2 class="section-title" style="margin-bottom:36px;">你可能想問的事</h2>
  <div class="faq-item" onclick="this.classList.toggle('open')">
    <div class="faq-q">完全沒有基礎，真的可以嗎？<span class="faq-icon">+</span></div>
    <div class="faq-a">完全可以。這門課就是為零基礎設計的，從最基本的概念開始，用有邏輯的SOP帶你一步步建立。很多學員是帶著「星座是什麼」這個問題進來的，一樣學得很好。</div>
  </div>
  <div class="faq-item" onclick="this.classList.toggle('open')">
    <div class="faq-q">是用我自己的星盤上課嗎？<span class="faq-icon">+</span></div>
    <div class="faq-a">是的。課堂上你會打開自己的真實星盤，珮慈老師帶著你一格一格讀，解讀的就是你自己的人生——不是範例，不是別人的盤，是你的。</div>
  </div>
  <div class="faq-item" onclick="this.classList.toggle('open')">
    <div class="faq-q">一年內可以複訓幾次？<span class="faq-icon">+</span></div>
    <div class="faq-a">沒有次數限制。一年會籍期間，只要有開初階課，你都可以來參加。第一次沒聽懂沒關係，下次再來，直到你真的會為止。</div>
  </div>
  <div class="faq-item" onclick="this.classList.toggle('open')">
    <div class="faq-q">7/4、7/5 我有事來不了怎麼辦？<span class="faq-icon">+</span></div>
    <div class="faq-a">沒關係，你可以等下一期開課再來。一年會籍從報名起算，名額永遠保留給你，等你準備好再來就好。</div>
  </div>
  <div class="faq-item" onclick="this.classList.toggle('open')">
    <div class="faq-q">上完初階之後可以做什麼？<span class="faq-icon">+</span></div>
    <div class="faq-a">上完初階，你能獨立解讀自己的本命盤，了解性格全貌、事業方向、財運體質和感情模式，也能做基本的合盤分析。如果想進一步學推運、流年預測、深度合盤，可以升級高階課程木曜星軌。</div>
  </div>
  <div class="faq-item" onclick="this.classList.toggle('open')">
    <div class="faq-q">不確定適不適合，可以先諮詢嗎？<span class="faq-icon">+</span></div>
    <div class="faq-a">完全可以，而且強烈建議！預約諮詢完全免費，我希望每個學員都是確認適合自己之後再報名。點上方按鈕預約，我們聊聊再決定。</div>
  </div>
</section>

<!-- CTA FINAL -->
<section class="cta-final" id="cta">
  <div class="reveal">
    <span class="section-label" style="display:block;margin-bottom:18px;">現在就開始</span>
    <h2 class="cta-final-title">你的星盤裡<br><span>藏著你還不知道的自己</span></h2>
    <p class="cta-final-sub">先預約免費諮詢，確認適合你，再決定要不要報名</p>
    <p class="cta-final-urgency">🔴 7/4、7/5 即將開課 · 6人小班 · 名額有限</p>
    <a href="https://calendly.com/crystal-artian-academy/30min" class="cta-final-btn" target="_blank">📅 立即預約免費諮詢</a>
    <p class="cta-note">✦ 預約完全免費 · 確認適合你再決定 ✦</p>
  </div>
</section>

<footer>
  <p>星盤識人學 · 珮慈老師 · Crystal Artian Academy · 所有課程內容僅供付費學員使用</p>
</footer>

<script>
const observer = new IntersectionObserver((entries)=>{
  entries.forEach(e=>{if(e.isIntersecting)e.target.classList.add('visible');});
},{threshold:0.08});
document.querySelectorAll('.reveal').forEach(el=>observer.observe(el));
</script>
</body>
</html>
