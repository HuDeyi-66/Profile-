[English](README.md) | [简体中文](README.zh-CN.md)

# Hi, I'm Hu Deyi 👋

## ⚓ About me

I'm an undergraduate student at **Dalian Maritime University**, majoring in
**English (Foreign-related Rule of Law)**.

I work and experiment at the intersection of **social research, artificial
intelligence, governance and information systems**.

My current interests can be summarized into five areas:

- ⚖️ **Socio-legal Studies**
- 🤖 **Artificial Intelligence**
- 🏛️ **Governance**
- 🔍 **Critical Sociology**
- 🌏 **Cross-cultural Studies**

I'm particularly interested in how institutions, rules, evidence, technologies
and social structures interact — and how some of these relationships can be
translated into systems that are **retrievable, structured, verifiable and
reusable**.

## Research interests

`Socio-legal Studies` · `Artificial Intelligence` · `Governance` ·
`Critical Sociology` · `Cross-cultural Studies`

## 🌊 What I'm building

### [SeaFlow](https://github.com/HuDeyi-66/SeaFlow)

**SeaFlow** is my long-term legal AI and evidence infrastructure project.

It explores how heterogeneous sources can be transformed into reliable,
traceable and machine-usable evidence while preserving provenance, citation
and evidentiary boundaries.

Current principles:

> **Evidence First · Traceable Sources · Small Core · Extensible Skills**

The SeaFlow base runtime is maintained privately. Its public Skills are
designed to remain independently usable.

### 📘 [ShanHai（海珊）](https://github.com/HuDeyi-66/Shan_Hai_Code_Skill) — Legal Text Evidence Skill

**ShanHai** is an open-source, standalone Skill for legal-text evidence.

It focuses on:

- source retrieval
- exact text extraction
- structural recognition
- native text citation
- ambiguity handling
- explicit refusal when evidence is insufficient

Its core principle is:

> **Find the source before answering the question.**

ShanHai can be used independently of the private SeaFlow base runtime.

### 📊 [LuoHai（海珞）](https://github.com/HuDeyi-66/Luo_Hai_Tables_Skill) — Tabular Evidence Skill

**LuoHai** is an open-source, standalone Skill for structured and tabular
evidence.

It is designed to work with heterogeneous spreadsheets, reports, tables and
structured datasets while preserving their source boundaries and
traceability.

Its core principle is:

> **Organizing evidence ≠ creating evidence.**

LuoHai can be used independently of the private SeaFlow base runtime.

### 🔭 Upcoming Skills (Reserved / Planned)

The following four Skills are **reserved and planned**. Their repositories are the
canonical future implementation homes and are intentionally documentation-first at
this stage: the initial commits fix the Skill contract, architectural boundary and
planned public interface before implementation begins. No working functionality is
claimed for them yet.

Together they describe how evidence is organised once it has been acquired:
**WenHai** registers durable documentary assets, **XianHai** places evidence and
events in time, **JueHai** connects them through typed relationships and
provenance paths, and **ChenHai** judges whether the resulting evidence is
sufficient and asks for recovery when it is not.

#### 🕰️ [XianHai（海现）](https://github.com/HuDeyi-66/Xian_Hai_Time_Skill) — Temporal Evidence Orchestration Skill

**XianHai** organizes evidence through time.

- temporal ordering of evidence and events; event timelines
- evidence-state transitions; temporal validity and staleness awareness
- missing-period and temporal-gap detection; gap-driven recheck / recovery requests

It does not create evidence, does not decide legal conclusions and does not
replace source retrieval. Timeline and temporal orchestration belong to XianHai;
general evidence relationships and provenance paths belong to JueHai.

#### 🔎 [ChenHai（海琛）](https://github.com/HuDeyi-66/Chen_Hai_Explore_Skill) — Evidence Exploration and Evaluation Skill

**ChenHai** asks whether the evidence is sufficient.

- evidence coverage assessment; insufficiency detection
- retrieval-risk and recall-risk signals
- benchmark precision / recall evaluation when qrels exist; runtime coverage proxies otherwise
- identification of unresolved evidence gaps, with retry / recovery recommendations

It does not retrieve evidence itself, does not invent missing evidence and does
not silently fill gaps. ChenHai detects insufficiency and requests recovery;
XianHai decides orchestration; retrieval Skills perform retrieval.

#### 🗂️ [WenHai（海玟）](https://github.com/HuDeyi-66/Wen_Hai_Files_Skill) — Documentary Asset Skill

**WenHai** preserves documents as durable evidence assets.

- documentary asset registration; durable file identity
- source metadata preservation; artifact tracking; document provenance
- stable documentary references for downstream Skills

Target materials include speeches, policy documents, reports, public statements,
meeting minutes, and institutional and enterprise records. WenHai is not a generic
file manager, not a cloud-drive replacement and not a temporal reasoner.

#### 🕸️ [JueHai（海珏）](https://github.com/HuDeyi-66/Jue_Hai_Graph_Skill) — Evidence Graph / Provenance Graph Skill

**JueHai** connects evidence through relationships.

- typed nodes for evidence, claims, sources and events
- typed relations such as `supports`, `contradicts`, `derived_from`, `contained_in`, `references`, `corroborates`, `qualifies`
- provenance-path construction and auditable graph traversal

It does not replace a general-purpose knowledge graph platform, does not own
temporal orchestration and does not infer unsupported edges or convert
correlation into evidentiary support.

## 🧭 How I think about these projects

A recurring structure behind my work is:

**Social Reality → Institutions & Rules → Evidence → Information Systems → Artificial Intelligence**

I'm interested in both directions of this chain:

- how social and institutional structures can be represented computationally;
- how computational systems reshape the production, organization and use of evidence.

This is where my interests in **Socio-legal Studies, Artificial Intelligence,
Governance, Critical Sociology and Cross-cultural Studies** intersect.

## 🛠 Selected projects

- 🌊 [SeaFlow](https://github.com/HuDeyi-66/SeaFlow) — public entry point for the SeaFlow project and its architecture.
- 📘 [ShanHai（海珊）](https://github.com/HuDeyi-66/Shan_Hai_Code_Skill) — evidence-oriented retrieval for textual sources.
- 📊 [LuoHai（海珞）](https://github.com/HuDeyi-66/Luo_Hai_Tables_Skill) — evidence-oriented processing for structured and tabular sources.
- 🧭 [SeaFlow Project Control](https://github.com/HuDeyi-66/seaflow-library-project-control) — public project-control and review site for SeaFlow development.
- 🕰️ [XianHai（海现）](https://github.com/HuDeyi-66/Xian_Hai_Time_Skill) — *Reserved / Planned* — temporal evidence orchestration: evidence states, timelines and temporal gaps.
- 🔎 [ChenHai（海琛）](https://github.com/HuDeyi-66/Chen_Hai_Explore_Skill) — *Reserved / Planned* — evidence coverage, insufficiency detection and recovery recommendations.
- 🗂️ [WenHai（海玟）](https://github.com/HuDeyi-66/Wen_Hai_Files_Skill) — *Reserved / Planned* — durable documentary asset intake and document provenance.
- 🕸️ [JueHai（海珏）](https://github.com/HuDeyi-66/Jue_Hai_Graph_Skill) — *Reserved / Planned* — provenance-aware evidence graphs with typed nodes and relations.

## 📖 Research × Engineering

I see research and engineering as connected parts of the same process:

> **Observe → Understand → Formalize → Build → Re-examine**

Research helps identify structures that matter.

Engineering forces those structures to become explicit.

Once a system is built, its limitations often reveal new research questions.

Some repositories here are stable tools.
Some are research prototypes.
Some are experiments.

Together, they document how ideas gradually become systems.

## 🌱 Currently exploring

- evidence-oriented AI systems
- retrieval and provenance
- modular AI Skills
- lightweight and local models
- multimodal research workflows
- AI-supported research infrastructure
- the social consequences of intelligent systems

## 🤖 Models I commonly work with

`GPT` · `DeepSeek` · `Kimi`

## 🧩 Five tags

**⚖️ Socio-legal Studies**
Institutions, rules, legal practices, and their relationship with social structures.

**🤖 Artificial Intelligence**
Retrieval, agents, language models, evidence systems, and human–AI interaction.

**🏛️ Governance**
Institutional design, coordination, regulation, and the governance of emerging technologies.

**🔍 Critical Sociology**
Power, institutions, technology, social structure, and the assumptions embedded in apparently neutral systems.

**🌏 Cross-cultural Studies**
How meaning, norms and institutions travel across languages, legal cultures and social contexts.

## What I'm exploring

How legal and social research can work with AI without hiding the evidence
chain behind the answer.
