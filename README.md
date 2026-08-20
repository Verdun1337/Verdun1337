<div align="center">

<h1>👋 Patryk Pszeniczny</h1>

<h3>Backend Engineer · EV Charging · Distributed Systems</h3>

<p>
  Designing backend services, integration layers and charging infrastructure<br/>
  with a focus on <strong>reliability, interoperability and maintainable architecture.</strong>
</p>

<br/>

<p>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/OCPP-1.6%20%7C%202.x-0A66C2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OCPI-eRoaming-0A66C2?style=for-the-badge" />
</p>

<p>
  <img src="https://img.shields.io/badge/CSMS-EV%20Infrastructure-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/Backend-Architecture-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/Event--Driven-Systems-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/System-Integration-111111?style=flat-square" />
</p>
<sub>
  ⚡ From charging station protocols to roaming integrations and user-facing applications.
</sub>
</div>
<p align="center">
  <a href="https://www.bitbridge.pl">Website</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/patryk-pszeniczny?tab=repositories">Repositories</a>
  &nbsp;·&nbsp;
  <a href="https://twitter.com/verdun">X / Twitter</a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=verdun1337&label=Profile%20views&color=555555&style=flat-square" />
</p>

---

<table>
<tr>
<td width="50%" valign="top">

### ⚡ EV Charging

Backend systems for charging infrastructure and interoperability.

* OCPP 1.6 / 2.x
* OCPI
* CSMS
* CPO / eMSP
* Hubject / eRoaming
* Plug & Charge
* EVSE lifecycle
* Charging sessions & CDRs

</td>

<td width="50%" valign="top">

### ⚙️ Backend Engineering

Production-oriented APIs, services and integration layers.

* ASP.NET Core
* Java / Spring Boot
* REST APIs
* Authentication & authorization
* Data persistence
* Integration services
* Background processing
* External APIs

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧩 Architecture

Systems designed around explicit state and clear boundaries.

* Event-driven architecture
* CQRS / read models
* Idempotency
* Eventual consistency
* Domain boundaries
* Replayable state
* Failure handling
* Data pipelines

</td>

<td width="50%" valign="top">

### ☁️ Infrastructure

Deployment and operational tooling around backend systems.

* Docker
* Docker Compose
* AWS
* Terraform
* GitHub Actions
* GitLab CI
* Jenkins
* Observability

</td>
</tr>
</table>

---

# ⚡ EV Charging & eMobility

<p>
  <img src="https://img.shields.io/badge/OCPP-1.6%20%7C%202.x-0A66C2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OCPI-eRoaming-0A66C2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/CSMS-Charging%20Systems-0A66C2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Hubject-eRoaming-0A66C2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Plug%20%26%20Charge-ISO%2015118-0A66C2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Mobile-App%20%26%20Backend-0A66C2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Proxy-OCPP%20Gateway-0A66C2?style=for-the-badge" />
</p>

<table>
<tr>

<td width="33%" valign="top">

### 🔌 Charging Infrastructure

* OCPP 1.6 / 2.x
* Charging stations
* EVSE / connector state
* Sessions & transactions
* Remote commands
* Authorization flows
* Meter values
* Station lifecycle

</td>

<td width="33%" valign="top">

### 📱 Mobile & Product

* Mobile app integration
* User authentication
* Start / stop charging
* Session visibility
* Station discovery
* Tariff / pricing display
* Charging history
* Backend-to-mobile APIs

</td>

<td width="33%" valign="top">

### 🌐 Roaming & Interoperability

* OCPI
* Hubject / eRoaming
* CPO / eMSP flows
* CDR handling
* Token exchange
* Partner integrations
* Session synchronization
* Cross-platform interoperability

</td>

</tr>
</table>

---

## EV Architecture

<table>
<tr>

<td width="25%" valign="top">

### 🔌 Infrastructure

<pre>
Charging Station
      │
    OCPP
      │
      ▼
 OCPP Proxy
      │
      ▼
     CSMS
      │
 ┌────┼─────┐
 ▼    ▼     ▼
EVSE Auth Sessions
</pre>

</td>

<td width="25%" valign="top">

### 📱 Mobile

<pre>
    Driver
      │
      ▼
 Mobile App
      │
      ▼
 Backend API
      │
 ┌────┼─────┐
 ▼    ▼     ▼
Auth EVSE Sessions
      │
      ▼
     CSMS
</pre>

</td>

<td width="25%" valign="top">

### 🌐 Roaming

<pre>
     CSMS
       │
       ▼
Integration
   Layer
       │
  ┌────┴────┐
  ▼         ▼
 OCPI    Hubject
  │         │
  ▼         ▼
 eMSP    Partners
</pre>

</td>

<td width="25%" valign="top">

### 🔀 Proxy

<pre>
   Station
      │
      ▼
OCPP Gateway
      │
 ┌────┼─────┐
 ▼    ▼     ▼
Route Valid Normalize
      │
      ▼
    CSMS
</pre>

</td>

</tr>
</table>

---

## Proxy / Gateway Responsibilities

<table>
<tr>

<td width="33%" valign="top">

### Protocol

* OCPP message handling
* validation
* normalization
* compatibility handling
* protocol boundaries

</td>

<td width="33%" valign="top">

### Routing

* station routing
* tenant routing
* backend selection
* connection management
* session correlation

</td>

<td width="33%" valign="top">

### Reliability

* logging
* retries
* buffering
* resilience
* security boundaries

</td>

</tr>
</table>

<p>

`OCPP` · `OCPI` · `CSMS` · `EVSE` · `Charging Station` · `Proxy` · `Gateway` · `Mobile` · `Backend API` · `CPO` · `eMSP` · `Hubject` · `Plug & Charge` · `Sessions` · `Transactions` · `CDRs`

</p>

---

# 🛠 Tech Stack

<table>
<tr>

<td width="50%" valign="top">

### Languages

<p>
<img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/VHDL-555555?style=flat-square" />
<img src="https://img.shields.io/badge/Assembly-555555?style=flat-square" />
</p>

</td>

<td width="50%" valign="top">

### Backend & Frameworks

<p>
<img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/EF%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/Java%208--21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Spring%20Core-6DB33F?style=flat-square&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" />
<img src="https://img.shields.io/badge/Netty-111111?style=flat-square" />
<img src="https://img.shields.io/badge/Java%20Sockets-111111?style=flat-square" />
<img src="https://img.shields.io/badge/Kryo-111111?style=flat-square" />
<img src="https://img.shields.io/badge/KryoNet-111111?style=flat-square" />
</p>

</td>
</tr>

<tr>

<td width="50%" valign="top">

### Databases & Persistence

<p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-555555?style=flat-square" />
</p>

</td>

<td width="50%" valign="top">

### APIs & Integrations

<p>
<img src="https://img.shields.io/badge/REST-111111?style=flat-square" />
<img src="https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapiinitiative&logoColor=white" />
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black" />
<img src="https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white" />
<img src="https://img.shields.io/badge/XML-555555?style=flat-square" />
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
<img src="https://img.shields.io/badge/OAuth2-555555?style=flat-square" />
<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
</p>

</td>
</tr>

<tr>

<td width="50%" valign="top">

### Frontend

<p>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/shadcn/ui-000000?style=flat-square&logo=shadcnui&logoColor=white" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
<img src="https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
</p>

</td>

<td width="50%" valign="top">

### Infrastructure & DevOps

<p>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white" />
<img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" />
</p>

</td>
</tr>

<tr>

<td width="50%" valign="top">

### Testing & Quality

<p>
<img src="https://img.shields.io/badge/JUnit%205-25A162?style=flat-square&logo=junit5&logoColor=white" />
<img src="https://img.shields.io/badge/Mockito-111111?style=flat-square" />
<img src="https://img.shields.io/badge/Spring%20Test-6DB33F?style=flat-square&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/Testcontainers-2496ED?style=flat-square&logo=testcontainers&logoColor=white" />
<img src="https://img.shields.io/badge/Integration%20Tests-555555?style=flat-square" />
<img src="https://img.shields.io/badge/REST%20API%20Testing-555555?style=flat-square" />
<img src="https://img.shields.io/badge/Newman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
</p>

</td>

<td width="50%" valign="top">

### Tooling & Observability

<p>
<img src="https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white" />
<img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white" />
<img src="https://img.shields.io/badge/SLF4J-555555?style=flat-square" />
<img src="https://img.shields.io/badge/Logback-555555?style=flat-square" />
</p>

</td>
</tr>
</table>

---

# 🚀 Selected Work

<table>
<tr>

<td width="50%" valign="top">

### ⚙️ FlowOps

**Event-Driven Subscription & Billing**

`ASP.NET Core` `CQRS` `Events` `Idempotency`

Event-driven billing and subscription platform with replay-capable state and read models.

[View repository →](https://github.com/patryk-pszeniczny/FlowOps)

</td>

<td width="50%" valign="top">

### 🎟️ Ticket Booking API

**Cinema reservation backend**

`Java` `Spring Boot` `REST` `Docker`

Backend covering screenings, seats, movies and reservation workflows.

[View repository →](https://github.com/patryk-pszeniczny/ticket-booking-app)

</td>

</tr>

<tr>

<td width="50%" valign="top">

### 🔐 BitBridge Authentication

**Authentication & Authorization**

`Spring Security` `OAuth2` `JWT`

Backend and frontend experiments around secure authentication flows.

[Backend →](https://github.com/patryk-pszeniczny/bitbridge-springboot-authentication)

[Frontend →](https://github.com/patryk-pszeniczny/bitbridge-frontend-authentication)

</td>

<td width="50%" valign="top">

### 📨 Kafka Example

**Event-driven messaging**

`Kafka` `REST` `Messaging` `Docker`

Small producer/consumer workflow demonstrating asynchronous integration patterns.

[View repository →](https://github.com/patryk-pszeniczny/kafka-example)

</td>

</tr>

<tr>

<td width="50%" valign="top">

### 🧠 Gallstone AI Lab

**ML & fuzzy logic experiment**

`Python` `MLP` `Fuzzy Logic`

Educational ML pipeline combining neural networks and fuzzy logic.

[View repository →](https://github.com/patryk-pszeniczny/gallstone-ai-lab)

</td>

<td width="50%" valign="top">

### 📄 CV Analyzer 3000™

**AI-assisted analysis**

`AI` `JSON` `Structured Analysis`

Resume parsing and scoring workflow based on configurable criteria.

[View repository →](https://github.com/patryk-pszeniczny/bitbridge-ai-cv-analyzer)

</td>

</tr>

<tr>

<td width="50%" valign="top">

### 🔎 GitHub Repositories Scrapper

**Repository discovery API**

`REST` `External API` `Backend`

Small REST service for retrieving public repositories for a selected GitHub user.

[View repository →](https://github.com/patryk-pszeniczny/GitHub-Repositories-Scrapper)

</td>

<td width="50%" valign="top">

### 🎮 Sudoku C++/CLI

**Desktop OOP project**

`C++` `OOP` `Desktop UI`

Desktop Sudoku project focused on object-oriented design and application logic.

[View repository →](https://github.com/patryk-pszeniczny/sudoku-cpp)

</td>

</tr>
</table>

---

# 🧩 Engineering Principles

<table>
<tr>

<td width="33%" align="center">

### Explicit State

Predictable transitions
and easier debugging.

</td>

<td width="33%" align="center">

### Safe Failure

Retries, idempotency
and recovery paths.

</td>

<td width="33%" align="center">

### Simple Architecture

Clear boundaries
over clever abstractions.

</td>

</tr>

<tr>

<td width="33%" align="center">

### Observability

Logs and metrics
should explain the system.

</td>

<td width="33%" align="center">

### Integration First

External boundaries
deserve explicit contracts.

</td>

<td width="33%" align="center">

### Maintainability

Readable systems
outlive clever code.

</td>

</tr>
</table>

---

<p align="center">
  <strong>Backend · EV Charging · Distributed Systems · System Integration</strong>
</p>

<p align="center">
  <sub>Building systems that remain understandable as they grow.</sub>
</p>
