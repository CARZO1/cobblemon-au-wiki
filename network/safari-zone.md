---
description: Catch Pokémon from 18 type-themed biomes with Safari Balls, Bait and Mud Balls.
---

<!-- Sources: CobbleSafari wiki (mirrored at wiki.cobblemon-realms.com/mods-guides/CobbleSafari/{safari_dimension,wild_pokemon_safari}.html), checked against
test-server/config/cobblesafari/safari_config.json (entry fee = 1 Safari Ticket item, once per day; 24 Safari Balls, 32 Bait, 32 Mud Balls on the first visit each day; paid re-entry off;
shinyCatchMultiplier 4; canShinyFlee; flee grace 100 ticks; alpha rage 600 ticks, bait calm 0.15; Safari Balloons on), dimensional_timer_config.json (domedimension 900 s per day),
dimensional_restrictions_config.json (only Safari Balls, no battles), test-server/config/skiesguis/guis/safari_ticket.json ($500 per ticket), commandaliases/safari.json (/safari -> Hub entrance, survival hands off to hub),
cobblesafari-fabric-1.21.1-0.3.5.jar (TeleporterTickHandler: fee charged once per day, free re-entry while time is left; EntryFeeHelper: item fee = 1; SafariCatchEventHandler: shiny catch x4;
lang strings; spawn_pool_world/* = the biome table below, generated from the jar, no legendaries). -->

# Safari Zone

{% hint style="info" %}
<p align="center">The Safari Zone is a separate world made of <strong>18 biomes, one for each type</strong>. There are no battles here: you sneak up on wild Pokémon and catch them with Safari Balls, using Bait and Mud Balls to tip the odds.</p>
{% endhint %}

***

## 🚪 Getting in

{% stepper %}
{% step %}
### Head to the entrance

Type `/safari` from either server. It takes you to the Safari Zone entrance on the Hub.
{% endstep %}

{% step %}
### Get a Safari Ticket

Entry costs **1 Safari Ticket**. Buy one for **$500** at the entrance.
{% endstep %}

{% step %}
### Use the Safari Teleporter

Step onto the **Safari Teleporter** and stand still while it counts down. You'll be asked to confirm, and the ticket is taken. You land somewhere different every time.
{% endstep %}
{% endstepper %}

| | |
| --- | --- |
| ⏱️ **Time** | **15 minutes a day** |
| 🎟️ **Ticket** | Only your **first** trip of the day costs a ticket. Coming back later the same day is free while you still have time left. |
| 🎒 **Free supplies** | Your first trip each day gives you **24 Safari Balls**, **32 Bait** and **32 Mud Balls** |
| 🚶 **Leaving early** | Type `/safariexit` to go back to where you came in. Your leftover time is saved for later that day. |

Your time and free supplies reset every day. If you're inside when the Safari resets, you'll get a warning and then be sent out.

{% hint style="warning" %}
⚠️ Be careful in there. If you nearly die, you're sent out and the rest of the day's Safari time is used up.
{% endhint %}

***

## 📏 Safari rules

* **Only Safari Balls** work. Your own Poké Balls can't be used.
* **No battles,** and you can't send out your Pokémon.
* **No fishing.**
* Wild Pokémon **can run away**.

***

## 🎯 Catching

Throw Safari Balls straight at a wild Pokémon. There's no battle, so it all comes down to your aim and a bit of luck.

| Item | What it does |
| --- | --- |
| 🍖 **Bait** | Makes the Pokémon **less likely to run**, but a little **harder to catch** |
| 🟤 **Mud Ball** | Makes the Pokémon **easier to catch**, but **more likely to run** |

* **Running away:** when a Pokémon is about to flee, a warning pops up on screen. You've got about **5 seconds** for one last throw before it's gone for good.
* ✨ **Shinies** are **4 times easier to catch** in the Safari, but they can still run away, so don't waste your chance.
* 🦣 **Alphas** can get **enraged** for 30 seconds. Throwing Bait has a 15% chance to calm one down.
* 🎈 **Safari Balloons** float around the biomes. Pop them for extra Safari supplies.

***

## 🌿 What lives where

Each biome has common, uncommon, rare and ultra-rare Pokémon of its type. Every biome's **ultra-rare** is a **starter Pokémon**, so the Safari is a great place to hunt for them.

| Biome | Rare | Ultra-rare |
| --- | --- | --- |
| **Bug** | Beedrill, Butterfree, Heracross, Pinsir, Scizor, Venomoth, Vikavolt, Vivillon | Chespin |
| **Dark** | Absol, Grimmsnarl, Pupitar, Sableye, Umbreon, Weavile, Zorua | Froakie, Sprigatito |
| **Dragon** | Dragonair, Druddigon, Fraxure, Gabite, Goodra, Hakamo-o, Haxorus, Hisuian Sliggoo, Noivern, Shelgon, Sliggoo | Charmander, Totodile |
| **Electric** | Galvantula, Heliolisk, Toxtricity, Vikavolt | Rotom |
| **Fairy** | Florges, Gardevoir, Sylveon, Togekiss | Chikorita, Popplio |
| **Fighting** | Breloom, Hariyama, Heracross, Lucario, Pangoro, Riolu, Scrafty, Tyrogue | Chimchar, Torchic |
| **Fire** | Heatmor, Talonflame, Torkoal | Cyndaquil, Scorbunny |
| **Flying** | Noivern, Rufflet, Staraptor, Talonflame, Tropius | Rowlet |
| **Ghost** | Dusknoir, Gengar, Golurk, Gourgeist, Spiritomb | Cyndaquil, Fuecoco |
| **Grass** | Breloom, Gogoat, Jumpluff, Maractus, Shiftry, Victreebel, Vileplume | Snivy, Treecko |
| **Ground** | Diggersby, Excadrill, Hippowdon, Mudsdale, Palpitoad | Mudkip, Turtwig |
| **Ice** | Abomasnow, Arctibax, Avalugg, Cloyster, Dewgong, Froslass, Frosmoth, Lapras, Mamoswine, Vanilluxe, Walrein | Piplup |
| **Normal** | Chansey, Ditto, Drampa, Furfrou, Kangaskhan, Smeargle, Staraptor | Litten, Quaxly |
| **Poison** | Drapion, Toxicroak, Toxtricity | Bulbasaur |
| **Psychic** | Espeon, Gallade, Gardevoir, Girafarig, Gothorita, Reuniclus, Slowking | Fennekin |
| **Rock** | Barbaracle, Gigalith, Lycanroc, Lycanroc (Dusk), Lycanroc (Midnight), Pupitar, Shuckle | Grookey, Tepig |
| **Steel** | Aggron, Excadrill, Klefki, Lairon, Metang, Steelix | Oshawott |
| **Water** | Azumarill, Milotic, Poliwrath, Seismitoad, Wishiwashi | Sobble, Squirtle |

***

{% hint style="success" %}
💡 Looking for the Sinnoh Underground or the Distortion World? Those are reached through [Hoopa Portals](hoopa-portals.md).
{% endhint %}
