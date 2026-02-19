# SOC 2 Quality Guild

**Practitioner-driven standards for SOC 2 report reliability**

A community creating standardized evaluation criteria to help GRC and TPRM practitioners assess how much weight to give a SOC 2 report when making vendor trust decisions.

🌐 **Website:** [s2guild.org](https://s2guild.org)  
💬 **Community:** [Join Slack](https://join.slack.com/t/soc2qualityguild/shared_invite/zt-3on72t7v8-qgN0~aHuYM4gbDR2uDnRlA) 

---

## What We Do

SOC 2 has become the most widely adopted security assurance framework for SaaS companies. But rapid growth in demand has created a quality gap — reports vary dramatically in rigor, and the ecosystem lacks standardized ways to tell the difference.

**The SOC 2 Quality Guild provides:**
- 📋 **[SOC 2 Reliability Rubric](https://s2guild.org/#rubric)** - 11 standardized signals across Structure, Substance, and Source
- 🛠️ **[Tactical Response Guide](https://s2guild.org/#responding)** - 8 practical approaches for addressing quality concerns
- 🤝 **[Community Projects](https://s2guild.org/#projects)** - Vote on and contribute to ecosystem improvements

---

## The Problem

TPRM teams make critical vendor trust decisions based on SOC 2 reports, but face fundamental challenges:

- **Quality varies widely** - from rigorous professional audits to compliance theater
- **No shared evaluation criteria** - practitioners rely on vibes, anecdotes, or brand recognition
- **Information asymmetry** - hard to distinguish high-quality audits from low-effort check-the-box exercises
- **Inconsistent decisions** - different teams assess the same report differently

This creates uncertainty for practitioners, inconsistent feedback for vendors, and an ecosystem that struggles to differentiate quality work.

---

## Our Approach

### SOC 2 Reliability Rubric

A practical framework with **11 signals across 3 pillars** to evaluate report quality:

#### 🟢 **Structure** (3 signals)
Does the report include required components and maintain professional consistency?
- S1: Required Auditor's Report Section Structure
- S2: Management's Assertion Completeness  
- S3: Inconsistent Language Across Report Sections

#### 🔵 **Substance** (4 signals)
Do the controls, testing, and conclusions logically align and support each other?
- S4: System Description Specificity
- S5: Control-to-Criteria Mapping Logic
- S6: Vague or Conflicting Control Descriptions
- S7: Test Procedure Detail and Specificity

#### 🟣 **Source** (4 signals)
What credentials, independence factors, and track record may affect report credibility?
- S8: CPA Firm Registration, Peer Review Enrollment & Results
- S9: CPA-to-SOC Reports Issued Ratio
- S10: CPA Firm Leadership & Report Signer Experience
- S11: Use of a GRC Tool

**→ [Explore the full rubric](https://s2guild.org/#rubric-explore)**

---

## AI-Assisted Analysis

Use the SOC 2 Quality Guild's Claude Code skill to analyze any SOC 2 report against the full Reliability Rubric. The skill evaluates all 11 signals across Structure, Substance, and Source and produces a structured assessment with ratings, evidence, and recommended actions.

### Option 1: Clone the Repo (slash command)

```bash
git clone https://github.com/SOC-2-Quality-Guild/s2guild.org.git
cd s2guild.org
claude
```

Then in Claude Code:

```
/soc2-review /path/to/vendor-soc2-report.pdf
```

### Option 2: Plugin Marketplace (no clone needed)

```
/plugin marketplace add SOC-2-Quality-Guild/s2guild.org
/plugin install soc2-review@s2guild
/soc2-review:soc2-review /path/to/vendor-soc2-report.pdf
```

### Option 3: Direct Skill Reference (power users)

Add this repo as a skill source in your own project's Claude Code settings to make `/soc2-review` available in any project.

### What You Get

- **11 signals evaluated** across Structure, Substance, and Source pillars
- **GREEN/YELLOW/RED ratings** for each signal with specific evidence from the report
- **Verification checklists** with direct links for Source pillar manual review items
- **Prioritized recommended actions** calibrated to the severity of findings

> **Note:** Claude reads PDFs natively. Most SOC 2 reports (up to ~100 pages) work without any preprocessing.

---

## Contributing

We welcome contributions from GRC practitioners, TPRM professionals, auditors, and anyone who cares about improving security assurance quality.

### Ways to Contribute

1. **Vote on Community Projects** - Visit [s2guild.org/#projects](https://s2guild.org/#projects) and upvote initiatives that matter to you
2. **Propose New Projects** - [Open an issue](https://github.com/SOC-2-Quality-Guild/s2guild.org/issues/new?labels=community-project) with your idea
3. **Share Examples** - Contribute real-world examples (anonymized) of quality signals
4. **Improve the Rubric** - Suggest refinements to evaluation criteria
5. **Build Tools** - Create automation, templates, or integrations

**→ [View all projects and vote](https://s2guild.org/#projects)**

---

## Rubric Versioning

We maintain **official versions** in this repository while active collaboration happens in **Google Docs**.

### Versioning Workflow

1. **Active Development** - Community discusses in shared Google Doc
2. **Consensus Decision** - Working group agrees changes are ready
3. **Version Lock** - Export to GitHub as new versioned release
4. **Changelog** - Document what changed and why
5. **Announcement** - Publish to community via Slack, website
6. **Iterate** - Continue refining in Google Doc for next version

This ensures practitioners have **stable references to cite** while enabling **ongoing collaborative improvement**.

**→ [View version history](rubric/CHANGELOG.md)**

---

## Principles

### Focus on Education, Not Accusations
We evaluate the **reliability of reports as evidence** — not the trustworthiness of individual vendors or auditors. Our frameworks provide repeatable, verifiable signals that any practitioner can apply.

### Practitioner-Driven
The Guild exists to serve practitioners making real vendor trust decisions. Community members set priorities through voting, discussion, and direct contribution.

### Market Pressure for Quality
By giving practitioners tools to consistently evaluate report quality, we create incentives that improve outcomes for everyone — vendors, auditors, and the organizations that rely on their work.

### Transparent and Open
Our work is open-source (CC BY-SA 4.0), community-governed, and built in public. Anyone can review, adapt, or build upon what we create.

---

## Get Involved

### Join the Community
- 💬 **Slack** - [Join here](https://join.slack.com/t/soc2qualityguild/shared_invite/zt-3on72t7v8-qgN0~aHuYM4gbDR2uDnRlA) for real-time discussions
- 🌐 **Website** - [s2guild.org](https://s2guild.org)

---

## License

This work is licensed under **[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)**.

You are free to:
- ✅ **Share** - Copy and redistribute in any medium or format
- ✅ **Adapt** - Remix, transform, and build upon the material

Under the following terms:
- **Attribution** - Give appropriate credit, provide a link to the license
- **ShareAlike** - Distribute adaptations under the same license
- **No additional restrictions** - You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits

© 2026 SOC 2 Quality Guild

---

## Acknowledgments

Built by practitioners, for practitioners. Many thanks to the community members who contribute expertise, examples, mentorshop, and feedback to this growing community.

---

## Contact

- 🌐 Website: [s2guild.org](https://s2guild.org)
- 💬 Community: [Join Slack](https://join.slack.com/t/soc2qualityguild/shared_invite/zt-3on72t7v8-qgN0~aHuYM4gbDR2uDnRlA) | [GitHub](https://github.com/SOC-2-Quality-Guild)
- 📧 Email: [contact info TBD]

---

**Together, we're building a more transparent, consistent, and quality-driven trust ecosystem.**
