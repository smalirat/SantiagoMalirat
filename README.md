# 👋 Hi, I'm Santiago Malirat

I am an **Information Systems Engineering student (UTN)**, with an interest in cybersecurity, software development, and backend & fullstack design.

---

## Academic Projects

Projects developed as collaborative efforts for university courses.

- [TP DSI – DonaTrack](https://github.com/smalirat/donatrack)
  Annual project for the *Information Systems Design* course (2026). A donation management and traceability system built as microservices: four Spring Boot services (Java 21) with their own PostgreSQL databases, integrated synchronously over REST and asynchronously through RabbitMQ (work queues with competing workers, retries and dead letter queues, and a topic exchange for domain events). Implements the CQRS pattern with a read model in MongoDB, kept up to date through idempotent event projections and queried with aggregation pipelines, behind a Spring Cloud Gateway. Includes observability with Micrometer and Datadog (business metrics, centralized logging and email alerts), a Telegram bot, and an MCP server in TypeScript to operate the whole system from Claude.

- [TP DSI – Information Systems Design](https://github.com/smalirat/tp-dsi-1)
  Practical assignment for the *Information Systems Design* course. Development of a web platform (MetaMapa) applying MVC architecture and REST API design. Built with Java and Javalin, it implements relational persistence through JPA/Hibernate, using PostgreSQL as the database engine. Application of design patterns for integration with external source APIs (Adapter), and *server-side* rendering using Handlebars.

- [SSL – Syntax and Semantics of Languages Laboratory](https://github.com/smalirat/SSL-Grupo-7)
  Exercises related to the development of a compiler written in C, Flex, and Bison, covering lexical and syntactic analysis for the *Syntax and Semantics of Languages* course.

- [TP TGC – Computer Graphics Techniques](https://github.com/smalirat/TP-TGC-2025-1C-FIFO)
  Practical assignment for the *Computer Graphics Techniques* course, aimed at creating an interactive environment and 3D graphical simulation. Programmed in C# using the MonoGame framework on the .NET platform. Practical implementation of the low-level graphics pipeline (DirectX/OpenGL), applying matrix transformations and spatial projections. Includes the programming of custom Shaders (in HLSL/GLSL) for real-time lighting calculation and visual effects, texture mapping, rasterization, and spatial camera management applied to video game design.

- [TP SO – Operating Systems](https://github.com/smalirat/Tp-so)
  Development in C of a distributed system that simulates the components of an Operating System on Linux. Modular implementation (Kernel, CPU, Memory, and I/O) communicated via TCP Sockets. Application of concurrency and multithreading (pthreads), synchronization, process scheduling algorithms, and virtual memory management (Pagination, MMU, and TLB). Compilation and orchestration managed with Makefiles.

- [TP GDD – Data Management](https://github.com/smalirat/GDD-TP-2C-2025)
  Project focused on the design and modeling of a relational database, as well as the elaboration of SQL and T-SQL queries for the migration of denormalized data and visualization oriented to Business Intelligence, corresponding to the *Data Management* course.

- [TP DDS – Software Development](https://github.com/smalirat/TP-DDS)
  Practical assignment for the *Software Development* course, consisting of the simulation of an Airbnb-type web application. With a backend built on Node.js, exposing a REST API structured under a rigorous object-oriented multilayer MVC architecture (Routes, Controllers, Services, and Repositories). The frontend is a SPA developed with React and Vite. Includes NoSQL data modeling (Schemas) for the use of MongoDB, automated testing (unit and integration) with Jest and Supertest, and development environment orchestration using Docker.

---

## Personal Projects

Independently developed projects to practice and apply acquired knowledge.

- [Comment Editor](https://github.com/smalirat/comment-editor)
  Visual Studio Code extension developed in TypeScript. It interacts with the VS Code API and implements a text processing engine based on Regular Expressions (Regex) for the automated detection and cleaning of source code (comments, logs, and emojis). Structured under a modular architecture with support for automated testing.

### ArgStats · Argentine football statistics

A data project about Argentine football, from the sources to a public website: it collects, cleans and unifies data from several providers into a single PostgreSQL database, keeps it up to date automatically, and publishes it as a statistics site, inspired in pages such as FBref. It covers the Liga Profesional, Primera Nacional, Primera B Metropolitana, Federal A and Copa Argentina. **Live demo:** [arg-stats.duckdns.org](https://arg-stats.duckdns.org)

- [ArgStats Web](https://github.com/smalirat/arg-stats)
  The statistics website: standings, results, and club, player and match pages. Built with Astro (server-side rendering) on top of a REST API in Node.js and Express, reading PostgreSQL on Supabase.
- [Arg Football Scrapper](https://github.com/smalirat/arg-football-scrapper)
  The project's central repository: scrapers and ETL per source that build the database, data checks, and links to the rest of the ecosystem (update pipeline and website).

### Torneo de Exalumnos · Amateur football league management

Web app to run a local league, built to replace the manual system based on the Excel workbooks it is run with today: seasons, fixtures, results, standings, top scorers, suspensions and the champions' history. **Demo:** [torneo-marianista-demo.duckdns.org](https://torneo-marianista-demo.duckdns.org)

---

📫 **Contact**
- 💼 [LinkedIn](https://www.linkedin.com/in/santiago-malirat-b18999286)
- 📧 [Email](mailto:santimalirat@gmail.com)
