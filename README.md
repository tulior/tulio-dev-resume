# Túlio Ribeiro dos Anjos
**Senior Full-Stack Engineer** · Campo Grande, Brazil (Remote)  
+55 67 9 9266 0804 · mail@tulio.org · tulio.org · linkedin.com/in/tulioanjos

---

### SKILLS
**Backend:** .NET 8, C#, Entity Framework, REST/GraphQL APIs, Spring Boot, Java  
**Frontend:** Angular 17, TypeScript, Astro, React.js  
**Data & Cloud:** SQL Server, PostgreSQL, MongoDB, Redis · AWS (Lambda, S3, SQS, SNS) · Azure (Event Hubs, Pipelines)

---

### EXPERIENCE

**BairesDev - Senior Full-Stack Engineer** | Jun 2022 - Present  
*Consultant for US-based clients on long-term embedded assignments.*

**Client: Enterprise Fleet Telematics Platform | Feb 2025 - Present**  
Engineered the core C# service logic to assign individual drivers to vehicle trips, making the fleet's performance reports actionable. I then built the platform's shift management module, allowing operators to upload their schedules via CSV. A new C# background service aggregates vehicle data against these schedules, computing distinct performance metrics (max/avg speed, fuel use, safety scores) for each completed shift. The main challenge for both features was parsing the raw driver ID signals from BigQuery; I wrote specific data sanitization rules to handle signal flicker and resolve logical conflicts like a single driver appearing in multiple vehicles simultaneously.

**Client: E-commerce Platform | Jan 2023 - Jan 2025**  
Built a serverless image processing pipeline (AWS Lambda, SQS, SNS) to automatically generate product collages. My initial approach used an advanced context-aware cropping algorithm from OpenCVSharp, but its native dependencies proved incompatible with the AWS Lambda execution environment. I re-engineered the function, replacing the OpenCVSharp module with a lightweight edge-detection algorithm and using the SkiaSharp library to compose the final image. This pivot unblocked the project, enabling the pipeline to successfully deliver optimized collage assets to an S3 bucket for use on the storefront.

**Client: B2B Data Privacy & Compliance SaaS | Jun 2022 - Jan 2023**  
Tasked with modernizing the platform's data access layer, I migrated the application from raw JDBC to Spring Boot with Spring Data JPA. This systematic overhaul replaced manual, string-based queries with a type-safe repository pattern, which eliminated an entire class of critical SQL injection vulnerabilities. The migration also removed brittle, error-prone code for manual connection management, making the data layer more reliable and maintainable.

**GEOI2 Tecnologia** — *Software Engineer* | Aug 2019 – Jun 2022  
Decommissioned a high-risk legacy JSF application that depended on a single developer by rebuilding its front end in Angular 13, creating a modern codebase that could be supported by the entire team. I also automated data collection for state financial audits, replacing a manual process that required engineers to physically drive to remote municipal sites to copy databases. I built a Java CLI tool that orchestrated an existing Pentaho Kettle pipeline to extract data from Sybase, Firebird, and PostgreSQL. To ensure reliability over low-bandwidth municipal networks, I implemented Gzip compression, reducing data payloads by 90% and preventing transfer failures.

**Fonte Tecnologia** — *Software Engineer* | Aug 2017 – Aug 2019  
I proactively diagnosed and repaired a severe rendering bottleneck in the real-time vehicle dispatch UI, a core component built with Knockout.js. Using the Chrome profiler, I traced sluggish animations to an inefficient design that attached a separate event handler to every cell in the data grid. I refactored the component to a single event delegation pattern and replaced its `setTimeout`-based animation loop with `requestAnimationFrame`. This eliminated the performance degradation and ensured the UI would remain responsive as the number of active dispatches scaled. I also built the system's emergency call reporting module with .NET.

**PSG Tecnologia** — *Software Engineer* | Mar 2013 – Aug 2017  
Built the state's legislative drafting and budget management system. The core engineering task was to model complex legal document hierarchies (articles, sections, paragraphs) in a relational database; I solved this by designing a schema with a recursive, self-referencing table structure. On the front end, I used jQuery to build the rich text editor for drafting legislation and a tree-based UI for managing multi-year budgets, which both operated on this hierarchical data model.

---

### EDUCATION & CERTIFICATIONS
*   B.S. Computer Engineering — Uniderp (2013)
*   Oracle Certified Java SE 11 Developer (2021)
