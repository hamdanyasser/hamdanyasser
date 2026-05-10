![Plate 01 — Subject: Yasser Hamdan](./assets/hero.svg)

<br/>

> *Subject is a Python and Odoo ERP developer with practical AI delivery experience.* <br/>
> *Currently a third-year Data Science student at the University of Sciences and Arts in Lebanon (USAL), graduating June 2026.* <br/>
> *Working at the seam where business systems meet AI agents — Odoo modules in production, LangGraph agents in development.*

<br/>

![Bill of Materials — career arc](./assets/journey.svg)

<br/>

![Plate 02 — Operating State](./assets/divider-02-now.svg)

<br/>

| &nbsp; | &nbsp; |
|:---|:---|
| **`IN BUILD`** &nbsp; | Polishing **AtlasBrief** for a public demo. Refactoring the LangGraph state machine so every agent decision is observable from the UI. |
| **`IN REVIEW`** &nbsp; | *Designing Data-Intensive Applications* (Kleppmann). Plus the LangGraph release notes — they ship fast. |
| **`IN STUDY`** &nbsp; | Production patterns for multi-agent systems. Cost optimisation for two-model LLM routing at scale. |

<br/>

![Plate 03 — Featured Work](./assets/divider-03-work.svg)

<table>
<tr>
<td width="50%">
<a href="https://github.com/hamdanyasser/atlasbrief-travel-agent">
<img src="./assets/module-01-atlasbrief.svg" alt="MOD.01 — AtlasBrief"/>
</a>
</td>
<td width="50%">
<a href="https://github.com/hamdanyasser/atelier-real-estate-estimator">
<img src="./assets/module-02-atelier.svg" alt="MOD.02 — Atelier"/>
</a>
</td>
</tr>
<tr>
<td width="50%">
<a href="https://github.com/hamdanyasser/support-triage-cockpit">
<img src="./assets/module-03-triage.svg" alt="MOD.03 — Triage Cockpit"/>
</a>
</td>
<td width="50%">
<a href="https://github.com/hamdanyasser/NLP-NER-Project">
<img src="./assets/module-04-ner.svg" alt="MOD.04 — Biomedical NER"/>
</a>
</td>
</tr>
<tr>
<td width="50%">
<a href="https://github.com/hamdanyasser/auction-system-odoo">
<img src="./assets/module-05-odoo.svg" alt="MOD.05 — Odoo Auction"/>
</a>
</td>
<td width="50%">
<a href="https://github.com/hamdanyasser/debugmaster-android">
<img src="./assets/module-06-debugmaster.svg" alt="MOD.06 — DebugMaster"/>
</a>
</td>
</tr>
</table>

<sub>↑ &nbsp; each module links to its repository.  full index at <a href="https://github.com/hamdanyasser?tab=repositories">github.com/hamdanyasser</a></sub>

<br/>

![Plate 04 — Subsystem Detail](./assets/divider-04-system.svg)

> *Code shows what was built. Architecture shows how it was reasoned.*

![AtlasBrief — request flow](./assets/architecture.svg)

<details>
<summary><sub>↳ &nbsp; <code>NOTE.A1</code> &nbsp;—&nbsp; <i>why two-model routing</i></sub></summary>

<br/>

A lightweight model handles structured extraction from the user query — cheap, fast, deterministic, Pydantic-validated at the boundary. A stronger model handles synthesis, where reasoning quality matters and latency is acceptable. Per-request token logging shows the routing genuinely saves cost without measurable quality loss on extraction. The agent's tool decisions are stateful and traceable end-to-end.

</details>

<br/>

![Plate 05 — Operating Metrics](./assets/divider-05-stats.svg)

![Operating metrics readout](./assets/metrics.svg)

<br/>

![Plate 06 — Certifications](./assets/divider-06-certifications.svg)

<table>
<tr>
<td valign="top" width="50%">

**`CERT.001`** &nbsp;—&nbsp; **IBM — RAG and Agentic AI**
*<sub>Professional Certificate · 9 courses</sub>*

> RAG pipelines, vector databases, LangChain, LangGraph, CrewAI, AutoGen, BeeAI, MCP, multi-agent systems.

<sub>Issued Mar 2026  ⋅  external sign-off</sub>

</td>
<td valign="top" width="50%">

**`CERT.002`** &nbsp;—&nbsp; **Anthropic — Claude Code in Action**
*<sub>Official Anthropic certification</sub>*

> AI-assisted development, tool chaining, context management, MCP integration.

<sub>Issued Nov 2025  ⋅  external sign-off</sub>

</td>
</tr>
</table>

<br/>

![Plate 07 — Contact](./assets/divider-07-reach.svg)

![Contact — drawing title block](./assets/footer.svg)

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0B1F33?style=for-the-badge&logo=linkedin&logoColor=EDE6D6&labelColor=0B1F33)](https://www.linkedin.com/in/yasser-hamdan063/)
&nbsp;
[![Email](https://img.shields.io/badge/EMAIL-0B1F33?style=for-the-badge&logo=gmail&logoColor=EDE6D6&labelColor=0B1F33)](mailto:hamdanyasser2005@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GITHUB-E25E1E?style=for-the-badge&logo=github&logoColor=EDE6D6&labelColor=E25E1E)](https://github.com/hamdanyasser)

</div>
