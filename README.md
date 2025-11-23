# Túlio Ribeiro dos Anjos
**Senior Software Engineer**  
Remote (based in Campo Grande, Brazil – UTC-4)  
+55 67 9 9266 0804 · [mail@tulio.org](mailto:mail@tulio.org) · [linkedin.com/in/tulioanjos](https://linkedin.com/in/tulioanjos) · [tulio.org](https://tulio.org)

---

### SUMMARY
Senior Software Engineer specializing in high-velocity feature delivery within distributed cloud environments. Expert in executing architectural roadmaps with full autonomy, translating complex requirements into robust .NET solutions. Proven track record of building and optimizing high-throughput systems (150M+ daily events), balancing rapid development with strict performance and cost constraints.

---

### TECHNICAL SKILLS
**Languages:** C#, Java, TypeScript, SQL.  
**Core:** Distributed Systems, High-Scale Ingestion, Legacy Modernization, Performance Engineering.  
**Cloud & Infra:** AWS (Lambda, S3), Azure (Event Hubs), Redis, Docker, CI/CD.  
**Data:** BigQuery, SQL Server, PostgreSQL, MongoDB.  
**AI Integration:** Model Context Protocol (MCP), OpenAI Tool Use, Context-Aware State Compression (proof-of-concept).  
**Frameworks:** .NET 8, ASP.NET Core, Spring Boot, Angular 17, WPF/MVVM, Entity Framework, Spring Data JPA.

---

### PROFESSIONAL EXPERIENCE

**BairesDev** | *Remote*  
*Senior Software Engineer (Contract)* | *Jun 2022 – Nov 2025*

Deployed as a core engineering resource for high-scale US tech clients. Specialized in distributed systems, legacy modernization, and high-throughput data architecture.

**Project: OEM Telematics & IoT Platform**  
*Client: Global Automotive OEM (Bus/Transit)*
*    **Big Data Optimization:** Refactored the aggregation service responsible for generating rollup tables from raw telemetry. Implemented a **BigQuery staging-table MERGE pattern** to handle deduplication and bulk upserts, reducing job runtime from **60+ minutes to 30 seconds**.
*   **Scalability:** Enabled horizontal scaling for the high-throughput ingestion service (150M+ daily events) by migrating state from local memory to **distributed Redis**, eliminating cache inconsistency across instances.
*    **Core Algorithms:** Developed the driver-attribution logic to map telemetry to operators. implemented **timeline reconstruction algorithms** to handle noisy logon events, solving edge cases like mid-trip driver swaps and multi-vehicle assignments.

**Project: Fintech & POS Platform ($4.5B+ Volume)**  
*Client: Fintech Platform for Enterprise Retail*
*   **Distributed Architecture:** Engineered a fault-tolerant, bi-directional bridge between the core ledger and Shopify. Implemented **AWS SQS/Lambda** and **Polly policies** to handle GraphQL rate limits and ensure eventual consistency for real-time inventory reconciliation.
*   **Scale & Impact:** Unlocked multi-channel sales for high-volume retailers by orchestrating bulk catalog ingestion (100k+ SKUs per merchant), directly supporting the platform's **$4.5B+ GMV**.
*   **Computer Vision:** Built serverless AWS Lambda/OpenCVSharp pipeline with context-aware cropping to generate marketing assets.
*   **Cost:** Replaced commercial image library with custom solution, permanently eliminating licensing fees and vendor dependency.

**Project: Enterprise Privacy SaaS**  
*Client: VC-Backed Privacy Platform*
*   **Security:** Migrated raw SQL to Spring Data JPA, eliminating injection risks.
*   **Modernization:** Refactored brittle data-access patterns to support rapid feature development, reducing technical debt in the platform's core.

&nbsp;

**Grupo Imagetech** | *Campo Grande, Brazil*  
*Senior Software Engineer* | *Aug 2019 – Jun 2022*

**Client: State Court of Accounts (TCE-MS)**
*   **Distributed ETL:** Architected a Linux-based ingestion pipeline to extract financial data from heterogeneous municipal environments. Engineered a custom Java/Pentaho CLI to bypass vendor lock-in and automate connectivity across 79 distinct jurisdictions.
*   **Resilience:** Implemented custom GZIP compression and error-recovery protocols to ensure reliable delivery and data integrity over unstable, low-bandwidth government networks.
*   **Modernization:** Led the migration of the central auditing dashboard from legacy JSF to Angular, decoupling the frontend to accelerate fiscal monitoring capabilities.

&nbsp;

**Fonte Tecnologia** | *Campo Grande, Brazil*  
*Software Engineer* | *Aug 2017 – Aug 2019*

**Client: State Dept. of Justice (Sejusp-MS) / Military Police**
*   **Mission-Critical Infrastructure:** Contributed to the Integrated Operational Management System (SIGO) and Computer-Aided Dispatch (CADG), the core command-and-control platforms used by state police for emergency response.
*   **Full-Stack Development:** maintained and expanded backend services (.NET Web API) and frontend interfaces to support real-time incident tracking, ensuring high availability for 24/7 public safety operations.

&nbsp;

**PSG Tecnologia** | *Campo Grande, Brazil*  
*Software Engineer* | *Mar 2013 – Aug 2017*

**Client: State Secretariat of Finance (SEFAZ-MS) / SGI**
*   **Strategic Resource Planning (PPA):** Owned the full-stack development of the Multi-Year Plan module within the State Financial Planning System (SPF). Designed data models used by all state secretariats to define 4-year fiscal programs.
*   **Recursive Data Structures:** Engineered a recursive SQL engine to model complex legal hierarchies (articles, paragraphs). Implemented automatic hierarchical renumbering and validation logic.
*   **Custom Tooling:** Built a specialized browser-based editor and visual "diff" engine, enabling state auditors to draft and version multi-year budget legislation.

---

### EDUCATION & CERTIFICATIONS
**Bachelor of Engineering - Computer Engineering** | Uniderp (2013)  
**Oracle Certified Professional: Java SE 11 Developer** | Oracle (2021)  
**EF SET English Certificate (Score: 79/100)** | C2 Proficient Level
