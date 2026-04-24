# portfoliyo-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Devashish Rawat | Portfolio</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"/>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet"/>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar">
    <div class="nav-container">
      <div class="logo">Devashish<span>.</span></div>
      <ul class="nav-links" id="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <div class="hamburger" id="hamburger">
        <i class="fas fa-bars"></i>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="hero-content">
      <h1>Hello, I'm <span class="highlight">Devashish Rawat</span></h1>
      <h2>
        <span id="typing-text"></span>
        <span class="cursor">|</span>
      </h2>
      <p>Electronics & Communication Engineering Student | Passionate Coder & Tech Enthusiast</p>
      <div class="hero-buttons">
        <a href="#projects" class="btn primary">View My Projects</a>
        <a href="#contact" class="btn secondary">Get In Touch</a>
      </div>
      <div class="social-links">
        <a href="https://github.com" target="_blank"><i class="fab fa-github"></i></a>
        <a href="https://linkedin.com" target="_blank"><i class="fab fa-linkedin"></i></a>
        <a href="mailto:workwth@gmail.com"><i class="fas fa-envelope"></i></a>
      </div>
    </div>
    <div class="hero-image">
      <div class="profile-circle">
        <!-- Replace with your photo URL or keep placeholder -->
        <img src="https://via.placeholder.com/400x400/ffe4f0/ffb6c1?text=DR" alt="Devashish Rawat"/>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="section">
    <div class="container">
      <h2 class="section-title">About Me</h2>
      <div class="about-content">
        <div class="about-text">
          <p>I'm a passionate Electronics and Communication Engineering student at <strong>Manav Rachna International Institute of Research and Studies</strong>, Faridabad. I love building innovative solutions at the intersection of hardware and software.</p>
          <p>Currently, I enjoy coding and exploring new technologies. My strong foundation in microcontrollers, cloud platforms, UI/UX design, and Machine Learning helps me create impactful projects.</p>
          <p><strong>Location:</strong> Faridabad, India</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="section skills-section">
    <div class="container">
      <h2 class="section-title">Skills & Expertise</h2>
      <div class="skills-grid">
        <div class="skill-card">
          <i class="fas fa-microchip"></i>
          <h3>Embedded Systems</h3>
          <p>Arduino, Raspberry Pi, Microcontrollers, Microprocessors</p>
        </div>
        <div class="skill-card">
          <i class="fas fa-code"></i>
          <h3>Programming</h3>
          <p>Python, C, C++</p>
        </div>
        <div class="skill-card">
          <i class="fas fa-cloud"></i>
          <h3>Cloud Technologies</h3>
          <p>AWS, Google Cloud, Azure</p>
        </div>
        <div class="skill-card">
          <i class="fas fa-brain"></i>
          <h3>AI & ML</h3>
          <p>Machine Learning, Artificial Intelligence</p>
        </div>
        <div class="skill-card">
          <i class="fas fa-palette"></i>
          <h3>UI/UX Design</h3>
          <p>Figma, Color Theory, Data Visualization (Tableau, Power BI)</p>
        </div>
        <div class="skill-card">
          <i class="fas fa-tools"></i>
          <h3>Tools & Others</h3>
          <p>Git & GitHub, Leadership, Time Management</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects Section (Placeholder - add your real projects) -->
  <section id="projects" class="section">
    <div class="container">
      <h2 class="section-title">Featured Projects</h2>
      <div class="projects-grid">
        <div class="project-card">
          <div class="project-img" style="background: linear-gradient(135deg, #ffe4f0, #ffb6c1);">
            <i class="fas fa-robot fa-3x"></i>
          </div>
          <h3>Smart IoT System</h3>
          <p>Arduino + Raspberry Pi based monitoring system with cloud integration.</p>
          <a href="#" class="project-link">View Project →</a>
        </div>
        <div class="project-card">
          <div class="project-img" style="background: linear-gradient(135deg, #ffe4f0, #ffb6c1);">
            <i class="fas fa-chart-bar fa-3x"></i>
          </div>
          <h3>ML Dashboard</h3>
          <p>Data visualization dashboard using Python, Tableau & Power BI.</p>
          <a href="#" class="project-link">View Project →</a>
        </div>
        <div class="project-card">
          <div class="project-img" style="background: linear-gradient(135deg, #ffe4f0, #ffb6c1);">
            <i class="fas fa-mobile-alt fa-3x"></i>
          </div>
          <h3>UI/UX Mobile App</h3>
          <p>Modern UI design in Figma for an electronics learning platform.</p>
          <a href="#" class="project-link">View Project →</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section contact-section">
    <div class="container">
      <h2 class="section-title">Let's Connect</h2>
      <div class="contact-content">
        <p>Have a project in mind or just want to chat about tech? Feel free to reach out!</p>
        <a href="mailto:workwth@gmail.com" class="btn primary email-btn">
          <i class="fas fa-envelope"></i> workwth@gmail.com
        </a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Devashish Rawat. Made with ❤️ and lots of code.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
:root {
  --pink: #ffb6c1;
  --light-pink: #ffe4f0;
  --dark-pink: #ff8da1;
  --text: #333;
  --bg: #fffaf5;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
  background: var(--bg);
  color: var(--text);
  line-height: 1.6;
  overflow-x: hidden;
}

.navbar {
  position: fixed;
  top: 0;
  width: 100%;
  background: rgba(255, 250, 245, 0.95);
  backdrop-filter: blur(10px);
  z-index: 1000;
  padding: 1rem 5%;
  box-shadow: 0 2px 15px rgba(255, 182, 193, 0.2);
}

.nav-container {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.8rem;
  font-weight: 700;
  color: var(--dark-pink);
}

.logo span {
  color: var(--pink);
}

.nav-links {
  display: flex;
  list-style: none;
  gap: 2.5rem;
}

.nav-links a {
  text-decoration: none;
  color: var(--text);
  font-weight: 500;
  transition: color 0.3s;
}

.nav-links a:hover {
  color: var(--dark-pink);
}

.hamburger {
  display: none;
  font-size: 1.8rem;
  color: var(--dark-pink);
  cursor: pointer;
}

/* Hero */
.hero {
  min-height: 100vh;
  display: flex;
  align-items: center;
  padding: 100px 5% 0;
  background: linear-gradient(135deg, #fffaf5 0%, #ffe4f0 100%);
  position: relative;
  overflow: hidden;
}

.hero-content {
  max-width: 600px;
  z-index: 2;
}

.hero h1 {
  font-size: 3.5rem;
  margin-bottom: 1rem;
}

.highlight {
  color: var(--dark-pink);
}

.hero h2 {
  font-size: 2.2rem;
  color: #555;
  margin-bottom: 1.5rem;
  min-height: 70px;
}

#typing-text {
  color: var(--dark-pink);
}

.cursor {
  animation: blink 0.7s infinite;
}

@keyframes blink {
  50% { opacity: 0; }
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 2rem;
  color: #666;
}

.btn {
  padding: 12px 28px;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s;
  display: inline-block;
  margin-right: 15px;
}

.primary {
  background: var(--dark-pink);
  color: white;
}

.primary:hover {
  background: #ff8da1;
  transform: translateY(-3px);
}

.secondary {
  background: transparent;
  color: var(--dark-pink);
  border: 2px solid var(--dark-pink);
}

.secondary:hover {
  background: var(--dark-pink);
  color: white;
}

.hero-image {
  position: absolute;
  right: 10%;
  top: 50%;
  transform: translateY(-40%);
}

.profile-circle {
  width: 320px;
  height: 320px;
  border-radius: 50%;
  overflow: hidden;
  border: 12px solid white;
  box-shadow: 0 20px 40px rgba(255, 182, 193, 0.4);
}

.profile-circle img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

/* Sections */
.section {
  padding: 100px 5%;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
}

.section-title {
  text-align: center;
  font-size: 2.8rem;
  margin-bottom: 3rem;
  color: var(--dark-pink);
}

.skills-grid, .projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
}

.skill-card, .project-card {
  background: white;
  padding: 2.5rem 2rem;
  border-radius: 20px;
  text-align: center;
  box-shadow: 0 10px 30px rgba(255, 182, 193, 0.15);
  transition: transform 0.3s;
}

.skill-card:hover, .project-card:hover {
  transform: translateY(-15px);
}

.skill-card i {
  font-size: 3rem;
  color: var(--dark-pink);
  margin-bottom: 1rem;
}

.project-img {
  height: 180px;
  border-radius: 16px;
  margin-bottom: 1.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
}

/* Contact */
.contact-section {
  background: linear-gradient(135deg, #ffe4f0, #fffaf5);
  text-align: center;
}

.email-btn {
  font-size: 1.3rem;
  padding: 18px 40px;
}

/* Footer */
footer {
  text-align: center;
  padding: 3rem;
  background: #333;
  color: #ddd;
  font-size: 0.95rem;
}

/* Mobile Responsive */
@media (max-width: 768px) {
  .hamburger {
    display: block;
  }

  .nav-links {
    position: fixed;
    top: 80px;
    left: -100%;
    width: 100%;
    height: calc(100vh - 80px);
    background: white;
    flex-direction: column;
    align-items: center;
    justify-content: start;
    padding-top: 4rem;
    transition: 0.4s ease;
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
  }

  .nav-links.active {
    left: 0;
  }

  .hero {
    flex-direction: column;
    text-align: center;
    padding-top: 140px;
  }

  .hero-image {
    position: relative;
    right: auto;
    top: auto;
    transform: none;
    margin-top: 3rem;
  }

  .profile-circle {
    width: 260px;
    height: 260px;
  }

  .hero h1 {
    font-size: 2.8rem;
  }
}
// Typing Animation
const texts = [
  "Electronics Engineer",
  "Embedded Systems Developer",
  "Cloud & AI Enthusiast",
  "UI/UX Designer"
];

let count = 0;
let index = 0;
let currentText = '';
let letter = '';

const typingText = document.getElementById('typing-text');

function type() {
  if (count === texts.length) count = 0;
  
  currentText = texts[count];
  
  letter = currentText.slice(0, ++index);
  
  typingText.textContent = letter;
  
  if (letter.length === currentText.length) {
    setTimeout(() => {
      count++;
      index = 0;
      setTimeout(type, 1500);
    }, 2000);
  } else {
    setTimeout(type, 80);
  }
}

// Hamburger Menu
const hamburger = document.getElementById('hamburger');
const navLinks = document.getElementById('nav-links');

hamburger.addEventListener('click', () => {
  navLinks.classList.toggle('active');
  
  // Change icon to X when active
  if (navLinks.classList.contains('active')) {
    hamburger.innerHTML = '<i class="fas fa-times"></i>';
  } else {
    hamburger.innerHTML = '<i class="fas fa-bars"></i>';
  }
});

// Close menu when clicking a link
document.querySelectorAll('.nav-links a').forEach(link => {
  link.addEventListener('click', () => {
    navLinks.classList.remove('active');
    hamburger.innerHTML = '<i class="fas fa-bars"></i>';
  });
});

// Start typing animation
window.onload = () => {
  type();
};
