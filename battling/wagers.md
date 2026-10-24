---
description: Bet money on a Pokémon battle against another player.
---

<!-- Sources: dev/wager/src/main/java/au/cobblemon/wager/WagerConfig.java (MIN 100, MAX 1,000,000, EXPIRY 60 s, MAX_DISTANCE 32, BATTLE_LEVEL 50, formats singles/doubles/triples), WagerMod.java (commands, escrow, team check, forfeit/refund rules, player messages). Live on hub and survival (wager 1.9.0). -->

# Wagers

{% hint style="info" %}
<p align="center">Think your team's the best? Challenge another player to a battle with money on the line. Both of you put in the same amount, and the winner takes it all.</p>
{% endhint %}

***

## ⚔️ How to wager

{% stepper %}
{% step %}
### Send the challenge

Stand near the other player and type:

`/wager <player> <singles|doubles|triples> <amount>`

For example, `/wager Ash singles 5000` challenges Ash to a singles battle for $5,000 each.
{% endstep %}

{% step %}
### Check the teams

Both players see each other's party in chat before anything is accepted, including any fainted Pokémon.
{% endstep %}

{% step %}
### Accept or decline

The other player clicks **\[ACCEPT]** or **\[DENY]** in chat, or types `/wager accept` or `/wager deny`. You can withdraw your challenge with `/wager cancel` before they accept.
{% endstep %}

{% step %}
### Battle!

Once it's accepted, both stakes are held safely and the battle starts. The winner gets **both stakes**.
{% endstep %}
{% endstepper %}

***

## 📏 The rules

| | |
| --- | --- |
| 💰 **Stake** | $100 to $1,000,000 each |
| 🏆 **Prize** | The winner gets both stakes, with no fees |
| 📊 **Level** | Every Pokémon is set to **level 50** for the battle |
| 📍 **Distance** | You both need to be in the same world and within **32 blocks** of each other |
| ⏱️ **Time to accept** | A challenge expires after **60 seconds**. Sending a new one replaces the old one. |
| 🐾 **Teams** | If either party changes after the challenge is sent, the wager is cancelled |

***

## 🔌 What if someone leaves?

* If a player **leaves, runs or disconnects while they're losing**, they forfeit and the other player wins the pot.
* If the battle ends any other way without a clear winner, **both players get their money back**.
* If the server restarts mid-wager, both players are refunded when it comes back up.

{% hint style="success" %}
💡 Just want a friendly battle? Use `/challenge <player>` instead. No money involved.
{% endhint %}
