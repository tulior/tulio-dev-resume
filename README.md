# Túlio Ribeiro dos Anjos
**Senior Software Engineer**
Remote (based in Campo Grande, Brazil – UTC-4)
[mail@tulio.org](mailto:mail@tulio.org) · +55 67 9 9266 0804 · [linkedin.com/in/tulioanjos](https://linkedin.com/in/tulioanjos) · [tulio.org](https://tulio.org)

### THE GIST
I am a Senior Software Engineer who builds distributed systems that actually work. I have 12+ years of experience, primarily in .NET and Java. I specialize in fixing slow data pipelines, modernizing legacy code without breaking production, and building backend infrastructure for US startups and enterprises. I value code that is simple to read, cheap to run, and scales.

### TECHNICAL SKILLS
*   **Languages:** C#, Java, TypeScript, SQL.
*   **Core:** Distributed Systems, High-Scale Ingestion (150M+ events/day), Performance Tuning.
*   **Cloud & Infra:** AWS (Lambda, SQS, S3), Azure (Event Hubs), Redis, Docker, CI/CD.
*   **Data:** BigQuery, SQL Server, PostgreSQL, MongoDB, Entity Framework.
*   **Frameworks:** .NET 8, ASP.NET Core, Spring Boot, Angular 17.

---

### EXPERIENCE

**BairesDev** | *Remote*
*Senior Software Engineer (Contract)* | *Jun 2022 – Nov 2025*

I was hired to solve specific scaling and architectural problems for US clients. I worked embedded within their core teams, not on the periphery.

**Client: Global Automotive OEM (Telematics Platform)**
*   **Fixed a 60-minute bottleneck:** The system took over an hour to generate rollup tables from raw telemetry. I rewrote the aggregation service using a **BigQuery staging-table MERGE pattern**. It now runs in **30 seconds**.
*   **Scaled to 150M+ daily events:** The ingestion service couldn't scale because it held state in local memory. I migrated that state to **distributed Redis**, allowing us to autoscale instances horizontally to handle traffic spikes.
*   **Solved complex logic:** I wrote the algorithms that figure out who is driving the bus. This required timeline reconstruction logic to handle edge cases like mid-trip driver swaps and noisy logon events.

**Client: Enterprise Fintech Platform**
*   **Handled $4.5B+ in volume:** I built the bridge between the core ledger and Shopify. This allowed high-volume retailers to ingest 100k+ SKUs at once. The system supported **$4.5B in Gross Merchandise Value**.
*   **Built for failure:** APIs fail. I implemented **AWS SQS** and **Polly policies** to handle GraphQL rate limits and ensure eventual consistency. When the external API went down, our system didn't lose data; it just waited.
*   **Serverless Computer Vision:** Built an AWS Lambda pipeline using OpenCVSharp to automatically crop and generate marketing assets from raw images.

**Client: VC-Backed Privacy SaaS**
*   **Security Patching:** Migrated raw SQL queries to **Spring Data JPA**. This eliminated SQL injection risks across the platform.
*   **Refactoring:** Untangled brittle data-access patterns that were slowing down the team, allowing them to ship features faster.

&nbsp;

**Grupo Imagetech** | *Campo Grande, Brazil*
*Senior Software Engineer* | *Aug 2019 – Jun 2022*

**Client: State Court of Accounts (Government Auditing)**
*   **Hacked a solution for bad infrastructure:** We needed to pull financial data from 79 different municipalities with terrible internet and different database vendors. I built a custom **Java/Pentaho CLI** to run locally on their servers, bypass vendor lock-in, and compress data via GZIP so it could actually traverse the network.
*   **Modernization:** Led the migration of the central auditing dashboard from legacy JSF to **Angular**, which decoupled the frontend and improved load times for auditors.

&nbsp;

**Fonte Tecnologia** | *Campo Grande, Brazil*
*Software Engineer* | *Aug 2017 – Aug 2019*

**Client: Military Police & Dept. of Justice**
*   **High Stakes:** Worked on the Computer-Aided Dispatch (CADG) system. If this software goes down, 911 calls don't get answered. I maintained the .NET Web API backend that kept the system running 24/7.
*   **Real-time tracking:** Built features for the Integrated Operational Management System (SIGO) to track incidents in real-time.

&nbsp;

**PSG Tecnologia** | *Campo Grande, Brazil*
*Software Engineer* | *Mar 2013 – Aug 2017*

**Client: State Secretariat of Finance**
*   **Built the State Budget System:** I owned the full-stack development of the Multi-Year Plan module. This is the software the government uses to define its 4-year fiscal plan.
*   **Recursive SQL:** Legal hierarchies (Articles -> Paragraphs -> Sections) are deeply nested. I wrote a recursive SQL engine to model this structure and automatically handle renumbering when laws changed.
*   **Visual Diffing:** Built a browser-based editor that allowed auditors to visually "diff" budget versions, saving them hours of manual checking.

---

### EDUCATION
**Bachelor of Engineering - Computer Engineering** | Uniderp (2013)
**Oracle Certified Professional: Java SE 11 Developer** | (2021)
**English Proficiency:** C2 (EF SET Score: 79/100)
