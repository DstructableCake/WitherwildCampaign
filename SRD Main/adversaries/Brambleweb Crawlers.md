---
statblock: true
layout: Daggerheart Adversary
source: Custom
name: Brambleweb Crawlers
creature: Brambleweb Crawlers
motives_and_tactics: Swarm and entangle, inject wither venom, web traps, overwhelm isolated targets
tier: 2
type: Horde
description: A cluster of spider-like insects with bramble-thorn legs and webs that spread decaying blight, infesting corrupted undergrowth like a plague of twisted arachnids.
attackDetails:
  - 2
  - Close
  - Phy
  - 7 (1d6+2)
experience: Web Ambush +2
feats:
  - name: Thorn Web - Action
    desc: Create a web trap in a Close area. Creatures entering must save Agility or be Restrained and take 1d4 wither damage.
  - name: Venom Injection - Reaction
    desc: On a hit against a Restrained target, deal +1d4 damage and they gain Poisoned until end of scene.
  - name: Horde (1d4+2) - Passive
    desc: When the swarm has marked half or more of their HP, their standard attack deals 1d4+1 phy instead.
hp: "6"
stats:
  - 12
  - 6/10
  - 6
  - 2
ac: "0"
---