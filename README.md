![headshot](https://github.com/user-attachments/assets/992eca99-2839-43f8-bee0-228b11ec53e3)
[index.html](https://github.com/user-attachments/files/23833703/index.html)<!DOCTYPE html>
<html lang="en">![webcertificate](https://github.com/user-attachments/assets/d317fecb-38f2-4b86-85bc-dd6cf3169e74)

<head>
  <meta charset="UTF-8">![leadercertificate](https://github.com/user-attach/* ---------------- ROOT VARIABLES ---------------- */
:root {
  --text-color: #1a1c20;
  --link-color: #4a76ee;
  --background-color: #eeeff1;
}

/* ---------------- GLOBAL STYLES ---------------- */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  font-family: 'Poppins', sans-serif;
  background-color: var(--background-color);
  color: var(--text-color);
}

a {
  color: var(--link-color);
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* ---------------- NAVBAR ---------------- */
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 50px;
  height: 80px;
  background-color: transparent;
}

nav .left a {
  color: var(--text-color);
  font-size: 22px;
  font-weight: 600;
}

nav .right a {
  color: var(--text-color);
  margin: 0 10px;
  font-size: 18px;
  transition: color 0.3s ease;
}

nav .right a:hover {
  color: var(--link-color);
}

nav .right a:last-child {
  color: var(--text-color);
  background-color: transparent;
  padding: 0;
}

nav .right a span {
  margin-left: 5px;
  display: none;
}

/* ---------------- HERO SECTION ---------------- */
.hero-section {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 50px;
  margin: 50px 0 100px;
  gap: 40px;
}

.hero-section .text {
  flex: 5;
}

.hero-section .text h2 {
  font-size: 28px;
  font-weight: 600;
  color: var(--text-color);
  display: flex;
  align-items: center;
  gap: 8px;
}

.wave {
  font-size: 28px;
  animation: wave-hand 2s infinite;
}

@keyframes wave-hand {
  0% { transform: rotate(0deg); }
  15% { transform: rotate(14deg); }
  30% { transform: rotate(-8deg); }
  40% { transform: rotate(14deg); }
  50% { transform: rotate(-4deg); }
  60% { transform: rotate(10deg); }
  100% { transform: rotate(0deg); }
}

.hero-section .text .links {
  margin-top: 25px;
}

.hero-section .text .links a {
  display: inline-block;
  padding: 5px 10px;
  border: 2px solid var(--link-color);
  border-radius: 5px;
  margin-right: 10px;
  margin-bottom: 10px;
  transition: 0.2s;
}

.hero-section .text .links a:hover {
  color: var(--text-color);
  border: 2px solid var(--text-color);
}

.hero-section .headshot {
  flex: 2;
  display: flex;
  justify-content: right;
}

.hero-section .headshot img {
  width: 250px;
  border-radius: 50%;
}

/* ---------------- SKILLS SECTION ---------------- */
.skills-section {
  padding: 60px 20px;
  text-align: center;
}

.skills-section h2 {
  font-size: 32px;
  margin-bottom: 15px;
}

.skills-intro {
  margin-bottom: 30px;
  color: #131313;
  font-size: 16px;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
  gap: 20px;
  justify-content: center;
  align-items: center;
}

.skill-card {
  background: #f9f9f9;
  padding: 20px;
  border-radius: 16px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
  transition: transform 0.2s ease;
}

.skill-card:hover {
  transform: translateY(-5px);
}

.skill-card i {
  font-size: 36px;
  color: #333;
  margin-bottom: 10px;
}

.skill-card h3 {
  margin: 10px 0 5px;
  font-size: 18px;
}

.stars {
  color: #f1c40f;
  font-size: 16px;
}

/* ---------------- CERTIFICATES SECTION ---------------- */
.certificates-section {
  padding: 60px 20px;
  background-color: #ffffff;
  text-align: center;
}

.certificates-section h2 {
  font-size: 32px;
  margin-bottom: 40px;
  color: #333;
}

.cert-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  max-width: 1000px;
  margin: auto;
}

.certificate-card {
  background: #f9f9f9;
  border-radius: 12px;
  padding: 15px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
  transition: 0.3s ease;
  text-align: center;
}

.certificate-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
}

.certificate-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 10px;
}

/* ---------------- AWARDS & ACHIEVEMENTS SECTION ---------------- */
.awards-section {
  padding: 60px 20px;
  background-color: #f4f6fa;
  text-align: center;
}

.awards-section h2 {
  font-size: 32px;
  margin-bottom: 40px;
  color: #222;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px;
}

.awards-section h2 i {
  color: #f7b731;
  font-size: 28px;
}

.awards-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 25px;
  max-width: 1000px;
  margin: 0 auto;
}

.award-card {
  background-color: #ffffff;
  border-radius: 12px;
  padding: 25px 20px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  text-align: left;
}

.award-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 10px 18px rgba(0, 0, 0, 0.12);
}

.award-card i {
  font-size: 34px;
  color: #f7b731;
  margin-bottom: 12px;
}

.award-card h3 {
  font-size: 20px;
  margin-bottom: 8px;
  color: #222;
  font-weight: 600;
}

.award-card p {
  font-size: 15px;
  color: #555;
  line-height: 1.6;
}

/* ---------------- CONTACT SECTION ---------------- */
.contact-section {
  padding: 60px 20px;
  background-color: #f9f9f9;
  text-align: center;
}

.contact-section h2 {
  font-size: 32px;
  margin-bottom: 30px;
  color: #333;
}

.contact-info {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 15px;
}

.contact-item {
  font-size: 18px;
  color: #444;
  display: flex;
  align-items: center;
  gap: 10px;
}

.contact-item a {
  color: #4a76ee;
  text-decoration: none;
}

.contact-item a:hover {
  text-decoration: underline;
}

/* ---------------- FOOTER ---------------- */
footer {
  background: #1a1c20;
  color: #fff;
  text-align: center;
  padding: 20px;
  font-size: 14px;
}

/* ---------------- RESPONSIVE MEDIA QUERIES ---------------- */
@media (max-width: 850px) {
  .hero-section .text h2 {
    font-size: 35px;
  }
}

@media (max-width: 740px) {
  .hero-section {
    flex-direction: column-reverse;
    text-align: center;
  }

  .hero-section .headshot {
    justify-content: center;
  }

  .hero-section .text .links {
    justify-content: center;
  }
}

@media (max-width: 600px) {
  nav {
    padding: 0 20px;
  }

  .hero-section {
    padding: 0 20px;
  }

  .hero-section .text h2 {
    font-size: 30px;
  }

  .hero-section .headshot img {
    width: 200px;
  }

  .awards-section h2 {
    font-size: 26px;
  }

  .award-card {
    text-align: center;
  }

  .award-card i {
    font-size: 30px;
  }
}
[style.css](https://github.com/user-attachments/files/23833706/style.css)
ments/assets/2e7dd13e-677d-4481-82c7-eace08534757)

  <meta name="viewport" content="width=device-width, i![internshipcertificate](https://github.com/user-attachments/assets/ddd9dbfe-84f6-44b6-bf66-abb104e88f63)
nitial-scale=1.0">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
    integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" 
    crossorigin="anonymous" referrerpolicy="no-referrer" />
  <link rel="stylesheet" href="style.css">
  <title>Portfolio | Rahul Ganesh</title>
</head>

<body>
  <!-- NAVBAR -->
  <nav>
    <div class="left">
      <a href="/">Rahul Ganesh</a>
    </div>
    <div class="right">
      <a href="http://github.com" target="_blank" rel="noopener noreferrer">
        <i class="fa-brands fa-github"></i>
        <span>Github</span>
      </a>

      <a href="http://linkedin.com" target="_blank" rel="noopener noreferrer">
        <i class="fa-brands fa-linkedin"></i>
        <span>LinkedIn</span>
      </a>

      <a href="mailto:rahulganesherd@gmail.com">
        <i class="fa-solid fa-envelope"></i>
        <span>Email</span>
      </a>
    </div>
  </nav>

  <main>
    <!-- SECTION 1: Hero -->
    <section class="hero-section">
      <div class="text">
        <h2>Hi, I'm Rahulganesh <span class="wave">👋</span></h2>
        <p>
          I'm a final-year Computer Science student passionate about web development and modern technologies.
          I specialize in building responsive websites using HTML, CSS, JavaScript, React, and Node.js.
          I love turning ideas into real-world applications and aspire to grow in the tech industry.
        </p>

        <div class="links">
          <a href="#skills"><i class="fa-solid fa-code"></i><span>Skills</span></a>
          <a href="#certificates"><i class="fa-solid fa-certificate"></i><span>Certificates</span></a>
          <a href="#awards"><i class="fa-solid fa-trophy"></i><span>Achievements</span></a>
          <a href="#contact"><i class="fa-solid fa-envelope"></i><span>Contact</span></a>
        </div>
      </div>

      <div class="headshot">
        <img src="headshot.webp" alt="Rahul Ganesh headshot">
      </div>
    </section>

    <!-- SECTION 2: Skills -->
    <section id="skills" class="skills-section">
      <h2><i class="fa-solid fa-code"></i> Skills</h2>
      <p class="skills-intro">Technologies I work with and my comfort level</p>

      <div class="skills-grid">
        <div class="skill-card"><i class="fa-brands fa-html5"></i><h3>HTML</h3><div class="stars">★★★★★</div></div>
        <div class="skill-card"><i class="fa-brands fa-css3-alt"></i><h3>CSS</h3><div class="stars">★★★★★</div></div>
        <div class="skill-card"><i class="fa-brands fa-js"></i><h3>JavaScript</h3><div class="stars">★★★★☆</div></div>
        <div class="skill-card"><i class="fa-brands fa-node-js"></i><h3>Node.js</h3><div class="stars">★★★★☆</div></div>
        <div class="skill-card"><i class="fa-brands fa-react"></i><h3>React.js</h3><div class="stars">★★★★☆</div></div>
      </div>
    </section>

    <!-- SECTION 3: Certificates -->
    <section id="certificates" class="certificates-section">
      <h2><i class="fa-solid fa-certificate"></i> Certificates</h2>
      <div class="cert-grid">
        <div class="certificate-card">
          <img src="leadercertificate.webp" alt="Web Development Certificate">
          <h3>Web Development</h3>
          <p>Issued by PSG CAS</p>
          <p>March 2025</p>
        </div>

        <div class="certificate-card">
          <img src="webcertificate.webp" alt="Leadership Skill Certificate">
          <h3>Enhancement of Leadership Skill</h3>
          <p>Issued by PSG CAS</p>
          <p>Feb 2025</p>
        </div>

        <div class="certificate-card">
          <img src="internshipcertificate.webp" alt="Full Stack Internship Certificate">
          <h3>Certificate of Internship</h3>
          <p>Issued by Skypark ITech</p>
          <p>May 2025</p>
        </div>
      </div>
    </section>

    <!-- SECTION 4: Awards & Achievements -->
    <section id="awards" class="awards-section">
      <h2><i class="fa-solid fa-trophy"></i> Awards & Achievements</h2>
      <div class="awards-list">
        <div class="award-card">
          <i class="fa-solid fa-award"></i>
          <h3>Winner - Hackathon 2024</h3>
          <p>Secured 1st place in a national-level 24-hour coding event organized by TechFest.</p>
        </div>

        <div class="award-card">
          <i class="fa-solid fa-medal"></i>
          <h3>Best Project Award</h3>
          <p>Received the Best Project Award for developing a MERN stack job portal during college demo day.</p>
        </div>

        <div class="award-card">
          <i class="fa-solid fa-star"></i>
          <h3>Google Cloud Career Readiness Certificate</h3>
          <p>Completed Cloud Infrastructure training by Google and earned a Certificate of Excellence.</p>
        </div>
      </div>
    </section>

    <!-- SECTION 5: Contact -->
    <section id="contact" class="contact-section">
      <h2><i class="fa-solid fa-address-card"></i> Contact Me</h2>
      <div class="contact-info">
        <div class="contact-item"><i class="fa-solid fa-user"></i><span><strong>Name:</strong> Rahul Ganesh</span></div>
        <div class="contact-item"><i class="fa-solid fa-envelope"></i><span><strong>Email:</strong> <a href="mailto:rahulganesherd@gmail.com">rahulganesherd@gmail.com</a></span></div>
        <div class="contact-item"><i class="fa-brands fa-github"></i><span><strong>GitHub:</strong> <a href="https://github.com/yourgithubid" target="_blank">github.com/yourgithubid</a></span></div>
        <div class="contact-item"><i class="fa-brands fa-linkedin"></i><span><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/yourlinkedinid" target="_blank">linkedin.com/in/yourlinkedinid</a></span></div>
      </div>
    </section>
  </main>

  <footer>
    © 2025 Rahul Ganesh | All Rights Reserved
  </footer>
</body>
</html>

