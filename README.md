<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Nihal Noushad — AI Engineer</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600;700&family=Playfair+Display:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root{
      --navy:#12153a;
      --accent:#6d49ff;
      --muted:#f4f4f6;
      --text:#222233;
      --soft:#e9e6f2;
      font-family: 'Montserrat', sans-serif;
    }
    *{box-sizing:border-box}
    body{margin:0;color:var(--text);background:#fff;scroll-behavior:smooth}
    a{color:inherit;text-decoration:none}

    /* Header */
    header{background:linear-gradient(180deg, rgba(18,21,58,0.85) 0%, rgba(18,21,58,0.6) 60%), url('hero-bg.jpg') center/cover no-repeat; color:#fff; padding:36px 20px}
    .nav{max-width:1100px;margin:0 auto;display:flex;justify-content:flex-end;gap:20px;align-items:center}
    .nav a{font-size:13px;letter-spacing:1px;opacity:0.95;cursor:pointer}

    /* Hero card */
    .hero-inner{max-width:1100px;margin:24px auto 0;display:flex;align-items:center;gap:30px}
    .photo{flex:0 0 320px;background:#eee;padding:12px;border-radius:2px}
    .photo img{width:100%;height:auto;display:block;border-radius:4px}
    .card{background:#fff;padding:28px 36px;flex:1;border-radius:2px;box-shadow:0 0 0 6px rgba(18,21,58,0.06)}
    .name{font-family:'Playfair Display', serif;font-size:28px;color:var(--navy);margin:0}
    .title{color:#6a6f88;margin-top:6px;font-size:14px}
    .contact{margin-top:16px;font-size:13px;color:#4b5166}
    .socials{margin-top:18px;background:var(--navy);color:#fff;padding:10px;text-align:center;border-radius:4px}
    .socials a{margin:0 8px;opacity:0.9;font-size:14px;color:#fff}

    /* Intro */
    .intro{background:var(--muted);padding:64px 20px;text-align:center}
    .intro h2{margin:0;font-weight:600;color:var(--navy)}
    .intro p{max-width:760px;margin:18px auto;color:#5b5e73;line-height:1.6}

    /* Sections */
    .section{max-width:1100px;margin:48px auto;padding:0 20px}
    h3.section-title{text-align:center;letter-spacing:4px;color:var(--navy);margin-bottom:28px}

    /* Timeline lists */
    .timeline{display:grid;grid-template-columns:1fr;gap:12px}
    .timeline-item{display:flex;gap:20px;padding:18px 0;border-bottom:1px solid #eee}
    .timeline-item .years{width:140px;color:#6a6f88;font-size:13px}
    .timeline-item .content{flex:1}
    .timeline-item .role{font-weight:600;color:var(--navy);margin-bottom:6px}
    .timeline-item p{margin:0;color:#5b5e73}

    /* Skills */
    .skills-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:22px;align-items:center}
    .skill-pill{background:rgba(255,255,255,0.06);border:1px solid rgba(255,255,255,0.04);padding:16px;text-align:center;border-radius:2px}
    .skills-section{background:linear-gradient(180deg, rgba(18,21,58,0.95), rgba(18,21,58,0.95));color:#fff;padding:48px 20px}
    .skills-grid .skill-pill{background:rgba(255,255,255,0.06);border:none}

    /* Expertise */
    .expertise{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
    .expertise .box{padding:18px;border:1px solid #eee}

    /* Contact footer */
    footer{background:#f9f5f4;padding:48px 20px}
    .contact-grid{max-width:1100px;margin:0 auto;display:flex;gap:30px;align-items:flex-start}
    .contact-info{flex:1}

    /* Responsive */
    @media(max-width:900px){
      .hero-inner{flex-direction:column;align-items:center}
      .photo{width:220px}
      .skills-grid{grid-template-columns:1fr}
      .expertise{grid-template-columns:1fr}
      .nav{justify-content:center}
      .contact-grid{flex-direction:column}
      .timeline-item{flex-direction:column}
      .timeline-item .years{width:auto}
    }

    /* small helpers */
    .muted{color:#6a6f88;font-size:13px}
  </style>
</head>
<body>
  <header>
    <nav class="nav">
      <a href="#experience">Experience</a>
      <a href="#education">Education</a>
      <a href="#skills">Skills</a>
      <a href="#expertise">Expertise</a>
      <a href="#contact">Contact</a>
    </nav>
    <div class="hero-inner">
      <div class="photo">
        <img src="https://d.imgvision.net/nihlnshd/WhatsApp_Image_2025-03-18_at_14.49.58_44b004c4.jpg" alt="Nihal Noushad AI Engineer" loading="lazy" width="320" height="320">



      </div>
      <div class="card">
        <h1 class="name">Nihal Noushad</h1>
        <div class="title">AI Engineer</div>
        <div class="contact">
          <div>📍 Calicut, Kerala</div>
          <div>📧 <a href="mailto:nihalnoushad3329@gmail.com">nihalnoushad3329@gmail.com</a></div>
          <div>📱 +91-9037040579</div>
        </div>
        <div class="socials">
          <a href="https://www.linkedin.com/in/nihal-noushad-509916281/" target="_blank">LinkedIn</a> • 
          <a href="https://github.com/nihalnoushad1" target="_blank">GitHub</a>
        </div>
      </div>
    </div>
  </header>

  <section class="intro">
    <h2>Hello — I'm Nihal</h2>
    <p>Aspiring AI and Machine Learning professional with a strong foundation in programming, data analysis, and algorithmic problem-solving. Currently pursuing a Bachelor of Computer Applications (BCA) with a specialization in AI & ML at Lovely Professional University. Proficient in Python, C, SQL, and Machine Learning concepts, with hands-on experience in building AI-driven applications. Strong analytical mindset, adaptability, and a passion for innovation in the tech industry. Seeking opportunities to apply my technical expertise and collaborative skills to real-world AI challenges.</p>
  </section>

  <section id="experience" class="section">
    <h3 class="section-title">EXPERIENCE</h3>
    <div class="timeline">
      <div class="timeline-item">
        <div class="years">2023 - Present</div>
        <div class="content">
          <div class="role">AI / ML Projects (Student & Personal)</div>
          <p>Worked on multiple projects including a Spam vs. Ham email classifier and industry-trend visualizations. Built end-to-end ML pipelines: data cleaning, feature engineering, model training, and evaluation.</p>
        </div>
      </div>

      <div class="timeline-item">
        <div class="years">2022 - 2023</div>
        <div class="content">
          <div class="role">Web Developer (Personal)</div>
          <p>Designed and developed an Online Clothing Store website using HTML, CSS, and JavaScript. Implemented responsive layouts and interactive UI components.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="education" class="section">
    <h3 class="section-title">EDUCATION</h3>
    <div class="timeline">
      <div class="timeline-item">
        <div class="years">2024 – 2027</div>
        <div class="content">
          <div class="role">Lovely Professional University — BCA (AI & ML)</div>
          <p>Pursuing Bachelor of Computer Applications with a specialization in AI & ML. Coursework: programming, data structures, machine learning, databases, and networking.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="skills" class="skills-section">
    <h3 class="section-title" style="color:#fff">SKILLS</h3>
    <div class="section" style="padding-top:6px;padding-bottom:6px;max-width:1100px;margin:0 auto;">
      <div class="skills-grid">
        <div class="skill-pill">Data Analysis — Pandas, NumPy, Matplotlib, Folium</div>
        <div class="skill-pill">Machine Learning — Supervised & Unsupervised</div>
        <div class="skill-pill">Object-Oriented Programming — C++</div>
        <div class="skill-pill">Front-End Development — HTML, CSS, JavaScript</div>
        <div class="skill-pill">Computer Networking</div>
        <div class="skill-pill">Problem-Solving & Critical Thinking</div>
      </div>
    </div>
  </section>

  <section id="expertise" class="section">
    <h3 class="section-title">EXPERTISE</h3>
    <div class="expertise">
      <div class="box">
        <h4 style="margin-top:0">AI & ML Development</h4>
        <p class="muted">Model building, preprocessing, evaluation, and deployment readiness.</p>
      </div>
      <div class="box">
        <h4 style="margin-top:0">Data Visualization</h4>
        <p class="muted">Creating clear, insightful visual analysis and dashboards.</p>
      </div>
      <div class="box">
        <h4 style="margin-top:0">Full-Stack Fundamentals</h4>
        <p class="muted">Front-end development and small-scale web applications.</p>
      </div>
    </div>
  </section>

  <section id="certs" class="section">
    <h3 class="section-title">CERTIFICATIONS & ACHIEVEMENTS</h3>
    <div class="timeline">
      <div class="timeline-item">
        <div class="years">Cisco</div>
        <div class="content"><div class="role">Basics in Networking — Cisco Networking Academy</div></div>
      </div>
      <div class="timeline-item">
        <div class="years">IBM</div>
        <div class="content"><div class="role">Make Your Own Chatbot — IBM Watson</div></div>
      </div>
      <div class="timeline-item">
        <div class="years">Google</div>
        <div class="content"><div class="role">Basics in Cybersecurity — Google Inc.</div></div>
      </div>
      <div class="timeline-item">
        <div class="years">Hackathons</div>
        <div class="content"><div class="role">AIESEC & GeeksforGeeks</div></div>
      </div>
    </div>
  </section>

  <footer id="contact">
    <div class="contact-grid">
      <div class="contact-info">
        <h3 class="section-title" style="margin-top:0">CONTACT ME</h3>
        <p><strong>Email:</strong> <a href="mailto:nihalnoushad3329@gmail.com">nihalnoushad3329@gmail.com</a></p>
        <p><strong>Phone:</strong> +91-9037040579</p>
        <p><strong>Location:</strong> Calicut, Kerala</p>
        <p><strong>Languages:</strong> English, Hindi, Malayalam</p>
      </div>
      <div style="flex:1">
        <h4 style="margin-top:0">Want to collaborate?</h4>
        <p class="muted">Feel free to reach out via email or phone. You can also connect with me on LinkedIn or check my projects on GitHub.</p>
      </div>
    </div>
    <div style="max-width:1100px;margin:28px auto 0;text-align:center;color:#8a8790;font-size:13px">© <span id="year"></span> Nihal Noushad — Built with HTML & CSS</div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
