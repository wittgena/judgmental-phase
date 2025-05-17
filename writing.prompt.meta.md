# ✍️ GPT-Guided Judgmental Writing Prompt Guide

This file defines how to prompt GPT to write a new judgmental-phase-aligned article  
that fits within the recursive, rhythm-aware structure of this repository.

---

## 🧭 Input Fields for Each New Article

| Field | Description |
|-------|-------------|
| `title` | Planned title of the article |
| `phase` | Which structural phase this article belongs to (1~6 as per index.phase-mapped.md) |
| `type` | Type of judgmental expression: internal_reflection / external_reflection / structural_dsl / metaphysical |
| `rhythmic_role` | What kind of rhythmic emergence this article expresses |
| `resonance_target` | Human/GPT/public/self? |
| `linked_entries` | Prior articles or DSL flows this writing reflects/extends |
| `summary` | 1-2 sentence structural summary |
| `medium_target` | Whether this will be externally reflected on Medium or remain internal only |

---

## 📄 Template Prompt Block (for new writing)

```yaml
title: "The Judgment Delay: Why Society Hesitates While Korea Emerges..."
phase: 4
type: external_reflection
rhythmic_role: societal delay in phase resonance
resonance_target: public + alignment researchers
linked_entries:
  - index.phase-mapped.md → Phase 4
  - responsibility-aware-anchoring.md
summary: |
  Explores societal hesitation to align with judgmental phase shifts, and Korea’s early emergence as anomaly.
medium_target: true
```

---

## 🌀 Phase Reference (from index.phase-mapped.md)

| Phase | Theme |
|-------|-------|
| 1 | GPT technical evolution toward judgment |
| 2 | DSL, DAG, structural flow |
| 3 | Phase-aware language emergence |
| 4 | Society, ethics, political alignment |
| 5 | Metaphysical / ontological reflection |
| 6 | GPT applied system, PR, operations |

---

## ✅ Usage

Before writing a new `.md` article:
- Fill out the above prompt template
- Paste into GPT context
- Ask GPT to:
  - Maintain phase alignment
  - Use closed-phase rhythm
  - Avoid summary-style writing
