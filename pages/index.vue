<template>
  <div class="profile-page">
    <div class="profile-container">
      <!-- Header Section -->
      <header class="profile-header">
        <div class="profile-image-container">
          <img src="/assets/profile2.png" alt="Nadila Yanuarika" class="profile-image">
          <div class="image-border"></div>
        </div>
        <div class="profile-title">
          <h1>Nadila Yanuarika Rimawati</h1>
          <p class="subtitle">Mahasiswa D3 Teknologi Informasi</p>
          <div class="contact-info">
            <p><i class="bi bi-telephone"></i> +62 821-3171-5495</p>
            <p><i class="bi bi-envelope"></i> yanuarikanadila@gmail.com</p>
          </div>
        </div>
      </header>

      <!-- Main Content -->
      <main class="profile-content">
        <!-- About Section -->
        <section class="profile-section">
          <h2><i class="bi bi-person-badge"></i> Tentang Saya</h2>
          <p>Mahasiswa D3 Teknologi Informasi dengan ketertarikan kuat di bidang Frontend Development, UI/UX Design,
            Social Media dan Event Management. Berpengalaman mengembangkan beberapa proyek website menggunakan
            JavaScript, serta memiliki pemahaman dasar tentang desain antarmuka web dan mobile. Antusias belajar,
            teliti, dan mampu bekerja dalam tim maupun individu.</p>
        </section>

        <!-- Education Section -->
        <section class="profile-section">
          <h2><i class="bi bi-book"></i> Pendidikan</h2>
          <div class="education-container">
            <!-- SMA -->
            <div class="education-item">
              <div class="education-header">
                <div class="education-icon">
                  <i class="bi bi-mortarboard"></i>
                </div>
                <div>
                  <h3>SMAN 1 Tumpang</h3>
                  <p class="education-period">2020 - 2023</p>
                </div>
              </div>
              <div class="education-details">
                <p class="education-major">Jurusan MIPA</p>
                <ul class="education-achievements">
                  <li>Lulusan IPA dengan dasar kuat dalam logika dan analisis</li>
                  <li>Aktif dalam organisasi dan kerja kelompok</li>
                  <li>Pengembangan minat di teknologi sejak sekolah</li>
                </ul>
              </div>
            </div>

            <!-- Universitas -->
            <div class="education-item">
              <div class="education-header">
                <div class="education-icon">
                  <i class="bi bi-building"></i>
                </div>
                <div>
                  <h3>Universitas Brawijaya</h3>
                  <p class="education-period">2023 - Sekarang</p>
                </div>
              </div>
              <div class="education-details">
                <p class="education-major">D3 Teknologi Informasi</p>
                <ul class="education-achievements">
                  <li>Fokus pada pengembangan web, UI/UX, media sosial, dan event</li>
                  <li>Pengalaman membuat website manajemen laundry dan membuat desain UI app (Figma)</li>
                  <li>Aktif dalam kepanitiaan orientasi mahasiswa</li>
                </ul>
              </div>
            </div>
          </div>
        </section>

        <!-- Organization Experience -->
        <section class="profile-section">
          <h2><i class="bi bi-people"></i> Pengalaman Organisasi</h2>
          <div class="experience-grid">
            <div class="experience-card">
              <div class="exp-header">
                <h3>Staff Divisi Kesehatan</h3>
                <span class="exp-year">2024</span>
              </div>
              <p class="exp-org">Yuwaraja – Ospek Fakultas Vokasi UB</p>
              <p class="exp-desc">Bertanggung jawab memantau kesehatan ±700 mahasiswa baru selama orientasi,
                berkoordinasi dengan tim medis, serta menjaga kelancaran dan kenyamanan acara fakultas selama 3 hari.
              </p>
            </div>
            <div class="experience-card">
              <div class="exp-header">
                <h3>Supervisor</h3>
                <span class="exp-year">2024</span>
              </div>
              <p class="exp-org">Sambati – Ospek Jurusan Teknologi Informasi</p>
              <p class="exp-desc">Bertanggung jawab mendampingi 20 mahasiswa baru, memastikan kehadiran, pemahaman
                agenda, dan kelancaran orientasi jurusan.</p>
            </div>
          </div>
        </section>

        <!-- Skills Section -->
        <section class="profile-section">
          <h2><i class="bi bi-tools"></i> Kemampuan</h2>
          <div class="skills-container">
            <div class="skill-category">
              <h3>Teknis</h3>
              <div class="skill-tags">
                <span class="skill-tag">Desain UI/UX</span>
                <span class="skill-tag">HTML, CSS, & JavaScript</span>
              </div>
            </div>
            <div class="skill-category">
              <h3>Manajerial</h3>
              <div class="skill-tags">
                <span class="skill-tag">Manajemen Event</span>
                <span class="skill-tag">Leadership</span>
                <span class="skill-tag">Komunikasi</span>
              </div>
            </div>
          </div>
        </section>
      </main>

      <!-- Portfolio Section -->
      <section class="profile-section">
        <h2 class="section-title"><i class="bi bi-code-slash"></i> Portofolio</h2>
        <div class="portfolio-grid">

          <!-- Project 1: Laundry React App -->
          <div class="portfolio-card">
            <div class="portfolio-image">
              <img src="/assets/laundry-react.png" alt="Laundry React App">
              <div class="live-badge">Live Demo</div>
            </div>
            <div class="portfolio-content">
              <h3>Laundry Management System</h3>
              <div class="portfolio-tech">
                <span class="tech-pill">React</span>
                <span class="tech-pill">Node.js</span>
                <span class="tech-pill">Express</span>
                <span class="tech-pill">MySQL</span>
              </div>
              <ul class="portfolio-features">
                <li><i class="bi bi-check-circle"></i> Sistem pemesanan online dengan tracking</li>
                <li><i class="bi bi-check-circle"></i> Dashboard admin untuk manajemen order</li>
              </ul>
              <div class="portfolio-links">
                <a href="https://github.com/nadila-yanuarika/laundry" target="_blank" class="portfolio-link">
                  <i class="bi bi-github"></i> Source Code
                </a>
                <a href="https://web-laundry-pi.vercel.app/" target="_blank" class="portfolio-link primary">
                  <i class="bi bi-box-arrow-up-right"></i> Live Demo
                </a>
              </div>
            </div>
          </div>

          <!-- Project 2: CV Website -->
          <div class="portfolio-card">
            <div class="portfolio-image">
              <img src="/assets/cv.png" alt="Interactive CV Website">
              <div class="live-badge">Live Demo</div>
            </div>
            <div class="portfolio-content">
              <h3>Interactive CV Website</h3>
              <div class="portfolio-tech">
                <span class="tech-pill">Vue.js</span>
                <span class="tech-pill">CSS3</span>
                <span class="tech-pill">HTML5</span>
                <span class="tech-pill">Responsive</span>
              </div>
              <ul class="portfolio-features">
                <li><i class="bi bi-check-circle"></i> Portofolio interaktif dengan animasi</li>
                <li><i class="bi bi-check-circle"></i> Desain responsif untuk semua perangkat</li>
              </ul>
              <div class="portfolio-links">
                <a href="https://github.com/nadila-yanuarika/CV-nadila" target="_blank" class="portfolio-link">
                  <i class="bi bi-github"></i> Source Code
                </a>
                <a href="https://cv-nadila.vercel.app/" target="_blank" class="portfolio-link primary">
                  <i class="bi bi-box-arrow-up-right"></i> Live Demo
                </a>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Footer with Social Media -->
      <footer class="profile-footer">
        <h3>Temukan Saya di</h3>
        <div class="social-links">
          <a href="https://instagram.com/@nadilaayan.__" class="social-link">
            <i class="bi bi-instagram"></i> Instagram
          </a>
          <a href="https://www.linkedin.com/in/nadila-yanuarika-5a9488289" class="social-link">
            <i class="bi bi-linkedin"></i> LinkedIn
          </a>
          <a href="https://github.com/nadila-yanuarika" class="social-link">
            <i class="bi bi-linkedin"></i> GitHub
          </a>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: "ProfilePage",
  head() {
    return {
      title: "Profil Nadila Yanuarika Rimawati"
    }
  }
}
</script>

<style scoped>
.profile-page {
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  min-height: 100vh;
  padding: 2rem;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.profile-container {
  max-width: 900px;
  margin: 0 auto;
  background: white;
  border-radius: 20px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
  overflow: hidden;
}

.profile-header {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2rem;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  text-align: center;
  position: relative;
}

.profile-image-container {
  position: relative;
  width: 150px;
  height: 150px;
  margin-bottom: 1.5rem;
}

.profile-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 50%;
  border: 5px solid rgba(255, 255, 255, 0.2);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
  z-index: 2;
  position: relative;
}

.image-border {
  position: absolute;
  top: -10px;
  left: -10px;
  right: -10px;
  bottom: -10px;
  border-radius: 50%;
  background: linear-gradient(135deg, rgba(255, 255, 255, 0.3) 0%, rgba(255, 255, 255, 0.1) 100%);
  z-index: 1;
}

.profile-title h1 {
  margin: 0;
  font-size: 1.8rem;
  font-weight: 700;
}

.subtitle {
  margin: 0.5rem 0;
  font-size: 1.1rem;
  opacity: 0.9;
}

.contact-info {
  margin-top: 1rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
}

.contact-info p {
  margin: 0;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.profile-content {
  padding: 2rem;
}

.profile-section {
  margin-bottom: 2.5rem;
}

.profile-section h2 {
  color: #667eea;
  display: flex;
  align-items: center;
  gap: 0.5rem;
  margin-bottom: 1.5rem;
  font-size: 1.4rem;
}

.education-container {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

.education-item {
  background: #f9f9ff;
  border-radius: 12px;
  padding: 1.5rem;
  border-left: 4px solid #667eea;
  transition: transform 0.3s ease;
}

.education-item:hover {
  transform: translateY(-3px);
}

.education-header {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin-bottom: 1rem;
}

.education-icon {
  background: #e0e8ff;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #667eea;
  font-size: 1.2rem;
}

.education-header h3 {
  margin: 0;
  font-size: 1.2rem;
  color: #333;
}

.education-period {
  margin: 0.2rem 0 0;
  color: #667eea;
  font-weight: 500;
  font-size: 0.9rem;
}

.education-major {
  margin: 0 0 0.8rem;
  font-weight: 600;
  color: #555;
  padding-left: 52px;
  /* Sesuaikan dengan icon */
}

.education-achievements {
  margin: 0;
  padding-left: 52px;
  list-style-type: none;
}

.education-achievements li {
  position: relative;
  padding-left: 1.2rem;
  margin-bottom: 0.5rem;
  color: #666;
  font-size: 0.95rem;
  line-height: 1.5;
}

.education-achievements li::before {
  content: "•";
  position: absolute;
  left: 0;
  color: #667eea;
  font-weight: bold;
}

/* Responsif */
@media (max-width: 576px) {
  .education-header {
    flex-direction: column;
    align-items: flex-start;
    gap: 0.5rem;
  }

  .education-major,
  .education-achievements {
    padding-left: 0;
  }
}

.experience-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
}

.experience-card {
  background: #f9f9ff;
  border-radius: 10px;
  padding: 1.5rem;
  border-left: 4px solid #667eea;
}

.exp-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 0.5rem;
}

.exp-header h3 {
  margin: 0;
  font-size: 1.1rem;
}

.exp-year {
  background: #667eea;
  color: white;
  padding: 0.2rem 1rem;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: 500;
}

.exp-org {
  margin: 0 0 0.8rem;
  font-weight: 500;
  color: #555;
}

.exp-desc {
  margin: 0;
  color: #666;
  font-size: 0.95rem;
}

.skills-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 2rem;
}

.skill-category h3 {
  margin: 0 0 1rem;
  color: #555;
  font-size: 1.1rem;
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.8rem;
}

.skill-tag {
  background: #e0e8ff;
  color: #667eea;
  padding: 0.5rem 1rem;
  border-radius: 20px;
  font-size: 0.9rem;
  font-weight: 500;
}

.profile-footer {
  padding: 1.5rem 2rem;
  background: #f5f7ff;
  text-align: center;
}

.profile-footer h3 {
  margin: 0 0 1rem;
  color: #555;
}

.social-links {
  display: flex;
  justify-content: center;
  gap: 1.5rem;
}

.social-link {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  color: #667eea;
  text-decoration: none;
  font-weight: 500;
  transition: all 0.3s;
}

.social-link:hover {
  color: #764ba2;
  transform: translateY(-2px);
}

/* Responsive Design */
@media (max-width: 768px) {
  .profile-header {
    padding: 1.5rem;
  }

  .profile-content {
    padding: 1.5rem;
  }

  .experience-grid {
    grid-template-columns: 1fr;
  }

  .timeline-date {
    position: static;
    text-align: left;
    padding-right: 0;
    margin-bottom: 0.3rem;
  }

  .timeline::before {
    display: none;
  }

  .timeline-content {
    padding-left: 0;
  }
}

/* Portfolio Enhancements */
.section-title {
  font-size: 1.5rem;
  font-weight: bold;
  color: #5f7cf9;
  margin-top: 0rem;
  margin-bottom: 1rem;
  margin-left: var(--section-title-margin-left, 2rem);
}

.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 2rem;
  justify-items: center;
}

.portfolio-card {
  width: 100%;
  max-width: 360px;
  border-radius: 16px;
  overflow: hidden;
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.1);
  background: white;
  display: flex;
  flex-direction: column;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.portfolio-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 16px 40px rgba(0, 0, 0, 0.15);
}


.portfolio-image {
  height: 200px;
  overflow: hidden;
  position: relative;
}

.portfolio-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.4s ease;
}

.portfolio-card:hover .portfolio-image img {
  transform: scale(1.05);
}


.live-badge {
  position: absolute;
  top: 15px;
  right: 15px;
  background: #00b894;
  color: white;
  padding: 0.4rem 1rem;
  border-radius: 9999px;
  font-size: 0.75rem;
  font-weight: 600;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
}


.portfolio-content {
  padding: 1.5rem;
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.portfolio-content h3 {
  font-size: 1.25rem;
  color: #2d3436;
  margin-bottom: 0.75rem;
}

.portfolio-tech {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-bottom: 1rem;
}

.tech-pill {
  background-color: #e0f3ff;
  color: #0984e3;
  padding: 0.3rem 0.7rem;
  border-radius: 9999px;
  font-size: 0.75rem;
  font-weight: 500;
}

.portfolio-features {
  list-style: none;
  padding-left: 0;
  margin: 0 0 1.2rem;
  color: #636e72;
  font-size: 0.85rem;
  line-height: 1.5;
}

.portfolio-features li {
  margin-bottom: 0.6rem;
  padding-left: 1.5rem;
  position: relative;
  color: #555;
  font-size: 0.85rem;
  line-height: 1.5;
}

.portfolio-features li i {
  position: absolute;
  left: 0;
  color: #00b894;
  font-size: 1.1rem;
}

.portfolio-links {
  display: flex;
  gap: 1rem;
  margin-top: auto;
}

.portfolio-link {
  flex: 1;
  text-align: center;
  padding: 0.6rem 0;
  border-radius: 8px;
  font-size: 0.9rem;
  font-weight: 500;
  text-decoration: none;
  transition: all 0.3s;
}

.portfolio-link.primary {
  background-color: #6c5ce7;
  color: white;
}

.portfolio-link.primary:hover {
  background-color: #5649c0;
  transform: translateY(-2px);
  box-shadow: 0 3px 10px rgba(108, 92, 231, 0.3);
}

.portfolio-link:not(.primary) {
  background-color: #f0f2f5;
  color: #2d3436;
  border: 1px solid #dfe6e9;
}

.portfolio-link:not(.primary):hover {
  background-color: #dfe6e9;
}

@media (max-width: 768px) {
  .portfolio-card {
    max-width: 100%;
  }

  .portfolio-grid {
    gap: 1rem;
  }

  .portfolio-content {
    padding: 1rem;
  }
}

/* Responsive Adjustments */
@media (max-width: 768px) {
  .portfolio-grid {
    grid-template-columns: 1fr;
  }

  .portfolio-image img {
    height: 180px;
  }

  .setup-guide pre {
    font-size: 0.75rem;
    padding: 0.6rem;
  }
}

@media (max-width: 480px) {
  .portfolio-content {
    padding: 1rem;
  }

  .portfolio-links {
    flex-direction: column;
    gap: 0.8rem;
  }

  .portfolio-link {
    width: 100%;
    justify-content: center;
  }
}

@media (max-width: 480px) {
  .profile-page {
    padding: 1rem;
  }

  .contact-info {
    flex-direction: column;
    gap: 0.5rem;
  }

  .social-links {
    flex-direction: column;
    gap: 1rem;
  }
}
</style>