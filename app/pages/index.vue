<template>
  <div class="cv-root">
    <!-- Ambient background blobs -->
    <div class="blob blob-1" />
    <div class="blob blob-2" />
    <div class="blob blob-3" />

    <main class="cv-container">

      <!-- ═══════════════ HERO ═══════════════ -->
      <section class="hero-section">
        <div class="hero-inner">
          <div class="hero-text">
            <p class="hero-label">Full-Stack Web Developer</p>
            <h1 class="hero-name">Fatkul Umar</h1>
            <p class="hero-tagline">
              Crafting performant web experiences with Laravel &amp; Nuxt.js since 2022.
            </p>
            <div class="hero-links">
              <a href="mailto:fatkulumar@gmail.com" class="chip chip-email">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/></svg>
                fatkulumar@gmail.com
              </a>
              <a href="https://github.com/fatkulumar" target="_blank" class="chip chip-github">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0 1 12 6.844a9.59 9.59 0 0 1 2.504.337c1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.02 10.02 0 0 0 22 12.017C22 6.484 17.522 2 12 2z"/></svg>
                github.com/fatkulumar
              </a>
              <a href="https://linkedin.com/in/fatkulumar" target="_blank" class="chip chip-linkedin">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6zM2 9h4v12H2z"/><circle cx="4" cy="4" r="2"/></svg>
                LinkedIn
              </a>
              <span class="chip chip-location">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0Z"/><circle cx="12" cy="10" r="3"/></svg>
                Ngawi, Jawa Timur
              </span>
            </div>
          </div>
        </div>
      </section>

      <!-- ═══════════════ GRID LAYOUT ═══════════════ -->
      <div class="content-grid">

        <!-- LEFT COLUMN -->
        <aside class="left-col">

          <!-- Summary -->
          <div class="card card-summary">
            <h2 class="section-title">
              <span class="title-bar" />
              Summary
            </h2>
            <p class="summary-text">
              Full-Stack Web Developer dengan 1+ tahun pengalaman membangun aplikasi web skala produksi
              menggunakan <strong>Laravel/Lumen</strong> dan <strong>Nuxt.js/Vue.js</strong>.
              Fokus pada performa, skalabilitas, dan user experience yang luar biasa.
            </p>
          </div>

          <!-- Skills -->
          <div class="card">
            <h2 class="section-title">
              <span class="title-bar" />
              Keahlian Teknis
            </h2>
            <div class="skill-group">
              <p class="skill-category">Backend</p>
              <div class="skill-tags">
                <span class="tag">PHP</span>
                <span class="tag">Laravel</span>
                <span class="tag">Lumen</span>
                <span class="tag">RESTful API</span>
                <span class="tag">MySQL</span>
              </div>
            </div>
            <div class="skill-group">
              <p class="skill-category">Frontend</p>
              <div class="skill-tags">
                <span class="tag">Vue.js</span>
                <span class="tag">Nuxt.js</span>
                <span class="tag">Inertia.js</span>
                <span class="tag">HTML5</span>
                <span class="tag">CSS3</span>
              </div>
            </div>
            <div class="skill-group">
              <p class="skill-category">Styling</p>
              <div class="skill-tags">
                <span class="tag">Tailwind CSS</span>
                <span class="tag">Bootstrap</span>
              </div>
            </div>
            <div class="skill-group">
              <p class="skill-category">Tools</p>
              <div class="skill-tags">
                <span class="tag">Git</span>
                <span class="tag">Binance API</span>
                <span class="tag">Database Design</span>
                <span class="tag">Chart.js</span>
              </div>
            </div>
          </div>

          <!-- Education -->
          <div class="card">
            <h2 class="section-title">
              <span class="title-bar" />
              Pendidikan
            </h2>
            <div class="edu-item">
              <div class="edu-icon">🎓</div>
              <div>
                <p class="edu-degree">S1 Teknik Informatika</p>
                <p class="edu-school">STT STIKMA, Malang</p>
                <div class="edu-meta">
                  <span class="edu-year">2016 – 2020</span>
                  <span class="edu-gpa">GPA 3.25</span>
                </div>
              </div>
            </div>
          </div>

        </aside>

        <!-- RIGHT COLUMN -->
        <section class="right-col">

          <!-- Experience -->
          <div class="card">
            <h2 class="section-title">
              <span class="title-bar" />
              Pengalaman Kerja
            </h2>

            <div class="timeline">
              <div class="timeline-item">
                <div class="timeline-dot" />
                <div class="timeline-content">
                  <div class="job-header">
                    <div>
                      <p class="job-title">Junior Web Developer</p>
                      <p class="job-company">PT. Pateron Edukasi Indonesia</p>
                    </div>
                    <span class="job-period">Feb 2023 – Sekarang</span>
                  </div>
                  <ul class="job-list">
                    <li>Mengembangkan &amp; maintenance platform e-learning menggunakan <strong>Nuxt.js</strong> + <strong>Lumen</strong> + MySQL</li>
                    <li>Membangun user management system dengan role-based access control (Admin &amp; Siswa)</li>
                    <li>Implementasi RESTful API untuk data peserta, kelas, dan progress pembelajaran</li>
                    <li>Kolaborasi UI/UX untuk responsive design di semua device</li>
                    <li>Bug fixing &amp; maintenance rutin untuk stabilitas aplikasi</li>
                  </ul>
                  <div class="job-stack">
                    <span class="stack-badge">Nuxt.js</span>
                    <span class="stack-badge">Lumen</span>
                    <span class="stack-badge">MySQL</span>
                    <span class="stack-badge">Tailwind CSS</span>
                    <span class="stack-badge">Git</span>
                  </div>
                </div>
              </div>

              <div class="timeline-item">
                <div class="timeline-dot timeline-dot-secondary" />
                <div class="timeline-content">
                  <div class="job-header">
                    <div>
                      <p class="job-title">Freelance Junior Web Developer</p>
                      <p class="job-company">PT. Biner Cipta Data</p>
                    </div>
                    <span class="job-period">Jul – Agu 2022</span>
                  </div>
                  <ul class="job-list">
                    <li>Membangun Sistem Informasi Stunting dari <em>scratch</em> menggunakan Laravel, Bootstrap, MySQL</li>
                    <li>Implementasi fitur input data balita &amp; generate laporan</li>
                    <li>Dashboard admin untuk monitoring &amp; analisis data stunting</li>
                    <li>Desain database efisien untuk data balita &amp; riwayat kesehatan</li>
                  </ul>
                  <div class="job-stack">
                    <span class="stack-badge">Laravel</span>
                    <span class="stack-badge">MySQL</span>
                    <span class="stack-badge">Bootstrap</span>
                    <span class="stack-badge">JavaScript</span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Projects -->
          <div class="card">
            <h2 class="section-title">
              <span class="title-bar" />
              Projects
            </h2>
            <div class="projects-grid">

              <div class="project-card project-card-1">
                <div class="project-card-inner">
                  <div class="project-top">
                    <span class="project-icon">🤖</span>
                    <span class="project-status project-status-live">Production</span>
                  </div>
                  <h3 class="project-name">ZenithBot</h3>
                  <p class="project-desc">Platform trading otomatis terintegrasi Binance API untuk cryptocurrency trading</p>
                  <ul class="project-features">
                    <li>Auth &amp; authorization (Admin &amp; User)</li>
                    <li>Binance API key management</li>
                    <li>Balance tracking &amp; transaction history</li>
                    <li>Top-up system with admin approval</li>
                  </ul>
                  <div class="project-footer">
                    <div class="project-stack">
                      <span>Laravel v12</span><span>Nuxt.js v3</span><span>MySQL</span><span>Binance API</span>
                    </div>
                  </div>
                </div>
              </div>

              <div class="project-card project-card-2">
                <div class="project-card-inner">
                  <div class="project-top">
                    <span class="project-icon">📝</span>
                    <span class="project-status project-status-active">Active</span>
                  </div>
                  <h3 class="project-name">Web Pengerjaan Tryout</h3>
                  <p class="project-desc">Landing page &amp; sistem informasi pengerjaan tryout olimpiade sains</p>
                  <ul class="project-features">
                    <li>Auth Admin &amp; Student</li>
                    <li>Pengerjaan tryout online</li>
                    <li>Unduh data pembelian &amp; pengerjaan</li>
                    <li>Responsive semua device</li>
                  </ul>
                  <div class="project-footer">
                    <div class="project-stack">
                      <span>Laravel v12</span><span>Nuxt.js v4</span><span>Tailwind 4</span>
                    </div>
                    <a href="https://internationalscienceolympiad.com/" target="_blank" class="project-link">
                      https://internationalscienceolympiad.com ↗
                    </a>
                  </div>
                </div>
              </div>

              <div class="project-card project-card-3">
                <div class="project-card-inner">
                  <div class="project-top">
                    <span class="project-icon">🗓️</span>
                    <span class="project-status project-status-present">Present</span>
                  </div>
                  <h3 class="project-name">Rekap Data Kelas</h3>
                  <p class="project-desc">Sistem manajemen kelas &amp; penjadwalan dengan multi-level user management</p>
                  <ul class="project-features">
                    <li>3-tier: Admin, Panitia, Peserta</li>
                    <li>Penjadwalan kelas &amp; pengisi materi</li>
                    <li>Pendaftaran berbasis regional</li>
                    <li>Approval workflow + email notif</li>
                  </ul>
                  <div class="project-footer">
                    <div class="project-stack">
                      <span>Laravel v10</span><span>Inertia Vue</span><span>MySQL</span>
                    </div>
                  </div>
                </div>
              </div>

              <div class="project-card project-card-4">
                <div class="project-card-inner">
                  <div class="project-top">
                    <span class="project-icon">📊</span>
                    <span class="project-status project-status-present">Present</span>
                  </div>
                  <h3 class="project-name">SIMPAS</h3>
                  <p class="project-desc">Data Monitoring &amp; Reporting System dengan visualisasi interaktif</p>
                  <ul class="project-features">
                    <li>Interactive charts (Chart.js)</li>
                    <li>Admin &amp; User access control</li>
                    <li>Real-time stats &amp; trend analysis</li>
                    <li>Export ke Excel/PDF</li>
                  </ul>
                  <div class="project-footer">
                    <div class="project-stack">
                      <span>CodeIgniter v3</span><span>Bootstrap v4</span><span>Chart.js</span>
                    </div>
                  </div>
                </div>
              </div>

            </div>
          </div>

        </section>
      </div>

      <!-- Footer -->
      <footer class="cv-footer">
        <p>Fatkul Umar · Junior Web Developer · Ngawi, Jawa Timur</p>
        <p class="footer-sub">Built with Nuxt 4 + Tailwind CSS 4</p>
      </footer>
    </main>
  </div>
</template>

<script setup lang="ts">
useHead({
  title: 'Fatkul Umar — Junior Web Developer',
  meta: [
    { name: 'description', content: 'CV / Portfolio Fatkul Umar — Full-Stack Web Developer (Laravel, Nuxt.js, Vue.js)' },
    { property: 'og:title', content: 'Fatkul Umar — Junior Web Developer' },
    { property: 'og:description', content: 'Full-Stack Web Developer dengan 2+ tahun pengalaman di Laravel & Nuxt.js' },
  ],
})
</script>

<style scoped>
/* ─── CUSTOM PROPERTIES ─────────────────────────── */
:root {
  --c-bg: #0a0f1e;
  --c-surface: rgba(255,255,255,0.04);
  --c-border: rgba(255,255,255,0.08);
  --c-text: #e2e8f0;
  --c-muted: #8892a4;
  --c-accent-1: #6ee7f7;  /* cyan */
  --c-accent-2: #818cf8;  /* indigo */
  --c-accent-3: #f472b6;  /* pink */
  --c-grad-1: linear-gradient(135deg, #6ee7f7, #818cf8);
  --c-grad-2: linear-gradient(135deg, #818cf8, #f472b6);
}

/* ─── ROOT ─────────────────────────────────────── */
.cv-root {
  min-height: 100vh;
  background: var(--c-bg);
  color: var(--c-text);
  font-family: 'DM Sans', 'Segoe UI', sans-serif;
  position: relative;
  overflow-x: hidden;
}

/* ─── AMBIENT BLOBS ────────────────────────────── */
.blob {
  position: fixed;
  border-radius: 50%;
  filter: blur(120px);
  pointer-events: none;
  z-index: 0;
}
.blob-1 {
  width: 600px; height: 600px;
  background: radial-gradient(circle, rgba(110,231,247,0.15), transparent 70%);
  top: -200px; left: -200px;
}
.blob-2 {
  width: 500px; height: 500px;
  background: radial-gradient(circle, rgba(129,140,248,0.18), transparent 70%);
  top: 40%; right: -150px;
}
.blob-3 {
  width: 400px; height: 400px;
  background: radial-gradient(circle, rgba(244,114,182,0.12), transparent 70%);
  bottom: -100px; left: 30%;
}

/* ─── CONTAINER ─────────────────────────────────── */
.cv-container {
  position: relative;
  z-index: 1;
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem 1.5rem 4rem;
}

/* ─── HERO ──────────────────────────────────────── */
.hero-section {
  margin-bottom: 3rem;
  padding: 3rem 2.5rem;
  background: rgba(255,255,255,0.03);
  border: 1px solid var(--c-border);
  border-radius: 24px;
  backdrop-filter: blur(20px);
  position: relative;
  overflow: hidden;
}
.hero-section::before {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(135deg, rgba(110,231,247,0.06) 0%, rgba(129,140,248,0.06) 50%, rgba(244,114,182,0.04) 100%);
  pointer-events: none;
}
.hero-section::after {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 2px;
  background: var(--c-grad-1);
  border-radius: 24px 24px 0 0;
}
.hero-inner {
  display: flex;
  align-items: center;
  gap: 2.5rem;
  position: relative;
}

/* avatar */
.avatar-wrap {
  position: relative;
  flex-shrink: 0;
}
.avatar-ring {
  position: absolute;
  inset: -4px;
  border-radius: 50%;
  background: var(--c-grad-1);
  animation: spin 6s linear infinite;
}
@keyframes spin {
  from { transform: rotate(0deg); }
  to   { transform: rotate(360deg); }
}
.avatar-initials {
  width: 96px; height: 96px;
  border-radius: 50%;
  background: #0f1629;
  border: 3px solid transparent;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2rem;
  font-weight: 800;
  background-clip: padding-box;
  color: var(--c-accent-1);
  position: relative;
  z-index: 1;
  letter-spacing: -1px;
}

/* hero text */
.hero-label {
  font-size: 0.7rem;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--c-accent-1);
  margin-bottom: 0.5rem;
  font-weight: 600;
}
.hero-name {
  font-size: clamp(2.5rem, 5vw, 4rem);
  font-weight: 900;
  line-height: 1;
  margin: 0 0 0.75rem;
  letter-spacing: -2px;
  color: #fff;
}
.hero-name span {
  background: var(--c-grad-1);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}
.hero-tagline {
  color: var(--c-muted);
  font-size: 0.95rem;
  max-width: 500px;
  line-height: 1.7;
  margin-bottom: 1.5rem;
}
.hero-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

/* chips */
.chip {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  padding: 0.35rem 0.8rem;
  border-radius: 100px;
  font-size: 0.75rem;
  font-weight: 500;
  text-decoration: none;
  border: 1px solid var(--c-border);
  background: rgba(255,255,255,0.05);
  color: var(--c-text);
  transition: all 0.2s;
}
.chip:hover {
  transform: translateY(-1px);
  border-color: var(--c-accent-1);
  color: var(--c-accent-1);
}
.chip-email { color: var(--c-accent-1); border-color: rgba(110,231,247,0.3); }
.chip-github { color: #e2e8f0; }
.chip-linkedin { color: #60a5fa; border-color: rgba(96,165,250,0.3); }
.chip-location { cursor: default; }
.chip-phone { color: #34d399; border-color: rgba(52,211,153,0.3); }

/* ─── GRID ──────────────────────────────────────── */
.content-grid {
  display: grid;
  grid-template-columns: 320px 1fr;
  gap: 1.5rem;
  align-items: start;
}
@media (max-width: 860px) {
  .content-grid { grid-template-columns: 1fr; }
  .hero-inner { flex-direction: column; text-align: center; }
  .hero-links { justify-content: center; }
}

/* ─── CARDS ─────────────────────────────────────── */
.card {
  background: var(--c-surface);
  border: 1px solid var(--c-border);
  border-radius: 20px;
  padding: 1.75rem;
  backdrop-filter: blur(12px);
  margin-bottom: 1.5rem;
  transition: border-color 0.3s;
}
.card:hover {
  border-color: rgba(110,231,247,0.2);
}
.card-summary {
  background: linear-gradient(135deg, rgba(110,231,247,0.05), rgba(129,140,248,0.05));
}

/* ─── SECTION TITLES ────────────────────────────── */
.section-title {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  font-size: 0.75rem;
  font-weight: 700;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--c-muted);
  margin-bottom: 1.25rem;
}
.title-bar {
  display: inline-block;
  width: 3px;
  height: 16px;
  border-radius: 2px;
  background: var(--c-grad-1);
  flex-shrink: 0;
}

/* ─── SUMMARY ───────────────────────────────────── */
.summary-text {
  font-size: 0.9rem;
  line-height: 1.8;
  color: var(--c-muted);
}
.summary-text strong {
  color: var(--c-accent-1);
  font-weight: 600;
}

/* ─── SKILLS ────────────────────────────────────── */
.skill-group { margin-bottom: 1rem; }
.skill-group:last-child { margin-bottom: 0; }
.skill-category {
  font-size: 0.65rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: var(--c-accent-2);
  font-weight: 700;
  margin-bottom: 0.5rem;
}
.skill-tags { display: flex; flex-wrap: wrap; gap: 0.4rem; }
.tag {
  display: inline-block;
  padding: 0.25rem 0.65rem;
  border-radius: 8px;
  font-size: 0.72rem;
  font-weight: 500;
  background: rgba(129,140,248,0.1);
  border: 1px solid rgba(129,140,248,0.2);
  color: #a5b4fc;
  transition: all 0.2s;
}
.tag:hover {
  background: rgba(129,140,248,0.2);
  color: #c7d2fe;
  transform: translateY(-1px);
}

/* ─── EDUCATION ─────────────────────────────────── */
.edu-item {
  display: flex;
  gap: 1rem;
  align-items: flex-start;
}
.edu-icon {
  font-size: 1.5rem;
  flex-shrink: 0;
  margin-top: 2px;
}
.edu-degree {
  font-weight: 700;
  color: var(--c-text);
  font-size: 0.95rem;
  margin-bottom: 0.2rem;
}
.edu-school {
  color: var(--c-muted);
  font-size: 0.82rem;
  margin-bottom: 0.5rem;
}
.edu-meta {
  display: flex;
  gap: 0.75rem;
  align-items: center;
}
.edu-year {
  font-size: 0.72rem;
  color: var(--c-muted);
  background: rgba(255,255,255,0.05);
  padding: 0.2rem 0.6rem;
  border-radius: 6px;
}
.edu-gpa {
  font-size: 0.72rem;
  font-weight: 700;
  color: #34d399;
  background: rgba(52,211,153,0.1);
  padding: 0.2rem 0.6rem;
  border-radius: 6px;
}

/* ─── TIMELINE ──────────────────────────────────── */
.timeline { position: relative; }
.timeline::before {
  content: '';
  position: absolute;
  left: 10px;
  top: 0; bottom: 0;
  width: 1px;
  background: linear-gradient(to bottom, var(--c-accent-1), var(--c-accent-2), transparent);
}
.timeline-item {
  display: flex;
  gap: 1.25rem;
  margin-bottom: 2rem;
}
.timeline-item:last-child { margin-bottom: 0; }
.timeline-dot {
  width: 22px;
  height: 22px;
  border-radius: 50%;
  background: var(--c-grad-1);
  flex-shrink: 0;
  margin-top: 2px;
  box-shadow: 0 0 12px rgba(110,231,247,0.4);
  position: relative;
  z-index: 1;
}
.timeline-dot-secondary {
  background: var(--c-grad-2);
  box-shadow: 0 0 12px rgba(129,140,248,0.4);
}
.timeline-content { flex: 1; }

.job-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 1rem;
  margin-bottom: 0.75rem;
  flex-wrap: wrap;
}
.job-title {
  font-size: 1rem;
  font-weight: 700;
  color: #fff;
  margin-bottom: 0.15rem;
}
.job-company {
  font-size: 0.82rem;
  color: var(--c-accent-2);
  font-weight: 500;
}
.job-period {
  font-size: 0.7rem;
  color: var(--c-muted);
  background: rgba(255,255,255,0.05);
  padding: 0.25rem 0.7rem;
  border-radius: 100px;
  white-space: nowrap;
  flex-shrink: 0;
}
.job-list {
  list-style: none;
  padding: 0;
  margin: 0 0 0.85rem;
}
.job-list li {
  position: relative;
  padding-left: 1rem;
  font-size: 0.85rem;
  color: var(--c-muted);
  line-height: 1.7;
  margin-bottom: 0.3rem;
}
.job-list li::before {
  content: '▸';
  position: absolute;
  left: 0;
  color: var(--c-accent-1);
  font-size: 0.7rem;
  top: 0.15rem;
}
.job-list li strong { color: var(--c-text); font-weight: 600; }
.job-stack {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
}
.stack-badge {
  font-size: 0.67rem;
  font-weight: 600;
  padding: 0.15rem 0.55rem;
  border-radius: 6px;
  background: rgba(110,231,247,0.08);
  border: 1px solid rgba(110,231,247,0.2);
  color: var(--c-accent-1);
}

/* ─── PROJECTS GRID ─────────────────────────────── */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1rem;
}
@media (max-width: 640px) {
  .projects-grid { grid-template-columns: 1fr; }
}

.project-card {
  border-radius: 16px;
  border: 1px solid var(--c-border);
  overflow: hidden;
  transition: transform 0.25s, border-color 0.25s, box-shadow 0.25s;
}
.project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 20px 40px rgba(0,0,0,0.3);
}
.project-card-1 { border-color: rgba(110,231,247,0.2); background: linear-gradient(135deg, rgba(110,231,247,0.05), rgba(0,0,0,0)); }
.project-card-1:hover { border-color: rgba(110,231,247,0.5); box-shadow: 0 20px 40px rgba(110,231,247,0.1); }
.project-card-2 { border-color: rgba(129,140,248,0.2); background: linear-gradient(135deg, rgba(129,140,248,0.05), rgba(0,0,0,0)); }
.project-card-2:hover { border-color: rgba(129,140,248,0.5); box-shadow: 0 20px 40px rgba(129,140,248,0.1); }
.project-card-3 { border-color: rgba(244,114,182,0.2); background: linear-gradient(135deg, rgba(244,114,182,0.05), rgba(0,0,0,0)); }
.project-card-3:hover { border-color: rgba(244,114,182,0.5); box-shadow: 0 20px 40px rgba(244,114,182,0.1); }
.project-card-4 { border-color: rgba(52,211,153,0.2); background: linear-gradient(135deg, rgba(52,211,153,0.05), rgba(0,0,0,0)); }
.project-card-4:hover { border-color: rgba(52,211,153,0.5); box-shadow: 0 20px 40px rgba(52,211,153,0.1); }

.project-card-inner { padding: 1.25rem; height: 100%; display: flex; flex-direction: column; }
.project-top { display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.75rem; }
.project-icon { font-size: 1.4rem; }
.project-status {
  font-size: 0.62rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  padding: 0.2rem 0.55rem;
  border-radius: 100px;
}
.project-status-live { background: rgba(110,231,247,0.15); color: var(--c-accent-1); border: 1px solid rgba(110,231,247,0.3); }
.project-status-active { background: rgba(129,140,248,0.15); color: var(--c-accent-2); border: 1px solid rgba(129,140,248,0.3); }
.project-status-present { background: rgba(52,211,153,0.15); color: #34d399; border: 1px solid rgba(52,211,153,0.3); }

.project-name {
  font-size: 1rem;
  font-weight: 800;
  color: #fff;
  margin-bottom: 0.4rem;
  letter-spacing: -0.3px;
}
.project-desc {
  font-size: 0.78rem;
  color: var(--c-muted);
  line-height: 1.6;
  margin-bottom: 0.75rem;
}
.project-features {
  list-style: none;
  padding: 0;
  margin: 0 0 0.85rem;
  flex: 1;
}
.project-features li {
  font-size: 0.75rem;
  color: var(--c-muted);
  padding-left: 0.9rem;
  position: relative;
  margin-bottom: 0.25rem;
  line-height: 1.5;
}
.project-features li::before {
  content: '·';
  position: absolute;
  left: 0;
  color: var(--c-accent-1);
  font-weight: 700;
}
.project-footer {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  gap: 0.5rem;
  flex-wrap: wrap;
  margin-top: auto;
}
.project-stack {
  display: flex;
  flex-wrap: wrap;
  gap: 0.3rem;
}
.project-stack span {
  font-size: 0.62rem;
  font-weight: 600;
  color: var(--c-muted);
  background: rgba(255,255,255,0.05);
  padding: 0.15rem 0.45rem;
  border-radius: 5px;
}
.project-link {
  font-size: 0.72rem;
  font-weight: 700;
  color: var(--c-accent-1);
  text-decoration: none;
  white-space: nowrap;
  transition: opacity 0.2s;
}
.project-link:hover { opacity: 0.75; text-decoration: underline; }

/* ─── FOOTER ─────────────────────────────────────── */
.cv-footer {
  text-align: center;
  margin-top: 3rem;
  padding-top: 2rem;
  border-top: 1px solid var(--c-border);
  color: var(--c-muted);
  font-size: 0.8rem;
  line-height: 1.8;
}
.footer-sub {
  font-size: 0.7rem;
  opacity: 0.5;
}
</style>