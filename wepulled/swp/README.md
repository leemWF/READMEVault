# Kalecgos

```mermaid
gantt
    title Kalecgos Portal Timeline
    dateFormat  mm:ss
    axisFormat %M:%S

    section Portal 1
    Melee Group           :p1, 00:00, 1m
    Manatide/Bearbob     :crit, 00:00, 1m
    
    section Portal 2
    Hunter & Mage Group      :p2, 00:30, 1m

    section Portal 3
    Warlock Group    :p3, 01:00, 1m
    Levi +  Elji     :crit, 01:00, 1m

    section Portal 4
    Exhaustion      :crit, p4, 01:30, 1m
```

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

![BrutallusMap](https://cdn.discordapp.com/attachments/775973769537126412/990358559348912189/Screen_Shot_2022-06-25_at_1.50.55_PM.png)

<details>
<summary>Click for team bear details</summary>

```mermaid
stateDiagram-v2
    t2: Pickii
    h4: Behrmy
    h5: Manatide
    h6: Elji
    rr1: Firedestruct
    rr2: Shar
    rr3: Junzi
    rr4: Beek
    rr5: Brooks
    rr6: Zarj
    
    h4 --> t2
    h5 --> t2
    h6 --> t2
    rr1 --> h4
    rr2 --> h4
    rr3 --> h5
    rr4 --> h5
    rr5 --> h6
    rr6 --> h6
```

</details>

<details>
<summary>Click for team warrior details</summary>

```mermaid
stateDiagram-v2
    t1: Abe
    h1: Bearbob
    h2: Levi
    h3: Exhaustion
    r1: Dan
    r2: Twyrp
    r3: Victra
    r4: Kepa
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

</details>
<br>
<br>

# Felmyst

![FelmystMap](https://cdn.discordapp.com/attachments/775973769537126412/990364968299954216/Screen_Shot_2022-06-25_at_2.15.48_PM.png)

| Group :x: | Group :small_red_triangle_down: | Group :large_orange_diamond: | Group :large_blue_circle: |
| ----------- | ----------- | ----------- | ----------- |
| Melee Group [G1]| Hunter Group [G2]| Mage Group [G4]| Warlock Group [G3]|
| Exhaustion | Elji | | Behrmy |
| | Stud | | Bearbob |
| | | | |

<br>
<br>

# Twins

![TwinsMap](https://cdn.discordapp.com/attachments/775973769537126412/990375297964736522/Screen_Shot_2022-06-25_at_2.32.23_PM.png)

<br>
<br>

# Muru

![MuruP2Map](https://cdn.discordapp.com/attachments/775973769537126412/990372769868947556/Screen_Shot_2022-06-25_at_2.47.07_PM.png)

<br>
<br>

# KJ

![KJMap](https://cdn.discordapp.com/attachments/945886124784644156/988662912614805583/KilJaeden___RaidPlan.io_-_Google_Chrome_6_20_2022_9_25_52_PM.png)

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
      Hero Melee & DPS boss: 5: Melee
      [30sec] Hero Range & Kill adds/boss: 4: Range
      [After 1st Shield] Hero Melee & Push: 2: Melee
    section Phase 5 (<25%)
      Survive & Win!: 4: Range, Melee, Healer
```

<details>
<summary>Click for hero timeline</summary>

```mermaid
journey
    title Hero Timeline
    section Phase 3 (85-55%)
      [OPTIONAL] Hero Melee & DPS boss: 7: N/A
    section Phase 4 (55-25%)
      Hero Melee & DPS boss: 7: Bamm
      [30sec] Hero Range & Kill adds/boss: 7: Levi/Jun/Mana
      [After 1st Shield] Hero Melee & Push: 7: Exhaustion
```


</details>
