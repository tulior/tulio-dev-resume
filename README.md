# Túlio Ribeiro dos Anjos  
**Senior Software Engineer**  
Remote (based in Campo Grande, Brazil – UTC-4)  
[mail@tulio.org](mailto:mail@tulio.org) · +55 67 9 9266 0804 · [linkedin.com/in/tulioanjos](https://linkedin.com/in/tulioanjos) · [tulio.org](https://tulio.org)  

### SUMMARY  
Senior Software Engineer with 12+ years of experience specializing in Distributed Systems, .NET, and Java. I build high-throughput backend infrastructure (150M+ daily events) and modernize legacy environments for US-based startups and enterprises. My expertise lies in solving hard architectural problems—optimizing data pipelines, securing complex fintech integrations, and refactoring brittle code—while working as an autonomous, embedded core contributor.  

### TECHNICAL SKILLS  
*   **Languages:** C#, Java, TypeScript, SQL.  
*   **Core:** Distributed Systems, High-Scale Ingestion, Performance Engineering, System Architecture.  
*   **Cloud & Infra:** AWS (Lambda, SQS, SNS, S3), Azure (Event Hubs), Redis, Docker, CI/CD.  
*   **Data:** BigQuery, SQL Server, PostgreSQL, MongoDB, Entity Framework.  
*   **Frameworks:** .NET 8, ASP.NET Core, Spring Boot, Angular 17.  

---

### EXPERIENCE  

**BairesDev** | *Remote*  
*Senior Software Engineer (Contract)* | *Jun 2022 – Nov 2025*  

Embedded in US product teams to solve scaling bottlenecks and architectural debt. I did not work on maintenance tickets; I built core infrastructure.  

**Client: Global Automotive OEM (Telematics Platform)**  
*   **Fixed a 60-minute bottleneck:** The aggregation service took over an hour to populate rollup tables from raw telemetry. I refactored the entire service and implemented a **BigQuery staging-table MERGE pattern**. It now completes the job in **30 seconds**.  
*   **Scaled to 150M+ daily events:** The ingestion API relied on local memory to cache and merge vehicle signals, causing Out-of-Memory crashes during spikes. I rewrote the caching strategy to use **distributed Redis**, eliminating crashes and enabling horizontal scaling.  
*   **Solved complex logic:** I wrote the algorithms that figure out who is driving the bus. This required timeline reconstruction logic to handle edge cases like mid-trip driver swaps and noisy logon events.  

**Client: Fintech Platform (Enterprise Retail)**  
*   **Opened a major sales channel:** The platform's users (independent retailers) were locked into a proprietary POS. I built the bidirectional bridge that allowed them to sell their inventory on **Shopify**. This wasn't just a data dump; it was a live sync engine.  
*   **Event-Driven Architecture:** I decoupled the legacy POS from Shopify's strict rate limits using **AWS SNS and SQS**. Changes in the legacy ledger triggered events consumed by **Lambda**, which then updated the Shopify store via their **GraphQL API**.  
*   **Handling Complexity:** Syncing products is easy; syncing a catalog with **100k+ SKUs** and thousands of variants (colors, sizes, weights, images) per store is hard. I built the bulk-loading logic to map these complex hierarchies and handle webhooks to decrement the core ledger inventory immediately upon a Shopify sale.  

**Client: VC-Backed Privacy SaaS**  
*   **Eliminating Technical Debt:** The platform relied on brittle raw SQL that made feature development dangerous and slow. I migrated the persistence layer to **Spring Data JPA**, eliminating injection risks and standardizing data access so the team could ship features faster.  

&nbsp;  

**Grupo Imagetech** | *Campo Grande, Brazil*  
*Senior Software Engineer* | *Aug 2019 – Jun 2022*  

**Client: State Court of Accounts (TCE-MS)**  
*   **Reliable Ingestion over Unreliable Networks:** We needed to pull financial data from 79 different municipalities with terrible internet and different database vendors. I built a custom **Java/Pentaho CLI** to run locally on their servers, bypass vendor lock-in, and compress data via GZIP so it could actually traverse the network.  
*   **Frontend Architecture (e-Contas):** I rebuilt the fiscal submission portal ("e-Contas") from scratch, migrating from legacy JSF to **Angular**. I architected it as a **micro-frontend**, allowing the Court to embed the tools directly into their central "TCE Digital" platform. I owned the full UI implementation, ensuring strict validation for the XML-based government accounts.  

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
*   **Internal Tooling:** Built a browser-based editor that allowed auditors to visually "diff" budget versions, saving them hours of manual checking.  

---

### EDUCATION  
**Bachelor of Engineering - Computer Engineering** | Uniderp (2013)  
**Oracle Certified Professional: Java SE 11 Developer** | (2021)  
**English:** Full Professional Proficiency (C2)
