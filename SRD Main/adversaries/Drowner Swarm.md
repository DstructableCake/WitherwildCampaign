---
statblock: true
layout: Daggerheart Adversary
source: Custom
name: Drowner Swarm
creature: Drowner Swarm
motives_and_tactics: Drag into water, overwhelm with numbers, retreat to depths, ambush from murky pools
tier: 2
type: Horde
description: A pack of waterlogged undead humanoids with webbed claws and glowing eyes, risen from cursed bogs. Inspired by Slavic water spirits (rusalka/vodyanoy) and Witcher drowners.
attackDetails:
  - 2
  - Close
  - Phy
  - 7 (1d6+2)
experience: Aquatic Ambush +2
feats:
  - name: Drag Under - Action
    desc: On a hit, pull the target into adjacent water (if present); they must save Agility or be Prone and take 1d4 ongoing damage until they escape.
  - name: Swarm Surge - Action
    desc: If at least 3 drowners remain, deal 1d8 phy to all targets in a Close line.
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