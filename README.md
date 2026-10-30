<p align="center">
  <img width="100%" src="./assets/banner.svg" alt="Nitin Kumar: Java Full Stack Engineer"/>
</p>

<p align="center">
  <a href="https://github.com/Its-Nitin">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3200&pause=900&color=38BDF8&center=true&vCenter=true&width=760&lines=5%2B+years+shipping+enterprise+software;I+cut+API+response+times+by+35%25;I+build+multi-tenant+SSO+with+Keycloak;I+modernize+legacy+Spring+to+Spring+Boot;Open+to+full-time+roles+%26+freelance+work" alt="Typing intro"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nitin-kumar-k7"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:nitinkumarblb@gmail.com"><img src="https://img.shields.io/badge/Email-Hire%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Based%20in-Delhi%20NCR-1F2937?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location"/>
  <img src="https://img.shields.io/badge/Open%20to-Full--time%20%26%20Freelance-22C55E?style=for-the-badge" alt="Open to work"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Its-Nitin&label=Profile%20views&color=0e75b6&style=flat-square" alt="Profile views"/>
  <img src="https://img.shields.io/badge/Experience-5%2B%20years-38BDF8?style=flat-square" alt="Experience"/>
  <img src="https://img.shields.io/badge/Role-Senior%20Software%20Engineer-A78BFA?style=flat-square" alt="Role"/>
  <img src="https://img.shields.io/badge/Architecture-Microservices-0F766E?style=flat-square" alt="Microservices"/>
</p>

---

## 👨‍💻 About me

```java
public record Engineer(
        String name,
        String role,
        int yearsOfExperience,
        List<String> coreStack,
        List<String> specializations,
        List<String> currentFocus
) {
    public static Engineer nitin() {
        return new Engineer(
            "Nitin Kumar",
            "Senior Software Engineer",
            5,
            List.of("Java", "Spring Boot", "Microservices", "Angular", "TypeScript", "PostgreSQL/Oracle"),
            List.of(
                "Microservices architecture & REST API design",
                "Identity & access management (Keycloak, OAuth2, OIDC)",
                "Legacy-to-modern platform migration",
                "Multi-tenant, multilingual enterprise applications"
            ),
            List.of("Containerization (Docker, Kubernetes)", "System design", "AI-assisted engineering")
        );
    }
}
```

I'm a **Java Full Stack Engineer with 5+ years of experience** building enterprise platforms end to end. On the backend I design and build **Spring Boot microservices and APIs** with strong security and data-access foundations. On the frontend I build **Angular applications** that stay responsive and consistent across languages and devices. I'm most useful on systems that need to be **secure, scalable and maintainable** as they grow.

---

## 🚀 Impact at a glance

<table align="center">
  <tr>
    <td align="center" width="25%"><h2>35%</h2><b>faster API responses</b><br/><sub>Hibernate N+1 fixes, native SQL and execution-plan tuning</sub></td>
    <td align="center" width="25%"><h2>Multi-tenant</h2><b>SSO platform</b><br/><sub>Keycloak with MFA, PKCE and RBAC across applications</sub></td>
    <td align="center" width="25%"><h2>XML → Boot</h2><b>legacy modernization</b><br/><sub>Spring MVC/Servlet moved to annotation-driven Spring Boot</sub></td>
    <td align="center" width="25%"><h2>EN + AR</h2><b>global-ready UIs</b><br/><sub>Angular i18n with full RTL support, web and mobile</sub></td>
  </tr>
  <tr>
    <td align="center"><h2>+30%</h2><b>UI responsiveness</b><br/><sub>RxJS / NgRx state management</sub></td>
    <td align="center"><h2>+25%</h2><b>fresher dashboards</b><br/><sub>Quartz + ShedLock background jobs</sub></td>
    <td align="center"><h2>+20%</h2><b>auth flexibility</b><br/><sub>custom Keycloak provider for user/group queries</sub></td>
    <td align="center"><h2>Audit-ready</h2><b>data history</b><br/><sub>Hibernate Envers for traceable changes</sub></td>
  </tr>
</table>

---

## 🧭 Career journey

```mermaid
timeline
    title Ascent Business Technologies · Gurugram
    2021 : Software Engineer I
         : Spring MVC → Spring Boot migration
         : Secure REST APIs on Hibernate/JPA + Oracle
         : Keycloak-based IAM and RBAC
    2023 : Software Engineer II
         : Multilingual Angular apps (i18n + RTL)
         : RxJS / NgRx performance work
         : Quartz + ShedLock jobs, custom Keycloak provider
    2024 : Senior Software Engineer
         : Hibernate performance (-35% API time)
         : Multi-tenant SSO with MFA and PKCE
         : Individual contributor on API design and security
```

---

## 🔬 Case studies

<details>
<summary><b>⚡ Cutting API response time by 35%</b></summary>

- **Problem:** Slow endpoints in a data-heavy enterprise platform.
- **Diagnosis:** Hibernate N+1 query patterns and queries that didn't use the best execution path.
- **Fix:** Fetch strategy changes, native SQL and `EntityManager` for hot paths, tuning based on execution plans.
- **Result:** **~35% lower API response time**, plus Hibernate Envers for audit without sacrificing throughput.

</details>

<details>
<summary><b>🔐 Multi-tenant SSO with Keycloak</b></summary>

- **Problem:** Several applications needed one secure, consistent way to sign users in.
- **Fix:** Centralized identity on Keycloak with MFA, PKCE and role-based access control, plus a custom provider for advanced user and group queries.
- **Result:** **Multi-tenant SSO**, simpler access management, and more flexible authentication (**~20%**).

</details>

<details>
<summary><b>🏗️ Legacy to Spring Boot</b></summary>

- **Problem:** A Spring MVC / Servlet system held together with XML configuration.
- **Fix:** Built an upgraded Spring Boot platform alongside the legacy one and replaced XML wiring with annotation-driven components.
- **Result:** Simpler dependency management, easier maintenance, and a clear modernization path.

</details>

<details>
<summary><b>🌍 Arabic + English Angular apps</b></summary>

- **Problem:** One product, two languages, two reading directions.
- **Fix:** Angular i18n with full RTL layout support, and RxJS / NgRx state management for speed.
- **Result:** Consistent UX on web and mobile, and **~30% better responsiveness**.

</details>

---

## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,hibernate,maven,angular,ts,rxjs,nextjs,postgres,mysql,oracle,docker,kubernetes,git,postman,idea&perline=8" alt="Skills"/>
</p>

| Area | What I use |
|---|---|
| **Backend** | Java, Spring Boot, Spring Security, REST APIs, Microservices, JPA/Hibernate, Envers, Jakarta migration |
| **Frontend** | Angular (v10–v20), TypeScript, RxJS, NgRx, Reactive Forms, i18n/RTL, Next.js |
| **Security** | Keycloak, OAuth2, PKCE, MFA, JWT, RBAC |
| **Data** | Oracle, MSSQL, MySQL, PostgreSQL, native SQL optimization |
| **Jobs and real time** | Quartz, ShedLock, WebSockets (STOMP) |
| **AI-assisted dev** | Cursor, GitHub Copilot, Augment, Antigravity: faster coding, debugging, tests and docs, with the same quality bar |

---

## 📌 Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Its-Nitin/talkie-time">💬 TalkieTime</a></h3>
      <b>Real-time chat platform</b><br/>
      One-to-one messaging, chat history and live user presence. REST for data, WebSockets (STOMP) for real time, JWT for security.<br/><br/>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/WebSocket-010101?style=flat-square"/>
      <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white"/>
      <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Its-Nitin/church">⛪ Church Website</a></h3>
      <b>Client-style web UI</b><br/>
      A clean, responsive website built for a church, from design to delivery.<br/><br/><br/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
    </td>
  </tr>
</table>

---

## 🧱 How I build

- 📏 **Measure first.** I profile before I optimize, and I keep before-and-after numbers.
- 🔒 **Secure by default.** Authentication, roles and tenancy are designed in, not bolted on.
- 🧩 **Small, reviewable changes.** Easy to read, easy to test, easy to roll back.
- 🤖 **AI as a force multiplier.** I use it for speed, and I own the quality.

---

## 🌱 Currently levelling up

<p align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/System%20Design-0F766E?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AI%20Tooling-7C3AED?style=for-the-badge"/>
</p>

---

## 📊 GitHub snapshot

<p align="center">
  <img width="49%" src="./profile-summary-card-output/tokyonight/3-stats.svg" alt="GitHub stats"/>
  <img width="49%" src="./profile-summary-card-output/tokyonight/2-most-commit-language.svg" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Its-Nitin&theme=tokyonight&hide_border=true" alt="Streak"/>
</p>

---

## 🤝 Let's work together

I'm open to **full-time roles** (Java / Spring / Angular) and **freelance projects** (backend, security, or full-stack).

<p align="center">
  <a href="https://www.linkedin.com/in/nitin-kumar-k7"><img src="https://img.shields.io/badge/Message%20me%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:nitinkumarblb@gmail.com"><img src="https://img.shields.io/badge/Send%20an%20email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center"><i>"I like making slow systems fast and secure systems usable."</i></p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:0E3B4F,100:070B1A&section=footer" alt="footer"/>
