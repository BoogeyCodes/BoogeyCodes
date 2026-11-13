# Hi, I'm Abdul Raheem

**Software Engineer · Backend, Full-Stack & AI coding-agent evaluation · Lahore, Pakistan · Open to freelance and remote work**

I have a vast experience building and operating backend and full-stack systems with C#, .NET,
ASP.NET Core, PostgreSQL and AWS-hosted infrastructure. I design REST APIs, service-layer workflows and
data-access patterns for operationally important software: monitoring systems, simulation platforms,
data pipelines and customer-facing products. I care about correctness, maintainability and release
quality, and I'm comfortable owning a feature from database schema to React component to CI pipeline
to production troubleshooting.

I also build **tooling for evaluating AI coding agents** — reading an agent's run, scoring it on a
quality rubric, comparing runs side by side, and running its code against tests in a sandbox — the
kind of work frontier AI training and evaluation teams do. Strong in Python and TypeScript, fluent
with shell, Git, Docker and test pipelines, and comfortable running and modifying real projects
locally.

📫 abdulraheem07170@gmail.com

---

## What I build

- **REST APIs and microservice-style backends** with ASP.NET Core, clear service boundaries, OpenAPI
  contracts and integration tests that boot the real application.
- **Data access that performs**: Entity Framework Core for the model, Dapper where the SQL needs to be
  explicit, PostgreSQL and SQL Server query tuning, Redis caching.
- **Authentication and authorization**: JWT, claims-based and policy-based access control, Auth0 and
  Azure AD integrations.
- **Real-time and background processing**: SignalR, hosted services, System.Threading.Channels
  pipelines, scheduled jobs and crawlers.
- **Frontends** in React with TypeScript, Redux Toolkit and Redux-Saga.
- **Cloud and delivery**: Docker, Kubernetes, Amazon EKS, AWS Lambda, Helm, Pulumi, GitLab CI/CD,
  Azure DevOps, structured logging with Serilog, monitoring with New Relic.
- **Automated testing**: unit and integration suites for APIs, CQRS handlers, persistence and
  authorization paths; Python tooling for test-data generation and regression reporting.

## Skills

| Area | Technologies |
| --- | --- |
| **Languages** | C#, Python, SQL, JavaScript, TypeScript |
| **.NET** | .NET 8, ASP.NET Core, Minimal APIs, Web API, MVC, Entity Framework Core, Dapper, MediatR (CQRS), FluentValidation, SignalR, LINQ, ADO.NET, WCF, Active Reports |
| **Frontend** | React, Redux, Redux Toolkit, Redux-Saga, HTML5, CSS3, Bootstrap, jQuery, AJAX, Vite |
| **Databases** | PostgreSQL, SQL Server, MySQL, Redis, MongoDB, DynamoDB, SQLite, query optimisation, schema design, Apache Solr |
| **Auth & security** | JWT, OAuth 2.0, Auth0, Azure AD, claims-based authorization, policy-based authorization |
| **Cloud & DevOps** | AWS (EC2, S3, Lambda, EKS, RDS, DynamoDB), Docker, Docker Compose, Kubernetes, Helm, Pulumi, GitLab CI/CD, GitHub Actions, Azure DevOps, IIS |
| **Observability** | Serilog, structured logging, New Relic, Sumo Logic, health checks, production debugging |
| **Testing** | xUnit, integration testing with WebApplicationFactory, pytest, Vitest, Testing Library, code coverage, regression automation |
| **Architecture** | REST, OpenAPI/Swagger, microservices, CQRS, vertical slices, repository pattern, dependency injection, OOAD, design patterns |
| **Practices** | Agile/Scrum, code review, root-cause analysis, defect reproduction, CI/CD, Git, Jira, Bitbucket |
| **Other** | Web crawling and scraping, Windows services, Shopify, Postman, Visual Studio, VS Code |

## AI coding-agent evaluation toolkit

A suite for reviewing AI coding agents — the workflow of rating, ranking and verifying agent runs.

| Project | What it is | Stack |
| --- | --- | --- |
| [**AgentScore**](https://github.com/BoogeyCodes/agentscore) | Web app to rate three agent runs on a 10-dimension rubric, rank them, and export the review | React, TypeScript |
| [**agentrubric**](https://github.com/BoogeyCodes/agentrubric) | Agent-evaluation **platform**: score & rank runs against a 10-dimension rubric, a web dashboard, a REST API, and a cross-evaluation agent leaderboard | Python, FastAPI, SQLite, Docker |
| [**runtrace**](https://github.com/BoogeyCodes/runtrace) | Normalise heterogeneous agent run transcripts into one schema **and a browser run-comparison dashboard**: metrics table, side-by-side bars, and shared-file detection | TypeScript, Vite, Docker |
| [**patchkit**](https://github.com/BoogeyCodes/patchkit) | Parse, summarise and apply the unified diffs agents produce | Python |
| [**sandrun**](https://github.com/BoogeyCodes/sandrun) | Sandbox-execution **service**: run agent work against tests (local or Docker), a web dashboard, a REST API, and pass-rate tracking across runs | Python, FastAPI, SQLite, Docker |
| [**difflens**](https://github.com/BoogeyCodes/difflens) | Side-by-side multi-run diff views of what each agent changed | TypeScript |

## Featured projects

| Project | What it is | Stack |
| --- | --- | --- |
| [**Gambit**](https://github.com/BoogeyCodes/gambit) | A chess engine you can play in the browser: a from-scratch, **perft-verified** legal move generator (matches the published node counts for Kiwipete et al.), alpha-beta search with piece-square evaluation, and a dependency-free click-to-play board | TypeScript, Vite, Vitest, zero runtime deps, Docker |
| [**Upcheck**](https://github.com/BoogeyCodes/upcheck) | Self-hosted uptime & incident monitor: a background scheduler probes endpoints on their interval, an up/down state machine with a failure threshold opens and resolves incidents, rolling uptime stats, a JSON API and a live server-rendered status page | ASP.NET Core 8, hosted BackgroundService, EF Core, SQLite, Serilog, xUnit, Docker |
| [**FairShare**](https://github.com/BoogeyCodes/fairshare) | Shared-expense tracker (Splitwise-style): groups, four split strategies (equal/exact/percent/shares) in integer cents, per-member balances, and a minimal "settle-up" that collapses debts into the fewest payments. JSON API **and** a server-rendered HTMX web UI | Python, FastAPI, SQLAlchemy 2.0, SQLite, Jinja2 + HTMX, Pydantic, pytest, Docker |
| [**TaskForge**](https://github.com/BoogeyCodes/taskforge) | Team project & issue-tracker API: JWT auth, projects/members/roles, Kanban boards, issues with labels/assignees/comments, filtered+paginated queries, and real-time board updates over SignalR | ASP.NET Core 8, MediatR (CQRS), FluentValidation, EF Core, SignalR, JWT, Serilog, xUnit, Docker |
| [**Trackpense**](https://github.com/BoogeyCodes/trackpense) | Personal finance tracker built entirely in C# with Blazor: transactions, budgets, and a live dashboard with inline-SVG charts | C# / .NET 8, Blazor Server, EF Core, SQLite, Docker |
| [**pulseboard**](https://github.com/BoogeyCodes/pulseboard) | Real-time fleet monitoring console: telemetry pipeline, alert rules, role-based operations, live dashboard | ASP.NET Core 8, SignalR, Channels, EF Core + Dapper, JWT, React 19, TypeScript, Redux Toolkit, Recharts, Docker |
| [**shortlink-api**](https://github.com/BoogeyCodes/shortlink-api) | Production-shaped URL shortener: CQRS slices, validation pipeline, RFC 7807 errors, integration tests | ASP.NET Core 8 Minimal API, MediatR, FluentValidation, EF Core, Serilog, xUnit, Docker |
| [**statemachine**](https://github.com/BoogeyCodes/statemachine) | A declarative finite state machine: states, transitions, guards and callbacks | Python, pytest |
| [**expreval**](https://github.com/BoogeyCodes/expreval) | Safe arithmetic expression evaluator (shunting-yard), functions, variables, no `eval` | Python, pytest |
| [**globlite**](https://github.com/BoogeyCodes/globlite) | Glob matcher (`*`, `**`, `?`, classes, braces) compiled to RegExp | TypeScript, tsup, Vitest |
| [**tinycsv**](https://github.com/BoogeyCodes/tinycsv) | RFC 4180 CSV parser and stringifier with object mapping | TypeScript, tsup, Vitest |
| [**Outcome**](https://github.com/BoogeyCodes/outcome) | Result and Option functional types: Map, Bind, Match | C# / .NET 8, xUnit |
| [**tabulate**](https://github.com/BoogeyCodes/tabulate) | CLI rendering CSV/TSV as aligned ASCII or Markdown tables | C# / .NET 8, xUnit |
| [**cronparse**](https://github.com/BoogeyCodes/cronparse) | Parse cron expressions, compute the next run times, and describe them in plain English | Python, pytest |
| [**fuzzykit**](https://github.com/BoogeyCodes/fuzzykit) | String similarity and fuzzy search: Levenshtein, Jaro-Winkler, Sorensen-Dice, ranked search | TypeScript, tsup, Vitest |
| [**bytefmt**](https://github.com/BoogeyCodes/bytefmt) | A `DataSize` value type **and DiskScope**, a disk-usage explorer built on it: a scan engine + an ASP.NET Core dashboard and REST API showing the biggest folders, file types and files | C# / .NET 8, ASP.NET Core, xUnit, Docker |
| [**quickpoll**](https://github.com/BoogeyCodes/quickpoll) | Polls API: create polls, vote once per voter, live results with percentages; validations and a clean JSON error contract | Ruby on Rails 7.1, SQLite, Minitest |
| [**recall**](https://github.com/BoogeyCodes/recall) | Spaced-repetition flashcards driven by the SM-2 algorithm; signals and localStorage | Angular 18, TypeScript, Jasmine |
| [**contrastcheck**](https://github.com/BoogeyCodes/contrastcheck) | WCAG colour-contrast checker: live ratio, accessibility-level breakdown, suggested accessible colour | React 19, TypeScript, Vitest |
| [**gridcalc**](https://github.com/BoogeyCodes/gridcalc) | Spreadsheet formula engine: Pratt-parsed formulas, ranges, a dependency graph with incremental recompute, circular-reference detection | TypeScript, tsup, Vitest |
| [**sketchkit**](https://github.com/BoogeyCodes/sketchkit) | Probabilistic data structures (Bloom filter, Count-Min Sketch, HyperLogLog) with statistical guarantee tests | Python, pytest |
| [**ratekit**](https://github.com/BoogeyCodes/ratekit) | Zero-dependency keyed rate limiter: token-bucket and sliding-window, LRU key eviction, ESM + CJS | TypeScript, tsup, Vitest, GitHub Actions matrix |
| [**flagpole**](https://github.com/BoogeyCodes/flagpole) | Feature-flag service with deterministic percentage rollouts | Python, FastAPI, Pydantic, pytest |
| [**jsondiff**](https://github.com/BoogeyCodes/jsondiff) | CLI that structurally diffs two JSON files by path; packable as a dotnet tool | C# / .NET 8, System.Text.Json, xUnit |
| [**logsift**](https://github.com/BoogeyCodes/logsift) | Zero-dependency CLI to filter and summarise JSON-lines and plain-text logs | Python 3.10+, pytest, ruff, GitHub Actions matrix |

More coming regularly. Each repo has a README that explains the design decisions, a test suite and CI.

📚 **Deeper write-ups** for every project — purpose, stack, architecture and the decisions behind
them — live in [**project-docs**](https://github.com/BoogeyCodes/project-docs).

## Experience

- **Software Engineer, NorthBay Solutions** (Dec 2022 – present). C#/.NET backend services and REST
  APIs, CQRS workflows, EF Core and Dapper over PostgreSQL, JWT and claims-based auth, automated test
  coverage, GitLab CI/CD and AWS deployments, production troubleshooting.
- **Software Engineer, Digital Mandee** (Dec 2021 – Nov 2022). Backend components for simulation and
  operational software, MediatR command/query handlers, PostgreSQL optimisation, Python test tooling.
- **Intern, Alchemative** (Jun 2021 – Oct 2021). Shopify and web application projects.

**BSc Computer Science**, Lahore Garrison University (2018 – 2022).

## Working with me

I take on freelance and contract work: new backend services, API design, modernising legacy .NET
applications, performance and database work, adding tests and CI to codebases that have none, and
full-stack features with React. Email me at **abdulraheem07170@gmail.com** with a short description
of what you need and I'll reply within a day.
