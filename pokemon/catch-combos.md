---
description: Catch, battle or fish the same Pokémon over and over to boost your shiny, IV and hidden ability odds.
---

<!-- Re-checked 4 Nov 2026 against test-server/config/unchained/** (identical to both staging copies apart from a stale careAboutForms key) and test-server/config/unchained.json (boostActivatedHabitatSpawns true).
4 Nov: egg boosters switched ON (hidden egg marbles 5 -> 200); every booster blacklists any_label=legendary,mythical,ultra_beast,paradox; combosync 1.8.1 never biases spawns INTO those labels and /combosync boost refuses those chains.
Sources: network/_upload/{hub,survival}/config/unchained/{spawn,capture,fish,resurrection,egg,snack}/*.json (thresholds, enabled, breakStreakOnSuccess, lockToPlayer, marbles),
network/_upload/hub/config/cobblemon/main.json (shinyRate 32768), the chain spawn-bias config,
dev/combocmd ComboCmd.java (/combo shows catch + fishing chains). Shiny odds = (1 + bonus) / 32768. Snack, shiny-on-capture and spawn IV/HA boosters are disabled.
Fossil shiny odds combine Cobblemon's fossilMachineShinyChance 4000 (main.json) with unchained's extra (1 + bonus) / 32768 roll, which only runs once a bonus is unlocked (AbstractBoosterRunner skips a 0 boost). -->

# Catch combos

{% hint style="info" %}
<p align="center">Catch or knock out the same Pokémon again and again to build a <strong>combo</strong>. The longer your combo, the better your odds of finding a shiny, and the better the IVs and hidden abilities of what you catch.</p>
{% endhint %}

***

## 🔢 How a combo works

* Each kind of combo counts one species at a time.
* Catching or knocking out the **same species and form** adds 1 to your combo.
* Catching or knocking out a **different species or form** starts that combo again from zero. A Paldean Wooper and a normal Wooper are different forms!
* Type `/combo` to see your current catch and fishing combos. Egg combos aren't shown there.

There are four combos, and they're tracked separately:

| Combo | Builds when you... |
| --- | --- |
| 🎯 **Catch combo** | Catch the same species |
| 💥 **KO combo** | Knock out the same species in battle |
| 🎣 **Fishing combo** | Fish up the same species |
| 🥚 **Egg combo** | Hatch eggs of the same species |

Fossil revives also build a combo of their own (see below).

***

## 🎯 Catch combo

Catch the same species over and over. Your catch combo boosts the shiny odds for that species when it spawns near you, and improves the Pokémon you catch.

| Catch combo | Shiny odds | Perfect IVs |
| --- | --- | --- |
| 0 to 24 | 1 in 32,768 | |
| 25 | 1 in 16,384 | |
| 30 | | plus a 1 in 200 hidden ability chance |
| 50 | 1 in 8,192 | 1 |
| 75 | 1 in 5,461 | |
| 100 | 1 in 4,096 | 2 |
| 150 | 1 in 2,731 | 3 |
| 200 | 1 in 2,048 | 4 |
| 250 | 1 in 1,365 | |
| 300+ | 1 in 1,024 | |

***

## 💥 KO combo

Knock out the same species in battle over and over. Your KO combo boosts the shiny odds for that species when it spawns near you. It doesn't change IVs or hidden abilities.

| KO combo | Shiny odds |
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

{% hint style="info" %}
💡 If you catch **and** knock out the same species, the two combos are **added together** for the shiny odds. For example, a catch combo of 150 plus a KO combo of 150 counts as 300, which is 1 in 1,024.
{% endhint %}

* A boosted shiny is **reserved for you**, so other players can't steal it.
* You'll get a message in chat when your combo pays off.

{% hint style="warning" %}
⚠️ When a combo-boosted shiny spawns, **both your catch combo and your KO combo go back to zero**. A shiny you find by normal luck doesn't reset anything.
{% endhint %}

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

## 🥚 Egg combo

Hatch eggs of the same species over and over. Your egg combo improves the Pokémon that hatch, on top of anything they inherit from their parents.

| Egg combo | Shiny odds | Perfect IVs |
| --- | --- | --- |
| 0 to 19 | 1 in 32,768 | |
| 20 | | 1 |
| 40 | | 2 |
| 75 | 1 in 16,384 | |
| 80 | | 3 |
| 120 | | 4 |
| 150 | 1 in 10,923 | |
| 300+ | 1 in 8,192 | |

When a combo-boosted shiny hatches, your egg combo resets to zero.

Hidden ability chances from eggs go up with the **total** number of eggs you've ever hatched: 1 in 200 after 100, 2 in 200 after 200, and 3 in 200 after 300.

***

## 🦴 Fossil revives

Reviving the same fossil Pokémon builds a revive combo. Every revived fossil already has a 1 in 4,000 shiny chance, and your revive combo adds to it. See [Fossils & reviving](fossils.md) for how the machine works.

| Revive combo | Shiny odds | Perfect IVs |
| --- | --- | --- |
| 0 to 4 | 1 in 4,000 | |
| 5 | | 1 |
| 10 | | 2 |
| 15 | 1 in 2,928 | |
| 20 | | 3 |
| 30 | 1 in 2,484 | |
| 35+ | | 4 |
| 50 | 1 in 2,157 | |
| 80+ | 1 in 1,906 | |

When a revive combo shiny comes out, your revive combo resets to zero.

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
* A combo on a Legendary, Mythical, Ultra Beast or Paradox Pokémon never makes more of them spawn.

{% hint style="warning" %}
⚠️ Combos don't boost **Legendaries, Mythicals, Ultra Beasts or Paradox Pokémon** at all: no better shiny odds, IVs or hidden abilities, however long your combo is. Catch Combo vouchers can't be used on a combo of them either.
{% endhint %}

{% hint style="success" %}
💡 Your combos are shared between the Hub and Survival, so you can keep a chain going in the Resource World or on Survival.
{% endhint %}
