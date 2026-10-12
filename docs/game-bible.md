# Tomes and Gnomes — Game Bible

**Status:** proposal, draft 1 (2026-10-11). Nothing here is locked. No technology has been chosen, on purpose: this document comes first.

**Who it is for:** the two of us. First as a proposal to review and argue with, then as the reference we check feature ideas against.

## How to read this

Every section is marked with where it stands:

- **Vision** — the founding idea, as Oren described it. Challenge it, but it is the starting point.
- **Proposed** — an elaboration drafted to fill a gap. Neither of us has agreed to it yet. Treat each one as a suggestion to accept, change, or strike.
- **Open** — a question we have to answer together. They are collected in [Open questions](#open-questions), most important first.

When we settle something, move it to **Agreed**, and add a line to the [Decision log](#decision-log).

---

## The pitch

**Vision.** A new take on the multi-user dungeon: a turn-based strategy game set in a shared, living world that players explore hex by hex, like an old-school hexcrawl.

You pick a place to call home. Then you go out — to complete quests, loot enemies, stumble on treasure, and earn experience — and you try to make it back alive. Nothing you gained counts until you are home. Getting there means actually travelling the route, hex by hex and location by location, while other players, creatures and the world itself may get in your way.

In one line: **a hexcrawl where every trip out is a bet, and getting home is the game.**

## Pillars

**Vision.** These are the ideas everything else should serve. A feature that does not serve one of them needs a good reason to exist.

1. **The journey home is the game.** Loot and experience are only promises until they are banked at home. Tension comes from the distance between where you are and where you are safe.
2. **The world is a real place you have to cross.** No teleporting past the map. Hexes connect to hexes; each hex has its own map of locations; routes, distance and terrain matter.
3. **The world is alive and shared.** Other players and non-player creatures act in the same world, and can interrupt your plans — including your trip home.
4. **Your choices decide whether you make it.** Survival comes from decisions — how far to push, which way to go, when to turn back — not from reflexes.
5. **The world keeps changing.** A world clock, with a reason in the fiction, refreshes the world on a cadence so that it never becomes a solved puzzle.
6. **Play in layers.** The game works for someone playing attentively turn by turn, and for someone checking in from a phone, because time runs at more than one speed.

## The core loop

**Vision.**

1. **Choose a home.** At the start, each player picks a place in the world to call home.
2. **Venture out.** Travel from hex to hex, and through the locations inside each hex.
3. **Gain.** Complete quests and objectives, defeat and loot enemies, find treasure, earn experience.
4. **Decide.** Push further for more, or turn back with what you have.
5. **Return.** Navigate the whole way home. Anything might attack you on the way.
6. **Bank.** At home, spend money, store treasure, spend experience. Then go again.

**Proposed.** The loop's emotional shape is *greed against distance*: every step outward makes the haul bigger and the walk home longer. The best features will sharpen that trade-off; the worst will let players skip it.

## The world

### Hexes and locations

**Vision.** The world is a grid of hexes. A player is always "in" a hex. Each hex can contain a map of locations and things to do. Moving through the world means crossing hexes, and crossing a hex means moving through its locations.

**Proposed.**

- A hex is a region with a character of its own: terrain, danger level, what lives there, what can be found there.
- A location is a place inside a hex — a ruin, a crossroads, a cave mouth, a village. Locations connect to each other by paths, and some connect across the hex border to a neighbouring hex.
- You do not see a hex's map until you explore it. What you have charted is knowledge you carry (see [Tomes](#where-the-name-comes-in)).
- Hexes differ in size and density: a quiet stretch of road might be three locations, a ruined city thirty.

### Home

**Vision.** Home is where gains become permanent: money is spent, treasure stored, experience spent. It is the safe end of every journey.

**Proposed.**

- Homes are settlements in the world, not private instances. Several players can share one, which gives neighbours — and rivals — a reason to know each other.
- Home is safe. Whatever happens to PvP elsewhere, it does not happen inside a home.
- Where you choose to live matters: a home near rich, dangerous hexes means short, deadly trips; a home in quiet country means long, safer ones.

## Time

**Vision.** Time passes in turns, at three speeds layered on top of each other.

| Layer | What advances | Who feels it |
| --- | --- | --- |
| **Turn** | A player's individual actions: move, fight, search, talk. An attentive player may take several in a row. | The person playing right now, in a browser or on a phone |
| **Hex tick** | The state of a hex: creatures move, events unfold, things left behind decay or are found. | Everyone in or near that hex |
| **World clock** | The freshness of the whole world: what is where, what is new, what is gone. | Everyone |

**Proposed.** The layers are what make the game playable at different levels of attention:

- *Attentive play* lives at the turn layer: a focused session where you take many turns back to back.
- *Check-in play* lives at the hex layer: you set an intention — travel this route, rest here, keep watch — and come back later to see what the hex did with it.
- *The long game* lives at the world clock: seasons of the world that reward returning players with something new.

How fast each layer runs in real time, and how the layers hand off to one another, is the largest open design question we have. See [Open questions](#open-questions) 1 and 2.

### The world clock and why it exists

**Vision.** The world clock dictates the freshness of the world, and there is a lore reason for it: magical rifts in the fabric of the universe mean things keep mysteriously changing on a certain cadence.

**Proposed.**

- Call each cycle of the world clock a **Turning**. When the world turns, rifts open and close and parts of the world are rewritten: a cave that was empty holds something new, a road is gone, a ruin has appeared where there was forest.
- Homes are stable. Settlements stand where the fabric is thick, which is why people live there, and why they are safe.
- A Turning does not wipe players. What is banked at home stays banked. What changes is the world out there.
- The Turning gives old knowledge a shelf life: a map charted two Turnings ago may be wrong in ways that get you killed. That makes fresh exploration valuable every cycle, including to veterans.
- People in the world know about the Turning and plan around it. It can drive quests ("get this out of the vale before it turns").

## Risk and extraction

**Vision.** At any point, other players or non-player creatures might attack and ruin a journey home. Making it back alive depends on the player's choices.

**Proposed.**

- **Carried versus banked.** Everything you hold is in one of two states. Carried things — loot, coin, unspent experience — are at risk. Banked things are safe at home.
- **Losing.** If you fall before reaching home, you lose what you were carrying. What you had banked is untouched. Whether the character itself survives is [Open question](#open-questions) 3.
- **What falls stays in the world.** Dropped loot remains where you fell, for others to find, until the hex or the world clock clears it. Someone else's bad day becomes your lucky find.
- **Readable danger.** Players should be able to tell roughly how dangerous a hex is before committing to it. Losing to a risk you chose is a story; losing to something you could not have known is a reason to quit.

## Conflict

**Vision.** Threats come from both the world (NPCs and monsters) and other players.

**Proposed.**

- Combat is turn-based and decided by choices and preparation: positioning, what you brought, when you run.
- Running away is always a real option, and often the right one. A game about getting home should make retreat a skill.
- Player-against-player conflict is the feature most likely to make or break the game. Unlimited, it drives away everyone but the most aggressive players; absent, the world loses its edge. This needs its own conversation: [Open question](#open-questions) 4.

## Progression

**Vision.** Players build experience and spend it at home, along with their money and treasure.

**Proposed.**

- Experience is earned in the field but only spent at home, so a long, successful expedition is carrying a great deal of unrealised growth — more to lose, more reason to get back.
- Growth should widen what a player can attempt (further hexes, new approaches) more than it inflates numbers, so that new and veteran players can share a world.
- Home itself can grow: storage, services, and things that make the next expedition different.

## Quests and things to do

**Vision.** Hexes contain things to do: quests and objectives, enemies to loot, random treasure to find.

**Proposed.**

- Three sources of activity: *authored* quests with a story, *world-driven* objectives that arise from the current state of a hex, and *discoveries* found only by exploring.
- Quests should pull players away from home and into decisions about route and risk. A quest that can be finished on the doorstep does not serve the loop.
- The Turning refreshes what is available, so the quest board is never permanently exhausted.

## Where the name comes in

**Proposed — and the part most worth your reaction.** The vision above does not yet say what tomes or gnomes have to do with it. A suggestion that ties both to the core loop:

- **Gnomes** are who the players are: small folk in a world that is very large and not built for them. It makes the journey home feel long and the dangers feel big, and it earns the game a tone that is warm and wry rather than grim.
- **Tomes** are what you carry and what you keep. In the field you write a field tome: the maps you chart, the things you learn, the experience you earn. It only counts when it is shelved at home. Lose the tome on the road and you lose what it held.
- This makes the name describe the game: the gnomes go out, the tomes come back — or do not.
- It also gives the Turning something to bite on: tomes go out of date when the world turns.

## What this game is not

**Proposed.** Guard rails, to be argued over:

- **Not a twitch game.** No outcome should depend on reaction speed.
- **Not a game you can lose while asleep without having chosen the risk.** Whatever we decide about offline characters, the player must have accepted the exposure.
- **Not a solved map.** If the best route is the same every week, the world clock is not doing its job.
- **Not a grind.** If the efficient way to play is to repeat a safe trip forever, the loop is broken.
- **Not pay-to-survive.** Nothing that affects whether you make it home should be for sale.

## Open questions

Ordered by how much else depends on the answer.

1. **How do turns work when several players share a place?** Do they act at the same moment, in order, or on a timer? What happens when one of them is slow? This shapes almost everything about how the game feels.
2. **How fast do the three layers run in real time?** Is a hex tick minutes or hours? Is a Turning a week or a season? And what does a player who checks in twice a day actually do?
3. **What happens to your character when you stop playing mid-journey?** Do they vanish, make camp, or stand there exposed? And what does falling cost beyond what you carried — is the character gone, or back home with empty pockets?
4. **What are the rules for player-against-player conflict?** Everywhere or only in some hexes? What can be taken? What stops a strong player from camping outside a home?
5. **Is there one world, or many?** One shared world for everyone, or separate worlds of a limited size? How many players should a hex feel right with?
6. **How much of the game is text?** The MUD heritage suggests text-forward play with maps; a strategy game suggests a board you look at. Where do we sit between the two?
7. **Solo or party?** Can players travel together, share loot, and defend each other? Are there formal groups tied to a shared home?
8. **How is the world made?** Hand-authored, generated, or a mix — and does the Turning rewrite content by rule or by hand?
9. **Do the tomes-and-gnomes ideas above fit**, or does the name mean something else to you?
10. **What is the smallest version worth playing?** One hex, one home, one creature, one trip out and back — is that enough to test whether the journey home is fun?
11. **Who is this for, and how do they find the time?** Ten minutes on a phone, an hour at a desk, or both?
12. **Does it ever cost money, and if so, for what?**

## What the design asks of the technology

Not decisions — the stack is still open. These are the demands the vision makes, so that the stack conversation starts from the game rather than from habit:

- A single shared world whose state persists and keeps changing while players are away.
- Time that advances on a schedule at more than one speed, independent of any player being connected.
- Many players acting on the same hex, with one agreed outcome.
- The same game playable in a desktop browser and on a phone.
- Rules that run somewhere players cannot tamper with, since loot can be lost to other players.
- A way to tell a player that something happened to them while they were away.

## Glossary

| Term | Meaning | Standing |
| --- | --- | --- |
| Hex | One region of the world map; contains a map of locations | Vision |
| Location | A place inside a hex | Vision |
| Home | The safe place a player chooses, where gains are banked | Vision |
| Turn | One player action | Vision |
| Hex tick | One step of a hex's own state | Vision |
| World clock | The cadence on which the world refreshes | Vision |
| Rift | A tear in the fabric of the world; the cause of change | Vision |
| Turning | One cycle of the world clock | Proposed |
| Carried / banked | At risk in the field / safe at home | Proposed |
| Extraction | Getting home alive with what you gained | Vision |
| Field tome | What a gnome records and carries until it is shelved at home | Proposed |

## Decision log

| Date | Decision | Decided by |
| --- | --- | --- |
| 2026-10-11 | Game design is written down and agreed before any technology is chosen | Oren |
