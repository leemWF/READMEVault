# Start

## Soulstone 

```mermaid
flowchart LR
    A(Firedestruct) --> B(Elji)
    C(Shar) --> D(Pickii)
    E(Brooks) --> F(Abe)
    G(Zarj) --> H(Stud)
```

# Kalecgos

| Group | Hero |
| ----------- | ----------- |
| [G2] Hunter | Hero in Demon Realm |
| [G4] Mage | Hero in Demon Realm |
| [G3] Warlock | Hero in Demon Realm |

```mermaid
gantt
    title Kalecgos Portal Timeline
    dateFormat  mm:ss
    axisFormat %M:%S

    section Portal 1
    Melee Group           :p1, 00:00, 1m
    Manatide + Bearbob     :crit, 00:00, 1m
    
    section Portal 2
    Hunter & Mage Group      :p2, 00:30, 1m

    section Portal 3
    Warlock Group    :p3, 01:00, 1m
    Levi +  Elji     :crit, 01:00, 1m

    section Portal 4
    Exhaustion + Beek      :crit, p4, 01:30, 1m
```

:fire: Attention :fire:
- Portal 4 healers do not enter portal until Portal 1 healers teleport back
- More attention on dragon tank healing since no pally healer

<details>
<summary>Click for healer assignment details</summary>

```mermaid
stateDiagram-v2
    s1: Healer in Portal 3 or 4 Group
    s2: Manatide stays up
    s1 --> s2: teleported during Portal 1

    s3: Healer in Portal 3 or 4 Group
    s4: Elji stays up
    s3 --> s4: teleported during Portal 2

    state N/A {
    s5: Behrmy stays up and bubbles
    s6: Call out so other healer stays
    s5 --> s6: early teleport
    }
```
</details>
<br>
<br>

![KalecgosMap](https://cdn.discordapp.com/attachments/775973769537126412/990375252431364146/Screen_Shot_2022-06-25_at_1.26.34_PM.png)
<br>
<br>

# Brutallus

| Group | Hero |
| ----------- | ----------- |
| [G1] Melee | Hero after 1st Taunt |
| [G2] Hunter | Manatide Hero after 1st Taunt |
| [G3] Warlock | Exhaustion Hero after 1st Taunt |
| [G2] Hunter | Hero off Cooldown |
| [G3] Warlock | Hero off Cooldown |
| [G4] Mage | Hero off Cooldown |

![BrutallusMap](https://cdn.discordapp.com/attachments/775973769537126412/990358559348912189/Screen_Shot_2022-06-25_at_1.50.55_PM.png)

```mermaid
stateDiagram-v2
    t2: Pickii
    h4: Beek
    h5: Manatide
    h6: Elji
    rr1: Firedestruct
    rr2: Rich
    rr3: Junzi
    rr4: Shar
    rr5: Brooks
    rr6: Zarj
    
    rr5 --> h4
    h4 --> t2
    h5 --> t2
    h6 --> rr2
    rr1 --> rr3
    rr2 --> t2
    rr3 --> h5
    rr4 --> h5
    rr6 --> rr4
```

```mermaid
stateDiagram-v2
    t1: Abe
    h1: Bearbob
    h2: Levi
    h3: Exhaustion
    r1: Dan
    r2: Refinement
    r3: Victra
    r4: Twyrp
    r5: Akugi
    r6: Corntallis

    t1 --> h1
    t1 --> h2
    t1 --> h3
    h1 --> r1
    h1 --> r2
    h2 --> r3
    h2 --> r4
    h3 --> r5
    h3 --> r6
```

:fire: Attention :fire:
- Levi positions totems towards mid so all hunters can get buffs
- No Hpally. Big  tank heal. Healers stick to their assignments. Run as soon as you get burn.

<br>
<br>

# Felmyst

| Group | Hero |
| ----------- | ----------- |
| DPS groups | Hero off cooldown after 2nd air phase |

![FelmystMap](https://cdn.discordapp.com/attachments/775973769537126412/990364968299954216/Screen_Shot_2022-06-25_at_2.15.48_PM.png)

| Group :x: | Group :small_red_triangle_down: | Group :large_orange_diamond: | Group :large_blue_circle: |
| ----------- | ----------- | ----------- | ----------- |
| Melee Group [G1]| Hunter Group [G2]| Mage Group [G4]| Warlock Group [G3]|
| Beek | Elji | Manatide | Exhaustion |
| | Stud | | Bearbob |
| | | | |

## Soulstone 

```mermaid
flowchart LR
    A(Firedestruct) --> B(Elji)
    C(Shar) --> D(Firechild)
    E(Brooks) --> F(Stud)
    G(Zarj) --> H(Victra)
```

## Priest Brez 

```mermaid
flowchart LR
    A(Bearbob) --> B(Any priest dies without SS)
```

<br>
<br>

# Twins

![TwinsMap](https://cdn.discordapp.com/attachments/775973769537126412/990375297964736522/Screen_Shot_2022-06-25_at_2.32.23_PM.png)

<br>
<br>

# Muru

| Group | Hero |
| ----------- | ----------- |
| [G1] Melee | Hero after callout at the beginning |
| [G2] Hunter | Hero after callout at the beginning |
| [G3] Warlock | Hero after callout at the beginning |
| [G4] Mage | Hero after callout at the beginning |
| == Phase 2 == |
| [G2] Hunter | Manatide Hero after callout |
| [G3] Warlock | Exhaustion Hero after callout |

```mermaid
gantt
    title [3min Kill] Muru P1 Adds
    dateFormat  mm:ss
    axisFormat %M:%S

    section 1st 1min
    Nothing         :done, p1, 00:00, 10s
    Humanoids 1     :crit, h1, after p1, 1m
    Sentinel 1      :s1, 00:30, 30s
    Darkness 1      :active, d1, 00:45, 20s

    section 2nd 1min
    Sentinel 2      :s2, after s1, 30s
    Humanoids 2     :crit, h2, after h1, 1m
    Sentinel 3      :s3, after s2, 30s
    Darkness 2      :active, d2, 01:30, 20s
```

![MuruP2Map](https://cdn.discordapp.com/attachments/775973769537126412/990372769868947556/Screen_Shot_2022-06-25_at_2.47.07_PM.png)

<br>
<br>

# KJ

```mermaid
journey
    title Hero Timeline
    section Phase 3 (85-55%)
      [OPTIONAL] Hero Melee & DPS boss: 7: Mana
    section Phase 4 (55-25%)
      Hero ALL DPS groups: 7: Bamm, Levi, Junzi, Refine
      [After 1st Shield] Hero Warlock & Push: 7: Exhaustion
```

![KJMap](https://cdn.discordapp.com/attachments/775973769537126412/996200066446540870/Screen_Shot_2022-07-11_at_4.41.01_PM.png)

```mermaid
journey
    title KJ Timeline (KILL THE ORBS & DODGE AOE)
    section Phase 1
      Kill adds & Watch out debuff stacks: 7: Range, Melee, Healer
    section Phase 2 (100-85%)
      Dodge AoE & DPS boss: 5: Range, Melee, Healer
    section Phase 3 (85-55%)
      [OPTIONAL] Hero Melee & DPS boss: 5: Melee
      [30sec] Stack for breath & watch FB: 3: Range, Melee, Healer
    section Phase 4 (55-25%)
      Hero ALL DPS groups: 5: Melee, Range
      [30sec] Stack for breath: 4: Melee, Range, Healer
      [After 1st Shield] Hero Warlock & Push: 2: Range
    section Phase 5 (<25%)
      Survive & Win!: 4: Range, Melee, Healer
```
