---
description: Beat a region's Elite Four, then challenge for its Champion title.
---

<!-- Sources: network/docs/CHAMPION.md (champion mod 1.5.0 player rules: ranked National Dex preset rules, team lock, team preview + lead pick, strikes, cooldowns, commands), network/_upload/hub/config/champion.json (kanto/johto/hoenn/sinnoh, winsNeeded 2, lockTeams, secondsBetweenGames 45, leadSelectSeconds 60, challengeExpiryHours 72, challengeCooldownHours 24, strikesToForfeit 3, strikeWindowDays 14, oneTitlePerPlayer, titleLossCooldownDays 7, prefix [Champion]). Re-read 25 Oct (CHAMPION.md updated 07:33): weekly Champion kit on hub, hub vs survival label limits, dodged challengers skip the 24h wait. Staff commands left out. -->
# Player Champions

{% hint style="info" %}
<p align="center">Every region has a <strong>Champion</strong>, and it's a real player. Beat a region's Elite Four and you can challenge its Champion for the title. Win, and the title is yours until someone takes it from you.</p>
{% endhint %}

***

## 🗺️ The titles

There's a Champion title for each region: **Kanto**, **Johto**, **Hoenn** and **Sinnoh**. A Champion gets a **\[Champion]** tag in chat, and the whole server hears about it when a title changes hands.

Type `/champion` to see who holds each title, or visit the **Hall of Fame** on the Hub (`/hall_of_fame`).

***

## ⚔️ Challenging for a title

{% stepper %}
{% step %}
### Beat the Elite Four

You can only challenge for a region's title after you've beaten that region's **Elite Four**.
{% endstep %}

{% step %}
### Send a challenge

Type `/champion challenge <region> [singles|doubles]`. You pick the format. Leave it out and you get singles. The Champion has to be online.
{% endstep %}

{% step %}
### Wait for an answer

The Champion has **72 hours** to accept or decline. Each title can only have one challenge waiting at a time.
{% endstep %}

{% step %}
### Win the series

It's a **best of 3**. The first player to win 2 games takes the title.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
<p align="center">If a title is <strong>empty</strong>, the first eligible player to challenge for it claims it straight away, with no battle.</p>
{% endhint %}

***

## 📏 Battle rules

Title matches use the same rules as the **Smogon National Dex** format in [Ranked](ranked.md). Type `/champion info` in game to see the exact rules the server is using.

| | |
| --- | --- |
| 🐾 **Team** | 6 Pokémon, battling at **level 50** |
| 🚫 **Bans** | The National Dex ban list for Pokémon, moves, abilities and items, plus the usual clauses (species, sleep, OHKO, evasion, endless battle) |
| ❤️ **Healing** | Both teams are fully healed before every game |

### 🌟 Limits depend on the server

A title match uses the rules of the server it's played on, and the two servers are slightly different:

| Limit | 🌲 Survival | 🏙️ Hub |
| --- | --- | --- |
| Legendaries | 1 | 2 |
| Mythicals | 1 | 6 |
| Paradox Pokémon | 1 | 6 |
| Ultra Beasts | 1 | 2 |
| Megas | 1 | 1 |

Survival also bans a few more Pokémon (such as Megas, Primals, Guzzlord, Shedinja and Urshifu), while the Hub bans Darkrai and the move Wicked Blow. Always type `/champion info` on the server you're battling on to check the exact rules before you build your team.

### 🔒 Your team is locked

Once the Champion accepts, your team is locked for the whole series: the **same Pokémon, moves and held items**. Changing any of them between games forfeits the series.

* Reordering your party is fine.
* A berry or gem that got used up in battle can stay empty, or you can put the same item back.

### 👀 Team preview and picking your lead

Before every game, a menu opens showing your team on the left and your rival's on the right.

* Click your lead Pokémon (two in doubles).
* You have **60 seconds**. If you don't pick, your party order decides.
* Closed the menu by accident? Type `/champion lead` to open it again.

There's a **45 second** break between games. If you both type `/champion ready`, the next game starts straight away.

{% hint style="warning" %}
⚠️ You **forfeit the series** if you log out, or if you're in another battle when a game is due to start.
{% endhint %}

***

## 🛡️ Being Champion

### 🎁 Weekly Champion kit

While you hold a title, you can claim the **Champion kit** once every **7 days** on the **Hub** with `/kits claim Champion`. It contains:

* $40,000
* 24 Battle Tower BP
* 20 Card Dust and 20 Relic Coins
* 5 each of Health, Mighty, Tough, Smart, Courage and Quick Candy
* 1 Ability Patch
* 1 Booster Pack

Lose your title and you lose the kit with it.

### 📋 The rules for Champions

* **Answer challenges** within 72 hours with `/champion accept` or `/champion decline`.
* **Don't dodge.** Declining or ignoring a challenge earns a **strike**. Get **3 strikes within 14 days** and your title goes to the challenger you dodged.
* **One title at a time.** Each player can only hold one Champion title.

| After... | You have to wait |
| --- | --- |
| Challenging a Champion (win or lose) | **24 hours** before challenging that region again. If the Champion dodged you, there's no wait. |
| Losing your title | **7 days** before you can hold any title again |

***

## ⌨️ Commands

| Command | What it does |
| --- | --- |
| `/champion` | See every region's Champion |
| `/champion info` | The current title match rules |
| `/champion challenge <region> [singles\|doubles]` | Challenge for a title, or claim an empty one |
| `/champion accept` / `decline` | Answer a challenge (Champions only) |
| `/champion ready` | Skip the break between games |
| `/champion lead` | Reopen the lead-pick menu |
| `/kits claim Champion` | Claim your weekly Champion kit (Hub, title holders only) |
