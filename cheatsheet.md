# Heroless: Character Health, Equipment, Actions, and Traits (Cheat) Sheet

## Origin Trait and Skills are just Bonuses

Your characters origin traits and skills are only a representation of what your character is especially good at. In no way do they limit the actions character can attempt.

Your character can use any weapon or armor without requiring the related skills. They can attempt to cast any magic desired without being skilled in it. Your character can attempt anything! Your character's origin trait and skills only increase the likelihood of their success.

## Equipment and Inventory

The inventory system is split into two systems, Inventory Slots and Packspace.

### Inventory Slots
Inventory slots hold your armor, weapons, and treasure/loot. Slots can also be used to hold any other item you want to be 100% sure you have access to in an emergency.

### Packspace
Packspace is like a grab bag of all your "regular, everyday" adventuring equipment. This could be health kits, rope, climbing gear, rations, repair kits, etc. Your pack is assumed to potentially contain most common materials that you may need. When an item is needed, you'll make a Packspace check to retrieve it. The more items you retrieve, the emptier your pack becomes. This reduces the likelihood of you having the next item you need. Depending on the situation, you may check you pack multiple times to find an item.

## Health and Wounds

Each character has a number of Wound Slots, typically five. These slots represent the number of distinct wounds your character can sustain before death. If you character receives a wound that cannot be allocated to a Wound Slot, your character dies.

### Wound Severity
Every wound your character receives has a severity level (1-6). These represent a small cut or bruise, all the way up to a severed limb or worse. Upon receiving an wound, the GM will inform you of its severity and you record it within an available Wound Slot. Most wounds will require a free Wound Slot to record. However minor wounds of severity 1 & 2 can be compounded if wished. For example if you have a Wound Slot already holding a severity 2 wound and receive another wound of severity 1 or 2, you may increase your existing severity 2 wound to a severity 3 or 4, accordingly. Once a Wound Slot is at severity 3 or higher, it can no longer be compounded.

### Complications
Wound Slots of severity 5 and 6 may cause further complications, including additional wounds if not Stabilized immediately

### Recovery
Wound Slots can be recovered via healing. The higher a severity level of a wound slot the more complicated and longer the healing process will be. This increased complexity may be a reason to not always compound minor wounds as mentioned above. Most wounds cannot be healed within a playing session and reducing them via active defense is critical.

## Basic Combat
Combat uses a system of Action Points (AP) and Actions.

### Turns don't matter (kind of)
While turns do exist within combat, their primary function is to indicate when your AP will be refreshed. Your AP is refreshed at the beginning of your turn, any unused AP are lost. You do not need to wait for your turn to act, instead you may act at any time, as long as you have AP available. This gives you the ability to react to an attack against you or an ally, or to act together with an ally for a better chance at success.

### Actions
There are a number of actions you can take on a turn each with their own requirements and AP cost. Following is a subset of actions commonly used during combat.

#### Attack
*1 AP | Requires Weapon Equipped*

- Roll **2d6**.  
- Add your **weapon skill bonus** and the weapon’s **Roll Modifier**.  
- Compare the final result to the **Attack Resolution Table**.  
- If the result indicates a wound:
	- Apply **armor wound reduction** (if any).
	- Apply the final wound level to the target.
	- Armor loses **1 durability** if it reduced the wound by any amount.

##### Armor Types and Modifiers

|Type|Base Durability|AP Penalty|Wound Reduction|Movement Penalty|
|---|---|---|---|---|
|Light|4|-1|-1|n/a|
|Heavy|8|–1|-2|all movement distances halved|

##### Weapon Types and Modifiers

|Type|Roll Modifier|
|---|---|
|Slashing|+1 against Unarmored|
|Piercing|+1 against Light Armor; -1 against Heavy Armor|
|Blunt|+1 against Heavy Armor; -1 against Light Armor|

##### Attack Resolution Table

| Roll Total | Result           | Wound Severity |
|------------|------------------|-------------|
| ≤ 5        | Miss             | —           |
| 6–7        | Glancing Blow    | Severity 1     |
| 8–9        | Weak Hit         | Severity 2     |
| 10–11      | Solid Hit        | Severity 3     |
| 12–13      | Strong Hit       | Severity 4     |
| 14–15      | Devastating Hit  | Severity 5     |
| 16+        | Critical Hit     | Severity 6     |

> The Basic Attack is the most common offensive action, representing a standard strike with any weapon.  
> Advanced techniques or weapon effects may alter this action or its outcome.

## Sundering Strike
*2 AP | Requires Blunt or Slashing Weapon*

You target the armor, not the body—hammering, prying, or tearing with the intent to compromise protection. Whether by raw force or precise leverage, your goal is to leave your opponent exposed and vulnerable, even if they walk away unharmed—this time.

- Attack as normal.  
- On a hit:  
	- **Blunt weapon:** Armor loses durability = wound level  
	- **Slashing weapon:** Armor loses durability = ½ wound level (round up)  
- Target suffers **no wounds** from this attack.  
- Has no effect on unarmored targets (treat as regular attack).

## Brace
*1 AP | Requires Heavy Armor Equipped*

You hold your ground, shifting your stance and tightening behind your armor to absorb the force of an incoming blow. It’s not about speed—it’s about resolve. You may not avoid the hit, but you’re prepared to take it head-on.

[Heavy Armor](04_skills.md#Heavy%20Armor)
- Declare before an incoming attack roll.  
- If the attack hits and would cause a wound:  
	- Reduce wound severity by **1 + Heavy Armor skill level**.  
- **Does not prevent armor durability loss**.  
- Must be **stationary** to use this action.

## Deflect
*1 AP | Requires Armor Equipped*

Instead of absorbing the full brunt of the attack, you shift your posture to let the blow glance off your armor. It’s a practiced maneuver—not one of brute resistance, but of angles and timing—meant to preserve the gear that might save your life in the next exchange.

[Heavy Armor](04_skills.md#Heavy%20Armor), [Light Armor](04_skills.md#Light%20Armor)
- Declare before an incoming attack roll.  
- If the attack hits and would cause your armor to lose durability, compare the attacker’s roll to your **Deflect DC**:
	- **Deflect DC = 8 + your armor skill modifier** (Light or Heavy Armor)
	- If the attacker’s roll is **less than the DC**, your armor takes **no durability damage**.
	- If the roll is **equal to or higher**, armor loses durability as normal.
	- This action does not prevent injury, only the durability loss incurred by the armor. Record your injury as usual.

## Evade
*1 AP*

With a quick read of your opponent’s movement, you attempt to slip aside at just the right moment. It’s not about blocking the strike—it’s about not being where the weapon lands. A risky gamble, but sometimes agility is your only shield.

[Agility](04_skills.md#Agility)
- Declare before an incoming attack roll.  
- The attacker’s roll is reduced by **1 + Agility skill level**.  
- If the modified result causes the attack to miss, no wound or armor damage occurs.

## Assist
*1 AP | Requires Proximity*

You lend your attention, effort, or expertise to support a nearby character's action. Assisting can mean helping lift a barrier, providing light, holding a tool, or offering verbal guidance.

- Declare your intent to assist before the primary character makes their roll.
- You must be within reach or have the means to meaningfully contribute.
- If the GM deems the help appropriate, the assisted character gains **+your relevant skill level**
- Only one Assist may apply to a given action.