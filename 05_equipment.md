[prev](04_skills.md) | [index](00_index.md) | [next](06_combat.md)
# Equipment
In the Heroless system, survival often hinges on the tools at hand. Equipment provides the foundation for a character’s effectiveness in combat and exploration, offering both protection and offensive capability. Unlike arbitrary item lists in some systems, each piece of gear in Heroless is governed by durability, quality, and traits that meaningfully affect gameplay. Armor mitigates harm rather than avoiding it, while weapons modify attack dynamics and can carry unique properties that influence tactics. This section details how equipment functions mechanically, how it degrades over time, and how quality impacts reliability and versatility.

## Armor
Armor in Heroless provides critical protection against the dangers of combat, absorbing the force of attacks and reducing the severity of injuries. Unlike in many systems, armor does not prevent hits—it reduces the consequences of being struck.

Armor wears down through use. Each piece has a durability value that decreases as it absorbs blows. Once an armor's durability reaches zero, it is broken and provides no further protection.

---

### Armor Types
There are two types of armor, each with its own tradeoffs between durability, agility, and protection:

|Type|Base Durability|AP Penalty|Wound Reduction|Movement Penalty|
|---|---|---|---|---|
|Light|4|-1|-1|n/a|
|Heavy|8|–1|-2|all movement distances halved|

- Durability is the number of damaging hits the armor can absorb before breaking.
- Armor loses 1 durability if it **reduces the severity of a wound** by any amount.
- AP Penalty is applied at the start of each round and reduces the wearer’s total Action Points for that round.
- While a character is wearing armor with durability remaining, all incoming wounds are modified by the Wound Reduction value.
- If armor is reduced to 0 durability, it no longer provides a Wound Reduction, all other penalties remain while equipped.
- Zero durability armor may be repaired, but loses one level of quality, armor will not drop below poor quality.

[Deflect](11_actions.md#Deflect) is the only way to prevent durability loss once an armor-reducing hit lands. It must be declared before the attack roll and costs 1 AP.

Armor durability values are based on Common quality. Apply quality multipliers to adjust actual durability.

See Crafting and Repairs for rules on restoring armor durability.

---
### Armor Quality
Armor quality determines how durable the armor is and how difficult it is to craft or repair.

|Quality Tier|Durability Multiplier|Notes|
|---|---|---|
|Masterwork|×2|Rare and highly durable. Often factional or legendary.|
|Fine|×1.5|Well-made and long-lasting. Favored by trained soldiers.|
|Common|×1.0|Standard issue gear. Readily available.|
|Poor|×0.5|Fragile or cobbled together. Breaks easily.|

Example: A Fine Heavy Armor has 8 × 1.5 = 12 durability.  
A Poor Light Armor has 4 × 0.5 = 2 durability.

## Weapons
Weapons in Heroless shape not just how a character deals harm, but how they approach combat altogether. Each weapon type comes with distinct strengths and weaknesses, expressed through a standardized set of modifiers that interact directly with the combat resolution system and associated actions.

Rather than dealing static damage, weapons modify how attacks hit and how badly they wound. This design creates a tactical triangle of weapon choices where no type is objectively best—only best for the situation.

---
### Weapon Types
Each weapon belongs to one of three core types. These types determine how the weapon modifies an attack roll:

|Type|Roll Modifier|
|---|---|
|Slashing|+1 against Unarmored|
|Piercing|+1 against Light Armor; -1 against Heavy Armor|
|Blunt|+1 against Heavy Armor; -1 against Light Armor|

- Roll Modifier is added to the final result of the attack roll.
- Wound Modifier adjusts the wound level if a wound is inflicted.

See Combat Resolution Table in Basic Attack for roll results and wound severity.

---
### Using Weapons in Combat
When making a Basic Attack, the weapon’s type affects the outcome as follows:

1. Roll 2d6
2. Add your Weapon Skill Bonus
3. Add your Weapon’s Roll Modifier
4. Consult the Combat Resolution Table

If a wound is inflicted:
- Apply the weapon’s Wound Modifier to adjust the wound level.

Armor reduces incoming wounds, but does not make the target invulnerable.

---
### Ammunition and Ranged Weapons
Weapons which are Ranged or Thrown may require ammunition or recovery.
- Ranged weapons consume ammo in abstract batches. When depleted, the GM may call for a Pack Space check to determine availability.
- Thrown weapons must be recovered after use or replaced.
- Ammunition may be stored in Pack Space or in an Item Slot for quicker access. 

---
### Weapon Quality and Trait Capacity
Each weapon has a Quality Tier, which affects how many traits it may possess and how difficult it is to craft or repair.

|Quality Tier|Max Traits|Notes|
|---|---|---|
|Masterwork|3|Rare, elite craftsmanship. Traits may not be replaceable once lost.|
|Fine|2|Durable, reliable, well-balanced. Often used by professionals.|
|Common|1|Basic weaponry suited to most fighters. Easily repaired or replaced.|
|Poor|0|Makeshift or heavily worn. Cannot support traits. Breaks easily.|

The Craft/Repair Cost Multiplier adjusts material and time costs when using the Crafting skill.  
See Crafting and Repairs for rules on restoring or improving weapon quality.

---
#### Weapon Degradation
It is possible for a weapon to break or become damaged (quality loss) through narrative events or specific actions against them. If a weapon drops in quality and can no longer sustain its current number of traits, the player may choose which trait(s) are lost.

---
### Weapon Traits
Traits provide weapons with special properties or allow them to be used with specific combat actions.

|Trait|Effect|
|---|---|
|Balanced| +1 to hit when thrown.|
|Two-Handed| +1 wound severity on hit. Requires both hands, cannot be used with a shield.|
|Reach|Can target enemies one space beyond standard melee range.|
|Quickdraw|Can be swapped in or out of an Item Slot once per round without AP.|

## Repairs and Crafting
In Heroless, repairing and crafting gear are critical to long-term survival. Both processes rely on the Crafting skill, proper tools, and time—but the outcome depends on your choices, not a fixed schedule.

### Repair & Crafting Costs
|Quality Tier|Base DC|Crafting Cost|Crafting Successes|Notes|
|---|---|---|---|---|
|Poor|5|2–5 gp|1-2|Easily fixed or assembled|
|Common|8|5–20 gp|2-5|Standard adventuring gear|
|Fine|10|20–40 gp|5-10|Requires precision and skill|
|Masterwork|13|60+ gp (GM approval)|10+|Complex, may require rare materials|

---
### Repairs
Damaged armor can be repaired outside of combat. Repairing armor restores lost durability, extending the life of your equipment and saving valuable resources.

#### Requirements
- Repair Kit

#### Repair Roll
To repair an item:
1. Choose how many points of durability you wish to restore
2. Roll 2d6 + relevant Crafting skill
3. Compare the result to the DC:

- DC = Base DC + durability points

On Success:
- Restore the chosen number of durability points

On Failure:
- The Repair Kit is consumed
- No durability is restored
- The GM may impose additional consequences after repeated failures

---
#### Fatigue from Repeated Repairs
- The first repair attempt per day causes no Exhaustion.
- Each additional repair attempt after the first causes 1 level of Exhaustion.

This reflects the physical toll of working long hours under pressure.

---
#### Example Repair Sequence:
- Laura, with Crafting +2, attempts to repair a Fine Chainmail (Base DC 9)
- She attempts to restore 2 durability → Final DC = 9 + 2 = 11
- Rolls 2d6 + 2 = 12 → Success!
- Later that day, she attempts a second repair on her armor (Fine, 3 durability)
- DC = 12; Exhaustion increased by +1 regardless of outcome
- Failing, she weighs whether to risk a third attempt, knowing she’ll gain another +1 Exhaustion…

---
### Crafting
Creating new weapons and armor requires materials, tools, and focused effort. Crafting is treated as a special downtime activity—only one crafting attempt may be made per Downtime Unit (DU).

#### Requirements
- Crafting skill (optional, but highly recommended)
- Workbench, field station, or forge (depending on item)
- Funds (for cost of materials and/or equipment)
- One crafting attempt per DU
- GM approval for rare or advanced gear

#### Craft Roll
To craft an item:
1. Declare the item’s quality tier.
2. Spend the required gold for materials.
3. Roll 2d6 + Crafting vs the item’s Base DC (see Repair & Crafting Costs table) once per DU.
4. Track the number of **successful rolls**. Continue crafting until the total number of **successful craft attempts** meets the item’s _Crafting Successes_ requirement.

- **Failures** do not reset progress—they consume materials and time, but you retain any previously accumulated successes.
- Once the required number of successful attempts is met, the item is completed at the end of that DU.

On Success:
- Add 1 to your total number of successful attempts toward completing the item.

On Failure:
- The DU is spent.
- No progress is made during that DU.
- At GM discretion, repeated failures may lead to narrative complications or increased material cost.

---
#### GM Controls and Limitations
The GM may require:
- Advanced environments for Fine or Masterwork gear
- Rare materials, faction access, or blueprints
- A minimum Crafting skill level
- Delays due to weather, travel, or outside pressure