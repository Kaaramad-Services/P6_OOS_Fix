<div align="center">

<img src="https://img.shields.io/badge/Version-Beta-4f7ef8?style=for-the-badge" alt="Version">
<img src="https://img.shields.io/badge/Primavera_P6-Compatible-22c97a?style=for-the-badge" alt="P6 Compatible">
<img src="https://img.shields.io/badge/AI_Providers-12-9b7ff0?style=for-the-badge" alt="AI Providers">
<img src="https://img.shields.io/badge/No_Installation_Required-Offline_Ready-f0a832?style=for-the-badge" alt="Offline">
<img src="https://img.shields.io/badge/License-Contact_Author-e8504a?style=for-the-badge" alt="License">

<br/><br/>

```
  ██████╗  ██████╗ ███████╗    ███████╗██╗██╗  ██╗███████╗██████╗      █████╗ ██╗
 ██╔═══██╗██╔═══██╗██╔════╝    ██╔════╝██║╚██╗██╔╝██╔════╝██╔══██╗    ██╔══██╗██║
 ██║   ██║██║   ██║███████╗    █████╗  ██║ ╚███╔╝ █████╗  ██████╔╝    ███████║██║
 ██║   ██║██║   ██║╚════██║    ██╔══╝  ██║ ██╔██╗ ██╔══╝  ██╔══██╗    ██╔══██║██║
 ╚██████╔╝╚██████╔╝███████║    ██║     ██║██╔╝ ██╗███████╗██║  ██║    ██║  ██║██║
  ╚═════╝  ╚═════╝ ╚══════╝    ╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝    ╚═╝  ╚═╝╚═╝
```

# OOS Fixer AI
### AI-Powered Out-of-Sequence Schedule Repair for Primavera P6

*The first OOS tool that thinks like a Senior Planning Engineer — not a rule table*

<br/>

[📥 **Download**](#-download) &nbsp;·&nbsp;
[🖼️ **Screenshots**](#-screenshots) &nbsp;·&nbsp;
[✅ **Features**](#-features) &nbsp;·&nbsp;
[🤝 **Commercial Use**](#-commercial-use--licensing) &nbsp;·&nbsp;
[👤 **Author**](#-about-the-author)

<br/>

> ⚠️ **Commercial use, integration into software products, or redistribution requires written permission from the author.**
> See [Commercial Use & Licensing](#-commercial-use--licensing) below.

</div>

---

## 🔴 The Problem Every Planning Engineer Knows

You run the schedule update. P6 flags out-of-sequence activities. Now you have to go through each one — manually checking the predecessor, understanding the relationship, deciding the right fix. With a live project schedule, this can mean hours of work every update cycle, and it takes real planning expertise to get right.

Existing tools apply fixed mechanical rules that don't understand **why** an activity went out of sequence, what industry it's in, whether it's on the critical path, or whether the fix will create new problems downstream.

**OOS Fixer AI solves this differently.**

---

## ✅ Features

<table>
<tr>
<td width="50%">

**📂 Works with your actual P6 data**
- Drop a Primavera P6 XER file directly
- Or paste TASK + TASKPRED tables from Excel
- Instant file validation — shows which tables were found

</td>
<td width="50%">

**🏗️ Understands your project**
- Set your industry, contract type, schedule level, and phase
- AI reasons with your project context, not generic defaults
- Supports Oil & Gas, Civil, EPC, Power, Marine, and more

</td>
</tr>
<tr>
<td width="50%">

**🧠 AI that reasons, not a rule table**
- Uses full surrounding network context for each OOS pair
- Reads WBS hierarchy, total float, actual vs planned dates
- Flags critical path relationships before making any decision

</td>
<td width="50%">

**📋 Expert-grade output**
- Action per relationship: Retype / Delete / Add Lag / Flag for Review
- Full expandable justification with planning logic per row
- Downstream impact check — does the fix create new OOS?

</td>
</tr>
<tr>
<td width="50%">

**🤖 Your AI engine, your cost**
- Bring your own API key from any of 12 supported providers
- Free options available — Gemini, Groq, Cerebras
- Keys stored only in your browser, never on any server

</td>
<td width="50%">

**📤 Ready to re-import into P6**
- Exports a corrected XER file with all original P6 fields intact
- Also exports a full Expert Report CSV for sign-off documentation
- Re-import via File → Import → Activity Relationships → Update Existing

</td>
</tr>
</table>

---

## 🖼️ Screenshots

<details open>
<summary><b>Main Interface — Load & Analyze</b></summary>
<br/>

```
┌────────────────────────────────────────────────────────────────────────────┐
│  ⬡ OOS Fixer AI  [Beta]                                    [⚙ Claude ●]   │
│  Expert planning assistant — Primavera P6 out-of-sequence repair           │
├────────────────────────────────────────────────────────────────────────────┤
│  [ 📄 XER file ]   [ 📊 Excel / paste ]                                    │
│                                                                            │
│  ┌──────────────────────────────────────────────────────────────────────┐  │
│  │                          ↑                                           │  │
│  │              Drop your .xer file here or click to browse            │  │
│  │                    Primavera P6 XER export                           │  │
│  └──────────────────────────────────────────────────────────────────────┘  │
│  ✓ JNGLF.xer (2057 KB)                                                    │
│  Tables found: CURRTYPE, PROJECT, TASK, TASKPRED, PROJWBS ...             │
│  ✓ TASK table    ✓ TASKPRED table    10,572 data rows detected             │
│                                                                            │
│  ┌─ Project context ──────────────────────────────────────────────────┐   │
│  │  Industry: [Oil & Gas — Onshore ▼]   Contract: [FIDIC Yellow ▼]   │   │
│  │  Level:    [Level 3 — Control   ▼]   Phase:    [Construction  ▼]   │   │
│  └────────────────────────────────────────────────────────────────────┘   │
│                                                                            │
│  ┌─────────────────────────────────────────────────────────────────────┐  │
│  │                  ▶  Analyze with AI — Expert Mode                   │  │
│  └─────────────────────────────────────────────────────────────────────┘  │
└────────────────────────────────────────────────────────────────────────────┘
```

</details>

<details>
<summary><b>AI Engine Setup — 12 Providers, Free Options Included</b></summary>
<br/>

```
┌────────────────── AI Engine Configuration ─────────────────────────────────┐
│                                                                            │
│  ★ Free API keys available — no credit card needed:                       │
│  ┌─────────────────────────┐  ┌─────────────────────────┐                 │
│  │ ✨ Gemini  Free forever │  │ ⚙️ Groq    Free forever  │                 │
│  └─────────────────────────┘  └─────────────────────────┘                 │
│                                                                            │
│  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐        │
│  │🌐        │ │⚙️        │ │🧠        │ │✨        │ │🤖        │        │
│  │OpenRouter│ │Groq      │ │Cerebras  │ │Gemini    │ │Claude    │        │
│  │★ BEST   │ │Free·Fast │ │Fastest·F │ │Free tier │ │Anthropic │        │
│  └──────────┘ └──────────┘ └──────────┘ └──────────┘ └──────────┘        │
│  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐        │
│  │⚡        │ │𝕏        │ │🔎        │ │🔍        │ │🌊        │        │
│  │ChatGPT   │ │Grok      │ │Perplexity│ │DeepSeek  │ │Mistral   │        │
│  └──────────┘ └──────────┘ └──────────┘ └──────────┘ └──────────┘        │
│                                                                            │
│  API Key: [••••••••••••••••••••••••••••••••]  Get key ↗                   │
│  Model:   [google/gemini-2.0-flash-001 ▼]                                 │
│                                                                            │
│  [ 💾 Save & remember ]   [ Clear key ]                                    │
└────────────────────────────────────────────────────────────────────────────┘
```

</details>

<details>
<summary><b>Live AI Analysis — 4-Step Process</b></summary>
<br/>

```
┌──────────────────── ◌ AI Expert Analysis in Progress ──────────────────────┐
│                                                                            │
│  ✓  1   Parsing schedule & building network context                        │
│         2,084 activities · 2,098 relationships · 159 WBS nodes             │
│                                                                            │
│  ✓  2   Detecting out-of-sequence relationships                            │
│         3 OOS relationships found out of 2,098 total                       │
│                                                                            │
│  ◌  3   AI expert analysis — reasoning with full planning context          │
│         Sending context to AI engine...                                    │
│                                                                            │
│  ·  4   Downstream impact check                                            │
│         Waiting...                                                         │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

</details>

<details>
<summary><b>Results — Expert Analysis with Full Justification</b></summary>
<br/>

```
 OOS FOUND    RETYPE    DELETE    FOR REVIEW    DOWNSTREAM ALERTS
     3           0         3           0               0

┌───────────────┬───────────────┬──────────┬────────┬───────┬──────────────┐
│ PREDECESSOR   │ SUCCESSOR     │ REL      │ ACTION │ FLOAT │ SUMMARY      │
├───────────────┼───────────────┼──────────┼────────┼───────┼──────────────┤
│ 487870        │ 487874        │ PR_SS    │[DELETE]│  N/A  │ RFQ completed│
│ ⚠ CRITICAL   │ PREPARE RFQ   │ ──────   │        │       │ 10 months    │
│ RECEIPT OF   │ FOR LUGS      │          │        │       │ before pred  │
│ PRELIM DRWGS │ ✓ Complete    │          │        │       │ planned start│
│               │               │          │        │       │[▼ Justify]  │
├───────────────┼───────────────┼──────────┼────────┼───────┼──────────────┤
│ 487867        │ 487878        │ PR_SS    │[DELETE]│  N/A  │ Parallel     │
│ ⚠ CRITICAL   │ RFQ SENT TO   │ ──────   │        │       │ workstreams  │
│ RFQ SENT TO  │ BIDDERS       │          │        │       │ — different  │
│ BIDDERS       │ ✓ Complete    │          │        │       │ WBS packages │
│               │               │          │        │       │[▼ Justify]  │
├───────────────┼───────────────┼──────────┼────────┼───────┼──────────────┤
│ 487898        │ 487853        │ PR_SS    │[DELETE]│  N/A  │ Logically    │
│ ⚠ CRITICAL   │ RFQ FOR       │ ──────   │        │       │ reversed —   │
│ AWARD ALL    │ VALVES        │          │        │       │ RFQ cannot   │
│ ENG. MAT POs │ ✓ Complete    │          │        │       │ follow Award │
│               │               │          │        │       │[▼ Justify]  │
└───────────────┴───────────────┴──────────┴────────┴───────┴──────────────┘

[ 📄 Export fixed XER ]   [ 📊 Export expert report (CSV) ]
```

</details>

<details>
<summary><b>Expandable Expert Justification (click any row)</b></summary>
<br/>

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ ▼ Full justification — Pred: 487898  →  Succ: 487853                       │
│                                                                             │
│  CHRONOLOGY CHECK                                                           │
│  Successor (Valve RFQ) completed 2025-07-05. Predecessor (Award POs)       │
│  not planned to start until 2025-09-10. RFQ was complete 2 months          │
│  before PO Award was even planned to begin.                                 │
│                                                                             │
│  PLANNING LOGIC                                                             │
│  Relationship is directionally reversed — in any procurement workflow,      │
│  RFQ issuance must precede bid evaluation, then PO award. A PO Award       │
│  activity cannot logically drive an RFQ. Entire Valve procurement           │
│  chain (RFQ → TBE → PO → Drawings) is independently complete.              │
│                                                                             │
│  INDUSTRY PRACTICE — Oil & Gas Onshore                                     │
│  Standard Oil & Gas EPC procurement sequence requires RFQ → TBE →         │
│  PO Award → Vendor Data. This relationship contradicts that sequence.      │
│                                                                             │
│  FLOAT & CRITICAL PATH IMPACT                                               │
│  Predecessor carries 0 days float. Deletion removes a logic constraint     │
│  that was never valid. Critical path position of 487898 is unaffected.     │
│                                                                             │
│  DOWNSTREAM RISK                                                            │
│  None. Valve package is a self-contained completed chain.                   │
│                                                                             │
│  ALTERNATIVE APPROACH                                                       │
│  If deletion is not acceptable, change to FF linking PO Award              │
│  completion to Valve chain completion — but deletion is cleaner.            │
└─────────────────────────────────────────────────────────────────────────────┘
```

</details>

---

## 📥 Download

> **This tool is provided for individual planning engineers for personal and project use.**
> Commercial integration or redistribution requires written permission — see [Licensing](#-commercial-use--licensing).

**To use:**
1. Download `OOS_Fixer_AI.html` from [Releases](https://github.com/Kaaramad-Services/OOS-Fixer-AI/releases)
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari)
3. Get a free API key from any provider below
4. Drop your XER file and analyze

**No installation. No server. No subscription.**

### Free API Keys (no credit card needed)

| Provider | Sign up | Notes |
|----------|---------|-------|
| ✨ **Gemini** | [aistudio.google.com](https://aistudio.google.com/app/apikey) | Free forever · 15 req/min |
| ⚙️ **Groq** | [console.groq.com](https://console.groq.com/keys) | Free forever · Very fast |
| 🧠 **Cerebras** | [cloud.cerebras.ai](https://cloud.cerebras.ai) | Free forever · Fastest |

---

## 🤝 Commercial Use & Licensing

<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   This tool is FREE for individual planning engineers to use     ║
║   on their own projects.                                         ║
║                                                                  ║
║   The following require WRITTEN PERMISSION from the author:      ║
║                                                                  ║
║    ✗  Integrating this tool into a commercial software product  ║
║    ✗  Redistributing or reselling this tool                     ║
║    ✗  Bundling with paid services or platforms                  ║
║    ✗  White-labelling or rebranding                             ║
║    ✗  Embedding in company-wide internal tooling without        ║
║       prior agreement                                            ║
║                                                                  ║
║   To request a commercial licence or partnership:               ║
║                                                                  ║
║        📧  suleman.muhammad@hotmail.com                          ║
║        🔗  github.com/Kaaramad-Services                          ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

</div>

---

## 👤 About the Author

<div align="center">

**Muhammad Suleman**
*Project Manager / Senior Planning Engineer*
*Kaaramad Services — Saudi Arabia*

[![GitHub](https://img.shields.io/badge/GitHub-Kaaramad--Services-4f7ef8?style=flat-square&logo=github)](https://github.com/Kaaramad-Services)
[![Email](https://img.shields.io/badge/Email-Contact_Me-22c97a?style=flat-square&logo=microsoft-outlook)](mailto:suleman.muhammad@hotmail.com)

</div>

<br/>

Planning engineer with 8+ years across Oil & Gas (Saudi Aramco), infrastructure, renewable energy, and EPC projects. Developer of open-source planning tools for scheduling professionals:

| Tool | Purpose |
|------|---------|
| 🛠️ [**P6 Cost Writer**](https://kaaramad-services.github.io/P6-Cost-Writer/) | BOQ-to-P6 cost loading — generates XER import file from any cost source |
| 📊 [**Productivity Planning Console**](https://kaaramad-services.github.io/Project_Productivity_Dashboard/) | AACE 25R-03 duration & man-hour calculator with P6 CSV export |
| ⚖️ [**EOT & Delay Analysis Assistant**](https://kaaramad-services.github.io/EOT-Delay-Assistant/) | FIDIC-compliant EOT claim preparation — XER to formal claim document |
| 🔧 **OOS Fixer AI** *(this tool)* | AI-powered OOS repair for Primavera P6 — reasons like a senior planner |

---

<div align="center">

*Built by a planning engineer, for planning engineers.*

⭐ **If this saved you time on a project, star the repo** ⭐

[🐛 Report a Bug](https://github.com/Kaaramad-Services/OOS-Fixer-AI/issues) &nbsp;·&nbsp; [💡 Suggest a Feature](https://github.com/Kaaramad-Services/OOS-Fixer-AI/issues) &nbsp;·&nbsp; [📧 suleman.muhammad@hotmail.com](mailto:suleman.muhammad@hotmail.com)

<br/>

© 2026 Muhammad Suleman · Kaaramad Services · All rights reserved

</div>
