[prev](07_resolutions.md) | [index](00_index.md) | [next](09_exhaustion.md)
# Health & Wounds
In Heroless, characters do not track hit points. Instead, injury is modeled through individual wounds, each with a severity level and specific consequences. Every wound matters, and enough accumulated trauma can kill even the most resilient traveler.

This section outlines how wounds are tracked, how injuries affect characters, and the tactical trade-offs involved in healing and survival.

---
## Wound Threshold
Characters can sustain up to five wounds at any one time by default. This value is known as the wound threshold and may be modified by traits, skills, or limitations.

If a character exceeds their wound threshold (typically the sixth wound), they die immediately—unless the new wound can be compounded with an existing minor wound (Level 1–2).

Wound compounding reflects how repeated injuries to the same area can escalate into more serious trauma.

### Compounding Wounds
- Both the new wound and the target wound must be minor—that is, Level 1 or 2.
- Wounds may only be compounded at the moment the new wound is received. The decision must be made immediately.
- The resulting wound has a severity equal to the sum of both wounds.

- Example: Level 1 + Level 2 = Level 3

- The compounded wound replaces both originals and uses a single wound slot.
- The player chooses which qualifying wound to compound with.
- If no valid compounding option exists when the wound threshold is exceeded, the character dies immediately.  

> Compound early and you may escalate minor injuries into dangerous ones. Wait too long and you may leave yourself without options when it matters most.

Example: A character has four wounds: Level 3, Level 2, Level 2, and Level 1. They receive a new Level 1 wound (their sixth). They choose to compound it with an existing Level 2, creating a new Level 3 wound. Their wound count remains at five, and they survive.

---
## Wound Levels
Wounds are assigned a severity level from 1 to 6. Each wound occupies one slot toward a character’s wound threshold. They do not stack numerically, but are tracked individually.

| Level | Category        | Description                        | Healing                        | Effects                                  |
|-------|------------------|-------------------------------------|----------------------------------|------------------------------------------|
| 1–2   | Minor Wounds     | Superficial or light injuries       | Heals naturally or with rest     | Minimal to no penalties; **can be compounded** |
| 3–4   | Major Wounds     | Moderate trauma                     | Requires downtime or treatment  | **Cannot be compounded**; no active effects     |
| 5     | Severe Wound     | Functional impairment               | Requires stabilization           | **Active effects**: bleeding, fracture, etc.    |
| 6     | Permanent Wound  | Lasting or disfiguring trauma       | Only magic or extended care     | **Permanent consequences**                      |

> Active effects are only applied for wounds of Level 5 or higher.  
> Major wounds still count toward the wound threshold and must be healed before recovery is complete.

---
### Active Effects (Severe Wounds)
Wounds of Level 5 introduce active effects that persist until stabilized:

- Bleeding: Causes additional wounds if untreated.
- Fracture: Reduces movement or limits actions.
- Fatigue: Increases exhaustion level with activity.

Stabilizing a wound removes its active effect but does not reduce its severity.

---
### Permanent Injuries and Scars
A Wound Level 6 injury causes a permanent impairment.

Examples:
- Limp: Reduced movement, balance penalties
- Missing eye: -1 to perception-related checks
- Maimed hand: Limits crafting or weapon use

Permanent injuries can also grant narrative weight:
- Earn fear, respect, or sympathy
- Affect reputation or faction standing
- Serve as badges of honor—or failure

The exact form and consequence of a permanent injury should be agreed upon by player and GM.

---
### Death and Dying
A character dies immediately upon exceeding their threshold, unless they successfully compound the new wound with an existing minor wound (see above).

A Wound Level 6 represents a permanent injury, not death, and carries lasting narrative or mechanical consequences unless resolved through magic or advanced recovery.

The GM may override this system in rare narrative situations (e.g., massive trauma or disintegration effects), but this should be the exception.

---
## Stabilizing a Character
Stabilization prevents death, halts bleeding, or removes active effects from severe wounds.

### Non-Magical Stabilization:
- Requires 2 AP, a healer’s kit, and a successful skill check
- Can target a specific wound
- Removes active effects but does not reduce severity

### Magical Stabilization:
- Requires a healing spell, a casting roll, and resource cost
- Instantly stabilizes or may reduce severity depending on success
- Follows all standard casting rules (Divine, Sacrificial, Raw)

---
## Healing Wounds
Healing is a skill-based process using a 2d6 + Healer Skill roll. Each wound may be treated once per day. Additional attempts on the same wound cause the healer to gain 1 level of exhaustion per extra attempt.

|Roll|Result|Effect|
|---|---|---|
|2–6|Failure|Wound severity increases or complications arise|
|7|No Effect|Wound remains unchanged|
|8–11|Stabilized|Active effects removed, severity unchanged|
|12+|Critical Success|Wound severity is reduced by 1|

> Minor wounds (Level 1–2) heal naturally: reduce severity by 1 per day with rest.  
> A healer’s kit is required for non-magical healing.

---
### Magical Restoration

Magical healing offers immediate benefits but comes at significant cost.
- Can remove active effects or reduce wound severity instantly  
- Requires a casting roll and AP cost based on the magic source:
	- Divine: Uses Piety (1 AP)
	- Sacrificial: Causes Wounds (2 AP)
	- Raw: Causes Exhaustion (3 AP)

While powerful, magical healing is resource-limited and cannot always replace consistent medical care.

> Tactical Note: Magical healing is best used in emergencies. Overreliance may drain critical resources or leave casters vulnerable.