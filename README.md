<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Kyrgyz Student Association — Rowan University</title>
<meta name="description" content="KSA brings together Kyrgyz students at Rowan and everyone curious about Kyrgyzstan.">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700&family=Unbounded:wght@600;700;800&display=swap">
<style>
#links, #site{min-height:100vh;display:flex;flex-direction:column;align-items:center;font-family:'Manrope',system-ui,sans-serif;color:#2A1A14}
#links *, #site *{box-sizing:border-box}

/* Общие стили */
.hero{width:100%;background:#A3161C;border-radius:0 0 32px 32px;padding:48px 24px 40px;display:flex;flex-direction:column;align-items:center;gap:18px;text-align:center}
.eyebrow{font-size:12px;font-weight:700;letter-spacing:2px;color:#F2B134}
.hero h1{margin:0;font-family:'Unbounded','Manrope',sans-serif;font-weight:700;font-size:30px;line-height:1.15;color:#FBF3E8}
.hero p{margin:0;font-size:15px;line-height:1.55;color:#F6E4D3;max-width:330px}
.list{width:100%;max-width:440px;padding:28px 20px 36px;display:flex;flex-direction:column;gap:12px}
.lk{min-height:58px;padding:0 22px;border-radius:999px;background:#FBF3E8;border:1px solid #E3CFB4;color:#2A1A14;font-weight:600;font-size:16px;display:flex;align-items:center;justify-content:space-between;gap:12px;transition:transform .15s ease,box-shadow .15s ease;text-decoration:none}
.lk:hover{transform:translateY(-2px);box-shadow:0 6px 16px rgba(80,20,20,.14)}
.lk.main{background:#A3161C;border-color:#A3161C;color:#FBF3E8;font-weight:700}
.lk svg{flex:none}
.event-card{background:#FBF3E8;border:1px solid #E3CFB4;border-radius:20px;padding:16px;margin-top:16px;text-align:center}
.event-card img{width:100%;border-radius:12px;object-fit:cover;max-height:220px}
.event-card h3{margin:12px 0 6px;font-size:18px;color:#2A1A14}
.event-card p{margin:0;font-size:14px;color:#6B5648}
.foot{margin:20px 0 0;text-align:center;font-size:13px;color:#6B5648}

/* Переключение видов для ProFlink / site */
html:not([data-view="site"]) #site{display:none}
html[data-view="site"] #links{display:none}
</style>
</head>
<body>

<!-- Стандартное отображение со ВСЕМИ разделами (включая Past Events) -->
<div id="links">
  <div class="hero">
    <div class="eyebrow">ROWAN UNIVERSITY</div>
    <h1>Kyrgyz Student Association</h1>
    <p>KSA brings together Kyrgyz students at Rowan and everyone curious about Kyrgyzstan.</p>
  </div>
  
  <div class="list">
    <!-- Ссылка на Instagram -->
    <a class="lk" href="https://www.instagram.com/ksa.rowan/" target="_blank">
      <span>Instagram</span>
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
    </a>

    <!-- Секция Upcoming Events -->
    <div class="event-card">
      <img src="путь_к_фото_upcoming.jpg" alt="Upcoming Event">
      <h3>Upcoming Events</h3>
      <p>Описание предстоящего мероприятия, дата и время проведения.</p>
    </div>

    <!-- Секция Past Events (присутствует по умолчанию) -->
    <div class="event-card">
      <img src="путь_к_фото_past.jpg" alt="Past Event">
      <h3>Past Events</h3>
      <p>Описание прошедших мероприятий и прошедших событий.</p>
    </div>
  </div>

  <div class="foot">
    © 2026 Kyrgyz Student Association — Rowan University
  </div>
</div>

<!-- Отображение для ProFlink (data-view="site") — БЕЗ раздела Past Events -->
<div id="site">
  <div class="hero">
    <div class="eyebrow">ROWAN UNIVERSITY</div>
    <h1>Kyrgyz Student Association</h1>
    <p>KSA brings together Kyrgyz students at Rowan and everyone curious about Kyrgyzstan.</p>
  </div>
  
  <div class="list">
    <!-- Ссылка на Instagram -->
    <a class="lk" href="https://www.instagram.com/ksa.rowan/" target="_blank">
      <span>Instagram</span>
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
    </a>

    <!-- Секция Upcoming Events -->
    <div class="event-card">
      <img src="<img width="896" height="1184" alt="WhatsApp Image 2026-10-26 at 23 40 46" src="https://github.com/user-attachments/assets/8889cbfb-b529-4a97-844c-e4325505a8ec" />" alt="Upcoming Event">
      <h3>Upcoming Events</h3>
      <p>We're plannig a student meetup with games Kahoot and Jeopardy.</p>
    </div>
  </div>

  <div class="foot">
    © 2026 Kyrgyz Student Association — Rowan University
  </div>
</div>

</body>
</html>
