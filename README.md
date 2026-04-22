<p align="center">
  <h1 align="center">MAMA Mental Health</h1>
  <h3 align="center"><em>AI crisis detection with mandatory 988 handoff. No one falls through the cracks.</em></h3>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-GPL--3.0-blue.svg" alt="License"></a>
  <img src="https://img.shields.io/badge/cost-Free_Forever-green" alt="Free">
  <img src="https://img.shields.io/badge/status-Active-brightgreen" alt="Active">
  <a href="https://mama.oliwoods.ai"><img src="https://img.shields.io/badge/Built_with-MAMA-8b5cf6" alt="Built with MAMA"></a>
  <a href="https://cofounder.software"><img src="https://img.shields.io/badge/Powered_by-CoFounder-06b6d4" alt="Powered by CoFounder"></a>
  <a href="https://oliwoodsfoundation.org"><img src="https://img.shields.io/badge/OliWoods-Foundation-10b981" alt="OliWoods Foundation"></a>
</p>

<p align="center">
  <a href="#the-problem">Problem</a> &bull;
  <a href="#the-solution">Solution</a> &bull;
  <a href="#agents">Agents</a> &bull;
  <a href="#quick-start">Quick Start</a> &bull;
  <a href="#contributing">Contribute</a>
</p>

---

> **1 in 5 US adults** lives with a mental illness. Crisis hotlines have **40+ minute wait times**. People in crisis need immediate support — not a hold queue. And most don't even know what resources exist in their community.

## The Problem

Six AI agents that detect crisis signals, connect people with help, and provide evidence-based support tools. **This is NOT therapy.** This is a navigation and support tool that ensures no one falls through the cracks.

**CRITICAL:** Any crisis signal triggers **MANDATORY handoff to 988 Suicide & Crisis Lifeline**. This cannot be disabled, overridden, or turned off by any user, admin, or configuration change.

## Agents

| Agent | Role |
|-------|------|
| **CrisisDetector** | Monitors language for risk signals; MANDATORY 988/VCL handoff |
| **PeerMatcher** | Connects users with trained peer support specialists |
| **TherapistFinder** | Searches provider directories by insurance/specialty/location |
| **CBTCoach** | Guided CBT psychoeducation exercises (not treatment) |
| **MoodTracker** | Daily check-ins, pattern detection, insight generation |
| **ResourceNavigator** | Local/national mental health resources, hotlines, support groups |

**Slack command:** `/mentalhealth [situation]`

## Safety

**MANDATORY crisis handoffs (cannot be disabled):**
- **988 Suicide & Crisis Lifeline** — call or text 988
- **Veterans Crisis Line** — 988 then press 1
- **Crisis Text Line** — text HOME to 741741

Any mention of suicidal ideation, self-harm, or psychosis triggers immediate handoff. The AI provides support and navigation. Humans provide care.

## Data Sources

- SAMHSA treatment locator
- Psychology Today provider directory
- NAMI resource database
- 988 Lifeline integration

## Quick Start

```bash
git clone https://github.com/OliWoods-Org/mama-mental-health.git
cd mama-mental-health
# Full setup instructions coming soon
# Or use via MAMA Slack: see agent commands below
```

## Use via MAMA

If you're a [MAMA](https://mama.oliwoods.ai) user, these agents are available as a free marketplace pack. No setup required.

## Contributing

We need **mental health professionals**, **crisis counselors**, **developers**, and **lived experience advocates**. Clinical review of all agent responses is critical.

**How to contribute:**
1. Fork the repo
2. Create a feature branch (`git checkout -b feat/your-feature`)
3. Commit your changes
4. Push and open a PR

See [CONTRIBUTING.md](CONTRIBUTING.md) when available.

## Related Projects

| Project | Description |
|---------|-------------|
| [MAMA](https://mama.oliwoods.ai) | AI Chief of Staff — 85+ agent teams |
| [CoFounder](https://cofounder.software) | AI agent marketplace |
| [MAMA AI Clinic](https://github.com/OliWoods-Org/mama-ai-clinic) | $170 offline health clinic for Raspberry Pi |
| [OliWoods Foundation](https://oliwoodsfoundation.org) | Open-source AI for humanitarian impact |

---

<p align="center">
  <strong>An <a href="https://oliwoodsfoundation.org">OliWoods Foundation</a> Project</strong>
  <br><em>Open-source AI tools for humanitarian and public good</em>
  <br><br>
  <sub>
    Built with <a href="https://mama.oliwoods.ai">MAMA</a> · Powered by <a href="https://cofounder.software">CoFounder</a>
    <br>Our commercial products fund the Foundation's open-source work.
    <br><br>
    <strong>GPL-3.0 — If you're in crisis, call 988. This tool helps everyone else.</strong>
  </sub>
</p>
