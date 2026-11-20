# The Laws of Thaumic Physics

*Version 1.4. The magic system for The Thrum.*

See also: [Examples](EXAMPLES.md) · [Open questions](OPEN_QUESTIONS.md)

## Design goals

Magic in The Thrum is a branch of physics: it moves energy around, it never makes energy from nothing, and every spell leaves a trace. Players should be able to reason their way to clever spells the way an engineer would.\
An LLM will be used as a physics engine to emulate Thaumic effects and will be made available to the players and the DM to answer "what happens if I..." questions.

The world is generic fantasy with real physics and magic on top, in the spirit of Discworld.\
Characters use the standard 5e ability scores (Strength, Constitution, Wisdom and so on).

- **A few simple laws, no spell list.** Players learn seven laws and one table of conversions, then invent their own spells and techniques from them.
- **Emergent, not enumerated.** Clever setups (stored energy, sympathy, the environment) should beat raw power, the way they do in real physics.
- **The LLM advises the DM and players**.** The DM describes the situation and the player's intent; the LLM answers what would happen under the laws, with its reasoning, and keeps rulings consistent. Players can field ideas on the side to a separate session to answer general questions.
- **Costly enough to matter.** Big magic needs a big energy source, and finding one is an adventure.

The Flux is a basic property of the world and has always been there, like gravity. Locals call its hum the Thrum, which is also the world's name.

## The seven laws

Magic is the art of moving energy, measured in **Motes**. These seven laws are the whole system. Any spell a player can describe is legal if they can pay for it under these laws.

1. **Conservation.** Motes are never created or destroyed, only moved and changed. Every effect costs exactly the energy of the physical change it makes (see the conversion table). Energy taken out of something, like heat pulled from water, has to go somewhere.
2. **Source.** Every Mote comes from somewhere: the *ambient Flux* of a place, the caster's own mana pool, a store such as gold or a gem crystal, the caster's body (Life Force dice), or a *patron* who lends it and wants it back with interest.
3. **Loss.** Shaping is never perfect. For every 4 Motes shaped, 1 escapes as *Residue*: heat, light, noise, a smell of ozone. Residue soaks into the caster as *Burn* unless they vent it somewhere. To work out a cast, go in this order: base Motes, then the distance multiplier, then sympathy (halve, with the saving capped), then any focus discounts. Round the final cost up to a whole Mote. Loss is that final cost divided by 4, rounded up, and silver then cuts it by its grade %, rounded to the nearest whole Mote.
4. **Distance.** Energy is cheapest where you stand. Effects at touch cost x1, within 60 ft x1.5, anywhere in sight x2, and beyond sight x4, unless a *link* (a name, hair, blood, a possession) bridges the gap at x2.
5. **Sympathy.** Like moves like. Working with a matching medium halves the cost, because the medium does part of the shaping. It gives no energy of its own: you can't slow a river to get Motes, and every Mote still comes from a Source. The saving per action is capped by the medium's size (candle 1 Mote, torch 3, campfire 6, forge 15, river or storm 20). Working against your medium, like fire underwater, doubles it.
6. **Release.** The world is full of stored energy: a gas pocket, a dammed river, a boulder on a slope, a tensioned rope. Magic can unlock it for the cost of a trigger (usually 1 Mote), and the world pays the rest. Whatever is released obeys the other laws, and it doesn't care whose side you're on. A chain of releases (a flask lights the gas, the gas drops a pillar) costs only the first trigger, as long as every link is physically plausible, and setting off that trigger is the caster's action for the turn.
7. **Saturation.** A place holds a limited pool of Flux that refills slowly. Drain it and the place goes *dead*: plants wilt, flames gutter, and casters must pay from their own pools or bodies.

Two things follow from the laws rather than being separate rules. **Spread:** energy divides over everything it touches, so a blast that hits four targets gives each a quarter. **Interference:** opposed energies cancel Mote for Mote, and because of Conservation the cancelled energy bursts out where they meet.

**Spread and Interference in play.** For Spread, the caster picks the shape of the effect: a beam, a cone or a burst. The energy divides evenly among the creatures and objects in that shape that the spell is meant to affect. Floors, air and clothing don't soak up a share, so a narrow beam on one target gives that target everything. For Interference, a counter meets the incoming spell somewhere along its path, and the countering caster picks the spot, paying the distance cost to reach it. The cancelled Motes burst there as thunder: 1d6 per cancelled Mote, spread over everything within 10 ft. That's base damage, so saves and cover still apply.

### Forms of energy

Magic can become any ordinary form of energy, at about 5 kJ per Mote.

- **Kinetic:** shoot a rock, shove a door, lift a load. A shot rock does 1d6 per Mote.
- **Heat:** see the heat rule and heat loans.
- **Chemical:** this is alchemy (see below).
- **Electrical:** lightning, at 1d6 per Mote.
- **Nuclear:** possible in theory, but splitting atoms takes more concentration than any caster has. It would need a real physical reactor.

**It only runs one way.** Motes come from the Flux. No physical energy, whether a falling rock, a fire, a river or a lightning storm, ever turns back into Motes.

**Moving physical energy strains the caster.** A caster can take energy from one thing and put it into another, just as they move heat. Slowing a falling rock to lift another rock is legal, and the Motes come from the moving rock rather than the caster's pool. But every Mote moved passes through the caster: it counts against capacity and causes Burn as if they had shaped it. A rope and pulley does the same job with no limit and no Burn, and a sensible caster uses the rope.

**Alchemy is archmage work.** Chemical energy can be pulled out of one substance and used to build another. For example, burning oil down to ash can power turning wood into something like plastic. It's slow and needs full concentration, plus years of study of the substances involved. A master who has done it for decades makes a few ounces an hour, a pound at best. Starting characters can't do it at all.

**Shaping matter costs more for detail.** Shaping or shattering a cubic foot of stone or wood costs 1 Mote for a rough shape (a wall, a ramp, a hole). Fine work, like a hinge or a blade's edge, costs x2. Intricate work, like a lock, a gear train or jewelry, costs x4. Cutting away a load-bearing piece is a Release trigger: the cut costs what it costs, and the world pays for the collapse. Magic shapes but doesn't give skill, so anything meant to be good, not just shaped, still needs a crafting check. Skilled craftsmen stay in business.

## Life and healing

Living flesh carries **life force**; dead matter doesn't. The body has a limited amount of life force available, and it restores naturally at a steady rate. Forcing an arm to regrow is easy with magic, but making it **alive** is hard.

- **Life Force dice.** (d6 each) Adventurers have one per level, with a minimum of 2. They are the body's limited life reserve, and a long rest restores half your maximum (round up), or all of them in a Rich place. A hearty meal of fresh food also restores 1 die, once a day.
- **Healing has two jobs: regrow and enliven.** Spend a Life Force die and roll 1d6 + Con. Half the roll regrows broken flesh (HP) and half makes it alive, so on its own a die heals half its roll (round up).
- **A healer's magic can do all the regrowing.** Magic regrows flesh at 1d6 per Mote, and then each Life Force die spent goes entirely to making it alive. A healer and patient working together heal about twice as fast.
- **Regrown but not alive** is grey flesh. A wound healed with grey flesh counts as temporary HP. Grey flesh only replaces what was lost, so it can never take you above your body's max HP, and regrowth can't add new body parts. Someone who loses both legs and regrows them grey is back to full HP, but about 40% of it is temporary. Sensation is deadened, as if the limb were asleep, and Dexterity suffers (-1 per grey limb). Grey flesh that gets no life force within a day calls for a DC 10 Constitution saving throw for each grey limb, at disadvantage if the patient didn't rest. On a failure, that limb becomes necrotic and stays that way until it is healed with life force. Limbs with necrotic wounds must be amputated after 1 week or the body takes 1/3 HP poison damage per day. At that point the limb loses all function: it can't grip, carry or bear weight.
- **Where life force comes from:**
  - *Yourself.* Your own dice, at full value.
  - *A willing donor.* Die for die; the donor spends their own Life Force dice.
  - *A captive, taken by force.* Only 1 in 4 gets through. The captive gains a level of exhaustion per die taken, and the taker's soul is stained: nightmares and -1 Wisdom until they atone.
  - *An animal.* Only 1 in 3 gets through, and the patient takes on some of the animal's traits for a few days.
- **Healers can train their reserves.** A month of practice adds one Life Force die, up to the healer's proficiency bonus.
- **Undead.** A zombie is a body regrown entirely without life force, with its portals to the spirit realm cut off. It moves, but nobody is home.

**Resurrection.** A dead body has no life force left to work with, so it can't be healed from its own reserves. Life force has to come from outside: a donor's Life Force dice, a patron, or one of the very few special places (an ancient grove, a sacred spring) with life force to spare. An ordinary Rich place doesn't hold enough to matter. Rebuild the body without it and you've made a zombie.

**Animal donors.** Life force from an animal works, but cross-species impedance steals 2/3 of it, so you need three times as much. The patient's spirit also takes on some of the animal's traits for a few days. Monkey life leaves you craving bananas; wolf life makes you restless at the full moon.

## Mind and soul

The mind obeys the same laws; it's just hard to reach. A creature's brain and body and its **Chokras** are 3D portals into the 4D spirit realm, where its soul lives. A soul is like a 4D amoeba: a skin separates the self from the surrounding Chaos, and floating inside are the far end of the brain portal and the Chokras.

To affect a mind, magic has to reach through the portal and act on the soul's side. That has three consequences:

- **Impedance.** Ordinary magic couples badly through a portal. Untuned, only 1 in 4 Motes gets through (cost x4), and the rest reflects back into the target's body as Residue: headaches, nosebleeds, ringing ears. **Tuned** magic, from practice or a mind-specialized tradition, pays x2. **Resonant** magic pays x1: casting on your own mind, on a willing target, or through a strong link to that soul (a true name, a lifelong bond).
- **The soul's skin.** The target makes a Wisdom save. On a success the energy spreads across the skin and dissipates as harmless Residue.
- **Conversions on the soul's side** (starting guesses): 1 Mote nudges an emotion for a round or reads surface mood · 3 Motes sends a thought or plants a short suggestion · sleep or calm costs Motes equal to the target's level · a charm lasting an hour costs twice the target's level.

  **Scaling mental effects.** Duration: the costs above last one round, and each step up (a minute, an hour, a day) doubles the cost. Control: an effect that gives orders rather than nudging a feeling costs +50%. Repeats: every attempt on the same creature within a day, whether it worked or not, gives them +2 on their next save against mind magic, and the bonus stacks. Awareness: the target feels something reaching into their mind unless the caster's spellcasting check beats their passive Wisdom (Insight). True names: knowing someone's true name makes the magic resonant (x1), but they still get advantage on the save, because a soul guards its name.

**Death and resurrection.** When the body dies, the portal closes but the soul still exists. Its skin slowly erodes into Chaos, over about 10 days as a starting value. Bringing someone back means repairing the body (see Life and healing) and then reopening the portal with tuned magic (5 Motes per level of the dead) before the skin dissolves. That is far more than one action allows, so resurrection is a ritual: one caster or a circle pours in up to capacity each action until the cost is paid, while someone keeps the portal tuned the whole time (see Reconnection).

- **Reconnection.** Healing the body isn't enough: mind and body have to re-link. While the body's ports stand open and empty, other things may come knocking, such as wandering souls or something from the Chaos. The caster has to keep the portal tuned to the right soul; a strong link (hair, a true name, a loved one present) makes that easier, and a weak one invites possession.

  **What lives in the Chaos.** Whatever common sense says lurks in the void, from hungry mindless things to hungry thinking ones like demons. They are drawn to open portals and empty bodies. The details are left to the DM.
- **Soul aging.** A soul cut off from its body loses its physical anchor and ages fast: **10 years per day** dead. Someone revived after 3 days returns as a 30-years-older soul in their young body. They think, move and tire like an older person. Some of that fades over the next few weeks, but not all of it.
- **The clock.** Aging and skin erosion run together. By day 10 the soul is a century older and its skin is nearly gone into Chaos, so late resurrections are both harder and costlier for the person who comes back.

This makes mind casters a specialty: anyone can try, but without tuning it's four times the cost and it hurts the target in obvious ways.

## Life Basics

These benchmarks anchor the numbers. Since 1 Mote is about 1d6 (3.5 damage), a farmer (12 HP) dies to three or four Motes, and even a legendary hero falls to a couple dozen.

| Who | HP | Life Force Dice 1d6 |
| --- | --- | --- |
| Child or frail elder | 4 | 1 |
| Commoner | 12 | 2 |
| Trained soldier | 20 | 3 |
| Elite soldier, the best a body can get | 30 | 4 |
| Level 1 adventurer (an advanced farmer) | 14 | 2 |
| Level 5 adventurer | 30 | 5 |
| Level 10 adventurer | 30 body + 20 tuned = 50 | 10 |
| Level 20 hero | 30 body + 50 tuned = 80 | 20 |

**The body caps at about 30 HP.** Training takes anyone from farmer to elite soldier, and no further. Adventurers pass that cap by tuning their own life force, so everything above 30 is magic: it can be suppressed in dead zones, drained, or stolen.

### What 1 Mote buys

(Roughly 5 kJ)

| 1 Mote equals | Notes |
| --- | --- |
| Lift 250 lb by 10 ft | Holding it up costs 1 Mote per round |
| 1d6 base damage to one target (armor, cover and resistances still apply) | Heat, cold, force, lightning, all the same energy |
| Freeze a bucket of water (a heat loan) | See Heat loans below; the loan is repaid when the ice melts |
| Shape or shatter a cubic foot of stone | Once shaped, it stays; matter has no duration |
| Light a room for an hour | Or a blinding flash for one round |
| Regrow 1d6 HP of flesh | It stays grey until Life Force dice make it alive; see Life and healing |

### Mote cost examples

Common spells and actions, worked out with the laws: base Motes, then distance (touch x1, within 60 ft x1.5, in sight x2), then sympathy, rounded up. Burn is the cost divided by 4, rounded up. A level 5 caster has capacity 7.

| Action | Cost | How it adds up | Burn |
| --- | --- | --- | --- |
| Light a candle or campfire by touch | 1 | A spark at touch | 1 |
| Light a room for an hour | 1 | Table rate | 1 |
| Shove a door open or knock someone down | 1 | 1 Mote of force at touch | 1 |
| Leap 10 ft straight up | 1 | Lifting yourself 10 ft | 1 |
| Freeze a bucket of water | 1 | A heat loan | 1 |
| Throw a fist-sized rock at someone 60 ft away (1d6) | 2 | 1 x 1.5, rounded up | 1 |
| Hurl a boulder at someone 60 ft away (3d6) | 5 | 3 x 1.5, rounded up | 2 |
| Fire bolt at one target 60 ft away (2d6) | 3 | 2 x 1.5 | 1 |
| Fireball, 6d6 burst 60 ft away | 9 | 6 x 1.5. Over capacity 7: a torch's sympathy brings it to 6, or the caster strains | 3 |
| Lightning bolt, 6d6 within 60 ft | 9 | 6 x 1.5. Same problem as the fireball | 3 |
| Ignite a gas pocket or drop a cracked ceiling 60 ft away | 2 | 1-Mote trigger x 1.5. The world pays the rest (Release) | 1 |
| Fog wall over a river 60 ft away | 3 | 4 buckets on loan x 1.5, halved by the river | 1 |
| Punch a hole a foot across through a stone wall | 1 | A cubic foot of stone at touch | 1 |
| Regrow 3d6 HP of flesh by touch | 3 | 1d6 per Mote. It stays grey until Life Force dice make it alive | 1 |
| Counter a 6d6 spell halfway down a 40 ft corridor | 9 | 6 opposed Motes x 1.5. Over capacity: counter 4 for 6 instead | 3 |
| Send a thought to a willing friend | 3 | Resonant mind magic, x1 | 1 |
| Put a level 3 guard to sleep by touch | 12 (6 tuned) | 3 Motes x4 untuned (x2 tuned), and they get a Wisdom save | 3 (2 tuned) |
| Charge a gold ring | 2 | Its full charge, at touch | 1 |
| Fill a mercury flask | 10 | Poured in over two actions | 2 + 1 |
| Resurrect a level 5 companion | 25 + Life Force dice | 5 per level, as a ritual over several actions | 2 per action |

### Stored energy for Release

**Magic converts, then physics takes over.** The laws only cover turning Motes into physical energy and back. Once that's done, real physics runs the rest. Light a barrel of oil and you get a pool of lukewarm oil burning weakly on its surface until it heats up, and only then a hot oil fire. The DM makes an educated guess from the setting. Olive or lamp oil barely burns without a wick or a lot of heat. An alchemical solvent can flash all at once, and that's a real problem.

The table shows what common stores give back when a trigger (usually 1 Mote, plus distance) sets them off. Falling and swinging things use real physics at 5 kJ per Mote. Burst means what happens in the first round. Spread divides it over everything in the area.

| Store | Burst (Motes) | Area | Afterwards |
| --- | --- | --- | --- |
| Portcullis or 500 lb weight dropping 10 ft | 1 | One target under it | Blocks the way |
| Catapult or ballista, cocked | 4 | One target along its line | Needs rewinding |
| A ton of rock dropping 10 ft | 6 | 10 ft | Rubble, difficult terrain |
| Felled tree | 10 | A 5 ft wide line its height long | Blocks the path |
| Cracked vault ceiling | 10 to 20 | 20 ft | Buries what's under it |
| Boulder rolling down a slope | 15 to 20 | A 5 ft wide line down the slope | Keeps rolling to the bottom |
| Flask or barrel of lamp or olive oil | 0 | Its surface | Smoulders; with a wick or strong heat it builds to a hot oil fire over minutes |
| Alchemical solvent (spirits, naphtha) | 10 per gallon | 10 ft per gallon | Flashes at once, then burns out fast |
| Marsh gas pocket | 16 | 20 ft | Flames on the water for a round |
| Keg of black powder (if it exists) | 40 | 30 ft | Smoke, deafening |
| A blazing forge or kiln | 10 | 10 ft | Heat burst; the forge goes cold |
| Mill dam or millpond | 30 per round for a minute | A flood down the channel | Mud and wreckage |
| Lightning drawn from a storm | 40 | One strike point and 10 ft around it | Needs a storm overhead |
| Rockslide or avalanche | 100 or more | A whole slope | Changes the map |

### Wizard Proficiency

| Caster | Capacity per action | Burn threshold | What that means |
| --- | --- | --- | --- |
| Novice wizard (level 1, Int +3, Con 12) | 4 Motes | 13 | A 2d6 blast at range or 4d6 at touch |
| Journeyman (level 5, +4, Con 14) | 7 Motes | 19 | About 4d6 at range; bigger effects need Release, crystals or teamwork |
| Master (level 11, +5, Con 14) | 11 Motes | 25 | About 7d6 at range, enough to drop an elite soldier |
| Legendary archmage (level 20, +5, Con 16) | 15 Motes | 36 | About 10d6 at range; legendary feats still need a ley line or a patron |

**Moving heat is cheaper than making it, but only downhill.** Pumping heat from one place to another costs a fraction of the heat moved, and the fraction depends on how much hotter the destination gets than the source:

| Heat move | Heat moved per Mote spent | Example |
| --- | --- | --- |
| Gentle: destination under \~30 degrees hotter than the source | 10 | Chilling a drink, warming a cold room |
| Hot: up to \~100 degrees hotter | 3 | Boiling a kettle with heat from the air |
| Searing: hotter than that | 1, no discount | Anything that burns, which costs the same as making fire |

Three patches stop physics-minded players from breaking it:

1. **No free fire.** Concentrating heat into something that burns is a searing move, so stealing a room's warmth to roast an enemy costs as much as a Fireball. Waste heat from freezing is cold heat, and throwing it as fire pays full price.
2. **Living things guard their own warmth.** Moving heat into or out of a living body always costs 1 per Mote and counts as damage. No cheap heart-freezing.
3. **Throughput cap.** In one action you can move at most 10 x your capacity in heat, and it has to go somewhere. Dumping it into a small sink, like your own hands, heats that sink up fast.

**Heat loans.** magical phase transitions to Ice and steam don't pay for the heat they require; they borrow it from the Thrum. Opening a loan costs 1 Mote per bucket of water frozen or boiled (a cup is a fraction of a Mote, so round up to 1). The ice or steam is real and lasts as long as nature lets it with some slight deviations.

The loan settles itself. When magical ice melts, it takes back from the Thrum the same Motes that were borrowed to freeze it, not heat from its surroundings. When magical steam condenses, the energy it gives off is absorbed back into the Thrum Motes that were borrowed to make it. Either way, the books balance. A loan buys the change, never Motes: it adds nothing to a pool or a store, so melting magical ice can't be captured for mana, and lead or a dead zone makes no difference to it.

**No free engines.** Magical steam is really a hot mist. It doesn't get the thousandfold expansion of real steam, so it builds almost no pressure: it can scald, fog a room and fill a space, but it can't drive a piston or spin a turbine, or cause a vacuum. It doesn't rise either; it hangs where it was made. Air heated by magic is ordinary hot air, though, and it rises.

Sustained effects pay their cost again each round (for force) or each hour (for light and warmth). Changed matter stays changed until the world changes it back: ice melts, stone stays.

### Motes in the hands of a Caster

- **Capacity = half caster level (round up)** **+ spellcasting modifier.** The most Motes you can shape in one action. A level 5 caster with +4 handles 7, enough for about 4d6 at range: roughly half of a same-level adventurer's HP. By default a caster works at capacity: a fireball into a crowd uses all 7 and Spread divides the damage. Going over happens only when the player says their character strains, giving it everything. Straining doesn't take a separate check: going over capacity adds strain to the casting roll, based on how far over you push (see The casting roll).
- **Burn threshold = Constitution score + caster level.** Residue you don't vent becomes Burn. Each spell that takes you over the threshold gives a level of exhaustion. A short rest clears half, a long rest all.
- **Body as fuel:** the body pays in life energy, never HP: each Life Force die gives 2 Motes. Burning HP for Motes isn't possible, which closes the loop of turning HP into Motes and back into grey flesh. **Patron loans** are repaid at 1.5x by draining Life Force dice at each long rest; any shortfall becomes a favor owed.

### The casting roll

The laws say what a spell can do and what it costs. The casting roll says how well the caster pulls it off. The player says what they're trying to do, pays the Motes, and rolls d20 + spellcasting modifier, minus any strain. The DM reads the total on the scale below and frames it so it means something at the table. Damage dice and the target's saves still apply on top.

**Strain.** Straining is part of this same roll. How far over capacity you push, as a share of your capacity, sets the strain, and each point of strain slides the whole scale up by one (with 1 point, a 2 no longer works and a 3 barely does). Up to a quarter over is 2 points. Up to half over is 5 points. Up to double your capacity is 10 points. Nobody can push past double. For a level 5 caster with capacity 7, that means 8 Motes is 2 points, 9 or 10 Motes is 5 points, and 11 to 14 Motes is 10 points.

| Total | Result |
| --- | --- |
| 1 or less | Doesn't work. The energy comes back at the caster. |
| 2 to 4 | Barely works, in the least technically possible way. A 2 works only to a tiny degree. "I cast fireball to light him on fire." Roll: 2. "His mustache is burning." |
| 5 to 9 | Mediocre. It works, but the effect wanes: half the damage or duration, a wobbly aim, a short-lived result. |
| 10 to 14 | Works as intended. |
| 15 or more | Works with pep and vigor: a little extra, like a longer duration, a cleaner shape, or a useful side effect. |
| Natural 20 | Spectacular, whatever the total. The DM helps steer the result into something memorable and meaningful for the players. |

**Where the leftover energy goes.** Conservation still holds. On a total below 10, whatever energy the spell didn't spend on the task ends up as chaotic aftereffects and side effects nearby, as the DM decides. A fireball rolls a 5: his shirt is on fire, and now the tapestry is too. Only on a full failure (1 or less) does the energy come back at the caster, as Burn or as damage at the DM's call.

**Natural 1.** On top of whatever the total says, a natural 1 is a mishap: some of the energy goes somewhere it shouldn't, as the DM decides, and the Residue is doubled.

The roll never changes the cost or creates energy. A great roll shapes the same Motes better, and a bad one wastes them.

### The mana pool

Casters can store Motes inside their own soul and carry them into dead zones. That store is the **mana pool**. Casting from it works like casting from the Flux: it still counts against capacity and still causes Burn.

| Stat | Base value | Level 1 | Level 5 | Level 20 |
| --- | --- | --- | --- | --- |
| Capacity (Motes per action) | Half level (round up) + modifier | 4 | 7 | 15 |
| Pool (Motes stored) | 4 x level | 4 | 20 | 80 |
| Regeneration (refill rate) | Proficiency bonus Motes per 10 minutes, drawn from the local Flux | 2 | 3 | 6 |

Regeneration pulls from the place's Flux pool, so it stops in a dead zone and competes with other casters in a thin one. A long rest in a place with Flux refills the pool completely. As a check, a level 5 caster refills 20 Motes in a little over an hour. Regeneration can never take more than the place has left: once a place's pool runs dry, the casters in it share only its hourly refill.

**Opening Chokras.** Training opens Chokras, the soul-side ends of the body's portals. Each opening gives one permanent upgrade, chosen by the player:

- **Wider channel:** +1 capacity. It can be taken at most twice, because capacity is the limit everything else is balanced against.
- **Deeper well:** pool + your level.
- **Faster draw:** +1 Mote per 10 minutes to your draw rate. It raises how fast you pull, not how much the place holds.

A caster can open one Chokra at levels 1, 4, 8, 12, 16 and 20, after a month of training or a meaningful event in play (a ley-line vigil, a near-death experience, a mentor's rite), up to six in total. These are starting values.

Half-casters (Paladin, Ranger, Artificer) use half their level. Classes keep their flavor through one tweak each, for example Sorcerers get 3 Motes per Life Force die instead of 2, Druids get double sympathy caps from nature, and Warlocks owe no interest on their first few borrowed Motes per day.

**Tuning.** A caster can be tuned to a kind of magic: fire, cold, lightning and force, life, mind, or any other the DM allows. There are three ways in, and all are equal: born with it (a class or bloodline that starts tuned), training (a month under a tuned teacher), or self-improvement (taking it as the upgrade when opening a Chokra). Tuning to mind or life lowers the portal impedance one step, as described in those sections. For other kinds, the caster counts as their own small sympathetic medium: the cost is halved, with the saving capped at their proficiency bonus per action, and it stacks geometrically with other discounts.

### What a place holds

| Place | Flux pool (Motes) | Refill per hour |
| --- | --- | --- |
| Dead | 0 | 0 |
| Thin (crypts, cities) | 15 | 5 |
| Ordinary | 40 | 10 |
| Rich (old forests, teeming marshes and reefs: Flux follows life, not raw physical energy) | 100 | 30 |
| Ley line | 250+ | 60 |

Every caster within 100 ft draws from the same pool. Where one place's pool ends and the next begins is the DM's call, made on the fly.

## Metals and the Thrum

Metal is a pipe for the Thrum. Flux flows along it like magnetic fields in iron, and the metal it's made of decides what happens to the energy inside. Metals never create energy: the best they can do is focus it.

**Every metal conducts.** If you touch metal that is also touching your target, you cast at touch range (x1) along it. A spear stuck in a ghoul, a chain around a prisoner and an iron railing that runs to the door all count. Two limits:

- **Resistance.** The pipe leaks. Like a long wire, metal has resistance: a spell loses half its energy over a set distance, and the losses stack, so twice that distance leaves a quarter. Purity sets the distance. Silver and gold lose half every 200 ft. Ordinary worked metal (copper, bronze, steel, a spearhead) loses half every 100 ft. Rusty, corroded or scrap iron loses half every 50 ft. As a guide, about 85% arrives at a quarter of that distance and about 70% at half of it. Round the loss down, so a 1-Mote trigger still gets through a spear haft and short runs stay nearly free. The lost energy heats the metal along the way.
- **Thickness.** A conductor carries only so much per action. A wire carries 2 Motes, a rod, spear or sword carries 10, and a beam, railing or anchor chain has no practical limit. Push more through and the excess bursts out as heat where the conductor starts, burning the caster's hand and melting a wire.
- **Both ends are live.** Anyone touching the metal is part of the circuit. An enemy grabbing the other end of your chain can cast back at you just as cheaply.

Each metal below does one thing to the Thrum:

### Lead: swallows

Magic can't pass through lead. Any energy that hits it turns to heat in the lead.

A lead-lined box is a dead zone inside, so it hides magic items, stores crystals and charged gold safely, and holds a captured caster. A lead shield blocks a spell, but it's too hot to hold the next round.

### Iron and steel: pull

Iron pulls the Thrum toward it like a magnet and bleeds it off. A spell passing within 5 ft of a large iron mass bends into it unless the caster pays x1.5 to steer past. Spells cast through iron, or while wearing it, double their Loss.

Casters avoid plate armor. A knight in steel draws spells aimed at whoever stands beside them, and an iron portcullis shields the people behind it. Cold iron is the classic charm against spirits.

### Bismuth: pushes

Bismuth is iron's opposite. A spell passing within 5 ft of a large bismuth mass veers away unless the caster pays x1.5 to force it through. The deflected energy still goes somewhere, at an angle the DM chooses.

A bismuth shield or shrine turns spells aside, but a ricochet can hit bystanders. Iron and bismuth together can bend a spell around a corner. Bismuth is rare: it comes a few ounces at a time from lead and silver mines, and it's too brittle to make into wire.

### Copper and bronze: carry

Copper carries the Thrum cleanly and does nothing else.

This is the material for cables, traps and ritual circles. A copper wire under a rug makes a magical tripwire, and a copper line lets a caster work on someone without touching them.

### Silver: focuses

Silver cuts the Loss on Motes shaped through it by a percentage set by its grade (see Focus grades and rarity).

Silver focuses are prized because they cut Burn. A silver blade carries a spell into its target with less waste.

### Gold: stores

Gold holds a charge: 2 Motes per pound (50 gp). It starts empty, and a caster charges it from their pool or the Flux, up to capacity each action. Drawing from it works like any other source, so it counts against capacity and causes Burn.

Gold is valuable because it holds magic, and a dragon's hoard is a battery. Charged gold sells for barely more than plain gold, since any caster can charge it. It only fetches a real premium where there are no casters around. Loose charged gold is a liability: it hums so casters within 30 ft can sense it, anyone touching it can draw from it, and in a dead zone it bleeds 1 Mote every 10 minutes. Carry it in a lead-lined purse, or wear it as a loop.

### Mercury: holds a shape

Mercury is a liquid mold. Casters pour a shaped spell into it over several actions, up to capacity each action. When the vessel breaks, or the caster triggers, the whole spell releases at once, for free and outside capacity. The spell was shaped at touch range, so it pays no distance multiplier. A held spell leaks 1 Mote every 10 minutes.

Flasks are spell grenades and remote triggers, and basins power the greatest works. Most of the mercury is lost when the vessel breaks, and it's poison: a broken vessel calls for Constitution saves, and a carried flask can break on a critical hit or a bad fall. Gold stores fuel, while mercury stores a finished spell.

### Shapes and vessels

**Closed loops hold the Thrum forever.** A loop never bleeds, even in a dead zone, and only its wearer can draw from it.

- Gold ring, bracelet or anklet: 2 Motes, despite its tiny weight.
- Gold circlet or torc: 5 Motes.
- Loops close together interfere and cancel, so ring-mail and stacked rings don't work. A caster can wear five working loops at most: one ring or bracelet per arm, one per ankle, and one circlet or torc on the head or neck. Rings, bracelets and anklets hold 2 Motes each, so the maximum is 13 Motes.

### Focus grades and rarity

Silver focuses and tuned gems come in grades. The grade sets the percentage: for silver, how much Loss it removes; for a gem, how much it cuts the cost of its energy type. High grades should be rare finds, not shop stock.

| Grade | Effect | Rarity | Typical price | Examples |
| --- | --- | --- | --- | --- |
| Crude | 10% | Common | 10 gp | Silver-plated ring, cloudy garnet |
| Fine | 20% | Uncommon | 100 gp | Sterling wand, well-cut ruby |
| Superior | 30% | Rare | 1,000 gp | Pure silver staff tip, flawless sapphire |
| Masterwork | 40% | Very rare | 10,000 gp | Elven-drawn silver, ley-grown emerald |
| Legendary | 50% | Legendary | Not for sale | Named relics |

**Discounts stack geometrically.** Each extra discount applies to what's left, never to the original cost. A Superior ruby (30%) used beside a forge (sympathy halves, 50%) cuts a fire spell's cost to 35%, not 20%. Two Fine silver pieces (20% each) remove 36% of the Loss, not 40%. Even a Legendary relic stops at 50%, so nothing ever reaches 100%.

**Mercury vessels:**

- Flask (1 lb, 25 gp): 10 Motes. Thrown as a ranged attack, 20/60 ft. On a miss it bursts a few feet off target.
- Jug (5 lb): 30 Motes. Needs two hands and throws only 10/30 ft.
- Basin: 100 Motes and can't be moved. A circle of casters fills it over an hour, and a heavy copper bar carries the release (a wire would melt) to a patient or workpiece. A basin can regrow a whole body, but making the flesh alive still takes Life Force dice.

**Rules of thumb for the DM and LLM.**

- Find the metal, then ask which way it pushes: does it carry, pull, push, swallow, focus, store or hold a shape?
- Shape matters as well as material. Closed loops hold energy in, and open shapes such as wire, rods and coins leak or pass it along.
- Iron's pull always picks the largest nearby mass. When in doubt, the spell hits the most iron.
- Energy that metal soaks up becomes heat in the metal. A lead shield hit by 6 Motes is too hot to hold next round.

## Gems and the Thrum

If metal is a pipe, a gem is a lens. Gems are the crystals named in the Source law. They hold energy locked in their lattice, and each kind is tuned to one form of energy.

**Every gem stores.** A gem holds 1 Mote per 25 gp of value, so a 100 gp ruby holds 4 and the 40-Mote crystal in Test run 3 is worth about 1,000 gp. Unlike gold, a gem is sealed: it doesn't hum, doesn't bleed in dead zones and can't be drawn by a stranger's touch. Charging and drawing work like gold, and drawing counts against capacity and causes Burn.

**Every gem tunes.** A charged gem held as a focus counts as a sympathetic medium for its energy, cutting the cost of spells of that type by its grade's percentage (see Focus grades and rarity). The saving per action is capped by the Motes it holds. A ruby with 4 Motes makes fire spells cheaper even underwater.

**Gems crack.** Straining through a gem, or drawing it to zero in one action, takes a DC 10 spellcasting check. On a failure it cracks and releases everything left in it at once, a raw, untuned blast at the gem's location.

### The tunings

- **Ruby: heat and fire.** The war-caster's stone.
- **Sapphire: cold and water.** Pairs with heat loans for cheap ice and fog.
- **Topaz: lightning and force.** Good for Release triggers and pushing objects.
- **Emerald: life.** Cuts the Mote cost of regrowth when healing. It doesn't supply life force, which still comes from Life Force dice.
- **Amethyst: mind.** Lowers the impedance of mind magic one step (untuned to tuned) while held. This makes amethysts the most sought-after gems in The Thrum.
- **Diamond: any energy, but it only stores.** A diamond tunes nothing, but it holds twice as much per gp and is the only gem that never cracks.

**Rules of thumb.** Metals move the Thrum; gems hold and tune it. A gem set in a silver ring combines both: the silver's Loss cut plus the gem's tuning, stacked geometrically. Players who combine a material with a shape this way are using the system as intended. Every store, from the mana pool to gold, gems and loops, releases through the caster's capacity and causes Burn. Only mercury releases a finished spell outside it.

## How the LLM advises the DM and players

The DM stays in charge. The LLM is a physics engine that the DM and players can both consult. At the table, the DM types the situation and what the player is trying to do, and the LLM answers what the laws say happens. Between sessions, players can test ideas in a separate session of their own, but only the DM's session sets rulings.

**What the DM gives it:** the caster's level, modifier and current Burn; the place's Flux pool; what is nearby (water, fire, gas, height, crowds); and the player's intent in plain words.

**What it gives back, every time, in this order:**

1. **Energy path.** Where the Motes come from and where they end up, including waste.
2. **Cost.** One line of math: conversions, then distance, sympathy and focus discounts, rounded up (see Loss).
3. **Can they do it?** Against capacity, the Flux pool and Burn. If not, the closest version that works.
4. **What happens.** The outcome, including side effects the laws imply but the player didn't ask for.
5. **Ledger update.** Flux left, Burn taken, debt owed.

**Precedent log.** Every ruling gets a one-line entry ("Igniting a gas pocket: 1-Mote trigger, releases about 16 Motes across 20 ft"). The log is pasted back in each session, so the same trick always works the same way. This is what lets players build their own systems: once a ruling exists, they can rely on it. Answers from a player's side session go in the log only after the DM confirms them.

Starter prompt for the LLM:

```
You advise the Dungeon Master of a D&D campaign where magic obeys seven laws: Conservation, Source, Loss, Distance, Sympathy, Release and Saturation, plus the constants (casters work at capacity unless the player says they strain, which triggers the over-capacity check), heat loans, metals, mana pool, mind and Life Force rules below. You are a physics engine, not a storyteller. When the DM describes a situation and a player's intent, answer in five parts: Energy path, Cost (one line of math), Can they do it, What happens (include side effects the laws imply), Ledger update. Never let energy appear from nothing or vanish. Reward clever use of stored energy, sympathy and the environment. Follow the precedent log exactly; if a new ruling is needed, add a one-line precedent at the end. If the laws don't cover something, say so and propose the simplest rule consistent with them.
```
