<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ifra.dev | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@400;700;800&family=Instrument+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="bg" aria-hidden="true">
  <canvas id="net"></canvas>
</div>

<header>
  <nav class="wrap" aria-label="Main">
    <a class="logo" href="#home">ifra<span>.</span>dev</a>
    <button class="menu" id="menu" aria-label="Open menu" aria-expanded="false">☰</button>

    <ul class="links" id="links">
      <li><a href="#about">About</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#achievements">Achievements</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<main>
  <section class="hero" id="home">
    <div class="wrap">
      <h1>Hi, I'm<br><em>Ifra</em></h1>

      <p class="lead">
        Computer science student who builds <b>data tools</b>,
        <b>web apps</b> and the occasional
        <b>robot that follows a line</b>.
        Looking for a summer internship.
      </p>

      <div class="cta">
        <a class="btn primary" href="#projects">See my projects</a>
        <a class="btn" href="#contact">Get in touch</a>
      </div>
    </div>
  </section>

  <section id="about">
    <div class="wrap about">
      <div>
        <h2>About me</h2>

        <p>
          I'm a third-year B.Tech student who likes turning messy
          problems into small, useful programs. I started with
          Arduino kits at fourteen and haven't stopped tinkering since.
        </p>

        <p>
          I care about clear interfaces, readable code and tools
          that save people time. Outside class I mentor first-years
          in the coding club and sketch UI ideas on paper before
          opening an editor.
        </p>

        <p class="muted">
          Off screen: film photography, chess, and long walks with a podcast.
        </p>
      </div>

      <div class="facts">
        <div class="fact">
          <b data-count="9.1">0</b>
          CGPA so far
        </div>

        <div class="fact">
          <b data-count="12">0</b>
          projects shipped
        </div>

        <div class="fact">
          <b data-count="3">0</b>
          hackathon podiums
        </div>
      </div>
    </div>
  </section>

  <section id="education">
    <div class="wrap">
      <h2>Education</h2>

      <ol class="tl">
        <li>
          <time>2023 - 2027</time>
          <h3>B.Tech, Computer Science and Engineering</h3>
          <p>
            Northfield Institute of Technology. Focus on algorithms,
            databases and machine learning.
          </p>
        </li>

        <li>
          <time>2021 - 2023</time>
          <h3>Higher Secondary, Science stream</h3>
          <p>
            St. Anne's Senior School. 94% with Mathematics
            and Computer Science.
          </p>
        </li>

        <li>
          <time>2024</time>
          <h3>Machine Learning Specialization</h3>
          <p>
            Online certification covering supervised learning,
            neural networks and model evaluation.
          </p>
        </li>
      </ol>
    </div>
  </section>

  <section id="skills">
    <div class="wrap">
      <h2>Technical skills</h2>

      <div class="skills">
        <div class="panel">
          <h3>Languages</h3>

          <div class="bar">
            <div><span>Python</span><span>90%</span></div>
            <div class="track">
              <div class="fill" data-w="90"></div>
            </div>
          </div>

          <div class="bar">
            <div><span>JavaScript</span><span>85%</span></div>
            <div class="track">
              <div class="fill" data-w="85"></div>
            </div>
          </div>

          <div class="bar">
            <div><span>Java</span><span>75%</span></div>
            <div class="track">
              <div class="fill" data-w="75"></div>
            </div>
          </div>

          <div class="bar">
            <div><span>C / C++</span><span>70%</span></div>
            <div class="track">
              <div class="fill" data-w="70"></div>
            </div>
          </div>
        </div>

        <div class="panel">
          <h3>Frameworks and tools</h3>

          <div class="bar">
            <div><span>React</span><span>80%</span></div>
            <div class="track">
              <div class="fill" data-w="80"></div>
            </div>
          </div>

          <div class="bar">
            <div><span>Node.js</span><span>75%</span></div>
            <div class="track">
              <div class="fill" data-w="75"></div>
            </div>
          </div>

          <div class="bar">
            <div><span>SQL and MongoDB</span><span>78%</span></div>
            <div class="track">
              <div class="fill" data-w="78"></div>
            </div>
          </div>

          <div class="bar">
            <div><span>Git and Linux</span><span>82%</span></div>
            <div class="track">
              <div class="fill" data-w="82"></div>
            </div>
          </div>
        </div>

        <div class="panel">
          <h3>Also comfortable with</h3>

          <div class="tags">
            <span class="tag">scikit-learn</span>
            <span class="tag">Pandas</span>
            <span class="tag">TensorFlow</span>
            <span class="tag">Figma</span>
            <span class="tag">REST APIs</span>
            <span class="tag">Arduino</span>
            <span class="tag">Docker</span>
            <span class="tag">HTML and CSS</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="projects">
    <div class="wrap">
      <h2>Projects</h2>

      <div class="filters" id="filters"
           role="group" aria-label="Filter projects"></div>

      <div class="grid" id="grid"></div>

      <p class="empty" id="empty" hidden>
        No projects match this filter yet.
      </p>
    </div>
  </section>

  <section id="achievements">
    <div class="wrap">
      <h2>Achievements</h2>

      <div class="ach">
        <div class="panel">
          <span>🏆</span>
          <h3>Smart India Hackathon finalist</h3>
          <p>
            Built a crop-disease detector that reached the national
            grand finale.
          </p>
        </div>

        <div class="panel">
          <span>🎓</span>
          <h3>Dean's List, four semesters</h3>
          <p>
            Top 5% of the department on grades since first year.
          </p>
        </div>

        <div class="panel">
          <span>👩‍💻</span>
          <h3>Coding club mentor</h3>
          <p>
            Taught Python basics to 40+ first-year students.
          </p>
        </div>

        <div class="panel">
          <span>📄</span>
          <h3>Published student paper</h3>
          <p>
            Co-authored a short paper on lightweight image classifiers.
          </p>
        </div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="wrap contact">
      <div>
        <h2>Let's talk</h2>

        <p>
          Have an internship, a project or a question?
          Fill in the form and I'll reply within two days.
        </p>

        <p class="muted">ifra@example.com</p>
      </div>

      <form id="form" novalidate>
        <label for="name">
          Name *
          <input id="name" name="name" autocomplete="name" required>
          <span class="err" id="e-name"></span>
        </label>

        <label for="email">
          Email *
          <input id="email" name="email" type="email"
                 autocomplete="email" required>
          <span class="err" id="e-email"></span>
        </label>

        <label for="msg">
          Message *
          <textarea id="msg" name="msg" required></textarea>
          <span class="err" id="e-msg"></span>
        </label>

        <button class="btn primary" type="submit"
                style="justify-self:start">
          Send message
        </button>

        <div class="ok" id="ok" role="status">
          Message sent. Thanks for reaching out!
        </div>
      </form>
    </div>
  </section>
</main>

<footer>
  <div class="wrap">
    &copy; 2026 Ifra. Designed and built by hand.
  </div>
</footer>

<button class="totop" id="totop" aria-label="Back to top">↑</button>

<dialog id="dlg">
  <div class="dlg-body" id="dlgBody"></div>
</dialog>

<script src="script.js"></script>
</body>
</html>
:root {
  color-scheme: dark;
  --bg: #0c0a18;
  --surface: #16122b;
  --surface-2: #1f1a3d;
  --line: #2e2757;
  --text: #ece9f7;
  --muted: #a29cc4;
  --accent: #9d8cff;
  --warm: #ff9eb0;

  --display: "Bricolage Grotesque", "Trebuchet MS", system-ui, sans-serif;
  --body: "Instrument Sans", system-ui, -apple-system, "Segoe UI", sans-serif;

  box-sizing: border-box;
  padding-top: env(safe-area-inset-top, 0px);
  padding-bottom: env(safe-area-inset-bottom, 0px);
}

@media (prefers-color-scheme: dark) {
  :root:not([data-theme="light"]) {
    --bg: #0c0a18;
    --text: #ece9f7;
  }
}

:root[data-theme="dark"] {
  --bg: #0c0a18;
  --text: #ece9f7;
}

*,
*::before,
*::after {
  box-sizing: inherit;
}

html {
  scroll-behavior: smooth;
  scroll-padding-top: calc(72px + env(safe-area-inset-top, 0px));
}

body {
  margin: 0;
  background: var(--bg);
  color: var(--text);
  font: 400 1.05rem/1.65 var(--body);
  overflow-x: hidden;
}

body::before {
  content: "";
  position: fixed;
  inset: 0 0 auto;
  height: env(safe-area-inset-top, 0px);
  background: var(--bg);
  z-index: 60;
}

.bg {
  position: fixed;
  inset: 0;
  z-index: -1;
  overflow: hidden;
  background:
    radial-gradient(60vmax 60vmax at 85% -10%, #2b1f6b55, transparent 60%),
    radial-gradient(50vmax 50vmax at -10% 40%, #5a1d4a40, transparent 60%),
    radial-gradient(45vmax 45vmax at 70% 110%, #1d3a6b40, transparent 60%),
    var(--bg);
}

.bg::after {
  content: "";
  position: absolute;
  inset: 0;
  background-image:
    linear-gradient(var(--line) 1px, transparent 1px),
    linear-gradient(90deg, var(--line) 1px, transparent 1px);
  background-size: 64px 64px;
  opacity: 0.18;
  -webkit-mask-image: radial-gradient(ellipse at 50% 30%, #000, transparent 75%);
  mask-image: radial-gradient(ellipse at 50% 30%, #000, transparent 75%);
}

#net {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
}

a {
  color: inherit;
}

:focus-visible {
  outline: 2px solid var(--accent);
  outline-offset: 3px;
  border-radius: 6px;
}

.wrap {
  width: min(1080px, 100% - 2.5rem);
  margin-inline: auto;
}

section {
  padding: 5.5rem 0;
}

h1,
h2,
h3 {
  font-family: var(--display);
  line-height: 1.08;
  margin: 0;
}

h2 {
  font-size: clamp(1.9rem, 4.5vw, 2.8rem);
  font-weight: 700;
  margin-bottom: 2rem;
  letter-spacing: -0.02em;
}

h3 {
  font-size: 1.2rem;
  font-weight: 700;
}

p {
  margin: 0 0 1rem;
  max-width: 62ch;
}

.muted {
  color: var(--muted);
}

/* Navigation */

header {
  position: fixed;
  top: env(safe-area-inset-top, 0px);
  left: 0;
  right: 0;
  z-index: 50;
  background: #0c0a18cc;
  -webkit-backdrop-filter: blur(14px);
  backdrop-filter: blur(14px);
  border-bottom: 1px solid var(--line);
}

nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 64px;
}

.logo {
  font: 800 1.25rem var(--display);
  text-decoration: none;
  letter-spacing: -0.02em;
}

.logo span {
  color: var(--accent);
}

.links {
  display: flex;
  gap: 0.25rem;
  list-style: none;
  margin: 0;
  padding: 0;
}

.links a {
  display: block;
  padding: 0.45rem 0.8rem;
  border-radius: 999px;
  text-decoration: none;
  color: var(--muted);
  font-size: 0.95rem;
  font-weight: 500;
  transition: color 0.2s, background 0.2s;
}

.links a:hover,
.links a.on {
  color: var(--text);
  background: var(--surface-2);
}

.menu {
  display: none;
  background: none;
  border: 1px solid var(--line);
  color: var(--text);
  border-radius: 10px;
  width: 44px;
  height: 44px;
  font-size: 1.2rem;
  cursor: pointer;
}

@media (max-width: 760px) {
  .menu {
    display: block;
  }

  .links {
    position: absolute;
    top: 64px;
    left: 0;
    right: 0;
    flex-direction: column;
    background: var(--surface);
    padding: 0.75rem 1.25rem 1rem;
    border-bottom: 1px solid var(--line);
    display: none;
  }

  .links.open {
    display: flex;
  }
}

/* Hero */

.hero {
  min-height: 100svh;
  display: flex;
  align-items: center;
  padding: 7rem 0 4rem;
}

.hero h1 {
  font-size: clamp(3rem, 11vw, 7.5rem);
  font-weight: 800;
  letter-spacing: -0.045em;
  line-height: 0.95;
  animation: rise 0.9s cubic-bezier(0.2, 0.7, 0.2, 1) both;
}

.hero h1 em {
  font-style: normal;
  background: linear-gradient(100deg, var(--accent), var(--warm));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}

.hero .lead {
  font-size: clamp(1.1rem, 2.2vw, 1.4rem);
  margin: 1.75rem 0 2.25rem;
  color: var(--muted);
  animation: rise 0.9s 0.15s cubic-bezier(0.2, 0.7, 0.2, 1) both;
}

.hero .lead b {
  color: var(--text);
  font-weight: 500;
}

.cta {
  display: flex;
  gap: 0.8rem;
  flex-wrap: wrap;
  animation: rise 0.9s 0.3s cubic-bezier(0.2, 0.7, 0.2, 1) both;
}

@keyframes rise {
  from {
    opacity: 0;
    transform: translateY(22px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

.btn {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.85rem 1.5rem;
  border-radius: 999px;
  font: 600 1rem var(--body);
  text-decoration: none;
  cursor: pointer;
  border: 1px solid var(--line);
  background: transparent;
  color: var(--text);
  transition: transform 0.2s, background 0.2s, border-color 0.2s;
}

.btn:hover {
  transform: translateY(-2px);
  border-color: var(--accent);
}

.btn.primary {
  background: var(--accent);
  border-color: var(--accent);
  color: #14102b;
}

.btn.primary:hover {
  background: #b3a6ff;
}

/* About */

.about {
  display: grid;
  grid-template-columns: 1.4fr 1fr;
  gap: 3rem;
  align-items: start;
}

.facts {
  display: grid;
  gap: 0.9rem;
}

.fact {
  background: var(--surface);
  border: 1px solid var(--line);
  border-radius: 18px;
  padding: 1.1rem 1.3rem;
}

.fact b {
  display: block;
  font: 700 1.9rem var(--display);
  color: var(--warm);
}

@media (max-width: 760px) {
  .about {
    grid-template-columns: 1fr;
  }
}

/* Education timeline */

.tl {
  position: relative;
  margin: 0;
  padding: 0 0 0 1.6rem;
  list-style: none;
  border-left: 2px solid var(--line);
}

.tl li {
  position: relative;
  padding: 0 0 2rem 1rem;
}

.tl li::before {
  content: "";
  position: absolute;
  left: calc(-1.6rem - 7px);
  top: 0.45rem;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: var(--accent);
  box-shadow: 0 0 0 5px var(--bg), 0 0 14px var(--accent);
}

.tl time {
  color: var(--warm);
  font-weight: 600;
  font-size: 0.95rem;
}

.tl p {
  margin: 0.3rem 0 0;
  color: var(--muted);
}

/* Skills */

.skills {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.25rem;
}

.panel {
  background: var(--surface);
  border: 1px solid var(--line);
  border-radius: 20px;
  padding: 1.5rem;
}

.panel h3 {
  margin-bottom: 1.1rem;
}

.bar {
  margin-bottom: 0.95rem;
}

.bar > div:first-child {
  display: flex;
  justify-content: space-between;
  font-size: 0.95rem;
  margin-bottom: 0.35rem;
}

.track {
  height: 8px;
  background: var(--surface-2);
  border-radius: 99px;
  overflow: hidden;
}

.fill {
  height: 100%;
  width: 0;
  border-radius: 99px;
  background: linear-gradient(90deg, var(--accent), var(--warm));
  transition: width 1.2s cubic-bezier(0.2, 0.7, 0.2, 1);
}

.tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.tag {
  padding: 0.3rem 0.8rem;
  border-radius: 99px;
  background: var(--surface-2);
  border: 1px solid var(--line);
  font-size: 0.88rem;
}

/* Projects */

.filters {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-bottom: 1.75rem;
}

.chip {
  padding: 0.5rem 1.1rem;
  border-radius: 99px;
  border: 1px solid var(--line);
  background: transparent;
  color: var(--muted);
  font: 500 0.95rem var(--body);
  cursor: pointer;
  transition: all 0.2s;
}

.chip:hover {
  color: var(--text);
  border-color: var(--accent);
}

.chip[aria-pressed="true"] {
  background: var(--accent);
  border-color: var(--accent);
  color: #14102b;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(290px, 1fr));
  gap: 1.25rem;
}

.card {
  text-align: left;
  font: inherit;
  color: inherit;
  background: var(--surface);
  border: 1px solid var(--line);
  border-radius: 20px;
  padding: 0;
  overflow: hidden;
  cursor: pointer;
  transition: transform 0.25s, border-color 0.25s;
}

.card:hover {
  transform: translateY(-4px);
  border-color: var(--accent);
}

.thumb {
  height: 140px;
  display: grid;
  place-items: center;
  font-size: 2.6rem;
}

.card .body {
  padding: 1.2rem 1.3rem 1.4rem;
}

.card p {
  color: var(--muted);
  font-size: 0.97rem;
  margin: 0.5rem 0 0.9rem;
}

.empty {
  color: var(--muted);
}

/* Project dialog */

dialog {
  border: 1px solid var(--line);
  background: var(--surface);
  color: var(--text);
  border-radius: 24px;
  padding: 0;
  width: min(560px, calc(100% - 2rem));
  max-height: 88svh;
  overflow: auto;
}

dialog::backdrop {
  background: #05030fcc;
  -webkit-backdrop-filter: blur(4px);
  backdrop-filter: blur(4px);
}

dialog[open] {
  animation: pop 0.25s ease both;
}

@keyframes pop {
  from {
    opacity: 0;
    transform: scale(0.96);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

.dlg-body {
  padding: 1.75rem;
}

.dlg-body ul {
  padding-left: 1.2rem;
  color: var(--muted);
}

.dlg-actions {
  display: flex;
  gap: 0.7rem;
  flex-wrap: wrap;
  margin-top: 1.4rem;
}

/* Achievements */

.ach {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.25rem;
}

.ach .panel span {
  font-size: 1.8rem;
}

.ach .panel p {
  color: var(--muted);
  margin: 0.4rem 0 0;
  font-size: 0.97rem;
}

/* Contact */

.contact {
  display: grid;
  grid-template-columns: 1fr 1.2fr;
  gap: 3rem;
}

@media (max-width: 760px) {
  .contact {
    grid-template-columns: 1fr;
  }
}

form {
  display: grid;
  gap: 1.1rem;
}

label {
  display: grid;
  gap: 0.4rem;
  font-weight: 500;
  font-size: 0.95rem;
}

input,
textarea {
  font: inherit;
  color: var(--text);
  background: var(--surface);
  border: 1px solid var(--line);
  border-radius: 14px;
  padding: 0.85rem 1rem;
  width: 100%;
  transition: border-color 0.2s;
}

input:focus,
textarea:focus {
  outline: none;
  border-color: var(--accent);
  box-shadow: 0 0 0 3px #9d8cff33;
}

textarea {
  min-height: 140px;
  resize: vertical;
}

.err {
  color: #ff9aa8;
  font-size: 0.87rem;
  min-height: 1.1em;
  font-weight: 400;
}

[aria-invalid="true"] {
  border-color: #ff7b8f;
}

.ok {
  display: none;
  padding: 1rem 1.2rem;
  border-radius: 14px;
  background: #1d3b33;
  border: 1px solid #2f7a63;
  color: #bff3e0;
}

.ok.show {
  display: block;
}

/* Footer and back-to-top */

footer {
  padding: 2rem 0 3rem;
  border-top: 1px solid var(--line);
  color: var(--muted);
  font-size: 0.92rem;
}

.totop {
  position: fixed;
  right: 1rem;
  bottom: calc(1rem + env(safe-area-inset-bottom, 0px));
  width: 46px;
  height: 46px;
  border-radius: 50%;
  border: 1px solid var(--line);
  background: var(--surface);
  color: var(--text);
  cursor: pointer;
  opacity: 0;
  pointer-events: none;
  transition: opacity 0.25s;
  z-index: 40;
}

.totop.show {
  opacity: 1;
  pointer-events: auto;
}

/* Reduced motion accessibility */

@media (prefers-reduced-motion: reduce) {
  *,
  *::before,
  *::after {
    animation: none !important;
    transition: none !important;
    scroll-behavior: auto !important;
  }
}
/* Project data */

const projects = [
  {
    t: "CropScan",
    cat: "AI / ML",
    tech: ["Python", "TensorFlow"],
    e: "🌱",
    c: "#2b4a3f",
    d: "Detects leaf diseases from a phone photo.",
    more: [
      "Trained a CNN on 50,000 labelled leaf images",
      "Reached 93% accuracy on a held-out test set",
      "Runs offline on low-end Android phones"
    ],
    link: "#"
  },
  {
    t: "StudyBuddy",
    cat: "Web",
    tech: ["React", "Node.js", "MongoDB"],
    e: "📚",
    c: "#3b2f6b",
    d: "Shared study planner with timers and group goals.",
    more: [
      "Real-time group sessions with WebSockets",
      "Used by 120 students in my department",
      "Designed in Figma before coding"
    ],
    link: "#"
  },
  {
    t: "LineRunner",
    cat: "Hardware",
    tech: ["C / C++", "Arduino"],
    e: "🤖",
    c: "#5a2f45",
    d: "Line-following robot with PID steering.",
    more: [
      "Custom sensor array and 3D-printed chassis",
      "Tuned PID gains for smooth cornering",
      "Won the college robotics round"
    ],
    link: "#"
  },
  {
    t: "ExpenseLens",
    cat: "Data",
    tech: ["Python", "Pandas"],
    e: "📊",
    c: "#2f4666",
    d: "Turns bank CSVs into clear spending dashboards.",
    more: [
      "Sorts transactions into categories with simple rules",
      "Monthly trend and anomaly charts",
      "Exports a one-page PDF summary"
    ],
    link: "#"
  },
  {
    t: "Campus Connect",
    cat: "Web",
    tech: ["JavaScript", "Node.js"],
    e: "🎓",
    c: "#4a3b6b",
    d: "Event board where clubs post and students RSVP.",
    more: [
      "Role-based logins for clubs and students",
      "REST API with 14 endpoints",
      "Responsive layout tested on phones first"
    ],
    link: "#"
  },
  {
    t: "SentimentSense",
    cat: "AI / ML",
    tech: ["Python", "scikit-learn"],
    e: "💬",
    c: "#6b3a4f",
    d: "Classifies the mood of product reviews.",
    more: [
      "TF-IDF plus logistic regression baseline",
      "Compared against a small transformer",
      "Interactive demo with confidence scores"
    ],
    link: "#"
  }
];

/* Short selector helper */

const $ = selector => document.querySelector(selector);

const cats = ["All", ...new Set(projects.map(p => p.cat))];

const techs = [
  ...new Set(projects.flatMap(p => p.tech))
].sort();

let active = "All";

const fbox = $("#filters");
const grid = $("#grid");
const dlg = $("#dlg");

/* Create filter buttons */

[...cats, ...techs].forEach(filter => {
  const button = document.createElement("button");

  button.className = "chip";
  button.textContent = filter;

  button.setAttribute(
    "aria-pressed",
    String(filter === "All")
  );

  button.onclick = () => {
    active = filter;

    fbox.querySelectorAll(".chip").forEach(chip => {
      chip.setAttribute(
        "aria-pressed",
        String(chip === button)
      );
    });

    render();
  };

  fbox.appendChild(button);
});

/* Render project cards */

function render() {
  grid.innerHTML = "";

  let count = 0;

  projects.forEach((project, index) => {
    if (
      active !== "All" &&
      project.cat !== active &&
      !project.tech.includes(active)
    ) {
      return;
    }

    count++;

    const card = document.createElement("button");

    card.className = "card";
    card.type = "button";

    const thumb = document.createElement("div");
    thumb.className = "thumb";
    thumb.style.background =
      `linear-gradient(135deg, ${project.c}, #0c0a18)`;
    thumb.textContent = project.e;

    const body = document.createElement("div");
    body.className = "body";

    const title = document.createElement("h3");
    title.textContent = project.t;

    const description = document.createElement("p");
    description.textContent = project.d;

    const tags = document.createElement("div");
    tags.className = "tags";

    project.tech.forEach(technology => {
      const tag = document.createElement("span");

      tag.className = "tag";
      tag.textContent = technology;

      tags.appendChild(tag);
    });

    body.append(title, description, tags);
    card.append(thumb, body);

    card.addEventListener("click", () => {
      openDlg(index);
    });

    grid.appendChild(card);
  });

  $("#empty").hidden = count > 0;
}

/* Open project details */

function openDlg(index) {
  const project = projects[index];
  const body = $("#dlgBody");

  body.replaceChildren();

  const title = document.createElement("h3");
  title.style.fontSize = "1.6rem";
  title.style.marginBottom = "0.4rem";
  title.textContent = `${project.e} ${project.t}`;

  const category = document.createElement("p");
  category.className = "muted";
  category.textContent = project.cat;

  const description = document.createElement("p");
  description.textContent = project.d;

  const list = document.createElement("ul");

  project.more.forEach(detail => {
    const item = document.createElement("li");
    item.textContent = detail;
    list.appendChild(item);
  });

  const tags = document.createElement("div");
  tags.className = "tags";

  project.tech.forEach(technology => {
    const tag = document.createElement("span");
    tag.className = "tag";
    tag.textContent = technology;
    tags.appendChild(tag);
  });

  const actions = document.createElement("div");
  actions.className = "dlg-actions";

  const viewLink = document.createElement("a");
  viewLink.className = "btn primary";
  viewLink.href = project.link;
  viewLink.textContent = "View code";

  const closeButton = document.createElement("button");
  closeButton.className = "btn";
  closeButton.type = "button";
  closeButton.textContent = "Close";

  closeButton.addEventListener("click", () => {
    dlg.close();
  });

  actions.append(viewLink, closeButton);

  body.append(
    title,
    category,
    description,
    list,
    tags,
    actions
  );

  dlg.showModal();
}

/* Close dialog by clicking outside */

dlg.addEventListener("click", event => {
  if (event.target === dlg) {
    dlg.close();
  }
});

/* Initial project rendering */

render();

/* Mobile navigation */

const menu = $("#menu");
const links = $("#links");

menu.addEventListener("click", () => {
  const isOpen = links.classList.toggle("open");

  menu.setAttribute("aria-expanded", String(isOpen));

  menu.setAttribute(
    "aria-label",
    isOpen ? "Close menu" : "Open menu"
  );

  menu.textContent = isOpen ? "✕" : "☰";
});

links.addEventListener("click", event => {
  if (event.target.closest("a")) {
    links.classList.remove("open");

    menu.setAttribute("aria-expanded", "false");
    menu.setAttribute("aria-label", "Open menu");
    menu.textContent = "☰";
  }
});

/* Highlight the current navigation section */

const navLinks = [
  ...links.querySelectorAll("a")
];

if ("IntersectionObserver" in window) {
  const spy = new IntersectionObserver(
    entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          navLinks.forEach(link => {
            link.classList.toggle(
              "on",
              link.hash === `#${entry.target.id}`
            );
          });
        }
      });
    },
    {
      rootMargin: "-45% 0px -50% 0px"
    }
  );

  document
    .querySelectorAll("main section[id]")
    .forEach(section => spy.observe(section));
}

/* Back-to-top button */

const toTop = $("#totop");

window.addEventListener(
  "scroll",
  () => {
    toTop.classList.toggle("show", window.scrollY > 600);
  },
  { passive: true }
);

toTop.addEventListener("click", () => {
  window.scrollTo({
    top: 0,
    behavior: "smooth"
  });
});

/* Animate skill bars and counters */

const animatedElements = document.querySelectorAll(
  "[data-w], [data-count]"
);

function animateElement(element) {
  if (element.dataset.w) {
    element.style.width = `${element.dataset.w}%`;
  }

  if (element.dataset.count) {
    const end = Number(element.dataset.count);
    const decimals = end % 1 ? 1 : 0;
    const startTime = performance.now();
    const duration = 1200;

    function step(currentTime) {
      const progress = Math.min(
        (currentTime - startTime) / duration,
        1
      );

      const eased = 1 - Math.pow(1 - progress, 3);
      const value = end * eased;

      element.textContent = value.toFixed(decimals);

      if (progress < 1) {
        requestAnimationFrame(step);
      }
    }

    requestAnimationFrame(step);
  }
}

if ("IntersectionObserver" in window) {
  const seen = new IntersectionObserver(
    entries => {
      entries.forEach(entry => {
        if (!entry.isIntersecting) return;

        seen.unobserve(entry.target);
        animateElement(entry.target);
      });
    },
    { threshold: 0.4 }
  );

  animatedElements.forEach(element => {
    seen.observe(element);
  });
} else {
  animatedElements.forEach(animateElement);
}

/* Contact form validation */

const form = $("#form");

const rules = {
  name: value =>
    value.trim().length < 2
      ? "Enter your name (at least 2 characters)."
      : "",

  email: value =>
    !value.trim()
      ? "Enter your email address."
      : !/^[^\s@]+@[^\s@]+\.[^\s@]{2,}$/.test(value.trim())
        ? "That email doesn't look right. Try name@example.com."
        : "",

  msg: value =>
    value.trim().length < 10
      ? "Write a message of at least 10 characters."
      : ""
};

const fields = {
  name: $("#name"),
  email: $("#email"),
  msg: $("#msg")
};

function check(fieldName) {
  const field = fields[fieldName];
  const message = rules[fieldName](field.value);
  const error = $(`#e-${fieldName}`);

  error.textContent = message;

  field.setAttribute(
    "aria-invalid",
    String(Boolean(message))
  );

  return message === "";
}

/* Validate fields when the user leaves them */

Object.keys(fields).forEach(fieldName => {
  fields[fieldName].addEventListener("blur", () => {
    check(fieldName);
  });

  fields[fieldName].addEventListener("input", () => {
    if (fields[fieldName].getAttribute("aria-invalid") === "true") {
      check(fieldName);
    }
  });
});

/* Validate the form when submitted */

form.addEventListener("submit", event => {
  event.preventDefault();

  const invalidFields = Object.keys(fields).filter(
    fieldName => !check(fieldName)
  );

  if (invalidFields.length > 0) {
    fields[invalidFields[0]].focus();
    return;
  }

  /*
    This is a front-end demo.
    Connect a backend or form service to send real messages.
  */

  form.reset();

  Object.values(fields).forEach(field => {
    field.removeAttribute("aria-invalid");
  });

  Object.keys(fields).forEach(fieldName => {
    $(`#e-${fieldName}`).textContent = "";
  });

  const success = $("#ok");

  success.classList.add("show");

  setTimeout(() => {
    success.classList.remove("show");
  }, 6000);
});

/* Animated network background */

(function () {
  const canvas = $("#net");
  const context = canvas.getContext("2d");

  if (
    !context ||
    window.matchMedia("(prefers-reduced-motion: reduce)").matches
  ) {
    return;
  }

  let width;
  let height;
  let points = [];
  let animationId;

  const mouse = {
    x: -999,
    y: -999
  };

  function resizeCanvas() {
    const dpr = Math.min(window.devicePixelRatio || 1, 2);

    width = window.innerWidth;
    height = window.innerHeight;

    canvas.width = width * dpr;
    canvas.height = height * dpr;

    canvas.style.width = `${width}px`;
    canvas.style.height = `${height}px`;

    context.setTransform(dpr, 0, 0, dpr, 0, 0);

    points = Array.from(
      {
        length: Math.min(
          70,
          Math.floor((width * height) / 20000)
        )
      },
      () => ({
        x: Math.random() * width,
        y: Math.random() * height,
        vx: (Math.random() - 0.5) * 0.25,
        vy: (Math.random() - 0.5) * 0.25
      })
    );
  }

  function drawNetwork() {
    context.clearRect(0, 0, width, height);

    points.forEach((point, index) => {
      point.x += point.vx;
      point.y += point.vy;

      if (point.x < 0 || point.x > width) {
        point.vx *= -1;
      }

      if (point.y < 0 || point.y > height) {
        point.vy *= -1;
      }

      context.fillStyle = "#b9adff99";
      context.beginPath();
      context.arc(point.x, point.y, 1.6, 0, Math.PI * 2);
      context.fill();

      for (let j = index + 1; j < points.length; j++) {
        const other = points[j];

        const distance = Math.hypot(
          point.x - other.x,
          point.y - other.y
        );

        if (distance < 130) {
          context.strokeStyle =
            `rgba(157, 140, 255, ${0.22 * (1 - distance / 130)})`;

          context.beginPath();
          context.moveTo(point.x, point.y);
          context.lineTo(other.x, other.y);
          context.stroke();
        }
      }

      const mouseDistance = Math.hypot(
        point.x - mouse.x,
        point.y - mouse.y
      );

      if (mouseDistance < 170) {
        context.strokeStyle =
          `rgba(255, 158, 176, ${0.5 * (1 - mouseDistance / 170)})`;

        context.beginPath();
        context.moveTo(point.x, point.y);
        context.lineTo(mouse.x, mouse.y);
        context.stroke();
      }
    });

    animationId = requestAnimationFrame(drawNetwork);
  }

  window.addEventListener("resize", resizeCanvas);

  window.addEventListener(
    "pointermove",
    event => {
      mouse.x = event.clientX;
      mouse.y = event.clientY;
    },
    { passive: true }
  );

  window.addEventListener("pointerleave", () => {
    mouse.x = -999;
    mouse.y = -999;
  });

  document.addEventListener("visibilitychange", () => {
    if (document.hidden) {
      cancelAnimationFrame(animationId);
    } else {
      animationId = requestAnimationFrame(drawNetwork);
    }
  });

  resizeCanvas();
  drawNetwork();
})();
