---
description: Catch the Wanted Pokémon before anyone else for cash, Battle Points and candies.
---

<!-- Sources: network/_upload/{hub,survival}/config/pokehunt/config.json (slotHours 4, timezone Australia/Brisbane, slotPlan, tiers + rewards, alphaTargets 3, alphaResetDay MONDAY 00:00, broadcastNewHunts/broadcastClaims), dev/pokehunt/src (Generator, Matcher, Hunts, HuntGui: requirements, chance windows, what counts, GUI),
Downloads/{hub,survival} logs/logs/latest.log (pokehunt 1.2.1 live on both; pool 1036 candidates). -->

# PokéHunt

{% hint style="info" %}
<p align="center">Every 4 hours, three <strong>Wanted Pokémon</strong> go up on the PokéHunt board. The first player on the network to catch one that matches wins the reward. Type <code>/pokehunt</code> to see the board.</p>
{% endhint %}

***

## 📋 How it works

* A new board goes up every 4 hours: **12am, 4am, 8am, 12pm, 4pm and 8pm AEST** (Queensland time, so an hour later in daylight saving states).
* Each board has **3 targets**: one **Easy**, one **Medium**, and one **Hard** or **Extreme**.
* Each target is a species plus a few requirements, like a nature or a size.
* The **first player to catch a match** on either server wins it. Once it's caught, it's gone for that round.
* You can win more than one target, and you get paid straight away. If you're offline when it's confirmed, you'll be paid when you next join.

Everyone gets an announcement in chat when a new board goes up and when a target is caught.

***

## 🔍 Requirements

Targets can ask for any of these:

| Requirement | Example |
| --- | --- |
| 🚻 Gender | Must be female |
| 🌿 Nature | Must be Timid |
| ⭐ Ability | Must have Intimidate |
| 💫 Hidden ability | Must have its hidden ability (Easy targets only) |
| 📏 Size | XS, S, M, L or XL |
| 🗺️ Form | Must be the Alolan form |

{% hint style="info" %}
💡 Natures are checked as caught. Using a Mint afterwards won't count.
{% endhint %}

### What counts

* ✅ Normal catches, including in the **Safari Zone**
* ❌ Raid catches
* ❌ Legendaries, Mythicals, Ultra Beasts and Paradox Pokémon are never targets

***

## 🏆 Rewards

| Tier | Where the species comes from | Cash | Battle Points | Items |
| --- | --- | --- | --- | --- |
| 🟢 **Easy** | Common spawns | $6,500 | | 2 EXP Candy M, 5 Relic Coins |
| 🟡 **Medium** | Uncommon spawns | $16,250 | 5 | 2 EXP Candy L, 1 Relic Coin Pouch |
| 🔴 **Hard** | Rare spawns | $39,000 | 15 | 1 EXP Candy XL, 2 Relic Coin Pouches |
| 🟣 **Extreme** | Ultra-rare spawns | $65,000 | 25 | 2 EXP Candy XL, 4 Relic Coin Pouches |
| 🟠 **Alpha** | Any species that can be an Alpha | $50,000 | 40 | 3 EXP Candy XL, 1 Relic Coin Sack |

Harder targets have fewer requirements, because the species itself is harder to find.

***

## 🦣 Weekly Alpha hunts

Click the **nether star** at the bottom right of the board to see page 2.

* There are **3 Alpha targets**, all open at the same time.
* They reset every **Monday at 12am AEST**.
* The Pokémon you catch has to be an **Alpha**.
* First catch wins, just like the main board.

***

## 🖥️ Reading the board

| Part | What it shows |
| --- | --- |
| ⏰ **Clock** (top) | Time until the next board. On the Alpha page it's the time until Monday's reset. |
| 🐾 **The three Pokémon** | Hover over each to see its tier, what it **must have**, the reward, and when it ends |
| ⬜ **Grey dye** | That target has been caught. Hover to see who got it. |
| ⭐ **Nether star** (bottom right) | Go to the weekly Alpha hunts |
| ⬅️ **Arrow** (bottom left, Alpha page) | Back to the 4-hour hunts |
