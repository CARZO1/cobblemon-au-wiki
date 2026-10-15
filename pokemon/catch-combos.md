---
description: Catch, battle or fish the same Pokémon over and over to boost your shiny, IV and hidden ability odds.
---

<!-- Sources: network/_upload/{hub,survival}/config/unchained/{spawn,capture,fish,resurrection,egg,snack}/*.json (thresholds, enabled, breakStreakOnSuccess, lockToPlayer, marbles),
network/_upload/hub/config/cobblemon/main.json (shinyRate 32768), test-server/config/combosync.json (spawn bias; spawn section identical to the survival 1.7.3 mirror),
dev/combocmd ComboCmd.java (/combo shows catch + fishing chains). Shiny odds = (1 + bonus) / 32768. Egg, snack, shiny-on-capture and spawn IV/HA boosters are disabled. -->

# 🔗 Catch combos

{% hint style="info" %}
<p align="center">Catch or knock out the same Pokémon again and again to build a <strong>combo</strong>. The longer your combo, the better your odds of finding a shiny, and the better the IVs and hidden abilities of what you catch.</p>
{% endhint %}

***

## 🔢 How a combo works

* Each kind of combo counts one species at a time.
* Catching or knocking out the **same species and form** adds 1 to your combo.
* Catching or knocking out a **different species or form** starts that combo again from zero. A Paldean Wooper and a normal Wooper are different forms!
* Type `/combo` to see your current catch and fishing combos.

There are three combos, and they're tracked separately:

| Combo | Builds when you... |
| --- | --- |
| 🎯 **Catch combo** | Catch the same species |
| 💥 **KO combo** | Knock out the same species in battle |
| 🎣 **Fishing combo** | Fish up the same species |

Fossil revives also build a combo of their own.

***

## ✨ Shiny odds near you

Your **catch combo and KO combo are added together**. The bigger the total, the better the shiny odds for that species when it spawns near you. Normal shiny odds are **1 in 32,768**.

| Catch + KO combo | Shiny odds for that species |
| --- | --- |
| 0 to 24 | 1 in 32,768 |
| 25 | 1 in 16,384 |
| 50 | 1 in 8,192 |
| 75 | 1 in 5,461 |
| 100 | 1 in 4,096 |
| 150 | 1 in 2,731 |
| 200 | 1 in 2,048 |
| 250 | 1 in 1,365 |
| 300+ | 1 in 1,024 |

* A boosted shiny is **reserved for you**, so other players can't steal it.
* You'll get a message in chat when your combo pays off.

{% hint style="warning" %}
⚠️ When a combo-boosted shiny spawns, **both your catch combo and your KO combo go back to zero**. A shiny you find by normal luck doesn't reset anything.
{% endhint %}

***

## 💪 Perfect IVs & hidden abilities

Your **catch combo** also improves the Pokémon you catch.

| Catch combo | Bonus |
| --- | --- |
| 30+ | 1 in 200 chance of a hidden ability |
| 50 | 1 guaranteed perfect IV |
| 100 | 2 guaranteed perfect IVs |
| 150 | 3 guaranteed perfect IVs |
| 200+ | 4 guaranteed perfect IVs |

***

## 🎣 Fishing combo

Fishing has its own combo with its own rewards.

| Fishing combo | Shiny odds | Perfect IVs |
| --- | --- | --- |
| 10 | 1 in 16,384 | |
| 15 | | plus a 1 in 200 hidden ability chance |
| 20 | 1 in 10,923 | |
| 25 | | 1 |
| 30 | 1 in 8,192 | |
| 40 | 1 in 6,554 | |
| 50 | 1 in 5,461 | 2 |
| 60 | 1 in 4,681 | |
| 70+ | 1 in 4,096 | |
| 75 | | 3 |
| 100+ | | 4 |

When a boosted fishing shiny bites, your fishing combo resets to zero.

***

## 🦴 Fossil revives

Reviving the same fossil Pokémon builds a revive combo.

| Revive combo | Shiny odds | Perfect IVs |
| --- | --- | --- |
| 5 | | 1 |
| 10 | | 2 |
| 15 | 1 in 10,923 | |
| 20 | | 3 |
| 30 | 1 in 6,554 | |
| 35+ | | 4 |
| 50 | 1 in 4,681 | |
| 80+ | 1 in 3,641 | |

Hidden ability chances from fossils go up with the **total** number of fossils you've ever revived: 1 in 200 after 50, 2 in 200 after 100, and 3 in 200 after 150.

***

## 🧲 Your combo Pokémon finds you

Once your catch combo reaches 20, some wild Pokémon that spawn within 48 blocks of you turn into the species you're chaining.

| Catch combo | Chance a nearby spawn becomes your combo Pokémon |
| --- | --- |
| 20 | 14% |
| 40 | 22% |
| 60 | 29% |
| 80 | 37% |
| 100+ | 45% |

* It works best in your combo Pokémon's usual biome. Outside it, the chance drops by about a third.
* Legendaries, Mythicals, Ultra Beasts, Paradox Pokémon and other players' shinies are never swapped out.

{% hint style="success" %}
💡 Your combos are shared between the Hub and Survival, so you can keep a chain going in the Resource World or on Survival.
{% endhint %}
