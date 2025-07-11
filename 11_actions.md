[prev](10_magic.md) | [index](00_index.md) | [next](12_inventory-management.md)
# Actions
Actions represent everything a character can actively attempt during a scene—whether in combat, exploration, or social encounters. Each action has an **AP cost**, and characters can take any number of actions per round as long as they have the Action Points (AP) to spend.

Actions are divided into categories such as **Defensive**, **Offensive**, and **Utility**, though all follow the same core structure.

Each action defines:
- **AP cost**
- **Requirements**, if any
- A list of mechanical steps or checks
- Effects based on success or failure

---
## Skill Use in Actions
Many actions reference a related **skill**. This can influence outcomes in two distinct ways:
- **Skill Modifier** refers to the numerical bonus applied to rolls:
    - **Novice** = +1
    - **Advanced** = +3
    - **Master** = +5
    When you roll dice (e.g., 2d6), this is the number added to the result.
- **Skill Level** refers to the **tier of training** (Novice = 1, Advanced = 2, Master = 3).  
    This is used in some actions to determine static effects, scaling bonuses, or contributions to another character’s effort (e.g., “reduce damage by 1 + skill level”).

Always check whether the action calls for your **modifier** (for a dice roll) or your **level** (for a flat value).

---
## Defensive

### Brace
*1 AP | Requires Heavy Armor Equipped*

You hold your ground, shifting your stance and tightening behind your armor to absorb the force of an incoming blow. It’s not about speed—it’s about resolve. You may not avoid the hit, but you’re prepared to take it head-on.

[Heavy Armor](04_skills.md#Heavy%20Armor)
- Declare before an incoming attack roll.  
- If the attack hits and would cause a wound:  
	- Reduce wound severity by **1 + Heavy Armor skill level**.  
- **Does not prevent armor durability loss**.  
- Must be **stationary** to use this action.

---
### Cast  
*2 AP*

You invoke magical power through practiced command of a specific domain. Effects are described narratively by the player and resolved mechanically based on the scope of the effect .

[See: 10_magic.md](10_magic.md)

- Choose a **Domain Skill** that aligns with your intended magical effect.
- Choose a **Source** of magic
- Describe the effect you wish to create.
- Roll **2d6 + domain skill modifier** vs the assigned DC.

**On success**:
- The intended effect occurs as described.
- The effect lasts **1 round** by default.

**To extend the effect**:
- Spend **2 AP** again on your next turn.
- Roll again vs **original DC + 1 per additional round**.

- **Duration**: All effects last **1 round** by default. To extend:
  - Spend the **same AP cost** again on your next turn
  - Roll again vs **DC + 1 per additional round**

*Only one magical effect may be actively maintained at a time.*

*See the magic rules for guidance on assigning DCs, examples of effect magnitude, and source-specific complications.*

---
### Deflect
*1 AP | Requires Armor Equipped*

Instead of absorbing the full brunt of the attack, you shift your posture to let the blow glance off your armor. It’s a practiced maneuver—not one of brute resistance, but of angles and timing—meant to preserve the gear that might save your life in the next exchange.

[Heavy Armor](04_skills.md#Heavy%20Armor), [Light Armor](04_skills.md#Light%20Armor)
- Declare before an incoming attack roll.  
- If the attack hits and would cause your armor to lose durability, compare the attacker’s roll to your **Deflect DC**:
	- **Deflect DC = 8 + your armor skill modifier** (Light or Heavy Armor)
	- If the attacker’s roll is **less than the DC**, your armor takes **no durability damage**.
	- If the roll is **equal to or higher**, armor loses durability as normal.
	- This action does not prevent injury, only the durability loss incurred by the armor. Record your injury as usual.

---
### Evade
*1 AP*

With a quick read of your opponent’s movement, you attempt to slip aside at just the right moment. It’s not about blocking the strike—it’s about not being where the weapon lands. A risky gamble, but sometimes agility is your only shield.

[Agility](04_skills.md#Agility)
- Declare before an incoming attack roll.  
- The attacker’s roll is reduced by **1 + Agility skill level**.  
- If the modified result causes the attack to miss, no wound or armor damage occurs.

---
## Offensive

### Attack
*1 AP | Requires Weapon Equipped*

- Roll **2d6**.  
- Add your **weapon skill bonus** and the weapon’s **Roll Modifier**.  
- Compare the final result to the **Attack Resolution Table**.  
- If the result indicates a wound:
	- Apply **armor wound reduction** (if any).
	- Apply the final wound level to the target.
	- Armor loses **1 durability** if it reduced the wound by any amount.

> The Basic Attack is the most common offensive action, representing a standard strike with any weapon.  
> Advanced techniques or weapon effects may alter this action or its outcome.

---
### Shadow Strike  
*2 AP | Requires Ranged Attack, Must be Hidden*

From the shroud of foliage, shadows, or smoke, the attacker looses a projectile with deadly intent. The shot is swift and sudden, offering no clear origin point. Enemies reel from the impact, but can only guess where it came from.

[Stealth](04_skills.md#Stealth)
- Attack as normal using a ranged attack while hidden
- On a hit
	- Roll 2d6 and add the **Stealth** skill modifier
	- The **DC** is determined by the GM based on difficulty
	- On success, attack is made without revealing your exact location
		- Target knows the general direction of the attack
		- Others must roll Search against your Stealth roll to pinpoint your location

---
### Sundering Strike
*2 AP | Requires Blunt or Slashing Weapon*

You target the armor, not the body—hammering, prying, or tearing with the intent to compromise protection. Whether by raw force or precise leverage, your goal is to leave your opponent exposed and vulnerable, even if they walk away unharmed—this time.

- Attack as normal.  
- On a hit:  
	- **Blunt weapon:** Armor loses durability = wound level  
	- **Slashing weapon:** Armor loses durability = ½ wound level (round up)  
- Target suffers **no wounds** from this attack.  
- Has no effect on unarmored targets.

## Utility

### Assist
*1 AP | Requires Proximity*

You lend your attention, effort, or expertise to support a nearby character's action. Assisting can mean helping lift a barrier, providing light, holding a tool, or offering verbal guidance.

- Declare your intent to assist before the primary character makes their roll.
- You must be within reach or have the means to meaningfully contribute.
- If the GM deems the help appropriate, the assisted character gains **+your relevant skill level**
- Only one Assist may apply to a given action.

---
### Deceive  
*1 AP | Requires opportunity to speak or present misinformation*

You present a falsehood as truth using confidence, omission, or manipulation. This could be a lie, a false identity, forged credentials, or misdirection during a negotiation.

[Diplomacy](04_skills.md#Diplomacy)
- Describe the falsehood and how it is being delivered
- Roll Diplomacy against a DC set by the GM based on plausibility and skepticism of the target
- Success means the target accepts or acts upon the deception
- Failure may result in disbelief, suspicion, or exposure

*Repeated use against the same target increases DC. Complex lies may require supporting evidence or coordination with other actions.*

---
### Hide
*1 AP | Requires Cover*

You duck into shadows, behind obstacles, or into the landscape, using the terrain to break line of sight. Hiding is not invisibility—it’s about exploiting the moment.

- Must be adjacent to or within an area that provides **sufficient concealment**.
- Make a Hide check using your **Stealth skill**.
- Observers must beat your result with a relevant **Perception or Awareness check** to detect you.
- Being spotted or taking an action (other than movement between cover) ends the hidden state.

*Situational Modifiers*
- Heavy armor (–1 to the roll)

---
### Intimidate  
*1 AP | Requires leverage, threat, or demonstration of force*

You use fear, coercion, or force of presence to compel action. This could be a verbal threat, a show of overwhelming strength, or invoking authority the target respects—or fears.

[Diplomacy](04_skills.md#Diplomacy)
- Describe the threat or presence being projected
- Roll Diplomacy against a DC set by the GM based on the target’s resolve and the credibility of the threat
- Success causes the target to comply or back down
- Failure may provoke resistance, mockery, or retaliation

*GMs may allow [Resolve](04_skills.md#Resolve) checks as the target’s defense. Intimidation can damage rapport or trust if overused.*

---
### Jump  
*1 AP | Basic Movement*

A sudden burst of movement, the Jump action is used to leap across gaps, ascend to higher ground, or avoid obstacles. Its success depends on momentum, distance, and the character’s physical aptitude.

[Athletics](04_skills.md#Athletics)
- Roll 2d6 and add the **Athletics** skill modifier
- The **DC** is determined by the GM based on distance and difficulty

*Situational Modifiers*
- Running start (+1 to the roll)
- Heavy armor (–1 to the roll)

---
### Move
*1 AP | Basic Movement*

You move carefully through your surroundings, staying alert to danger and maintaining awareness. This covers tactical movement, navigation during exploration, or repositioning in combat without haste.

- Move a number of spaces up to your **base movement speed** (default is 3 spaces).
- Applies to all forms of unimpeded movement, including swimming and flying when applicable to your character.

---
### Move Undetected  
*1 AP | Requires concealment, cover, or darkness*

You move stealthily through your surroundings without drawing attention. When successful, the character may reposition while remaining hidden from enemies.

[Stealth](04_skills.md#Stealth)
- Roll 2d6 and add the **Stealth** skill modifier
- The **DC** is determined by the GM based on distance and difficulty

*Situational Modifiers*
- Heavy armor or noisy gear: –2
- Moving slowly (half speed): +1

---
### Persuade  
*1 AP | Requires time to speak and a listener not actively hostile*

You attempt to influence someone's beliefs or decisions through reason, empathy, or mutual interest. Persuasion is most effective when goals align, trust is present, or emotions can be redirected.

[Diplomacy](04_skills.md#Diplomacy)
- Clearly state what you're asking the target to do or believe
- Roll Diplomacy against a DC set by the GM based on the target's disposition and the nature of the request
- Success means the target agrees or complies within reason
- Failure may result in doubt, negotiation, or resistance

*Bonuses may apply if offering tangible incentives or appealing to known values. Penalties may apply if goals strongly conflict or trust is low.*

---
### Search
*1 AP | Requires Line of Sight*

You take a focused moment to examine your surroundings. Whether you're checking for traps, identifying a hidden object, or assessing the layout of a room, Search allows you to turn attention into information.

- Choose a visible object, area, or feature within close range (adjacent or same room/zone).
- Make a Search check using an appropriate skill (e.g., Awareness, Lore, Crafting).
- The GM compares your result to the hidden or required DC and reveals any relevant information.
- May not reveal all details at once—multiple checks may be required for complex features.

---
### Sprint
*2 AP | Extended Movement*

You push your body beyond normal pacing, covering more ground at the expense of attention and combat readiness. Sprinting is faster but riskier.

[Athletics](04_skills.md#Athletics)
- Move **2x your base movement speed** plus your **Athletic skill modifier**.

---
### Stabilize Wound  
*1 AP*

You act quickly to prevent a dying character from slipping away—compressing a wound, applying a makeshift tourniquet, or steadying shallow breaths. This is emergency triage, not recovery.

[Medicine](04_skills.md#Medicine)
- Choose a Wounded and Incapacitated target within reach
- Roll **Medicine vs DC 8**
- On success: The target is **Stabilized** and will no longer worsen from their current wounds
- On failure: The target remains unstable and continues deteriorating per normal wound rules

*Situational Modifiers*
- Apply **–2** penalty if no healer’s kit is used.

---
### Treat Wound  
*3 AP*

You take time to clean, set, and dress a wound—reducing its severity through practiced technique and careful attention. This is battlefield medicine, not long-term care, but it’s often enough to restore a fighter to action.

[Medicine](04_skills.md#Medicine)
- Choose a wounded target within reach
- Roll **Medicine vs wound's DC** (see [Wound Resolution Table](08_woundslots.md)) for the effects

*Situational Modifiers*
- Apply **–2** penalty if no healer’s kit is used.

---
### Use
*1 AP | Requires Item or Feature*

You interact directly with an item, device, mechanism, or environmental feature. This can include everything from opening a door to lighting a torch to activating a strange device.

- The GM determines whether the use is immediate, contested, or part of a larger sequence.
- Simple or obvious items may succeed automatically.
- Complex, locked, or dangerous items may require a skill check (e.g., Mechanics, Dexterity, Crafting).

---
