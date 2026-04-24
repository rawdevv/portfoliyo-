# portfoliyo-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Devashish Rawat | Portfolio</title>
  <meta name="description" content="Portfolio website of Devashish Rawat, an Electronics and Communication Engineering student skilled in embedded systems, cloud, AI/ML, UI/UX, and programming." />
  <meta property="og:title" content="Devashish Rawat | Portfolio" />
  <meta property="og:description" content="ECE student portfolio featuring embedded systems, cloud, AI/ML, UI/UX, and development skills." />
  <meta property="og:type" content="website" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Manrope:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css">
  <link rel="stylesheet" href="./style.css" />
  <script defer src="./script.js"></script>
</head>
<body>
  <a class="skip-link" href="#main">Skip to content</a>

  <header class="site-header" id="top">
    <div class="container nav-wrap">
      <a href="#hero" class="brand" aria-label="Devashish Rawat home">
        <span class="brand-mark" aria-hidden="true">
          <svg viewBox="0 0 64 64" role="img" aria-label="DR monogram logo">
            <rect x="8" y="8" width="48" height="48" rx="18" fill="currentColor" opacity="0.12"></rect>
            <path d="M21 43V21h10.6c8.7 0 14.4 4.3 14.4 11s-5.7 11-14.4 11H21Zm7.4-5.8h3c4.7 0 7.3-2.2 7.3-5.2s-2.6-5.2-7.3-5.2h-3v10.4Z" fill="currentColor"></path>
          </svg>
        </span>
        <span class="brand-text">Devashish</span>
      </a>

      <nav class="nav" aria-label="Primary navigation">
        <button class="theme-toggle" type="button" data-theme-toggle aria-label="Switch theme">
          <span class="theme-icon theme-icon-moon"><i class="ri-moon-clear-line"></i></span>
        </button>

        <button class="menu-toggle" type="button" aria-expanded="false" aria-controls="mobile-menu" aria-label="Open menu">
          <span></span><span></span><span></span>
        </button>

        <div class="nav-links" id="mobile-menu">
          <a href="#about">About</a>
          <a href="#skills">Skills</a>
          <a href="#highlights">Highlights</a>
          <a href="#contact">Contact</a>
          <a href="mailto:workwth@gmail.com" class="btn btn-primary nav-cta">Hire Me</a>
        </div>
      </nav>
    </div>
  </header>

  <main id="main">
    <section class="hero section" id="hero">
      <div class="container hero-grid">
        <div class="hero-copy reveal">
          <p class="eyebrow">Electronics & Communication Engineering Student</p>
          <h1>
            Hi, I’m <span class="accent-text">Devashish Rawat</span> —
            <span class="typing-line"><span id="typing-text"></span><span class="cursor" aria-hidden="true"></span></span>
          </h1>
          <p class="hero-text">
            I build across embedded systems, software, cloud, AI/ML, and design — combining engineering depth with modern product thinking.
          </p>
          <div class="hero-actions">
            <a href="#contact" class="btn btn-primary">Let’s Connect</a>
            <a href="#skills" class="btn btn-secondary">Explore Skills</a>
          </div>
          <ul class="hero-meta" role="list">
            <li><i class="ri-map-pin-line"></i> Faridabad, India</li>
            <li><i class="ri-mail-line"></i> workwth@gmail.com</li>
            <li><i class="ri-code-s-slash-line"></i> Currently enjoying coding</li>
          </ul>
        </div>

        <div class="hero-card reveal delay-1">
          <div class="glass-card profile-card">
            <div class="avatar-orb">
              <div class="avatar-inner">
                <i class="ri-cpu-line"></i>
              </div>
            </div>
            <div class="profile-content">
              <p class="mini-label">Modern Engineering Portfolio</p>
              <h2>Technical + Creative</h2>
              <p>
                Embedded systems, Python development, cloud platforms, UI/UX design, dashboards, and machine intelligence.
              </p>
            </div>
            <div class="stats-grid">
              <article>
                <strong>Embedded</strong>
                <span>Microcontrollers, Arduino, Raspberry Pi</span>
              </article>
              <article>
                <strong>Cloud</strong>
                <span>AWS, Azure, Google Cloud</span>
              </article>
              <article>
                <strong>Design</strong>
                <span>Figma, color theory, UI/UX</span>
              </article>
              <article>
                <strong>Data + AI</strong>
                <span>Power BI, Tableau, ML, AI</span>
              </article>
            </div>
          </div>
        </div>
      </div>
      <div class="hero-blur blur-one" aria-hidden="true"></div>
      <div class="hero-blur blur-two" aria-hidden="true"></div>
    </section>

    <section class="section" id="about">
      <div class="container split-layout">
        <div class="section-heading reveal">
          <p class="eyebrow">About Me</p>
          <h2>Engineering logic with creative execution.</h2>
        </div>
        <div class="about-panel reveal delay-1">
          <p>
            I am an Electronics and Communication Engineering student at Manav Rachna International Institute of Research and Studies, with strong interest in electronics engineering and communication engineering.
          </p>
          <p>
            My work sits at the intersection of hardware, software, cloud, and design, helping me build solutions that are both technically solid and visually thoughtful.
          </p>
          <div class="chips" aria-label="Core traits">
            <span>Leadership</span>
            <span>Time Management</span>
            <span>Problem Solving</span>
            <span>Version Control</span>
          </div>
        </div>
      </div>
    </section>

    <section class="section alt-section" id="skills">
      <div class="container">
        <div class="section-heading reveal">
          <p class="eyebrow">Skill Set</p>
          <h2>Built for modern product and engineering workflows.</h2>
        </div>
        <div class="skills-grid">
          <article class="skill-card reveal">
            <div class="skill-icon"><i class="ri-cpu-line"></i></div>
            <h3>Embedded Systems</h3>
            <p>Microcontrollers, microprocessors, Arduino, and Raspberry Pi with practical hands-on confidence.</p>
          </article>
          <article class="skill-card reveal delay-1">
            <div class="skill-icon"><i class="ri-code-box-line"></i></div>
            <h3>Programming</h3>
            <p>Python, C, and C++ for building efficient software and engineering-focused applications.</p>
          </article>
          <article class="skill-card reveal delay-2">
            <div class="skill-icon"><i class="ri-cloud-line"></i></div>
            <h3>Cloud Foundation</h3>
            <p>Working knowledge of Google Cloud, AWS, and Azure for scalable and modern workflows.</p>
          </article>
          <article class="skill-card reveal">
            <div class="skill-icon"><i class="ri-pencil-ruler-2-line"></i></div>
            <h3>UI/UX Design</h3>
            <p>Figma, color theory, and interface aesthetics with a user-first design mindset.</p>
          </article>
          <article class="skill-card reveal delay-1">
            <div class="skill-icon"><i class="ri-bar-chart-box-line"></i></div>
            <h3>Data Visualization</h3>
            <p>Tableau and Microsoft Power BI for translating raw information into clear visual stories.</p>
          </article>
          <article class="skill-card reveal delay-2">
            <div class="skill-icon"><i class="ri-brain-line"></i></div>
            <h3>AI & Machine Learning</h3>
            <p>Strong foundational understanding of machine learning and artificial intelligence concepts.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="section" id="highlights">
      <div class="container highlights-grid">
        <div class="highlight-intro reveal">
          <p class="eyebrow">Highlights</p>
          <h2>What I bring beyond technical skills.</h2>
        </div>
        <article class="feature-panel reveal delay-1">
          <i class="ri-team-line"></i>
          <h3>Leadership</h3>
          <p>I bring extraordinary leadership skills and enjoy working with responsibility, collaboration, and initiative.</p>
        </article>
        <article class="feature-panel reveal delay-2">
          <i class="ri-time-line"></i>
          <h3>Time Management</h3>
          <p>I manage priorities effectively and maintain consistency while balancing learning and technical execution.</p>
        </article>
        <article class="feature-panel reveal">
          <i class="ri-git-branch-line"></i>
          <h3>Git & GitHub</h3>
          <p>I use version control systems to organize code, collaborate smoothly, and maintain clean development practices.</p>
        </article>
      </div>
    </section>

    <section class="section cta-section" id="contact">
      <div class="container cta-card reveal">
        <div>
          <p class="eyebrow">Contact</p>
          <h2>Let’s build something meaningful together.</h2>
          <p>
            If you’d like to collaborate, discuss projects, or connect professionally, feel free to reach out anytime.
          </p>
        </div>
        <div class="cta-actions">
          <a href="mailto:workwth@gmail.com" class="btn btn-primary">Email Me</a>
          <a href="#hero" class="btn btn-secondary">Back to Top</a>
        </div>
      </div>
    </section>
  </main>
</body>
</html>
/* Art direction: soft modern portfolio with baby-pink luxury tone
   Palette: blush pink neutrals with rose accent
   Typography: Playfair Display + Manrope for elegant contrast
   Density: spacious and mobile-first */

:root,
[data-theme="light"] {
  --text-xs: clamp(0.75rem, 0.7rem + 0.25vw, 0.875rem);
  --text-sm: clamp(0.875rem, 0.8rem + 0.35vw, 1rem);
  --text-base: clamp(1rem, 0.95rem + 0.25vw, 1.125rem);
  --text-lg: clamp(1.125rem, 1rem + 0.75vw, 1.5rem);
  --text-xl: clamp(1.5rem, 1.2rem + 1.25vw, 2.25rem);
  --text-2xl: clamp(2.3rem, 1.4rem + 3vw, 4.75rem);
  --space-1: 0.25rem;
  --space-2: 0.5rem;
  --space-3: 0.75rem;
  --space-4: 1rem;
  --space-5: 1.25rem;
  --space-6: 1.5rem;
  --space-8: 2rem;
  --space-10: 2.5rem;
  --space-12: 3rem;
  --space-16: 4rem;
  --space-20: 5rem;
  --space-24: 6rem;
  --radius-sm: 0.5rem;
  --radius-md: 0.9rem;
  --radius-lg: 1.25rem;
  --radius-xl: 1.75rem;
  --radius-full: 9999px;
  --font-display: 'Playfair Display', Georgia, serif;
  --font-body: 'Manrope', Arial, sans-serif;
  --color-bg: #fff7fb;
  --color-surface: #fff1f7;
  --color-surface-2: #ffe7f1;
  --color-surface-offset: #ffdbe9;
  --color-surface-dynamic: #f6c9da;
  --color-border: rgba(103, 58, 79, 0.14);
  --color-divider: rgba(103, 58, 79, 0.09);
  --color-text: #3f2633;
  --color-text-muted: #7a5869;
  --color-text-faint: #a78898;
  --color-text-inverse: #fff8fb;
  --color-primary: #dc6f9d;
  --color-primary-hover: #c95b8c;
  --color-primary-active: #ad4674;
  --color-primary-highlight: rgba(220, 111, 157, 0.16);
  --shadow-sm: 0 8px 30px rgba(164, 99, 128, 0.10);
  --shadow-md: 0 18px 50px rgba(164, 99, 128, 0.15);
  --shadow-lg: 0 28px 80px rgba(164, 99, 128, 0.2);
  --content-wide: 1180px;
  --transition: 220ms cubic-bezier(0.16, 1, 0.3, 1);
}

[data-theme="dark"] {
  --color-bg: #1b1419;
  --color-surface: #241a21;
  --color-surface-2: #2b1f27;
  --color-surface-offset: #362430;
  --color-surface-dynamic: #4a3242;
  --color-border: rgba(255, 221, 236, 0.14);
  --color-divider: rgba(255, 221, 236, 0.1);
  --color-text: #ffe8f1;
  --color-text-muted: #ddb7c7;
  --color-text-faint: #aa8394;
  --color-text-inverse: #1f151b;
  --color-primary: #ff91bc;
  --color-primary-hover: #ffabd0;
  --color-primary-active: #ff72aa;
  --color-primary-highlight: rgba(255, 145, 188, 0.18);
  --shadow-sm: 0 10px 30px rgba(0, 0, 0, 0.25);
  --shadow-md: 0 18px 50px rgba(0, 0, 0, 0.32);
  --shadow-lg: 0 28px 80px rgba(0, 0, 0, 0.44);
}

@media (prefers-color-scheme: dark) {
  :root:not([data-theme]) {
    --color-bg: #1b1419;
    --color-surface: #241a21;
    --color-surface-2: #2b1f27;
    --color-surface-offset: #362430;
    --color-surface-dynamic: #4a3242;
    --color-border: rgba(255, 221, 236, 0.14);
    --color-divider: rgba(255, 221, 236, 0.1);
    --color-text: #ffe8f1;
    --color-text-muted: #ddb7c7;
    --color-text-faint: #aa8394;
    --color-text-inverse: #1f151b;
    --color-primary: #ff91bc;
    --color-primary-hover: #ffabd0;
    --color-primary-active: #ff72aa;
    --color-primary-highlight: rgba(255, 145, 188, 0.18);
  }
}

*, *::before, *::after { box-sizing: border-box; }
html {
  scroll-behavior: smooth;
  -webkit-text-size-adjust: none;
  text-size-adjust: none;
}
body {
  margin: 0;
  min-height: 100vh;
  font-family: var(--font-body);
  font-size: var(--text-base);
  line-height: 1.7;
  color: var(--color-text);
  background:
    radial-gradient(circle at top left, rgba(255, 187, 215, 0.45), transparent 28%),
    radial-gradient(circle at right 20% top 20%, rgba(255, 214, 230, 0.5), transparent 20%),
    var(--color-bg);
}
img, svg { display: block; max-width: 100%; }
a { color: inherit; text-decoration: none; }
button, input, textarea, select { font: inherit; }
button { cursor: pointer; border: none; background: none; }
h1, h2, h3 { font-family: var(--font-display); line-height: 1.08; margin: 0; }
p { margin: 0; color: var(--color-text-muted); }

.skip-link {
  position: absolute;
  left: var(--space-4);
  top: -3rem;
  background: var(--color-primary);
  color: var(--color-text-inverse);
  padding: var(--space-2) var(--space-4);
  border-radius: var(--radius-full);
  z-index: 999;
}
.skip-link:focus { top: var(--space-4); }

:focus-visible {
  outline: 2px solid var(--color-primary);
  outline-offset: 3px;
}

.container {
  width: min(calc(100% - 2rem), var(--content-wide));
  margin-inline: auto;
}

.section {
  padding: clamp(var(--space-16), 9vw, var(--space-24)) 0;
}

.site-header {
  position: sticky;
  top: 0;
  z-index: 50;
  backdrop-filter: blur(14px);
  background: rgba(255, 247, 251, 0.72);
  border-bottom: 1px solid var(--color-divider);
}
[data-theme="dark"] .site-header { background: rgba(27, 20, 25, 0.72); }

.nav-wrap {
  min-height: 5rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: var(--space-4);
}

.brand {
  display: inline-flex;
  align-items: center;
  gap: var(--space-3);
  font-weight: 800;
  letter-spacing: 0.02em;
}
.brand-mark {
  width: 2.75rem;
  height: 2.75rem;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  color: var(--color-primary);
}
.brand-text { font-size: var(--text-sm); color: var(--color-text); }

.nav {
  display: flex;
  align-items: center;
  gap: var(--space-3);
}

.nav-links {
  display: flex;
  align-items: center;
  gap: var(--space-4);
}

.nav-links a:not(.btn) {
  font-size: var(--text-sm);
  color: var(--color-text-muted);
}

.nav-links a:hover,
.nav-links a:focus-visible { color: var(--color-text); }

.menu-toggle,
.theme-toggle {
  width: 2.8rem;
  height: 2.8rem;
  border-radius: var(--radius-full);
  display: inline-flex;
  align-items: center;
  justify-content: center;
  border: 1px solid var(--color-border);
  background: color-mix(in srgb, var(--color-surface) 70%, transparent);
  color: var(--color-text);
  transition: transform var(--transition), background var(--transition), border-color var(--transition);
}
.menu-toggle:hover,
.theme-toggle:hover { transform: translateY(-2px); }

.menu-toggle { display: none; flex-direction: column; gap: 4px; }
.menu-toggle span {
  width: 18px;
  height: 2px;
  border-radius: 999px;
  background: currentColor;
  transition: transform var(--transition), opacity var(--transition);
}
.menu-toggle.is-active span:nth-child(1) { transform: translateY(6px) rotate(45deg); }
.menu-toggle.is-active span:nth-child(2) { opacity: 0; }
.menu-toggle.is-active span:nth-child(3) { transform: translateY(-6px) rotate(-45deg); }

.hero {
  position: relative;
  overflow: clip;
  padding-top: clamp(var(--space-16), 10vw, 8rem);
}
.hero-grid {
  display: grid;
  grid-template-columns: 1.05fr 0.95fr;
  gap: clamp(var(--space-8), 5vw, var(--space-16));
  align-items: center;
}
.eyebrow {
  display: inline-flex;
  align-items: center;
  gap: var(--space-2);
  margin-bottom: var(--space-4);
  padding: 0.45rem 0.9rem;
  border-radius: var(--radius-full);
  background: var(--color-primary-highlight);
  color: var(--color-primary-active);
  font-size: var(--text-xs);
  font-weight: 800;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}
.hero h1 {
  font-size: var(--text-2xl);
  max-width: 12ch;
  color: var(--color-text);
}
.accent-text {
  color: var(--color-primary-active);
}
.typing-line {
  display: block;
  margin-top: var(--space-2);
  min-height: 1.25em;
  color: var(--color-primary);
}
.cursor {
  display: inline-block;
  width: 2px;
  height: 1em;
  background: currentColor;
  margin-left: 0.15em;
  vertical-align: text-bottom;
  animation: blink 1s steps(1) infinite;
}
@keyframes blink { 50% { opacity: 0; } }

.hero-text {
  margin-top: var(--space-5);
  max-width: 58ch;
}
.hero-actions,
.cta-actions {
  display: flex;
  flex-wrap: wrap;
  gap: var(--space-3);
  margin-top: var(--space-6);
}
.hero-meta {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  gap: var(--space-4);
  padding: 0;
  margin: var(--space-6) 0 0;
  color: var(--color-text-muted);
  font-size: var(--text-sm);
}
.hero-meta li {
  display: inline-flex;
  align-items: center;
  gap: var(--space-2);
}
.hero-meta i,
.feature-panel i,
.skill-icon i {
  color: var(--color-primary);
}

.glass-card,
.skill-card,
.feature-panel,
.cta-card,
.about-panel {
  background: color-mix(in srgb, var(--color-surface) 86%, white 14%);
  border: 1px solid var(--color-border);
  box-shadow: var(--shadow-sm);
}
[data-theme="dark"] .glass-card,
[data-theme="dark"] .skill-card,
[data-theme="dark"] .feature-panel,
[data-theme="dark"] .cta-card,
[data-theme="dark"] .about-panel {
  background: color-mix(in srgb, var(--color-surface) 88%, transparent);
}

.profile-card {
  border-radius: var(--radius-xl);
  padding: clamp(var(--space-6), 4vw, var(--space-8));
  position: relative;
}
.avatar-orb {
  width: 6.2rem;
  aspect-ratio: 1;
  border-radius: 50%;
  display: grid;
  place-items: center;
  background: radial-gradient(circle at 30% 30%, #ffd2e5, var(--color-primary));
  box-shadow: var(--shadow-md);
  margin-bottom: var(--space-5);
}
.avatar-inner {
  width: 70%;
  height: 70%;
  display: grid;
  place-items: center;
  border-radius: 50%;
  background: rgba(255,255,255,0.18);
  backdrop-filter: blur(10px);
  color: white;
  font-size: 1.9rem;
}
.profile-content h2 { font-size: var(--text-xl); margin-bottom: var(--space-2); }
.mini-label {
  font-size: var(--text-xs);
  font-weight: 800;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  margin-bottom: var(--space-3);
  color: var(--color-primary-active);
}
.stats-grid {
  margin-top: var(--space-6);
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: var(--space-3);
}
.stats-grid article {
  padding: var(--space-4);
  border-radius: calc(var(--radius-lg) - 0.25rem);
  background: color-mix(in srgb, var(--color-surface-2) 76%, white 24%);
}
.stats-grid strong {
  display: block;
  margin-bottom: 0.25rem;
  color: var(--color-text);
  font-size: var(--text-sm);
}
.stats-grid span { color: var(--color-text-muted); font-size: var(--text-xs); }

.btn {
  min-height: 44px;
  padding: 0.95rem 1.3rem;
  border-radius: var(--radius-full);
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: var(--space-2);
  font-size: var(
const phrases = [
  'embedded systems enthusiast.',
  'a cloud-ready developer.',
  'an AI & ML learner.',
  'a UI/UX focused creator.',
  'a coding-driven engineer.'
];

const typingTarget = document.getElementById('typing-text');
let phraseIndex = 0;
let charIndex = 0;
let deleting = false;

function typeLoop() {
  if (!typingTarget) return;

  const current = phrases[phraseIndex];
  typingTarget.textContent = deleting
    ? current.slice(0, charIndex--)
    : current.slice(0, charIndex++);

  let delay = deleting ? 45 : 85;

  if (!deleting && charIndex > current.length) {
    deleting = true;
    delay = 1400;
  } else if (deleting && charIndex < 0) {
    deleting = false;
    phraseIndex = (phraseIndex + 1) % phrases.length;
    charIndex = 0;
    delay = 350;
  }

  window.setTimeout(typeLoop, delay);
}

typeLoop();

const menuToggle = document.querySelector('.menu-toggle');
const navLinks = document.querySelector('.nav-links');
const navAnchors = document.querySelectorAll('.nav-links a');

if (menuToggle && navLinks) {
  menuToggle.addEventListener('click', () => {
    const isOpen = navLinks.classList.toggle('is-open');
    menuToggle.classList.toggle('is-active', isOpen);
    menuToggle.setAttribute('aria-expanded', String(isOpen));
    menuToggle.setAttribute('aria-label', isOpen ? 'Close menu' : 'Open menu');
  });

  navAnchors.forEach((link) => {
    link.addEventListener('click', () => {
      navLinks.classList.remove('is-open');
      menuToggle.classList.remove('is-active');
      menuToggle.setAttribute('aria-expanded', 'false');
      menuToggle.setAttribute('aria-label', 'Open menu');
    });
  });
}

const themeToggle = document.querySelector('[data-theme-toggle]');
const root = document.documentElement;
let currentTheme = window.matchMedia('(prefers-color-scheme: dark)').matches ? 'dark' : 'light';

function updateThemeIcon(theme) {
  if (!themeToggle) return;
  themeToggle.innerHTML = theme === 'dark'
    ? '<span class="theme-icon"><i class="ri-sun-line"></i></span>'
    : '<span class="theme-icon"><i class="ri-moon-clear-line"></i></span>';
  themeToggle.setAttribute('aria-label', `Switch to ${theme === 'dark' ? 'light' : 'dark'} mode`);
}

root.setAttribute('data-theme', currentTheme);
updateThemeIcon(currentTheme);

if (themeToggle) {
  themeToggle.addEventListener('click', () => {
    currentTheme = currentTheme === 'dark' ? 'light' : 'dark';
    root.setAttribute('data-theme', currentTheme);
    updateThemeIcon(currentTheme);
  });
}

const revealElements = document.querySelectorAll('.reveal');
const reducedMotion = window.matchMedia('(prefers-reduced-motion: reduce)').matches;

if (reducedMotion) {
  revealElements.forEach((el) => el.classList.add('is-visible'));
} else {
  const revealObserver = new IntersectionObserver((entries) => {
    entries.forEach((entry) => {
      if (entry.isIntersecting) {
        entry.target.classList.add('is-visible');
        revealObserver.unobserve(entry.target);
      }
    });
  }, { threshold: 0.16 });

  revealElements.forEach((el) => revealObserver.observe(el));
}
