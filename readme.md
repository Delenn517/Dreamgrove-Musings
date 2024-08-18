---
title: 'Feral Druid Compendium'
patch: '10.2.6'
draft: false
authors: ["Crazymeow", "Cheesey"]
summary: 'Everything you need to know about Feral Druid'
---

# News:

## Season 4 News

Nothing is changing for Feral Druids in terms of gameplay or talents, but the Dinar system is returning in season 4 with the new currency [Antique Bronze Bullion](https://www.wowhead.com/ptr-2/item=213089/antique-bronze-bullion). For more information on how to spend these, go [here](#dinar)

# Rotation:
**What is a priority list?**

When reading the priority lists below, you should not think about these as steps to follow in a specific order. At any given point in combat, you should cast the first thing in the list that you are able to cast.

The way this section is written is very formulaic and has the same structure as the Action Priority List (APL) used in sims. If you need a more digestable format, try [WoWHead's guide](https://www.wowhead.com/guide/classes/druid/feral/rotation-cooldowns-pve-dps#single-target) written by Guilty

## Pre-combat

**Pre-Combat:**
- Use !Heart of the Wild!
- Use !Prowl!
- Use !Tiger's Fury!
- Use !Rake! from stealth.

## Single Target Priority

**Select which talents you have talented to filter the priority list:**

<CheckboxProvider>
<Checkbox id="Feral Frenzy" spellId={274838} name="Feral Frenzy" defaultCheck />
<Checkbox id="Convoke the Spirits" spellId={391528} name="Convoke the Spirits" defaultCheck />
<Checkbox id="Adaptive Swarm" spellId={391889} name="Adaptive Swarm" defaultCheck radio="Adaptive Swarm"/>
<Checkbox id="Unbridled Swarm" spellId={391951} name="Unbridled Swarm"  radio="Adaptive Swarm"/>
<Checkbox id="Incarnation" spellId={102543} name="Incarnation"  />
<Checkbox id="Lunar Inspiration" spellId={155580} name="Lunar Inspiration"  />
<Checkbox id="Apex Predator's Craving" spellId={391881} name="Apex Predator's Craving" defaultCheck />
<Checkbox id="Bloodtalons" spellId={319439} name="Bloodtalons" defaultCheck />
<Checkbox id="Relentless Predator" spellId={393771} name="Relentless Predator"  />
<Checkbox id="Thrashing Claws" spellId={405300} name="Thrashing Claws"  />
<Checkbox id="Sudden Ambush" spellId={384667} name="Sudden Ambush" defaultCheck />
<Checkbox id="Brutal Slash" spellId={202028} name="Brutal Slash" radio="Brutal Slash" defaultCheck />
<Checkbox id="Wild Slashes" spellId={390864} radio="Brutal Slash" name="Wild Slashes"  />
<Checkbox id="Shadowmeld" spellId={58984} name="Shadowmeld"  />
<Checkbox id="Dire Fixation" spellId={417710} name="Dire Fixation" defaultCheck />
<Checkbox id="T31 2P" name="T31 2P" defaultCheck isText/>
<Checkbox id="T31 4P" name="T31 4P" defaultCheck isText/>
</CheckboxProvider>

**Single Target priority list:**

- Use !Tiger's Fury! if any of the following conditions are met
    - !Tiger's Fury! is not up.
    - You are more than 65 energy from the cap.
    - [*T31 2P] !Feral Frenzy! is ready to be used.
    - [*~T31 4P] You've talented !Convoke the Spirits! (This keeps !Tiger's Fury! and !391528|Convoke! aligned.)
- [*Adaptive Swarm]  Use !Adaptive Swarm! when all of these conditions are met:
    - There isn't an !Adaptive Swarm! heading to an enemy target.
    - !Adaptive Swarm! is either not up or it is about to expire with 1 or 2 stacks.
- [*Unbridled Swarm] !Adaptive Swarm! conditions change based on the amount of !391888|Adaptive Swarms! you have out:
    - If you have 3 !391888|Adaptive Swarms! with at least 2 stacks out then you will target allies with priority 1 stack > 0 stack > 2 stacks.
    - If you have 2 or fewer !391888|Adaptive Swarms! of at least 2 stacks, cast on your enemy target when swarm is not on them, and is not traveling towards them.
- [*Incarnation] Use !102543|Incarnation! if it's ready.
- [*Convoke the Spirits] Use !391528|Convoke! if all of the following conditions are met:
    - !Rip! will not fall off during Convoke's channel.
    - !Tiger's Fury! is up.
    - [*T31 4P] !422751|Smoldering Frenzy! is up
    - [*T31 2P] You have 0 or 1 combo points OR !422751|Smoldering Frenzy! would fall off before Convoke ends.
- [*Feral Frenzy] Use !Feral Frenzy! if all of the following conditions are met:
    - [*Dire Fixation] !Dire Fixation! is applied to the target.
    - You have less than 2 combo points and are not in !102543|Incarn!/!Berserk!, or under 3 combo points during !102543|Incarn!/!Berserk!.
- [*Apex Predator's Craving] Use !Ferocious Bite! if you have a !Apex Predator's Craving! proc.

**If you are in !Berserk! check this as your priorities from here on out change a bit:**
<Checkbox id="Berserk" spellId={106951} name="Berserk" /> 

<div>
- [*~Berserk] **Standard Priority**
    - Use !Rip! when all of these conditions are met:
        - You have at least 4 combo points
        - [*T31 2P] !Rip! is in pandemic OR all of these conditions are met:
            - !Rip! has less than 10 seconds remaining
            - Your next gcd will be !Feral Frenzy!
        - [*~T31 2P] !Rip! is in pandemic
        - [*T31 2P] !Rip! has less than 2 seconds remaining, or you don't have !422751|Smoldering Frenzy! up. Yes this means !Rip! will sometimes fall off with proper play.
        - !Tiger's Fury! is up, or won't be up before !Rip! expires.
        - [*Bloodtalons] !Bloodtalons! is up, or won't be up before !Rip! expires.
    - Use !Ferocious Bite! when all of these conditions are met:
        - You have at least 4 combo points
        - [*~Relentless Predator] You have at least 50 energy. If you have the combo points, you should wait until you reach these energy thresholds.
        - [*Relentless Predator] You have at least 45 energy. If you have the combo points, you should wait until you reach these energy thresholds.
    - [*Bloodtalons] **Below this point, skip any spells you've already casted towards !Bloodtalons!, if you have 0 or 1 stacks of !Bloodtalons! remaining.**
    - [*~Thrashing Claws] Use !Clearcasting! procs on !Thrash! if all of these conditions are met:
        - !Thrash! is in Pandemic.
        - [*Dire Fixation] !Dire Fixation! is already applied to your target.
    - [*Dire Fixation] Use !Shred! if !Dire Fixation! is not on your target or you have a !Clearcasting! proc.
    - [*~Dire Fixation] Use !Shred! if you have a !Clearcasting! proc.
    - [*Brutal Slash] Use !Brutal Slash! if it will cap on charges within the next 4 seconds.
    - [*Shadowmeld] Use !58984|Shadowmeld! followed by !Rake! if all of these conditions are met:
        - [*Sudden Ambush] You do not have a !Sudden Ambush! proc
        - !Rake! is in pandemic OR you would be upgrading !Rake!'s snapshot value.
    - Use !Rake! if any of these conditions are met:
        - !Rake! is in pandemic and !Tiger's Fury! is either up, or won't be before !Rake! falls off.
        - You are in stealth
        - [*Sudden Ambush] You have a !Sudden Ambush! proc and you would be upgrading !Rake!'s snapshot value.
    - [*Lunar Inspiration] Use Lunar Inspiration !Moonfire! if it is in pandemic.
    - [*~Thrashing Claws] Use !Thrash! if it is in pandemic
    - [*Brutal Slash] Use !Brutal Slash!.
    - [*Wild Slashes] Use !Swipe!
    - Use !Shred!.
    - [*Bloodtalons] If you still need !Bloodtalons! proc it with this priority:
        - [*Lunar Inspiration] Clip Lunar Inspiration !Moonfire!
        - [*~Brutal Slash] Use !Swipe!
        - Use !Rake! if it will not downgrade !Rake!'s snapshot value.
        - Clip !Thrash!
</div>
<div>
- [*Berserk] **Berserk Priority**
    - Use !Rip! when all of these conditions are met:
        - You have 5 combo points
        - [*T31 2P] !Rip! is in pandemic OR all of these conditions are met:
            - !Rip! has less than 10 seconds remaining
            - Your next gcd will be !Feral Frenzy!
        - [*~T31 2P] !Rip! is in pandemic
        - [*T31 2P] !Rip! has less than 2 seconds remaining, or you don't have !422751|Smoldering Frenzy! up. Yes this means !Rip! will sometimes fall off with proper play.
        - !Tiger's Fury! is up, or won't be up before !Rip! expires.
        - [*Bloodtalons] !Bloodtalons! is up, or won't be up before !Rip! expires.
    - Use !Ferocious Bite! with 5 combo points
    - [*Incarnation]  Use !Prowl! followed by !Rake! if it won't disrupt !Bloodtalons! and any of these conditions are true:
        - !Rake! is not applied or is in pandemic range
        - [*Sudden Ambush] You don't have !Sudden Ambush! AND a stealth !Rake! would be upgrading its snapshot
    - [*Shadowmeld]  Use !58984|Shadowmeld! followed by !Rake! if it won't disrupt !Bloodtalons! and any of these conditions are true:
        - !Rake! is not applied or is in pandemic range
        - [*Sudden Ambush] You don't have !Sudden Ambush! AND a stealth !Rake! would be upgrading its snapshot
    - [*Bloodtalons] Use !Rake! if it won't disrupt !Bloodtalons! and any of these conditions are true:
        - !Rake! is not applied or is in pandemic range
        - [*Sudden Ambush] You have a !Sudden Ambush! proc AND a stealth !Rake! would be upgrading its snapshot
    - [*~Bloodtalons] Use !Rake! if any of these conditions are true:
        - !Rake! is not applied or is in pandemic range
        - [*Sudden Ambush] You have a !Sudden Ambush! proc AND a stealth !Rake! would be upgrading its snapshot
    - [*Bloodtalons] If you are one spell away from proccing !Bloodtalons! then proc it with this priority:
        - !Shred!
        - [*Brutal Slash] !Brutal Slash!.
        - [*Lunar Inspiration] Lunar Inspiration !Moonfire! This is true even if it means clipping moonfire early.
        - !Thrash! This is true even if it means clipping thrash early.
    - [*Lunar Inspiration] Use Lunar Inspiration !Moonfire! if it is not applied or is in pandemic range.
    - [*Brutal Slash] Use !Brutal Slash! if you have 2 or 3 charges
    - Use !Shred!
</div>
## AoE priority

**Select which talents you have talented to filter the priority list:**

<CheckboxProvider>
<Checkbox id="Feral Frenzy-AOE" spellId={274838} name="Feral Frenzy" defaultCheck />
<Checkbox id="Convoke the Spirits-AOE" spellId={391528} name="Convoke the Spirits" defaultCheck />
<Checkbox id="Adaptive Swarm-AOE" spellId={391889} name="Adaptive Swarm" radio="Adaptive Swarm" />
<Checkbox id="Unbridled Swarm-AOE" spellId={391951} name="Unbridled Swarm" radio="Adaptive Swarm"/>
<Checkbox id="Incarnation-AOE" spellId={102543} name="Incarnation"  />
<Checkbox id="Lunar Inspiration-AOE" spellId={155580} name="Lunar Inspiration"  />
<Checkbox id="Apex Predator's Craving-AOE" spellId={391881} name="Apex Predator's Craving" defaultCheck />
<Checkbox id="Bloodtalons-AOE" spellId={319439} name="Bloodtalons" defaultCheck />
<Checkbox id="Tear Open Wounds-AOE" spellId={391786} name="Tear Open Wounds" defaultCheck />
<Checkbox id="Rampant Ferocity-AOE" spellId={391710} name="Rampant Ferocity"  />
<Checkbox id="Thrashing Claws-AOE" spellId={405300} name="Thrashing Claws"  />
<Checkbox id="Sudden Ambush-AOE" spellId={384667} name="Sudden Ambush" defaultCheck />
<Checkbox id="Brutal Slash-AOE" spellId={202028} name="Brutal Slash" defaultCheck />
<Checkbox id="Shadowmeld-AOE" spellId={58984} name="Shadowmeld"  />
<Checkbox id="Dire Fixation-AOE" spellId={417710} name="Dire Fixation" defaultCheck />
<Checkbox id="Primal Wrath-AOE" spellId={285381} name="Primal Wrath" defaultCheck />
<Checkbox id="T31 2P-AOE" name="T31 2P" defaultCheck isText/>
<Checkbox id="T31 4P-AOE" name="T31 4P" defaultCheck isText/>
</CheckboxProvider>

**AoE priority list(2+ targets):**
**Special Note: Try to use single-target spells on higher priority/higher healthed mobs, or mobs that have !Dire Fixation! on them.**
- Use !Tiger's Fury! if any of the following conditions are met
    - !Tiger's Fury! is not up.
    - You are more than 65 energy from the cap.
    - [*T31 2P-AOE] !Feral Frenzy! is ready to be used.
    - [*~T31 4P-AOE] You've talented !Convoke the Spirits! (This keeps !Tiger's Fury! and !391528|Convoke! aligned.)
- [*Adaptive Swarm-AOE] Use !Adaptive Swarm! when all of these conditions are met:
    - There isn't an !Adaptive Swarm! heading to an enemy target.
    - !Adaptive Swarm! is not up on a target.
- [*Unbridled Swarm-AOE] With !Unbridled Swarm! talented, use !Adaptive Swarm! as often as you can with this priority:
    - An enemy target has 2 stacks of !Adaptive Swarm!.
    - An enemy target has 1 stack of !Adaptive Swarm!.
    - An enemy target does not have !Adaptive Swarm!.
- [*Incarnation-AOE] Use !102543|Incarnation!
- [*~Incarnation-AOE] Use !Berserk!
- [*Convoke the Spirits-AOE] Use !391528|Convoke! if all of the following conditions are met:
    - Your !Rip!s will not fall off during !391528|Convoke's! channel.
    - !Tiger's Fury! is up.
    - [*T31 4P-AOE] !422751|Smoldering Frenzy! is up.
    - [*T31 2P-AOE] You have 0 or 1 combo points OR !422751|Smoldering Frenzy! would fall off before !391528|Convoke! ends.
    - [*~T31 2P-AOE] You have 0 or 1 combo points
- [*Feral Frenzy-AOE] Use !Feral Frenzy! if you have less than 2 combo points and are not in !102543|Incarn!/!Berserk!, or under 3 combo points during !102543|Incarn!/!Berserk!.
- [*Apex Predator's Craving-AOE] Use !Ferocious Bite! if you have a !Apex Predator's Craving! proc and:
    - [*~Primal Wrath-AOE] Don't have !Primal Wrath! talented or
    - Don't have !Sabertooth! up.
- [*Primal Wrath-AOE] Use !Primal Wrath! if you have 5 combo points, or at least 4 combo points outside of !Berserk!/!102543|Incarnation! and any of these conditions are met:
    - [*~Tear Open Wounds-AOE] !Rip!s from !Primal Wrath! are in pandemic
    - [*Tear Open Wounds-AOE] You have Tear Open Wounds talented
    - [*~Rampant Ferocity-AOE] There are at least 5 targets in range
- [*~Primal Wrath-AOE] Use !Rip! on targets without !Rip! that will live for a decent amount of time.
    - Please, I beg you, if you are using !Rip! on multiple targets you should seriously be talenting !Primal Wrath!. It's as close to mandatory as it gets.
- Use !Ferocious Bite! if you have 5 combo points, or at least 4 combo points outside of !Berserk!/!102543|Incarnation!.
- [*Bloodtalons-AOE] **Below this point, skip any spells you've already casted towards !Bloodtalons! if inside !Berserk!/!102543|Incarnation! or if you have 0 or 1 stacks of !Bloodtalons!.**
- [*Brutal Slash-AOE] Use !Brutal Slash! if it will cap on charges within the next 4 seconds.
- [*~Thrashing Claws-AOE] Use !Thrash! if in pandemic range and any of these conditions:
    - You have a !Clearcasting! proc
    - [*Sudden Ambush-AOE] You either do not have !Double-Clawed Rake! talented or !Sudden Ambush! isn't up
    - [*~Sudden Ambush-AOE] You do not have !Double-Clawed Rake! talented
- [*Incarnation-AOE] Use !Prowl! followed by !Rake! on a target where !Rake! is either not applied or in pandemic range
- [*Shadowmeld-AOE] Use !58984|Shadowmeld! followed by !Rake! on a target where !Rake! is either not applied or in pandemic range
- [*Incarnation-AOE] Use !Prowl! followed by !Rake! on a target where !Rake! does not have a !Pouncing Strikes! snapshot
- [*Shadowmeld-AOE] Use !58984|Shadowmeld! followed by !Rake! on a target where !Rake! does not have a !Pouncing Strikes! snapshot
- Use !Rake! on a target with either of these conditions met:
    - !Rake! is not applied or is in pandemic range
    - [*Sudden Ambush-AOE] You have !Sudden Ambush! up and can upgrade the snapshot value of a !Rake!
- [*~Thrashing Claws-AOE] Use !Thrash! if in pandemic range
- [*Brutal Slash-AOE] Use !Brutal Slash!
- [*~Brutal Slash-AOE] Use !Swipe! if there are 5 or more targets
- [*Lunar Inspiration-AOE] Use Lunar Inspiration !Moonfire! on a target without !Moonfire! or if !Moonfire! is in pandemic range and there are less than 5 targets.
- [*~Brutal Slash-AOE] Use !Swipe!.
- [*Sudden Ambush-AOE] Use !Shred! if !Sudden Ambush! is not up and:
    - [*Dire Fixation-AOE]  !Dire Fixation! is talented
    - [*~Dire Fixation-AOE] There are 3 or fewer targets.
- [*~Sudden Ambush-AOE] Use !Shred! if:
    - [*Dire Fixation-AOE]  !Dire Fixation! is talented
    - [*~Dire Fixation-AOE] There are 3 or fewer targets.
- [*~Thrashing Claws-AOE] Use !Thrash!.
- [*Bloodtalons-AOE] If you still need !Bloodtalons! proc it with this priority:
    - [*Lunar Inspiration-AOE] Lunar Inspiration !Moonfire! if there is a target without !Moonfire!.
    - !Shred!
    - [*Lunar Inspiration-AOE] Lunar Inspiration !Moonfire! on the target with the lowest duration.
    - !Rake! ideally on a target where the new snapshot would be at least the same strength as the currently applied !Rake!.
    - [*Thrashing Claws-AOE] !Thrash!

# Talents:

## Raid Talents

### T31 4pc Talent Builds (Amirdrassil tier-set, still applies in season 4)

[T31 Standard Convoke Single-Target](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVFAVRUVFVKVRAQCBU)
[One-minute Burst](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCYpCFREExRQQBRNVFAVRUVFVoVRECBU)
[Raid ST-AoE hybrid](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVRAVRUVFVYRVBQCFU)
[Raid Cleave](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCYpCFREExRQQBBOVRURRQVFVIUVRQCFQ)
[Alternative L/R LI Single Target](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCYpCFREExRQQBROVBAZRVVFUiURBQBE)
[Alternative L/R BrS Single Target](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVFAVRUVFViURBQCBQ) (slightly worse).
- Note: generally best to play 'Standard Convoke' for single-target, assuming you have an on-use trinket like Ashes or Witherbark's. They sim equally, however Convoke offers more burst, and pulls ahead with Augmentation buffing you. Kill timers can also play a factor; if you are unsure, stick to Convoke. If you do play L/R, Infected Wounds can optionally be swapped for Lunar Inspiration with T31 as well.

### Vault of the Incarnates Raid Boss Talents
[Eranog](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCYZCFRUExRQQBROVRQRRUVFVIVVBQCFU)
- You can alternatively play a more single-target oriented build, or if your guild one-phases the boss can drop !Berserk: Heart of the Lion! for another talent point, and most likely 1 minute convoke with that.

[The Primal Council](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCYZCFRUExRQQBROURURVQVFVYRVBQCFE)
- Full sustain AoE. Can consider going Unbridled Swarm as well.

[Terros](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVFAVRUVFVKVRAQCBU)
- Very straightforward, full single target. Can sim your expected fight timer to see if any of the other single target builds are better for your guild.

[Sennarth](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVFAVRUVFVKVRAQCBU)
- Adds die too fast to get any meaningful cleave so just go full single target.

[Kurog Grimtotem](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCYZCFRUExRQQBROURURVQVFVIVVBQCFU)
- Mostly 2t cleave

[Dathea - Boss Duty](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVFAVRUVFVKVRAQCBU)
- This assumes you stay on boss the entire time. If you are on adds instead, then play the Add Duty build below.

[Dathea - Add Duty](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQZCFVUUxRQQCQQOURURVQVFVYRVBQCFU)

[Broodkeeper Diurna](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCYZCFRUExRQQBROURURVQVFVYRVBQCFU)
- If adds end up dying too fast on Fated then you can drop double-clawed rake and/or rampant ferocity for more p3 boss burn.

[Raszageth](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFVEExhQQBBOVRQRRUVFVIRVFQCFU)

### Aberrus Raid Boss Talents
[Kazzara](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVFAVRUVFVKVRAQCBU)
- Can sim your expected kill timer to see if 1 minute convoke would do more damage for you, but this is just a single target fight.

[Amalgamation Chamber](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVFAVRUVFVKVRAQCBU)

[Forgotten Experiments](https://www.wowhead.com/talent-calc/druid/feral/DAQAUEEBCYpCFBUEwhFBAOVRQRRUVFVIUVRQCFQ)
- Can make a case for alternate builds, feel free to 'experiment' around with things.

[Assault of the Zaqali](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVFAVRUVFVKVRAQCBU)
- This assumes zerg strat, if you dont do zerk strat then you probably should be doing zerg strat but play full aoe.

[Rashok](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVFAVRUVFVKVRAQCBU)

[Zskarn](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVFAVRUVFVKVRAQCBU)
- Primal wrath is bait. Golems should be handled by other specs. If you absolutely need some aoe, dont do anything more than talenting primal wrath.

[Magmorax](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVFAVRUVFVKVRAQCBU)

[Echo of Neltharion](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCYZCFRUExRQQBROVVARRUVFVIVVBQCBV)
- Can consider dropping primal wrath altogether, and can go 2 points into saber jaws, removing points from circle and rip and tear.

[Sarkareth](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCYZCFRUExRQQBROVVARRUVFVIVVBQCBV)
- Can also go 2 points into saber jaws, removing points from circle and rip and tear.

### Amirdrassil Raid Boss Talents
[Gnarlroot](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCQpCFREExhUQBROVVARRUVFVoRVAQCBV)
- If you need more AOE, swap !Carnivorous Instinct! to !400320|Circle!. You can also play full single-target if adds don't feel like an issue.

[Igira](https://www.wowhead.com/talent-calc/druid/feral/DAREUEEBCQZCFREExhUQBROVFAVRUVFVKVRAQCBU)
- Play full single-target, the spears will die too fast for Primal Wrath to be worth it in most cases. Frenzied Regen can be useful for clearing the healing absorb.

[Volcoross](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCYpCBREExhQQBRNVFAVRUVFVoVRECBU)
- If your kill time is above 4.20~ or so, swap to the 2 minute 'standard convoke single-target' build listed above.

[Council of Dreams](https://www.wowhead.com/talent-calc/druid/feral/DARBUUEFCYpCBREAxBQQBEOVRURRQVFVIUVRQCFQ)
- You can play Lunar Inspiration, which is technically better, albeit more difficult to play. With Dire Fixation you use Shred as a last priority filler.
- You can also play Incarn instead which is more simple to play.
- Dispel allows you to quickly and safely dispel yourself on Mythic. 

[Nymue](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCYpCBREExhQQBRNVFAVRUVFVoVRECBU)
- 1 minute Convoke lines up with all of the intermissions. 

[Larodar](https://www.wowhead.com/talent-calc/druid/feral/DARAUEEBCUpCBREExhUQBRNVFAVRUVFVoVRECBU)
- L/R single target also works here, but given you probably have gear optimised for Convoke, just play 1 min Convoke, as it has great timings for this fight too. 

[Smolderon](https://www.wowhead.com/talent-calc/druid/feral/DAQEVEFBCQpCFREEwhEBQOVFAZREVFVKRREQCBU)
- Extra Tireless Energy + Apex to try and get Berserk up for each intermission. 1 min Convoke for intermission damage amps.

[Tindral](https://www.wowhead.com/talent-calc/druid/feral/DAREVEFBCQJCFREExhQQBROVFAVRUVFVaRRAQCBU)
- With roots being nerfed, Feral should play full single-target on Tindral now with 2 minute Convoke. Let other specs carry the roots. Convoke will line up with the shields.

[Fyrakk](https://www.wowhead.com/talent-calc/druid/feral/DAREUEEBCQJCFVEExhUQBROVFAVRUVFVKVRAQCBU)
- Damage to adds are irrelevant, this is another 2 minute single-target Convoke fight as Feral where you can carry the boss damage. Take Typhoon to knock the adds however.

### T31 Raid Talent Customisation

In the first two gates, you can freely swap between !Merciless Claws!, !Tireless Energy!, !Infected Wounds!, and !Primal Wrath!, based on what you need.
- !Merciless Claws! is the strongest burst option of these nodes, and only slightly behind in sustained single-target and cleave.
- !Infected Wounds! for stronger sustained single-target, or if multi-dotting with Rake.
- !Tireless Energy! for strong single-target and solid in cleave and AoE, but weaker for burst. You should also adjust points if you are overcapping energy via !391881|Apex! procs or downtime due to mechanics. 
- !Primal Wrath! if there are regular adds that need to die, or adds that can provide funnel opportunities with !391881|Apex!.
- Note: !Tear Open Wounds! and !Double-Clawed Rake! are additional options particularly for sustained AoE/cleave (Council), or if your raid is struggling with certain adds. 

Final gate options: swap between !Carnivorous Instinct!, !Circle of Life and Death!, !Saber Jaws!, !Rip and Tear!, 1 minute !Convoke the Spirits!, and !Adaptive Swarm!, as needed.
- !400320|Circle!: generally worth grabbing if taking !Primal Wrath! with !391881|Apex!, or if there's a lot of multi-dot potential.
- !Carnivorous Instinct!: strong burst, with good single-target and AoE. Predator resets and high !Tiger's Fury! uptime add value here.
- !Saber Jaws!: strong single-target pathing option to !391881|Apex!. 
- !Rip and Tear!: cleave and AoE pathing option to !391881|Apex!, not too far behind on single-target vs Saber Jaws with Convoke as it lets you spend another point elsewhere.
- 1m !Convoke the Spirits!: if you need more frequent burst, or are just a gambling addict. Your Kill times will also play a significant factor. For instance, if your raids kill time aligns better with the cooldown of 1 minute Convoke (odd e.g. 5:31) compared to 2 minute Convoke (even e.g. 4:31).
- !Adaptive Swarm!: incredibly strong single-target synergy with tier-set, can drop at times for heavy AoE.

### Class Tree Talents for Raid

- *Coming soon with specific boss builds. 
- For now: remember to take !Innervate!! You can cast in Cat Form now, and your healers will need it as the Rashok healer trinket has been nerfed.

 
## Dungeon Talents

The builds listed here are only a sample, and can be customised significantly. Various options and the logic on when you might swap certain talents are outlined in the section below.

[Standard M+](https://www.wowhead.com/ptr-2/talent-calc/druid/feral/DARAUEEBCQJCFVUExhUQBBOVRURRQVFVYRVBQCFU)
[More Single-Target](https://www.wowhead.com/ptr-2/talent-calc/druid/feral/DARAUEEBCQJCFVUExhUQBBOVRURRQVFVIVVBQCFU)
[More Priority Damage](https://www.wowhead.com/ptr-2/talent-calc/druid/feral/DARAUEEBCQJCFVUExhUQBBOURURRUVFVIVVBQCFU)
[Max Dungeon Single-Target](https://www.wowhead.com/ptr-2/talent-calc/druid/feral/DARAUEEBCQJCFVUExhUQBBOVRQRRUVFVIVVBQCFU)
[MDI Pad](https://www.wowhead.com/ptr-2/talent-calc/druid/feral/DARAUEEBCQJCFVUExhUQBBOVRQRVEVFVYRVBQCFU)
[Incarn](https://www.wowhead.com/ptr-2/talent-calc/druid/feral/DARAUEEBCQJCFVUExhUQBBOVRURRQVFVYRVBQCFE)
[Beekeeping](https://www.wowhead.com/ptr-2/talent-calc/druid/feral/DARAUEEBCYJCFVUExRQQBBOVRURRQVFVIUVRQCFQ)
[Funnel Option](https://www.wowhead.com/ptr-2/talent-calc/druid/feral/DARAUEEBCQJCFVUExhUQBBOVRERVQVFVYRVBQCFU)

### [M+ Talent Customisation](#m+)

![Mythic](/static/images/feral-tree-mythic+.png)

Note: for Feral, the talents in the first two gates have similar power-levels, and you can freely distribute extra points how you please here, up until you have spent 20 points. The final gate has stronger nodes and you should always spend the maximum points possible here (10).

Options for the first two gates:
- !Double-Clawed Rake! -> !Rampant Ferocity!: this comes down to pull size; DCR particularly excels in low and medium (pug) size pulls and is generally the better choice, however RF can pull ahead with large pulls e.g. in a dungeon with dense trash or with an organised group doing consistent triple~ pulls.
- !Double-Clawed Rake! -> !Taste for Blood!: if you want more single target, TFB is a great option e.g. for Tyrannical weeks, while also providing some funnel value on trash.
- !Tear Open Wounds! -> !Rampant Ferocity!: if your goal is purely to funnel, you can change to RF and spend your finishers on Bite while only using !Primal Wrath! to maintain !Rip! in AoE. This is somewhat more advanced with more consideration for energy and combo points, and requires you to break 'primal wrath spam' muscle memory.
- !Infected Wounds! -> !Taste for Blood!: if you are not running Double-clawed Rake, Taste for Blood is a great option that offers a prominent single target gain over Infected Wounds this patch as a result of the !391881|Apex! changes. Even moreso if running !Convoke the Spirits!.
- !Taste for Blood! -> !Dire Fixation!: both are great single-target options, you can run Taste for Blood for more funnel (via Apex) and burst with Convoke.
- !Dire Fixation! -> !Rampant Ferocity!: you can run both Tear Open Wounds and Rampant Ferocity together if it is an AOE heavy dungeon, but single-target will be lower without Dire Fixation or Taste for Blood.

Options for the final gate:
- !Bloodtalons! vs !Lion's Strength!: in 10.2, BT gains a lot of quality of life when changing to the new tier-set, in addition to the !391881|Apex! change with procs slowing down slightly in AoE. This combined with the 10.1 change of 3 charges makes BT feel smooth to play in season 3 M+. However, Lion's Strength is still a competitive option and only a small DPS loss while allowing you to focus on other things. If you are fairly new to Feral, you should start with Lion's Strength and swap to Bloodtalons when you have learnt everything else.
- !Convoke the Spirits! vs !102543|Incarnation!: both talents are equally viable and will depend on your talents, gear, dungeon, and own preference. Convoke is very strong with Witherbark's Branch or similar on-use trinkets, and similarly should be played if dropping Rake talents such as Infected Wounds (as Incarn wants Rake talents), while Incarn can pull ahead with larger pulls. These two options are interchangeable though and there is no all-round 'best.' 
- 1 min !391528|Convoke!: generally worse than 2m, however is a competitive option if running !Rampant Ferocity!. Drop Carnivorous Instincts/Swarm for it.
- !Carnivorous Instinct! vs !Adaptive Swarm!: CI is your 'safe' all-round good pick, however Swarm is a very strong single-target option and should be considered for Tyrannical.
- !Unbridled Swarm!: for a talent that undersims, this is simming competitively with the more standard builds. In other words: this is looking to be very, very good this patch. Take in medium pull size dungeons.
- Honourable mention: !Veinripper! can be a good funnel option if playing a !Rampant Ferocity!-focused build and focusing on ethical prio-damage.

### M+ Class Tree

![MythicClass](/static/images/feral-class-tree-mythic+.png)

The druid tree offers a fair degree of customisation as Feral in M+, with a range of utility and defensive options. What is selected (yellow) is mandatory, with blue nodes being your options based on affixes or personal preference. 

- !Remove Corruption! for Afflicted weeks. Additionally, the following dungeons have poison and curse dispels: Atal'Dazar, Darkheart Thicket, Throne of the Tides, and Waycrest Manor.
- !Hibernate! for Incorporeal weeks.
- !Nature's Vigil! is still very strong in AoE, and will often keep you alive or minimise the need to Regrowth on big pulls, increasing your DPS. Over the dungeon it usually does more personal healing to you than any other talent, while also healing your group mates. Macro to Berserk/Incarn. 
- !Protector of the Pack! is a strong self-healing node for Feral, and gains even more value if you can occasionally utilise it to heal your group as well.
- !Nurturing Instinct! should only be considered if Beekeeping for small DPS and HPS gains.
- !Feline Swiftness! is commonly dropped in high-end for more defensives and utility, as Catform gives 30% speed baseline which is more than enough for dungeon mechanics. If uncomfortable, try only dropping 1 point at first to retain 8%.
- !Ursine Vigor! is more of a high-key talent to survive one-shots.

# Consumables:

## Potions

[Elemental Potion of Ultimate Power](https://www.wowhead.com/item=191383/elemental-potion-of-ultimate-power) for every situation

## Food

[Grand Banquet of the Kalu'ak](https://www.wowhead.com/item=197794/grand-banquet-of-the-kaluak), or [Deviously Deviled Eggs](https://www.wowhead.com/item=204072/deviously-deviled-eggs) giving the same buff with a cheaper individual price.
You can also use secondary food such as [Feisty Fish Sticks](https://www.wowhead.com/item=197782/feisty-fish-sticks) or [Sizzling Seafood Medley](https://www.wowhead.com/item=197784/sizzling-seafood-medley) or [Thousandbone Tongueslicer](https://www.wowhead.com/item=197786/thousandbone-tongueslicer) for a small dps gain. Sim your character to see what is best for you.

## Phials

- [Iced Phial of Corrupting Rage](https://www.wowhead.com/item=191329/iced-phial-of-corrupting-rage): Default phial unless the fight has too high damage intake or you are at risk of dying.
- [Phial of Tepid Versatility](https://www.wowhead.com/item=191341/phial-of-tepid-versatility): Recommended phial if the fight has high damage intake or you are at risk of dying.

## Runes

I apoogize for being annoying but, sim your character for the most accurate answer. Generally ~Convoke! builds do not want to play [Howling Rune](https://www.wowhead.com/item=194819/howling-rune) in single target if that is any consolation-but even that's not a guarantee. Make sure you select Rune (stat) (Main Hand) else it may not sim properly. ie: Buzzing (Crit) (Main Hand). Crit is the default setting.

# Gearing:
 
## Stat Priority:

Sim yourself using [Raidbots Top Gear](https://www.raidbots.com/simbot/topgear). Do not follow any stat priorities.

## Enchants

Weapon - [Wafting Devotion](https://www.wowhead.com/item=200058/enchant-weapon-wafting-devotion)
Chest - [Waking Stats](https://www.wowhead.com/item=200030/enchant-chest-waking-stats?crafting-quality=6)
Cloak - [Graceful Avoidance](https://www.wowhead.com/item=200031/enchant-cloak-graceful-avoidance) or [Homebound Speed](https://www.wowhead.com/item=199948/enchant-cloak-homebound-speed) 
Belt - [Shadowed Belt Clasp](https://www.wowhead.com/item=205039/shadowed-belt-clasp)
Legs - [Fierce Armor Kit](https://www.wowhead.com/item=193565/fierce-armor-kit) or [Lambent Armor Kit](https://www.wowhead.com/item=204702/lambent-armor-kit)
Wrist - [Devotion of Avoidance](https://www.wowhead.com/item=200021/enchant-bracer-devotion-of-avoidance?crafting-quality=6) or [Devotion of Speed](https://www.wowhead.com/item=199939/enchant-bracer-devotion-of-speed)
Boots - [Watchers Loam](https://www.wowhead.com/item=199936/enchant-boots-watchers-loam) or [Plainsrunner's Breeze](https://www.wowhead.com/ptr-2/item=199934/enchant-boots-plainsrunners-breeze)
Ring -  You should always sim your own character to determine what enchant to use in this slot. Depending on your gear, any of the four secondaries can be best for you.

## S4 Dinar/Bullion:

In Season 4 you can exchange [Antique Bronze Bullion](https://www.wowhead.com/ptr-2/item=213089/antique-bronze-bullion) for any piece of raid loot. Below includes a rough priority list for both Raid and M+, however make sure to customise to your own needs, for example if you loot any of these items, or if you want to go for a more hybrid-mix between Raid and M+. Video on Dinar and trinkets [here](https://www.youtube.com/watch?v=lcnwAexuJG8)

**Raid Priority**

- [Manic Grieftorch](https://www.wowhead.com/item=194308/manic-grieftorch?bonus=4795&class=11&ilvl=528&spec=103) This should be the highest value trinket in raid, especially early on when clearing due to deaths in your raid resetting the trinket. Send on CD but don't use while Smoldering Frenzy is up. Use Ashes first on pull when running both.
- [Djaarun](https://www.wowhead.com/item=202569/djaruun-pillar-of-the-elder-flame?bonus=4795&class=11&ilvl=528&spec=103) BIS Weapon. Macro to Berserk, and use on CD (it's off the GCD so just press Berserk again).
- [Ashes of the Embersoul](https://www.wowhead.com/item=207167/ashes-of-the-embersoul?bonus=6652:7981:9576:1520:8767&ilvl=528&spec=103) BIS trinket for Convoke.
- [Seal of Filial Duty](https://www.wowhead.com/item=195526/seal-of-filial-duty?bonus=4795:1808&ilvl=535&spec=103) Higher item level than other rings and provides a very powerful absorb for you that procs from Fire damage like our tier set.
- [Seal of Diurna's Chosen](https://www.wowhead.com/item=195480/seal-of-diurnas-chosen?bonus=4795:1808&ilvl=528&spec=103) Another free proc from our tierset.
- [Neltharion's Call to Sufffering](https://www.wowhead.com/item=204211/neltharions-call-to-suffering?bonus=4795&ilvl=535&spec=103) The most reliable stat stick, big RNG swings though but can always be favourable. 
- [Voice of the Silent Star](https://www.wowhead.com/item=204465/voice-of-the-silent-star?bonus=4795&class=11&ilvl=535&spec=103) Sark Cloak should be low priority for when you have the raids on farm, as it reduces your health (do not use in M+ either!).

**M+**
- [Djaarun](https://www.wowhead.com/item=202569/djaruun-pillar-of-the-elder-flame?bonus=4795&class=11&ilvl=528&spec=103) BIS Weapon. Macro to Berserk, and use on CD (it's off the GCD so just press Berserk again).
- [Neltharion's Call to Sufffering](https://www.wowhead.com/item=204211/neltharions-call-to-suffering?bonus=4795&ilvl=535&spec=103) The most reliable stat stick, big RNG swings though but can always be favourable. Great for AOE or if you don't want to run Grieftorch.
- [Seal of Filial Duty](https://www.wowhead.com/item=195526/seal-of-filial-duty?bonus=4795:1808&ilvl=535&spec=103) Higher item level than other rings and provides a very powerful absorb for you that procs from Fire damage like our tier set.
- [Seal of Diurna's Chosen](https://www.wowhead.com/item=195480/seal-of-diurnas-chosen?bonus=4795:1808&ilvl=528&spec=103) Another free proc from our tierset.
- [Ashes of the Embersoul](https://www.wowhead.com/item=207167/ashes-of-the-embersoul?bonus=6652:7981:9576:1520:8767&ilvl=528&spec=103) (assuming you are running Convoke).
- [Whispering Incarnate Icon](https://www.wowhead.com/item=194301/whispering-incarnate-icon?bonus=4795&class=11&ilvl=528&spec=103) Equal to Neltharion's, but requires a tank and healer in your raid to also equip.
- [Manic Grieftorch](https://www.wowhead.com/item=194308/manic-grieftorch?bonus=4795&class=11&ilvl=528&spec=103) Great priority/single-target damage, S-tier if group has lots of deaths. Don't use while Smoldering Frenzy is up. Use Ashes first with CDs when running both.
- [Fyrakk's Tainted Rageheart](https://www.wowhead.com/item=207174/fyrakks-tainted-rageheart?bonus=4795&class=11&ilvl=535&spec=103) Defensive option for high-keys, small sim lose but less in reality as it lets your healer do more DPS and minimises your time sitting in Bear etc.

## Embellishments

**Updated for Season 4**

For M+: you should always use 2x [Blue Silken Lining](https://www.wowhead.com/ptr-2/item=193946/blue-silken-lining) (BSL) on either Wrist, Neck, or Back.

For Raid: you should also craft 2x [Blue Silken Lining](https://www.wowhead.com/ptr-2/item=193946/blue-silken-lining), but prioritise Wrist or Neck so you still have the option for [Sark Cloak](https://www.wowhead.com/item=204465/voice-of-the-silent-star?bonus=4795&class=11&ilvl=535&spec=103) later on.

If your uptime is poor on certain fights (e.g. Council of Dreams or Fyrakk), [Shadowflame-Tempered Armor Patch](https://www.wowhead.com/ptr-2/item=204710/shadowflame-tempered-armor-patch) is the alternative raid embellishment that you can craft on Wrist or Back.

Never use any embellishment besides these two in Season 4 and do NOT craft on rings, as we have access to [Seal of Filial Duty](https://www.wowhead.com/item=195526/seal-of-filial-duty?bonus=4795:1808&ilvl=535&spec=103) and [Seal of Diurna's Chosen](https://www.wowhead.com/item=195480/seal-of-diurnas-chosen?bonus=4795:1808&ilvl=528&spec=103)

See: BSL analysis for Feral: https://youtu.be/JLnEaOndrsw?t=135

**Simming BSL**

This can be tricky, as sims simply offer a flat uptime, where in reality it's uptime during CDs that matters more than overall uptime. There is no perfect solution to this conundrum.

For M+ you might want to do anywhere from 65-75% (a lot of trash pulls it can hover around 60-80%, while for some bosses it can sit as high as 90%~). Even 65-75% may still be underselling BSL if you can ensure higher uptime during CDs etc, but ultimately you should check details or your logs to find an uptime that is most useful to you and the keys you are doing.

For raid, 40-60%, depending on boss. You might have 40% overall uptime on a fight, but that doesn't show the full picture if you had 80% uptime during CDs - therefore I would recommend adding to whatever overall uptime you are getting for simming purposes. A 45% uptime fight I might choose to sim at 55% for example.

**Crafting order**

The most optimal 'long-term' slots to craft [Blue Silken Lining](https://www.wowhead.com/ptr-2/item=193946/blue-silken-lining) on are: Neck, Bracers, or Back. This is because crafted gear is 3 item levels below that of a fully upgraded Mythic track piece, and these slots have fewer stats compared to other options.  

1. Craft Neck or Bracers with [Blue Silken Lining](https://www.wowhead.com/ptr-2/item=193946/blue-silken-lining).
2. Craft whatever slot you didn't craft on next, or alternatively can craft on Back if your focus is M+.

## Trinkets

There are a LOT of trinkets in season 4, below includes only the very best. Please use Top Gear or Droptimizer on [Raidbots](https://raidbots.com) in order to decide what trinkets to use/farm, but the following list should give you a good idea of some of the trinkets you will want to look out for. The list is in roughly power-level order assuming the highest item level versions of the trinkets. 
### To use in Raid

- [Manic Grieftorch](https://www.wowhead.com/item=194308/manic-grieftorch?bonus=4795&class=11&ilvl=528&spec=103) This should be the highest value trinket in raid, especially early on when clearing due to deaths in your raid resetting the trinket.
- [Ashes of the Embersoul](https://www.wowhead.com/item=207167/ashes-of-the-embersoul?bonus=6652:7981:9576:1520:8767&ilvl=528&spec=103) BIS (assuming you are running Convoke) but Grieftorch is a better first-pick.
- [Cataclysmic Signet Brand](https://www.wowhead.com/item=207166/cataclysmic-signet-brand?bonus=4795&class=11&ilvl=528&spec=103) Very good on longer fights (5m+), but weak on short fights and punishing if you die.
- [Neltharion's Call to Sufffering](https://www.wowhead.com/item=204211/neltharions-call-to-suffering?bonus=4795&ilvl=535&spec=103) Stat-stick that just works, though a bit RNG. Great for AOE or if you don't want to run Grieftorch.
- [Whispering Incarnate Icon](https://www.wowhead.com/item=194301/whispering-incarnate-icon?bonus=4795&class=11&ilvl=528&spec=103) Equal to Neltharion's, but requires a tank and healer in your raid to also equip.

### To use in Dungeons

- [Neltharion's Call to Sufffering](https://www.wowhead.com/item=204211/neltharions-call-to-suffering?bonus=4795&ilvl=535&spec=103) Stat-stick that just works, though a bit RNG. 
- [Whispering Incarnate Icon](https://www.wowhead.com/item=194301/whispering-incarnate-icon?bonus=4795&class=11&ilvl=528&spec=103) Equal to Neltharion's, but requires a tank and healer in your group to also equip. Can run double stat stick for M+.
- [Ashes of the Embersoul](https://www.wowhead.com/item=207167/ashes-of-the-embersoul?bonus=6652:7981:9576:1520:8767&ilvl=528&spec=103) Extremely good with Convoke builds and highest value in terms of burst.
- [Fyrakk's Tainted Rageheart](https://www.wowhead.com/item=207174/fyrakks-tainted-rageheart?bonus=4795&class=11&ilvl=535&spec=103) Defensive option for high-keys, lose thereotical damage but lets your healer do more DPS and minimises your time sitting in Bear etc.
- [Storm-Eater's Boon](https://www.wowhead.com/item=194302/storm-eaters-boon?bonus=4795&class=11&ilvl=528&spec=103) This is very niche and may only be playable in a few keys, if at all, but does big damage if you can pull it off (keeps you stationary for its duration, meaning you can't avoid any swirlies or mobs being moved away). You can always Bearform and/or Survival Instincts with this if needed too.
- [Manic Grieftorch](https://www.wowhead.com/item=194308/manic-grieftorch?bonus=4795&class=11&ilvl=528&spec=103) Good for priority burst damage which will be valuable for many bosses and trash packs. If your group has lots of deaths, has the potential be giga-bis.

# Miscellaneous:

## What is snapshotting?

Snapshotting refers to the process of continually ensuring that your strongest bleeds are ticking on your targets. The strength of feral bleed ticks is snapshotted (calculated) at the moment of application and lasts for the duration of the bleed. If certain buffs are active when the bleed is applied, such as !Tiger’s Fury!, the damage of its snapshot will be stronger. A good feral player is aware of this and will weave between applying stronger bleeds and leaving currently ticking bleeds alone. 

Tracking the strength of different bleeds across multiple/changing mobs is notoriously difficult, so we recommend the use of Weak Aura bleed packages such as those found in dreamgrove.gg. All our WA packages follow the same general format:
* If the bleed’s icon is highlighted in green or its number is higher than 100: this is a stronger bleed than the one you currently have active
* If the bleed’s icon is highlighted in grey or its number is equal to 100: equal value bleed
* If the bleed’s icon is highlighted in red or its number is lower than 100: this is a weaker bleed than the one you currently have active

Note: You will not necessarily upgrade every snapshot. Please review the rotation section.

__Which bleeds are snapshotted?__

* _All_ feral bleeds will snapshot at higher values when paired with:
    * !Tiger’s Fury!
* !Rake!’s snapshot can also be buffed by: 
    * !Prowl!
    * !Shadowmeld!
    * !390772/Pouncing Strikes! procs
* Rip’s snapshot can also be buffed by:
    * !Bloodtalons!
* Thrash’s snapshot can also be buffed by:
    * !236068/Moment of Clarity!
* Shred’s snapshot can also be buffed by:
    * !390772/Pouncing Strikes! procs (usually, though, !390772/Pouncing Strikes! is used on !Rake!)

A bleed will ideally be applied only when 30% or less of the prior bleed remains. This triggers a mechanic known as “pandemic,” which is common to most damage over time spells.  

## What is “pandemic range?”
This term refers to a DoT mechanic in WoW. The baseline duration of a DoT can be extended by up to 30% if a target is already affected by that DoT. Due to the 30% cap on extension, the DoT ought not to be refreshed early, or potential ticks will be lost. The ideal window of time to refresh a DoT is known as its “pandemic range.” 

Let’s use an example. Consider a 10 second DoT:
* Refresh with 1s remaining: the new DoT will be 11s long (10s baseline duration + 1s from prior DoT)
* Refresh with 3s remaining: the new DoT will be 13s long (10s baseline duration + 3s from prior DoT)
* Refresh with 8s remaining: the new DoT will still be 13s long (10s baseline + up to 30% from prior DoT)

It is therefore best to wait until 70% or more of your bleed has ticked to refresh its DoT. 

Fun trivia: the name “pandemic” derives from an old warlock passive that was eventually integrated as a baseline feature of damage over time spells. 

__What is “clipping?”__

Clipping refers to refreshing a dot prior to its pandemic window.
_Important note:_ Rake is the only bleed that ought to be clipped early to maintain stronger snapshots.



## Macros

Here, we provide a list of macros. These macros are not _required_, but using them may elevate your gameplay. (_Note:_ These macros are not set in stone. Customize them as you see fit!)


**Tie Lunar Inspiration !Moonfire! and !391528|Convoke! to one keybind:**

```
#showtooltip
/cast [known: Lunar Inspiration] Moonfire; [known: Convoke the Spirits] Convoke the Spirits
```
This macro helps save a keybind, as there are no talent builds that play both Lunar Inspiration and Convoke at the same time.

**Cast Ursol's Vortex at your cursor location (@cursor macro):**

```
#showtooltip
/cast [@cursor] Ursol's Vortex
```

**Use your trinket(s) and/or weapon at the same time as an ability:**

Some trinkets and weapons ought to be procced at the same time as a major cooldown. It is best to macro these items with Berserk. 
* 13 is the top trinket slot
* 14 is the bottom trinket slot
* 16 is your weapon slot

If you would like to use all three items with Berserk, use this macro:

```
#showtooltip
/use 13
/use 14
/use 16
/cast Berserk
```
This macro may be modified. For example, the macro below only uses the 2nd trinket with Berserk:

```
#showtooltip
/use 14
/cast Berserk
```

**Cast Entangling Roots on mouseover:**

This macro casts Entangling Roots on your mouseover target. If you do not have a mouseover target, the macro instead casts Entangling Roots on your current target.
```
#showtooltip
/cast [@mouseover, harm, nodead] [] Entangling Roots
```

**Skull Bash your Focus:**

This macro casts Skull Bash on your focus target. If you have not set a focus target, the macro instead casts Skull Bash on your current target.

We recommend creating a keybind that will assign a target as your focus with one click. This option can be found in the game's keybind settings. 
```
#showtooltip
/cast [@focus, harm, nodead] [] skull bash
```

**Cast Adaptive Swarm on friendly or enemy mouseover:**

This macro casts Adaptive Swarm on your current mouseover target. If you do not have a mouseover target, the macro instead casts Adaptive Swarm on your Casts Swarm on your current target. Your mouseover target may be a friendly.

Many abilities that are cast on allies - Rejuvenation, Regrowth, Innervate, etc - may be macro'd in this fashion. To make those macros, replace "Adaptive Swarm" with your spell of choice.
```
#showtooltip
/cast [@mouseover, help, nodead] [] Adaptive Swarm 
```

**Cast Rebirth on an ally:**

This macro casts Rebirth on your current friendly mouseover target. If your ally is alive, the macro instead casts Mark of the Wild.
```
#showtooltip
/cast [@mouseover, help, dead] Rebirth; Mark of the Wild
```
 

## Useful WeakAura(s)

### **Feral Weakaura Packs**
The following links lead to various feral druid weakaura packs. These contain everything that's recommended to track to play at a high level. None of these are particular better or more useful than others, and which one you should use is up to your personal preference.
 
- [by Drufearr](https://wago.io/us2RURgE6) 
- [by Chips](https://wago.io/WkTBZuH3y) 
- [by Fore](https://wago.io/H1tFNCh-t) 
- [by Cheesey](https://wago.io/18VspFroU)  
- [variant by Cheesey](https://wago.io/H3yjY1gs1)  
- [by Guiltyas](https://wago.io/OaJQX6khW)
- [by Oi/Dsune](https://wago.io/OiFeral)
- [by enthh](https://wago.io/bfgPasy27) requires his [addon](https://www.curseforge.com/wow/addons/feralsnapshots)

### **Commonly used WeakAuras and Addons**
[Feral Bleed Power by Oi](https://wago.io/qYnbZzlmP)
See the description of the WA for more details. This is not a required WA but will make it easier to track the power of your next bleed compared to the currently active one.

[Feral Snapshots by Enth](https://www.curseforge.com/wow/addons/feralsnapshots)
An addon alternative. See the description for more details. This can also show snapshot details on your enemy nameplates (default and plater) or personal resource display.

[Rake Plater mods by Sretnuh](https://wago.io/p/Sretnuh)
Search through these to see what you like, these Plater mods help identify which targets have your rake on them at a glance.

[Apex Predator's Craving by Marvel](https://wago.io/KzSX7dDMM)
Alerts you when you have an !Apex Predator's Craving! (free bite) proc with a glowing icon and a sound.

[Adaptive Swarm Helper by KnewOne](https://wago.io/0P93t1-nG)
See the description of the WA for more details. This will assist you with using Adaptive Swarm, including Unbridled Swarm support for ally targeting.

[Bloodtalons Tracker from Fore's pack](https://wago.io/cQkL9nrAw)
This tracks your progress towards procing !Bloodtalons!, showing the 4 second timer for each spell you cast towards it.

[Bloodtalons Tracker from Cheesey's pack](https://wago.io/zinn-QaFI)
Additional BT tracker.

[Focus Skull Bash](https://wago.io/mOvsNkzJ7)
Helps emphasise focus kicks when your Skull Bash is off CD.