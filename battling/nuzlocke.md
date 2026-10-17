---
description: The weekly Nuzlocke Challenge. Beat 8 leaders in a row, and lose your whole team if you fall.
---

<!-- Sources: network/_upload/hub/config/nuzlocke/config.json (leadersPerRun 8, resetDay FRIDAY 18:00 Australia/Brisbane, requiredPermissions = any region's E4, teamSize 6, GEN_9_SINGLES_FLAT_100, regions Kanto/Johto/Hoenn/Sinnoh, pool of 32, bannedItems revives, bannedMoves revivalblessing, moneyPerWin 10000, completionRewards),
dev/nuzlocke/src (rules text shown to players, commands, arenas, no items in battle), Downloads/hub logs/logs/latest.log (nuzlocke live on hub only). Second Chance (nuzlocke 1.5.0, 18 Oct 2026): config resetPrice 500000, only after a LOST run, once per week, sold by the Nuzlocke Reset NPC on the Hub. -->

# 💀 Nuzlocke Challenge

{% hint style="info" %}
<p align="center">The Nuzlocke Challenge is the hardest test on Cobblemon AU. Take one team of 6 through <strong>8 gym leaders in a row</strong>. Win and you earn big rewards. Lose a single battle and <strong>your whole team is deleted</strong>.</p>
{% endhint %}

{% hint style="danger" %}
<p align="center"><strong>Pokémon deleted in the Nuzlocke Challenge are gone forever.</strong> Only bring Pokémon you're prepared to lose.</p>
{% endhint %}

***

## ✅ Before you start

| | |
| --- | --- |
| 🏆 **Requirement** | Beat the Elite Four of **any one region** |
| 🐾 **Team** | Exactly **6 Pokémon** in your party. These are locked in as your team for the whole run. |
| 🗓️ **Attempts** | **One attempt per week**. Starting a run uses it up. Lost your run? See Second Chance below. |
| 🖥️ **Server** | The Nuzlocke Challenge is on the **Hub** |

***

## 🗓️ This week's leaders

Every week, **8 leaders** are picked at random from all **32 gym leaders** of Kanto, Johto, Hoenn and Sinnoh. Everyone faces the same 8, in the same order. A new lineup comes out every **Friday at 6pm AEST**.

Type `/nuzlocke lineup` to see this week's leaders before you commit.

{% hint style="warning" %}
⚠️ These aren't the normal gym teams. Every Nuzlocke leader has a new, much stronger team built around a strategy, often with Legendaries, a Mega Evolution and a Tera Type. Expect a real fight.
{% endhint %}

***

## 📜 The rules

* **Lose a battle and your whole team is deleted.** Forfeiting, disconnecting or dying during a battle counts as losing.
* **Win and your whole team is fully healed** for the next leader, even the Pokémon that fainted.
* **No items during battles.** Revives, Max Revives and Revival Herbs are banned for the whole run, and so is the move Revival Blessing.
* **These 6 are your only team.** You can't swap in other Pokémon.
* **Every battle is at level 100.**
* **Gym rules apply.** Your team is checked against the normal gym ban list when you start and before every battle.
* A server restart or a battle stopped by staff costs you nothing. You just face that leader again.

***

## ▶️ Running the challenge

| Command | What it does |
| --- | --- |
| `/nuzlocke` | Shows your current run, or how to start one |
| `/nuzlocke start` | Start a run (you'll be asked to confirm) |
| `/nuzlocke battle` | Fight your next leader |
| `/nuzlocke status` | Your progress |
| `/nuzlocke lineup` | This week's 8 leaders |
| `/nuzlocke rewards` | What you can win |
| `/nuzlocke quit` | End your run early and keep your team. Your attempt for the week is still used up. |

Each battle takes you to an arena in the leader's region, and you're sent back when it's over.

***

## 🔁 Second Chance

Lost your run? You can buy **one more attempt** that week from the **Nuzlocke Reset** NPC for **$500,000**.

* Only if your run **ended in a loss**. A run you finished or quit doesn't qualify.
* **Once per week.** Lose your second attempt and you'll have to wait for Friday's reset.
* You'll need a new team of 6, since your old one is gone.

Talk to the NPC, then click again to confirm. `/nuzlocke` tells you when a Second Chance is available.

***

## 🏆 Rewards

**For every leader you beat:** $10,000 multiplied by how many leaders you've beaten so far. That's $10,000 for the first, $20,000 for the second, and so on up to $80,000 for the eighth.

**For clearing all 8**, the whole server hears about it, and you get:

| Reward | Chance |
| --- | --- |
| Master Ball | Always |
| 30 Battle Points **or** 50 Glory | Always |
| 3 Mega Stone Crate keys | Always |
| Hat Crate key | Always |
| 2 Shiny Crate keys | 35% |
| Plushie Crate key | 30% |
| 2 Relic Coin Sacks | 30% |
| Paradox Crate key | 25% |
| Ultra Beast Crate key | 25% |
| Legendary Crate key | 10% |
| Radiant Crate key | 8% |
| Shiny Card | 2% |
| Alpha Card | 2% |
