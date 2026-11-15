---
description: Hoopa Rings pop up around the world and lead to the Sinnoh Underground, the Bell Tower, the Distortion World, Hyperspace Kalos and Ultra Megalopolis.
---

<!-- Sources: CobbleSafari wiki (cobblesafari.maxigregrze.fr, mirrored at wiki.cobblemon-realms.com/mods-guides/CobbleSafari/{hoopa_portals,sinnoh_underground,distortion_world,fight_boss}.html),
checked against test-server/config/cobblesafari/dungeon_spawn_config.json (every 900 s, chance 1.0, 32-80 blocks from a random player, overworld only, lasts 60 min, notify within 80 blocks;
underground weight 3, dungeon_jump weight 1, distortion weight 1; 0.4.0 configVersion 2 has enableNotification false), dimensional_timer_config.json (600 s per visit; dungeon_jump 1500 s from 5 Nov), dimensional_restrictions_config.json (no breaking/placing; underground bans bone meal;
distortion bans fireworks + mounting; dungeon_jump: no battles, mounting, elytra or Rotom safety), config/safarifee.json (undergroundEntryFee 500, jumpEntryFee 500, distortionEntryFee 2500, once per day), test-server/mods/cobblesafari-fabric-1.21.1-0.3.5.jar + 0.4.0 (lang names,
underground_treasure/*), Datapacks/cobblemonau_safari_tweaks (special fossils off; underground_final = 1 of 15 real fossils; giratina_core_trade = ball/EV/gender/IV/level crystals, no shiny reroll;
giratina_unique core 0.10; red_chain = 9 cores; hiker trades; hooh_unique Rainbow Feather 0.25, one random participant since uniqueLootCommunism false). Bell Tower (5 Nov 2026): csboss/hooh.json (300-600 s, ribbon 0.1),
hooh_common 1-3 Phoenix Ashes per participant, PhoenixAshesItem = bone meal on 3x3, RainbowFeatherRevive = either hand, not bypasses_invulnerability damage, regen/absorption/fire res; csboss_settings
balmBossDamagePercent 5, dispenser 30 s. 15 Nov 2026: Paris (Hyperspace Kalos) + Megalopolis ON at weight 2 each (staged 11-13 Nov for the launch), timers 900 s (Ultra Space areas 300 s),
safarifee parisEntryFee 500 / megalopolisEntryFee 1000; hyperspace_clusters 1-5 star herds, no legendaries/UBs; auspicious balls 1-3 rolls over candy/hyperberry/ball/treasure, once per player;
enableShardsClusters true (obstacle_shardcluster 1-3 megashards); quasartico_executive via build_quasartico_trades.py (40+4 Star Piece / 60+Phoenix Ashes / 64+Red Chain Core / 64+Rainbow Feather);
Warp Ride nerfed in safari_tweaks (difficulty.json: UB pool 0-3% by portal rank, shiny 1/8000-1/2000, 0-3 perfect IVs); Ultra Space treasure tables (Recon armour ~0.5% a piece, UB items);
Catch Booster: Hiker 'large' 4 prism_l + 4 pale_l, Giratina 5% (build_catch_boost.py). Dungeon donuts left out: their ingredients have no survival source. Hideaways left out (needs Trial Edition, not installed). -->

# Hoopa Portals

{% hint style="info" %}
<p align="center">Every so often a strange golden ring appears near a player. Rumour has it Hoopa put them there. Step through and you could end up digging for treasure in the <strong>Sinnoh Underground</strong>, climbing Ho-Oh's <strong>Bell Tower</strong>, lost in Giratina's <strong>Distortion World</strong>, exploring the city of <strong>Hyperspace Kalos</strong> or riding the wormholes of <strong>Ultra Megalopolis</strong>.</p>
{% endhint %}

***

## 🌀 How Hoopa Rings appear

| | |
| --- | --- |
| ⏱️ **How often** | A new ring appears every **15 minutes**, near a random player |
| 📍 **Where** | In the overworld on **Survival** and in the **Resource World**, 32 to 80 blocks from that player |
| ⌛ **How long it stays** | **1 hour**, then it disappears |

Each ring leads to one dungeon:

| Destination | Chance |
| --- | --- |
| ⛏️ **Sinnoh Underground** | 3 in 9 |
| 🏙️ **Hyperspace Kalos** | 2 in 9 |
| 🛸 **Ultra Megalopolis** | 2 in 9 |
| 🔔 **Bell Tower** | 1 in 9 |
| 🌌 **Distortion World** | 1 in 9 |

The only way into these dungeons is through one of these naturally spawning rings, so keep an eye out! 👀

***

## 🚪 Going through

{% stepper %}
{% step %}
### Check where it goes

Right-click the bottom of the ring. A screen shows you where it leads before you go anywhere.
{% endstep %}

{% step %}
### Pay the entry fee

You pay once a day for each dungeon. Going back in again the same day is free.

| Dungeon | Entry fee |
| --- | --- |
| Sinnoh Underground | **$500** |
| Bell Tower | **$500** |
| Hyperspace Kalos | **$500** |
| Ultra Megalopolis | **$1,000** |
| Distortion World | **$2,500** |
{% endstep %}

{% step %}
### Explore

The first trip into a new ring can take a moment while the dungeon loads. Once you're inside you have **10 minutes** in the Underground and the Distortion World, **15 minutes** in Hyperspace Kalos and Ultra Megalopolis, and **25 minutes** in the Bell Tower. You can leave early through the portal inside at any time.
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
⚠️ When your time is up, or the ring closes, you're sent back out automatically. Each ring's dungeon is gone for good once the ring disappears.
{% endhint %}

Inside every dungeon you **can't break or place blocks**. You can still battle everywhere except the Bell Tower.

***

## ⛏️ The Sinnoh Underground

A huge network of tunnels full of buried treasure.

### Digging

Find a dig spot in the walls to start the excavation mini-game. Uncover the items hidden in the wall before it collapses.

* **Pickaxe:** precise, but slower.
* **Hammer:** clears more at once, but shakes the wall more.
* The cracks at the top show how stable the wall is. Hammer hits and iron deposits make it collapse faster. When it gives way, the dig is over.
* You only get an item if you uncover **all** of it.

### What you can dig up

* **Spheres** in five colours, which you trade with the Hikers
* **Fossils:** all 11 single fossils. See [Fossils & reviving](../pokemon/fossils.md).
* **Evolution stones:** Fire, Water, Thunder, Leaf, Moon, Sun, Dawn, Dusk, Shiny and Ice
* **Arceus Plates** of every type
* **Key Stones and raw Mega Stones**
* Star Pieces, Heart Scales, Revives, Max Revives, Relic Coins, Tumblestones, held items like Hard Stone, Damp Rock and Iron Ball, and more

### Hikers and rewards

* **Hikers** live in the Underground. Trade them your spheres for fossils, rare items and more. Some Hikers that want large spheres also offer a [Catch Booster](../pokemon/catch-boosters.md) for 4 Prism and 4 Pale large spheres.
* **Reach the end** of the Underground and you get a random fossil, which can be any of the 15 including the Galar halves.

### 💎 The Quasartico Executive

A trader in the Underground who swaps **Mega Shard Blocks** for the Mega Stone of your choice. You get Mega Shards in [Hyperspace Kalos](#hyperspace-kalos), and **9 Mega Shards** craft into **1 Mega Shard Block**. Each Executive offers 6 stones at random, and each offer can be used once.

| Stones | Cost |
| --- | --- |
| Basic stones (Absolite, Mawilite, Lopunnite...) | **40 Mega Shard Blocks** + **4 Star Pieces** |
| Mid stones (Gardevoirite, Scizorite, Lucarionite, Gyaradosite...) | **60 Mega Shard Blocks** + **1 Phoenix Ashes** |
| Strong stones (Charizardite X/Y, Garchompite, Metagrossite, Tyranitarite...) | **64 Mega Shard Blocks** + **1 Red Chain Core** |
| Legendary stones (Latiasite, Latiosite, Mewtwonite X/Y, Diancite) | **64 Mega Shard Blocks** + **1 Rainbow Feather** |

Star Pieces come from the Underground, Phoenix Ashes and Rainbow Feathers from the [Bell Tower](#the-bell-tower), and Red Chain Cores from [Giratina](#the-giratina-boss). For other ways to get Mega Stones, see [Mega Stones, Z-Moves & Tera](../pokemon/megas-z-tera.md).

{% hint style="info" %}
💡 Bone Meal can't be used in the Underground.
{% endhint %}

***

## 🔔 The Bell Tower

<figure><img src="../.gitbook/assets/screenshots/bell-tower.jpg" alt="The Bell Tower rising above an autumn forest"><figcaption><p>The Bell Tower</p></figcaption></figure>

A towering pagoda above an endless autumn forest. Ho-Oh waits at the very top, and the only way up is to climb.

* **Climbing:** make your way up floor by floor using ladders, suspension bridges and **Jump Ramps**. You **can't ride Pokémon** or use an **Elytra** here.
* **Watch your step:** Rotom's safety systems don't work in the tower, so it won't save you from a bad jump.
* **No wild battles:** there are no Pokémon battles inside the tower. The only fight is Ho-Oh.

### The Ho-Oh boss

At the top of the tower, use the **Arena Altar** to summon **Ho-Oh** for a real-time boss fight, just like Giratina's. You don't attack it yourself: your Pokémon wear down its health bar while **you dodge its fiery attacks**. Stronger teams bring it down faster, and a fight lasts between 5 and 10 minutes.

* **Balms:** grab a Balm from a **Balm Dispenser** around the arena and throw it at Ho-Oh. Each hit takes off about **5%** of its health. Dispensers refill every 30 seconds, and any Balms left over disappear when the fight ends.
* **Friends:** you can fight it together. If you go down, the fight carries on as long as someone is still standing.

### Rewards

| Reward | Who gets it |
| --- | --- |
| **Phoenix Ashes** (1 to 3) | Everyone still in the arena when Ho-Oh falls |
| **Rainbow Feather** | A **1 in 4** chance per win, given to one random player |
| **Bell Tower Ribbon** | A **1 in 10** chance per win |

* **Phoenix Ashes** work like Bone Meal on a 3×3 area at once.
* **Rainbow Feather:** hold it in either hand and it saves you from a killing blow, like a Totem of Undying, then gives you Regeneration, Absorption and Fire Resistance. It's used up when it saves you, and it can't save you from falling into the void.

***

## 🌌 The Distortion World

Giratina's home, where up and down stop making sense. Islands float in the void, the floor can become the ceiling, and even water ignores gravity.

* **Platforms:** jump across floating rocks and flowers to get around. You **can't ride Pokémon** or use **Firework Rockets** here.
* **Falling into the void** sends you straight back out of the Distortion World.
* **Illusion mazes:** not everything is real. Some plants vanish, others appear out of nowhere and turn paths into mazes.

### Distorted Pokémon

Giant shadowy Pokémon that are much stronger than normal ones. They **can't be caught**, but beating them can drop **Red Chain Fragments**.

### Giratina and Turnback Cave

The only way out leads to **Turnback Cave**, where Giratina waits. Giratina takes your **Red Chain Fragments** and turns them into a **Distorted Red Crystal**, which you use on one of your Pokémon:

| Crystal | What it does |
| --- | --- |
| Distorted Red Crystal B | Changes the Pokémon's Poké Ball at random |
| Distorted Red Crystal E | Shuffles its EVs |
| Distorted Red Crystal G | Swaps its gender |
| Distorted Red Crystal I | Rerolls all of its IVs |
| Distorted Red Crystal L | Sets its level to anything from 1 to 100 |

### The Giratina boss

In the arena you can take on **Giratina's shadow** in a real-time boss fight. You don't attack it yourself: your Pokémon wear down its health bar while **you dodge its attacks**. Stronger teams bring it down faster, and it gets a second phase partway through. Throw **Distorted Balms** from the arena's dispensers to take off about 5% of its health per hit.

Beating it gives a **1 in 10** chance of a **Red Chain Core**. Craft **9 cores** into a **Red Chain**, which you throw to shackle a wild Pokémon. There's also a **1 in 20** chance of a [Catch Booster](../pokemon/catch-boosters.md).

***

## 🏙️ Hyperspace Kalos

A strange copy of a Kalos city, glowing under a purple sky. Every ring leads to its own private copy for you and your friends, and wild Pokémon roam its streets in herds.

### Wild Pokémon

The city is split into zones, each rated **1 to 5 stars** and themed around one or two types. Higher-star zones have stronger, higher-level Pokémon, including fully evolved starters, Eeveelutions and pseudo-legendaries like Dragonite, Tyranitar, Garchomp and Baxcalibur. **Alphas** roam here too. There are no Legendaries or Ultra Beasts in Hyperspace.

### Auspicious Poké Balls

Giant Poké Balls are scattered all over the city. Right-click one to open it. Each ball gives **1 to 3** items, and **every player** can open each ball once:

* **Candy:** EXP Candy L and XL, and Rare Candies
* **Hyper Berries:** see below
* **Poké Balls**, now and then a special one
* **Treasure:** Relic Coins, Apricorns, healing items, evolution items, type Gems and more

**Golden Auspicious Poké Balls** are rarer and give better rewards. Look out for **Lost Items** hidden around the city too.

### Hyper Berries

Rare berries you can only find in Hyperspace. Use them as seasoning in a **Poké Snack**, and the Pokémon it attracts get a big boost:

| Hyper Berry | Effect on the Pokémon the snack attracts |
| --- | --- |
| Hyper Starf | Extra chances to be **shiny** |
| Hyper Enigma | A chance to have its **Hidden Ability** |
| Hyper Liechi, Ganlon, Petaya, Apicot, Salac, Lansat | **+10 IVs** in one stat |
| Hyper Pomeg, Kelpsy, Qualot, Hondew, Grepa, Tamato | Extra **EVs** in one stat |

You can also sell them at the **EV Berries** shop in the [PokéMart](../economy/pokemart.md).

### Mega Shard Clusters

Crystal clusters grow all over the city. Break one with your Pokémon to get **1 to 3 Mega Shards**. Craft **9 Mega Shards** into a **Mega Shard Block**, then trade the blocks to the [Quasartico Executive](#the-quasartico-executive) in the Underground for the Mega Stone you want.

### Tasks

Each visit gives you a list of tasks, like catching a certain Pokémon or type, catching an Alpha, picking up floating items or clearing boulders, brambles and sludge with your Pokémon. Finish them all for a bonus **Auspicious Poké Ball**.

***

## 🛸 Ultra Megalopolis

A city at the edge of Ultra Space, full of **Ultra Wormholes**.

### The Ultra Warp Ride

Step into an Ultra Wormhole to ride it. Steer through the wormhole, grab boosts and dodge hazards, and take one of the portals that open up along the way. The **further you travel** before you take one, the better the portals you'll find.

Every portal leads to a world in **Ultra Space**: the Ultra Jungle, Ultra Desert, Ultra Crater, Ultra Plant, Ultra Deep Sea, Ultra Forest or Ultra Ruins. You have **5 minutes** in each one.

### Ultra Space

Each ride ends with **one special Pokémon** waiting for you in that world. It's usually a strong Pokémon from there, like Garchomp, Metagross, Dragonite or Tyranitar, and it can have perfect IVs, its Hidden Ability or be an Alpha. Better portals give better Pokémon, and on the very best ones there's a **very rare** chance of meeting an **Ultra Beast**.

### Lost treasures

Search each Ultra Space world for **Lost Items**. Along with Relic Coins and evolution items, they can hold:

| Item | What it does |
| --- | --- |
| **Ultra Recon armour** (4 pieces) | Strong armour. Wear the full set to glide like an Elytra (not inside dungeons). Rare |
| **Poipole Darts** | Arrows that fly fast and straight |
| **Nihilego Hat** | Conduit Power while you're in water, at the cost of hunger |
| **Celesteela and Kartana Cannons** | Fire smoke signals or paper planes |
| **Xurkitree Bombs** | Throw one for a lightning strike under a clear sky |
| **Rotom skin** | Unlocks a new look for your Rotom Phone |

You **can't ride Pokémon** or use an **Elytra** in Ultra Megalopolis or Ultra Space.
