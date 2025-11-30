# Council of Elders - Raid Leader Strategy Guide

## 📋 **Fight Overview**
Council of Elders is a **4-boss council fight** where you face all four Troll bosses simultaneously until they die. The Spirit of Gara'jal continuously empowers one boss at a time, making them more dangerous. You must damage each empowered boss for 25% of their health to break the empowerment and move it to the next boss. This cycle continues until all bosses are dead.

**Core Mechanic:** Empowerment rotates through bosses → Deal 25% damage to break → New boss empowered → Repeat until all dead

**No Hard Enrage Timer** - But letting bosses reach 100 Dark Energy = escalating raid damage

---

## 🎯 **THE FOUR BOSSES**

### **Frost King Malakk** 🧊 (Tank Swap Boss)
- **Frigid Assault** - Stacking debuff, 15 stacks = 15-second stun on tank
- **Biting Cold** (Normal) - DoT on random player, damages allies within 4 yards for 30 seconds
- **Frostbite** (Empowered) - 5-stack debuff, damage multiplied by stacks, reduced by standing near allies

### **Kazra'jin** ⚡ (Charge Boss)
- **Reckless Charge** - Charges random player, damages path, knocks back at destination
- **Overload** (Empowered - Normal) - Stunned 20 seconds, reflects 50% damage taken to attacker
- **Discharge** (Empowered - Heroic) - Reflects % damage to ENTIRE RAID

### **Sul the Sandcrawler** 🏜️ (Quicksand Boss)
- **Sand Bolt** - Nature damage to target + 5-yard splash (INTERRUPT)
- **Quicksand** - Creates pools that slow/root players (5 stacks = Entrapped 30 seconds)
- **Sandstorm** (Empowered) - Every 40 seconds, transforms Quicksand into Living Sand adds
- **Living Sand** - Adds that gain +100% damage + full heal from each subsequent Sandstorm

### **High Priestess Mar'li** 🌟 (Spirit Boss)
- **Wrath of the Loa** - Holy/Shadow damage (INTERRUPT)
- **Blessed Loa Spirit** (Normal) - Runs to lowest HP boss, heals 10% if reaches/survives 20s
- **Shadowed Loa Spirit** (Empowered - Normal) - Fixates player, kills if within 6 yards or after 20s
- **Twisted Fate** (Empowered - Heroic) - Spawns 2 adds that damage raid based on proximity

---

## ⚠️ **DEADLY MECHANISMS**

### **Universal Mechanics**

| Mechanic | Danger Level | Details |
|----------|--------------|---------|
| **Dark Power** | 🔴🔴🔴 LETHAL | Boss reaches 100 Dark Energy → Casts increasing damage every second until empowerment broken |
| **Lingering Presence** | 🟡 Escalating | Each broken empowerment = +10% damage (Normal) / +15% (Heroic) permanently |
| **Failed Interrupts** | 🔴 High | Sand Bolt and Wrath of the Loa MUST be interrupted |

### **Boss-Specific Deadly Mechanics**

**Frost King Malakk:**
- 🔴 **15-Stack Frigid Assault** - Tank stunned 15 seconds = boss runs loose
- 🔴 **Frostbite (Empowered)** - 5-stack damage can one-shot if not soaked
- 🔴🔴 **Frostbite (Heroic)** - Body Heat debuff prevents re-soaking for 8 seconds

**Kazra'jin:**
- 🟡 **Reckless Charge Path** - High damage if caught in path
- 🟡 **Overload Reflection** (Normal) - 50% reflected damage to attackers
- 🔴🔴 **Discharge** (Heroic) - Massive raid damage during empowerment, requires healing cooldowns

**Sul the Sandcrawler:**
- 🔴 **Quicksand Overlap** - 5 stacks = 30-second root
- 🔴🔴 **Living Sand Spam** - Multiple Sandstorms = room full of adds
- 🔴🔴 **Fortified Living Sands** - +100% damage + full heal per Sandstorm = unkillable if stacked
- 🔴🔴🔴 **Merged Quicksand (Heroic)** - Overlapping pools = larger, more powerful adds when transformed

**High Priestess Mar'li:**
- 🔴 **Blessed Loa Spirit** - Heals bosses 10%, problematic if reaches low-HP target
- 🔴 **Shadowed Loa Spirit** (Normal) - Instant death if reaches target or after 20s
- 🟡 **Twisted Fate** (Heroic) - Heavy raid damage if adds too close together

### **Heroic-Only Deadly Mechanics**

| Mechanic | Danger Level | Details |
|----------|--------------|---------|
| **Soul Fragment** | 🔴🔴 CRITICAL | Random player gets debuff every other empowerment break - Stacks 2% damage taken per 5s - Must rotate through raid |
| **Quicksand Merging** | 🔴🔴🔴 LETHAL | Overlapping pools create MASSIVE Living Sands - Sul MUST die before first empowerment |
| **Body Heat** | 🔴 High | Prevents Frostbite soaking for 8s after taking damage - Need rotation or solo-tank strategy |
| **Discharge** | 🔴🔴 EXTREME | Entire raid takes reflected damage during Kazra'jin empowerment |

---

## 🔴 **HEROIC MODE STRATEGY**

### **⚡ The Golden Rule: KILL SUL BEFORE FIRST EMPOWERMENT**

**Why this is absolutely critical:**
- Overlapping Quicksand pools merge into larger zones that spawn larger, more powerful Living Sands when Sul casts Sandstorm
- These merged adds are "extremely damaging and almost impossible to handle without many deaths"
- Sul CANNOT be allowed to ever cast Sandstorm in Heroic mode

**Execution:**
1. Use Heroism/Bloodlust at pull
2. Tank Sul with Malakk, focus Sul with cleave damage to Malakk
3. Break Malakk's empowerment just before 100 Dark Energy (75% HP)
4. Ensure Mar'li is next empowered (higher HP than Kazra'jin)
5. Continue burning Sul while breaking Mar'li's empowerment in time
6. Sul must die before 4th empowerment (his turn)

### **🎭 Soul Fragment Management**

**How it works:**
- Spawns on random player every OTHER empowerment break (2nd, 4th, 6th, etc.)
- Stacks Shadowed Soul: +2% damage taken per stack (every 5 seconds)
- Can be passed to other players via extra action button
- Stacks persist FOREVER on each player

**Strategy:**
- First player keeps until 5 stacks (~25 seconds)
- Pass to next player with 0 stacks
- Continue rotation until everyone has 5 stacks
- Then rotate again to 10 stacks per player
- **NEVER give to tanks until Malakk is dead** (can't afford extra damage)
- Warlocks/high-mitigation classes can take extra stacks

**Assignment Example (10-man):**
```
Order: Healer1 → Healer2 → RDPS1 → RDPS2 → RDPS3 → MDPS1 → MDPS2 → MDPS3 → repeat
```

### **❄️ Heroic Frostbite Handling**

**The Problem:**
- Body Heat: Taking Frostbite damage prevents soaking for 8 seconds
- Normal soak rotation doesn't work well

**Recommended Strategy:**
- Afflicted player moves OUT of raid
- Takes full unreduced Frostbite damage alone
- Healers spam + use externals (Pain Suppression, Ironbark, Guardian Spirit)
- Requires coordination but safer than complex rotation

**Alternative (Advanced):**
- Rotation of 4 players in 25m / 2 players in 10m
- Each soaks, then moves away when Body Heat applied
- Very movement-intensive, prone to errors

### **⚡ Discharge (Kazra'jin Empowered)**

**The Challenge:**
- Entire raid takes heavy damage based on DPS done to Kazra'jin
- Must still break empowerment in time

**Strategy:**
- Healers use defensive cooldowns during Kazra'jin empowerment
- Keep raid HP topped at all times
- **Stop DPS when Blessed Loa Spirit spawns** - Switch to kill spirit, gives healers breathing room
- Resume burning Kazra'jin after spirit dead
- Don't over-DPS early - let empowerment run to 80-100 Dark Energy

### **🎯 Twisted Fate (Mar'li Empowered - Heroic)**

**How it works:**
- Targets melee player + farthest player
- Spawns 2 adds at their locations
- Adds walk toward each other
- Raid damage increases as they get closer
- If one dies, other pulses AoE until killed

**Strategy:**
- Designate ranged DPS "bait" player
- When Twisted Fate casting, bait moves FAR from raid
- Creates maximum distance between adds
- Slow, stun, and kill adds quickly
- Focus one at a time (kill both nearly simultaneously to minimize pulse damage)

---

## 💡 **CRITICAL TIPS**

### **General Tips**

✅ **Empowerment Pacing:** Don't burn empowered bosses immediately - let them sit at 80-100 Dark Energy (except Sul in Heroic)
✅ **Dark Power Survival:** First ~10 seconds of Dark Power is survivable - use this time to finish breaking empowerment
✅ **Kill Order Priority (Normal):** Kazra'jin → Sul → Mar'li → Malakk (reduces Overload + Sandstorm casts)
✅ **Alternative Strategy (Normal):** Burn Sul first with Bloodlust at pull - Many groups find this easier
✅ **Malakk HP Management:** Never make Malakk lowest HP - Prevents Blessed Loa Spirit complications
✅ **Interrupt Reliability:** Assign dedicated interrupters for Sand Bolt + Wrath of the Loa
✅ **Living Sand Spawns:** Sul casts Sandstorm every 40s while empowered (2x max per empowerment)
✅ **Quicksand Positioning:** Avoid creating pools in high-traffic areas or melee zones

### **Tank Tips**

✅ **Tank Assignment:** Tank 1 = Mar'li + alternating Malakk | Tank 2 = Sul + alternating Malakk
✅ **Malakk Swap Timing:** Swap at 10-12 stacks of Frigid Assault (never reach 15)
✅ **Living Sand Pickup:** Off-Malakk tank grabs Living Sands immediately
✅ **Late Fight Living Sands:** May need to split adds between both tanks (25m can use 3rd tank)
✅ **Mar'li Positioning:** Keep Mar'li away from raid to make spirit management easier
✅ **Sul Positioning (Heroic):** Tank with Malakk for cleave damage during burn phase

### **Healer Tips**

✅ **Frostbite Healing (Normal):** Focus heal afflicted player + nearby soakers
✅ **Frostbite Healing (Heroic):** Solo-tanked player needs spam heals + externals
✅ **Discharge Preparation:** Top raid before each Kazra'jin charge, use CDs liberally
✅ **Dark Power Response:** Be ready for escalating raid damage if boss not broken in time
✅ **Living Sand Waves:** Heavy tank damage spikes when Sandstorm transforms pools
✅ **Soul Fragment Awareness:** Track who has debuff, adjust healing accordingly

### **DPS Tips**

✅ **Priority Targets:** Loa Spirits > Living Sands > Empowered Boss
✅ **Loa Spirit Timing:** Spirits must die in under 20 seconds
✅ **Shadowed Loa Kiting:** Slow, root, and kite away - never let reach target
✅ **Blessed Loa Strategy:** Kill OR slow/root to prevent reaching low-HP boss
✅ **Living Sand Focus:** AoE down quickly before next Sandstorm (Fortified = +100% damage + heal)
✅ **Overload/Discharge Respect:** Don't over-DPS Kazra'jin during empowerment (especially Heroic)
✅ **Sul Burn (Heroic):** All cooldowns on Sul at pull, cleave to Malakk acceptable
✅ **Quicksand Awareness:** Melee - Watch for pools after Living Sands die

### **Positioning Tips**

✅ **Base Spread:** 7 yards apart to minimize Sand Bolt + Biting Cold damage
✅ **Reckless Charge:** Path players have 1-2 seconds to dodge - stay alert
✅ **Frostbite Soaking (Normal 10m):** 2 players within 4 yards of afflicted player
✅ **Frostbite Soaking (Normal 25m):** 4 players within 4 yards (or 0 - damage is same, just less spread)
✅ **Frostbite Solo (Heroic):** Afflicted player moves OUT, away from all raid members
✅ **Mar'li Distance:** Stay away from Mar'li except her tank/melee on her
✅ **Twisted Fate Bait (Heroic):** Designated ranged player moves to max range when cast incoming
✅ **Melee Challenges:** Harder to spread, more Quicksand exposure, must dodge charges together

---

## 📊 **READY-TO-USE ASSIGNMENTS**

### **Tank Assignments**

| Tank | Primary Boss | Secondary | Responsibilities |
|------|--------------|-----------|------------------|
| **Tank 1** | High Priestess Mar'li | Malakk (alternate) | • Tank Mar'li away from raid<br>• Swap Malakk at 10-12 stacks<br>• Pick up Living Sands when not on Malakk<br>• **Heroic:** Never take Soul Fragment until Malakk dead |
| **Tank 2** | Sul the Sandcrawler | Malakk (alternate) | • Tank Sul (with Malakk in Heroic)<br>• Swap Malakk at 10-12 stacks<br>• Primary Living Sand tank when not on Malakk<br>• **Heroic:** Position Sul for cleave during burn |

**Tank Swap Schedule:**
- Swap at 10-12 stacks of Frigid Assault
- Debuff resets over time, can re-tank after stacks drop
- Communication essential to avoid 15-stack stun

**Heroic Tank Notes:**
- May use 3rd tank in 25m for Living Sands
- Tanks take Soul Fragment last (after Malakk dead)
- Extra healing needed during Sul burn (tanking 2 bosses)

### **Healer Assignments**

**Dispel/Heal Priority:**
| Situation | Action | Healers Needed |
|-----------|--------|----------------|
| Biting Cold | Focus heal + minor spread healing | 1-2 |
| Frostbite (Normal) | Heal afflicted + 2-4 soakers | 2-3 |
| Frostbite (Heroic) | SPAM HEAL solo player + externals | ALL |
| Living Sand Waves | Heavy tank healing | 1-2 on tanks |
| Dark Power | Escalating raid healing | ALL + CDs |
| Discharge (Heroic) | Constant raid healing + CDs | ALL |

**Cooldown Rotation (Heroic):**

**Kazra'jin Empowerment (Discharge):**
1. First Charge → Spirit Link Totem
2. Second Charge → Barrier / Tranquility
3. Third Charge → Rally / Divine Hymn
4. Throughout → Aura Mastery, Darkness, etc.

**Frostbite External Rotation:**
- Pain Suppression
- Ironbark
- Guardian Spirit
- Hand of Sacrifice
- Safeguard

**Soul Fragment Healing Adjustments:**
- Players with 5+ stacks take 10%+ more damage
- Players with 10+ stacks take 20%+ more damage
- Adjust healing assignments as debuff rotates

### **DPS Assignments**

**Interrupt Rotation:**

| Boss | Ability | Casters Assigned |
|------|---------|------------------|
| Sul the Sandcrawler | Sand Bolt | 2-3 interrupters |
| High Priestess Mar'li | Wrath of the Loa (both versions) | 2-3 interrupters |

**Example 10-man Interrupt Assignment:**
- Sul: Shaman, Mage, Hunter
- Mar'li: DK, Warlock, Priest

**Kill Priority (ALWAYS):**
1. 🔴 **Blessed Loa Spirit** / **Shadowed Loa Spirit** / **Twisted Fate Adds** - Drop everything
2. 🔴 **Living Sand** - Must die before Fortified stacks
3. 🟡 **Empowered Boss** - Damage to 25% HP loss

**Boss Kill Order:**

**Normal Mode - Standard:**
1. Kazra'jin (reduces Overload casts)
2. Sul the Sandcrawler (reduces Sandstorm casts)
3. High Priestess Mar'li
4. Frost King Malakk (keep highest HP to prevent Blessed Loa issues)

**Normal Mode - Alternative (Popular):**
1. Sul the Sandcrawler (burn at pull with Bloodlust, cleave to Malakk/Mar'li)
2. Kazra'jin
3. High Priestess Mar'li
4. Frost King Malakk

**Heroic Mode - MANDATORY:**
1. 🔴🔴🔴 **Sul the Sandcrawler** (MUST DIE BEFORE FIRST EMPOWERMENT)
2. Kazra'jin (careful with Discharge damage)
3. High Priestess Mar'li
4. Frost King Malakk

### **Empowerment DPS Strategy**

**Empowerment Damage Pacing:**
- **Frost King Malakk:** Let run to 80-100 Dark Energy (abilities same when empowered)
- **Kazra'jin:** Let run to 80-100 Dark Energy (burning faster = more reflected damage)
- **Sul (Normal):** Break ASAP to avoid 2nd Sandstorm
- **Sul (Heroic):** Never gets empowered (dies first)
- **High Priestess Mar'li:** Let run to 80-100 Dark Energy (abilities similar when empowered)

**Dark Energy Management:**
- 0-80 Energy: Comfortable, damage off-targets acceptable
- 80-100 Energy: Focus empowered boss, break soon
- 100 Energy: Dark Power starts, increasing damage - Break within 10 seconds

### **Special Role Assignments**

**Shadowed Loa Spirit Kiting (Normal Mode):**
- Targeted player: Kite away from spirit
- Support DPS: Slow, root, damage spirit
- Entire raid: Kill before 20 seconds or reaches target

**Blessed Loa Spirit Handling:**
- All available DPS switch immediately
- Slow, root, kill before reaches target or 20s expires
- If can't kill in time: Root/slow to delay until death

**Twisted Fate Management (Heroic):**
- Designated Bait: Ranged DPS with good mobility (Mage, Hunter, etc.)
- Bait moves to MAX range when Twisted Fate cast starts
- Kill team: Focus one add, then other (near-simultaneous)
- CC team: Stuns, slows on adds while being killed

**Soul Fragment Rotation (Heroic - Example 10-man):**
```
Spawn 1 (2nd empowerment break): Healer1 → Healer2 → RDPS1 → RDPS2
Spawn 2 (4th empowerment break): RDPS3 → MDPS1 → MDPS2 → MDPS3
Spawn 3 (6th empowerment break): Back to Healer1 (now going to 10 stacks)
```
- Each player holds for 5 stacks (25 seconds) then passes
- Track with raid frames addon or WeakAura
- Call out passes in voice

### **Cooldown Schedule**

**Bloodlust/Heroism:**
- **Normal:** At pull (all DPS benefit) OR save for emergency
- **Heroic:** At pull for Sul burn phase

**DPS Cooldowns:**
- **Normal:** Use on cooldown, prioritize empowered bosses
- **Heroic:** All cooldowns on Sul burn, then on cooldown after

**Defensive Cooldowns:**
- Save for Kazra'jin Discharge (Heroic)
- Use for Dark Power if boss reaches 100 Energy
- Externals for Frostbite (Heroic)

---

## 🎯 **POSITIONING DIAGRAM**

```
                    Mar'li (Tank 1)
                         🔵
                         
                         
    [Raid Spread 7 yards apart]
           🟢 🟢 🟢
         🟢    ⭐    🟢
           🟢 🟢 🟢
           
           
    Sul (Tank 2)              Malakk (alternating tank)
        🔴                            🟡
        
        
    Kazra'jin (charges into raid randomly)
        ⚡ → → → → 🎯
        
        
HEROIC ADJUSTMENTS:
- Bait player for Twisted Fate: MAX RANGE (far right/left)
- Frostbite player: Moves OUT completely
- Sul tanked WITH Malakk during burn phase
```

---

## ⚡ **QUICK REFERENCE CARD**

| Item | Details |
|------|---------|
| **Boss Count** | 4 simultaneous |
| **Empowerment Cycle** | 25% damage to break, ~67 seconds to 100 Energy |
| **Tank Swap** | At 10-12 stacks Frigid Assault |
| **Must Interrupt** | Sand Bolt, Wrath of the Loa (both versions) |
| **Kill Priority** | Spirits > Living Sands > Empowered Boss |
| **Bloodlust (Normal)** | Pull or emergency |
| **Bloodlust (Heroic)** | Pull for Sul burn |
| **Spread Distance** | 7 yards base |
| **Frostbite Soaking (Normal)** | 2 players (10m) / 4 players (25m) |
| **Hardest Mechanics** | Dark Power (100 Energy), Living Sand waves, Frostbite (H), Discharge (H), Soul Fragment (H) |
| **Heroic Kill Order** | Sul before empowerment > Kazra'jin > Mar'li > Malakk |

---

## 📝 **PULL SEQUENCE**

### **Normal Mode:**

1. **Pre-pull:** Assign interrupt rotations, Frostbite soakers, spread positions
2. **Pull:** Tank 1 takes Mar'li, Tank 2 takes Sul, both alternate Malakk
3. **First Empowerment (Malakk):**
   - Handle Frostbite soaking (2-4 players within 4 yards)
   - Break at 80-100 Dark Energy
4. **Ongoing:**
   - Interrupt Sand Bolt + Wrath of the Loa
   - Avoid Reckless Charge paths
   - Stay out of Quicksand pools
   - Kill Loa Spirits immediately
   - AoE Living Sands during Sandstorm
   - Never let boss reach 100 Energy (or break quickly after)
5. **Maintain spread, focus priority targets, break empowerments**

### **Heroic Mode:**

1. **Pre-pull:**
   - Assign Soul Fragment rotation order
   - Designate Twisted Fate bait player
   - Assign Frostbite external cooldown rotation
   - Review Sul burn strategy with all DPS
2. **Pull → Sul Burn Phase:**
   - Bloodlust immediately
   - Tank Sul with Malakk
   - ALL DPS on Sul (cleave to Malakk acceptable)
   - Malakk gets empowered first
3. **First Empowerment (Malakk - Sul Burn Continues):**
   - Continue burning Sul
   - Break Malakk just before 100 Energy
   - First Soul Fragment spawns - Begins rotation
   - Frostbite players move OUT, receive externals
4. **Second Empowerment (Mar'li - Sul Burn Continues):**
   - Continue burning Sul
   - Handle Twisted Fate (bait moves far, kill adds)
   - Break Mar'li just before 100 Energy
5. **Sul Dies (Before 4th Empowerment):**
   - Crisis averted
   - Switch to Kazra'jin
   - Manage Soul Fragments (continue rotation)
6. **Kazra'jin Empowerment:**
   - Healing cooldowns for Discharge
   - Stop DPS for Blessed Loa Spirits
   - Don't over-burn
7. **Finish:** Mar'li → Malakk (standard priority management)

---

## 🚨 **COMMON MISTAKES TO AVOID**

❌ **Letting bosses reach 100 Dark Energy** - Dark Power escalates quickly
❌ **Over-burning empowered Kazra'jin** - Reflected damage kills raid (especially Heroic Discharge)
❌ **Failing Loa Spirit interrupts** - Blessed Loa heals 10%, Shadowed Loa kills
❌ **Malakk tank reaching 15 stacks** - 15-second stun = loose boss
❌ **Quicksand overlap creating impassable zones** - Especially deadly in melee
❌ **Not AoEing Living Sands** - Each Sandstorm makes them stronger (Fortified)
❌ **Standing in Quicksand** - 5 stacks = 30-second Entrapment
❌ **Forgetting to spread for Sand Bolt** - Heavy splash damage
❌ **Sul empowerment in Heroic** - Instant wipe from merged Quicksand adds
❌ **Soul Fragment staying on one player too long (H)** - 10+ stacks = massive damage taken
❌ **Twisted Fate adds too close (H)** - Extreme raid damage
❌ **Frostbite players staying in raid (H)** - Body Heat prevents soaking, kills nearby players

---

**Source:** [Icy Veins - Council of Elders Strategy Guide](https://www.icy-veins.com/wow/council-of-elders-strategy-guide-normal-heroic)
