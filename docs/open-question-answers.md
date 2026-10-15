# Tomes and Gnomes — One World, Many Timelines

**Status:** Derek's proposal in answer to the open questions in draft 1 of the [game bible](game-bible.md) (2026-10-14). Nothing here is agreed yet. Once we agree on something, it moves into the bible as **Agreed**, with a line in the [Decision log](game-bible.md#decision-log).

**How to read this:** it describes the game as one picture rather than question by question. A paragraph that answers one of the bible's [open questions](game-bible.md#open-questions) carries the question's number above it, like *Q5*. [The index at the end](#where-each-question-is-answered) lists where each question is answered. The words loot, gear and cards are used somewhat interchangeably: loot becomes gear, and gear is represented by cards.

## The idea in brief

Every day, the world splits into many copies. In each copy, players live out a day of the season's story and bend it with their choices. At the end of the day, the copies collapse back into a single timeline, shaped by what happened most often across all of them, and the day becomes a chapter of a novel everyone reads going into the next day. By the end of the season, the chapters make a book: the story of a world built together by everyone who played.

---

## Part 1: One world, one story

### A season begins

*Q8*

Each season starts from a hand-authored campaign: the high-level story, the major events that will happen whatever players do, and the world's starting state. Working with AI, we will have mappped out a set of **archetype event patterns**: the shapes the story could take, described abstractly in terms of the emotional direction or effective outcomes of events, i.e. an anticipation of all the most common ways a choose-your-own-adventure book could branch. The world is reasonably ready for wherever players take it.

*Q8*

From those patterns we generate a large library of art, and the AI picks whatever fits most closely the direction a story has taken. The library doesn't need to be endless, because the world's rules limit how far players can shape the overall game narrative.

*Q2 · Q8*

A season lasts about three months and ends in a **Turning**: rifts reshape the land and a new campaign begins. Season dates are targets rather than fixed dates, so we can prepare each one at a pace we can keep up. Within a season, details vary by the day, but the shape of the land holds, so charting it in your tome stays worth doing. Places you charted during a day remain charted, with details updated to match the collapsed timeline. A full season gives players time to complete their tomes, including the hardest-won details, and to show them off.

### Many timelines, collapsed into one

*Q5*

Each day, the world runs as many separate **instances**, all from the same starting state and all heading toward the same major events. Inside them, players push the story in different directions, and the AI judges how far each instance can bend while still arriving at those events. [Part 3](#part-3-world-instances) covers how instances work.

*Q2 · Q5*

At the end of each day comes the **Collapse**. By then the instances might range from moderately similar to vastly different. Using the archetype patterns, we match what happened in each one by its emotional direction and outcomes, find the patterns that occurred most often, and collapse every timeline into one: a single history weighted toward what most players made happen. In the lore, it is the magic beneath the world tearing and restitching reality. What happened in your own timeline that didn't survive the collape lives only in your memory, the game's version of the Mandela effect. The collapsed world becomes the starting state for the next day.

Players then discover the new state of the world and its rewritten history as the next chapter of a book: novel-quality writing, the same book for everyone, honoring every timeline where feasible, while settling on the most common one for the shape of major events. The more players that made something happen, the more it shapes history. The will of the yesterday's many has manifested the starting state of the day to come.

*Q8*

A new day also brings news of what has happened on the map since a player's last visit: rumors of dragon attacks circulating from the mountains to the west, say, or the collapse of a bridge into a town, now in need of repair. This is how the season advances its story with the shared events planned for it, building the overarching story of the campaign.

### The book of the season

*Q12*

At the end of a season, its chapters form a novel aimed at being genuinely good, written out of the collective effort of strangers building a world together online. Players can buy a high-quality printed copy, and everyone gets the complete digital book free, forever, on any account.

Every book joins a permanent public archive/library, **the Great Library of Tomes & Gnomes**, capturing the struggle, betrayal, war and friendship of each season, where printed copies can be purchased. We might consider selling the books without claiming copyright or restriction over how the digital copies of the story are used (it might get messy otherwise given that players helped shape the story direciton and the books are self-announced as AI-generated). But even without copyright protections, the Library could be viable way among others to support the game through revenue streams.

### Imagination, within the world's rules

*Q6*

Non-player characters, and a narrating voice from the sky that follows your progress across the map, are generated by AI as the story moves. That puts an enormous range of story directions at players' disposal. When a player wants something, the world finds a way to honor the spirit of it to the degree it is feasible, and with every other player's experience in mind. As mentioned, our AI has access to a vast library of graphical assets to choose from.

Where players are limited: they don't write the world's rules with their imagination. For example, this is high fantasy: no technology or ideas can be introduced that break it. You can imagine flying over a mountain. You can't invent a spell that turns the mountain into a lake of lava, conveniently killing every player on it, or bulldoze a town to make space for 21st century shopping mall. Common sense limitations, but worth mentioning as we'll need AI skills to be the judge of what is and isn't allowed.

*Q4*

During PvP interactions, players are subject to a standardized set of rules and allowed actions aimed at promoting consistency and balance during combat. A flying character, for example, like every form, has a fixed set of strengths and weaknesses in combat. PvP is the chess-like, strategic part of the game, and a stable experience across worlds.

The world should be a safe place for healthy imagination, and vigilant against players who set out to sabotage what others are building. Holding that line in something this dynamic may require several AI agents to split tasks and audit results, with failsafe behaviors for whenever mistakes occur.

---

## Part 2: Playing a run

### The board

*Q6*

Story progression and encounters with NPCs play out MUD-style: decisions and story, rolling for outcomes, with no action-point limits. The board view appears only for PvP encounters: when PvP combat starts, the curent hex location transforms into an omnidirectional board overlaying an environment where the characters battle, and every move costs action points and adheres to units of measurement on the grid.

*Q2*

Hex ticks are driven by interactions, rather than a clock: actions inside the hex, or events in other hexes its state depends on.

### PvP is always on

*Q1 · Q4*

PvP is always on. You can find and ambush other players, and they can do the same to you. What keeps this fair is everything else in this part: fleeing is always an option, lighter characters move farther, dropping loot buys speed, fleeing in proximity to home brings a stamina boost, zones keep veterans from preying on newer players (explained later), and features like setting camp and Auto Play let you step away safely.

*Q1 · Q4*

Combat starts with an attack, which costs the attacker an action point. Unless the defender has a spell/card that grants first strike when attacked, the attack lands, and only then does the defender choose whether to fight or flee. Without that first hit, a player could flee every attempt to engage them and play the game with no PvP risk at all.

*Q1 · Q6*

In combat, each party takes all of its actions before play passes to the next, leaving room for teammates to combine abilities. PvP turns run on a short timer, maybe 1–2 minutes per turn(?).

When accepting combat, the attacker lands the opening hit, but the first full turn goes to the player under attack. Players only have the option to flee at the start of each of their turns during combat before other turn actions have been taken. For example, they can't complete a turn where they landed a bunch of damage, and then flee without allowing the opponent a chance to take their turn in response.

### Cards

*Q6*

Actions are cards. These are satisfying to collect as a loot type. Each character brings a 20-30 card deck into a run (with 30 being the max). A free standard deck is open to everyone: play it whole, or use standard cards to fill out a deck of your own extracted cards. Every player starts a season with 20 standard cards, whether or not they've extracted anything yet. Some cards are single-use and some have cooldowns; moving and basic attacks can be repeated freely, though they still cost action points. Standard cards are never single-use. When carrying gear (cards), you can choose whether to place a card into your playable deck or into your backpack as an inventory item outside of your playable deck. Either choice adds weight to your character, affecting their agility and stamina.

Two ways to play the cards, which Derek likes equally:

- **Every card available each turn,** limited only by your action points, the card's cost and any cooldown (as in *Battlemarked*). This essentially uses cards as a visual representation of standard RPG actions. In this approach, starting with 20-30 cards is excessive and should likely be a much lower number.
- **Deck building:** If we do deck building, players would draw a hand each turn and play from it. Here, extraction is ultimately about building a better deck.

Later ideas: temporary alliances between parties mid-battle during multi party combat, with cards that respond to them (e.g. "If your party becomes outnumbered due to an alliance of opponents, gain 5 strength on physical attacks until the opposing alliance ends"); Some cards can be played outside of PvP, like if you are fleeing, you might play a card that creates a barricade that slows your pursuer down by forcing them to spend time clearing it; or you might cast a spell to create a mirror image of your party that runs the other way when fleeing; or one that disguises your party that needs a reveal spell to counter (like transforming into trees or rocks or mimicking something in the environment more dynamically).

Using cards also opens the possibility of a physical trading card game down the line where extracting a card in a run unlocks a code to order the real one. This is another possible revenue stream for T&G.

### Zones

*Q4*

The map is divided into numbered zones: zone 1, zone 2, and so on (or named, just using numbers for now). Your **zone rating** comes purely from the total value of the gear/loot you carry, and to enter a higher zone, it must exceed that zone's threshold. You can't initiate combat with a player rated in a lower zone than you, but lower-rated players can attack you. That lets new players share a server with veterans wihtout being under constant threat from the get-go.

*Q4*

For the first 30 minutes of a fresh run, a party can't attack or be attacked. Players who join a party already in play get no such window (see [Joining a game in progress](#joining-a-game-in-progress-and-spirits)). The exact length should be the shortest one that makes veterans gain more from rushing into higher zones than from lingering in zone 1 to prey on new players; 30 minutes is a placeholder.

*Q4*

Zones also give a desperate player one more way out of a chase. Drop enough loot to lower your zone rating, and you become immune to your pursuer, unless they drop enough loot to follow you down. Lowering your rating has a cost: for 30 minutes afterwards you can't be promoted back to the higher zone, regardles of how quickly you acquire new loot, so players can't abuse the rule by straddling the line. Meanwhile, the loot you dropped lies unprotected in the higher zone area that you can no longer access for those 30 minutes.

A character occupying space in a zone rated above their own disturbs the Rift magic there. **Rift spirits** rise from the earth, aggressive only toward that character. They lie in wait and attack if the character moves in any direction other than a straight line to the exit into the lower zone. Once the character crosses into the lower zone, the spirits sink back into the earth. That also keeps your dropped loot out of your reach until you're promoted again.

### Running away

*Q4*

Fleeing is always an option, and weight decides how well it goes: the less you carry, the farther each move action takes you. Drop loot to outpace your attacker, and they must slow down to pick it up (game dialogue cannot be skipped so collecting dropped loot adds real time you can't dodge, though for reference game dialogue can be interupted when attacked by another real player). Drop enough loot, and you may fall into a lower zone rating, out of their reach (see [Zones](#zones)). A mini map always shows which hexes within two in every direction hold other players, except players fleeing from you, who get a grace period off your map. Players fleeing near their home get a stamina boost, which makes an early retreat and the final leg of a journey more doable.

### What's at stake

*Q4*

Lose a fight, and the winner can take everything you carry except your **safe pocket** items: one or more inventory spaces in your backpack that you never lose, so weaker players can still grow their inventory, if more slowly, and keep a reason to play. Cards from the free standard deck are never lost either.

*Q3*

When you die, you resurrect. Your soul moves into your tome, which sprouts legs and races home across the map. At home, the page holding your soul works as a resurrection spell. Other players can strike a passing tome to shake loose some of the run's experience it holds, which dwindles to nothing as the tome nears home. To play again the same day, see [Joining a game in progress](#joining-a-game-in-progress-and-spirits).

### When you step away

*Q3 · Q11*

There are two ways to step away safely:

- **Make camp.** You can camp for as long as you like, and your party can't be attacked while camped, but you can't make camp with potential enemies nearby, only when your minimap is clear of enemy threats. Your camp can be discovered, though: after a grace period, every few hours other players or non-player characters who come across it can steal additional items while you sleep. The longer you stay away, the more you lose, and the weaker your position when you return.
- **Turn on Auto Play,** at any time. Your party follows your standing settings: the route to take, and how to behave when it meets other players (attack, or fight back when attacked, or flee), including making camp as a priority or switching from attack to fleeing if damage to your party reaches a set threshold during combat.

*Q3 · Q11*

If you go idle mid-run outside of PvP, your party makes camp after a timeout, or switches to Auto Play if potential enemies nearby prevent camping. If you miss a turn in PvP combat, Auto Play takes over on the following turn. Missing a turn is unfortunate and there's no reimbursement for it, but switching to Auto Play after one skipped turn is a generous failsafe, especially since your Auto Play settings may tell your party to flee the fight and make camp. If you return while combat is still underway, you can turn off Auto Play to take control again at any time.

During Auto Play, your party skips optional encounters and quests, leaving those for active players. When the story demands a decision during Auto Play, it chooses whatever fits best with the collapsed timeline emerging for that day. Auto Play can count as hex interaction, so it can advance hex state it passes through.

*Q1 · Q3*

Your **Auto Play settings**:

- **Route:** where to go, and whether to make camp or not upon arrival.
- **When attacked:** flee at once, or fight with a condition for fleeing later.
- **While fleeing:** drop loot to travel lighter, or retain all loot at the cost of moving more slowly. Choose to auto-use inventory items/cards that can assist with fleeing once underway.
- **After fleeing, or after winning a fight but taking damage past a set level:** carry on to your destination, or get clear of other players and make camp.

### Chat

*Q6 · Q7*

Every party has an ever-present **party chat**, visible only to its members, where you can talk with your companions about anything, like strategy during combat. When you're on the same hex as other players, you also share a **proximity chat** with them. AI companions can post to it spontaneously, and anyone can address a companion by name to bring it into the conversation.

You can block an offensive player from chatting with you, both in the current chat and in future ones. Outside of runs, matchmaking prioritizes keeping blocked players away from you, though this isn't always possible when you queue for a specific world rather than a random one.

### Tomes and gnomes

*Q9*

Re literal tomes and gnomes - love this! Small folk in a big world open up so much possibility: a colony of fire ants is a real threat, and an ogre is a HUGE one.

*Q9*

Players can sell their knowledge of the map to other parties mid-run for in-run gold or loot, and can also see how much of the map others have charted. Bought knowledge goes into your tome as **soul-linked pages**: learned, not earned. If the seller dies, the pages vanish. If they die because you betrayed them, your tome turns heavy for the rest of the run: you can't drop it, and it cuts your carrying capacity and slows your escape.

---

## Part 3: World instances

### Home and guilds

*Q4 · Q5*

Homes stand where the fabric of the world is thickest, so they're shared across every instance and untouched by the Collapse. A home is a social space, with a trading board, quest board, leaderboard and group chats.

One home contains many **guilds**. Guilds use an internal board to post recent attacks nearby the home territory on servers where guild members are actively playing. Guild members can donate gold toward defending the map outside their home on those servers. Dealing with players camping your return? The guild's collective gold can deploy AI enemies to attack them. Members can donate ahead of time or as the need arises between runs. Guild halls display how much gold the guild has donated collectively for the day and for the season. At the end of each day, unused donations are shared equally among everyone in the guild, not only those who donated. This is a way for guild members to support each other across their adventures in the multiverse.

Outside of runs, players can gift items from their inventories to other members of the same guild, but not to players in other guilds. If you defeat a guildmate during an FFA run, there's no damage to your reputation in the guild, and you can always gift them something good afterwards if you feel like it. To trade with members outside your guild, players list items for trade or sale on the home's communal boards.

### Who shares an instance

*Q5 · Q7*

An world instance holds at most 25 parties comprised of 4 characters each at any one time, or up to 50 FFA players depending on the game mode of the world. Parties are made up of human players, or humans with AI companions. Everyone in a party comes from the same home: party members extract to the same home, so a party with members from different homes couldn't stick together. Each AI companion acts for itself, with its own action points during combat, while its human sets the turn order and can talk strategy with it first, which also keeps turns moving faster than having the human control the actions of its AI party members.

*Q7*

To form a party, players open a public or private game lobby and invite specific players from their home or guild, or use **squad fill** to be matched with human party members at random, with AI companions filling any places no human is available for.

*Q7*

There are two game modes, kept to two so the player base isn't split too thinly to fill servers:

- **Free-for-all (FFA):** every party is a potential enemy.
- **Neighbor runs:** players party up with others from the same home, not necessarily the same guild, and all parties from the same home are allied. Guild members who want to play together form a party in the game lobby and enter a neighbor run together.

In FFA mode, no alliances hold, even within a guild: guildmates can fight and compete for resources without damage to their standing in the guild. Matchmaking prioritizes putting guildmates in separate FFA instances but doesn't strictly prevent them meeting, and guildmates who recognize each other can still choose not to fight.

*Q5*

In FFA mode, parties leaving from the same home enter at staggered times, since they aren't allied. Entry locations are naturally far apart for parties hailing from different homes.

### Joining a game in progress, and spirits

*Q3 · Q5 · Q7*

Players are not bound to one party or world instance from one run to the next. A player who wants to join a different game in progress, or come back to the same world after dying, has two ways in:

- **Join a party already in play,** taking an AI companion's place in a party that allows this in its settings. It may be a party of neighbors or guildmates, but always one from the player's own home. The player must bring gear whose value matches the zone the party is rated for, and gets no immunity grace period upon entering: they're in the game, in a party, geared for its zone, and ready for whatever comes.
- **Start a fresh run.** Players queue for a place in a particular instance or one at random, first come, first served, with server priority given to queued players that have remained on the same world instance throughout the day. A fresh run starts near home in zone 1, even if the gear you bring rates you higher, and gives your party 30 minutes in which it can't attack or be attacked.

*Q7*

When a player takes an AI companion's place, the AI isn't removed: it becomes a **spirit** somewhere on the map, keeping its character's personality and memories. Spirits move, and decide when to appear as friend or foe, at the AI's discretion, off-script. A companion that was aggressive or betrayed someone may return as a malevolent spirit and attack you when you least expect it; defeat it, and the calmed spirit may help you later. A companion that was treated well and played fair is likely to return as a helpful one.

### Gear caps

*Q5*

On a fresh run, the value of the gear you bring is capped at the highest total value you carried at any one moment in your earlier runs in that instance, whether or not you extracted with it.

Gear caps are instance specific and do not transfer when world hopping, so veterans with a high cap can't sweep the high-zone rewards of several worlds in one day at other players' expense. Players must learn each world zone by zone before they can bring their best gear into it, and get to know their worlds thoroughly along the way.

On the first day of a season, everyone's starting cap is the free kit, or gear worth no more than zone 1. After the first day a player has participated in a season, the highest cap you reached in any world during a day, reduced by 20%, becomes your starting cap the next day (capacity decay). It never falls below a zone 3 rating; a cap at or below zone 3 isn't reduced. Higher zones mean higher risk and higher reward, and maintaining a high cap requires consistent play from day to day. By design, extraction games favor players who are already strong by allowing them to start with more powerful gear, so capacity decay ensures they deserve to keep this privelage, which is good because we want true veterans to pull away from the pack early by progressing quickly into higher rated zones while the newbies explore the lower rated ones.

---

## Part 4: Building it

### The first version

*Q10*

One hex, one home, one creature with a round trip sounds good to me. From there we can iterate and test a PvP interation.

### Money

*Q12*

Nothing is pay-to-win. Alongside the season's printed book, players buy AI tokens from us to fill and refill their accounts, and play on the full, AI-driven servers described above.

Players without tokens play on **free servers**. There, the story follows a set of predefined directions from start to finish: a decision tree with far fewer branches than the AI-driven servers, advanced by fixed rules with no AI. Non-player characters have limited dialogue that eventually repeats. Free servers don't influence the Collapse.

If a player on a free server buys tokens mid-run, they can stay in their current run or leave to find a new one on an AI-driven server. If they leave while other human players remain on the free server, their characters are replaced by non-player characters that carry on playing under the same fixed rules.

### Platforms

Unity/C# - build for Xbox, Steam, desktop and mobile. Needs some research to ensure we are correctly setting ourselves up to build it once, deploy it everywhere. Cloudflare for CDN needs.

---

## Additional Open Questions

1. **Which card system:** every card available each turn, or drawing a hand from the deck? (or no card option - perhaps non-basic actions are spell pages in the tome)
2. **How long is a camp's grace period** before passers-by can start stealing items?
3. **Parties on the move at the Collapse.** A camp carries over from one day to the next, but what happens to a party that is actively (or auto) playing when the day ends? Idea: maybe a nightfall event occurs with a countdown to give players a heads up, and all players on the map either need to extract before the countdown runs out, or they will be forced to set camp when night falls regardless of what they were doing, including pvp. We need everyone to stop playing for the timeline Collapse to occur. Placing active players into a period of forced camping status until they can be transferred to a new server for the next day of content could work. They can also observe their new surroundings from the safety of their tent in the new world instance before emerging. If players were engaged in combat when night fell, their tents are next to each other which could be a fun dynamic. Who will be brave enough to break camp first? Will they book it, or try to steal from the other players camp or resume combat?
4. **The Great Library in the lore.** Should the Library be worked into the game's lore?

---

## Where each question is answered

| Bible question | Answered in |
| --- | --- |
| 1. Turns when players share a place | [PvP is always on](#pvp-is-always-on), [When you step away](#when-you-step-away) |
| 2. How fast the layers run | [A season begins](#a-season-begins), [Many timelines](#many-timelines-collapsed-into-one), [The board](#the-board) |
| 3. Stopping mid-journey, and death | [What's at stake](#whats-at-stake), [When you step away](#when-you-step-away), [Joining a game in progress](#joining-a-game-in-progress-and-spirits) |
| 4. Rules for PvP | [Imagination](#imagination-within-the-worlds-rules), [PvP is always on](#pvp-is-always-on), [Zones](#zones), [Running away](#running-away), [What's at stake](#whats-at-stake), [Home and guilds](#home-and-guilds) |
| 5. One world or many | [Many timelines](#many-timelines-collapsed-into-one), [Home and guilds](#home-and-guilds), [Who shares an instance](#who-shares-an-instance), [Joining a game in progress](#joining-a-game-in-progress-and-spirits), [Gear caps](#gear-caps) |
| 6. How much is text | [Imagination](#imagination-within-the-worlds-rules), [The board](#the-board), [PvP is always on](#pvp-is-always-on), [Cards](#cards), [Chat](#chat) |
| 7. Solo or party | [Chat](#chat), [Who shares an instance](#who-shares-an-instance), [Joining a game in progress](#joining-a-game-in-progress-and-spirits) |
| 8. How the world is made | [A season begins](#a-season-begins), [Many timelines](#many-timelines-collapsed-into-one) |
| 9. Tomes and gnomes | [Tomes and gnomes](#tomes-and-gnomes) |
| 10. Smallest version | [The first version](#the-first-version) |
| 11. Who it's for, and their time | [When you step away](#when-you-step-away) |
| 12. Money | [The book of the season](#the-book-of-the-season), [Money](#money) |
