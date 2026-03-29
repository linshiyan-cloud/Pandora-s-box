<template>
  <main class="home">
    <!-- 1. Hero 大标题区 -->
    <section class="hero">
      <div class="hero-inner">
        <div class="hero-left">
          <h1>Maximize Your Efficiency with ProductivityPro</h1>
          <p>Stay organized, focused, and achieve more with our powerful productivity web app. Take control of your tasks, conquer your goals.</p>
        </div>
        <div class="hero-right">
          <div class="app-preview"></div>
        </div>
      </div>
    </section>

    <!-- 2. 功能卡片区 -->
    <section class="features">
      <div class="features-inner">
        <div class="feature-card">
          <div class="icon blue">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="white">
              <path d="M12 4L19 11H15V20H9V11H5L12 4Z"/>
            </svg>
          </div>
          <h3>Task Management</h3>
          <p>Effortlessly organize and prioritize your tasks.</p>
        </div>
        <div class="feature-card">
          <div class="icon green">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="white">
              <path d="M12 21.35L10.55 20.03C5.4 15.36 2 12.27 2 8.5C2 5.42 4.42 3 7.5 3C9.24 3 10.91 3.81 12 5.09C13.09 3.81 14.76 3 16.5 3C19.58 3 22 5.42 22 8.5C22 12.27 18.6 15.36 13.45 20.04L12 21.35Z"/>
            </svg>
          </div>
          <h3>Time Tracking</h3>
          <p>Stay accountable with time tracking and insights.</p>
        </div>
        <div class="feature-card">
          <div class="icon orange">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="white">
              <path d="M12 12C14.21 12 16 10.21 16 8C16 5.79 14.21 4 12 4C9.79 4 8 5.79 8 8C8 10.21 9.79 12 12 12ZM12 14C9.33 14 4 15.34 4 18V20H20V18C20 15.34 14.67 14 12 14Z"/>
            </svg>
          </div>
          <h3>Collaboration Tools</h3>
          <p>Seamlessly collaborate and communicate with your team.</p>
        </div>
      </div>
    </section>

    <!-- 3. 目标追踪区 -->
    <section class="goals">
      <div class="goals-inner">
        <div class="goals-left">
          <h2>Set and track your goals for success</h2>
          <p>Embrace life's vastness, venture forth, and discover the wonders waiting beyond. The world beckons; seize its grand offerings now!</p>
          <p>Our tools help you monitor progress and stay motivated every single day.</p>
        </div>
        <div class="goals-right">
          <div class="chart-group">
            <div class="chart-card">
              <div class="circle-chart">
                <div class="percent">47%</div>
              </div>
              <div class="legend">
                <span class="dot red"></span> Restless
                <span class="dot yellow"></span> Awaits
              </div>
            </div>
            <div class="chart-card bar-chart">
              <div class="bar-item">
                <span>Instagram</span>
                <div class="bar-fill yellow"></div>
                <span>63,370</span>
              </div>
              <div class="bar-item">
                <span>Facebook</span>
                <div class="bar-fill blue"></div>
                <span>78,900</span>
              </div>
              <div class="bar-item">
                <span>Twitter</span>
                <div class="bar-fill orange"></div>
                <span>103,645</span>
              </div>
            </div>
            <div class="chart-card line-chart">
              <h4>Income And Outcome</h4>
              <div class="line-placeholder"></div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- 4. 用户展示区 -->
    <section class="user-showcase">
      <div class="user-inner">
        <div class="user-left">
          <div class="user-card">
            <div class="avatar"></div>
            <h4>Anastasia M.</h4>
            <p>Product Manager</p>
            <div class="stats">
              <span>Views</span>
              <span>Followers</span>
              <span>Likes</span>
            </div>
          </div>
          <div class="shield-icon"></div>
        </div>
        <div class="user-right">
          <h2>Set and track your goals for success</h2>
          <p>Embrace life's vastness, venture forth, and discover the wonders waiting beyond. The world beckons; seize its grand offerings now!</p>
        </div>
      </div>
    </section>

    <!-- 5. 用户评价区 -->
    <section class="testimonials">
      <div class="test-inner">
        <h2>Testimonials from our members</h2>
        <div class="test-cards">
          <div class="test-card">
            <div class="quote">"</div>
            <p>ProductivityPro has revolutionized my workflow. It's a game-changer!</p>
            <div class="stars">⭐⭐⭐⭐⭐</div>
            <div class="author">
              <div class="avatar"></div>
              <div>
                <h5>Jennifer W.</h5>
                <p>Creative Producer</p>
              </div>
            </div>
          </div>
          <div class="test-card">
            <div class="quote">"</div>
            <p>I love the simplicity and power of ProductivityPro. Highly recommended!</p>
            <div class="stars">⭐⭐⭐⭐⭐</div>
            <div class="author">
              <div class="avatar"></div>
              <div>
                <h5>Alex M.</h5>
                <p>Creative Producer</p>
              </div>
            </div>
          </div>
        </div>
        <div class="arrows">
          <button>&lt;</button>
          <button>&gt;</button>
        </div>
      </div>
    </section>

    <!-- 6. CTA 行动区 -->
    <section class="cta">
      <div class="cta-inner">
        <h2>Ready to get started?</h2>
        <button class="cta-btn">Create an Account</button>
      </div>
    </section>

    <!-- 7. Footer 页脚 -->
    <footer class="footer">
      <div class="footer-inner">
        <div class="footer-col">
          <h4>Get in Touch</h4>
          <p>Our quick support team is here to help</p>
          <div class="social">
            <span>f</span>
            <span>t</span>
            <span>in</span>
          </div>
        </div>
        <div class="footer-col">
          <h4>Company info</h4>
          <p>About Us</p>
          <p>Careers</p>
          <p>We're hiring</p>
          <p>Blog</p>
p>
        </div>
        <div class="footer-col">
          <h4>Features</h4>
          <p>Business Marketing</p>
          <p>SSH Analytics</p>
          <p>Live Chat</p>
          <p>Unlimited Support</p>
        </div>
      </div>
      <div class="copyright">
        <p>Made With Love By ProductivityPro All Rights Reserved</p>
      </div>
    </footer>
  </main>
</template>

<script setup>
</script>

<style scoped>
/* 全局样式 */
.home {
  width: 100%;
}
section {
  padding: 4rem 0;
}
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

/* 1. Hero 区 */
.hero {
  background: linear-gradient(to bottom right, #e0f2fe, #ffffff);
  position: relative;
  overflow: hidden;
}
.hero::after {
  content: '';
  position: absolute;
  bottom: -100px;
  right: 100px;
  width: 300px;
  height: 300px;
  background: #3b82f6;
  border-radius: 50%;
  opacity: 0.2;
}
.hero-inner {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  align-items: center;
  gap: 4rem;
}
.hero-left {
  flex: 1;
}
.hero-left h1 {
  font-size: 2.2rem;
  font-weight: 700;
  color: #1e293b;
  margin-bottom: 1rem;
}
.hero-left p {
  font-size: 0.9rem;
  color: #64748b;
  line-height: 1.6;
}
.hero-right {
  flex: 1;
}
.app-preview {
  width: 450px;
  height: 280px;
  background: #ffffff;
  border-radius: 12px;
  box-shadow: 0 8px 24px rgba(0,0,0,0.1);
}

/* 2. 功能卡片区 */
.features {
  border-top: 3px solid #ec4899;
  border-bottom: 3px solid #ec4899;
}
.features-inner {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  justify-content: center;
  gap: 2rem;
}
.feature-card {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  text-align: center;
  width: 280px;
}
.icon {
  width: 48px;
  height: 48px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 1rem;
}
.blue { background: #3b82f6; }
.green { background: #10b981; }
.orange { background: #f97316; }
.feature-card h3 {
  font-size: 1rem;
  font-weight: 600;
  color: #1e293b;
  margin-bottom: 0.5rem;
}
.feature-card p {
  font-size: 0.8rem;
  color: #64748b;
}

/* 3. 目标追踪区 */
.goals-inner {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  align-items: flex-start;
  gap: 4rem;
}
.goals-left {
  flex: 1;
}
.goals-left h2 {
  font-size: 1.8rem;
  font-weight: 700;
  color: #1e293b;
  margin-bottom: 1rem;
}
.goals-left p {
  font-size: 0.9rem;
  color: #64748b;
  line-height: 1.6;
  margin-bottom: 1rem;
}
.goals-right {
  flex: 1;
}
.chart-group {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}
.chart-card {
  background: white;
  padding: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}
.circle-chart {
  width: 100px;
  height: 100px;
  border: 8px solid #fef2f2;
  border-right: 8px solid #ef4444;
  border-radius: 50%;
  margin: 0 auto 1rem;
  position: relative;
}
.percent {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-weight: 600;
}
.legend {
  display: flex;
  justify-content: center;
  gap: 1rem;
  font-size: 0.8rem;
  color: #64748b;
}
.dot {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  display: inline-block;
}
.red { background: #ef4444; }
.yellow { background: #fbbf24; }
.bar-item {
  display: flex;
  align-items: center;
  margin-bottom: 0.8rem;
  font-size: 0.8rem;
}
.bar-item span {
  width: 70px;
}
.bar-fill {
  flex: 1;
  height: 8px;
  border-radius: 4px;
  margin: 0 0.5rem;
}
.bar-chart .yellow { background: #fbbf24; }
.bar-chart .blue { background: #3b82f6; }
.bar-chart .orange { background: #f97316; }
.line-chart {
  grid-column: 1 / -1;
}
.line-chart h4 {
  font-size: 1rem;
  font-weight: 600;
  color: #1e293b;
  margin-bottom: 1rem;
}
.line-placeholder {
  width: 100%;
  height: 150px;
  background: #0f172a;
  border-radius: 8px;
}

/* 4. 用户展示区 */
.user-showcase {
  background: linear-gradient(to top right, #e0f2fe, #ffffff);
}
.user-inner {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  align-items: center;
  gap: 4rem;
}
.user-left {
  flex: 1;
  position: relative;
}
.user-card {
  background: white;
  padding: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  width: 200px;
  text-align: center;
}
.avatar {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  background: #e0f2fe;
  margin: 0 auto 1rem;
}
.user-card h4 {
  font-size: 1rem;
  font-weight: 600;
  color: #1e293b;
  margin-bottom: 0.3rem;
}
.user-card p {
  font-size: 0.8rem;
  color: #64748b;
  margin-bottom: 1rem;
}
.stats {
  display: flex;
  justify-content: space-between;
  font-size: 0.7rem;
  color: #64748b;
}
.shield-icon {
  position: absolute;
  top: -20px;
  right: 20px;
  width: 40px;
  height: 40px;
  background: #10b981;
  border-radius: 50%;
}
.user-right {
  flex: 1;
}
.user-right h2 {
  font-size: 1.8rem;
  font-weight: 700;
  color: #1e293b;
  margin-bottom: 1rem;
}
.user-right p {
  font-size: 0.9rem;
  color: #64748b;
  line-height: 1.6;
}

/* 5. 用户评价区 */
.test-inner {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}
.test-inner h2 {
  font-size: 2rem;
  font-weight: 700;
  color: #1e293b;
  margin-bottom: 2rem;
}
.test-cards {
  display: flex;
  gap: 2rem;
  overflow-x: auto;
}
.test-card {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  min-width: 300px;
}
.quote {
  font-size: 3rem;
  color: #e2e8f0;
  margin-bottom: 1rem;
}
.test-card p {
  font-size: 0.9rem;
  color: #64748b;
  margin-bottom: 1rem;
}
.stars {
  color: #fbbf24;
  margin-bottom: 1rem;
}
.author {
  display: flex;
  align-items: center;
  gap: 1rem;
}
.author .avatar {
  width: 30px;
  height: 30px;
  margin: 0;
}
.author h5 {
  font-size: 0.9rem;
  font-weight: 600;
  color: #1e293b;
}
.author p {
  font-size: 0.7rem;
  color: #64748b;
  margin: 0;
}
.arrows {
  display: flex;
  gap: 1rem;
  margin-top: 2rem;
}
.arrows button {
  background: white;
  border: 1px solid #e2e8f0;
  border-radius: 50%;
  width: 30px;
  height: 30px;
  cursor: pointer;
}

/* 6. CTA 区 */
.cta-inner {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 2rem;
}
.cta-inner h2 {
  font-size: 2rem;
  font-weight: 700;
  color: #1e293b;
}
.cta-btn {
  background: #f97316;
  color: white;
  border: none;
  padding: 0.8rem 2rem;
  border-radius: 6px;
  font-size: 1rem;
  font-weight: 600;
  cursor: pointer;
}

/* 7. Footer 区 */
.footer {
  background: #f8fafc;
  padding: 3rem 0 1rem;
}
.footer-inner {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  justify-content: space-between;
  margin-bottom: 2rem;
}
.footer-col h4 {
  font-size: 1rem;
  font-weight: 600;
  color: #1e293b;
  margin-bottom: 1rem;
}
.footer-col p {
  font-size: 0.8rem;
  color: #64748b;
  margin-bottom: 0.5rem;
}
.social {
  display: flex;
  gap: 1rem;
  margin-top: 1rem;
}
.social span {
  width: 20px;
  height: 20px;
  background: #3b82f6;
  border-radius: 50%;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 0.7rem;
}
.copyright {
  text-align: center;
  font-size: 0.7rem;
  color: #64748b;
  padding-top: 1rem;
  border-top: 1px solid #e2e8f0;
}
</style>