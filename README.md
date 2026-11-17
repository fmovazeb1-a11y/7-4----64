# 7-4----64

<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#07182b">
<title>AMIR SG | پرونده آب تهران</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;500;600;700;800;900&display=swap');

:root{
  --bg:#061525;
  --bg2:#0a2036;
  --card:#102a42;
  --blue:#168fe5;
  --cyan:#36d4df;
  --green:#20c9a1;
  --white:#f4f9ff;
  --muted:#a8bed0;
  --line:rgba(255,255,255,.11);
}
*{box-sizing:border-box;scroll-behavior:smooth}
body{
  margin:0;
  font-family:'Vazirmatn',Tahoma,sans-serif;
  background:var(--bg);
  color:var(--white);
  line-height:2;
  overflow-x:hidden;
}
body:before{
  content:"امیرحسین مواظب     امیرحسین مواظب     امیرحسین مواظب     امیرحسین مواظب     امیرحسین مواظب";
  position:fixed;
  inset:-50px;
  z-index:-1;
  color:rgba(255,255,255,.045);
  font-size:25px;
  font-weight:900;
  line-height:6;
  letter-spacing:3px;
  word-spacing:22px;
  transform:rotate(-18deg) scale(1.3);
  pointer-events:none;
  overflow:hidden;
}
a{color:inherit;text-decoration:none}
button{font-family:inherit}
.container{width:min(1120px,91%);margin:auto}
nav{
  position:sticky;top:0;z-index:50;
  background:rgba(5,19,34,.88);
  backdrop-filter:blur(18px);
  border-bottom:1px solid var(--line);
}
.nav-inner{
  min-height:72px;display:flex;align-items:center;
  justify-content:space-between;gap:20px;
}
.logo{font-size:20px;font-weight:900;letter-spacing:1px}
.logo span{color:var(--cyan)}
.nav-links{display:flex;gap:22px;align-items:center}
.nav-links a{font-size:13px;color:var(--muted);transition:.2s}
.nav-links a:hover{color:var(--cyan)}
.menu-btn{
  display:none;background:var(--card);border:1px solid var(--line);
  color:white;border-radius:10px;padding:7px 13px;font-size:20px;
}
.hero{
  min-height:640px;display:flex;align-items:center;
  position:relative;overflow:hidden;
  background:
    radial-gradient(ellipse at 78% 35%,rgba(0,153,230,.28),transparent 36%),
    radial-gradient(ellipse at 15% 90%,rgba(0,205,180,.14),transparent 35%),
    linear-gradient(125deg,#061525,#0a2944 60%,#061525);
  border-bottom:1px solid var(--line);
}
.hero:after{
  content:"";position:absolute;width:460px;height:460px;
  border:1px solid rgba(54,212,223,.2);border-radius:50%;
  left:-100px;top:90px;box-shadow:0 0 0 35px rgba(54,212,223,.025),0 0 0 75px rgba(54,212,223,.02);
}
.hero-content{position:relative;z-index:2;padding:95px 0}
.eyebrow{
  display:inline-flex;gap:9px;align-items:center;
  color:var(--cyan);font-size:13px;font-weight:700;
  border:1px solid rgba(54,212,223,.3);
  padding:5px 14px;border-radius:30px;background:rgba(54,212,223,.07)
}
.hero h1{font-size:clamp(38px,7vw,76px);line-height:1.35;margin:22px 0 12px;font-weight:900}
.hero h1 span{
  background:linear-gradient(90deg,#36d4df,#168fe5);
  -webkit-background-clip:text;color:transparent;
}
.hero p{max-width:650px;color:#bed0df;font-size:17px}
.hero-actions{display:flex;gap:12px;flex-wrap:wrap;margin-top:30px}
.btn{
  display:inline-block;padding:11px 23px;border-radius:12px;
  font-weight:700;font-size:14px;transition:.2s;
}
.btn-primary{background:linear-gradient(110deg,#168fe5,#16bfc9);color:white}
.btn-outline{border:1px solid var(--line);color:white;background:rgba(255,255,255,.04)}
.btn:hover{transform:translateY(-3px);filter:brightness(1.1)}
.hero-note{margin-top:50px;color:#8eaabd;font-size:12px}
.section{padding:85px 0;scroll-margin-top:80px}
.section.alt{background:rgba(12,37,59,.58);border-block:1px solid var(--line)}
.section-head{margin-bottom:35px}
.kicker{color:var(--cyan);font-size:12px;font-weight:800;letter-spacing:1px}
.section h2{font-size:clamp(26px,4vw,39px);margin:7px 0 8px;line-height:1.5}
.section-head p{color:var(--muted);max-width:750px;margin:0}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:17px}
.card{
  background:linear-gradient(145deg,rgba(18,48,73,.95),rgba(9,30,49,.9));
  border:1px solid var(--line);border-radius:19px;padding:23px;
  transition:.25s;position:relative;overflow:hidden;
}
.card:hover{transform:translateY(-5px);border-color:rgba(54,212,223,.45)}
.card-icon{
  width:48px;height:48px;border-radius:14px;
  display:grid;place-items:center;font-size:23px;
  background:rgba(22,143,229,.14);margin-bottom:13px
}
.card h3{margin:0 0 8px;font-size:18px}
.card p{color:var(--muted);font-size:14px;margin:0}
.tag{display:inline-block;color:var(--cyan);font-size:11px;margin-top:14px}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:15px;margin-top:25px}
.stat{
  padding:23px;border-radius:16px;background:rgba(255,255,255,.045);
  border:1px solid var(--line)
}
.stat strong{display:block;font-size:32px;color:var(--cyan);line-height:1.6}
.stat span{font-size:13px;color:var(--muted)}
.warning{
  margin-top:20px;padding:16px 20px;border-right:3px solid #e9b84d;
  background:rgba(233,184,77,.08);border-radius:10px;
  color:#e8d7ad;font-size:13px
}
.dam-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:12px}
.dam{
  text-align:center;padding:19px 10px;border-radius:15px;
  background:rgba(255,255,255,.045);border:1px solid var(--line)
}
.dam .emoji{font-size:28px}
.dam b{display:block;margin:7px 0 2px}
.dam small{font-size:11px;color:var(--muted)}
.flow{display:grid;grid-template-columns:repeat(5,1fr);gap:10px;align-items:stretch}
.flow-step{
  text-align:center;padding:20px 10px;border:1px solid var(--line);
  border-radius:15px;background:rgba(255,255,255,.04);cursor:pointer;
  transition:.2s
}
.flow-step:hover,.flow-step.active{
  border-color:var(--cyan);background:rgba(54,212,223,.1)
}
.flow-step .emoji{font-size:30px;display:block}
.flow-step b{display:block;font-size:14px;margin:7px 0}
.flow-step small{font-size:11px;color:var(--muted)}
.flow-detail{
  margin-top:17px;padding:22px;border-radius:15px;
  background:rgba(22,143,229,.09);border:1px solid rgba(54,212,223,.25);
  min-height:110px
}
.flow-detail h3{margin:0 0 5px;color:var(--cyan)}
.flow-detail p{margin:0;color:#c0d2df;font-size:14px}
.uses{display:grid;grid-template-columns:repeat(2,1fr);gap:15px}
.use-item{display:flex;gap:15px;align-items:flex-start}
.use-item .card-icon{flex-shrink:0}
.use-item h3{margin:0 0 5px;font-size:17px}
.use-item p{margin:0;color:var(--muted);font-size:13px}
.compare{width:100%;border-collapse:collapse;margin-top:20px;font-size:13px}
.compare th,.compare td{padding:13px;text-align:right;border-bottom:1px solid var(--line)}
.compare th{color:var(--cyan);background:rgba(54,212,223,.06)}
.compare td{color:#c2d2df}
.compare tr:hover td{background:rgba(255,255,255,.025)}
.accordion{display:grid;gap:10px}
.acc-item{border:1px solid var(--line);border-radius:14px;overflow:hidden;background:rgba(255,255,255,.035)}
.acc-btn{
  width:100%;text-align:right;background:none;color:white;border:0;
  padding:17px 20px;font-weight:700;font-size:15px;cursor:pointer;
  display:flex;justify-content:space-between;gap:15px
}
.acc-content{display:none;padding:0 20px 18px;color:var(--muted);font-size:14px}
.acc-item.open .acc-content{display:block}
.acc-item.open .plus{transform:rotate(45deg);color:var(--cyan)}
.plus{font-size:22px;transition:.2s}
.proposal-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:15px}
.proposal{padding:19px;border:1px solid var(--line);border-radius:15px;background:rgba(255,255,255,.035)}
.proposal b{color:var(--cyan);display:block;margin-bottom:5px}
.proposal p{margin:0;color:var(--muted);font-size:13px}
.quiz{
  background:linear-gradient(135deg,rgba(22,143,229,.13),rgba(32,201,161,.07));
  border:1px solid rgba(54,212,223,.23);border-radius:20px;padding:25px
}
.quiz h3{margin-top:0}
.question{padding:15px 0;border-bottom:1px solid var(--line)}
.question p{font-weight:700;margin:0 0 10px}
.question label{display:block;color:var(--muted);font-size:14px;padding:5px;cursor:pointer}
.question input{accent-color:var(--cyan);margin-left:7px}
.quiz button{
  margin-top:20px;background:var(--blue);color:white;border:0;
  border-radius:10px;padding:12px 25px;font-weight:700;cursor:pointer
}
#quiz-result{margin-top:15px;font-weight:700;color:var(--cyan)}
.sources{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
.source{
  border:1px solid var(--line);padding:16px;border-radius:13px;
  background:rgba(255,255,255,.035)
}
.source a{color:var(--cyan);font-weight:700}
.source p{font-size:12px;color:var(--muted);margin:5px 0 0}
footer{padding:35px 0;background:#04101d;border-top:1px solid var(--line)}
.footer-inner{display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap}
footer p{color:var(--muted);font-size:12px;margin:4px 0}
footer strong{color:white}
.back-top{
  position:fixed;bottom:20px;left:20px;width:43px;height:43px;
  border-radius:50%;border:1px solid var(--line);background:#0c3452;
  color:white;font-size:20px;cursor:pointer;z-index:30
}
@media(max-width:850px){
 .nav-links{display:none;position:absolute;top:72px;right:0;left:0;
  background:#07182b;padding:20px;flex-direction:column;align-items:stretch;
  border-bottom:1px solid var(--line)}
 .nav-links.show{display:flex}
 .menu-btn{display:block}
 .grid{grid-template-columns:repeat(2,1fr)}
 .dam-grid{grid-template-columns:repeat(3,1fr)}
 .flow{grid-template-columns:repeat(3,1fr)}
}
@media(max-width:560px){
 .hero{min-height:570px}
 .hero-content{padding:75px 0}
 .hero p{font-size:14px}
 .grid,.stats,.uses,.proposal-grid,.sources{grid-template-columns:1fr}
 .dam-grid{grid-template-columns:repeat(2,1fr)}
 .flow{grid-template-columns:repeat(2,1fr)}
 .section{padding:65px 0}
 .stat strong{font-size:27px}
}
</style>
</head>
<body>

<nav>
 <div class="container nav-inner">
  <a class="logo" href="#home">AMIR <span>SG.</span></a>
  <button class="menu-btn" onclick="toggleMenu()" aria-label="باز کردن منو">☰</button>
  <div class="nav-links" id="navLinks">
   <a href="#sources">منابع آب</a>
   <a href="#journey">سفر آب</a>
   <a href="#uses">مصارف</a>
   <a href="#pollution">آلودگی</a>
   <a href="#solutions">راهکارها</a>
   <a href="#quiz">آزمون</a>
  </div>
 </div>
</nav>

<header class="hero" id="home">
 <div class="container hero-content">
  <div class="eyebrow">● پرونده ویژه محیط زیست و علوم هفتم</div>
  <h1>تهران و <span>آخرین قطره</span></h1>
  <p>
   آب از کجا می‌آید، چگونه به خانه‌های ما می‌رسد و چه خطرهایی آینده منابع آبی پایتخت را تهدید می‌کند؟
   در این پرونده، مسیر آب تهران را از سرچشمه تا شیر آب بررسی می‌کنیم.
  </p>
  <div class="hero-actions">
   <a class="btn btn-primary" href="#sources">شروع بررسی ←</a>
   <a class="btn btn-outline" href="#solutions">راهکارهای ما</a>
  </div>
  <div class="hero-note">یک تحقیق دانش‌آموزی درباره منابع آب، مصرف، آلودگی و حفاظت از آب تهران</div>
 </div>
</header>

<main>
<section class="section" id="sources">
 <div class="container">
  <div class="section-head">
   <div class="kicker">01 / WATER SOURCES</div>
   <h2>آب تهران از کجا می‌آید؟</h2>
   <p>
    آب موردنیاز شهر تهران از دو گروه اصلی منابع تأمین می‌شود: آب‌های سطحی و آب‌های زیرزمینی.
    این دو منبع در کنار یکدیگر در تأمین آب شهر نقش دارند.
   </p>
  </div>

  <div class="grid">
   <article class="card">
    <div class="card-icon">🏞️</div>
    <h3>آب‌های سطحی</h3>
    <p>
     آب باران و برف در رودخانه‌ها و پشت سدها جمع می‌شود.
     بخشی از آب شرب تهران از سدهای اطراف شهر تأمین می‌شود و پیش از ورود به شبکه، تصفیه می‌شود.
    </p>
    <span class="tag">منابع طبیعی روی سطح زمین</span>
   </article>
   <article class="card">
    <div class="card-icon">💧</div>
    <h3>آب‌های زیرزمینی</h3>
    <p>
     بخشی از بارش‌ها در زمین نفوذ می‌کند و در لایه‌های آبدار خاک و سنگ ذخیره می‌شود.
     این آب با استفاده از چاه‌ها برداشت می‌شود.
    </p>
    <span class="tag">آب ذخیره‌شده در زیر زمین</span>
   </article>
   <article class="card">
    <div class="card-icon">⚖️</div>
    <h3>چرا هر دو منبع؟</h3>
    <p>
     میزان بارندگی و ذخیره سدها در طول سال تغییر می‌کند.
     استفاده از چند منبع، امکان مدیریت بهتر تأمین آب را فراهم می‌کند؛ البته برداشت از آب زیرزمینی باید کنترل شود.
    </p>
    <span class="tag">مدیریت منابع آب</span>
   </article>
  </div>

  <h3 style="margin-top:38px">پنج سد مهم در سامانه تأمین آب تهران</h3>
  <div class="dam-grid">
   <div class="dam"><div class="emoji">🏔️</div><b>امیرکبیر</b><small>سد کرج</small></div>
   <div class="dam"><div class="emoji">🌊</div><b>طالقان</b><small>استان البرز</small></div>
   <div class="dam"><div class="emoji">🏞️</div><b>لار</b><small>شرق تهران</small></div>
   <div class="dam"><div class="emoji">💦</div><b>لتیان</b><small>رودخانه جاجرود</small></div>
   <div class="dam"><div class="emoji">🌿</div><b>ماملو</b><small>جنوب‌شرق تهران</small></div>
  </div>

  <div class="warning">
   نکته علمی: این سدها در سامانه تأمین آب شرب تهران نقش دارند؛ اما آب شهر فقط از سدها تأمین نمی‌شود و منابع زیرزمینی نیز سهم مهمی دارند.
  </div>

  <div class="stats">
   <div class="stat">
    <strong>۲</strong>
    <span>گروه اصلی منابع: سطحی و زیرزمینی</span>
   </div>
   <div class="stat">
    <strong>۵</strong>
    <span>سد مهم در سامانه تأمین آب شرب تهران</span>
   </div>
   <div class="stat">
    <strong>۱۰۰٪</strong>
    <span>اهمیت حفاظت از هر دو منبع آبی</span>
   </div>
  </div>
 </div>
</section>

<section class="section alt" id="journey">
 <div class="container">
  <div class="section-head">
   <div class="kicker">02 / WATER JOURNEY</div>
   <h2>سفر یک قطره آب تا خانه</h2>
   <p>روی هر مرحله بزن تا ببینی آب چگونه از طبیعت به شیر آب خانه می‌رسد.</p>
  </div>
  <div class="flow">
   <button class="flow-step active" onclick="showStep(0)">
    <span class="emoji">🌧️</span><b>بارش</b><small>باران و برف</small>
   </button>
   <button class="flow-step" onclick="showStep(1)">
    <span class="emoji">🏞️</span><b>ذخیره</b><small>سد و سفره آب</small>
   </button>
   <button class="flow-step" onclick="showStep(2)">
    <span class="emoji">🏭</span><b>تصفیه</b><small>آماده‌سازی آب</small>
   </button>
   <button class="flow-step" onclick="showStep(3)">
    <span class="emoji">🚰</span><b>توزیع</b><small>شبکه لوله‌کشی</small>
   </button>
   <button class="flow-step" onclick="showStep(4)">
    <span class="emoji">🏠</span><b>مصرف</b><small>خانه و شهر</small>
   </button>
  </div>
  <div class="flow-detail" id="flowDetail">
   <h3>مرحله اول: بارش</h3>
   <p>بخشی از بارش‌ها روی سطح زمین جاری می‌شود و به رودخانه‌ها و سدها می‌رسد. بخشی دیگر در زمین نفوذ می‌کند و ذخایر آب زیرزمینی را تغذیه می‌کند.</p>
  </div>
  <div class="warning">
   آب چاه و آب سد مستقیماً و بدون بررسی وارد مصرف آشامیدنی نمی‌شوند. کیفیت آب باید مطابق استانداردهای بهداشتی بررسی و در صورت نیاز تصفیه شود.
  </div>
 </div>
</section>

<section class="section" id="uses">
 <div class="container">
  <div class="section-head">
   <div class="kicker">03 / WATER USE</div>
   <h2>آب کجا مصرف می‌شود؟</h2>
   <p>آب فقط برای نوشیدن و شست‌وشو نیست؛ زندگی شهر و فعالیت‌های اقتصادی هم به آن وابسته‌اند.</p>
  </div>
  <div class="uses">
   <div class="card use-item">
    <div class="card-icon">🏡</div>
    <div><h3>مصارف خانگی</h3><p>نوشیدن، پخت‌وپز، حمام، شست‌وشوی لباس و ظروف، نظافت و آبیاری گیاهان خانه.</p></div>
   </div>
   <div class="card use-item">
    <div class="card-icon">🌾</div>
    <div><h3>کشاورزی</h3><p>آبیاری زمین‌های کشاورزی و باغ‌ها و تأمین آب موردنیاز دامداری‌ها.</p></div>
   </div>
   <div class="card use-item">
    <div class="card-icon">🏭</div>
    <div><h3>صنعت</h3><p>استفاده در فرایندهای تولید، شست‌وشو، خنک‌سازی دستگاه‌ها و کارخانه‌ها.</p></div>
   </div>
   <div class="card use-item">
    <div class="card-icon">🌳</div>
    <div><h3>خدمات شهری</h3><p>آبیاری فضای سبز، نظافت معابر، آتش‌نشانی و برخی خدمات عمومی شهر.</p></div>
   </div>
  </div>
  <div class="warning">
   سهم هر بخش از مصرف آب در شهر و استان یکسان نیست. برای بیان درصد دقیق باید آمار همان سال و همان محدوده جغرافیایی بررسی شود.
  </div>
 </div>
</section>

<section class="section alt" id="pollution">
 <div class="container">
  <div class="section-head">
   <div class="kicker">04 / WATER POLLUTION</div>
   <h2>چه چیزهایی آب را آلوده می‌کنند؟</h2>
   <p>آلودگی آب می‌تواند سلامت انسان، جانوران، گیاهان و محیط زیست را به خطر بیندازد.</p>
  </div>
  <div class="grid">
   <article class="card">
    <div class="card-icon">🧴</div>
    <h3>مواد شیمیایی</h3>
    <p>ورود مواد شوینده، روغن‌ها، سموم و برخی مواد صنعتی به آب می‌تواند کیفیت آن را کاهش دهد.</p>
   </article>
   <article class="card">
    <div class="card-icon">🗑️</div>
    <h3>زباله و پسماند</h3>
    <p>رها کردن زباله در رودخانه‌ها و طبیعت باعث آلودگی آب‌های سطحی و آسیب به جانداران می‌شود.</p>
   </article>
   <article class="card">
    <div class="card-icon">🚽</div>
    <h3>فاضلاب</h3>
    <p>ورود فاضلاب تصفیه‌نشده به رودخانه‌ها و زمین می‌تواند میکروب‌ها و مواد آلاینده را وارد منابع آب کند.</p>
   </article>
  </div>
  <h3 style="margin-top:35px">نتیجه آلودگی آب چیست؟</h3>
  <table class="compare">
   <thead><tr><th>عامل</th><th>پیامد احتمالی</th><th>راه پیشگیری</th></tr></thead>
   <tbody>
    <tr><td>فاضلاب تصفیه‌نشده</td><td>انتقال عوامل بیماری‌زا</td><td>تصفیه و دفع اصولی فاضلاب</td></tr>
    <tr><td>مواد شیمیایی</td><td>کاهش کیفیت آب و آسیب زیست‌محیطی</td><td>کنترل پساب و مصرف درست مواد شیمیایی</td></tr>
    <tr><td>زباله</td><td>آسیب به رودخانه‌ها و جانوران</td><td>جمع‌آوری و مدیریت پسماند</td></tr>
    <tr><td>سموم کشاورزی</td><td>آلودگی خاک و آب</td><td>مصرف کنترل‌شده و اصولی سموم</td></tr>
   </tbody>
  </table>
 </div>
</section>

<section class="section" id="groundwater">
 <div class="container">
  <div class="section-head">
   <div class="kicker">05 / UNDERGROUND WATER</div>
   <h2>خطر پنهان زیر پای تهران</h2>
   <p>آب‌های زیرزمینی ذخیره‌ای ارزشمند هستند؛ اما برداشت بیش از اندازه می‌تواند مشکلات جدی ایجاد کند.</p>
  </div>
  <div class="grid">
   <article class="card">
    <div class="card-icon">🕳️</div>
    <h3>برداشت بیش از حد</h3>
    <p>اگر مقدار آبی که از سفره‌های زیرزمینی برداشت می‌شود از میزان تغذیه طبیعی آن‌ها بیشتر باشد، سطح آب زیرزمینی پایین می‌رود.</p>
   </article>
   <article class="card">
    <div class="card-icon">📉</div>
    <h3>افت سطح آب</h3>
    <p>با کاهش ذخیره آب زیرزمینی، چاه‌ها ممکن است به آب کمتری دسترسی پیدا کنند و تأمین آب دشوارتر شود.</p>
   </article>
   <article class="card">
    <div class="card-icon">🏚️</div>
    <h3>فرونشست زمین</h3>
    <p>برداشت بی‌رویه می‌تواند باعث فشرده‌شدن لایه‌های خاک و فرونشست زمین شود؛ پدیده‌ای که در بخش‌هایی از دشت تهران گزارش شده است.</p>
   </article>
  </div>
  <div class="warning">
   فرونشست زمین با فرورفتن ناگهانی یک حفره فرق دارد. این پدیده معمولاً به‌تدریج و بر اثر فشرده‌شدن لایه‌های زیرزمینی رخ می‌دهد.
  </div>
 </div>
</section>

<section class="section alt" id="solutions">
 <div class="container">
  <div class="section-head">
   <div class="kicker">06 / OUR SOLUTIONS</div>
   <h2>پیشنهادهای AMIR SG برای آینده آب تهران</h2>
   <p>حفاظت از آب فقط وظیفه مردم نیست؛ شهروندان، مدیران شهری، کشاورزان و صنایع همگی نقش دارند.</p>
  </div>
  <div class="proposal-grid">
   <div class="proposal"><b>۱. تعمیر نشتی شبکه</b><p>شناسایی و تعمیر سریع لوله‌های فرسوده و نشتی‌های شبکه توزیع آب.</p></div>
   <div class="proposal"><b>۲. اصلاح روش آبیاری</b><p>استفاده از روش‌های مناسب و کم‌مصرف آبیاری متناسب با نوع زمین و محصول.</p></div>
   <div class="proposal"><b>۳. استفاده دوباره از پساب تصفیه‌شده</b><p>استفاده از پساب استاندارد و تصفیه‌شده برای بعضی مصارف غیرآشامیدنی، مانند آبیاری فضای سبز.</p></div>
   <div class="proposal"><b>۴. حفاظت از آب‌های زیرزمینی</b><p>کنترل برداشت از چاه‌ها، جلوگیری از چاه‌های غیرمجاز و کمک به تغذیه سفره‌های آب زیرزمینی.</p></div>
   <div class="proposal"><b>۵. جلوگیری از آلودگی</b><p>جلوگیری از ورود زباله، روغن، مواد شیمیایی و فاضلاب تصفیه‌نشده به محیط زیست.</p></div>
   <div class="proposal"><b>۶. فرهنگ‌سازی</b><p>آموزش روش‌های مصرف درست آب در مدرسه، خانه و رسانه‌ها.</p></div>
   <div class="proposal"><b>۷. مدیریت فضای سبز</b><p>انتخاب گیاهان سازگار با اقلیم و آبیاری در زمان مناسب برای کاهش تبخیر.</p></div>
   <div class="proposal"><b>۸. پایش کیفیت آب</b><p>آزمایش منظم منابع آب و نظارت بر کیفیت آب آشامیدنی و پساب‌ها.</p></div>
  </div>
  <div class="card" style="margin-top:22px;border-color:rgba(54,212,223,.35)">
   <div class="kicker">FINAL MESSAGE</div>
   <h2 style="font-size:25px">آب فقط یک منبع طبیعی نیست؛ سرمایه زندگی ماست.</h2>
   <p style="color:var(--muted)">اگر امروز از منابع آب درست نگهداری نکنیم، نسل‌های آینده با مشکلات بیشتری روبه‌رو خواهند شد. هر قطره آب ارزشمند است؛ اما راه‌حل بحران آب فقط صرفه‌جویی فردی نیست و به مدیریت علمی و برنامه‌ریزی درست هم نیاز دارد.</p>
  </div>
 </div>
</section>

<section class="section" id="quiz">
 <div class="container">
  <div class="section-head">
   <div class="kicker">07 / KNOWLEDGE TEST</div>
   <h2>چقدر از پرونده آب تهران یاد گرفتی؟</h2>
   <p>به پنج سؤال زیر جواب بده و نتیجه‌ات رو ببین.</p>
  </div>
  <div class="quiz">
   <h3>آزمون کوتاه آب تهران</h3>
   <form id="quizForm">
    <div class="question">
     <p>۱. دو گروه اصلی منابع آب تهران کدام‌اند؟</p>
     <label><input type="radio" name="q1" value="a"> آب شور و شیرین</label>
     <label><input type="radio" name="q1" value="b"> آب سطحی و زیرزمینی</label>
     <label><input type="radio" name="q1" value="c"> آب گرم و سرد</label>
    </div>
    <div class="question">
     <p>۲. کدام مورد یکی از سدهای تأمین‌کننده آب تهران است؟</p>
     <label><input type="radio" name="q2" value="a"> سد کرج (امیرکبیر)</label>
     <label><input type="radio" name="q2" value="b"> سد کارون ۳</label>
     <label><input type="radio" name="q2" value="c"> سد دز</label>
    </div>
    <div class="question">
     <p>۳. برداشت بی‌رویه از آب زیرزمینی می‌تواند چه پیامدی داشته باشد؟</p>
     <label><input type="radio" name="q3" value="a"> افزایش بارندگی</label>
     <label><input type="radio" name="q3" value="b"> فرونشست زمین</label>
     <label><input type="radio" name="q3" value="c"> تشکیل ابر</label>
    </div>
    <div class="question">
     <p>۴. کدام کار به جلوگیری از آلودگی آب کمک می‌کند؟</p>
     <label><input type="radio" name="q4" value="a"> ریختن روغن در فاضلاب</label>
     <label><input type="radio" name="q4" value="b"> رها کردن زباله در رودخانه</label>
     <label><input type="radio" name="q4" value="c"> تصفیه فاضلاب پیش از دفع</label>
    </div>
    <div class="question">
     <p>۵. استفاده مناسب از پساب تصفیه‌شده برای چیست؟</p>
     <label><input type="radio" name="q5" value="a"> برخی مصارف غیرآشامیدنی</label>
     <label><input type="radio" name="q5" value="b"> نوشیدن مستقیم بدون آزمایش</label>
     <label><input type="radio" name="q5" value="c"> جایگزینی کامل آب آشامیدنی</label>
    </div>
    <button type="button" onclick="checkQuiz()">بررسی پاسخ‌ها</button>
    <div id="quiz-result" aria-live="polite"></div>
   </form>
  </div>
 </div>
</section>

<section class="section alt" id="references">
 <div class="container">
  <div class="section-head">
   <div class="kicker">08 / REFERENCES</div>
   <h2>منابع و مطالعه بیشتر</h2>
   <p>برای تهیه این تحقیق از گزارش‌ها و منابع مرتبط با تأمین آب تهران و مسائل آب زیرزمینی استفاده شده است. آمارهای متغیر باید با تاریخ انتشارشان خوانده شوند.</p>
  </div>
  <div class="sources">
   <div class="source">
    <a href="https://www.tasnimnews.ir/fa/news/1405/08/16/3742130/" target="_blank" rel="noopener">گزارش وضعیت سدهای تهران - تسنیم ↗</a>
    <p>گزارش ۱۶ آبان ۱۴۰۵ درباره منابع سطحی و زیرزمینی و وضعیت سدهای پنج‌گانه تهران.</p>
   </div>
   <div class="source">
    <a href="https://www.tasnimnews.ir/fa/news/1403/05/13/3133008/" target="_blank" rel="noopener">گزارش فرونشست زمین در تهران - تسنیم ↗</a>
    <p>گزارشی درباره ارتباط برداشت بی‌رویه آب زیرزمینی با فرونشست زمین.</p>
   </div>
   <div class="source">
    <a href="https://environmentalhealth.ir/" target="_blank" rel="noopener">بهداشت محیط ایران ↗</a>
    <p>مطالب آموزشی درباره تصفیه آب و فرایندهای تصفیه‌خانه.</p>
   </div>
   <div class="source">
    <a href="https://www.tasnimnews.ir/" target="_blank" rel="noopener">خبرگزاری تسنیم ↗</a>
    <p>گزارش‌های خبری درباره مدیریت منابع آب و تأمین آب تهران.</p>
   </div>
  </div>
  <div class="warning">
   یادآوری: وضعیت ذخیره سدها، میزان بارش و سهم منابع مختلف در طول زمان تغییر می‌کند. اعداد یک گزارش خبری را نباید به‌عنوان آمار همیشگی یا مربوط به تمام مصارف استان تهران معرفی کرد.
  </div>
 </div>
</section>
</main>

<footer>
 <div class="container footer-inner">
  <div>
   <strong>AMIR SG</strong>
   <p>پرونده علمی آب تهران</p>
  </div>
  <div>
   <strong>تهیه و طراحی: امیرحسین مواظب</strong>
   <p>پروژه علوم تجربی پایه هفتم</p>
  </div>
  <div><p>© 2026 AMIR SG — نسخه آموزشی</p></div>
 </div>
</footer>

<button class="back-top" onclick="window.scrollTo({top:0,behavior:'smooth'})" aria-label="بازگشت به بالا">↑</button>

<script>
function toggleMenu(){
 document.getElementById('navLinks').classList.toggle('show');
}
document.querySelectorAll('.nav-links a').forEach(link=>{
 link.addEventListener('click',()=>{
  document.getElementById('navLinks').classList.remove('show');
 });
});

const steps=[
 {
  title:'مرحله اول: بارش',
  text:'بخشی از بارش‌ها روی سطح زمین جاری می‌شود و به رودخانه‌ها و سدها می‌رسد. بخشی دیگر در زمین نفوذ می‌کند و ذخایر آب زیرزمینی را تغذیه می‌کند.'
 },
 {
  title:'مرحله دوم: ذخیره آب',
  text:'آب‌های سطحی در پشت سدها ذخیره می‌شوند. آب نفوذکرده در زمین نیز در لایه‌های آبدار زیرزمینی جمع می‌شود و می‌تواند از طریق چاه‌ها برداشت شود.'
 },
 {
  title:'مرحله سوم: تصفیه',
  text:'آب خام در تصفیه‌خانه مراحل مختلفی مانند جداسازی ذرات، ته‌نشینی، صاف‌سازی و گندزدایی را طی می‌کند. مراحل دقیق با توجه به کیفیت آب ورودی متفاوت است.'
 },
 {
  title:'مرحله چهارم: توزیع',
  text:'پس از بررسی کیفیت و تأیید استانداردهای لازم، آب از طریق مخازن و شبکه لوله‌کشی به محله‌ها و ساختمان‌ها منتقل می‌شود.'
 },
 {
  title:'مرحله پنجم: مصرف',
  text:'آب در خانه‌ها، مدرسه‌ها، مراکز درمانی و دیگر بخش‌های شهر استفاده می‌شود. پس از مصرف، فاضلاب باید جمع‌آوری و به‌درستی تصفیه شود.'
 }
];

function showStep(index){
 document.querySelectorAll('.flow-step').forEach((el,i)=>{
  el.classList.toggle('active',i===index);
 });
 document.getElementById('flowDetail').innerHTML=
  '<h3>'+steps[index].title+'</h3><p>'+steps[index].text+'</p>';
}

document.querySelectorAll('.acc-btn').forEach(btn=>{
 btn.addEventListener('click',()=>{
  btn.parentElement.classList.toggle('open');
 });
});

function checkQuiz(){
 const answers={q1:'b',q2:'a',q3:'b',q4:'c',q5:'a'};
 let score=0,answered=0;
 Object.keys(answers).forEach(key=>{
  const selected=document.querySelector('input[name="'+key+'"]:checked');
  if(selected){
   answered++;
   if(selected.value===answers[key]) score++;
  }
 });
 const result=document.getElementById('quiz-result');
 if(answered<5){
  result.textContent='هنوز به همه سؤال‌ها جواب ندادی! ('+answered+' از ۵)';
  return;
 }
 let message='';
 if(score===5) message='عالی! همه پاسخ‌ها درست بود.';
 else if(score>=3) message='آفرین! اطلاعات خوبی یاد گرفتی.';
 else message='یک بار دیگر مطالب سایت را مرور کن و دوباره امتحان بده.';
 result.textContent='نتیجه: '+score+' از ۵ — '+message;
}
</script>
</body>
</html>
