---
name: mk-legal-mcp-skill
description: Official North Macedonia (MK) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# North Macedonia Legal Research & Multi-Tier Case Law Skill (`mk-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **North Macedonia (MK)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `Рев1.бр.123/2023 or Службен весник на РСМ бр. 20/24`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** Osnovni sudovi (27 Basic Courts including Osnoven građanski sud Skopje & Osnoven krivičen sud Skopje)
   - **Second Instance (Cantonal / Regional / Appellate):** 4 Apelacioni sudovi (Skopje, Bitola, Gostivar, Štip), Upravni sud & Viš upraven sud
   - **Supreme & Constitutional Instance:** Vrhoven sud na Republika Severna Makedonija (vsrm.mk) & Ustaven sud na RSM (ustavensud.mk)
   - **Primary Tiered Database:** Nacionalen portal na sudski odluki - Sud.mk (All Basic, Appellate, Administrative & Supreme Courts) (`http://www.sud.mk`)
