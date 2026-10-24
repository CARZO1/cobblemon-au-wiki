---
description: Answers to the questions we get asked most.
---

<!-- Sources: owner FAQ doc "Cobblemon AU - Frequently Asked Questions (FAQ)" (Google Docs), checked against:
network/_upload/hub/config/champion.json (champion rules),
network/_upload/{hub,survival}/config/cobblesafari/encounter_boost_config.json (incense/perfume multipliers, 30 min duration),
GTS sales tax config (2%),
network/_upload/hub/config/shops.json + dev/shops PlayerCommands.java (market rules and commands),
network/_upload/survival/config/flan/flan_config.json (claim blocks),
network/_upload/hub/config/skiesguis/guis/gyms_*.json (4 regions),
test-server/config/commandaliases/end.json (End requirement) -->

# Frequently Asked Questions

{% hint style="info" %}
<p align="center">Click a question to see the answer. Can't find what you're after? Ask in our <a href="https://discord.gg/G48XBcSNk4">Discord</a>.</p>
{% endhint %}

***

## 🌐 General

<details>

<summary>Is keepInventory on?</summary>

Yes. If you die, you keep all of your items.

</details>

<details>

<summary>How do I view crafting recipes?</summary>

Open your inventory and press **Ctrl + O**. You can search for an item and click it to see its recipe.

</details>

<details>

<summary>How do I update to the latest version of the modpack?</summary>

Close the game completely, then:

1. Open the Modrinth App.
2. Click into the **Cobblemon AU** page.
3. Go to the **Content** tab.
4. Click **Switch version** (next to the ⇄ arrows icon).
5. Select the version marked **Current**.
6. Click **Update** in the bottom-right corner.
7. Wait for it to finish, then launch the game as normal.

</details>

<details>

<summary>What's the difference between Hub and Survival?</summary>

**Hub** has the lobby, Pokémon Center, PokéMart, the gyms, crates, the Player Market, the Safari Zone and the Resource World. **Survival** is the main world where you build and claim land, plus the Nether, the End and the Battle Tower.

Your Pokémon, items, money and progress are shared between both. Type `/hub` or `/survival` to switch.

</details>

<details>

<summary>When does the server restart?</summary>

Every day at **2am and 2pm AEST**. You'll get a warning in chat before it happens, and you can rejoin about 30 seconds later.

</details>

<details>

<summary>How do I get to the End?</summary>

Beat at least **4 gyms in one region**. They have to be in the same region, so 2 in Kanto and 2 in Johto doesn't count. Once you've beaten your 4th gym, type `/end` to warp there.

</details>

<details>

<summary>What is voting and how can I vote?</summary>

Voting supports the server and earns you free rewards. Type `/vote` to see the voting sites. Open each link, enter your Minecraft username and submit your vote. You'll get a **Vote Key** for each vote, which you can open at the crates on the Hub (`/crates`).

See [Voting](voting.md) for the milestone rewards.

</details>

<details>

<summary>What is Wonder Trade, and how do I use it?</summary>

Wonder Trade lets you put one of your Pokémon into a pool and get a random Pokémon back. It's on the **Survival** server.

Put the Pokémon you want to trade in your party, then type `/wt <number>`, where the number (1 to 6) is its slot in your party. Click the confirm message in chat to complete the trade. You can trade once an hour.

See [Wonder Trade](../pokemon/wonder-trade.md) for more.

</details>

***

## 🐾 Pokémon basics

<details>

<summary>How do I choose my starter Pokémon?</summary>

Press **M** when you first join. If you already caught or were given a Pokémon before choosing, put it in a PC so your party is empty, then press **M** again.

</details>

<details>

<summary>How do I heal my Pokémon?</summary>

Heal at the Pokémon Center with `/pokecenter`. You can also craft or buy a **Healing Machine** at the PokéMart. The recipe is 3 Copper Ingots, 4 Iron Ingots, 1 Redstone Dust and 1 Max Revive.

Some ranks also get `/pokeheal`, which heals your whole party wherever you are.

</details>

<details>

<summary>How do I get Poké Balls?</summary>

Buy them at the PokéMart (`/pokemart`), find them in chests in structures, or craft them from Apricorns and metals found around the world. The [Cobblemon wiki](https://wiki.cobblemon.com/index.php/Pok%C3%A9_Ball) lists every recipe.

</details>

<details>

<summary>How do I see my Pokémon's stats?</summary>

Press **M**. The four tabs in the middle of the menu let you view and change moves, and see IVs, EVs, Friendship, Fertility and more.

</details>

<details>

<summary>How do I challenge gyms and become Champion?</summary>

Type `/gyms` to open the gym menu. There are four regions: **Kanto, Johto, Hoenn and Sinnoh**. Use the arrows to flip between them. You don't have to finish one region before starting another.

Beat all 8 Gym Leaders in a region to unlock that region's **Elite Four**. Beat the Elite Four and you can challenge the region's Champion with `/champion challenge <region>`. Type `/hall_of_fame` or `/champion` to see who holds each title.

Title matches are a best of three at level 50, using the Smogon National Dex rules. See [Player Champions](../battling/champions.md) for the full rules.

</details>

<details>

<summary>How do I trade Pokémon?</summary>

Look at the player you want to trade with and press **R**, then click **Trade**. They need to do the same to you. The trade menu opens once you've both requested it.

You can also type `/poketrade <player>`.

</details>

<details>

<summary>How do I get a Mega Ring, Z-Ring, Dynamax Band or Tera Orb?</summary>

Buy them from the **Cobblemon Supplies** store at the back of the PokéMart. Type `/pokemart` to get there.

</details>

<details>

<summary>Which Pokémon can I ride, and how do I mount one?</summary>

Hold **Shift** and right-click your Pokémon to open its interaction wheel. If it can be ridden, you'll see the option to mount it.

The [Cobblemon wiki](https://wiki.cobblemon.com/index.php/Pok%C3%A9mon/Riding) lists every Pokémon you can ride or fly on.

</details>

<details>

<summary>How do I evolve Eevee into the extra Eeveelutions?</summary>

Check the [Extra Eeveelutions](../pokemon/extra-eeveelutions.md) page. It has every evolution method, plus each one's type, stats and abilities.

</details>

<details>

<summary>How much do Incense and Perfumes boost my odds?</summary>

Each one lasts **30 minutes** and only affects new Pokémon that spawn near you.

| Item | Boost |
| --- | --- |
| Shiny Incense | 2x shiny odds |
| Great Shiny Incense | 4x shiny odds |
| Ultra Shiny Incense | 8x shiny odds |
| Uncommon Perfume | 2x Uncommon spawns |
| Rare Perfume | 2x Rare spawns |
| Ultra Rare Perfume | 4x Ultra Rare spawns |

Looking for a Legendary or Mythical? The **Legendary and Mythical Perfumes** work differently. See [How to boost your chances](../pokemon/legendary-perfumes.md).

</details>

***

## 💰 Economy & GTS

<details>

<summary>How can I make money?</summary>

There are plenty of ways, including:

* selling Pokémon and items on the GTS (`/gts`) or in your own Market shop
* selling items at the PokéMart
* completing quests (`/quest`)
* beating gyms
* opening vote crates
* filling in your Pokédex (`/dexrewards`)

</details>

<details>

<summary>What is the GTS?</summary>

The GTS (Global Trade Station) is the server-wide marketplace where players buy and sell Pokémon and items. Type `/gts` to open it. You can list something at a fixed price for anyone to buy, or as an auction that players bid on.

A **2% sales tax** is taken from each sale.

</details>

<details>

<summary>Is the GTS shared between Hub and Survival?</summary>

Yes. It's one marketplace across the whole network. A listing you create on Survival can be seen and bought from the Hub, and the other way round. Your GTS account is the same on both servers.

</details>

<details>

<summary>My listing sold. How do I get my money?</summary>

The money goes into your GTS account, not straight into your balance. Open `/gts` and click your player head to withdraw it from your Vault. Money from auctions works the same way. Your Vault holds it as long as you like, so there's no rush.

</details>

<details>

<summary>What is the GTS Vault?</summary>

It's your personal holding area inside the GTS. Anything that comes back to you lands there instead of your inventory or party: money from sales, Pokémon from expired listings, and items from listings you cancel.

</details>

<details>

<summary>What happens if I cancel a listing?</summary>

The Pokémon or item goes back to your GTS Vault and you can collect it from there. There's no penalty for cancelling.

</details>

<details>

<summary>How long do GTS listings last?</summary>

7 days. When a listing expires, the Pokémon or item goes back to your GTS Vault automatically. You don't need to be online.

</details>

***

## 🏪 The Player Market

<details>

<summary>What is the Market?</summary>

The Market is an area on the Hub where players rent a plot, build a shop, and buy and sell items with each other. Type `/market` to go there from either server.

</details>

<details>

<summary>How do I get a plot?</summary>

Right-click a plot sign marked **For Rent** and choose how many weeks to pay for. You can also stand inside the plot and type `/plot rent <weeks>`.

You can rent **one plot** at a time and pay up to **4 weeks** in advance.

</details>

<details>

<summary>How do I sell items in my shop?</summary>

1. Place a chest, barrel or similar container on your plot.
2. Put the items you want to sell inside.
3. Hold one of those items in your main hand.
4. Look at the side of the container where you want the shop sign.
5. Type `/shop create <price> <amount>`.

A 2% sales tax is taken from each sale.

</details>

<details>

<summary>What does trusting a player do?</summary>

A trusted player can help build on and manage your plot. Type `/plot trust <player>` (they need to be online). Type `/plot untrust <player>` to remove them.

</details>

<details>

<summary>How do I extend my rent?</summary>

Right-click your plot sign, or type `/plot extend <owner> <weeks>`. You can pay up to 4 weeks in advance.

If your rent runs out, you get a 3-day grace period to pay before the plot is reset.

</details>

<details>

<summary>How do I give up my plot?</summary>

Type `/plot abandon <plot>`, then confirm with `/plot abandon <plot> confirm`.

</details>

***

## 🎰 Gacha Machines

The Gacha Machines are on the Hub (`/gacha`) and cost Relic Coins to use. Every machine can also drop EXP Candies, Relic Coins, Silver Caps and Ability Patches or Capsules. See [Gacha Machines](../economy/gacha.md) for the full odds for every capsule.

<details>

<summary>🔴 Red machine</summary>

Heat Rock, Magma Cream, Blaze Powder, Super Potion, Red Apricorn, Charcoal Stick, Poké Ball, Cheri Berry, Fire Gem, Burn Heal, TM Flame Charge, Magmarizer, Fire Stone, Flame Orb and Calcium.

</details>

<details>

<summary>🟡 Yellow machine</summary>

Yellow Apricorn, Electric Gem, TM Charge Beam, Citrine Ball, Magnet, Cheri Berry, Paralyze Heal, Fighting Gem, Super Potion, Electirizer, Muscle Band, Protein, Punching Glove, Thunder Stone, Focus Band, TM Bulk Up, Focus Sash, Choice Specs, TM Thunderbolt, TM Brick Break and TM Zap Cannon.

</details>

<details>

<summary>🩷 Pink machine</summary>

Love Sweet, Normal Gem, Full Heal, Clover Sweet, Fairy Feather, Silk Scarf, Fairy Gem, Pink Apricorn, Roseate Ball, Destiny Knot, Shiny Stone, TM Draining Kiss, TM Body Slam, Whipped Dream, Moon Stone, TM Hyper Beam and Lucky Egg.

</details>

<details>

<summary>🟢 Green machine</summary>

Bug Gem, Grass Gem, Miracle Seed, Medicinal Leek, Big Root, Antidote, Verdant Ball, Leaf Stone, TM U-turn, TM Energy Ball, Blank TM, Sun Stone, Silver Powder, Black Sludge, TM Mega Drain, TM Giga Drain, Choice Specs and Carbos.

</details>

<details>

<summary>🔵 Blue machine</summary>

Never-Melt Ice, Azure Ball, Blue Apricorn, Ice Gem, Dive Ball, Mystic Water, Water Gem, Icy Rock, Ice Heal, TM Aqua Tail, Deep Sea Scale, Dragon Scale, Water Stone, Deep Sea Tooth, Ice Stone, TM Bubble Beam, Choice Specs, Choice Scarf, Calcium and TM Blizzard.

</details>

<details>

<summary>🟣 Black / Purple machine</summary>

Slate Ball, Dark Gem, Twisted Spoon, Black Tumblestone, Black Glasses, Black Apricorn, Rock Gem, Hard Stone, TM Crunch, TM Rock Tomb, TM Psyshock, Dawn Stone, Dusk Stone, Relic Coin, Black Augurite, TM Payback, TM Psybeam, Reaper Cloth, Choice Scarf, Wise Glasses, TM Dark Pulse and Scope Lens.

</details>

<details>

<summary>⚪ White machine</summary>

The White machines are disabled. Opening a White capsule announces a "dud" and drops nothing, and the Relic Coins aren't refunded. Don't use them!

</details>

***

## 🏡 Claiming land and homes

<details>

<summary>How do I claim land?</summary>

Type `/kits` on the Hub and choose **Starter** to get a **golden hoe**, the claim tool.

Hold the hoe and left-click one corner of your area, then go to the far opposite corner and left-click again. If it worked, gold blocks will appear around the edge of your claim.

Claims only work on **Survival**. You start with 500 claim blocks and earn more the longer you play. Claim block vouchers from crates and ranks are paper items. With a voucher in your inventory, type `/redeem` on Survival to add the blocks.

</details>

<details>

<summary>How do I set my home?</summary>

Stand in a safe spot inside your claim and type `/home set <name>`. To go back at any time, type `/home tp <name>`, or just `/home tp` if you only have one home.

Homes are on Survival. Using `/home` on the Hub sends you over to Survival.

</details>

<details>

<summary>How do I trust other people in my claim?</summary>

Stand in the claim and type `/flan menu`. Click the **book** icon to add a player as a visitor or co-owner.

</details>

<details>

<summary>How do I delete my claim?</summary>

Stand in the claim and type `/flan delete`. If it asks you to confirm, type `/flan confirm` or click **\[Confirm]** in chat.

</details>

<details>

<summary>I forgot where my base is. What do I do?</summary>

Type `/flan list` to see all of your claims and their coordinates. Then get close with `/rtp`, or fly there on one of your Pokémon.

Set a home next time so it doesn't happen again!

</details>

<details>

<summary>How do I stop people sending out Pokémon in my claim?</summary>

Type `/flan menu`, open **Global Permissions** (the beacon) and find the **Great Ball** on page 3. Set it to false and other players won't be able to throw out Pokémon in your claim.

</details>

<details>

<summary>How do I let other players use a Raid Den in my claim?</summary>

1. Type `/flan menu`.
2. Click **Configure bypasses for actions**.
3. Click **Allowed block use**, then **Add**.
4. Type `cobblemonraiddens:raid_crystal_block`.
5. Click the **book** to confirm.

</details>
