[prev](09_exhaustion.md) | [index](00_index.md) | [next](11_actions.md)
# Magic
Magic in _Heroless_ is powerful, flexible, and dangerous. There are no fixed spells—only **effects shaped by your intent**. Magic is resolved using a skill check:  
**2d6 + Domain Skill vs. calculated Difficulty Check (DC)**.

Effects are built from three components:
- **Magnitude** (1d6–3d6) determines strength
- **Range** and **Area** determine scope and risk
- **Source** determines how the magic is fueled

---
## Magic Sources
All magic must be fueled by one of two sources. Both cost **2 AP** to cast.

### Raw Magic
- **Resource**: Exhaustion
- Wrest power directly from the fabric of reality. Risk of burnout grows with each use.

### Sacrificial Magic
- **Resource**: Wounds (self-inflicted or willing)
- Fast and brutal—life force becomes fuel. Always painful, sometimes deadly.

---
## How to Cast Magic

1. Declare the intended effect.
2. Choose an appropriate Domain (e.g., Destruction, Restoration).
3. Define:
    - **Magnitude** (how strong)
    - **Range** (how far)
    - **Area** (how many targets)
4. Calculate the **DC**:  
    `DC = 7 + Range Modifier + Area Modifier + Magnitude Modifier`
5. Spend **2 AP**.
6. Roll: `2d6 + Domain Skill` vs. DC.
7. Apply the effect **and** pay the **resource cost based on result tier** (below).

---
## Degree-Based Resource Cost

|Result Range|Result Type|**Raw Magic**|**Sacrificial Magic**|
|---|---|---|---|
|Roll ≤ DC – 3|Critical Failure|3 Exhaustion|3 × Level 3 Wounds|
|DC – 2 to DC - 1 (inclusive)|Failure|2 Exhaustion|2 × Level 3 Wounds|
|DC |Success|2 Exhaustion|2 × Level 3 Wounds|
|DC + 1 to DC + 5 (inclusive)|Success|1 Exhaustion|1 × Level 3 Wound|
|Roll > DC + 5|Critical Success|Free|Free|

- **Wounds stack and occupy Wound Slots** as usual.
- **Exhaustion effects are cumulative and may impose penalties.**
- The resource cost is **always paid**, even on failure.

---
## Modifiers
### Range Modifiers

|Range|Description|Distance|Modifier|
|---|---|---|---|
|Touch|Self or adjacent target|≤ 5 ft|+0|
|Short|Room-scale effect|≤ 15 ft|+1|
|Long|Line of sight|≤ 45 ft|+3|

> _Line of sight or magical path must be clear._

### Area Modifiers

|Area|Description|Modifier|
|---|---|---|
|Target|Single entity or object|+0|
|Small|~10 ft radius / 2–3 targets|+2|
|Large|~20 ft radius / group zone|+4|

### Magnitude Modifiers

|Magnitude|Description|Effect Dice|Modifier|
|---|---|---|---|
|Minor|Simple or limited effect|1d6|+0|
|Moderate|Substantial or refined effect|2d6|+2|
|Major|Potent, complex, or forceful|3d6|+4|

---
## Sustaining Effects
Magical effects last **1 round by default**.

To extend an effect:
- At the **start of your turn**, pay **2 AP again**
- Roll: `2d6 + Domain Skill` vs. **DC +1 (per round extended)**
- No additional resource cost
- Drop effects voluntarily at any time

---
## Example: Casting with Risk
Effect: Conjure a barrier to shield allies
- **Domain**: Protection
- **Magnitude**: Moderate (2d6) → +2 DC
- **Range**: Short (≤ 15 ft) → +1 DC
- **Area**: Small (2–3 targets) → +2 DC
- **Final DC**: 7 + 2 + 1 + 2 = **12**
- Roll: 2d6 + Protection Skill
- Result:
    - Roll of 10 → Failure (2 Level 3 Wounds or 2 Exhaustion)
    - Roll of 14 → Success (1 Wound or 1 Exhaustion)
    - Roll of 18 → Critical Success (no resource cost!)

---
## Domains
Domains are individual magic skills. Each governs a specific theme of effect:
- **Destruction** – inflict damage or break 
- **Protection** – block harm, shield allies
- **Restoration** – heal injuries or remove conditions
- **Manipulation** – move or reshape physical matter
- **Perception** – sense hidden forces or amplify awareness
- **Summoning** – conjure objects, creatures, or allies
- **Binding** – restrain, suppress, or contain forces