# Application
<header>
  <nav>
    <span class="nav-title">
      Kristina Adams
    </span>
    <a href="#" class="nav-link">
      <i class="fas fa-print"></i>
    </a>
  </nav>
</header>

<main>
  <section class="personal-info">
    <div class="avatar">
      <img class="avatar-img" src="#" alt="">
    </div>
    <h1 class="name">
      Kristina Adams
    </h1>
    <div class="social-media">
      <a class="social-media-link" href="https://www.facebook.com" target="_blank">
        <i class="fab fa-facebook fa-lg"></i>
      </a>
      <a class="social-media-link" href="https://www.instagram.com/" target="_blank">
        <i class="fab fa-instagram fa-lg"></i>
      </a>
      <a class="social-media-link" href="https://www.linkedin.com/" target="_blank">
        <i class="fab fa-linkedin fa-lg"></i>
      </a>
      <a class="social-media-link" href="https://line.me/ti/g/" target="_blank">
        <i class="fab fa-line fa-lg"></i>
      </a>
      <a class="social-media-link" href="mailto:info@alphacamp.co">
        <i class="fas fa-envelope fa-lg"></i>
      </a>
    </div>
    <div class="title">
      UIUX | 網頁前端工程與設計 | 台北台灣
    </div>
    <p class="description">
      我是 AC Genie，是 ALPHA Camp 學習體驗 (Student Success) 團隊的一員。 為了協助同學們能在課程中能有效學習與成長，我將扮演你的最佳學習夥伴與教練，時時觀測你在平台上的學習與進展，進而提供同學們學習意見與協助。
    </p>
  </section>

  <section class="skill-section">
    <h2>專業技能</h2>
    <div class="skills">
      <div class="skill">
        <h3 class="skill-name">程式設計入門</h3>
        <p class="skill-description">
          具備網頁設計的能力，能夠製作使用者介面與線框圖繪製，熟悉 HTML、CSS 和 JavaScript，並對於基礎的演算法有一定的掌握力。
        </p>
      </div>
      <div class="skill">
        <h3 class="skill-name">掌握網頁開發</h3>
        <p class="skill-description">
          能夠打造兼具前後端的 Web App 產品。從網頁切版、RWD、操作 DOM 事件、使用 AJAX 與串接 API 等前端能力，到使用 Node.js 與 MongoDB 建立後端功能，能夠深入瞭解網路應用程式運作的每個環節，並親手打造自己的產品。
        </p>
      </div>
      <div class="skill">
        <h3 class="skill-name">軟體工程師實力</h3>
        <p class="skill-description">
          前端部分能夠透過前端框架建立 SPA 頁面，後端則能夠建置完整的登入系統、使用 SQL 與資料庫設計、實作購物車與金流串接。
        </p>
      </div>
    </div>
  </section>

  <section class="experience-section">
    <h2 class="job-experience">工作經歷</h2>
    <div class="experience">
      <div class="experience-item">
        <h3 class="job-title">行銷設計</h3>
        <span class="company"><i class="far fa-building"></i>Alpha Camp</span>
        <span class="duration"><i class="far fa-calendar-alt"></i>2019 年 7 月 - 至今</span>
        <p>
          負責CIS與平面設計並印刷發包、餐點商業攝影、Facebook社群經營文案撰寫、企劃行銷活動、外送電商管理、廠商業務接洽、顧客應對與問題處理以及廚房人員教導，並在轉型期間設計菜單，負責餐點研發與擺盤設計。
        </p>
      </div>
      <hr>
      <div class="experience-item">
        <h3 class="job-title">資料庫建置</h3>
        <span class="company"><i class="far fa-building"></i>Alpha Camp</span>
        <span class="duration"><i class="far fa-calendar-alt"></i>2018 年 7 月 - 2019 年 7 月</span>
        <p>
          負責CIS與平面設計並印刷發包、餐點商業攝影、Facebook社群經營文案撰寫、企劃行銷活動、外送電商管理、廠商業務接洽、顧客應對與問題處理以及廚房人員教導，並在轉型期間設計菜單，負責餐點研發與擺盤設計。
        </p>
      </div>
      <hr>
      <div class="experience-item">
        <h3 class="job-title">行銷設計</h3>
        <span class="company"><i class="far fa-building"></i>Alpha Camp</span>
        <span class="duration"><i class="far fa-calendar-alt"></i>2017 年 7 月 - 2018 年 7 月</span>
        <p>
          負責CIS與平面設計並印刷發包、餐點商業攝影、Facebook社群經營文案撰寫、企劃行銷活動、外送電商管理、廠商業務接洽、顧客應對與問題處理以及廚房人員教導，並在轉型期間設計菜單，負責餐點研發與擺盤設計。
        </p>
      </div>
    </div>
  </section>
</main>


html,
body {
  font-family: "Lato", "Noto Sans TC", sans-serif;
  margin: 0;
  padding: 0;
  color: #333333;
  background-color: #f6f7f8;
}

/* Header */
header {
  height: 60px;
  color: #666666;
  box-shadow: 0 4px 12px 0 rgba(0, 0, 0, 0.08);
}

nav {
  max-width: 820px;
  margin: 0 auto;
  height: 100%;
  padding: 0 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.nav-title {
  font-weight: bold;
  letter-spacing: 1px;
}

.nav-link {
  color: #666666;
}

/* Main */
main {
  max-width: 780px;
  margin: 0 auto;
  padding: 40px 20px;
}

h2 {
  font-size: 32px;
  margin: 24px 0 8px;
}

h3 {
  font-size: 21px;
  margin: 0 0 8px 0;
  font-weight: 500;
}

section {
  margin-bottom: 48px;
}

p {
  color: #666666;
}

/* Personal Info */

.avatar {
  text-align: center; /* 內容置中 */
}

.avatar-img {
  border-radius: 25px; /* 圓框效果 */
}

.name {
  text-align: center; /* 內容置中 */
  font-size: 32px;
  margin: 20px 0;
}

.social-media {
  text-align: center; /* 內容置中 */
  margin-bottom: 20px;
}

.social-media-link {
  color: #999999;
  text-decoration: none; /* 沒有底線 */
  margin: 0 5px;
}

.social-media-link:hover {
  /* 滑鼠移過時啟用這組設定 */
  color: #ff6600;
}

.title {
  margin-bottom: 20px;
  text-align: center;
  font-size: 14px; /* 內容置中 */
  letter-spacing: 2px; /* 字元間距 */
  color: #ff6600;
}

/* Skill Section */
.skills {
  display: flex;
  justify-content: space-between;
}
.skill {
  width: 30%;
}
.skill-name {
  border-top: 1px solid #999999;
  padding-top: 16px;
}

/* Experience Section */
hr {
  border: 0px;
  height: 1px;
  background: #cccccc;
  margin: 20px 0;
}

.company,
.duration {
  color: #666666;
  font-size: 12px;
  margin-right: 20px;
}

.fa-building,
.fa-calendar-alt {
  margin-right: 5px;
}
