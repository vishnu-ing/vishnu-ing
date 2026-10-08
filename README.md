<img src="https://capsule-render.vercel.app/api?type=slice&color=0:0F172A,100:064E3B&height=180&section=header&text=VISHNU%20KUMAR&fontSize=52&fontColor=A7F3D0&fontAlignY=48&fontAlign=25&desc=full%20stack%20%E2%80%A2%20microservices%20%E2%80%A2%20aws&descSize=16&descAlignY=72&descAlign=25" width="100%" alt="VISHNU KUMAR — full stack · microservices · aws">

```bash
$ whoami
```

```yaml
name:        Vishnu Kumar Ruppa Sridhar
role:        Full Stack Developer · Microservices Engineer
focus:       multi-brand web & mobile platforms, Java microservices, cloud
stack:       React · Ionic · TypeScript  ⇄  Java · Spring Boot · Node.js
shipped:     one codebase → 9 brands → web, Android & iOS
education:   MS Management Information Systems @ University at Buffalo (GPA 4.0)
credentials: AWS Solutions Architect – Associate · AWS Data Engineer – Associate
reachable:   vishnu.rsvk@gmail.com · linkedin.com/in/vishnu-kumar-ruppa-sridhar
```

<p>
  <a href="https://github.com/vishnu-ing"><img src="https://img.shields.io/badge/github-vishnu--ing-0F172A?style=flat-square&logo=github&logoColor=10B981" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/vishnu-kumar-ruppa-sridhar/"><img src="https://img.shields.io/badge/linkedin-vishnu--kumar--ruppa--sridhar-0F172A?style=flat-square&logo=linkedin&logoColor=10B981" alt="LinkedIn"></a>
  <a href="mailto:vishnu.rsvk@gmail.com"><img src="https://img.shields.io/badge/mail-vishnu.rsvk@gmail.com-0F172A?style=flat-square&logo=maildotru&logoColor=10B981" alt="Email"></a>
</p>

---

### &nbsp;❯&nbsp; What I build

<table>
<tr>
<td width="33%" valign="top" align="center">

**Multi-Brand Platforms**

<sub>One React + Ionic + Capacitor codebase that themes itself per brand and ships to web, Android and iOS.</sub>

</td>
<td width="33%" valign="top" align="center">

**Java Microservices**

<sub>Spring Boot and Hibernate services for authentication, workflows and integrations, behind clean REST APIs.</sub>

</td>
<td width="33%" valign="top" align="center">

**Cloud & Data on AWS**

<sub>Containerized services, CI/CD and warehouse pipelines, designed with two AWS Associate certifications behind them.</sub>

</td>
</tr>
</table>

---

### &nbsp;❯&nbsp; How a request flows through my platforms

```mermaid
%%{init: {"theme":"base","themeVariables":{"darkMode":true,"background":"#0F172A","git0":"#10B981","gitBranchLabel0":"#0F172A","primaryColor":"#111827","primaryBorderColor":"#10B981","primaryTextColor":"#E2E8F0","secondaryColor":"#064E3B","secondaryBorderColor":"#34D399","secondaryTextColor":"#ECFDF5","tertiaryColor":"#0B1220","tertiaryBorderColor":"#06B6D4","tertiaryTextColor":"#E2E8F0","mainBkg":"#111827","nodeBorder":"#10B981","clusterBkg":"#0B1220","clusterBorder":"#1E293B","lineColor":"#06B6D4","textColor":"#A7F3D0","edgeLabelBackground":"#0F172A","actorBkg":"#111827","actorBorder":"#10B981","actorTextColor":"#E2E8F0","actorLineColor":"#334155","signalColor":"#06B6D4","signalTextColor":"#A7F3D0","labelBoxBkgColor":"#111827","labelBoxBorderColor":"#10B981","labelTextColor":"#E2E8F0","loopTextColor":"#A7F3D0","noteBkgColor":"#064E3B","noteBorderColor":"#34D399","noteTextColor":"#ECFDF5","activationBkgColor":"#047857","activationBorderColor":"#34D399","sequenceNumberColor":"#0F172A","cScale0":"#064E3B","cScaleLabel0":"#ECFDF5","cScalePeer0":"#34D399","cScale1":"#0E7490","cScaleLabel1":"#ECFDF5","cScalePeer1":"#34D399","cScale2":"#047857","cScaleLabel2":"#ECFDF5","cScalePeer2":"#34D399","cScale3":"#155E75","cScaleLabel3":"#ECFDF5","cScalePeer3":"#34D399","cScale4":"#065F46","cScaleLabel4":"#ECFDF5","cScalePeer4":"#34D399","cScale5":"#0369A1","cScaleLabel5":"#ECFDF5","cScalePeer5":"#34D399","cScale6":"#064E3B","cScaleLabel6":"#ECFDF5","cScalePeer6":"#34D399","cScale7":"#0E7490","cScaleLabel7":"#ECFDF5","cScalePeer7":"#34D399","cScale8":"#047857","cScaleLabel8":"#ECFDF5","cScalePeer8":"#34D399","cScale9":"#155E75","cScaleLabel9":"#ECFDF5","cScalePeer9":"#34D399","cScale10":"#065F46","cScaleLabel10":"#ECFDF5","cScalePeer10":"#34D399","cScale11":"#0369A1","cScaleLabel11":"#ECFDF5","cScalePeer11":"#34D399"}}}%%
sequenceDiagram
    autonumber
    participant U as Client · Web / Android / iOS
    participant T as Brand layer · Redux · Context API
    participant A as Auth · JWT · HTTP-only cookies
    participant S as Services · Spring Boot · Node.js
    participant D as Data · MySQL · MongoDB · Redis
    U->>T: brand resolved → theme, content, feature flags
    T->>A: request with short-lived access token
    A-->>T: silent refresh when the token expires
    A->>S: authenticated REST call
    S->>D: read / write · cache hot paths in Redis
    S-->>U: response · SSR + lazy loading on the web
    Note over U,S: One shared codebase · Docker + CI/CD on AWS
```

---

### &nbsp;❯&nbsp; Engineering principles

> **One codebase, many brands.** Theme, content and features are configuration, not forks. Fifteen repositories became one.

> **Secure by default.** JWT with HTTP-only cookies and token refresh is the baseline for every app, not an extra.

> **Performance is a feature.** SSR, lazy loading and lean APIs show up as faster pages, better SEO and response times cut by up to 60%.

---

### &nbsp;❯&nbsp; Technology ecosystem

```mermaid
%%{init: {"theme":"base","themeVariables":{"darkMode":true,"background":"#0F172A","git0":"#10B981","gitBranchLabel0":"#0F172A","primaryColor":"#111827","primaryBorderColor":"#10B981","primaryTextColor":"#E2E8F0","secondaryColor":"#064E3B","secondaryBorderColor":"#34D399","secondaryTextColor":"#ECFDF5","tertiaryColor":"#0B1220","tertiaryBorderColor":"#06B6D4","tertiaryTextColor":"#E2E8F0","mainBkg":"#111827","nodeBorder":"#10B981","clusterBkg":"#0B1220","clusterBorder":"#1E293B","lineColor":"#06B6D4","textColor":"#A7F3D0","edgeLabelBackground":"#0F172A","actorBkg":"#111827","actorBorder":"#10B981","actorTextColor":"#E2E8F0","actorLineColor":"#334155","signalColor":"#06B6D4","signalTextColor":"#A7F3D0","labelBoxBkgColor":"#111827","labelBoxBorderColor":"#10B981","labelTextColor":"#E2E8F0","loopTextColor":"#A7F3D0","noteBkgColor":"#064E3B","noteBorderColor":"#34D399","noteTextColor":"#ECFDF5","activationBkgColor":"#047857","activationBorderColor":"#34D399","sequenceNumberColor":"#0F172A","cScale0":"#064E3B","cScaleLabel0":"#ECFDF5","cScalePeer0":"#34D399","cScale1":"#0E7490","cScaleLabel1":"#ECFDF5","cScalePeer1":"#34D399","cScale2":"#047857","cScaleLabel2":"#ECFDF5","cScalePeer2":"#34D399","cScale3":"#155E75","cScaleLabel3":"#ECFDF5","cScalePeer3":"#34D399","cScale4":"#065F46","cScaleLabel4":"#ECFDF5","cScalePeer4":"#34D399","cScale5":"#0369A1","cScaleLabel5":"#ECFDF5","cScalePeer5":"#34D399","cScale6":"#064E3B","cScaleLabel6":"#ECFDF5","cScalePeer6":"#34D399","cScale7":"#0E7490","cScaleLabel7":"#ECFDF5","cScalePeer7":"#34D399","cScale8":"#047857","cScaleLabel8":"#ECFDF5","cScalePeer8":"#34D399","cScale9":"#155E75","cScaleLabel9":"#ECFDF5","cScalePeer9":"#34D399","cScale10":"#065F46","cScaleLabel10":"#ECFDF5","cScalePeer10":"#34D399","cScale11":"#0369A1","cScaleLabel11":"#ECFDF5","cScalePeer11":"#34D399"}}}%%
mindmap
  root((Full Stack))
    Frontend
      React
      Next.js
      Angular
      Ionic · Capacitor
      Redux
      Tailwind CSS
    Backend
      Java
      Spring Boot
      Hibernate
      Node.js
      Express
      REST APIs
    Data
      MySQL
      MongoDB
      Redis
      Oracle
      Snowflake
      Power BI · Tableau
    Cloud & DevOps
      AWS
      Docker
      Kubernetes
      Jenkins
      GitHub Actions
    Delivery
      Agile
      JIRA
      Postman
      Figma
```

<sub>Primary languages &nbsp;→&nbsp; <code>TypeScript</code> · <code>JavaScript</code> · <code>Java</code> · <code>Python</code> · <code>SQL</code> &nbsp;&nbsp;·&nbsp;&nbsp; Also in production &nbsp;→&nbsp; <code>Docker</code> · <code>Kubernetes</code> · <code>Jenkins</code> · <code>Git</code> · <code>GitLab</code> · <code>CI/CD</code> · <code>Selenium</code> · <code>OpenAI API</code></sub>

---

### &nbsp;❯&nbsp; Career journey

```mermaid
%%{init: {"theme":"base","themeVariables":{"darkMode":true,"background":"#0F172A","git0":"#10B981","gitBranchLabel0":"#0F172A","primaryColor":"#111827","primaryBorderColor":"#10B981","primaryTextColor":"#E2E8F0","secondaryColor":"#064E3B","secondaryBorderColor":"#34D399","secondaryTextColor":"#ECFDF5","tertiaryColor":"#0B1220","tertiaryBorderColor":"#06B6D4","tertiaryTextColor":"#E2E8F0","mainBkg":"#111827","nodeBorder":"#10B981","clusterBkg":"#0B1220","clusterBorder":"#1E293B","lineColor":"#06B6D4","textColor":"#A7F3D0","edgeLabelBackground":"#0F172A","actorBkg":"#111827","actorBorder":"#10B981","actorTextColor":"#E2E8F0","actorLineColor":"#334155","signalColor":"#06B6D4","signalTextColor":"#A7F3D0","labelBoxBkgColor":"#111827","labelBoxBorderColor":"#10B981","labelTextColor":"#E2E8F0","loopTextColor":"#A7F3D0","noteBkgColor":"#064E3B","noteBorderColor":"#34D399","noteTextColor":"#ECFDF5","activationBkgColor":"#047857","activationBorderColor":"#34D399","sequenceNumberColor":"#0F172A","cScale0":"#064E3B","cScaleLabel0":"#ECFDF5","cScalePeer0":"#34D399","cScale1":"#0E7490","cScaleLabel1":"#ECFDF5","cScalePeer1":"#34D399","cScale2":"#047857","cScaleLabel2":"#ECFDF5","cScalePeer2":"#34D399","cScale3":"#155E75","cScaleLabel3":"#ECFDF5","cScalePeer3":"#34D399","cScale4":"#065F46","cScaleLabel4":"#ECFDF5","cScalePeer4":"#34D399","cScale5":"#0369A1","cScaleLabel5":"#ECFDF5","cScalePeer5":"#34D399","cScale6":"#064E3B","cScaleLabel6":"#ECFDF5","cScalePeer6":"#34D399","cScale7":"#0E7490","cScaleLabel7":"#ECFDF5","cScalePeer7":"#34D399","cScale8":"#047857","cScaleLabel8":"#ECFDF5","cScalePeer8":"#34D399","cScale9":"#155E75","cScaleLabel9":"#ECFDF5","cScalePeer9":"#34D399","cScale10":"#065F46","cScaleLabel10":"#ECFDF5","cScalePeer10":"#34D399","cScale11":"#0369A1","cScaleLabel11":"#ECFDF5","cScalePeer11":"#34D399"}}}%%
timeline
    2019 : B.E. Electronics & Communication · Anna University : Ideas2IT — Software Engineer
    2021 : Java REST APIs · microservices : up to 60% faster client responses
    2022 : Senior Software Engineer : 15 repos → 1 multi-brand PWA
    2023 : AWS Solutions Architect – Associate
    2025 : MS MIS · University at Buffalo · GPA 4.0 : AWS Data Engineer – Associate : Find Me LLC — Full Stack Developer
```

| Period | Company | Role | Key impact |
|:--|:--|:--|:--|
| **Aug 2025 — Nov 2025** | Find Me LLC | Full Stack Developer | React · Next.js · Node.js · MongoDB features · microservice-style REST APIs · faster auth and SSR |
| **Jul 2022 — May 2024** | Ideas2IT Technology Services | Senior Software Engineer | 15 repos → 1 PWA · 9 brands on web, Android & iOS · 70% easier maintenance · 50% faster deploys · led a team of 4 |
| **2019 — Jul 2022** | Ideas2IT Technology Services | Software Engineer | Java REST APIs · up to 60% faster client responses · microservices with automated CI/CD |

---

### ❯ Featured engineering projects

<details open>
<summary><b>E-Commerce Microservices Platform</b> — distributed commerce backend with cloud-native architecture</summary>
<br>

Built a Spring Boot and Spring Cloud based e-commerce backend organized into independent services for users, products, favourites, orders, shipping and payments. The system includes service discovery, centralized configuration, an API gateway and a dedicated authentication/authorization service. Docker Compose coordinates the service landscape and Kafka-based messaging, while the repository also includes Kubernetes configuration, observability through Actuator, Prometheus and Zipkin, resilience patterns with Resilience4j, and integration testing with Testcontainers.

```mermaid
%%{init: {"theme":"base","themeVariables":{"darkMode":true,"background":"#0F172A","primaryColor":"#111827","primaryBorderColor":"#10B981","primaryTextColor":"#E2E8F0","secondaryColor":"#064E3B","secondaryBorderColor":"#34D399","secondaryTextColor":"#ECFDF5","tertiaryColor":"#0B1220","tertiaryBorderColor":"#06B6D4","tertiaryTextColor":"#E2E8F0","mainBkg":"#111827","nodeBorder":"#10B981","clusterBkg":"#0B1220","clusterBorder":"#1E293B","lineColor":"#06B6D4","textColor":"#A7F3D0","edgeLabelBackground":"#0F172A"}}%%
flowchart LR
    C["Client"] --> G["API Gateway"]
    G --> D["Service Discovery"]
    G --> A["Auth / Proxy"]
    G --> U["User Service"]
    G --> P["Product Service"]
    G --> F["Favourite Service"]
    G --> O["Order Service"]
    G --> S["Shipping Service"]
    G --> PY["Payment Service"]
    O --> K["Kafka"]
    G --> M["Actuator · Prometheus · Zipkin"]

    style G fill:#064E3B,stroke:#34D399,color:#ECFDF5
    style K fill:#164E63,stroke:#06B6D4,color:#ECFDF5
```

<sub>`Java 11` `Spring Boot` `Spring Cloud` `Microservices` `REST APIs` `Docker` `Kubernetes` `Kafka` `Resilience4j` `Prometheus` `Zipkin` `Testcontainers`</sub>

</details>

<details>
<summary><b>Spring Boot Microservices Banking Application</b> — modular banking platform with service discovery and API gateway</summary>
<br>

Developed a modular banking backend using Spring Boot, Spring Data JPA, Spring Cloud and Spring Security. The application separates user management, account operations, fund transfers and transaction processing into independent services, with a Service Registry handling service discovery and an API Gateway providing a centralized entry point for the APIs. The repository also includes a sequence generator, documentation and a Postman collection for API testing.

```mermaid
%%{init: {"theme":"base","themeVariables":{"darkMode":true,"background":"#0F172A","primaryColor":"#111827","primaryBorderColor":"#10B981","primaryTextColor":"#E2E8F0","secondaryColor":"#064E3B","secondaryBorderColor":"#34D399","secondaryTextColor":"#ECFDF5","tertiaryColor":"#0B1220","tertiaryBorderColor":"#06B6D4","tertiaryTextColor":"#E2E8F0","mainBkg":"#111827","nodeBorder":"#10B981","clusterBkg":"#0B1220","clusterBorder":"#1E293B","lineColor":"#06B6D4","textColor":"#A7F3D0","edgeLabelBackground":"#0F172A"}}%%
flowchart LR
    C["Banking Client"] --> G["API Gateway"]
    G --> R["Service Registry"]
    G --> U["User Service"]
    G --> A["Account Service"]
    G --> F["Fund Transfer"]
    G --> T["Transaction Service"]
    A --> Q["Sequence Generator"]
    U & A & F & T --> DB[("Service Data")]

    style G fill:#064E3B,stroke:#34D399,color:#ECFDF5
    style R fill:#164E63,stroke:#06B6D4,color:#ECFDF5
```

<sub>`Java` `Spring Boot` `Spring Cloud` `Spring Data JPA` `Spring Security` `Maven` `REST APIs` `Microservices` `API Gateway` `Service Discovery`</sub>

</details>

<details>
<summary><b>Centralized Asset Management & Compliance Dashboard</b> — centralized security and compliance monitoring</summary>
<br>

Built a centralized asset-management dashboard for monitoring security and compliance across virtualized Linux and Windows environments. The system includes security assessment, CIS Benchmark compliance checks and Data Loss Prevention capabilities, with Vagrant used to provision Ubuntu Desktop, Ubuntu Server, Windows 10 and Windows 11 environments. A Node.js backend and responsive HTML, CSS and JavaScript dashboard provide centralized visibility into asset security, compliance and DLP status.

```mermaid
%%{init: {"theme":"base","themeVariables":{"darkMode":true,"background":"#0F172A","primaryColor":"#111827","primaryBorderColor":"#10B981","primaryTextColor":"#E2E8F0","secondaryColor":"#064E3B","secondaryBorderColor":"#34D399","secondaryTextColor":"#ECFDF5","tertiaryColor":"#0B1220","tertiaryBorderColor":"#06B6D4","tertiaryTextColor":"#E2E8F0","mainBkg":"#111827","nodeBorder":"#10B981","clusterBkg":"#0B1220","clusterBorder":"#1E293B","lineColor":"#06B6D4","textColor":"#A7F3D0","edgeLabelBackground":"#0F172A"}}%%
flowchart LR
    L["Ubuntu Desktop"] --> A["Centralized Asset Management"]
    LS["Ubuntu Server"] --> A
    W10["Windows 10"] --> A
    W11["Windows 11"] --> A

    A --> S["Security Assessment"]
    A --> C["CIS Compliance"]
    A --> D["Data Loss Prevention"]

    S & C & D --> API["Node.js"]
    API --> UI["Web Dashboard"]

    style A fill:#064E3B,stroke:#34D399,color:#ECFDF5
    style UI fill:#164E63,stroke:#06B6D4,color:#ECFDF5
```

<sub>`Node.js` `JavaScript` `HTML` `CSS` `Vagrant` `Linux` `Windows` `CIS Benchmarks` `Security Assessment` `DLP`</sub>

</details>

<details>
<summary><b>Online Banking Full-Stack Application</b> — React and Redux banking interface backed by Spring</summary>
<br>

Built a single-page online banking frontend using React and Redux, integrated with a Java Spring REST API. The application supports user registration and login, account history, opening new accounts, transfers between accounts, deposits, withdrawals and payments. Redux manages application state across components, while Redux Thunk handles asynchronous operations and Material UI provides the interface components. The application also includes account-flow visualizations and integrates with the backend through authenticated API communication.

```mermaid
%%{init: {"theme":"base","themeVariables":{"darkMode":true,"background":"#0F172A","primaryColor":"#111827","primaryBorderColor":"#10B981","primaryTextColor":"#E2E8F0","secondaryColor":"#064E3B","secondaryBorderColor":"#34D399","secondaryTextColor":"#ECFDF5","tertiaryColor":"#0B1220","tertiaryBorderColor":"#06B6D4","tertiaryTextColor":"#E2E8F0","mainBkg":"#111827","nodeBorder":"#10B981","clusterBkg":"#0B1220","clusterBorder":"#1E293B","lineColor":"#06B6D4","textColor":"#A7F3D0","edgeLabelBackground":"#0F172A"}}%%
flowchart LR
    U["User"] --> R["React SPA"]
    R --> X["Redux Store"]
    X --> T["Redux Thunk"]
    R --> API["Spring REST API"]
    API --> AU["Authentication"]
    API --> AC["Account Operations"]
    API --> TR["Transactions"]
    API --> FT["Fund Transfers"]
    API --> DB[("MySQL")]

    style R fill:#064E3B,stroke:#34D399,color:#ECFDF5
    style API fill:#164E63,stroke:#06B6D4,color:#ECFDF5
```

<sub>`React` `Redux` `Redux Thunk` `React Router` `Material UI` `JavaScript` `Spring Boot` `REST API` `JWT` `Cookies` `MySQL`</sub>

</details>

<details>
<summary><b>Distributed Bookstore Platform</b> — multi-service application with catalog, orders, billing and payments</summary>
<br>

Structured a distributed bookstore application into independent services covering account management, catalog, ordering, billing and payments. The repository includes a dedicated API Gateway and Eureka discovery service alongside a React frontend, with separate components for monitoring and observability. The service-oriented structure separates core business capabilities while allowing the frontend to consume the distributed backend through a centralized gateway.

```mermaid
%%{init: {"theme":"base","themeVariables":{"darkMode":true,"background":"#0F172A","primaryColor":"#111827","primaryBorderColor":"#10B981","primaryTextColor":"#E2E8F0","secondaryColor":"#064E3B","secondaryBorderColor":"#34D399","secondaryTextColor":"#ECFDF5","tertiaryColor":"#0B1220","tertiaryBorderColor":"#06B6D4","tertiaryTextColor":"#E2E8F0","mainBkg":"#111827","nodeBorder":"#10B981","clusterBkg":"#0B1220","clusterBorder":"#1E293B","lineColor":"#06B6D4","textColor":"#A7F3D0","edgeLabelBackground":"#0F172A"}}%%
flowchart LR
    U["React Frontend"] --> G["API Gateway"]
    G --> E["Eureka Discovery"]
    G --> A["Account Service"]
    G --> C["Catalog Service"]
    G --> O["Order Service"]
    G --> B["Billing Service"]
    G --> P["Payment Service"]

    M["Prometheus / Grafana"] --> G
    M --> A
    M --> C
    M --> O
    M --> B
    M --> P

    style G fill:#064E3B,stroke:#34D399,color:#ECFDF5
    style E fill:#164E63,stroke:#06B6D4,color:#ECFDF5
```

<sub>`Java` `Spring Boot` `Spring Cloud` `Microservices` `React` `API Gateway` `Eureka` `REST APIs` `Prometheus` `Grafana`</sub>

</details>

---

### &nbsp;❯&nbsp; Impact at a glance

<table>
<tr>
<td align="center" width="20%"><b>15 → 1</b><br><sub>repos consolidated</sub></td>
<td align="center" width="20%"><b>9</b><br><sub>brands on one codebase</sub></td>
<td align="center" width="20%"><b>70%</b><br><sub>easier maintenance</sub></td>
<td align="center" width="20%"><b>50%</b><br><sub>faster deployments</sub></td>
<td align="center" width="20%"><b>60%</b><br><sub>faster client responses</sub></td>
</tr>
</table>

---

### &nbsp;❯&nbsp; Credentials

<p>
  <a href="https://www.credly.com/badges/e5ba4d04-1c03-4083-b302-9a333f105dc4"><img src="https://images.credly.com/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" width="96" alt="AWS Certified Solutions Architect – Associate"></a>
  &nbsp;
  <a href="https://www.credly.com/badges/f42ceef1-91b4-4af3-acda-124766242d70"><img src="https://images.credly.com/images/e5c85d7f-4e50-431e-b5af-fa9d9b0596e7/image.png" width="96" alt="AWS Certified Data Engineer – Associate"></a>
</p>

| Year | Credential | Issuer |
|:--|:--|:--|
| 2025 | [AWS Certified Data Engineer – Associate](https://www.credly.com/badges/f42ceef1-91b4-4af3-acda-124766242d70) | Amazon Web Services |
| 2025 | MS Management Information Systems · GPA 4.0 | University at Buffalo, SUNY |
| 2024 | [Snowflake Data Warehousing Workshop](https://achieve.snowflake.com/deb625a0-411a-4d9c-a1f0-7f72fb122e75#acc.wFYqZ5r7) | Snowflake |
| 2024 | [Tableau: Connect and Transform Data](https://www.credly.com/badges/6fc17ca5-661d-4593-8f47-8711dc24d659/public_url) · [Create Views and Dashboards](https://www.credly.com/badges/b55846f4-7a23-4a72-a884-68fae744f805/public_url) | Tableau |
| 2023 | [AWS Certified Solutions Architect – Associate](https://www.credly.com/badges/e5ba4d04-1c03-4083-b302-9a333f105dc4) | Amazon Web Services |

---

### &nbsp;❯&nbsp; GitHub

<!-- animated contribution graph + stats card, built from real data.
     regenerated daily by .github/workflows/update-profile-art.yml
     (scripts/fetch_contributions.py → render_heatmap_svg.py → render_stats_svg.py) -->

<div align="center">

<h3><code>vishnu@github ~ $ ./contributions.sh</code></h3>

<img src="./assets/contrib-heatmap.svg" width="860" alt="vishnu-ing's GitHub contribution graph — auto-refreshed daily">

<br>
<br>

<h3><code>vishnu@github ~ $ ./stats.sh</code></h3>

<img src="./assets/stats.svg" width="860" alt="vishnu-ing's streaks, totals and contributions per month — auto-refreshed daily">

</div>

---

### &nbsp;❯&nbsp; Currently exploring

```text
→ event-driven services on AWS (Lambda · EventBridge · SQS)
→ cloud data warehousing with Snowflake alongside app backends
→ LLM features inside everyday product workflows
```

---

<div align="center">

```bash
$ reach me
→ email     vishnu.rsvk@gmail.com
→ linkedin  linkedin.com/in/vishnu-kumar-ruppa-sridhar
→ github    github.com/vishnu-ing
```

<sub>Open to full stack, microservices and cloud engineering conversations.</sub>

</div>
