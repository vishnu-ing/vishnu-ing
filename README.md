<img src="https://capsule-render.vercel.app/api?type=slice&color=0:0F172A,100:064E3B&height=180&section=header&text=VISHNU%20KUMAR&fontSize=52&fontColor=A7F3D0&fontAlignY=48&fontAlign=25&desc=AI%20software%20engineer%20%E2%80%A2%20LLM%20apps%20%E2%80%A2%20full%20stack%20%E2%80%A2%20AWS&descSize=16&descAlignY=72&descAlign=25" width="100%" alt="VISHNU KUMAR — AI software engineer · LLM apps · full stack · AWS">

```bash
$ whoami
```

```yaml
name:        Vishnu Kumar Ruppa Sridhar
role:        AI Software Engineer · building LLM-powered products
focus:       agents · RAG · tool calling, plus the production plumbing around them
ai:          OpenAI · Claude · Llama · LangChain · LangGraph · prompt engineering
background:  6+ yrs full stack · React · Angular · Node.js · Java/Spring Boot · AWS
shipped:     one codebase → 9 brands → web, Android & iOS
education:   MS Management Information Systems @ University at Buffalo (GPA 4.0)
credentials: AWS Data Engineer – Associate · AWS Solutions Architect – Associate (expired)
reachable:   vishnu.rsvk@gmail.com · linkedin.com/in/vishnu-kumar-rs · vishnukumar.me
```

<p>
  <a href="https://github.com/vishnu-ing"><img src="https://img.shields.io/badge/github-vishnu--ing-0F172A?style=flat-square&logo=github&logoColor=10B981" alt="GitHub"></a>
  <a href="https://www.linkedin.com/in/vishnu-kumar-rs/"><img src="https://img.shields.io/badge/linkedin-vishnu--kumar--rs-0F172A?style=flat-square&logo=linkedin&logoColor=10B981" alt="LinkedIn"></a>
  <a href="https://vishnukumar.me/"><img src="https://img.shields.io/badge/web-vishnukumar.me-0F172A?style=flat-square&logo=googlechrome&logoColor=10B981" alt="Portfolio"></a>
  <a href="mailto:vishnu.rsvk@gmail.com"><img src="https://img.shields.io/badge/mail-vishnu.rsvk@gmail.com-0F172A?style=flat-square&logo=maildotru&logoColor=10B981" alt="Email"></a>
</p>

---

### &nbsp;❯&nbsp; What I build

<table>
<tr>
<td width="25%" valign="top" align="center">

**LLM-Powered Features**

<sub>LLM agents, RAG and tool calling built into full-stack apps with OpenAI, Claude, LangChain and LangGraph.</sub>

</td>
<td width="25%" valign="top" align="center">

**Multi-Brand Platforms**

<sub>One React + Ionic + Capacitor codebase that themes itself per brand and ships to web, Android and iOS.</sub>

</td>
<td width="25%" valign="top" align="center">

**Java Microservices**

<sub>Spring Boot and Hibernate services for authentication, workflows and integrations, behind clean REST APIs.</sub>

</td>
<td width="25%" valign="top" align="center">

**Cloud & Data on AWS**

<sub>Containerized services, CI/CD and warehouse pipelines, backed by an AWS Data Engineer certification.</sub>

</td>
</tr>
</table>

---

### &nbsp;❯&nbsp; How I ship an LLM feature

```mermaid
%%{init: {"theme":"base","themeVariables":{"darkMode":true,"background":"#0F172A","git0":"#10B981","gitBranchLabel0":"#0F172A","primaryColor":"#111827","primaryBorderColor":"#10B981","primaryTextColor":"#E2E8F0","secondaryColor":"#064E3B","secondaryBorderColor":"#34D399","secondaryTextColor":"#ECFDF5","tertiaryColor":"#0B1220","tertiaryBorderColor":"#06B6D4","tertiaryTextColor":"#E2E8F0","mainBkg":"#111827","nodeBorder":"#10B981","clusterBkg":"#0B1220","clusterBorder":"#1E293B","lineColor":"#06B6D4","textColor":"#A7F3D0","edgeLabelBackground":"#0F172A","actorBkg":"#111827","actorBorder":"#10B981","actorTextColor":"#E2E8F0","actorLineColor":"#334155","signalColor":"#06B6D4","signalTextColor":"#A7F3D0","labelBoxBkgColor":"#111827","labelBoxBorderColor":"#10B981","labelTextColor":"#E2E8F0","loopTextColor":"#A7F3D0","noteBkgColor":"#064E3B","noteBorderColor":"#34D399","noteTextColor":"#ECFDF5","activationBkgColor":"#047857","activationBorderColor":"#34D399","sequenceNumberColor":"#0F172A","cScale0":"#064E3B","cScaleLabel0":"#ECFDF5","cScalePeer0":"#34D399","cScale1":"#0E7490","cScaleLabel1":"#ECFDF5","cScalePeer1":"#34D399","cScale2":"#047857","cScaleLabel2":"#ECFDF5","cScalePeer2":"#34D399","cScale3":"#155E75","cScaleLabel3":"#ECFDF5","cScalePeer3":"#34D399","cScale4":"#065F46","cScaleLabel4":"#ECFDF5","cScalePeer4":"#34D399","cScale5":"#0369A1","cScaleLabel5":"#ECFDF5","cScalePeer5":"#34D399","cScale6":"#064E3B","cScaleLabel6":"#ECFDF5","cScalePeer6":"#34D399","cScale7":"#0E7490","cScaleLabel7":"#ECFDF5","cScalePeer7":"#34D399","cScale8":"#047857","cScaleLabel8":"#ECFDF5","cScalePeer8":"#34D399","cScale9":"#155E75","cScaleLabel9":"#ECFDF5","cScalePeer9":"#34D399","cScale10":"#065F46","cScaleLabel10":"#ECFDF5","cScalePeer10":"#34D399","cScale11":"#0369A1","cScaleLabel11":"#ECFDF5","cScalePeer11":"#34D399"}}}%%
sequenceDiagram
    autonumber
    participant U as User · React / Next.js
    participant A as API · Node.js / Spring Boot
    participant O as Agent · LangGraph
    participant R as Retrieval · vector store
    participant M as LLM · OpenAI / Claude / Llama
    U->>A: request · authenticated, rate-limited
    A->>O: task + user context
    O->>R: fetch grounding documents
    R-->>O: top-k chunks
    O->>M: prompt + context + tool schema
    M-->>O: answer or tool call
    O-->>A: validated, structured result
    A-->>U: streamed response
    Note over A,M: timeouts · fallbacks · logging and evals on every call
```

---

### &nbsp;❯&nbsp; The full-stack foundation: how a request flows through my platforms

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

> **Treat the model as an unreliable dependency.** Ground it with retrieval, validate its output, set timeouts and fallbacks, and measure quality with evals instead of vibes.

> **One codebase, many brands.** Theme, content and features are configuration, not forks. Fifteen repositories became one.

> **Secure by default.** JWT with HTTP-only cookies and token refresh is the baseline for every app, not an extra.

> **Performance is a feature.** SSR, lazy loading and lean APIs show up as faster pages, better SEO and response times cut by up to 60%.

---

### &nbsp;❯&nbsp; Technology ecosystem

```mermaid
%%{init: {"theme":"base","themeVariables":{"darkMode":true,"background":"#0F172A","git0":"#10B981","gitBranchLabel0":"#0F172A","primaryColor":"#111827","primaryBorderColor":"#10B981","primaryTextColor":"#E2E8F0","secondaryColor":"#064E3B","secondaryBorderColor":"#34D399","secondaryTextColor":"#ECFDF5","tertiaryColor":"#0B1220","tertiaryBorderColor":"#06B6D4","tertiaryTextColor":"#E2E8F0","mainBkg":"#111827","nodeBorder":"#10B981","clusterBkg":"#0B1220","clusterBorder":"#1E293B","lineColor":"#06B6D4","textColor":"#A7F3D0","edgeLabelBackground":"#0F172A","actorBkg":"#111827","actorBorder":"#10B981","actorTextColor":"#E2E8F0","actorLineColor":"#334155","signalColor":"#06B6D4","signalTextColor":"#A7F3D0","labelBoxBkgColor":"#111827","labelBoxBorderColor":"#10B981","labelTextColor":"#E2E8F0","loopTextColor":"#A7F3D0","noteBkgColor":"#064E3B","noteBorderColor":"#34D399","noteTextColor":"#ECFDF5","activationBkgColor":"#047857","activationBorderColor":"#34D399","sequenceNumberColor":"#0F172A","cScale0":"#064E3B","cScaleLabel0":"#ECFDF5","cScalePeer0":"#34D399","cScale1":"#0E7490","cScaleLabel1":"#ECFDF5","cScalePeer1":"#34D399","cScale2":"#047857","cScaleLabel2":"#ECFDF5","cScalePeer2":"#34D399","cScale3":"#155E75","cScaleLabel3":"#ECFDF5","cScalePeer3":"#34D399","cScale4":"#065F46","cScaleLabel4":"#ECFDF5","cScalePeer4":"#34D399","cScale5":"#0369A1","cScaleLabel5":"#ECFDF5","cScalePeer5":"#34D399","cScale6":"#064E3B","cScaleLabel6":"#ECFDF5","cScalePeer6":"#34D399","cScale7":"#0E7490","cScaleLabel7":"#ECFDF5","cScalePeer7":"#34D399","cScale8":"#047857","cScaleLabel8":"#ECFDF5","cScalePeer8":"#34D399","cScale9":"#155E75","cScaleLabel9":"#ECFDF5","cScalePeer9":"#34D399","cScale10":"#065F46","cScaleLabel10":"#ECFDF5","cScalePeer10":"#34D399","cScale11":"#0369A1","cScaleLabel11":"#ECFDF5","cScalePeer11":"#34D399"}}}%%
mindmap
  root((AI + Full Stack))
    AI & GenAI
      LLMs · RAG
      Agentic AI
      OpenAI · Claude
      LangChain · LangGraph
      Prompt Engineering
      GitHub Copilot
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
    2019 : B.E. Electronics & Communication · Anna University : Ideas2IT — Senior Software Engineer
    2023 : AWS Solutions Architect – Associate
    Jan 2025 : Rupp Pfalzgraf — Full Stack Developer
    2025 : MS MIS · University at Buffalo · GPA 4.0 : AWS Data Engineer – Associate
    Aug 2025 : Find Me LLC — Full Stack Developer
    Nov 2025 : First Citizens Bank via BeaconFire — Full Stack Developer · present
    2026 : Focus → AI Software Engineering : LLM apps · RAG · agents
```

| Period | Company | Role | Key impact |
|:--|:--|:--|:--|
| **Nov 2025 — now** | First Citizens Bank · via BeaconFire | Full Stack Developer | 10+ app pages migrated off legacy SVB branding · SSO & identity hardening · 18 story points vs 10 planned · JWT + OAuth 2.0 |
| **Aug 2025 — Nov 2025** | Find Me LLC | Full Stack Developer | Next.js · Node.js · MongoDB features · Redux Toolkit state · HTTP-only cookie auth · SSR & SEO performance |
| **Jan 2025 — Jun 2025** | Rupp Pfalzgraf | Full Stack Developer | Angular KPI dashboard for C-suite · digitized performance reviews · RxJS + REST APIs |
| **Jun 2019 — May 2024** | Ideas2IT Technology Services | Senior Software Engineer | One codebase → 9 brands on web, Android & iOS · CircleCI CI/CD · Outstanding Performance award, 2 years running |

<details>
<summary><b>Full Stack Developer · First Citizens Bank through BeaconFire</b> &nbsp;—&nbsp; Nov 2025 – present</summary>

<br>

- Modernized more than 10 application pages and shared UI components using React, TypeScript, Node.js and MongoDB to replace legacy SVB branding with the First Citizens experience and support scheduled releases for product and engineering stakeholders.
- Applied approved AI-assisted development tools such as GitHub Copilot to support code exploration, documentation and development productivity while keeping engineering workflows aligned with enterprise development practices.
- Strengthened identity-related repositories and SSO workflows by coordinating security findings, authentication issues and cross-team production dependencies to improve release stability for application, security and platform teams.
- Resolved requirements and product-discovery gaps involving legacy URLs, content changes and component ownership to reduce late-stage ambiguity and improve release readiness across engineering and product teams.
- Delivered approximately 18 story points in a two-week sprint against a planned capacity of 10 by managing competing priorities and cross-team dependencies to meet release and code-freeze commitments.
- Integrated Java and Spring Boot backend services with React-based frontend workflows to support enterprise application functionality and maintain clear separation between presentation, business and integration layers.
- Secured authentication flows with JWT-based access tokens and OAuth 2.0 authorization patterns to protect API resources, standardize session handling and support enterprise identity requirements.
- Improved production support by analyzing application logs, monitoring signals and incident patterns to reduce mean time to resolution (MTTR) for authentication and release-related incidents and strengthen operational reliability for application owners.
- Containerized application workloads with Docker and Kubernetes and supported AWS-based deployment patterns to standardize runtime environments and improve consistency across development and production workflows.

<sub>`React` `TypeScript` `Node.js` `MongoDB` `Java` `Spring Boot` `JWT` `OAuth 2.0` `SSO` `Docker` `Kubernetes` `AWS` `GitHub Copilot`</sub>

</details>

<details>
<summary><b>Full Stack Developer · Find Me LLC</b> &nbsp;—&nbsp; Aug 2025 – Nov 2025</summary>

<br>

- Engineered full-stack features with Next.js, React, TypeScript, Node.js, Express and MongoDB to support application workflows through reusable frontend components and REST-based backend services.
- Reworked client and server state management with Redux Toolkit to provide predictable data flows across Next.js and React applications and simplify application behavior for development teams.
- Hardened authentication by implementing HTTP-only cookies and token refresh workflows with Next.js SSR to improve session security and application performance.
- Optimized application delivery through server-side rendering, static generation, lazy loading and structured sitemaps to improve initial page performance and strengthen SEO-oriented user experiences.
- Built responsive mobile-first interfaces with reusable carousels, tabs, modals and dynamic forms to create consistent user experiences across application workflows.
- Secured API communication with JWT-based authentication and Axios interceptors to manage authorization headers consistently across protected requests.

<sub>`Next.js` `React` `TypeScript` `Node.js` `Express` `MongoDB` `Redux Toolkit` `JWT` `Axios` `SSR`</sub>

</details>

<details>
<summary><b>Full Stack Developer · Rupp Pfalzgraf</b> &nbsp;—&nbsp; Jan 2025 – Jun 2025</summary>

<br>

- Developed an Angular and TypeScript performance dashboard around 4 core KPIs including Revenue per Customer, Total Compensation, Billable Hours and Realization Rate to provide C-suite leadership with a centralized view of business performance.
- Digitized performance review workflows using Angular Material, RxJS and REST APIs to replace fragmented manual processes with centralized dashboards and simplify review activities for managers and administrative stakeholders.
- Structured reusable Angular components and RxJS data flows to standardize API-driven updates and improve frontend maintainability across reporting and performance-management workflows.
- Integrated RESTful backend services with Angular dashboards to support consistent retrieval and presentation of business data for leadership reporting and internal application workflows.
- Refined responsive interfaces using TypeScript, JavaScript, HTML5 and CSS3 to improve navigation and usability across professional-services applications while maintaining reusable frontend patterns.
- Validated frontend and API integrations with Postman, Git-based development and defect analysis to identify integration issues earlier and improve release readiness for business stakeholders.
- Coordinated requirements, code reviews and Agile delivery activities with product and development teams to align dashboard enhancements with stakeholder expectations throughout the engagement.

<sub>`Angular` `TypeScript` `Angular Material` `RxJS` `REST APIs` `HTML5` `CSS3` `Postman` `Agile`</sub>

</details>

<details>
<summary><b>Senior Software Engineer · Ideas2IT Technology Services</b> &nbsp;—&nbsp; Jun 2019 – May 2024</summary>

<br>

- Engineered a hybrid multi-brand application platform using Node.js, Express, MongoDB, React, TypeScript and Ionic to deliver web, Android and iOS applications from a shared codebase for 9 brands, reducing duplicated implementation across product teams.
- Centralized dynamic theming, content, assets and API integrations through React Context API and Redux Toolkit to create reusable application patterns and support consistent promotions and feature rollouts across 9 brands.
- Designed reusable Node.js and Express REST services to separate business logic from client applications and establish consistent API contracts for customer-facing features and third-party integrations.
- Automated development and production deployments through CircleCI and CI/CD pipelines to standardize release execution, reduce manual deployment effort and improve delivery reliability across application environments.
- Integrated geolocation, latitude/longitude-based search and service discovery workflows across 3 application platforms to support location-aware customer journeys and reusable search capabilities.
- Implemented appointment push notifications and coupons/rewards workflows to connect customer interactions with transactional services and engagement features while maintaining reusable business logic across supported brands.
- Earned an Outstanding Performance for Contribution to the Organization award for 2 consecutive years through consistent delivery of cross-platform engineering initiatives and product enhancements.

<sub>`React` `TypeScript` `Ionic` `Node.js` `Express` `MongoDB` `Redux Toolkit` `Context API` `CircleCI` `CI/CD`</sub>

</details>

---

### ❯ Featured engineering projects

<details open>
<summary><b>Agentic AI</b> &nbsp;—&nbsp; tool-using Q&amp;A agent on Llama 3.2</summary>

<br>

AI-powered Q&A agent built with Python and Streamlit. A ReAct agent on **Llama 3.2** decides when to call tools, using a math **FunctionTool** for real-time calculations and the **DuckDuckGo API** for live web search, then composes the answer.

```mermaid
%%{init: {"theme":"base","themeVariables":{"darkMode":true,"background":"#0F172A","git0":"#10B981","gitBranchLabel0":"#0F172A","primaryColor":"#111827","primaryBorderColor":"#10B981","primaryTextColor":"#E2E8F0","secondaryColor":"#064E3B","secondaryBorderColor":"#34D399","secondaryTextColor":"#ECFDF5","tertiaryColor":"#0B1220","tertiaryBorderColor":"#06B6D4","tertiaryTextColor":"#E2E8F0","mainBkg":"#111827","nodeBorder":"#10B981","clusterBkg":"#0B1220","clusterBorder":"#1E293B","lineColor":"#06B6D4","textColor":"#A7F3D0","edgeLabelBackground":"#0F172A","actorBkg":"#111827","actorBorder":"#10B981","actorTextColor":"#E2E8F0","actorLineColor":"#334155","signalColor":"#06B6D4","signalTextColor":"#A7F3D0","labelBoxBkgColor":"#111827","labelBoxBorderColor":"#10B981","labelTextColor":"#E2E8F0","loopTextColor":"#A7F3D0","noteBkgColor":"#064E3B","noteBorderColor":"#34D399","noteTextColor":"#ECFDF5","activationBkgColor":"#047857","activationBorderColor":"#34D399","sequenceNumberColor":"#0F172A","cScale0":"#064E3B","cScaleLabel0":"#ECFDF5","cScalePeer0":"#34D399","cScale1":"#0E7490","cScaleLabel1":"#ECFDF5","cScalePeer1":"#34D399","cScale2":"#047857","cScaleLabel2":"#ECFDF5","cScalePeer2":"#34D399","cScale3":"#155E75","cScaleLabel3":"#ECFDF5","cScalePeer3":"#34D399","cScale4":"#065F46","cScaleLabel4":"#ECFDF5","cScalePeer4":"#34D399","cScale5":"#0369A1","cScaleLabel5":"#ECFDF5","cScalePeer5":"#34D399","cScale6":"#064E3B","cScaleLabel6":"#ECFDF5","cScalePeer6":"#34D399","cScale7":"#0E7490","cScaleLabel7":"#ECFDF5","cScalePeer7":"#34D399","cScale8":"#047857","cScaleLabel8":"#ECFDF5","cScalePeer8":"#34D399","cScale9":"#155E75","cScaleLabel9":"#ECFDF5","cScalePeer9":"#34D399","cScale10":"#065F46","cScaleLabel10":"#ECFDF5","cScalePeer10":"#34D399","cScale11":"#0369A1","cScaleLabel11":"#ECFDF5","cScalePeer11":"#34D399"}}}%%
flowchart LR
    Q["User question<br>Streamlit"] --> R["ReAct agent<br>Llama 3.2"]
    R -->|reason| R
    R --> M["FunctionTool<br>math"]
    R --> W["DuckDuckGo<br>web search"]
    M & W --> A["Grounded answer"]
    style R fill:#064E3B,stroke:#34D399,color:#ECFDF5
    style A fill:#164E63,stroke:#06B6D4,color:#ECFDF5
```

<sub>`Python` `Streamlit` `Llama 3.2` `ReActAgent` `FunctionTool` `DuckDuckGo API`</sub>

</details>

<details>
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
→ agentic workflows with LangGraph and tool-calling LLMs
→ RAG over product and operational data
```

---

<div align="center">

```bash
$ reach me
→ email     vishnu.rsvk@gmail.com
→ linkedin  linkedin.com/in/vishnu-kumar-rs
→ github    github.com/vishnu-ing
```

<sub>Open to AI Software Engineer roles: LLM-powered products, agents and RAG, backed by full-stack depth.</sub>

</div>
