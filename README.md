# Túlio Ribeiro dos Anjos  
**Senior Full-Stack Engineer** · Remote (Based in Campo Grande, Brazil)  
+55 67 9 9266 0804 · [mail@tulio.org](mailto:mail@tulio.org) · [tulio.org](https://tulio.org) · [linkedin.com/in/tulioanjos](https://linkedin.com/in/tulioanjos)

---

### TECHNICAL SKILLS  
**Backend:** C#, .NET 8, ASP.NET Core, REST/GraphQL APIs, Spring Boot, Java, Entity Framework  
**Frontend:** Angular 17, React, TypeScript, Astro  
**Data & Infrastructure:** SQL Server, PostgreSQL, MongoDB, Redis · AWS (Lambda, S3, SQS, SNS) · Azure (Event Hubs, DevOps Pipelines)  
**Practices:** Remote collaboration, CI/CD, Performance optimization, Secure coding, Legacy modernization

---

### PROFESSIONAL EXPERIENCE

**BairesDev — Senior Full-Stack Engineer**  
*Remote | Jun 2022 – Present*  
Worked as an embedded contractor for U.S. clients on long-term remote projects, collaborating daily with product and engineering teams across U.S. time zones.

- **Enterprise Fleet Telematics Platform** *(U.S. Client | Remote | Feb 2025 – Present)*  
  Built core C# services to assign drivers to vehicle trips using raw telemetry from BigQuery. Created a shift management module that accepts operator schedules via CSV, then wrote a background service to match vehicle data against those schedules and compute performance metrics (max/avg speed, fuel use, safety scores). Fixed data integrity issues caused by signal flicker and drivers appearing in multiple vehicles at once by writing custom sanitization rules.

- **E-commerce Platform** *(U.S. Client | Remote | Jan 2023 – Jan 2025)*  
  Built a serverless image pipeline on AWS (Lambda, SQS, SNS) to auto-generate product collages. OpenCVSharp failed in Lambda due to native dependencies, so I rewrote the image logic using SkiaSharp and a lightweight edge-detection algorithm. The new version ran reliably and delivered optimized assets to S3 for the storefront.

- **B2B Data Privacy & Compliance SaaS** *(U.S. Client | Remote | Jun 2022 – Jan 2023)*  
  Migrated the data layer from raw JDBC to Spring Data JPA. Swapped fragile string-based SQL queries for type-safe repositories, which removed a class of SQL injection bugs and eliminated manual connection management. After the change, the team could add new data features without worrying about connection leaks.

**GEOI2 Tecnologia — Software Engineer**  
*Remote/Hybrid | Aug 2019 – Jun 2022*  
- Replaced a legacy JSF app—maintained by only one developer—with a new Angular 13 frontend so the whole team could support it.  
- Automated financial audit data collection across 79 municipalities. Built a Java CLI tool that ran Pentaho Kettle pipelines (Sybase, Firebird, PostgreSQL) and added Gzip compression to cut payload size by 90%, which kept transfers from failing on slow municipal networks.

**Fonte Tecnologia — Software Engineer**  
*Campo Grande, Brazil | Aug 2017 – Aug 2019*  
- Fixed a serious UI slowdown in a real-time vehicle dispatch system built with Knockout.js. Used the Chrome profiler to find that every grid cell had its own event handler. Switched to event delegation and replaced setTimeout animations with requestAnimationFrame—restored smooth performance even with hundreds of active dispatches.  
- Built an emergency call reporting module using .NET Web API and SQL Server.

**PSG Tecnologia — Software Engineer**  
*Campo Grande, Brazil | Mar 2013 – Aug 2017*  
- Built a legislative drafting and budgeting system for state government. Modeled complex legal hierarchies (articles, sections, paragraphs) using a recursive SQL table.  
- Delivered a jQuery-based rich text editor and a tree UI for managing multi-year budgets, both working on the same data model.

---

### EDUCATION & CERTIFICATIONS  
- **B.S. in Computer Engineering** — Uniderp (2013)  
- **Oracle Certified Professional: Java SE 11 Developer** (2021)
