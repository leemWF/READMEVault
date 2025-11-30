# Horridon - Raid Leader Strategy Guide

## 📋 **Fight Overview**
Horridon is a 5-phase encounter with heavy add management. You'll face 4 different Troll tribes (one per phase), each spawning from doors around the room. After destroying all 4 doors, you face War-God Jalak + enraged Horridon. The fight is a **12-minute hard enrage** and tests your raid's ability to handle sustained boss damage while AoE-ing adds and dodging mechanics.

**Key Concept:** Each phase = 1 Troll tribe (75 seconds) → Kill Dinomancer → Horridon destroys door → 40 seconds break → Next phase

---

## ⚠️ **DEADLY MECHANISMS**

### **Horridon (Constant Throughout Fight)**
| Ability | Danger Level | Details |
|---------|--------------|---------|
| **Triple Puncture** | 🔴 High | Heavy tank damage + stacking 10% increased damage debuff - **REQUIRES TANK SWAP** |
| **Double Swipe** | 🔴 LETHAL | 35-yard cone front AND back - **STAY ON SIDES** or outrange (35y+) |
| **Charge** | 🟡 Medium | Charges random player → Double Swipe - Target must position to minimize raid movement |

### **Phase-Specific Deadly Mechanics**

**Phase 1 - Farraki (Northwest Door):**
- 🔴 **Sand Trap** - Expanding damage zones that are HARD TO SEE - can overlap with Double Swipe
- 🟡 **Stone Gaze** - 10-second stun (interrupt or dispel immediately)
- 🟡 **Blazing Sunlight** - DoT (must dispel)

**Phase 2 - Gurubashi (Northeast Door):**
- 🔴🔴 **Venom Bolt Volley** - MUST INTERRUPT or raid dies to stacking DoT
- 🔴 **Living Poison** - Moving poison pools (very deadly if combined with Double Swipe)
- The guide emphasizes: "Surviving through Venom Bolt Volley is one of the most crucial parts of the fight"

**Phase 3 - Drakkari (Southeast Door):**
- 🟡 **Deadly Plague** - Disease (dispel required)
- 🟡 **Frozen Orbs** - Slow-moving adds that slow + damage within 8 yards
- 🟡 **Mortal Strike** - 50% healing reduction on add tank

**Phase 4 - Amani (Southwest Door):**
- 🔴 **Chain Lightning** - Jumps to players within 5 yards, +50% damage per jump - **SPREAD 5+ YARDS**
- 🔴 **Lightning Nova Totems** - Unkillable totems dealing massive damage every 3 seconds within 8 yards
- 🟡 **Fireball** - High damage (interrupt)
- 🟡 **Hex of Confusion** - 50% chance to self-harm (dispel curse)
- 🟡 **Swipe** (Warbears) - Heavy frontal cone damage

**Phase 5 - War-God Jalak:**
- 🔴🔴 **Bestial Cry** - Heavy raid damage with stacking 25% increase - **BURN PHASE**
- 🔴🔴 **Horridon Enrage** (after Jalak dies) - 50% faster attacks, 100% increased damage - **EXTREME TANK DAMAGE**

---

## 🔴 **HEROIC MODE CHANGES**

### **New Mechanic: Dire Call (Every ~60 seconds)**

**What it does:**
1. Moderate raid-wide Physical damage
2. Buffs ALL living adds with 50% increased attack speed
3. **Spawns Direhorn Spirit** - one per cast

### **⚡ Direhorn Spirits - THE HEROIC MECHANIC**

**Critical Information:**
- Each Spirit fixates on one random raid member and only that player can see/attack it
- Spirits walk slowly toward their target
- If they reach their target, they deal extremely high melee damage, effectively killing them
- **Cannot be killed** (too much HP, only one person can attack)
- **Knockback on damage** - this is how you survive
- Fixation priority: Healers/Ranged DPS first → Melee DPS later
- Spirits spawn inside Horridon's hitbox

**Strategy:**
- Every player must manage their own Spirit for the entire fight
- Constantly knock back your Spirit with ranged abilities
- Stay away from Horridon when Dire Call is casting (gives you reaction time)

**Recommended Macro:**
```
#showtooltip [Your Ranged Ability]
/tar Direhorn Spirit
/cast [Your Ranged Ability]
/targetlasttarget
```

### **Heroic Kill Priority Adjustments**
The 50% attack speed buff makes these THE top priority in each phase:
1. **Farraki Wastewalkers**
2. **Gurubashi Venom Priests**
3. **Drakkari Frozen Warlords**
4. **Amani'shi Beast Shamans**

---

## 💡 **CRITICAL TIPS**

### **General Tips**
✅ **Tank Swap Timing:** Swap at the END of each phase (during 40s break) - tank can handle 6-7 stacks per phase
✅ **Horridon Positioning:** Always on the side (NEVER front/back due to Double Swipe)
✅ **Orb of Control:** You can MOVE while channeling - dodge traps/voids while directing Horridon
✅ **Charge Response:** Player targeted should move to minimize raid disruption from follow-up Double Swipe
✅ **Don't Push 30%:** If Horridon hits 30% HP before Phase 5, Jalak jumps early = likely wipe
✅ **Cracked Shell Stacks:** Horridon gains +50% damage taken per door destroyed (4 stacks by Phase 5)

### **Phase-Specific Tips**

**Phase 1 (Farraki):**
- Interrupt Stone Gaze OR dispel the stun immediately
- Sand Traps are hard to see - watch ground carefully during Double Swipe
- Dispel Blazing Sunlight DoT

**Phase 2 (Gurubashi):**
- 🚨 **INTERRUPT ROTATION ON VENOM BOLT VOLLEY** - This is fight-critical
- Dispel Venom Bolt Volley DoT if any get through
- Venomous Effusions are TOP PRIORITY (kill before Venom Priests)
- Watch for moving Living Poison pools

**Phase 3 (Drakkari):**
- Mass dispel Deadly Plague
- Kite Frozen Orbs away from raid
- Off-tank needs extra healing during Mortal Strike debuff

**Phase 4 (Amani):**
- **SPREAD 5+ YARDS** for Chain Lightning
- Kill Warbears one at a time to avoid overlapping Beast Shamans
- Avoid having 2 Beast Shamans alive (risk of double Lightning Nova Totems)
- Interrupt Fireball casts
- Dispel Hex of Confusion (curse)

**Phase 5 (Jalak):**
- 🚨 **USE BLOODLUST/HEROISM** - Burn Jalak down
- Stack for healing (Charge targets must minimize movement)
- Save ALL cooldowns for this phase
- **PRO TIP:** Jalak can be disarmed - set up disarm rotation to reduce Bestial Cry damage
- Some raids can survive long enough to kill Horridon first if disarm rotation is perfect
- After Jalak dies: Tank swap if possible, use ALL tank cooldowns for enraged Horridon

### **Heroic-Specific Tips**
✅ Stand away from Horridon during Dire Call cast
✅ Create and bind macro for Spirit knockback
✅ Never stop knocking back your Spirit
✅ Healers prepare for Dire Call raid damage spikes
✅ Kill priority adds FASTER due to attack speed buff

---

## 📊 **READY-TO-USE ASSIGNMENTS**

### **Tank Assignments**
| Role | Responsibilities |
|------|------------------|
| **Tank 1** (Horridon) | • Tank Horridon entire fight<br>• Position on SIDE of boss<br>• Swap at END of each phase (during 40s break)<br>• Move Horridon to next door during breaks<br>• **Heroic:** Stay away from Horridon during Dire Call |
| **Tank 2** (Adds/Jalak) | • Gather all adds in AoE-able position<br>• Tank Zandalari Dinomancers<br>• Tank War-God Jalak in Phase 5<br>• Interrupt Dino-Mending (Dinomancers)<br>• Taunt Horridon during phase transitions |

**Tank Swap Schedule:**
- Transition 1→2 (after Farraki door destroyed)
- Transition 2→3 (after Gurubashi door destroyed)
- Transition 3→4 (after Drakkari door destroyed)
- Transition 4→5 (after Amani door destroyed)
- Optional swap after Jalak dies if stacks dropped

### **Healer Assignments**

**Dispel Rotation (CRITICAL):**
| Phase | Priority Dispels | Type |
|-------|------------------|------|
| Phase 1 | Stone Gaze (stun), Blazing Sunlight (DoT) | Magic, Magic |
| Phase 2 | Venom Bolt Volley DoT | Magic |
| Phase 3 | Deadly Plague | Disease |
| Phase 4 | Hex of Confusion | Curse |

**Healing Focus:**
- Phase 1-4: Moderate sustained damage
- Phase 2: HEAVY if Venom Bolt Volley not interrupted
- Phase 5: EXTREME - use ALL healing cooldowns
- Post-Jalak: TANK WILL DIE - spam tank cooldowns

**Heroic Additions:**
- Prepare for Dire Call damage every ~60 seconds
- Each healer will eventually get a Direhorn Spirit to manage
- Assign healing cooldown rotation for Dire Call + Bestial Cry overlap

### **DPS Assignments**

**Interrupt Rotation:**
| Phase | Ability to Interrupt | Caster |
|-------|---------------------|--------|
| All Phases | Dino-Mending | Zandalari Dinomancer |
| Phase 2 | 🚨 Venom Bolt Volley (CRITICAL) | Gurubashi Venom Priest + Venomous Effusions |
| Phase 4 | Fireball | Amani'shi Flame Caster |

**Kill Priority by Phase:**

**Phase 1 (Farraki):**
1. Zandalari Dinomancer
2. Sul'lithuz Stonegazers (or interrupt Stone Gaze)
3. Farraki Wastewalkers
4. Farraki Skirmishers
5. Horridon (filler damage)

**Phase 2 (Gurubashi):**
1. Venomous Effusions (TOP PRIORITY)
2. Zandalari Dinomancer
3. Gurubashi Venom Priests
4. Gurubashi Bloodlords
5. Horridon (filler damage)

**Phase 3 (Drakkari):**
1. Zandalari Dinomancer
2. Drakkari Frozen Warlords
3. Risen Drakkari Warriors/Champions
4. Horridon (**DON'T push below 30%**)

**Phase 4 (Amani):**
1. Zandalari Dinomancer
2. Amani'shi Beast Shamans (kill one at a time)
3. Amani Warbears
4. Amani'shi Protectors/Flame Casters
5. Horridon (**DON'T push below 30%**)

**Phase 5 (Jalak):**
1. 🚨 **War-God Jalak** (BURN with all cooldowns)
2. Horridon (after Jalak dies)

**Heroic Priority Changes:**
- Wastewalkers/Venom Priests/Frozen Warlords/Beast Shamans become even higher priority
- These adds gain 50% attack speed from Dire Call

### **Positioning Assignments**

**Door Locations:**
- Phase 1: Northwest (Farraki)
- Phase 2: Northeast (Gurubashi)
- Phase 3: Southeast (Drakkari)
- Phase 4: Southwest (Amani)
- Phase 5: Center of room

**Raid Positioning:**
- **Melee:** Stay on Horridon's SIDE at all times
- **Ranged:** Spread loosely on sides, ready to move for Double Swipe
- **Phase 4:** Spread 5+ yards apart for Chain Lightning
- **Phase 5:** Stack for healing (except Charge targets)
- **Heroic:** Maintain distance from Horridon during Dire Call

### **Cooldown Schedule**

**DPS Cooldowns:**
- **DON'T use at pull**
- Save for Phase 5 Jalak burn
- Use Bloodlust/Heroism when Jalak jumps

**Defensive Cooldowns:**
- Phases 1-4: Minor cooldowns for Dire Call (Heroic)
- Phase 5: Rotate ALL raid cooldowns during Jalak burn
- Post-Jalak: ALL tank cooldowns to survive enraged Horridon

**Suggested Rotation (Phase 5):**
1. Jalak spawn → Bloodlust + DPS cooldowns
2. First Bestial Cry → Spirit Link Totem
3. Second Bestial Cry → Barrier/Tranquility
4. Third Bestial Cry → Rally/Divine Hymn
5. Jalak death → Devotion Aura/Darkness
6. Enraged Horridon → Shield Wall, Last Stand, Guardian Spirit on tank

### **Special Role Assignments**

**Orb of Control (All Phases 1-4):**
- Assign mobile player (ideally ranged DPS)
- Must click at 50% Dinomancer HP
- Channel while moving to avoid traps/voids
- Direct Horridon to destroy current door

**Disarm Rotation (Heroic Phase 5 - OPTIONAL):**
- Assign all classes with disarm abilities
- Rotate disarms on Jalak to reduce Bestial Cry damage
- Can extend survival significantly

---

## 🎯 **PHASE TIMELINES**

**Standard Run (75s per door):**
- 0:00 - Pull, Phase 1 starts
- 1:00 - Dinomancer 1 spawns
- 1:15 - Door 1 destroyed, 40s break
- 1:55 - Phase 2 starts
- 2:55 - Dinomancer 2 spawns
- 3:10 - Door 2 destroyed, 40s break
- 3:50 - Phase 3 starts
- 4:50 - Dinomancer 3 spawns
- 5:05 - Door 3 destroyed, 40s break
- 5:45 - Phase 4 starts
- 6:45 - Dinomancer 4 spawns
- 7:00 - Door 4 destroyed, 40s break
- 7:40 - Phase 5 starts (hold Horridon above 30%)
- 8:15 - War-God Jalak jumps
- 12:00 - **HARD ENRAGE**

---

## ⚡ **QUICK REFERENCE CARD**

| Item | Details |
|------|---------|
| **Enrage** | 12 minutes (hard) |
| **Tanks** | 2 (swap end of each phase) |
| **Healers** | 2-3 (10m) / 5-7 (25m) |
| **Phases** | 5 total (4 doors + Jalak) |
| **Door Timer** | ~75 seconds each + 40s break |
| **Bloodlust** | Phase 5 on Jalak |
| **Heroic Mechanic** | Direhorn Spirits (personal knockback management) |
| **Hardest Phases** | Phase 2 (Venom Priests), Phase 5 (Jalak burn) |
| **Common Wipes** | Venom Bolt Volley, Sand Traps, Pushing 30% early, Spirits reaching target (H) |

---

## 📝 **PULL SEQUENCE**

1. **Pre-pull:** Assign interrupt rotation, dispellers, Orb clicker
2. **Pull:** Tank 1 pulls Horridon to NW door
3. **0:05:** First Farraki adds spawn - Tank 2 picks up
4. **Throughout fight:**
   - Interrupt Dino-Mending
   - Kill priority targets
   - Stay on SIDES of Horridon
   - Dispel assigned debuffs
   - **Heroic:** Knock back Direhorn Spirits constantly
5. **Each door:** Kill Dinomancer → Click Orb → Direct to door → 40s break
6. **Transitions:** Clear adds, damage Horridon, move to next door, tank swap
7. **Before Phase 5:** Stop DPS if Horridon near 30%, regen mana, save cooldowns
8. **Phase 5:** Bloodlust + burn Jalak → Survive enraged Horridon

---

**Source:** [Icy Veins - Horridon Strategy Guide](https://www.icy-veins.com/wow/horridon-strategy-guide-normal-heroic)
