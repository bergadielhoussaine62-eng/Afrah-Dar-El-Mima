[afrah-dar-el-mima.html](https://github.com/user-attachments/files/29778007/afrah-dar-el-mima.html)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>أفراح دار الميمة | Afrah Dar El Mima — تنظيم الأفراح والمناسبات</title>
<meta name="description" content="أفراح دار الميمة — تنظيم حفلات الأعراس والمناسبات بسلا والرباط. تصوير، ديكور، DJ، طبخ تقليدي، بيفي، وأكثر.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Aref+Ruqaa:wght@400;700&family=Tajawal:wght@300;400;500;700;900&family=Cormorant+Garamond:ital,wght@0,400;0,500;1,400&display=swap" rel="stylesheet">
<style>
  :root{
    --maroon-deep:#3B0F1C;
    --maroon:#5C1526;
    --maroon-light:#7A2338;
    --gold:#C9A24B;
    --gold-light:#E8D49A;
    --gold-soft:#F1E2B8;
    --ivory:#FBF4E7;
    --ivory-dim:#F1E6D2;
    --charcoal:#1B120F;
    --rose:#B0687A;
    --shadow:0 20px 50px rgba(27,10,15,0.35);
  }

  *{margin:0;padding:0;box-sizing:border-box;}

  html{scroll-behavior:smooth;}

  body{
    background:var(--ivory);
    color:var(--charcoal);
    font-family:'Tajawal',sans-serif;
    overflow-x:hidden;
  }

  h1,h2,h3,.adm-display{
    font-family:'Aref Ruqaa',serif;
    font-weight:700;
  }

  .adm-eyebrow{
    font-family:'Cormorant Garamond',serif;
    font-style:italic;
    letter-spacing:0.12em;
    font-size:0.95rem;
    color:var(--gold);
    text-transform:uppercase;
  }

  a{color:inherit;text-decoration:none;}
  ul{list-style:none;}
  img{max-width:100%;display:block;}

  /* ============ ARCH SHAPE UTILITY ============ */
  .adm-arch{
    border-radius:50% 50% 0 0 / 60% 60% 0 0;
  }

  /* ============ ZELLIGE PATTERN BG ============ */
  .adm-zellige{
    background-image:
      radial-gradient(circle at 50% 50%, transparent 55%, rgba(201,162,75,0.10) 56%, rgba(201,162,75,0.10) 60%, transparent 61%);
    background-size:46px 46px;
  }

  /* ============ NAV ============ */
  .adm-nav{
    position:fixed;
    top:0;left:0;right:0;
    z-index:100;
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:16px 6vw;
    background:rgba(59,15,28,0.92);
    backdrop-filter:blur(8px);
    border-bottom:1px solid rgba(201,162,75,0.25);
    transition:padding 0.3s ease;
  }
  .adm-nav-brand{
    display:flex;
    align-items:center;
    gap:10px;
  }
  .adm-nav-emblem{
    width:38px;height:38px;
    border-radius:50%;
    border:1.5px solid var(--gold);
    display:flex;align-items:center;justify-content:center;
  }
  .adm-nav-emblem svg{width:20px;height:20px;}
  .adm-nav-name{
    color:var(--gold-soft);
    font-family:'Aref Ruqaa',serif;
    font-size:1.25rem;
  }
  .adm-nav-links{
    display:flex;
    gap:32px;
    align-items:center;
  }
  .adm-nav-links a{
    color:var(--ivory-dim);
    font-size:0.92rem;
    position:relative;
    padding-bottom:4px;
  }
  .adm-nav-links a::after{
    content:'';
    position:absolute;
    bottom:0;right:0;left:0;
    height:1px;
    background:var(--gold);
    transform:scaleX(0);
    transition:transform 0.3s ease;
  }
  .adm-nav-links a:hover::after{transform:scaleX(1);}
  .adm-nav-cta{
    background:var(--gold);
    color:var(--maroon-deep)!important;
    padding:9px 20px;
    border-radius:30px;
    font-weight:700;
    font-size:0.88rem;
    display:flex;
    align-items:center;
    gap:6px;
  }
  .adm-nav-cta svg{width:16px;height:16px;}
  .adm-nav-toggle{display:none;background:none;border:none;color:var(--gold);font-size:1.6rem;}

  /* ============ HERO ============ */
  .adm-hero{
    position:relative;
    min-height:100vh;
    background:
      radial-gradient(ellipse at 50% -10%, var(--maroon-light) 0%, var(--maroon) 45%, var(--maroon-deep) 100%);
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:140px 6vw 80px;
    overflow:hidden;
  }
  .adm-hero::before{
    content:'';
    position:absolute;
    inset:0;
    background-image:
      radial-gradient(circle at 50% 50%, transparent 58%, rgba(201,162,75,0.07) 59%, rgba(201,162,75,0.07) 62%, transparent 63%);
    background-size:70px 70px;
    opacity:0.5;
  }
  .adm-hero-frame{
    position:relative;
    z-index:2;
    width:180px;height:220px;
    background:linear-gradient(160deg, var(--maroon-light), var(--maroon-deep));
    border:2px solid var(--gold);
    border-radius:50% 50% 0 0 / 70% 70% 0 0;
    display:flex;
    align-items:flex-end;
    justify-content:center;
    padding-bottom:26px;
    margin-bottom:36px;
    box-shadow:0 0 0 6px rgba(201,162,75,0.12), var(--shadow);
    animation:admGlow 4s ease-in-out infinite;
  }
  @keyframes admGlow{
    0%,100%{box-shadow:0 0 0 6px rgba(201,162,75,0.12), var(--shadow);}
    50%{box-shadow:0 0 0 10px rgba(201,162,75,0.22), var(--shadow);}
  }
  .adm-hero-frame svg{width:78px;height:78px;}

  .adm-hero-eyebrow{
    position:relative;z-index:2;
    margin-bottom:18px;
  }
  .adm-hero h1{
    position:relative;z-index:2;
    color:var(--gold-soft);
    font-size:clamp(2.6rem, 7vw, 4.6rem);
    line-height:1.15;
    margin-bottom:20px;
    text-shadow:0 4px 24px rgba(0,0,0,0.3);
  }
  .adm-hero p{
    position:relative;z-index:2;
    color:var(--ivory-dim);
    font-size:clamp(1rem, 2vw, 1.25rem);
    max-width:620px;
    line-height:1.9;
    margin-bottom:40px;
    font-weight:300;
  }
  .adm-hero-ctas{
    position:relative;z-index:2;
    display:flex;
    gap:18px;
    flex-wrap:wrap;
    justify-content:center;
  }
  .adm-btn{
    display:inline-flex;
    align-items:center;
    gap:10px;
    padding:15px 32px;
    border-radius:34px;
    font-weight:700;
    font-size:0.98rem;
    transition:transform 0.25s ease, box-shadow 0.25s ease;
  }
  .adm-btn svg{width:18px;height:18px;}
  .adm-btn-solid{
    background:linear-gradient(135deg, var(--gold-light), var(--gold));
    color:var(--maroon-deep);
    box-shadow:0 10px 30px rgba(201,162,75,0.35);
  }
  .adm-btn-solid:hover{transform:translateY(-3px);box-shadow:0 14px 34px rgba(201,162,75,0.5);}
  .adm-btn-outline{
    border:1.5px solid var(--gold);
    color:var(--gold-soft);
  }
  .adm-btn-outline:hover{background:rgba(201,162,75,0.12);transform:translateY(-3px);}

  .adm-scroll-cue{
    position:absolute;
    bottom:30px;left:50%;
    transform:translateX(-50%);
    z-index:2;
    width:22px;height:34px;
    border:1.5px solid var(--gold);
    border-radius:12px;
    display:flex;
    justify-content:center;
    padding-top:6px;
  }
  .adm-scroll-cue::after{
    content:'';
    width:3px;height:8px;
    background:var(--gold);
    border-radius:2px;
    animation:admScroll 1.8s ease-in-out infinite;
  }
  @keyframes admScroll{
    0%{opacity:1;transform:translateY(0);}
    70%{opacity:0;transform:translateY(10px);}
    100%{opacity:0;}
  }

  /* ============ SECTION DIVIDER (arch keystone) ============ */
  .adm-divider{
    display:flex;
    align-items:center;
    justify-content:center;
    gap:14px;
    padding:0 0 10px;
  }
  .adm-divider::before,.adm-divider::after{
    content:'';
    height:1px;
    width:60px;
    background:linear-gradient(90deg, transparent, var(--gold), transparent);
  }
  .adm-divider svg{width:22px;height:22px;color:var(--gold);}

  /* ============ ABOUT ============ */
  .adm-about{
    padding:110px 6vw;
    text-align:center;
    max-width:840px;
    margin:0 auto;
  }
  .adm-about h2{
    font-size:clamp(1.9rem,4vw,2.6rem);
    color:var(--maroon);
    margin:18px 0 26px;
  }
  .adm-about p{
    font-size:1.1rem;
    line-height:2.1;
    color:#4a2f36;
    font-weight:400;
  }

  /* ============ SERVICES ============ */
  .adm-services{
    background:var(--maroon-deep);
    padding:100px 6vw 120px;
    position:relative;
  }
  .adm-services-head{text-align:center;margin-bottom:64px;}
  .adm-services-head h2{
    color:var(--gold-soft);
    font-size:clamp(2rem,4.5vw,2.8rem);
    margin-top:14px;
  }
  .adm-services-head .adm-divider::before,
  .adm-services-head .adm-divider::after{background:linear-gradient(90deg, transparent, var(--gold), transparent);}

  .adm-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(220px, 1fr));
    gap:28px;
    max-width:1200px;
    margin:0 auto;
  }
  .adm-card{
    background:linear-gradient(160deg, rgba(232,212,154,0.06), rgba(232,212,154,0.02));
    border:1px solid rgba(201,162,75,0.25);
    border-radius:6px 6px 90px 90px / 6px 6px 40px 40px;
    padding:38px 22px 32px;
    text-align:center;
    transition:transform 0.35s ease, border-color 0.35s ease, background 0.35s ease;
    opacity:0;
    transform:translateY(24px);
  }
  .adm-card.adm-visible{
    opacity:1;
    transform:translateY(0);
  }
  .adm-card:hover{
    transform:translateY(-8px);
    border-color:var(--gold);
    background:linear-gradient(160deg, rgba(232,212,154,0.13), rgba(232,212,154,0.03));
  }
  .adm-card-icon{
    width:56px;height:56px;
    margin:0 auto 20px;
    border:1px solid var(--gold);
    border-radius:50%;
    display:flex;
    align-items:center;
    justify-content:center;
    color:var(--gold);
  }
  .adm-card-icon svg{width:26px;height:26px;}
  .adm-card h3{
    color:var(--gold-soft);
    font-size:1.3rem;
    margin-bottom:8px;
  }
  .adm-card span{
    display:block;
    color:rgba(251,244,231,0.55);
    font-family:'Cormorant Garamond',serif;
    font-style:italic;
    font-size:0.95rem;
  }

  /* ============ ZONES ============ */
  .adm-zones{
    padding:100px 6vw;
    text-align:center;
  }
  .adm-zones h2{
    color:var(--maroon);
    font-size:clamp(1.9rem,4vw,2.6rem);
    margin:14px 0 40px;
  }
  .adm-zone-chips{
    display:flex;
    gap:20px;
    justify-content:center;
    flex-wrap:wrap;
  }
  .adm-chip{
    display:flex;
    align-items:center;
    gap:10px;
    padding:16px 34px;
    border:1.5px solid var(--maroon);
    border-radius:40px;
    color:var(--maroon);
    font-weight:700;
    font-size:1.15rem;
  }
  .adm-chip svg{width:18px;height:18px;}

  /* ============ CTA ============ */
  .adm-cta{
    position:relative;
    background:linear-gradient(160deg, var(--maroon), var(--maroon-deep));
    padding:110px 6vw;
    text-align:center;
    overflow:hidden;
  }
  .adm-cta::before{
    content:'';
    position:absolute;inset:0;
    background-image:radial-gradient(circle at 50% 50%, transparent 58%, rgba(201,162,75,0.06) 59%, rgba(201,162,75,0.06) 62%, transparent 63%);
    background-size:60px 60px;
  }
  .adm-cta-inner{position:relative;z-index:2;}
  .adm-cta h2{
    color:var(--gold-soft);
    font-size:clamp(2rem,5vw,3rem);
    margin-bottom:18px;
  }
  .adm-cta p{
    color:var(--ivory-dim);
    font-size:1.1rem;
    max-width:520px;
    margin:0 auto 40px;
    line-height:1.9;
    font-weight:300;
  }
  .adm-cta .adm-hero-ctas{margin-bottom:0;}

  /* ============ FOOTER ============ */
  footer{
    background:var(--charcoal);
    color:var(--ivory-dim);
    padding:60px 6vw 30px;
  }
  .adm-footer-grid{
    display:flex;
    flex-wrap:wrap;
    gap:40px;
    justify-content:space-between;
    max-width:1200px;
    margin:0 auto 40px;
  }
  .adm-footer-brand{display:flex;align-items:center;gap:12px;}
  .adm-footer-brand .adm-nav-emblem{border-color:var(--gold);}
  .adm-footer-brand-name{font-family:'Aref Ruqaa',serif;font-size:1.4rem;color:var(--gold-soft);}
  .adm-footer-col h4{
    color:var(--gold);
    font-family:'Tajawal',sans-serif;
    font-weight:700;
    margin-bottom:16px;
    font-size:1rem;
  }
  .adm-footer-col ul li{margin-bottom:10px;font-size:0.92rem;color:rgba(251,244,231,0.65);}
  .adm-footer-col ul li a:hover{color:var(--gold-soft);}
  .adm-footer-social{display:flex;gap:14px;margin-top:6px;}
  .adm-footer-social a{
    width:38px;height:38px;
    border:1px solid rgba(201,162,75,0.4);
    border-radius:50%;
    display:flex;align-items:center;justify-content:center;
    color:var(--gold);
  }
  .adm-footer-social a:hover{background:rgba(201,162,75,0.15);}
  .adm-footer-social svg{width:17px;height:17px;}
  .adm-footer-bottom{
    text-align:center;
    padding-top:26px;
    border-top:1px solid rgba(201,162,75,0.15);
    font-size:0.82rem;
    color:rgba(251,244,231,0.4);
  }

  /* ============ WHATSAPP FLOAT ============ */
  .adm-float-wa{
    position:fixed;
    bottom:24px;left:24px;
    z-index:99;
    width:58px;height:58px;
    border-radius:50%;
    background:linear-gradient(135deg, var(--gold-light), var(--gold));
    display:flex;align-items:center;justify-content:center;
    box-shadow:0 10px 30px rgba(201,162,75,0.45);
    animation:admFloat 3s ease-in-out infinite;
  }
  .adm-float-wa svg{width:28px;height:28px;color:var(--maroon-deep);}
  @keyframes admFloat{
    0%,100%{transform:translateY(0);}
    50%{transform:translateY(-8px);}
  }

  /* ============ REVEAL ANIM ============ */
  .adm-reveal{
    opacity:0;
    transform:translateY(24px);
    transition:opacity 0.8s ease, transform 0.8s ease;
  }
  .adm-reveal.adm-visible{opacity:1;transform:translateY(0);}

  /* ============ RESPONSIVE ============ */
  @media (max-width:820px){
    .adm-nav-links{
      position:fixed;
      top:70px;left:0;right:0;
      background:var(--maroon-deep);
      flex-direction:column;
      padding:20px 0;
      gap:20px;
      transform:translateY(-150%);
      transition:transform 0.35s ease;
      border-bottom:1px solid rgba(201,162,75,0.25);
    }
    .adm-nav-links.adm-open{transform:translateY(0);}
    .adm-nav-toggle{display:block;}
  }
  @media (prefers-reduced-motion: reduce){
    *{animation:none!important;transition:none!important;}
  }
</style>
</head>
<body>

<!-- NAV -->
<nav class="adm-nav">
  <div class="adm-nav-brand">
    <div class="adm-nav-emblem">
      <svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="2" style="color:var(--gold)">
        <path d="M8 24 L24 10 L40 24" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M12 22 V38 H36 V22" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M20 38 V28 H28 V38" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
    </div>
    <span class="adm-nav-name">أفراح دار الميمة</span>
  </div>
  <button class="adm-nav-toggle" id="admToggle" aria-label="القائمة">☰</button>
  <ul class="adm-nav-links" id="admLinks">
    <li><a href="#home">الرئيسية</a></li>
    <li><a href="#about">من نحنا</a></li>
    <li><a href="#services">خدماتنا</a></li>
    <li><a href="#contact">تواصل معانا</a></li>
    <li><a class="adm-nav-cta" href="https://wa.me/212661655667?text=سلام،%20بغيت%20نتواصل%20معاكم%20بخصوص%20تنظيم%20حفلة" target="_blank" rel="noopener">
      <svg viewBox="0 0 24 24" fill="currentColor"><path d="M12.04 2C6.58 2 2.13 6.45 2.13 11.91c0 1.75.46 3.45 1.32 4.95L2 22l5.29-1.39a9.9 9.9 0 0 0 4.75 1.21h.01c5.46 0 9.9-4.45 9.9-9.91C21.96 6.45 17.5 2 12.04 2zm0 18.06h-.01a8.2 8.2 0 0 1-4.19-1.15l-.3-.18-3.14.82.84-3.06-.2-.31a8.16 8.16 0 0 1-1.27-4.36c0-4.53 3.7-8.22 8.24-8.22 2.2 0 4.27.86 5.82 2.42a8.14 8.14 0 0 1 2.41 5.81c0 4.54-3.7 8.23-8.2 8.23zm4.5-6.16c-.25-.12-1.46-.72-1.68-.8-.23-.08-.39-.12-.56.12-.16.25-.64.8-.78.96-.15.17-.29.19-.53.06-.25-.12-1.04-.38-1.98-1.22-.73-.65-1.23-1.46-1.37-1.7-.15-.25-.02-.38.11-.5.11-.11.25-.29.37-.43.12-.15.16-.25.24-.41.08-.17.04-.31-.02-.43-.06-.12-.56-1.35-.77-1.85-.2-.48-.41-.42-.56-.43-.14-.01-.31-.01-.47-.01-.17 0-.43.06-.66.31-.23.25-.86.85-.86 2.06 0 1.22.89 2.4 1.01 2.56.12.17 1.75 2.67 4.24 3.74.59.26 1.06.41 1.42.53.6.19 1.14.16 1.57.1.48-.07 1.46-.6 1.67-1.18.2-.58.2-1.07.14-1.18-.06-.1-.22-.16-.47-.28z"/></svg>
      واتساب
    </a></li>
  </ul>
</nav>

<!-- HERO -->
<section class="adm-hero" id="home">
  <div class="adm-hero-frame">
    <svg viewBox="0 0 48 48" fill="none" stroke="var(--gold)" stroke-width="1.8">
      <path d="M8 24 L24 9 L40 24" stroke-linecap="round" stroke-linejoin="round"/>
      <path d="M11 22 V40 H37 V22" stroke-linecap="round" stroke-linejoin="round"/>
      <path d="M19 40 V27 H29 V40" stroke-linecap="round" stroke-linejoin="round"/>
      <circle cx="24" cy="18" r="1.6" fill="var(--gold)" stroke="none"/>
    </svg>
  </div>
  <p class="adm-eyebrow adm-hero-eyebrow">Wedding &amp; Events Planning — سلا · الرباط</p>
  <h1>أفراح دار الميمة</h1>
  <p>اللمسة لي كتجمع الدفء والأناقة فتنظيم حفلاتكم… من أول فكرة حتى آخر رقصة، كنعتناو بكل تفصيل باش يكون العرس ديالكم حكاية كتتحكى.</p>
  <div class="adm-hero-ctas">
    <a class="adm-btn adm-btn-solid" href="https://wa.me/212661655667?text=سلام،%20بغيت%20نتواصل%20معاكم%20بخصوص%20تنظيم%20حفلة" target="_blank" rel="noopener">
      <svg viewBox="0 0 24 24" fill="currentColor"><path d="M12.04 2C6.58 2 2.13 6.45 2.13 11.91c0 1.75.46 3.45 1.32 4.95L2 22l5.29-1.39a9.9 9.9 0 0 0 4.75 1.21h.01c5.46 0 9.9-4.45 9.9-9.91C21.96 6.45 17.5 2 12.04 2zm0 18.06h-.01a8.2 8.2 0 0 1-4.19-1.15l-.3-.18-3.14.82.84-3.06-.2-.31a8.16 8.16 0 0 1-1.27-4.36c0-4.53 3.7-8.22 8.24-8.22 2.2 0 4.27.86 5.82 2.42a8.14 8.14 0 0 1 2.41 5.81c0 4.54-3.7 8.23-8.2 8.23zm4.5-6.16c-.25-.12-1.46-.72-1.68-.8-.23-.08-.39-.12-.56.12-.16.25-.64.8-.78.96-.15.17-.29.19-.53.06-.25-.12-1.04-.38-1.98-1.22-.73-.65-1.23-1.46-1.37-1.7-.15-.25-.02-.38.11-.5.11-.11.25-.29.37-.43.12-.15.16-.25.24-.41.08-.17.04-.31-.02-.43-.06-.12-.56-1.35-.77-1.85-.2-.48-.41-.42-.56-.43-.14-.01-.31-.01-.47-.01-.17 0-.43.06-.66.31-.23.25-.86.85-.86 2.06 0 1.22.89 2.4 1.01 2.56.12.17 1.75 2.67 4.24 3.74.59.26 1.06.41 1.42.53.6.19 1.14.16 1.57.1.48-.07 1.46-.6 1.67-1.18.2-.58.2-1.07.14-1.18-.06-.1-.22-.16-.47-.28z"/></svg>
      احجزو حفلتكم
    </a>
    <a class="adm-btn adm-btn-outline" href="https://www.instagram.com/afrah_dar_el_mima" target="_blank" rel="noopener">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r="1"/></svg>
      شوفو الأعمال ديالنا
    </a>
  </div>
  <div class="adm-scroll-cue"></div>
</section>

<!-- ABOUT -->
<section class="adm-about adm-reveal" id="about">
  <p class="adm-eyebrow">من نحنا</p>
  <h2>الدفء ديال الدار… فخدمة فراحكم</h2>
  <p>أفراح دار الميمة هي فريق مغربي متخصص فتنظيم الأعراس والمناسبات بسلا والرباط. كنجمعو بين الأصالة المغربية والأناقة العصرية، ونتكلفو بكل شي: من الديكور والتصوير، للطبخ التقليدي والموسيقى، حتى الدبيحة المخزانية والتنكافت. الهدف ديالنا بسيط: تعيشو اللحظة، وحنا كنديرو الباقي.</p>
</section>

<!-- SERVICES -->
<section class="adm-services" id="services">
  <div class="adm-services-head adm-reveal">
    <p class="adm-eyebrow">خدماتنا</p>
    <h2>كلشي تحت سقف واحد</h2>
    <div class="adm-divider" style="margin-top:20px">
      <svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M8 24 L24 10 L40 24" stroke-linecap="round" stroke-linejoin="round"/><path d="M14 22 V34 H34 V22"/></svg>
    </div>
  </div>

  <div class="adm-grid">

    <div class="adm-card">
      <div class="adm-card-icon"><svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.6"><rect x="6" y="14" width="36" height="24" rx="3"/><circle cx="24" cy="26" r="7"/><rect x="17" y="9" width="10" height="6" rx="1.5"/></svg></div>
      <h3>التصوير</h3>
      <span>Photography</span>
    </div>

    <div class="adm-card">
      <div class="adm-card-icon"><svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M8 40 L24 10 L40 40 Z"/><path d="M16 40 V26 H32 V40"/></svg></div>
      <h3>الديكور</h3>
      <span>Décoration</span>
    </div>

    <div class="adm-card">
      <div class="adm-card-icon"><svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.6"><circle cx="24" cy="24" r="15"/><circle cx="24" cy="24" r="4"/><path d="M24 6 V10 M24 38 V42 M6 24 H10 M38 24 H42"/></svg></div>
      <h3>DJ وسهرة</h3>
      <span>Musique &amp; Ambiance</span>
    </div>

    <div class="adm-card">
      <div class="adm-card-icon"><svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.6"><ellipse cx="24" cy="30" rx="16" ry="8"/><path d="M24 22 C18 22 14 18 16 12 C20 15 22 12 24 8 C26 12 28 15 32 12 C34 18 30 22 24 22Z"/></svg></div>
      <h3>الطبخ التقليدي</h3>
      <span>Cuisine traditionnelle</span>
    </div>

    <div class="adm-card">
      <div class="adm-card-icon"><svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M8 20 Q24 8 40 20" /><rect x="8" y="20" width="32" height="4"/><path d="M10 24 L12 34 H36 L38 24"/></svg></div>
      <h3>البيفي</h3>
      <span>Buffet</span>
    </div>

    <div class="adm-card">
      <div class="adm-card-icon"><svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M14 42 V24 Q14 14 24 14 Q34 14 34 24 V42"/><path d="M10 42 H38"/><path d="M18 24 H30"/></svg></div>
      <h3>ممون الحفلات</h3>
      <span>Traiteur</span>
    </div>

    <div class="adm-card">
      <div class="adm-card-icon"><svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M24 6 C28 12 32 16 32 22 A8 8 0 1 1 16 22 C16 16 20 12 24 6Z"/></svg></div>
      <h3>الدبيحة المخزانية</h3>
      <span>تقليد مخزني</span>
    </div>

    <div class="adm-card">
      <div class="adm-card-icon"><svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M10 20 L14 40 H34 L38 20 Z"/><path d="M10 20 Q24 10 38 20"/><path d="M18 40 V28 M24 40 V26 M30 40 V28"/></svg></div>
      <h3>التنكافت</h3>
      <span>Plateaux d'hospitalité</span>
    </div>

    <div class="adm-card">
      <div class="adm-card-icon"><svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.6"><ellipse cx="20" cy="26" rx="10" ry="14" transform="rotate(-20 20 26)"/><path d="M28 16 L38 10 M38 10 L36 6 M38 10 L42 12"/><path d="M14 22 Q20 24 16 30"/></svg></div>
      <h3>الدقايقية مع عساوة</h3>
      <span>Musiciens traditionnels</span>
    </div>

    <div class="adm-card">
      <div class="adm-card-icon"><svg viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.6"><rect x="8" y="24" width="32" height="16" rx="2"/><path d="M8 30 H40"/><path d="M18 24 V18 M24 24 V16 M30 24 V18"/><path d="M24 16 C22 14 22 11 24 9 C26 11 26 14 24 16Z"/></svg></div>
      <h3>أعياد الميلاد</h3>
      <span>Anniversaires</span>
    </div>

  </div>
</section>

<!-- ZONES -->
<section class="adm-zones adm-reveal">
  <p class="adm-eyebrow">مناطق التغطية</p>
  <h2>كنغطيو سلا والرباط بجوج</h2>
  <div class="adm-zone-chips">
    <div class="adm-chip">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M12 21s-7-6.2-7-11a7 7 0 1 1 14 0c0 4.8-7 11-7 11Z"/><circle cx="12" cy="10" r="2.5"/></svg>
      سلا الجديدة — 477 المعرض
    </div>
    <div class="adm-chip">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M12 21s-7-6.2-7-11a7 7 0 1 1 14 0c0 4.8-7 11-7 11Z"/><circle cx="12" cy="10" r="2.5"/></svg>
      الرباط
    </div>
  </div>
</section>

<!-- CTA -->
<section class="adm-cta" id="contact">
  <div class="adm-cta-inner adm-reveal">
    <p class="adm-eyebrow">تواصلو معانا</p>
    <h2>خصكم تنظيم حفلة؟</h2>
    <p>هدرو معانا على واتساب، وغادي نبداو نخططو ليها بجوج — من الفكرة الأولى حتى آخر لحظة فالحفل.</p>
    <div class="adm-hero-ctas">
      <a class="adm-btn adm-btn-solid" href="https://wa.me/212661655667?text=سلام،%20بغيت%20نتواصل%20معاكم%20بخصوص%20تنظيم%20حفلة" target="_blank" rel="noopener">
        <svg viewBox="0 0 24 24" fill="currentColor"><path d="M12.04 2C6.58 2 2.13 6.45 2.13 11.91c0 1.75.46 3.45 1.32 4.95L2 22l5.29-1.39a9.9 9.9 0 0 0 4.75 1.21h.01c5.46 0 9.9-4.45 9.9-9.91C21.96 6.45 17.5 2 12.04 2zm0 18.06h-.01a8.2 8.2 0 0 1-4.19-1.15l-.3-.18-3.14.82.84-3.06-.2-.31a8.16 8.16 0 0 1-1.27-4.36c0-4.53 3.7-8.22 8.24-8.22 2.2 0 4.27.86 5.82 2.42a8.14 8.14 0 0 1 2.41 5.81c0 4.54-3.7 8.23-8.2 8.23zm4.5-6.16c-.25-.12-1.46-.72-1.68-.8-.23-.08-.39-.12-.56.12-.16.25-.64.8-.78.96-.15.17-.29.19-.53.06-.25-.12-1.04-.38-1.98-1.22-.73-.65-1.23-1.46-1.37-1.7-.15-.25-.02-.38.11-.5.11-.11.25-.29.37-.43.12-.15.16-.25.24-.41.08-.17.04-.31-.02-.43-.06-.12-.56-1.35-.77-1.85-.2-.48-.41-.42-.56-.43-.14-.01-.31-.01-.47-.01-.17 0-.43.06-.66.31-.23.25-.86.85-.86 2.06 0 1.22.89 2.4 1.01 2.56.12.17 1.75 2.67 4.24 3.74.59.26 1.06.41 1.42.53.6.19 1.14.16 1.57.1.48-.07 1.46-.6 1.67-1.18.2-.58.2-1.07.14-1.18-.06-.1-.22-.16-.47-.28z"/></svg>
        0661 65 56 67
      </a>
      <a class="adm-btn adm-btn-outline" href="https://www.instagram.com/afrah_dar_el_mima" target="_blank" rel="noopener">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r="1"/></svg>
        @afrah_dar_el_mima
      </a>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="adm-footer-grid">
    <div>
      <div class="adm-footer-brand">
        <div class="adm-nav-emblem">
          <svg viewBox="0 0 48 48" fill="none" stroke="var(--gold)" stroke-width="2"><path d="M8 24 L24 10 L40 24" stroke-linecap="round" stroke-linejoin="round"/><path d="M12 22 V38 H36 V22"/><path d="M20 38 V28 H28 V38"/></svg>
        </div>
        <span class="adm-footer-brand-name">أفراح دار الميمة</span>
      </div>
      <p style="margin-top:16px;max-width:260px;font-size:0.9rem;line-height:1.9;color:rgba(251,244,231,0.55)">اللمسة لي كتجمع الدفء والأناقة فتنظيم حفلاتكم.</p>
      <div class="adm-footer-social">
        <a href="https://www.instagram.com/afrah_dar_el_mima" target="_blank" rel="noopener" aria-label="Instagram">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r="1"/></svg>
        </a>
        <a href="https://wa.me/212661655667" target="_blank" rel="noopener" aria-label="WhatsApp">
          <svg viewBox="0 0 24 24" fill="currentColor"><path d="M12.04 2C6.58 2 2.13 6.45 2.13 11.91c0 1.75.46 3.45 1.32 4.95L2 22l5.29-1.39a9.9 9.9 0 0 0 4.75 1.21h.01c5.46 0 9.9-4.45 9.9-9.91C21.96 6.45 17.5 2 12.04 2zm4.5 13.9c-.25-.12-1.46-.72-1.68-.8-.23-.08-.39-.12-.56.12-.16.25-.64.8-.78.96-.15.17-.29.19-.53.06-.25-.12-1.04-.38-1.98-1.22-.73-.65-1.23-1.46-1.37-1.7-.15-.25-.02-.38.11-.5.11-.11.25-.29.37-.43.12-.15.16-.25.24-.41.08-.17.04-.31-.02-.43-.06-.12-.56-1.35-.77-1.85-.2-.48-.41-.42-.56-.43-.14-.01-.31-.01-.47-.01-.17 0-.43.06-.66.31-.23.25-.86.85-.86 2.06 0 1.22.89 2.4 1.01 2.56.12.17 1.75 2.67 4.24 3.74.59.26 1.06.41 1.42.53.6.19 1.14.16 1.57.1.48-.07 1.46-.6 1.67-1.18.2-.58.2-1.07.14-1.18-.06-.1-.22-.16-.47-.28z"/></svg>
        </a>
      </div>
    </div>

    <div class="adm-footer-col">
      <h4>روابط</h4>
      <ul>
        <li><a href="#home">الرئيسية</a></li>
        <li><a href="#about">من نحنا</a></li>
        <li><a href="#services">خدماتنا</a></li>
        <li><a href="#contact">تواصل معانا</a></li>
      </ul>
    </div>

    <div class="adm-footer-col">
      <h4>تواصل</h4>
      <ul>
        <li>0661 65 56 67</li>
        <li>سلا الجديدة — 477 المعرض</li>
        <li>سلا · الرباط</li>
      </ul>
    </div>
  </div>
  <div class="adm-footer-bottom">© 2026 أفراح دار الميمة — جميع الحقوق محفوظة</div>
</footer>

<a class="adm-float-wa" href="https://wa.me/212661655667?text=سلام،%20بغيت%20نتواصل%20معاكم%20بخصوص%20تنظيم%20حفلة" target="_blank" rel="noopener" aria-label="تواصل عبر واتساب">
  <svg viewBox="0 0 24 24" fill="currentColor"><path d="M12.04 2C6.58 2 2.13 6.45 2.13 11.91c0 1.75.46 3.45 1.32 4.95L2 22l5.29-1.39a9.9 9.9 0 0 0 4.75 1.21h.01c5.46 0 9.9-4.45 9.9-9.91C21.96 6.45 17.5 2 12.04 2zm4.5 13.9c-.25-.12-1.46-.72-1.68-.8-.23-.08-.39-.12-.56.12-.16.25-.64.8-.78.96-.15.17-.29.19-.53.06-.25-.12-1.04-.38-1.98-1.22-.73-.65-1.23-1.46-1.37-1.7-.15-.25-.02-.38.11-.5.11-.11.25-.29.37-.43.12-.15.16-.25.24-.41.08-.17.04-.31-.02-.43-.06-.12-.56-1.35-.77-1.85-.2-.48-.41-.42-.56-.43-.14-.01-.31-.01-.47-.01-.17 0-.43.06-.66.31-.23.25-.86.85-.86 2.06 0 1.22.89 2.4 1.01 2.56.12.17 1.75 2.67 4.24 3.74.59.26 1.06.41 1.42.53.6.19 1.14.16 1.57.1.48-.07 1.46-.6 1.67-1.18.2-.58.2-1.07.14-1.18-.06-.1-.22-.16-.47-.28z"/></svg>
</a>

<script>
  // Mobile nav toggle
  const toggle = document.getElementById('admToggle');
  const links = document.getElementById('admLinks');
  toggle.addEventListener('click', () => links.classList.toggle('adm-open'));
  links.querySelectorAll('a').forEach(a => a.addEventListener('click', () => links.classList.remove('adm-open')));

  // Reveal on scroll
  const revealEls = document.querySelectorAll('.adm-reveal, .adm-card');
  const io = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if(entry.isIntersecting){
        entry.target.classList.add('adm-visible');
        io.unobserve(entry.target);
      }
    });
  }, { threshold: 0.15 });
  revealEls.forEach((el, i) => {
    el.style.transitionDelay = (i % 10) * 0.06 + 's';
    io.observe(el);
  });
</script>

</body>
</html>
