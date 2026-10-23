---
description: Rent a plot in the Player Market, run your own shops, and buy from other players.
---

<!-- Sources: network/docs/MARKET-PLAYER-GUIDE.md (player guide, staff section left out), network/_upload/hub/config/shops.json + dev/shops (rent tiers $30k/$25k/$20k a week, 1 plot per player, 4 weeks prepaid, 3-day grace, 2% tax, 8-block buy range, Y 256, 10 s teleport cooldown, blocked items), owner FAQ doc.
Shop packs (64 included, +8 slots for $2,500/week, max 128): owner confirmed shops 1.5.0 live on 18 Oct. -->

# 🏪 Player Market

{% hint style="info" %}
<p align="center">The Market is a trading district on the Hub. Rent your own plot, build a shop, and sell to other players, even while you're offline. Everyone can visit, browse and buy. Type <code>/market</code> to go there.</p>
{% endhint %}

***

## 🧭 Getting around

| Command | What it does |
| --- | --- |
| `/market` | Go to the plaza in the middle of the Market |
| `/market warp <player>` | Go to that player's plot |
| `/plot visit <plot>` | Go to a plot by its ID, for example `/plot visit C7` |

These work from both servers. You can't use them during a battle, and there's a 10 second cooldown between teleports.

The Market is a **9 by 9 grid** of plots with the **plaza** in the middle. Plots are named like a map: columns **A to I** (west to east) and rows **1 to 9** (north to south), so the plaza is E5. Every plot has a sign facing the plaza showing its ID, tier, price and who rents it.

***

## 🏠 Renting a plot

| Tier | Where | Plots | Rent per week |
| --- | --- | --- | --- |
| ⭐ **Prime** | Right next to the plaza | 8 | $30,000 |
| 🛍️ **Main Street** | The next ring out | 16 | $25,000 |
| 🏘️ **Standard** | Everything further out | 56 | $20,000 |

1. Find a plot whose sign says **FOR RENT**.
2. Right-click the sign and pick how many weeks to pay for, from 1 to 4.

You can also stand inside the plot and type `/plot rent <weeks>`.

* Each player can rent **one plot**.
* You can pay up to **4 weeks** ahead.
* Each plot is **30 by 30 blocks**. You can build up to **Y 256** and 4 blocks down.

### 🤝 Trusting friends

`/plot trust <player>` lets a friend build on your plot, open your containers (including your shop chests) and pay your rent for you. Only trust people you'd hand your stock to. `/plot untrust <player>` removes them.

***

## 📅 Keeping your plot

| Command | What it does |
| --- | --- |
| `/plot extend <owner> <weeks>` | Pay for more time, or right-click the plot sign |
| `/plot info` | Details about the plot you're standing in |
| `/plot list` | Your plot, time left and shop count |

You'll get a reminder when you log in if your rent has **less than 2 days left**.

### ⚠️ If your rent runs out

1. **3-day grace period.** Your shops close and your sign shows **CLOSED**, but you or a trusted friend can still pay to keep it.
2. **After 3 days the plot is reset.** Everything stored in your chests, barrels, shulker boxes, item frames, armour stands, display cases and lecterns goes into your **reclaim box**, and the plot goes back up for rent.
3. Collect your items with **`/plot reclaim`**.

{% hint style="danger" %}
<p align="center"><strong>Blocks are not returned.</strong> Only the contents of storage blocks, frames and stands are saved. Take down anything you want to keep before your rent runs out.</p>
{% endhint %}

To give up your plot early, type `/plot abandon <plot>`, then `/plot abandon <plot> confirm`. There's no refund for time already paid.

***

## 🏷️ Making a shop

A shop is a container on your plot that sells **one item** in bundles called **lots**.

{% stepper %}
{% step %}
### Place a container

Place a **chest, barrel or iron chest** on your plot and put the items you want to sell inside.
{% endstep %}

{% step %}
### Hold the item

Hold one of those items in your main hand.
{% endstep %}

{% step %}
### Look at the side and create

Look at the side of the container where you want the sign (the space there must be empty) and type `/shop create <price> <amount>`.

For example, `/shop create 500 16` sells **16 at a time for $500**.
{% endstep %}
{% endstepper %}

* A shop only sells items that are **exactly** the same as the one you held: same enchantments, durability and name.
* `/shop price <price>` changes the price. `/shop remove`, or breaking the sign, closes the shop.
* Right-click your own shop sign to see how much stock is left.
* Money goes **straight to your balance**, even when you're offline. A **2% sales tax** is taken from each sale.
* `/shop stats` shows your whole plot's sales, tax, revenue and best sellers.

### ➕ More than 64 shops

Your plot includes **64 shops**. When you make your 65th, you'll get a message in chat. Click **\[Click to confirm]** within 60 seconds to add **8 more shop slots** for **$2,500 a week** on top of your rent.

* The first payment only covers the rent time you've already paid for. With 2 weeks left, it's $5,000.
* Every 8 shops after that works the same way, up to **128 shops** per plot.
* Close shops and your rent goes back down at your next extension. There are no refunds for time already paid.
* `/plot list` shows how many shops you have, your limit and your weekly rent.

### 🎯 Limited stock

* `/shop multibuy off` means buyers can only take one lot per purchase.
* `/shop playerlimit <items>` caps how much each player can buy. Setting it again resets everyone's count, which is handy for a new sale. `/shop playerlimit none` removes it.

### 🚫 What you can't sell

Items that hold other items (like shulker boxes and bundles), items carrying a lot of data (like very long books), and anything staff have blacklisted.

***

## 💵 Buying shops

A **buying shop** works the other way round: other players sell you an item and you pay them.

1. Place a container with room in it, hold the item you want, and look at the side of the container.
2. Type `/shop buy <price> <amount>`. For example, `/shop buy 50 1` pays **$50 for every diamond**.
3. Add a limit to stop after a certain number: `/shop buy 50 1 5` buys 5 diamonds, then stops. Use `/shop limit <items>` to set a new limit later.

The money comes from your balance, and the shop stops buying when you can't afford it or the container is full.

**Selling to a buying shop:** hold the item and right-click the sign to sell one lot, or **sneak and right-click** to sell as much as you're carrying. You get the price minus the 2% tax.

***

## 🛍️ Buying from a shop

1. Right-click a shop's sign or its chest. A shop menu opens.
2. Click **Buy 1**, **Buy 5** or **Buy 10** lots.

* You need to be within 8 blocks, have the money and have room in your inventory.
* The menu always shows the item's **real name**. If something has been renamed, a red line tells you, so you can't be tricked into buying renamed paper as an emerald.

***

## 📏 Market rules

* **No redstone.** Contraptions don't work in the Market.
* **Fire, water, lava and scaffolding** are allowed on your own plot, but they can't spread out of it.
* **Not allowed in the Market:** TNT and other explosives, hoppers, droppers, dispensers, pistons and other item movers, boats, chorus fruit, bows, crossbows, tridents, pastures and Alpha spawners.
* **No wild spawns** and **no weather**.
* **Seats and gacha machines** on any plot can be used by everyone.
* You can't break, place or open anything on a plot you don't rent or aren't trusted on.
