---
description: Breed Pokémon in a Daycare, hatch eggs in an Incubator, and pass down IVs, natures and abilities.
---

<!-- Sources: test-server/mods/daycareplus-1.5.0+1.21.1.jar (lang, breeding rules, recipes, behaviour), _archive/network-{hub,survival}-1.7.3-mirror/config/daycareplus/server-config.json (max_pastures_per_player 2, pasture_inventory_size 16, ticks_per_egg_attempt 12000, success_rate 0.75, produce_for_offline_players, use_competitive_mode, consume_held_items false, inherit_moves_from_both_parents, masuda_multiplier 2, ticks_per_egg_cycle 200) + incubators.json,
Destiny Knot passes 5 IVs (checked in mod code), cobblemonau_breeding.zip (Destiny Knot allowed), network/_upload/hub/config/cobblemon/main.json (shinyRate 32768), network/_upload/survival/config/skiesguis/guis/bt_shop*.json (Fertility Candy, Dizygotic/Sparkling Booster, Mirror Herb),
network/_upload/{hub,survival}/openloader-1.8/cobblemonau_easter_locked.zip (Easter forms lay normal eggs). network/docs/BREEDING-EXPLAINER.md is out of date; not used.
Owner pasted the live server-config.json on 16 Oct: max_fertility 4, shiny_booster_rate 2.0 (test-server copy updated to match). The Sparkling Booster's exact strength is left vague on purpose. -->

# Breeding & eggs

{% hint style="info" %}
<p align="center">Put two compatible Pokémon in a <strong>Daycare</strong> and they'll lay eggs, even while you're offline. Collect the eggs with an <strong>Incubator</strong> and they'll hatch while you carry it around.</p>
{% endhint %}

***

## 🏡 Setting up a Daycare

{% stepper %}
{% step %}
### Place a Pasture

Place a normal Cobblemon Pasture block. The first time you open it, choose **Daycare**. (Choose **Pasture** if you just want your Pokémon to hang out.)
{% endstep %}

{% step %}
### Add a breeding pair

Put **two** Pokémon in: a male and a female that share an **egg group**, or any Pokémon plus a **Ditto**. You can see egg groups in the summary screen.
{% endstep %}

{% step %}
### Wait for eggs

The Daycare tries for an egg every **10 minutes**, with a 75% chance each time. That's about 4 or 5 eggs an hour, and it keeps going while you're offline.
{% endstep %}
{% endstepper %}

* You can run **2 Daycares** at a time.
* Each Daycare holds **16 eggs**. It stops making eggs when it's full, so collect them often. Hoppers can pull eggs out too.
* Legendaries, Mythicals and other Pokémon in the **Undiscovered** egg group can't breed.
* Ditto can't breed with another Ditto.

***

## 🌡️ Incubators & hatching

Eggs only hatch inside an **Incubator**. Right-click your Daycare with your Incubator to collect the eggs, then just keep it in your inventory.

| Incubator | Holds | Hatches at once | Crafted from |
| --- | --- | --- | --- |
| Copper | 8 | 1 | Copper Blocks + Blaze Powder |
| Iron | 64 | 2 | Iron Blocks + Copper Incubator |
| Gold | 32 | 32 | Gold Blocks + Iron Incubator |
| Diamond | 96 | 4 | Diamond Blocks + Iron Incubator |
| Netherite | 128 | 8 | Netherite Ingots + Diamond Incubator |

* Incubators belong to you. Other players can't use yours.
* Only **one** Incubator in your inventory works at a time.
* Each egg cycle takes **10 seconds**. The number of cycles depends on the species: a Pokémon with 20 egg cycles hatches in about 3 minutes, and some need a lot more.
* Having a Pokémon with **Flame Body**, **Magma Armor** or **Steam Engine** in your party hatches eggs **twice as fast**.
* Hatched Pokémon are level 1 and go to your party, or your PC if your party is full.

***

## 🧬 What gets passed down

| | How it works |
| --- | --- |
| 💪 **IVs** | 3 IVs are passed down from the parents, picked at random. The rest are random. |
| 🪢 **Destiny Knot** | If either parent holds one, **5 IVs** are passed down instead of 3 |
| ⚖️ **Power items** | Each one passes its stat from the parent holding it: Power Weight (HP), Bracer (Attack), Belt (Defence), Lens (Sp. Atk), Band (Sp. Def), Anklet (Speed) |
| 🪨 **Everstone** | The holder passes down its nature. Mints don't change what's passed. |
| ⭐ **Ability** | The baby gets the same ability slot as the mother (or the non-Ditto parent), so a hidden ability mother passes down her hidden ability |
| 🥎 **Poké Ball** | Comes from the mother (or the non-Ditto parent). Master and Cherish Balls become a normal Poké Ball. |
| ⚔️ **Egg moves** | Can come from **both** parents |
| 📏 **Size** | Somewhere between the two parents' sizes |

{% hint style="success" %}
💡 Held items like the Destiny Knot, Everstone and Power items are **not used up** when breeding, so you can keep breeding with them.
{% endhint %}

**Mirror Herb:** a Pokémon holding a Mirror Herb in the Daycare learns egg moves that its partner knows.

***

## ❤️ Fertility

Every Pokémon has a **Fertility** value, shown in its summary screen. It starts at **4**, which is also the most it can have.

* Each egg uses up **1 Fertility from both parents**, so a fresh pair can make 4 eggs together.
* A Pokémon with **0 Fertility can't breed** any more. It's not harmed in any way.
* An egg's Fertility is the lower of its two parents' after breeding.
* **Fertility Candy** gives back 1 Fertility, up to the maximum of 4. Buy it from the Battle Tower BP Shop.

***

## ✨ Shiny eggs

| | Shiny odds |
| --- | --- |
| Normal eggs | 1 in 32,768 |
| Parents with different original trainers (Masuda method) | 1 in 16,384 |

Shiny eggs look different, and the Daycare screen shows your current shiny chance.

***

## 🛒 Breeding boosters

These are sold in the Battle Tower BP Shop. Use them on your Daycare.

| Item | What it does |
| --- | --- |
| 👯 **Dizygotic Booster** | The next 5 successful egg rolls give **2 eggs** instead of 1 (each egg still costs Fertility) |
| ✨ **Sparkling Booster** | Boosts the shiny chance of your next 5 eggs |
| ❤️ **Fertility Candy** | +1 Fertility |
