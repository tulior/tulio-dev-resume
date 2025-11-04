# Túlio Ribeiro dos Anjos
**Senior Software Engineer** · Remote (based in Campo Grande, Brazil)

+55 67 9 9266 0804 · [mail@tulio.org](mailto:mail@tulio.org) · [tulio.org](https://tulio.org) · [linkedin.com/in/tulioanjos](https://linkedin.com/in/tulioanjos)

---

### SUMMARY
Backend-leaning full-stack engineer. I turn raw data and legacy surfaces into simple, reliable features that teams can ship and support. Comfortable owning messy problems end-to-end and writing code other people aren’t afraid to change.

---

### TECHNICAL SKILLS
**Languages & Frameworks:** C#, .NET 8, ASP.NET Core, Java, Spring Boot, TypeScript, Angular 17, React, GraphQL/REST

**Data:** SQL Server, PostgreSQL, MongoDB, Redis, Entity Framework, Spring Data JPA

**Cloud & Infra:** AWS (Lambda, S3, SQS, SNS), Azure (Event Hubs, DevOps Pipelines), Docker, CI/CD

**Focus Areas:** Telemetry/analytics, reliability, performance, secure coding, legacy modernization, remote collaboration

---

### PROFESSIONAL EXPERIENCE

**BairesDev — Software Engineer**  
*Remote | Jun 2022 – Present*  
Embedded on U.S. client teams; daily collaboration across time zones.

**Enterprise Fleet Telematics Platform** *(U.S. Client | Feb 2025 – Present)*
- Solely conceived, designed, and delivered an internal **EventHub Sender** desktop tool (**C#/.NET 8, WPF/MVVM, Azure Event Hubs**) that lets QAs compose and send numeric and alphanumeric signals via a clean UI. Replaced a console workflow that required editing a messy text file, manually converting dates to **Unix time**, copy-pasting JSON to add signals, and looking up signal IDs. The tool provides an Object ID picker with clear kind labels (NUM/ALPHA) and combined architectures, a **multiline Value editor**, and automatic UTC timestamp handling—significantly reducing setup time and errors for test runs.
- Engineered a driver-to-trip assignment system in C#/.NET 8 that attributes fuel, distance, and safety scores to the correct operator on multi-driver routes. The system filters noisy telemetry signals (e.g., card-in/out flicker) using validation and debouncing logic to ensure attribution is reliable.
- Developed a full-stack fuel consumption dashboard for the diesel fleet, building a C# API to query and aggregate data from a BigQuery warehouse handling over **100M daily telemetry events** from Azure Event Hubs. The new dashboard, built with Angular 17, provided managers with first-time visibility into fleet efficiency.

**E-commerce Platform** *(U.S. Client | Jan 2023 – Jan 2025)*
- Architected and built an automated collage generator using an event-driven, serverless pipeline. The system uses SNS/SQS to trigger an AWS Lambda function on catalog updates, which applies context-aware cropping and publishes optimized assets to S3, eliminating manual photo editing.
- Engineered a two-way Shopify integration to synchronize a 100k+ SKU catalog, building the sync logic against their GraphQL API. This included an initial bulk import, real-time delta updates for inventory and pricing, and webhook processing for new orders. Contributed to the associated internal management UI using React.

**B2B Data Privacy & Compliance SaaS** *(U.S. Client | Jun 2022 – Jan 2023)*
- Refactored the data access layer by migrating raw SQL queries to Spring Data JPA, which eliminated SQL injection risks and simplified connection management, allowing the team to ship new features more safely and quickly.
- Established clear data access boundaries and introduced unit tests for the new repositories, making the persistence layer significantly easier to maintain and extend.

**GEOI2 Tecnologia — Software Engineer**  
*Remote/Hybrid | Aug 2019 – Jun 2022*
- Engineered a data collection pipeline for financial audits across 79 municipalities. The Java CLI tool used Kettle for ETL, loaded processed data into MongoDB, and used gzip compression to ensure reliability over low-bandwidth connections.
- After the success of the data pipeline, was entrusted to spearhead the modernization of a legacy JSF application to Angular 13. The new front end enabled the entire team to contribute, unblocking feature development and simplifying maintenance.

**Fonte Tecnologia — Software Engineer**  
*Campo Grande, Brazil | Aug 2017 – Aug 2019*
- Optimized a real-time dispatch grid that was lagging under the high frequency of updates pushed via SignalR. By consolidating event handlers and shifting rendering to requestAnimationFrame, I restored UI responsiveness, ensuring the grid remained fluid with hundreds of active jobs streaming in.

**PSG Tecnologia — Software Engineer**  
*Campo Grande, Brazil | Mar 2013 – Aug 2017*
- Built a legislative drafting and budgeting system for state government, modeling legal hierarchies with a recursive SQL schema.

---

### EDUCATION & CERTIFICATIONS
- **B.S. in Computer Engineering** — Uniderp (2013)
- **Oracle Certified Professional: Java SE 11 Developer** (2021)
