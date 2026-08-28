<div align="center">
  <img src="./welcome_banner.svg?v=2" alt="Mohamad Adib Tawil — Flutter Developer and Mobile Application Engineer" width="100%" />
</div>

<p align="center">
  <a href="#01--selected-work"><img src="https://img.shields.io/badge/Selected_Work-0B1220?style=flat-square&amp;logo=flutter&amp;logoColor=67E8F9" alt="Selected work" /></a>
  <a href="#02--engineering-system"><img src="https://img.shields.io/badge/Engineering_System-0B1220?style=flat-square&amp;logo=diagramsdotnet&amp;logoColor=34D399" alt="Engineering system" /></a>
  <a href="#03--technical-toolkit"><img src="https://img.shields.io/badge/Technical_Toolkit-0B1220?style=flat-square&amp;logo=dart&amp;logoColor=67E8F9" alt="Technical toolkit" /></a>
  <a href="#04--experience"><img src="https://img.shields.io/badge/Experience-0B1220?style=flat-square&amp;logo=readthedocs&amp;logoColor=C084FC" alt="Experience" /></a>
</p>

<p align="center">
  <a href="mailto:mohamad.adib.tawil@gmail.com"><img src="https://img.shields.io/badge/EMAIL-111827?style=for-the-badge&amp;logo=gmail&amp;logoColor=67E8F9" alt="Email Mohamad" /></a>
  <a href="https://www.linkedin.com/in/mohamad-adib-tawil-54024b314/"><img src="https://img.shields.io/badge/LINKEDIN-111827?style=for-the-badge&amp;logo=linkedin&amp;logoColor=67E8F9" alt="Mohamad on LinkedIn" /></a>
  <a href="https://github.com/Mohamad-Adib-Tawil"><img src="https://img.shields.io/badge/GITHUB-111827?style=for-the-badge&amp;logo=github&amp;logoColor=67E8F9" alt="Mohamad on GitHub" /></a>
</p>

<br />

<table>
  <tr>
    <td width="66%" valign="middle">
      <h2>Product-minded engineering.<br />Production-grade execution.</h2>
      <p>I am a Flutter developer with <strong>4 years of experience</strong> owning mobile products from requirements and architecture through backend integration, performance tuning, and store release.</p>
      <p>My work spans real-time social audio, bilingual marketplaces, offline document intelligence, and content platforms. I specialize in systems that remain predictable under pressure: feature-based Clean Architecture, BLoC/Cubit, typed failures, resilient realtime channels, and offline-first data flows.</p>
      <p><strong>Based in Syria · Working remotely worldwide</strong></p>
    </td>
    <td width="34%" align="center" valign="middle">
      <img src="./assets/profile.webp" alt="Mohamad Adib Tawil" width="250" />
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://img.shields.io/badge/4_YEARS-PRODUCTION_EXPERIENCE-0B1220?style=for-the-badge&amp;labelColor=111827&amp;color=0B1220" alt="4 years production experience" />
  <img src="https://img.shields.io/badge/5%2B_APPS-SHIPPED_END_TO_END-0B1220?style=for-the-badge&amp;labelColor=111827&amp;color=0B1220" alt="5+ apps shipped end to end" />
  <img src="https://img.shields.io/badge/ANDROID_%2B_IOS-STORE_RELEASES-0B1220?style=for-the-badge&amp;labelColor=111827&amp;color=0B1220" alt="Android and iOS store releases" />
</p>

---

## 01 / Selected work

<p><sub>REAL PRODUCTS · REAL USERS · MEASURABLE ENGINEERING</sub></p>

<a href="https://play.google.com/store/apps/details?id=com.bwmatbw.lklklivechatapp">
  <img src="./assets/projects/lklk.webp" alt="LKLK real-time social audio application" width="100%" />
</a>

<details>
  <summary><strong>Open engineering case study — LKLK</strong></summary>
  <br />
  <table>
    <tr>
      <td width="33%" valign="top"><strong>System</strong><br /><br />Architected live rooms for up to 500 listeners and 20 mic seats, with independent reconnect and exponential backoff per realtime channel.</td>
      <td width="33%" valign="top"><strong>Architecture</strong><br /><br />Placed ZEGOCLOUD and LiveKit behind an <code>AudioRepository</code>, making SDK switchover a dependency-injection change instead of a rewrite.</td>
      <td width="33%" valign="top"><strong>Product</strong><br /><br />Built six IAP coin tiers, VIP progression, and an SVGA/VAP gift queue capped at eight concurrent animations.</td>
    </tr>
  </table>
  <p><code>Flutter</code> · <code>Cubit</code> · <code>GetIt</code> · <code>ZEGOCLOUD</code> · <code>LiveKit</code> · <code>ZIM</code> · <code>Appwrite</code> · <code>Hive</code></p>
  <p><a href="https://play.google.com/store/apps/details?id=com.bwmatbw.lklklivechatapp"><strong>View on Google Play →</strong></a></p>
</details>

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://play.google.com/store/apps/details?id=com.wolfera.wolfera"><img src="./assets/projects/wolfera.webp" alt="Wolfera bilingual car marketplace" width="100%" /></a>
      <h3>Wolfera</h3>
      <p>AR/EN automotive marketplace with Supabase RLS, email/Google/Apple authentication, realtime buyer–seller chat, TFLite moderation, and targeted FCM price alerts.</p>
      <p><a href="https://play.google.com/store/apps/details?id=com.wolfera.wolfera"><strong>Google Play →</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://play.google.com/store/apps/details?id=com.werewolf.office_archiving"><img src="./assets/projects/office-archiving.webp" alt="Archiving Office on-device OCR application" width="100%" /></a>
      <h3>Archiving Office</h3>
      <p>Private on-device document manager with dual-engine Arabic/English OCR, orientation and preprocessing candidates, PDF editing, and SQLite full-text search.</p>
      <p><a href="https://play.google.com/store/apps/details?id=com.werewolf.office_archiving"><strong>Google Play →</strong></a></p>
    </td>
  </tr>
</table>

<details>
  <summary><strong>Compare the engineering decisions behind Wolfera and Archiving Office</strong></summary>
  <br />
  <table>
    <tr>
      <th>Decision</th>
      <th>Wolfera</th>
      <th>Archiving Office</th>
    </tr>
    <tr>
      <td><strong>Data boundary</strong></td>
      <td>Supabase PostgreSQL with Row-Level Security</td>
      <td>Fully on-device SQLite with additive-only migrations</td>
    </tr>
    <tr>
      <td><strong>Realtime / ML</strong></td>
      <td>Realtime chat, FCM diff-based alerts, TFLite moderation</td>
      <td>ML Kit + Tesseract candidate scoring and local processing</td>
    </tr>
    <tr>
      <td><strong>Resilience</strong></td>
      <td>Pagination, infinite scroll, secure auth flows</td>
      <td>Page/DPI/size caps and streamed rasterization</td>
    </tr>
  </table>
</details>

<br />

<img src="./assets/secondary-projects.svg" alt="Quran Ahmed Karasi and Book Code projects" width="100%" />

<p align="center">
  <a href="https://apps.apple.com/app/id6759857104"><img src="https://img.shields.io/badge/QURAN_APP-APP_STORE-111827?style=for-the-badge&amp;logo=apple&amp;logoColor=F8FAFC" alt="Quran Ahmed Karasi on App Store" /></a>
  <a href="https://play.google.com/store/apps/details?id=com.ahmadkarasi.quran"><img src="https://img.shields.io/badge/QURAN_APP-GOOGLE_PLAY-111827?style=for-the-badge&amp;logo=googleplay&amp;logoColor=34D399" alt="Quran Ahmed Karasi on Google Play" /></a>
</p>

---

## 02 / Engineering system

<p><sub>THE SAME DISCIPLINE FROM UI TO RELEASE</sub></p>

<img src="./assets/architecture.svg" alt="Production mobile architecture flow" width="100%" />

<table>
  <tr>
    <td width="25%" valign="top"><strong>Realtime</strong><br /><br />WebSockets, ZIM, LiveKit, ZEGOCLOUD, Supabase Realtime, reconnect policies.</td>
    <td width="25%" valign="top"><strong>Offline-first</strong><br /><br />Hive, SQLite, stale-while-revalidate, pagination, typed cache boundaries.</td>
    <td width="25%" valign="top"><strong>On-device ML</strong><br /><br />ML Kit, Tesseract, TFLite, image preprocessing, candidate scoring.</td>
    <td width="25%" valign="top"><strong>Release quality</strong><br /><br />Flavors, ProGuard/R8, secure storage, Crashlytics, Play Store, App Store.</td>
  </tr>
</table>

---

## 03 / Technical toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=flutter,dart,kotlin,supabase,firebase,sqlite,git,github,figma,postman&amp;theme=dark&amp;perline=10" alt="Core technology icons" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Clean_Architecture-111827?style=flat-square&amp;logoColor=67E8F9" alt="Clean Architecture" />
  <img src="https://img.shields.io/badge/BLoC_%2F_Cubit-111827?style=flat-square&amp;logo=bloc&amp;logoColor=67E8F9" alt="BLoC and Cubit" />
  <img src="https://img.shields.io/badge/GetIt_%2F_Injectable-111827?style=flat-square&amp;logo=dart&amp;logoColor=67E8F9" alt="GetIt and Injectable" />
  <img src="https://img.shields.io/badge/Freezed_%2F_dartz-111827?style=flat-square&amp;logo=dart&amp;logoColor=67E8F9" alt="Freezed and dartz" />
  <img src="https://img.shields.io/badge/Dio_%2F_REST_%2F_WebSockets-111827?style=flat-square&amp;logoColor=34D399" alt="Dio REST and WebSockets" />
  <img src="https://img.shields.io/badge/GoRouter-111827?style=flat-square&amp;logo=flutter&amp;logoColor=67E8F9" alt="GoRouter" />
</p>

<details>
  <summary><strong>Open the complete technology map</strong></summary>
  <br />
  <table>
    <tr><td><strong>Architecture & state</strong></td><td>Clean Architecture · SOLID · MVVM · feature modules · BLoC · Cubit · Provider · GetIt · Injectable · Freezed · dartz/Either</td></tr>
    <tr><td><strong>Backend & APIs</strong></td><td>REST · Dio interceptors · retry/backoff · WebSockets · Supabase Auth/Realtime/Storage/RLS · Firebase · Appwrite</td></tr>
    <tr><td><strong>Realtime & media</strong></td><td>ZEGOCLOUD · LiveKit · ZIM · just_audio · audio_session · SVGA/VAP · background_downloader</td></tr>
    <tr><td><strong>Offline & intelligence</strong></td><td>Hive · SQLite · secure storage · ML Kit · Tesseract · TFLite · PDF generation/editing · full-text search</td></tr>
    <tr><td><strong>Release & quality</strong></td><td>Flavors · ProGuard/R8 · Crashlytics · secure environments · isolates · background tasks · IAP · Google Play · App Store</td></tr>
  </table>
</details>

---

## 04 / Experience

<table>
  <tr>
    <td width="28%" valign="top"><sub>JUL 2022 — PRESENT</sub><br /><br /><strong>Flutter Developer</strong><br />Freelance & Contract · Remote</td>
    <td width="72%" valign="top">Designed and shipped 5+ production applications across social audio, marketplaces, document management, and content products—owning architecture, state, backend integration, performance, and release.</td>
  </tr>
  <tr>
    <td width="28%" valign="top"><sub>2022</sub><br /><br /><strong>Android Developer</strong><br />University & Independent</td>
    <td width="72%" valign="top">Built programming-education products with curated learning tracks, an in-app code console, runnable samples, and auto-graded quizzes.</td>
  </tr>
  <tr>
    <td width="28%" valign="top"><sub>2020 — 2022</sub><br /><br /><strong>Computer Engineering</strong><br />University of Aleppo</td>
    <td width="72%" valign="top">Software Engineering track · GPA <strong>82.89%</strong> · Data Structures, Algorithms, OOP, Databases, and Software Engineering.</td>
  </tr>
</table>

### GitHub signal

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Mohamad-Adib-Tawil&amp;theme=github_dark" width="100%" alt="Mohamad's GitHub profile details" />
</div>

<details>
  <summary><strong>Open repository and language statistics</strong></summary>
  <br />
  <div align="center">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Mohamad-Adib-Tawil&amp;theme=github_dark" width="49%" alt="Mohamad's GitHub statistics" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Mohamad-Adib-Tawil&amp;theme=github_dark" width="49%" alt="Repositories by language" />
  </div>
</details>

<br />

<a href="mailto:mohamad.adib.tawil@gmail.com">
  <img src="./assets/footer.svg" alt="Contact Mohamad Adib Tawil to build a mobile product" width="100%" />
</a>

<p align="center">
  <a href="mailto:mohamad.adib.tawil@gmail.com"><strong>Start a conversation</strong></a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/mohamad-adib-tawil-54024b314/"><strong>Connect on LinkedIn</strong></a>
</p>

<p align="center"><sub>Designed as a living engineering portfolio · Built with Markdown, SVG, and real product work</sub></p>
