# Start

## Soulstone 

```mermaid
flowchart LR
    C(Firedestruct) --> D(Pickii)
    E(Brooks) --> F(Abe)
    G(Zarj) --> H(Rene)
    A(Rin) --> B(Elji)
```

# Kalecgos

| Group | Hero |
| ----------- | ----------- |
| [G2] Hunter | Hero in Demon Realm |
| [G4] Mage | Hero in Demon Realm |
| [G1] Melee | Hero in Demon Realm |

```mermaid
gantt
    title Kalecgos Portal Timeline
    dateFormat  mm:ss
    axisFormat %M:%S

    section Portal 1
    Warlock Group           :p1, 00:00, 1m
    Manatide + Bearbob     :crit, 00:00, 1m
    
    section Portal 2
    Hunter & Mage Group      :p2, 00:30, 1m

    section Portal 3
    Melee Group    :p3, 01:00, 1m
    Levi +  Elji     :crit, 01:00, 1m

    section Portal 4
    Exhaustion      :crit, p4, 01:30, 1m
```

:fire: Attention :fire:
- :fire: **Melee Pumping Week: Pay attention to portal rotation + hero changes** :fire:
- After 1st full portal rotation, wait for Blair's callout before further pushing the dragon
- Hybrid classes help with raid healing

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

    s5: Behrmy stays up and bubbles
    s6: Call out so other healer stays
    s5 --> s6: early teleport
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
| [G1] Melee | Exhaustion Hero when Shar calls out |
| [G2] Hunter | Manatide Hero when Shar calls out |
| [G3] Warlock | Hero when Shar calls out |
| [G2] Hunter | Hero off Cooldown |
| [G1] Melee | Hero off Cooldown |
| [G4] Mage | Hero off Cooldown |

![BrutallusMap](https://cdn.discordapp.com/attachments/775973769537126412/990358559348912189/Screen_Shot_2022-06-25_at_1.50.55_PM.png)

```mermaid
stateDiagram-v2
    t2: Pickii
    h4: Behrmy
    h5: Exhaustion
    h6: Elji
    rr1: Firedestruct
    
    rr3: Shar
    rr4: Beek
    rr5: Brooks
    rr6: Zarj
    
    rr5 --> h4
    h4 --> t2
    h5 --> t2
    h6 --> t2
    rr1 --> rr3
    
    rr3 --> h5
    rr4 --> h5
    rr6 --> rr4
```

```mermaid
stateDiagram-v2
    t1: Abe
    h1: Bearbob
    h2: Manatide
    h3: Levi
    r1: Akugi
    r2: Kepa
    r3: Rich
    r4: Twyrp
    r5: Rin
    r6: Victra

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
- Less ranges this week on Bear side. Watch out your HP.
- Replicate what we did last week. Big tank heal. Healers stick to their assignments. Run as soon as you get burn.

<br>
<br>

# Felmyst

| Group | Hero |
| ----------- | ----------- |
| DPS groups | Hero off cooldown after 2nd air phase |

![FelmystMap](https://cdn.discordapp.com/attachments/775973769537126412/1003850255919480934/Screen_Shot_2022-08-01_at_7.21.19_PM.png)

| Group :x: | Group :small_red_triangle_down: | Group :large_orange_diamond: | Group :large_blue_circle: |
| ----------- | ----------- | ----------- | ----------- |
| Melee Group [G1]| Hunter Group [G2]| Mage Group [G4]| Warlock Group [G3]|
| Exhaustion | Behrmy | Bearbob | Elji |
| | Manatide | Rene | |

## Soulstone 

```mermaid
flowchart LR
    C(Firedestruct) --> D(Firechild)
    E(Brooks) --> F(Behrmy)
    G(Zarj) --> H(Rene)
```

## DI

```mermaid
flowchart LR
    C(Firechild) --> D(Behrmy) --> E(Rene)
```

## Priest Brez 

```mermaid
flowchart LR
    A(Bearbob) --> B(Elji)
    C(Beek) --> D(Victra)
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
| [G1] Melee | Exhaustion Hero after callout |

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

:fire: Attention :fire:
- Follow callouts and switch target **ASAP** :fire:
- **Only 1 warlock** will seed for 1st wave of Humanoids
- P2 survive and pump :fire:

<br>
<br>

# KJ

```mermaid
journey
    title Hero Timeline
    section Phase 3 (85-55%)
      [OPTIONAL] Hero Melee & DPS boss: 0: Exhaustion
    section Phase 4 (55-25%)
      Hero ALL DPS groups: 7: Bamm, Levi, Stud, Refinement
      [After 1st Shield] Hero Warlock & Push: 7: Manatide
```

![KJMap](https://cdn.discordapp.com/attachments/775973769537126412/1001100196308058193/Screen_Shot_2022-07-25_at_5.13.13_AM.png)

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
