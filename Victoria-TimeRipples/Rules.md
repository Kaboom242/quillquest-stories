# WARPS — Rules (cleaned, LLM-friendly)

> Purpose: concise, structured rules for the WARPS RPG; written to be easy to index by an LLM knowledge base.

## Quick reference
- Dice: D6. A roll of 5 or 6 = 1 Success.
- Checks: Roll N d6 (N = Dice from Stat + Mods). Count Successes (5–6).
- Success thresholds: GM assigns required Successes for tasks.
- Combat rounds: simultaneous Spotlights; each round ≈ 2–5 seconds.

---

## Resolution: Checks & Successes
- Check: roll a number of d6 and count successes (5–6). Example: rolls [2,5,6] = 2 Successes.
- Roll = total dice rolled (stat value + mods).
- Auto Successes: add fixed successes with +XS (e.g., +1S).
- Result = successes from roll + auto successes.
- Higher total successes = better outcome.

Check types
- Action Check: tied to a specific Action.
- Stat Check: roll dice equal to a single Stat.
- Challenge Check: a larger task, often multi-stat or multi-round.
- Resist Check: reduces incoming effects; each Success reduces effect by 1 point.

Modifiers
- Add dice with +XD (e.g., +2D). Apply once per check unless stated.
- Add auto-successes with +XS.

Example: Str 3 (+1D from tool) = roll 4d6. Rolls 5,2,3,6 → 2 successes.

---

## Stats (core characteristics)
Primary stats (use short tags):
- STR — Strength (physical power)
- FORT — Fortitude (toughness, pain resistance)
- ENDR — Endurance (stamina, fitness)
- AGL — Agility (speed, mobility)
- DEX — Dexterity (coordination, fine control)
- SENSE — Sense (perception, awareness)
- CHA — Charisma (social influence)
- INT — Intellect (reasoning, knowledge)
- SPIRIT — Spirit/Will (resolve)

Raising stats: via Training/Abilities. Culture caps apply; post-creation bonuses possible (+3 over culture max).

---

## Combat: structure & spotlighting
- Round: used when seconds matter. GM breaks combat into Spotlights: groups of characters whose actions interact.
- During a Spotlight players declare Actions; GM resolves them roughly simultaneously.
- Movement grid: spaces are ~5 ft × 5 ft (or hex). Use distance units for ranges (see "Pace & Ranges").
- Line-of-sight: attacks pass through intervening spaces; first obstacle hit typically stops the attack.

Area shapes (templates)
- Circle X: affects all spaces within X spaces.
- Semi-circle X: half-circle area from effect.
- Cone X (45°): affects spaces within cone.
- Blast: area effect; hits everything in the area.
- Thrown: travels in arc; can pass over obstacles.

Diagonals: measure shortest path between two points.

---

## Actions (overview)
Each Round a character may attempt one Action (combat) or perform Long-Term Actions outside combat.

Action types (combat)
- Use Action: generic action if cost paid.
- Active Action: mobile while doing it; can move Pace and still block/dodge. (Cannot move after attempting some Active Actions depending on ability.)
- Full Action: requires full focus; no movement beyond 1 space; cannot take Defend Action.
- Defense Action (reaction): Dodge, Block, or Cover.
  - Dodge: reduces hits from Strikes and Projectiles (not Blasts).
  - Block: reduces Strike damage (if reduced to 0, damage applies to blocking item/limb).
  - Cover: reduces projectile and blast damage using terrain or object.
- Free Action: can be performed anytime (usually once per round unless stated).
- Grapple Action: restricted to grappling state.

Long-term actions
- Downtime Action: performed once per day during rest (e.g., prayer, maintenance).
- Interim Action: 5–30 minutes; usually once per day.

Action modifiers
- Action Mods indicate situational dice/success changes. Apply once unless stated.

Movement states
- Prone, Swimming, Climbing: restrict available Actions to those listed for the state.
- Switching states may cost an Action or be a Free Action depending on context.

---

## Pace & Movement
- Pace: how many spaces a character can move while taking a Standard Action.
- Pace types: Ground, Surface (walk on surfaces), Swim, Fly, Float.
- Flying: may have minimum speed or fall if not met; can descend up to 10 spaces per round.
- Large creatures: occupying >1 space count turning as movement.

Movement detail
- Mobile limbs: required to move; damaged limbs reduce Pace.
- Remove action: a special action used to remove Constitution (Con) points; specify type (Free/Active/Full) and associated Check.

---

## Attacks, Hits & Damage
Resolution
1. Attacker makes a Hit Check (uses Strike or Projectile type).
2. Defender may attempt a Defense Action (Dodge/Block/Cover) to reduce the Hit value.
3. Remaining successes determine which Body Area(s) are hit.
4. Attacker rolls Damage (sometimes using successes as dice/thresholds) and applies to the Body Area's Damage Meter.

Body Areas
- Hitbox: torso, head, arms (main/off), legs, etc. Smaller hits (1S) may be randomly assigned unless attacker spends extra success to choose.

Damage meters
- Harm: short-term damage; often recoverable during short rests.
- Wound: long-term damage; requires extended healing.
- Critical: maximum threshold; severe effects when reached.

Damage types
- Physical: Bash (blunt), Slash (cutting), Pierce (penetrating)
- Energy: generic Energy, Fire, Ice, Elec, Light, Dark
- Some attacks list multiple types separated by '/': attacker chooses one for the attack.

Special notes
- Hands: necessary to hold/use items. If a hand is lost, character drops held items.
- Mobile (limb): used for movement. If lost, character cannot move their Pace normally.

Damage example
- Attacker hits with 2S to Torso, rolls Damage 4S → record 4 Harm in Torso meter.

---

## Resist & Recovery
- Resist Checks reduce incoming points (1 Success reduces 1 point of effect).
- After combat: characters may take a 10 minute Breather (remove temporary Stamina Loss, some Harm, Terror etc.)—only available if not immediately threatened.
- Resting: short/long rest rules remove Fatigue, restore Stamina, and heal Harm depending on bed quality.

Constitution, Stamina & Will
- Constitution tracks short-term penalties (Con points) such as Fatigue, Hunger, Dehydration, Drowsiness, Terror.
- Stamina: spent on special abilities; recovered after 10-minute break or rest.
- Will: gained only in combat; lost when combat ends; represents fighting determination.

Mental Effects
- Terror, Stress, Dread: each recorded in Con meter with tags (Tr, St, Dr).
- Mental Breakdown: remove mental effects but gain a Trauma card (or Insanity card if severe).
  - Trauma: long-term psychological problem (depression, nightmares).
  - Insanity: severe crisis that may end in catastrophic behavior.

---

## Items & Encumbrance
- Items are represented by Item Cards. Types: Weapons, Armor, Tools, Carriers, etc.
- Encumbrance E value: each item has E. Items occupy E slots in carriers.
- Capacity = STR + FORT + ENDR + Species Capacity Mod.
- 1/5 E rounding: small items <1E can be rounded down until 5 of them accumulate to 1E.
- Carriers (backpacks) provide E slots; carried items count against wearer’s total.

Item usage
- Held Items must be in hand to use; one held item per hand.
- Readied Items: drawn as a Free Action (usually items ≤1E or sidearm exceptions).
- Worn Items: protect specific body areas only when hit.
- Carried Items: retrieving is an Active Action unless otherwise noted.

Item damage
- Items have DR (Damage Resistance), Dmg (Damage Points) and Brk (Broken Points).
- Damage reduces Dmg, then Brk. When Brk depleted, item is Broken and treated as improvised.
- Full Block: if a block reduces Hit to 0, damage is applied to the blocking item/body area instead.

Keywords: Dmg Back (reflective damage), Threaten (contest), etc.

---

## Abilities, Training & Advancement
- Abilities come from Ability Cards (Classes, Talents, Doctrines). Training gains Ability Cards.
- Sequenced Abilities: must be learned in order (Runner 1 → Runner 2).
- Only one Ability Card may be used to provide a Bonus or Action in a single round (no stacking different Ability Cards for extra actions unless stated).
- Train Action grants AP (training points). Study abilities require a text; teachers may substitute for study materials.

Class tiers
- Basic Classes: foundation skills.
- Advanced Classes: require base levels (typically 3 base class levels).
- Master Classes: rare; require many prerequisites; characters usually can have only one Master Class.

Talents & Doctrines
- Talents: non-combat abilities (Athletics, Crafts, Arts, Wilderness, Organization, Intellectual).
- Doctrines: divine or cultic paths. Require initiation and grant Favor for aligned actions. Favor can be awarded/removed by GM.

Character level
- Level by number of Class Cards obtained: Basic (1–3), Advanced (4–7), Elite (8), Epic (9–12).
- Elite characters may convert XP into Stat increases (example: 20 XP → +1 Stat).

Legend Points (LP)
- 3 LP (Minor Fame): +1 Stat
- 6 LP (Renown): +1 Stat
- 9 LP (Legend): +1 Stat

---

## NPCs & Monsters
- NPC cards contain species, hitbox, stats, abilities, and tactics.
- Difficulty tiers: Normal, Hard, Dire, Epic, Godly (avoid).
- NPC Status Cards track damage, stamina, and other runtime data.

---

## Challenges & Contests
- A Challenge is a freeform Check; the GM picks appropriate Stats.
- Difficulty examples: Easy 1S, Hard 2S, Very Hard 3S; multi-round challenges can use cumulative successes (e.g., 2S easy, 4S hard).
- Multi-Stat: combine two stats (e.g., STR + FORT). Pure Stat +1D: single stat plus extra die.
- Contests: opposed checks; compare successes. Ties resolved by 50/50 or re-roll as GM prefers.

Common challenge templates (examples)
- Reposition (STR + AGL): change positions in space on success.
- Impede (STR + AGL): stop target moving/passing; target may attack you instead.
- Jump (STR + AGL): 1S per 5' forward. Off-by-1 = grab or partial success.
- Sneak (AGL + SENSE): stealth checks vs. Notice.
- Social (CHA + 1D): persuasion; more successes = better social outcome.

Stealth
- Alertness levels: Distracted, Relaxed, Searching. These modify Notice checks.
- Stealth penalties: armor, encumbrance, noisy actions.
- Sneak Attack: AGL +1D vs Target Sense +1D — win = target surprised; tie/lose = partial or failed surprise.

---

## Travel, Rest & Survival
Time use per day (examples)
- Adventure day: Adventure + Interim + Daily
- Travel day: Travel + Interim + Daily
- Rest day: Rest + Downtime + Interim + Daily

Travel
- World Space = ~10 miles. Travel 1 World Space uses Endr +1D resist check vs Travel Fatigue.
- Travel difficulty: 0 road, 1 trail, 2 wilderness/rough, 3 mountainous/jungle/swamp.
- Travel mods: weather, night, carrying loads, etc.

Rest & recovery
- Short breather (10 minutes): remove temporary Stamina Loss, some Harm/Terror if safe.
- Rest day in bed (inn): add +1D to healing; remove Fatigue or minor conditions.

Survival: daily needs
- Thirst: 1 drink prevents 1 Thirst point. Dirty water risks Illness (1D). Foul water (2D).
- Hunger: 1 food prevents 1 Hunger point; 1/3 food gives partial resist checks.
- Sleep: resist falling asleep with Spirit checks when deprived.
- Exposure: 0–3 scale (mild→extreme); Endr +1D to resist exposures.

Foraging & camp
- Forage: Endr + Sense checks; successes = food or rummage items.
- Campfire: provides cold protection (+1D) and allows cooking.

---

## Rules & GM guidance
- Rule Zero: GM finalizes rulings when rules are silent.
- Bonuses/Penalties: same-type bonuses generally don't stack; apply the greatest.
- Use clear naming for all stats and tags to make the knowledge base indexable (e.g., STR, FORT, ENDR, AGL, DEX, SENSE, CHA, INT, SPIRIT).

---

## Glossary (short)
- Check: d6 roll set to count successes (5–6).
- Success: each 5–6 on a d6.
- Roll: total dice pool rolled.
- Auto Success (+XS): fixed successes added.
- Bonus Dice (+XD): extra dice added to pool.
- Pace: movement allowance while taking a standard action.
- Con points: constitution penalties (fatigue, hunger, etc.).

---

## Example snippets (indexable)
- Dice example: STR 3 + tool +1D = roll 4d6 → results [1,5,6,3] → 2 successes.
- Hit example: attacker 3S hit vs defender dodge 1S → 2S to assign; choose Torso → roll damage => apply Harm.

---

Tags: rules, warps, mechanics, checks, combat, stats, abilities, items, npc, survival, travel

If you'd like, I can also:
- Produce a JSON/YAML export of this rule summary for an LLM knowledge base.
- Break this into separate files (combat.md, stats.md, items.md) for easier indexing.