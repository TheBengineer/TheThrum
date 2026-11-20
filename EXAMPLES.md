# Examples: test runs

Worked examples of the rules in [RULES.md](RULES.md) applied to play. Version 1.0.

## Test run 1: Ghouls in a flooded crypt

**Result:** under the new capacity limit, brute force can kill one ghoul per action at best. The marsh gas, the wizard's own mana pool and teamwork with the cleric carry the fight. The healing afterwards leaves the fighter with grey flesh to deal with.

**Situation the DM gives the LLM.** Level 5 wizard (Int +4, Con 14): capacity 7, mana pool 20 (full), Burn threshold 19, holding a torch. Four ghouls (15 HP each) are 40 ft away, knee-deep in black water. The party's level 5 fighter (30 HP) has waded in after them, and a level 5 cleric (Wis +4, capacity 7) waits by the door. The crypt is Thin (15 Motes). Bubbles are rising from the water, and the place smells of swamp.

**Intent A: "I blast all four ghouls with fire."**

- Cost: the most that fits in capacity 7 is 6d6. That's 6 Motes, x1.5 for distance makes 9, and the torch's sympathy takes off 3, for **6**. A seventh die would cost 7.5, which rounds up to 8 and doesn't fit.
- What happens: Spread splits 6d6 four ways, about 1.5d6 (5 damage) per ghoul. All four are still standing at about 10 HP.
- Ledger: the crypt drops to 9 Motes, and the wizard takes 2 Burn.
- **Alternative:** the same 6d6 on one ghoul does about 21 damage and kills it. The best brute force can do is one ghoul per action.

**Intent B: "Those bubbles are marsh gas. I flick a spark into them."**

- Cost: a 1-Mote trigger at x1.5 is **2 Motes**, drawn from the wizard's own pool (20 to 18) so the crypt's Flux is left for the cleric.
- What happens: the pocket releases about 16 Motes across 20 ft. Spread gives the four ghouls and the fighter about 3d6 each, roughly 10 damage. The ghouls are left at about 5 HP, and the fighter drops to 20 of 30.
- Follow-up: next round the wizard spends 3 more Motes from the pool on 4d6 (6 at x1.5, minus 3 for the torch), split between the two healthiest ghouls, finishing them. The fighter's sword handles the other two.
- Ledger: wizard pool 15 of 20 (refills at 3 per 10 minutes from the crypt) and 2 Burn. The crypt still holds 15 Motes.

**Healing the fighter.**

- The cleric regrows the burned flesh: 3 Motes from the crypt for 3d6, about 10 HP of new flesh. The crypt drops to 12.
- The fighter spends one Life Force die (1d6 + 3, about 6). Because the cleric did the regrowing, all 6 goes into making the flesh alive.
- Result: the fighter is back at 30 HP, but about 4 of it is grey flesh. Their burned forearm feels asleep and gives -1 Dexterity. If it doesn't get more life force within a day, the fighter makes a DC 10 Constitution save, at disadvantage if they keep pushing through the dungeon without resting.

**Lessons.**

- The new capacity makes area blasts weak, so players will look for stored energy and work together, which is what we wanted.
- The mana pool's real value is in not draining the shared Flux. That turns it into a party resource question: who casts from where?
- Healing now has an aftertaste. The fighter has a reason to rest, and the party has to decide whether to push on with a grey arm.
- **Gap, still open:** the LLM guessed the gas pocket's 16 Motes. The DM still needs a short table of common stored energies.

## Test run 2: Freezing a river to cross it

**Result:** heat loans make freezing a real but slow utility. A walkway in one action is out of reach. Freezing it a few feet at a time works, and a cheap mist wall makes it safe. The old heat-pumping combo is gone, because borrowed heat leaves nothing to throw.

**Situation the DM gives the LLM.** Level 5 druid (Wis +4, Con 14): capacity 7, mana pool 20 (full), Burn threshold 19. The river is 30 ft wide and it's summer. Two archers wait on the far bank. The riverbank is Rich (100 Motes).

**Intent A: "I freeze a walkway across."**

- Energy path: a heat loan. The Thrum lends the heat, so nothing vents and no steam rises.
- Size: ice that holds a walking person needs to be about 4 inches thick. A path 3 ft wide and 30 ft long at that thickness is about 30 cubic feet of water, roughly 75 buckets.
- Cost: 75 buckets is 75 Motes. x1.5 for distance is about 112. The river halves it, but the saving is capped at 20 per action: **92**.
- Can they do it? No. That's thirteen times capacity and over four times the druid's pool.
- **Alternative: walk and freeze.** The druid freezes the river at their feet (touch, x1) and steps onto each new piece. Capacity 7 at half cost freezes 14 buckets, about 5 ft of path, per action. Six actions get them across for about **38 Motes**, drawn from the riverbank since the pool alone isn't enough.
- What happens: the ice is real and floats until the summer current melts it, about 10 minutes. As it melts, it repays the Thrum, not the river. For six rounds the druid is a slow target on open ice.
- Ledger: the riverbank drops from 100 to 62. Loss gives the druid about 11 Burn over the crossing, a little over half their threshold.

**Intent B, first round: "Before I start, I boil a strip of the river into fog."**

- Cost: a steam loan on 4 buckets across the river. x1.5 for distance and half for sympathy is **3 Motes**, from the pool (20 to 17).
- What happens: magical steam is a hot mist, not an expanding blast. A bank of fog hangs over the river, and the archers shoot at disadvantage while it lasts, about a minute in still air. When it condenses, it repays the Thrum, so nobody gets scalded.
- **Ruled out: "I throw the stolen heat at the archers."** No heat was stolen. The ice and fog were bought on loan, so there's nothing to redirect. Fire at the archers means paying for it at full price.

**Lessons.**

- Heat loans close the heat-pumping combo without any special rule.
- Freezing becomes a ritual-speed tool: good for crossings, barricades and traps set before a fight, weak as a combat trick.
- A Rich place matters. On a Thin bank the druid would run out of Flux halfway across.
- **For the DM:** buckets are the unit to estimate. A hand-sized ice block is a fraction of a Mote, a door-sized slab is about 10 buckets, and a walkway is dozens.

## Test run 3: Counterspell in a dead vault

**Result:** the mana pool, not the patron, now carries casters through a dead zone. Capacity forces a choice between a full counter that blows up in your face and a partial counter that blows up safely down the corridor. The leftover blast damages the old ceiling, and the warlock uses that next round.

**Situation the DM gives the LLM.** Level 5 warlock (Cha +4, Con 14): capacity 7, mana pool 20 (full), Burn threshold 19, 5 Life Force dice. The level 5 fighter (30 HP) stands beside them. The vault is Dead (0 Motes), so nobody regenerates. An enemy mage (level 9, capacity 9) is 40 ft down the corridor with a 40-Mote crystal.

**The enemy's spell.** 6d6 lightning within 60 ft: 6 x 1.5 = 9 Motes from the crystal (40 to 31). Spread splits it between the warlock and the fighter, about 3d6 (10 damage) each.

**Intent A: "I meet the bolt with an equal and opposite force."**

- Energy path: the warlock's own mana pool. The vault has nothing to give.
- Full counter at mid-corridor: 6 opposed Motes x1.5 is **9**, over capacity 7.
- Full counter at arm's length (touch, x1): **6**, within capacity. But Conservation sends the 6 cancelled Motes out right where they meet, so 6d6 of thunder lands on the warlock and fighter. That's worse than taking the bolt.
- **What the warlock does: a partial counter at mid-corridor.** 4 opposed Motes at x1.5 cost 6, the most that fits (5 would cost 7.5, which rounds up to 8). The warlock could instead attempt the full counter with an over-capacity check, d20 + 7 against DC 14 (about 70%), but plays it safe. Those 4 cancel 20 ft away, and 4d6 of thunder hits the walls. The remaining 2d6 of lightning gets through, about 3 damage to each of the warlock and fighter.
- Ledger: pool 20 to 14, 2 Burn. The LLM notes the vault's old cracked ceiling took the thunder. It's now a Release hazard.

**Intent B, next round: "I bring the cracked ceiling down on the mage."**

- Cost: a Release trigger is 1 Mote, x1.5 for distance, so **2** from the pool (14 to 12).
- What happens: tons of stone fall about 10 ft. The LLM estimates around 10 Motes of stored energy, so roughly 10d6 spread over the mage and the corridor around them. The mage is buried or crushed, and the crystal (31 Motes) is loot under the rubble.

**Where the patron comes in.** With an empty pool, the warlock is the only caster left who can still cast in a dead zone. Borrowing 7 Motes means owing 11 at 1.5x. At the next long rest the patron drains all 5 Life Force dice (10 Motes), and the last 1 becomes a favor. The warlock wakes up unable to heal themselves.

**Lessons.**

- Every caster now carries a fuel tank into dead zones. The patron is the reserve tank, and a costly one.
- Interference plus capacity creates a real choice: cancel everything and take the burst, or cancel part of it and push the burst away.
- Counters damage the room. A smart DM keeps track of what the cancelled energy hit.

## What the tests exposed

All three re-runs worked under the current rules (capacity, mana pool, heat loans, Life Force dice) without any special-case rules. The combos came straight from the laws: igniting the marsh gas, freezing a path while walking under a mist wall, and a partial counter that cracks the ceiling and then brings it down. Capacity is the real limit. No level 5 caster shaped more than 7 Motes in an action. Every big effect came from stored energy.

| Gap | Proposed handling | Test |
| --- | --- | --- |
| Stored energy amounts were guesses (gas pocket 16, cracked ceiling 10) | Add a short table of common stores: gas pocket, oil barrel, loose ceiling or boulder, dam, lightning storm | 1, 3 |
| Area spells are weak: 6d6 split four ways is about 5 damage each | Intended. It rewards focus, stored energy and teamwork. Confirm with players | 1 |
| The mana pool's real value was leaving Flux for allies | Intended. Who casts from where becomes a party decision | 1 |
| Healing leaves grey flesh, which pushes the party to rest | Intended. Watch whether players find it fun or a chore | 1 |
| Ice is slow at scale (a walkway is 92 Motes) | Keep the bucket rate, since walk-and-freeze is the intended use. Optional buff: 1 Mote per 3 buckets | 2 |
| Heat pumping (from the old Test 2) | Closed. Heat loans leave no stolen heat to redirect | 2 |
| The over-capacity check went unused. A full counter at d20 + 7 against DC 14 succeeds about 70% of the time | Settled: casters work at capacity by default. The check applies only when the player says the character strains ("give it everything"), and that buys extra Motes at the check's risk | 3 |
| Partial casts need a rounding rule (7 / 1.5) | Settled: the final cost rounds up to a whole Mote (see Loss), so the effect drops a step when it won't fit | 3 |
| The patron is rarely needed now that pools work in dead zones | Fine. The pool is the main tank and the patron is a costly reserve that drains Life Force dice | 3 |
| Partial opposition (fire above water) was a judgment call | Precedent: only the medium the energy travels through counts | 1 (first run) |
