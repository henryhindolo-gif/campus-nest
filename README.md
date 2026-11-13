# campus-nest
Student accommodation website project for finding affordable rooms in Freetown, Sierra Leone.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Find safe and affordable student accommodation in Freetown with Campus Nest.">
  <title>Campus Nest | Find Your Space</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Manrope:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
*{box-sizing:border-box} :root{--ink:#18251f;--muted:#68746d;--green:#1f674e;--green-dark:#174d3b;--mint:#eaf2ed;--cream:#f7f8f4;--line:#e4e9e4;--orange:#d98c55} html{scroll-behavior:smooth} body{margin:0;font-family:"DM Sans",sans-serif;color:var(--ink);background:#fff} a{color:inherit;text-decoration:none} button,input,select,textarea{font:inherit}.site-header{height:82px;padding:0 7.5%;display:flex;align-items:center;justify-content:space-between;background:#fff;position:sticky;top:0;z-index:20;border-bottom:1px solid #edf0ed}.brand{display:flex;align-items:center;gap:10px;font-family:Manrope,sans-serif;font-size:21px;font-weight:800;letter-spacing:-1px}.brand-mark{width:35px;height:35px;border-radius:11px;background:var(--green);color:#fff;display:grid;place-items:center;font-size:12px;letter-spacing:0}.brand-accent{color:var(--green)}.main-nav{display:flex;gap:34px;color:#56635c;font-size:13px;font-weight:600}.main-nav a{padding:10px 0}.main-nav a:hover,.main-nav a.active{color:var(--green)}.nav-cta{font-size:13px;font-weight:700;color:var(--green);border:1px solid #cddbd2;border-radius:7px;padding:12px 16px}.nav-cta span{padding-left:10px}.menu-toggle{display:none;border:0;background:none;font-size:25px;color:var(--green)}.hero{min-height:590px;background:url("https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=2000&q=90") center/cover;position:relative;display:flex;align-items:center;padding:70px 10%}.hero-overlay{position:absolute;inset:0;background:linear-gradient(90deg,rgba(12,31,23,.84),rgba(12,31,23,.45) 52%,rgba(12,31,23,.08))}.hero-content{position:relative;max-width:620px;color:#fff}.eyebrow{font-size:10px;letter-spacing:2px;font-weight:700;color:var(--green);display:block;margin-bottom:15px}.eyebrow.light{color:#c9dfd2}.hero h1,.about-copy h2{font:800 clamp(48px,6vw,76px)/1.08 Manrope,sans-serif;letter-spacing:-3.5px;margin:0 0 22px}.hero h1 em,.contact-intro h2 em{font-style:normal;color:#b9d8c5}.hero-content p{font-size:16px;line-height:1.8;color:#e2eae4;max-width:510px;margin:0 0 30px}.button{border:0;border-radius:6px;padding:14px 19px;display:inline-flex;align-items:center;justify-content:center;gap:25px;font-weight:700;font-size:13px;cursor:pointer;transition:.2s}.button:hover{transform:translateY(-2px)}.button-light{background:#fff;color:var(--green)}.button-primary{background:var(--green);color:#fff}.button-primary:hover{background:var(--green-dark)}.button span{font-size:18px}.hero-note{position:absolute;bottom:28px;right:8%;color:#fff;font-size:11px;display:flex;align-items:center;gap:9px}.pulse{width:7px;height:7px;border-radius:50%;background:#b8dfc7;box-shadow:0 0 0 5px #b8dfc733}.search-wrap{max-width:1160px;margin:-1px auto 0;padding:66px 28px 45px}.search-heading,.section-top{display:flex;justify-content:space-between;align-items:end;gap:20px}.search-heading h2,.section-top h2,.center-heading h2,.trust-copy h2,.contact-intro h2{font:800 clamp(27px,3vw,38px)/1.2 Manrope,sans-serif;letter-spacing:-1.5px;margin:0}.search-heading p,.section-subtitle,.center-heading p{color:var(--muted);font-size:13px;line-height:1.7}.search-panel{display:grid;grid-template-columns:1fr 1fr 1fr auto;gap:0;border:1px solid var(--line);border-radius:10px;margin-top:28px;padding:10px;box-shadow:0 10px 30px #15281d0a}.search-field{padding:10px 17px;border-right:1px solid var(--line);display:flex;flex-direction:column;gap:8px}.search-field span{font-size:9px;letter-spacing:1.2px;font-weight:700;color:#7b887f}.search-field select{border:0;outline:0;background:#fff;color:var(--ink);font-size:13px;font-weight:600;min-width:0}.search-button{align-self:stretch;margin-left:8px}.filter-row{display:flex;align-items:center;gap:22px;margin-top:20px;font-size:11px;color:var(--muted);flex-wrap:wrap}.filter-row>span{font-weight:700;color:var(--ink)}.check-filter{display:flex;align-items:center;gap:6px;cursor:pointer}.check-filter input{accent-color:var(--green)}.clear-filter{margin-left:auto;border:0;background:none;color:var(--green);font-size:11px;font-weight:700;cursor:pointer}.listings-section{background:var(--cream);padding:75px max(7.5%, calc((100% - 1160px)/2)) 85px}.section-top{margin-bottom:30px}.section-subtitle{margin-bottom:0}.result-count{font-size:11px;color:var(--muted);white-space:nowrap}.listing-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}.listing-card{background:#fff;border:1px solid #e9ede8;border-radius:9px;overflow:hidden;transition:.25s}.listing-card:hover{transform:translateY(-5px);box-shadow:0 14px 35px #162c1d12}.listing-photo{height:220px;position:relative;overflow:hidden}.listing-photo img{width:100%;height:100%;object-fit:cover;transition:.5s}.listing-card:hover .listing-photo img{transform:scale(1.04)}.photo-tag{position:absolute;top:14px;left:14px;background:#fff;padding:7px 10px;border-radius:4px;font-size:9px;font-weight:700;color:var(--green)}.listing-info{padding:18px 19px 20px}.listing-location{font-size:10px;color:var(--muted);margin-bottom:8px}.listing-info h3{font:700 17px Manrope,sans-serif;margin:0 0 9px}.listing-price{font:800 20px Manrope,sans-serif;color:var(--green)}.listing-price small{font:400 10px "DM Sans",sans-serif;color:var(--muted)}.listing-meta{display:flex;gap:12px;border-top:1px solid var(--line);padding-top:14px;margin-top:15px;color:var(--muted);font-size:10px}.listing-bottom{display:flex;justify-content:space-between;align-items:center;margin-top:17px}.facility-mini{font-size:10px;color:var(--muted)}.details-link{border:0;background:none;color:var(--green);font-size:11px;font-weight:700;cursor:pointer}.empty-state{text-align:center;padding:35px;color:var(--muted)}.trust-section{max-width:1160px;margin:auto;padding:100px 28px;display:grid;grid-template-columns:1.05fr .95fr;gap:85px;align-items:center}.trust-image{position:relative;height:460px}.trust-image img{width:100%;height:100%;object-fit:cover;border-radius:9px}.image-caption{position:absolute;bottom:20px;left:20px;background:#fff;padding:16px 20px;border-radius:6px;display:flex;flex-direction:column;gap:5px;box-shadow:0 8px 30px #0001}.image-caption strong{font:700 13px Manrope}.image-caption span{font-size:10px;color:var(--muted)}.trust-copy h2{max-width:470px;margin-bottom:18px}.trust-copy>p{font-size:13px;line-height:1.9;color:var(--muted);max-width:490px}.trust-points{display:grid;gap:19px;margin:27px 0}.trust-points>div{display:flex;gap:13px;align-items:center}.point-icon{width:34px;height:34px;background:var(--mint);color:var(--green);border-radius:50%;display:grid;place-items:center;font-weight:700}.trust-points strong,.trust-points small{display:block}.trust-points strong{font-size:12px;margin-bottom:4px}.trust-points small{font-size:10px;color:var(--muted)}.text-link{color:var(--green);font-size:12px;font-weight:700}.text-link span{padding-left:12px}.steps-section{background:var(--cream);padding:80px 7.5% 90px}.center-heading{text-align:center}.center-heading .eyebrow{margin-bottom:12px}.center-heading p{margin-top:12px}.steps-grid{max-width:1050px;margin:40px auto 0;display:grid;grid-template-columns:repeat(3,1fr);gap:20px}.step-card{background:#fff;border:1px solid var(--line);border-radius:8px;padding:28px;position:relative}.step-number{position:absolute;right:22px;top:20px;color:#b8c8bd;font:700 12px Manrope}.step-icon{width:44px;height:44px;border-radius:50%;background:var(--mint);color:var(--green);display:grid;place-items:center;font-size:22px;margin-bottom:22px}.step-card h3{font:700 17px Manrope;margin:0 0 8px}.step-card p{font-size:12px;line-height:1.8;color:var(--muted);margin:0}.about-section{display:grid;grid-template-columns:1fr 1fr;background:var(--green-dark);min-height:490px}.about-copy{padding:80px 12% 80px 16%;color:#fff}.about-copy h2{font-size:48px;letter-spacing:-2px}.about-copy p{font-size:12px;line-height:1.9;color:#d3e2d8;max-width:450px}.button-outline-light{border:1px solid #ffffff70;color:#fff;margin-top:15px}.about-photo{min-height:490px}.about-photo img{width:100%;height:100%;object-fit:cover}.safety-section{max-width:1050px;margin:65px auto;padding:25px 30px;display:flex;align-items:center;gap:25px;border:1px solid #e9e9dd;border-radius:8px;background:#fcfcf8}.safety-icon{width:50px;height:50px;flex:0 0 50px;border-radius:50%;background:#f3eadb;color:#a66c2f;display:grid;place-items:center;font-size:23px}.safety-section .eyebrow{margin-bottom:6px;color:#a66c2f}.safety-section h2{font:700 19px Manrope;margin:0 0 6px}.safety-section p{font-size:11px;line-height:1.7;color:var(--muted);margin:0}.contact-section{background:var(--cream);padding:85px max(7.5%, calc((100% - 1050px)/2));display:grid;grid-template-columns:1fr 1fr;gap:100px}.contact-intro h2{font-size:42px;margin-bottom:15px}.contact-intro h2 em{color:var(--green)}.contact-intro>p{font-size:12px;color:var(--muted);line-height:1.8;max-width:350px}.contact-detail{display:flex;align-items:center;gap:13px;margin-top:23px}.contact-detail>span{width:34px;height:34px;background:var(--mint);color:var(--green);display:grid;place-items:center;border-radius:50%}.contact-detail small,.contact-detail strong{display:block}.contact-detail small{font-size:9px;color:var(--muted);letter-spacing:1px;margin-bottom:4px}.contact-detail strong{font-size:11px}.contact-form{background:#fff;padding:27px;border:1px solid var(--line);border-radius:8px;display:grid;gap:15px}.contact-form label{font-size:11px;font-weight:700;display:grid;gap:8px}.contact-form input,.contact-form textarea{width:100%;border:1px solid var(--line);border-radius:5px;padding:12px;font-size:11px;outline-color:var(--green);resize:vertical}.contact-form .button{justify-self:start}.form-note{font-size:9px;color:var(--muted);margin:0}.site-footer{padding:35px 7.5%;display:flex;align-items:center;justify-content:space-between;gap:20px;flex-wrap:wrap}.footer-brand{font-size:17px}.footer-brand .brand-mark{width:30px;height:30px}.site-footer p,.site-footer small{font-size:10px;color:var(--muted)}.footer-links{display:flex;gap:20px;font-size:10px;color:var(--muted)}.modal-backdrop{position:fixed;inset:0;background:#0c1b14b8;z-index:50;display:none;align-items:center;justify-content:center;padding:20px}.modal-backdrop.open{display:flex}.room-modal{background:#fff;border-radius:10px;max-width:850px;width:100%;max-height:90vh;overflow:auto;position:relative;display:grid;grid-template-columns:1fr 1fr}.modal-close{position:absolute;right:12px;top:10px;z-index:2;width:34px;height:34px;border:0;border-radius:50%;background:#fff;font-size:24px;cursor:pointer}.modal-image{width:100%;height:100%;min-height:490px;object-fit:cover}.modal-content{padding:40px 30px}.verified-label{font-size:9px;color:var(--green);font-weight:700;background:var(--mint);padding:7px 9px;border-radius:4px}.modal-content h2{font:800 25px Manrope;margin:20px 0 8px}.modal-location,.modal-content>p{font-size:11px;line-height:1.8;color:var(--muted)}.modal-price{font:800 22px Manrope;color:var(--green)}.modal-content h3{font:700 13px Manrope;margin-top:24px}.modal-facilities{display:flex;gap:7px;flex-wrap:wrap}.modal-facilities span{background:var(--cream);padding:8px;border-radius:4px;font-size:10px}.modal-actions{display:flex;gap:8px;margin-top:25px;flex-wrap:wrap}.button-whatsapp{background:#e5f5e9;color:#167344}.modal-disclaimer{font-size:9px!important;margin-top:20px}.no-scroll{overflow:hidden}
@media(max-width:900px){.site-header{padding:0 5%}.main-nav{gap:17px}.hero{padding-left:7%}.search-wrap{padding-left:5%;padding-right:5%}.listings-section{padding-left:5%;padding-right:5%}.listing-grid{grid-template-columns:repeat(2,1fr)}.trust-section{gap:40px}.contact-section{gap:45px}.about-copy{padding-left:10%;padding-right:8%}}
@media(max-width:650px){.site-header{height:68px}.menu-toggle{display:block;margin-left:auto}.nav-cta{display:none}.main-nav{display:none;position:absolute;top:68px;left:0;right:0;background:#fff;padding:15px 7%;border-bottom:1px solid var(--line);flex-direction:column;gap:5px}.main-nav.open{display:flex}.main-nav a{padding:11px 0}.hero{min-height:570px;padding:65px 7%;background-position:58% center}.hero h1{font-size:53px}.hero-content p{font-size:14px}.hero-note{left:7%;right:auto}.search-wrap{padding-top:48px}.search-heading,.section-top{align-items:flex-start;flex-direction:column}.search-heading p{margin:5px 0 0}.search-panel{grid-template-columns:1fr;padding:10px}.search-field{border-right:0;border-bottom:1px solid var(--line);padding:13px}.search-button{margin:10px 0 0}.filter-row{gap:13px}.clear-filter{margin-left:0}.listings-section{padding-top:55px;padding-bottom:60px}.listing-grid{grid-template-columns:1fr}.listing-photo{height:235px}.trust-section{grid-template-columns:1fr;padding:65px 7%;gap:35px}.trust-image{height:330px}.trust-copy h2{font-size:31px}.steps-section{padding:60px 7%}.steps-grid{grid-template-columns:1fr}.about-section{grid-template-columns:1fr}.about-copy{padding:60px 7%}.about-copy h2{font-size:43px}.about-photo{min-height:300px;height:300px}.safety-section{margin:40px 6%;padding:20px;align-items:flex-start}.contact-section{grid-template-columns:1fr;padding:60px 7%;gap:30px}.contact-intro h2{font-size:36px}.site-footer{padding:30px 7%;justify-content:flex-start}.site-footer p{width:100%;order:2}.footer-links{width:100%;order:3;flex-wrap:wrap}.site-footer small{order:4}.room-modal{grid-template-columns:1fr;max-height:92vh}.modal-image{height:220px;min-height:220px}.modal-content{padding:25px}.modal-close{position:fixed;right:28px;top:28px}}

</style>
</head>
<body>
  <header class="site-header">
    <a class="brand" href="#home" aria-label="Campus Nest home">
      <span class="brand-mark">CN</span>
      <span>campus<span class="brand-accent">nest</span></span>
    </a>
    <button class="menu-toggle" id="menuToggle" aria-label="Open navigation" aria-expanded="false">☰</button>
    <nav class="main-nav" id="mainNav">
      <a class="active" href="#home">Home</a>
      <a href="#find-room">Find a Room</a>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
    <a class="nav-cta" href="#find-room">Explore rooms <span>↗️</span></a>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="hero-overlay"></div>
      <div class="hero-content">
        <span class="eyebrow light">YOUR NEXT CHAPTER STARTS HERE</span>
        <h1>Find a place<br>to <em>feel at home.</em></h1>
        <p>Discover student-friendly rooms around Freetown. Compare prices, explore facilities and connect directly with landlords.</p>
        <a class="button button-light" href="#find-room">Find your room <span>→</span></a>
      </div>
      <div class="hero-note"><span class="pulse"></span> Student accommodation made easier</div>
    </section>

    <section class="search-wrap" id="find-room">
      <div class="search-heading">
        <div>
          <span class="eyebrow">START YOUR SEARCH</span>
          <h2>Your space is out there.</h2>
        </div>
        <p>Search available rooms in areas around Freetown.</p>
      </div>
      <form class="search-panel" id="searchForm">
        <label class="search-field">
          <span>LOCATION</span>
          <select id="areaFilter">
            <option value="">All areas</option>
            <option value="Lumley">Lumley</option>
            <option value="Goderich">Goderich</option>
            <option value="Wilkinson Road">Wilkinson Road</option>
            <option value="Hill Station">Hill Station</option>
            <option value="Congo Cross">Congo Cross</option>
          </select>
        </label>
        <label class="search-field">
          <span>MAXIMUM MONTHLY BUDGET</span>
          <select id="budgetFilter">
            <option value="">Any budget</option>
            <option value="1000">Up to NLe 1,000</option>
            <option value="1500">Up to NLe 1,500</option>
            <option value="2000">Up to NLe 2,000</option>
            <option value="3000">Up to NLe 3,000</option>
          </select>
        </label>
        <label class="search-field">
          <span>ROOM TYPE</span>
          <select id="typeFilter">
            <option value="">Any room type</option>
            <option value="Single room">Single room</option>
            <option value="Shared room">Shared room</option>
            <option value="Apartment">Apartment</option>
          </select>
        </label>
        <button class="button button-primary search-button" type="submit">Search rooms <span>→</span></button>
      </form>

      <div class="filter-row">
        <span>Quick filters:</span>
        <label class="check-filter"><input type="checkbox" id="waterFilter"> Water</label>
        <label class="check-filter"><input type="checkbox" id="electricityFilter"> Electricity</label>
        <label class="check-filter"><input type="checkbox" id="securityFilter"> Security</label>
        <label class="check-filter"><input type="checkbox" id="wifiFilter"> Wi-Fi</label>
        <button class="clear-filter" id="clearFilters" type="button">Clear filters</button>
      </div>
    </section>

    <section class="listings-section">
      <div class="section-top">
        <div>
          <span class="eyebrow">HANDPICKED FOR STUDENTS</span>
          <h2>Rooms worth coming home to</h2>
          <p class="section-subtitle">Explore sample listings around Freetown. Contact the landlord to confirm availability.</p>
        </div>
        <span class="result-count" id="resultCount">6 rooms found</span>
      </div>
      <div class="listing-grid" id="listingGrid"></div>
      <p class="empty-state" id="emptyState" hidden>No rooms match those filters. Try changing your location or budget.</p>
    </section>

    <section class="trust-section">
      <div class="trust-image">
        <img src="https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=1100&q=85" alt="Bright and comfortable modern living space">
        <div class="image-caption"><strong>A better way to find a room.</strong><span>Less searching. More settling in.</span></div>
      </div>
      <div class="trust-copy">
        <span class="eyebrow">WHY CAMPUS NEST?</span>
        <h2>Finding a room should feel simple, not stressful.</h2>
        <p>Moving to a new city for school can be challenging. Campus Nest brings useful room information together so students can compare options before arranging a visit.</p>
        <div class="trust-points">
          <div><span class="point-icon">₦</span><div><strong>Clear prices</strong><small>Compare monthly prices before you visit.</small></div></div>
          <div><span class="point-icon">⌖</span><div><strong>Useful locations</strong><small>Explore areas and distance to campus.</small></div></div>
          <div><span class="point-icon">✓</span><div><strong>Safety information</strong><small>Check facilities and look for verified listings.</small></div></div>
        </div>
        <a class="text-link" href="#services">Learn how it works <span>→</span></a>
      </div>
    </section>

    <section class="steps-section" id="services">
      <div class="center-heading">
        <span class="eyebrow">HOW IT WORKS</span>
        <h2>Three steps to your next room</h2>
        <p>Spend less time searching and more time getting ready for campus.</p>
      </div>
      <div class="steps-grid">
        <article class="step-card"><span class="step-number">01</span><div class="step-icon">⌕</div><h3>Search</h3><p>Choose your preferred area, room type and monthly budget.</p></article>
        <article class="step-card"><span class="step-number">02</span><div class="step-icon">▤</div><h3>Compare</h3><p>Check photos, prices, facilities and the details of each room.</p></article>
        <article class="step-card"><span class="step-number">03</span><div class="step-icon">↗️</div><h3>Connect</h3><p>Call or WhatsApp the landlord to ask questions and arrange a visit.</p></article>
      </div>
    </section>

    <section class="about-section" id="about">
      <div class="about-copy">
        <span class="eyebrow light">A LITTLE ABOUT US</span>
        <h2>Made with students<br>in mind.</h2>
        <p>Campus Nest is a student accommodation website concept created to make it easier for students, especially those coming to Freetown from other towns, to find a place to stay.</p>
        <p>Our goal is to make room information easier to compare, with clear prices, real photos, facility details and direct landlord contact.</p>
        <a class="button button-outline-light" href="#contact">Get in touch <span>→</span></a>
      </div>
      <div class="about-photo">
        <img src="https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?auto=format&fit=crop&w=1000&q=85" alt="Warm and welcoming furnished room">
      </div>
    </section>

    <section class="safety-section">
      <div class="safety-icon">✳</div>
      <div><span class="eyebrow">A QUICK SAFETY REMINDER</span><h2>Always visit before you pay.</h2><p>Confirm the room, facilities, landlord details and rental terms in person. Never send a deposit to someone you have not properly verified. A website listing is not a guarantee.</p></div>
    </section>

    <section class="contact-section" id="contact">
      <div class="contact-intro">
        <span class="eyebrow">LET'S TALK</span>
        <h2>Have a question?<br><em>We're listening.</em></h2>
        <p>Students and landlords can get in touch with the Campus Nest team.</p>
        <div class="contact-detail"><span>✉</span><div><small>EMAIL</small><strong>hello@campusnest.example</strong></div></div>
        <div class="contact-detail"><span>☎</span><div><small>PHONE</small><strong>+232 00 000 000</strong></div></div>
      </div>
      <form class="contact-form" id="contactForm">
        <label>Your name<input type="text" id="contactName" placeholder="Enter your name" required></label>
        <label>Email address<input type="email" id="contactEmail" placeholder="you@example.com" required></label>
        <label>Your message<textarea id="contactMessage" rows="4" placeholder="How can we help?" required></textarea></label>
        <button class="button button-primary" type="submit">Send message <span>→</span></button>
        <p class="form-note" id="formNote">Demo form: messages are not sent to a server.</p>
      </form>
    </section>
  </main>

  <footer class="site-footer">
    <a class="brand footer-brand" href="#home"><span class="brand-mark">CN</span><span>campus<span class="brand-accent">nest</span></span></a>
    <p>Helping students find a place to call home in Freetown.</p>
    <div class="footer-links"><a href="#home">Home</a><a href="#find-room">Find a Room</a><a href="#about">About</a><a href="#contact">Contact</a></div>
    <small>©️ 2026 Campus Nest. Student web design project.</small>
  </footer>

  <div class="modal-backdrop" id="roomModal" aria-hidden="true">
    <div class="room-modal" role="dialog" aria-modal="true" aria-labelledby="modalTitle">
      <button class="modal-close" id="modalClose" aria-label="Close details">×</button>
      <img class="modal-image" id="modalImage" src="" alt="Room photograph">
      <div class="modal-content">
        <span class="verified-label" id="modalVerified">✓ Listing information</span>
        <h2 id="modalTitle"></h2>
        <p class="modal-location" id="modalLocation"></p>
        <strong class="modal-price" id="modalPrice"></strong>
        <p id="modalDescription"></p>
        <h3>Facilities</h3>
        <div class="modal-facilities" id="modalFacilities"></div>
        <div class="modal-actions"><a class="button button-primary" id="modalCall" href="#">Call landlord</a><a class="button button-whatsapp" id="modalWhatsApp" href="#" target="_blank" rel="noopener">WhatsApp</a></div>
        <p class="modal-disclaimer">Sample listing for this student project. Confirm all details directly before making any payment.</p>
      </div>
    </div>
  </div>
  <script>
const rooms = [
  {id:1,title:"Bright single room",area:"Lumley",type:"Single room",price:1250,distance:"1.2 km to campus",size:"1 bedroom",verified:true,image:"https://images.unsplash.com/photo-1611892440504-42a792e24d32?auto=format&fit=crop&w=900&q=85",facilities:["Water","Electricity","Security","Wi-Fi"],description:"A neat, bright room with a simple layout and space for studying. Ask the landlord about current availability and the rental agreement.",phone:"+232000000001"},
  {id:2,title:"Comfortable shared room",area:"Congo Cross",type:"Shared room",price:850,distance:"0.8 km to campus",size:"Shared",verified:false,image:"https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?auto=format&fit=crop&w=900&q=85",facilities:["Water","Electricity","Security"],description:"A furnished shared accommodation option in a convenient area. Confirm the number of occupants and shared facilities before arranging a visit.",phone:"+232000000002"},
  {id:3,title:"Modern student apartment",area:"Wilkinson Road",type:"Apartment",price:2800,distance:"2.1 km to campus",size:"1 bedroom",verified:true,image:"https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=900&q=85",facilities:["Water","Electricity","Security","Wi-Fi"],description:"A modern apartment-style space with a comfortable living area. Contact the landlord to confirm utility arrangements and the full monthly cost.",phone:"+232000000003"},
  {id:4,title:"Peaceful private room",area:"Goderich",type:"Single room",price:1500,distance:"3.0 km to campus",size:"1 bedroom",verified:false,image:"https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=900&q=85",facilities:["Water","Electricity","Wi-Fi"],description:"A calm room option in Goderich. Check transport options, water supply and security arrangements with the landlord before deciding.",phone:"+232000000004"},
  {id:5,title:"Simple budget room",area:"Hill Station",type:"Single room",price:950,distance:"2.6 km to campus",size:"1 bedroom",verified:true,image:"https://images.unsplash.com/photo-1615874694520-474822394e73?auto=format&fit=crop&w=900&q=85",facilities:["Water","Security"],description:"A simple room for students looking to manage their monthly budget. Ask about electricity, water availability and any additional charges.",phone:"+232000000005"},
  {id:6,title:"Spacious shared apartment",area:"Lumley",type:"Apartment",price:1900,distance:"1.7 km to campus",size:"2 bedrooms",verified:false,image:"https://images.unsplash.com/photo-1560185008-b033106af5c3?auto=format&fit=crop&w=900&q=85",facilities:["Water","Electricity","Security","Wi-Fi"],description:"A spacious apartment option that may suit students sharing accommodation. Confirm the rent per person and room-sharing arrangements.",phone:"+232000000006"}
];

const grid = document.getElementById("listingGrid");
const resultCount = document.getElementById("resultCount");
const emptyState = document.getElementById("emptyState");

function money(value){return "NLe "+value.toLocaleString("en-US");}
function renderRooms(items){
  grid.innerHTML = items.map(room => `
    <article class="listing-card">
      <div class="listing-photo">
        <img src="${room.image}" alt="${room.title}" loading="lazy">
        <span class="photo-tag">${room.verified ? "✓ VERIFIED CONCEPT" : room.type.toUpperCase()}</span>
      </div>
      <div class="listing-info">
        <div class="listing-location">⌖ ${room.area}, Freetown</div>
        <h3>${room.title}</h3>
        <div class="listing-price">${money(room.price)} <small>/ month</small></div>
        <div class="listing-meta"><span>⌖ ${room.distance}</span><span>▣ ${room.size}</span></div>
        <div class="listing-bottom"><span class="facility-mini">${room.facilities.slice(0,3).join(" · ")}</span><button class="details-link" data-room="${room.id}">View details →</button></div>
      </div>
    </article>`).join("");
  resultCount.textContent = `${items.length} ${items.length === 1 ? "room" : "rooms"} found`;
  emptyState.hidden = items.length !== 0;
}
function applyFilters(){
  const area = document.getElementById("areaFilter").value;
  const budget = Number(document.getElementById("budgetFilter").value || 0);
  const type = document.getElementById("typeFilter").value;
  const selectedFacilities = ["water","electricity","security","wifi"].filter(key => document.getElementById(key+"Filter").checked).map(key => key === "wifi" ? "Wi-Fi" : key[0].toUpperCase()+key.slice(1));
  const filtered = rooms.filter(room =>
    (!area || room.area === area) &&
    (!budget || room.price <= budget) &&
    (!type || room.type === type) &&
    selectedFacilities.every(facility => room.facilities.includes(facility))
  );
  renderRooms(filtered);
}
document.getElementById("searchForm").addEventListener("submit", event => {event.preventDefault();applyFilters();document.querySelector(".listings-section").scrollIntoView({behavior:"smooth"});});
["areaFilter","budgetFilter","typeFilter","waterFilter","electricityFilter","securityFilter","wifiFilter"].forEach(id => document.getElementById(id).addEventListener("change",applyFilters));
document.getElementById("clearFilters").addEventListener("click",()=>{
  ["areaFilter","budgetFilter","typeFilter"].forEach(id=>document.getElementById(id).value="");
  ["waterFilter","electricityFilter","securityFilter","wifiFilter"].forEach(id=>document.getElementById(id).checked=false);
  renderRooms(rooms);
});

const modal = document.getElementById("roomModal");
function openRoom(id){
  const room = rooms.find(item=>item.id===Number(id)); if(!room)return;
  document.getElementById("modalImage").src=room.image;
  document.getElementById("modalImage").alt=room.title;
  document.getElementById("modalTitle").textContent=room.title;
  document.getElementById("modalLocation").textContent=`⌖ ${room.area}, Freetown · ${room.distance}`;
  document.getElementById("modalPrice").textContent=`${money(room.price)} / month`;
  document.getElementById("modalDescription").textContent=room.description;
  document.getElementById("modalVerified").textContent=room.verified?"✓ Sample verified-style listing":"SAMPLE LISTING";
  document.getElementById("modalFacilities").innerHTML=room.facilities.map(item=>`<span>✓ ${item}</span>`).join("");
  document.getElementById("modalCall").href=`tel:${room.phone}`;
  document.getElementById("modalWhatsApp").href=`https://wa.me/${room.phone.replace(/\D/g,"")}?text=${encodeURIComponent("Hello, I saw your accommodation listing on Campus Nest. Is it still available?")}`;
  modal.classList.add("open");modal.setAttribute("aria-hidden","false");document.body.classList.add("no-scroll");
}
function closeModal(){modal.classList.remove("open");modal.setAttribute("aria-hidden","true");document.body.classList.remove("no-scroll");}
grid.addEventListener("click",event=>{const button=event.target.closest("[data-room]");if(button)openRoom(button.dataset.room);});
document.getElementById("modalClose").addEventListener("click",closeModal);
modal.addEventListener("click",event=>{if(event.target===modal)closeModal();});
document.addEventListener("keydown",event=>{if(event.key==="Escape")closeModal();});

const menuToggle=document.getElementById("menuToggle"),nav=document.getElementById("mainNav");
menuToggle.addEventListener("click",()=>{const open=nav.classList.toggle("open");menuToggle.setAttribute("aria-expanded",String(open));});
nav.querySelectorAll("a").forEach(link=>link.addEventListener("click",()=>{nav.classList.remove("open");menuToggle.setAttribute("aria-expanded","false");}));

document.getElementById("contactForm").addEventListener("submit",event=>{
  event.preventDefault();
  const name=document.getElementById("contactName").value.trim();
  document.getElementById("formNote").textContent=`Thank you, ${name}. This demo form is working, but it is not connected to an email server.`;
  event.target.reset();
});

renderRooms(rooms);

</script>
</body>
</html>