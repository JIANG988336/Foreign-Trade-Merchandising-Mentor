# China Sourcing Agent Skill · 采购代理跟单全流程知识库

[![Skill](https://img.shields.io/badge/AI-Skill-blue)]() [![Content](https://img.shields.io/badge/Content-Markdown_only-9cf)]() [![Language](https://img.shields.io/badge/Lang-中文为主%20%2F%20EN%20key_phrases-orange)]()

An AI-ready, markdown-based operational skill that turns a zero-experience team into a working **China sourcing agency** — the complete merchandising playbook for buying-agent businesses (find suppliers, buy, inspect, ship on behalf of overseas clients, earn commission), benchmarked against the real operating model of [JingSourcing](https://jingsourcing.com).

> 本仓库是一个纯 Markdown 的 AI Skill（无代码）：一份可直接落地的采购代理跟单全流程操作手册，可作为 Claude / WorkBuddy 等 Agent 的 Skill 加载，也可直接作为团队的 SOP 手册使用。

---

## What this skill does / 这个 Skill 解决什么问题

A sourcing agent stands **between** an overseas buyer and a Chinese factory — and takes risk on neither side's terms. This handbook codifies the entire operating system:

| # | Stage | What's covered |
|---|---|---|
| ① | Inquiry intake | Client profiling, fake-inquiry screening, NDA & service agreement |
| ② | Requirement & RFQ | Spec sheets, market compliance (CE / FCC / SASO / NOM / INMETRO), RFQ packaging |
| ③ | Supplier development | Multi-channel sourcing, background checks (video factory audit), A/B/C grading |
| ④ | Quoting & negotiation | Like-for-like price comparison, commission models, price-validity tactics |
| ⑤ | Samples | Self-check before forwarding, sealed-sample protocol, re-sample fees |
| ⑥–⑦ | Order & contract | PI essentials, deposit-gated PO, exclusivity & tooling-ownership clauses |
| ⑧ | Production follow-up | Milestone evidence (photos, not promises), change-order discipline, delay escalation |
| ⑨ | Inspection | **AQL 2.5 / 4.0, Level II** (ANSI/ASQ Z1.4 / GB/T 2828.1) with a printable sampling table, DUPRO & FRI |
| ⑩ | Packing & marks | Compliance labels per destination market, FSC, IPPC, carton data verification |
| ⑪ | Shipping & customs | Freight benchmarking, 4-photo loading protocol, legal export declaration only |
| ⑫ | Documentation | CI / PL / BL / CO consistency checklist, telex-release control |
| ⑬ | Payments | Deposit-before-PO, balance-before-release, commission settlement, FX risk |
| ⑭ | Claims | Evidence-first triage, three-party cost sharing, supplier downgrading |
| ⑮ | Retention & review | Post-delivery follow-up, reorder triggers, project retrospectives |

## Highlights / 核心亮点

- **Dual revenue model** (the JingSourcing playbook, verified): Basic plan = transparent **5% service fee, min USD 100**; Pro plan = **0 fee, margin built into unit price** — with the commission-vs-buy-sell risk differences spelled out (title, deposit risk, quality liability, tax)
- **15 form templates** with full field designs (RFQ, supplier due-diligence, price comparison, sample ledger, PI, purchase contract, production tracker, AQL inspection report, shipping instruction, payment ledger, claim record, project retro…) — copy fields straight into Excel
- **Bilingual scripts** (🇨🇳/🇬🇧) for every stage: deposit chasing, delay reporting, price objection handling, refusing under-declaration, claims triage
- **30-day onboarding plan** for new merchandisers, day by day, with assessments and 5 zero-tolerance red lines
- **6 real-world case studies** in a five-part format (background → problem → wrong approach → right approach → lesson): sudden price hike, failed final inspection, mid-production change order, post-shipment quality claim, delayed balance payment, supplier deposit runaway
- **Market-fit by region**: EU (CE, EPR, FSC), US (FCC, CPSC), Middle East (SABER/SASO, embassy legalization), LatAm (NOM, INMETRO) — because the target clients buy into all four regions

## Use as an AI Skill / 作为 Skill 使用

Compatible with agent platforms that load markdown skills (e.g. Claude Skills, WorkBuddy):

```
your-agent/
└── skills/
    └── china-sourcing-agent/
        ├── SKILL.md      ← this repo, drop in as-is
        └── (no code — pure knowledge)
```

Or simply use it as a standalone SOP handbook for a sourcing / merchandising team.

## File map / 文件说明

| File | Purpose |
|---|---|
| `SKILL.md` | The full handbook (≈38,000 Chinese characters), front-mattered for agent loading |
| `README.md` | This file |
| `LICENSE` | MIT |

## Data grounding / 数据依据

Commission benchmarks (3%–15% tiered by order size), the Basic/Pro dual model, AQL 2.5 inspection standard and "no supplier disclosure" practice are grounded in the publicly published pricing and FAQ pages of JingSourcing and current industry fee surveys (2025–2026), not invented figures.

## Author's note / 作者说明

Built for a trade company launching a sourcing-agency business line from zero. Every process is written to be executable as-is ("照着做就能跑通"): each stage carries a step table (step / action / owner / deadline / deliverable), a risk table with concrete mitigations, and negotiation scripts. Feedback and issue reports welcome.

---

## License

MIT — free to use, adapt, and build upon. Attribution appreciated.
