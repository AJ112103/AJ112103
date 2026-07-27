Building AI-native software for healthcare. Mostly databases, agents, and the unglamorous plumbing.

### What I'm building

**[CoralEHR](https://coralehr.com)** is an EHR for behavioral health clinicians, running in production. I own the AI documentation agent, the billing engine, and the compliance code that stops either of them from doing something regrettable.

**[BonfireDB](https://bonfiredb.dev)** is an open-source clinical backend where governance lives in the database instead of a middleware layer everyone forgets to call. Agents can propose writes. They cannot approve their own. It passes 133/133 HL7 SQL-on-FHIR conformance tests, which I enjoyed far more than is reasonable.

Before that I owned the classification and policy engine at ArcOne: hybrid PII detection, and a policy platform built so governance teams could stop filing tickets at engineers.

### Currently nerding out on

- Making agent context **cited and scoped**, so you can point at the exact row that justified an answer
- Whether MCP tool surfaces actually help agents. I [pre-registered a study](https://github.com/coralehr/fhir-mcp-eval) and measured it instead of guessing. They do, by 9.5 points, on 43% less payload
- Hybrid retrieval that fuses vector and full-text search, then refuses to hand back anything you were never allowed to see
- Row-level security that fails closed from the very first row, because the alternative is a genuinely bad week

### Usually working in

`Python` `TypeScript` `PostgreSQL` `AWS` `FHIR` `MCP`

I ship fast, break prod occasionally, and write the test that stops it happening twice.

More at **[aamerjalan.me](https://aamerjalan.me)**
