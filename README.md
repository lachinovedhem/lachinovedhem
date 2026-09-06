## Adham Lachinov

**Software architect & backend engineer — C#/.NET and SQL Server.** Based in Berlin.

I build systems where **behaviour lives in data, not in code** — the systems a retail business
actually runs on: enterprise ERP, point of sale with fiscal compliance, warehouse flow, identity
and access, reporting. **40+ production systems** over eight years — most of them still running,
most of them closed source.

- 🏭 **Software Architect** at a national grocery retail chain — a platform of internal
  applications behind one identity and permission layer, serving 150+ stores.
- 🧾 **Founder & architect of Simple ERP** — a 20-module commercial ERP with 1,000+ users,
  and a **state-approved fiscal POS** deployed at 200+ businesses.
- 🤖 I build **Model Context Protocol** servers so AI agents can operate an ERP safely —
  and so AI-generated code stays inside the architecture rules.

### 🔧 Reference implementations

Almost everything I have built is either an employer's intellectual property or a certified
commercial product. The [Simple ERP](https://github.com/simpler-az) repositories are private by
design and will stay that way — it is a licensed, state-certified product with a fiscal path in it.

So I rebuild the **engines** from scratch instead: the logic, with none of the original code or
data. Each one ships in **both C# and TypeScript**, so the architecture is the subject rather than
the language.

| | |
|---|---|
| **[parent-child-sync](https://github.com/lachinovedhem/parent-child-sync)** | Offline-first synchronisation between a centre and many nodes — watermark deltas, tombstones for deletes, idempotent replay. A store keeps selling while the network is gone and reconciles when it returns. |
| **[sql-table-sync](https://github.com/lachinovedhem/sql-table-sync)** | Table replication driven by a configuration table: adding a synced table is a row, not a release. |
| **[sql-drilldown-reports](https://github.com/lachinovedhem/sql-drilldown-reports)** | Self-describing report rows — each row names the report that opens when you tap it, so an entire drill-down hierarchy is metadata instead of screens. |
| **[standards-mcp](https://github.com/lachinovedhem/standards-mcp)** | An MCP server that serves coding standards and checklists to AI agents. |

### 📄 [Portfolio → lachinovedhem.github.io](https://lachinovedhem.github.io)

Problem, architectural decision, outcome and stack for each system — with the mechanism behind
every number, so the figures can be argued with rather than taken on trust.

### 🇩🇪 [alida → alidadeutsch.simpler.az](https://alidadeutsch.simpler.az/)

A German study app I built for myself — vocabulary, grammar, flashcards, pronunciation.
React 19 + Vite, no backend, works offline as a PWA. [Source here.](https://github.com/lachinovedhem/german-booklet)

### 🎓 [Teaching → youtube.com/@elachinov](https://www.youtube.com/@elachinov)

Five recorded course series I ran live for my team — [SQL](https://www.youtube.com/playlist?list=PLuBzlr1yovEdV5u4NQwYZFOB5J1tZIObv),
[REST API](https://www.youtube.com/playlist?list=PLuBzlr1yovEcvEqYSlsHpyGzk8LtqKU1r), and three on the product itself.
Recorded so people could go over a topic at home rather than ask twice. In Azerbaijani.

---

**Daily:** C# · .NET 10 · ASP.NET Core · Minimal API · Native AOT · gRPC · EF Core · Dapper ·
MS SQL Server · T-SQL · PostgreSQL · Oracle · Clean Architecture · DDD

**Working level:** Blazor · React · Next.js · Docker · CI/CD · Azure DevOps · Entra ID · xUnit

**Not claiming:** large-scale cloud infrastructure. I would rather say so than find out in month two.

---

📍 Berlin · 🇩🇪 German residence permit · 🗣️ Azerbaijani (native), Turkish C2, English B2, German A2 and studying

[LinkedIn](https://www.linkedin.com/in/elachinov/) · [lachinov.edhem@gmail.com](mailto:lachinov.edhem@gmail.com)
