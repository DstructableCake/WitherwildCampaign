# Session 21 - Initiative Tracker Encounters

Use these blocks as tap-to-run packages for a **4 PC, Level 5 (Tier 3)** gauntlet.

Base budget: `[(3 × 4) + 2] = 14 BP`.

- Easier/shorter: **13**
- Standard: **14**
- Harder/longer: **16**

This is an attrition-run. Spend the listed BP, but **stagger waves** so the first round is readable. Identical encounter blocks also live on each combat scene.

Costs: Minion group of 4 = 1, Horde/Standard/Ranged/Skulk = 2, Leader = 3, Bruiser = 4, Solo = 5.

---

## Difficulty Snapshot

| Beat | Target BP | Built BP | Verdict |
|------|-----------|----------|---------|
| Shore of Unfinished Names | 13 | 13 | Opening Leshen fight, full spend via two waves |
| The Road That Walks | 14 | 14 | Standard; Mile-Eater is the toy |
| Grove of Two Shadows | 16 | 16 | Hard midpoint; leader plus wardens |
| The Hunger Notices | 9 | 9 | Chase pressure, not a full stand |
| Ford of Two Worlds | 16 | 16 | Climax Solo + Leader + leftover weft-things |

---

## Encounter A - Shore of Unfinished Names

**Target:** 13 (easier). **Built:** 13.

Wave 1 (6): [[Leshen Unseated]] 5 + [[Bound-Voice Echo]] x4 (1).  
Wave 2 on first Antler Call or after Major damage (7): [[Drowned Chorus]] 2 + [[Weft Warden]] 2 + [[Seam-Moth Swarm]] 2 + second Echo group (1).

```encounter
name: Session 21 - Shore of Unfinished Names
party: Main Party
creatures:
  - [[Leshen Unseated]]
  - [[Drowned Chorus]]
  - [[Weft Warden]]
  - [[Seam-Moth Swarm]]
  - 8: [[Bound-Voice Echo]]
```

Notes:

- Same Leshen from the elder platforms, now a Tier 3 Solo. Do not swap it for [[Ripple Host]].
- Echoes are the pinned grove warriors; they feed **Pinned Host**.
- **Sever the Brand** (Difficulty 17) remains the mercy off-ramp.
- Weft add-ons arrive because the shore treats the Leshen as native, not because this is a drowning tutorial.

---

## Encounter B - The Road That Walks

**Target:** 14. **Built:** 14.

Wave 1 (6): [[Mile-Eater]] 4 + [[Seam-Moth Swarm]] 2.  
Wave 2 on first Devour the Between (8): [[Weft Warden]] x2 (4) + [[Drowned Chorus]] 2 + [[Bound-Voice Echo]] x8 (2).

```encounter
name: Session 21 - The Road That Walks
party: Main Party
creatures:
  - [[Mile-Eater]]
  - 2: [[Weft Warden]]
  - [[Seam-Moth Swarm]]
  - [[Drowned Chorus]]
  - 8: [[Bound-Voice Echo]]
```

Notes:

- 8 Echoes are two minion groups of 4 (2 BP).
- Wardens drop from inverted branches against the aurora when distance collapses.
- Chorus sings from names packed into the roadbed.
- If isolation is already brutal, cut one Echo group first (-1).

---

## Encounter C - Grove of Two Shadows

**Target:** 16 (harder). **Built:** 16.

Wave 1 (9): [[Root-That-Remembers]] 3 + [[Weft Warden]] x2 (4) + [[Seam-Moth Swarm]] 2.  
Wave 2 if they refuse the bark bargain or after the first Warden falls (7): third [[Weft Warden]] 2 + second [[Seam-Moth Swarm]] 2 + [[Drowned Chorus]] 2 + [[Bound-Voice Echo]] x4 (1).

```encounter
name: Session 21 - Grove of Two Shadows
party: Main Party
creatures:
  - [[Root-That-Remembers]]
  - 3: [[Weft Warden]]
  - 2: [[Seam-Moth Swarm]]
  - [[Drowned Chorus]]
  - 4: [[Bound-Voice Echo]]
```

Notes:

- Two Shadows and Bramble Geometry carry more threat than the BP number suggests.
- If the table is wrecked, take the bargain and skip Wave 2.
- If the table is fresh and hungry, bring Wave 2 immediately.

---

## Encounter D - The Hunger Notices

**Target:** 9 (chase, not a 14-point stand). **Built:** 9.

```encounter
name: Session 21 - The Hunger Notices
party: Main Party
creatures:
  - 4: [[Bound-Voice Echo]]
  - 2: [[Weft Warden]]
  - [[Drowned Chorus]]
  - [[Seam-Moth Swarm]]
```

Notes:

- Do not run this as a HP slog. One move, one hazard, one hostile beat per round.
- [[The Hunger]] is silhouette only here. Do not put its sheet in this block.
- Spend Fear on Yank, Bright Beat Theft, and Echo Relay.
- If the table is wrecked after the grove, skip this block and go to the ford with Hunger already closing.

---

## Encounter E - Ford of Two Worlds

**Target:** 16 (harder). **Built:** 16.

Open (10): [[The Hunger]] 5 + [[Mask-That-Walks]] 3 + [[Drowned Chorus]] 2.  
Hold pressure (6): [[Weft Warden]] 2 + [[Seam-Moth Swarm]] 2 + [[Bound-Voice Echo]] x8 (2).

```encounter
name: Session 21 - Ford of Two Worlds
party: Main Party
creatures:
  - [[The Hunger]]
  - [[Mask-That-Walks]]
  - [[Drowned Chorus]]
  - [[Weft Warden]]
  - [[Seam-Moth Swarm]]
  - 8: [[Bound-Voice Echo]]
```

Notes:

- Run Crossing Hold and Living Tether publicly.
- Hunger Unseat can vomit another Chorus; if the field is already full, skip that summon.
- If the party arrives heavily worn, drop the Echo groups first (16 → 14) before touching Hunger or the Mask.
- If a fifth PC is present, add a second [[Weft Warden]] (+2) and a third Echo group (+1).

---

## Quick Scaling Dials

- **Too easy:** Pull the next staggered wave immediately.
- **Too hard:** Remove the newest horde/minion wave; never strip the scene boss first.
- **Too slow:** Convert one hostile spotlight into objective pressure (clock tick, route break, name bind).
- **Party of 5:** Add +3 BP of Horde + Minion group, not a second Solo.
