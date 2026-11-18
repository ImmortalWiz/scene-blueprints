# scene-blueprints: Granular Staging & Subtext (`SUBVERTED_HARRY`)

[![Repo Type: Scene Staging](https://img.shields.io/badge/Repo-Scene%20Blueprints-indigo.svg)](https://github.com/ImmortalWiz/scene-blueprints)
[![Layer: Intermediate Pre--Prose](https://img.shields.io/badge/Pipeline-Intermediate%20Staging-blue.svg)](https://github.com/ImmortalWiz/scene-blueprints)
[![Parent Engine](https://img.shields.io/badge/Parent-harry--potter--and--the--magical--reality--check-blue.svg)](https://github.com/ImmortalWiz/harry-potter-and-the-magical-reality-check)

The **Scene Blueprints (`scene-blueprints`)** repository bridges high-level chapter outlines from `plotline-architect` and raw prose in `prose-drafts`. It ensures every scene has deliberate physical blocking, authentic psychological subtext, and strict continuity adherence before writing begins.

---

## 🎭 The Blueprint Philosophy

In this universe, scenes are **never** drafted freeform. Writing prose without a blueprint leads to generic dialogue, unearned banter, and continuity regressions.

A Scene Blueprint establishes:
1. **Physical Blocking & Geography:** Where characters stand, how they move, how spatial tension is used.
2. **Psychological Subtext:** The unspoken tension between dialogue and true intent (e.g., Harry's charming smile hiding hyper-vigilance).
3. **Sensory & Atmospheric Palette:** Distinct tactile, auditory, and olfactory triggers that anchor the scene in physical reality.
4. **Continuity & Gap Verification:** Explicit verification that spells, injuries, or knowledge match active states in `war-entities`.

---

## 📂 Directory Layout

```
scene-blueprints/
├── book_01_the_fame_shield/
│   ├── chapter_01/
│   │   ├── scene_01_the_porch_assessment.md    # Blocking: Marge inspects Harry, Petunia looks away in silence
│   │   └── scene_02_the_grunscrawl_lesson.md   # Blocking: Dudley recites scripture, Harry in quarantine
│   └── chapter_02/
│       └── scene_01_the_diagon_ovation.md      # Staging: Harry's ego hijacked by public praise
└── book_05_the_hollow_victory/
    └── chapter_14/
        └── scene_01_the_ministry_ambush.md     # Tactical blocking: Guerrilla breach on Whitehall
```

---

## 📋 Standard Scene Blueprint Schema

Every blueprint file must adhere to this template:

```markdown
# Blueprint: Book [X], Chapter [Y], Scene [Z] - [Scene Title]

## 1. Setting & Environmental Physics
* **Location:** (Specific room/terrain, lighting, temperature, weather).
* **Sensory Triggers:** (Tactile, olfactory, and ambient sounds).

## 2. Character Blocking & Spatial Staging
* **Positions:** (Where each character starts, distances between them).
* **Micro-Actions:** (Physical tells: Petunia scrubbing clean counters, Harry adjusting cuffs).

## 3. Dialogue Beats & Subtextual Matrix
* **Beat 1:** [Surface topic] -> *Subtext: [True emotional objective]*.
* **Beat 2:** [Friction point] -> *Subtext: [Underlying fear or power play]*.
* **Beat 3:** [Resolution/Exit] -> *Subtext: [The unspoken agreement]*.

## 4. Continuity & Gap Check
* [x] Cross-referenced with Harry's `magical_gap_ledger.md`.
* [x] Verified that Dursley religious doctrine matches `01_scripture_fragments.md`.
* [x] Confirmed injuries or assets match `inventory_assets.md`.
```

---

## 🤖 Guide for AI Context Engines

* **Mandatory Input:** Never write prose in `prose-drafts` without parsing the corresponding blueprint from this repository.
* **Respecting Blocking:** The narrative prose must strictly follow the physical staging established in the blueprint (e.g., if Petunia never looks Harry in the eye in the blueprint, the prose must not depict direct eye contact).
* **Subtext Realization:** Dialogue must sound like a mask. Ensure Harry’s external lines sound theatrical, but the narrative perspective exposes the strain of maintaining the facade.
