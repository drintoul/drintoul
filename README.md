# David R. Rintoul, CISSP

**AI Solutions Architect building secure, self-hosted agentic AI and RAG systems for production use.**

I build AI systems inside organizations: language models connected to trusted
data, APIs, and enterprise tools, put into production where people depend on
them, and designed so every answer can be traced back to its sources.

What sets the work apart is the combination behind it — hands-on AI
engineering, CISSP security practice, and enterprise data and architecture
experience — so security, privacy, and auditability are design requirements,
not compliance steps added later.

## Featured Projects

### [Is It Canadian?](https://github.com/drintoul/is-it-canadian)

Evidence-grounded agentic AI that searches and scrapes authoritative sources, uses an LLM for classification, then deterministically verifies its cited evidence before accepting the result.

### [Local AI Stack](https://github.com/drintoul/local-ai-stack)

Self-hosted local AI stack in a single Docker Compose deployment: Ollama model inference, web scraping and Playwright browser automation exposed to agents over MCP, SearXNG search, and Langfuse observability — no outbound LLM calls.

### [Chatbot Concierge](https://github.com/drintoul/chatbot-concierge)

Self-hosted RAG chatbot that indexes a website once — scrape, chunk, embed, and store — then answers visitor questions from that persistent corpus through two checkpointed LangGraph workflows, using local Ollama models and a self-hosted Firecrawl pipeline. It includes an embeddable chat widget and an audit log of every question and outcome.

### [Neighbourhood Similarity Finder](https://github.com/drintoul/neighbours)

Enter an address and find nearby neighbourhoods with a similar mix of amenities — restaurants, parks, waterfront, transit — ranked by cosine similarity over OpenStreetMap POI profiles. No API keys, no accounts, no quotas.

### [Tableau XML Parse](https://github.com/drintoul/tableau-xml-parse)

Built to recover dependency visibility from an enterprise Tableau environment where hundreds of unmanaged, unversioned workbooks had accumulated on network shares, allowing database teams to assess the downstream impact of schema changes before breaking dashboards.

## What I'm Building

I designed, built, and operate a self-hosted agentic AI platform used for real-world travel research and planning — the architecture is documented in [voyages-by-dave](https://github.com/drintoul/voyages-by-dave). It combines:

- LangGraph orchestration
- Model Context Protocol (MCP) tools
- Retrieval-augmented generation (RAG)
- Qdrant vector search
- FastAPI services
- Ollama local inference
- Web search and scraping
- Source validation and citation tracking
- Docker-based deployment

Reusable agentic workflows have reduced research tasks that previously took **2–3 hours to under 10 minutes**.

## Security & Governance

Security is part of the architecture, not a separate compliance step.

As a CISSP, my work has included:

- Vulnerability management and threat-intelligence integration
- Secure, self-hosted AI architecture for sensitive data
- Permissioned access to tools and data sources
- Data governance, lineage, privacy, and auditability
- Enterprise security, retention, reliability, and operational risk

At **The Walt Disney Company**, I built an AWS-hosted historical
vulnerability pipeline and automated correlation between internal
vulnerability data and external threat intelligence to improve
remediation prioritization.

## Technology

**AI & Agents**
LangGraph · MCP · FastMCP · RAG · Ollama · Qdrant · Embeddings

**Security & Governance**
CISSP · Vulnerability Management · Threat Intelligence · Data Governance ·
Privacy · Auditability · Operational Risk

**Development**
Python · FastAPI · Flask · Streamlit · REST APIs · JupyterLab

**Data & Analytics**
PostgreSQL · MongoDB · Neo4j · MySQL · SQLAlchemy · Tableau · Alteryx · Dataiku

**Infrastructure & DevOps**
Docker · Linux · AWS · GitHub Actions · CI/CD · Cloudflare Tunnels

## Background

My background spans AI architecture, cybersecurity, enterprise data systems,
analytics, product development, and technical program leadership.

Earlier in my career, I held product, program, and alliance leadership roles
at **Microsoft** and **Siemens**.

I then spent nearly a decade in safety-critical commercial diving and
hyperbaric operations, where reliability, procedure, training, compliance,
and operational risk were everyday responsibilities.

More recently, my consulting work has included:

- **Charles Schwab** — Python-based Tableau lineage and dependency
  analysis across hundreds of workbooks
- **Evernorth Health Services** — rebuilt Neo4j ingestion pipelines,
  improving reliability from approximately 65% to 99.9%
- **The Walt Disney Company** — built an AWS-hosted pipeline correlating
  internal vulnerability scans with external threat intelligence under strict
  data-retention requirements, improving remediation prioritization and saving
  10+ hours of manual work per month

Today, I apply that combination of enterprise technology, security,
governance, and operational-risk experience to building practical AI systems.

## Education & Credentials

- **B.A.Sc., Computer Engineering** — University of Waterloo
- **CISSP** — Certified Information Systems Security Professional
- **AWS Certified AI Practitioner**
- **CDMP** — Certified Data Management Professional
- **CAIP** — Certified Artificial Intelligence Practitioner

## Elsewhere

[Website](https://davidrintoul.info) ·
[LinkedIn](https://www.linkedin.com/in/david-rintoul/) ·
[Resume](https://davidrintoul.info/resume.pdf)
