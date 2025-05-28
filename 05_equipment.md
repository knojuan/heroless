[prev](04_skills.md) | [index](00_index.md) | [next](06_combat.md)
# Armor
Armor in Heroless provides critical protection against the dangers of combat, absorbing the force of attacks and reducing the severity of injuries. Unlike in many systems, armor does not prevent hits—it reduces the consequences of being struck.

Armor wears down through use. Each piece has a durability value that decreases as it absorbs blows. Once an armor's durability reaches zero, it is broken and provides no further protection.

---

## Armor Types
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

[Deflect](09_actions.md#Deflect) is the only way to prevent durability loss once an armor-reducing hit lands. It must be declared before the attack roll and costs 1 AP.

Armor durability values are based on Common quality. Apply quality multipliers to adjust actual durability.

See Crafting and Repairs for rules on restoring armor durability.

---
## Armor Quality
Armor quality determines how durable the armor is and how difficult it is to craft or repair.

|Quality Tier|Durability Multiplier|Notes|
|---|---|---|
|Masterwork|×2|Rare and highly durable. Often factional or legendary.|
|Fine|×1.5|Well-made and long-lasting. Favored by trained soldiers.|
|Common|×1.0|Standard issue gear. Readily available.|
|Poor|×0.5|Fragile or cobbled together. Breaks easily.|

Example: A Fine Heavy Armor has 8 × 1.5 = 12 durability.  
A Poor Light Armor has 4 × 0.5 = 2 durability.

# Weapons
Weapons in Heroless shape not just how a character deals harm, but how they approach combat altogether. Each weapon type comes with distinct strengths and weaknesses, expressed through a standardized set of modifiers that interact directly with the combat resolution system and associated actions.

Rather than dealing static damage, weapons modify how attacks hit and how badly they wound. This design creates a tactical triangle of weapon choices where no type is objectively best—only best for the situation.

---
## Weapon Types
Each weapon belongs to one of three core types. These types determine how the weapon modifies an attack roll:

|Type|Roll Mod.|Wound Mod.|
|---|---|---|
|Piercing|-2|+2|
|Slashing|0|0|
|Blunt|+2|-2|

- Roll Modifier is added to the final result of the attack roll.
- Wound Modifier adjusts the wound level if a wound is inflicted.

See Combat Resolution Table in Basic Attack for roll results and wound severity.

---
## Using Weapons in Combat
When making a Basic Attack, the weapon’s type affects the outcome as follows:

1. Roll 2d6
2. Add your Weapon Skill Bonus
3. Add your Weapon’s Roll Modifier
4. Consult the Combat Resolution Table

If a wound is inflicted:
- Apply the weapon’s Wound Modifier to adjust the wound level.

Armor reduces incoming wounds, but does not make the target invulnerable.

---
## Ammunition and Ranged Weapons
Weapons with the Ranged or Thrown trait require ammunition or recovery.
- Ranged weapons consume ammo in abstract batches. When depleted, the GM may call for a Pack Space check to determine availability.
- Thrown weapons must be recovered after use or replaced.
- Ammunition may be stored in Pack Space or in an Item Slot for quicker access. 

---
## Weapon Quality and Trait Capacity
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
### Weapon Degradation
It is possible for a weapon to break or become damaged (quality loss) through narrative events or specific actions against them. If a weapon drops in quality and can no longer sustain its current number of traits, the player may choose which trait(s) are lost.

---
## Weapon Traits
Traits provide weapons with special properties or allow them to be used with specific combat actions.

|Trait|Effect|
|---|---|
|Balanced| +1 to hit when thrown.|
|Two-Handed| +1 wound severity on hit. Requires both hands, cannot be used with a shield.|
|Reach|Can target enemies one space beyond standard melee range.|
|Quickdraw|Can be swapped in or out of an Item Slot once per round without AP.|