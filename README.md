<div align="center">

# Taghi Molavi (تقی مولوی)

### AI Systems Architect · GEO & AI Visibility Researcher
**Builder of measurement, agent and media infrastructure.**

[![Website](https://img.shields.io/badge/Molavi.pro-0b1220?style=for-the-badge&logo=googlechrome&logoColor=white)](https://molavi.pro)
[![Research](https://img.shields.io/badge/Research%20Initiatives-de8814?style=for-the-badge&logo=readthedocs&logoColor=white)](https://molavi.pro/research)
[![Architecture](https://img.shields.io/badge/Ecosystem-Architecture%20Map-blueviolet?style=for-the-badge&logo=diagram&logoColor=white)](https://github.com/tmolavi/geo-scope/blob/main/docs/ECOSYSTEM_ARCHITECTURE.md)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/taqimolavi)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/taqimolavi)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0009-6253-5354)

*یاد بگیر، یاد بده و اثری ماندگار خلق کن — Learn. Share. Create a lasting impact.*

</div>

---

## 🏛️ Selected Projects

A curated selection of core open-source engineering initiatives spanning empirical AI measurement, static audit intelligence, autonomous site remediation, agent infrastructure, and developer skill distribution.

```text
Discovery & Measurement          Audit & Diagnostics           Remediation & Infrastructure
───────────────────────          ───────────────────           ────────────────────────────
     [GEO-Scope]           ──▶      [SAGE Audit]         ──▶          [SiteProbe]
(Empirical AI Visibility)        (SEO/AEO/GEO Audits)          (Autonomous Crawl & Patch)
                                                                            │
                                                                            ▼
                                                                     [Hamzad Gateway]
                                                               (Enterprise Agent OS Case Study)
                                                                            │
                                                                            ▼
                                                                  [Agent Skills Hub]
                                                             (Multi-Agent Skill Distribution)
```

---

### 1. [GEO-Scope](https://github.com/tmolavi/geo-scope)
**Empirical AI Answer Visibility Measurement Framework**
- **Role**: Observes, records, and quantifies entity mentions, recommendations, citations, and textual attributions across generative AI answer engines (Perplexity, Gemini Grounding) and parametric LLMs (GPT-4o, Claude).
- **Core Technology**: Python · Unicode Multi-Lingual Normalizer · Zero-Silent Fallback · Deterministic Replay · SHA-256 Verified Releases.
- **Evidence Artifact**: Evaluated across 45,000+ live observations in the *Global AI Answers Benchmark 2026.2*.

### 2. [SAGE Audit](https://github.com/tmolavi/sage-audit)
**SEO / AEO / GEO Audit Intelligence Engine**
- **Role**: Static diagnostic engine evaluating website crawlability, semantic extractability, JSON-LD Schema entity graphs, and citation survival proxies to understand and diagnose why sites fail to be cited by AI engines.
- **Core Technology**: Python · AST HTML Parser · 4-Layer Diagnostic Scoring · CLI & FastMCP Server.

### 3. [SiteProbe](https://github.com/tmolavi/siteprobe)
**Autonomous Website Crawling, Diagnostics & Code Remediation Platform**
- **Role**: Crawls web applications, analyzes AI bot access policies (`/llms.txt`, `robots.txt`), and executes automated AST code and configuration patches with atomic rollback safeguards.
- **Core Technology**: Go · Python · Playwright Automation · MCP Remediation Tools.

### 4. [Hamzad AI Gateway Resources](https://github.com/tmolavi/hamzad-ai-gateway-resources)
**Private AI Agent Infrastructure & Operating System (Architecture Case Study)**
- **Role**: High-reliability enterprise AI gateway and agent execution runtime providing dynamic latency-based fallback routing, token optimization, and governance.
- **Scope**: Open architectural specifications, routing policies, and design patterns.

### 5. [MCP Agent Skills Hub](https://github.com/tmolavi/mcp-agent-skills-hub)
**Distribution Layer for Reusable AI Agent Skills & MCP Tools**
- **Role**: Standardized, production-tested skill catalog for AI coding agents (Claude Code, Cursor, OpenAI Codex, Antigravity).
- **Scope**: Unified skill schemas, MCP configuration templates, and workflow patterns.
### 2️⃣ Agent Engineering & Skills Stack

Production-ready skills, workflow patterns, and token-optimized developer resources for autonomous coding agents.

| Repository | Purpose & Technical Role | Target Agents | Coverage |
| :--- | :--- | :---: | :---: |
| [**`scholar-provenance`**](https://github.com/tmolavi/scholar-provenance) | Portable AI Agent Skill transforming repositories, datasets, and benchmarks into traceable, peer-review-ready academic papers with automated academic distribution kits and zero citation fabrication. | Claude Code · Antigravity · Hermes · Codex · MCP | 17-Stage Pipeline · 13 Gates · v0.4.0 |
| [**`bale-bot-skills`**](https://github.com/tmolavi/bale-bot-skills) | Production skills, webhooks, state machines, and MiniApp patterns for Bale Messenger bots. | Claude Code · Cursor · Codex · Antigravity | 4 Skills · PHP / Python / TS / React |
| [**`mcp-agent-skills-hub`**](https://github.com/tmolavi/mcp-agent-skills-hub) | Curated catalog of production agent skills and MCP configuration templates. | Claude Code · Cursor · Codex · Antigravity | 20+ Skills · Multi-runtime |
| [**`n8n-agent-skills`**](https://github.com/tmolavi/n8n-agent-skills) | Production n8n workflow architecture, node routing, linting, and error-handling skills. | Claude Code · Codex · OpenCode | Enterprise n8n Patterns |
| [**`lean-agent-skills`**](https://github.com/tmolavi/lean-agent-skills) | Token-efficient, low-context agent skills optimized for reduced prompt overhead and fast execution. | Cursor · Copilot · Antigravity | Context-Compressed Skills |
| [**`agent-project-discovery-skill`**](https://github.com/tmolavi/agent-project-discovery-skill) | Universal workspace startup and codebase orientation skill for automated agent onboarding. | Claude Code · Cursor · Codex | Multi-language Discovery |
| [**`awesome-skills`**](https://github.com/tmolavi/awesome-skills) | Community-curated index of Agent Skills, MCP tools, and developer workflows. | Multi-Agent | Curated Catalog |

---

### 3️⃣ Applications, Tooling & Engines

Specialized engines, Laravel packages, and application backends powered by the AI Visibility Stack.

| Repository | Purpose & Technical Role | Tech Stack | Status |
| :--- | :--- | :---: | :---: |
| [**`laravel-ai-summary`**](https://github.com/tmolavi/laravel-ai-summary) | Provider-agnostic, multi-fallback AI summarization engine for Laravel (OpenAI, Gemini, Claude, Groq, Mistral). | PHP 8.2+ · Laravel 10/11 | 8 tests · CI Verified |
| [**`geo-aeo-news-engine`**](https://github.com/tmolavi/geo-aeo-news-engine) | Autonomous news rewriting, digital PR syndication, and entity-optimized press release engine. | Python · DOCX · JSON-LD | Operational Tool |
| [**`ivna-app`**](https://github.com/tmolavi/ivna-app) | Intelligent news aggregation and multilingual publishing mobile application. | Flutter / Dart · Clean Architecture | Application Client |
| [**`hamzad-ai-gateway-resources`**](https://github.com/tmolavi/hamzad-ai-gateway-resources) | Public architectural patterns, fallback routing schemas, and latency optimization templates for AI gateways. | Architecture · YAML / JSON | Open Specifications |

---

### 4️⃣ Enterprise AI & Industrial Intelligence Stack (هوش مصنوعی سازمانی و اتصال ERP)

Governed, auditable, and local-first integration platforms connecting enterprise databases, ERPs, and industrial systems to AI Executive Intelligence without numeric hallucination or raw database exposure.

| Repository | Purpose & Technical Role | Tech Stack | Evidence & Status |
| :--- | :--- | :---: | :---: |
| [**`iranian-enterprise-ai-bridge`**](https://github.com/tmolavi/iranian-enterprise-ai-bridge) | Open-source enterprise platform connecting Iranian ERP/CRM/BPMS (Rahkaran, Chargoon, Shomaran, Sepidar, MSSQL) to AI Executive Intelligence with deterministic metric calculations, subledger-to-GL reconciliation, and local on-prem LLM orchestration. | TypeScript · Node.js · Docker | 13 tests · [100-Question CEO Benchmark Catalog](https://github.com/tmolavi/iranian-enterprise-ai-bridge/blob/main/docs/fa/CEO-QUESTIONS.md) |

---

## 🔬 Epistemic Principles & Research Stance

* **Empirical Evidence Over Speculation**: Every published metric is tied to verbatim, preserved API payloads (`raw_responses.jsonl`) verifiable offline.
* **No Secret Algorithm Claims**: We measure observable model outputs under documented prompts; we never claim to possess or reverse-engineer private AI ranking algorithms.
* **Cryptographic Immutability**: All benchmark releases include bit-level SHA-256 checksums to ensure zero data drift.
* **Zero Silent Fallback**: Live empirical runs strictly record errors rather than substituting mock or synthetic data.

---

## 🤝 Enterprise & Research Collaboration

Open for research initiatives, technical discussions, and architecture advisory in:

* **Empirical AI Visibility Measurement**: Benchmark protocol design, multi-provider observation pipelines, and citation analysis.
* **GEO & AEO Research**: Semantic extractability, JSON-LD entity graph structuring, and AI crawler accessibility.
* **AI Systems Architecture**: Enterprise AI gateways, dynamic model routing, and autonomous agent tooling.

**Contact**:
- **Primary Website**: [molavi.pro](https://molavi.pro)
- **Research Initiatives**: [molavi.pro/research](https://molavi.pro/research)
- **ORCID**: [0009-0009-6253-5354](https://orcid.org/0009-0009-6253-5354)
- **Direct Email**: `taqimolavi@gmail.com`
من در تقاطع **بهینه‌سازی برای موتورهای هوش مصنوعی (GEO)**، **سئوی مبتنی بر هوش مصنوعی (AEO)**، **زیرساخت‌های ایجنت‌های نرم‌افزاری** و **سیستم‌های خودکار اصلاح کد** فعالیت می‌کنم. تمامی ابزارها به صورت منبع‌باز و همراه با داده‌های تجربی و آزمون‌های قابل بازتولید منتشر شده‌اند:

- **پایپ‌لاین دیده‌پذیری هوش مصنوعی**: `geo-scope` (بنچ‌مارک تجربی)، `answerpath-geo` (کشف پرسش‌ها)، `sage-audit` (موتور ارزیابی ۳ لایه)، `siteprobe` (ربات اصلاح خودکار کد) و `mcp-geo-server`.
- **هوش مصنوعی سازمانی و اتصال ERP**: بستر متن‌باز `iranian-enterprise-ai-bridge` جهت اتصال امن و دترمینستیک نرم‌افزارهای سازمانی و کارخانجات به هوش مصنوعی مدیران ارشد با حفظ کامل حریم داده‌ها.
- **زیرساخت ایجنت‌ها**: مهارت‌های تخصصی ایجنت برای Claude Code، Cursor، Codex و Antigravity (شامل `scholar-provenance` جهت تبدیل پژوهش و کد به مقالات علمی معتبر، `bale-bot-skills`، `n8n-agent-skills` و `mcp-agent-skills-hub`).
- **یادداشت‌ها و مقالات پژوهشی**: در [Molavi.pro فارسی](https://molavi.pro/fa) در دسترس است.

</details>

<details>
<summary>Türkçe | Türkçe Açıklama</summary>

### Taghi Molavi | Yapay Zekâ Mimarı ve GEO Araştırmacısı

Üretken Arama Motoru Optimizasyonu (GEO), Cevap Motoru Optimizasyonu (AEO), yapay zekâ aracı altyapıları ve otomatik kod düzeltme sistemleri üzerine açık kaynaklı araçlar ve ampirik benchmarklar geliştiriyorum:

- **Yapay Zekâ Görünürlük Yığını**: `geo-scope`, `answerpath-geo`, `sage-audit`, `siteprobe`, `mcp-geo-server`.
- **Ajan Mühendisliği**: Cursor, Claude Code, Codex ve Antigravity için üretim odaklı ajan becerileri (`scholar-provenance` bilimsel makale üretim becerisi dahil).
- **Araştırmalar**: [Molavi.pro Türkçe](https://molavi.pro/tr).

</details>

<details>
<summary>Azərbaycan dili | Azərbaycan dilində</summary>

### Tağı Mövləvi | Süni İntellekt Memarı və GEO Tədqiqatçısı

Süni intellekt axtarış sistemlərində görünürlük (GEO/AEO), avtonom agent infrastrukturları və kod təmiri sistemləri üzrə açıq mənbəli alətlər hazırlayıram:

- **Süni İntellekt Görünürlük Şəbəkəsi**: `geo-scope`, `answerpath-geo`, `sage-audit`, `siteprobe`.
- **Agent Mühəndisliyi**: `scholar-provenance` (elmi məqalə və tədqiqat bacarığı), `bale-bot-skills`, `mcp-agent-skills-hub`.
- **Tədqiqat və Məqalələr**: [Molavi.pro Azərbaycan](https://molavi.pro/az).

</details>

<details>
<summary>العربية | التعريف باللغة العربية</summary>

### تقي مولوي | مهندس ذكاء اصطناعي وباحث في ظهور الذكاء الاصطناعي (GEO/AEO)

أعمل على تطوير أنظمة مفتوحة المصدر واختبارات تجريبية قابلة لإعادة الإنتاج حول تحسين محركات الذكاء الاصطناعي (GEO)، وبنية الوكلاء الأذكياء (Agent Infrastructure)، والأدوات البرمجية الذكية:

- **حزمة ظهور الذكاء الاصطناعي**: `geo-scope` و `answerpath-geo` و `sage-audit` و `siteprobe` و `mcp-geo-server`.
- **بنية الوكلاء الأذكياء**: مهارات متقدمة للوكلاء الذاتيين (بما في ذلك `scholar-provenance` لإعداد الأوراق والبحوث الأكاديمية الموثقة).
- **الأبحاث والملاحظات**: متوفرة على [Molavi.pro العربية](https://molavi.pro/ar).

</details>

---

<div align="center">
<sub>Licensed under the <a href="https://opensource.org/licenses/MIT">MIT License</a> — Copyright (c) 2026 <a href="https://molavi.pro">Taghi Molavi (تقی مولوی)</a></sub>
</div>
