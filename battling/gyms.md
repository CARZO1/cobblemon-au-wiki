---
description: Take on the gyms of Kanto, Johto, Hoenn and Sinnoh, then the Elite Four and the hidden trainers.
---

<!-- Sources: network/docs/GYM-LEADER-COMMANDS.md (13 Oct: GEN_9_SINGLES_FLAT_50 + maxItemUses 2 for gyms, prize 10,000 x gym number, badge item, gym N needs gym N-1, can't re-fight; E4 = GEN_9_SINGLES/DOUBLES at the player's own levels, level 100 RunBun teams, win moves on / loss resets; hidden trainers Red/Ethan/Steven/Cynthia: E4 beaten, once only, no items, $100,000, Steven + Cynthia doubles),
network/_upload/{hub,survival}/config/skiesguis/guis/gyms_{kanto,johto,hoenn,sinnoh}.json (leaders, menu, locked gyms), the gym ban config (maxLegendaries 2, maxParadox 1, 26 Pokemon, 7 abilities, 16 moves, 49 items, 2 Tera types), test-server/config/commandaliases/end.json (4 badges of one region -> End), live hub logs (all four regions + E4 live). -->

# Gyms & Elite Four

{% hint style="info" %}
<p align="center">Cobblemon AU has the gyms of <strong>four regions</strong>: Kanto, Johto, Hoenn and Sinnoh. Beat all 8 gyms in a region to take on its <strong>Elite Four</strong>, then challenge for the region's <a href="champions.md">Champion</a> title.</p>
{% endhint %}

***

## 🗺️ Getting to the gyms

Type `/gyms` to open the gym menu. Use the arrows to flip between regions, then click a gym to warp there. Gyms you haven't unlocked yet show a barrier.

* In each region you beat the gyms **in order**: Gym 2 unlocks after Gym 1, and so on.
* The regions are separate, so you can work on several at once.
* Each gym can only be beaten **once**.

***

## 🏟️ The gym leaders

{% tabs %}
{% tab title="Kanto" %}
| # | Leader | Type |
| --- | --- | --- |
| 1 | Brock | Rock |
| 2 | Misty | Water |
| 3 | Lt. Surge | Electric |
| 4 | Erika | Grass |
| 5 | Koga | Poison |
| 6 | Sabrina | Psychic |
| 7 | Blaine | Fire |
| 8 | Giovanni | Ground |
{% endtab %}

{% tab title="Johto" %}
| # | Leader | Type |
| --- | --- | --- |
| 1 | Falkner | Flying |
| 2 | Bugsy | Bug |
| 3 | Whitney | Normal |
| 4 | Morty | Ghost |
| 5 | Chuck | Fighting |
| 6 | Jasmine | Steel |
| 7 | Pryce | Ice |
| 8 | Clair | Dragon |
{% endtab %}

{% tab title="Hoenn" %}
| # | Leader | Type |
| --- | --- | --- |
| 1 | Roxanne | Rock |
| 2 | Brawly | Fighting |
| 3 | Wattson | Electric |
| 4 | Flannery | Fire |
| 5 | Norman | Normal |
| 6 | Winona | Flying |
| 7 | Tate & Liza | Psychic (double battle) |
| 8 | Wallace | Water |
{% endtab %}

{% tab title="Sinnoh" %}
| # | Leader | Type |
| --- | --- | --- |
| 1 | Roark | Rock |
| 2 | Gardenia | Grass |
| 3 | Fantina | Ghost |
| 4 | Maylene | Fighting (double battle) |
| 5 | Crasher Wake | Water |
| 6 | Byron | Steel |
| 7 | Candice | Ice |
| 8 | Volkner | Electric |
{% endtab %}
{% endtabs %}

***

## ⚔️ Gym battles

| | |
| --- | --- |
| 📊 **Level** | Your Pokémon are set to **level 50** for the battle |
| 🎒 **Items** | You can use up to **2** bag items per battle |
| 🏅 **Reward** | The gym's **badge**, plus **$10,000 × the gym number** ($10,000 for Gym 1, up to $80,000 for Gym 8) |

{% hint style="success" %}
🌌 Beat the first **4 gyms of any one region** to unlock **the End** and the [Battle Tower](battle-tower.md). The 4 badges have to come from the same region.
{% endhint %}

***

## 📏 Gym rules

Your team is checked before every gym, Elite Four and hidden trainer battle. If it breaks a rule, the leader tells you why and won't battle.

* At most **2 Legendary or Mythical** Pokémon, combined.
* At most **1 Paradox** Pokémon.
* Some Pokémon, abilities, moves, held items and Tera Types are banned, including most server-exclusive forms, every Z-Crystal, and Shadow and Crystal Tera.

Type `/bans` in game to see the full gym ban list.

***

## 👑 The Elite Four

Beat all 8 gyms in a region and you can enter its Elite Four from the gym menu.

{% tabs %}
{% tab title="Kanto" %}
Lorelei → Bruno → Agatha → **Lance**
{% endtab %}

{% tab title="Johto" %}
Will → Koga → Bruno → **Karen**
{% endtab %}

{% tab title="Hoenn" %}
Sidney → Phoebe → Glacia → **Drake**
{% endtab %}

{% tab title="Sinnoh" %}
Aaron → Bertha → Flint (double battle) → **Lucian**
{% endtab %}
{% endtabs %}

* Face the four members **in order**. Win and you move on to the next room.
* **Lose and you're sent back to the start.** You'll need to beat all four again.
* Elite Four battles are **not** levelled down. You battle at your Pokémon's real levels, and every Elite Four team is **level 100**.
* You can use up to **3** bag items per battle.
* You can't warp out in the middle of an Elite Four run.

Beat the final member and you've conquered that region's Elite Four. That lets you challenge for the region's [Champion](champions.md) title, take on its hidden trainer, and enter the [Nuzlocke Challenge](nuzlocke.md).

***

## 🔍 Hidden trainers

Each region hides one legendary trainer, waiting for players who've beaten its Elite Four.

| Region | Trainer | Format |
| --- | --- | --- |
| Kanto | **Red** | Singles |
| Johto | **Ethan** | Singles |
| Hoenn | **Steven** | Doubles |
| Sinnoh | **Cynthia** | Doubles |

* **No items** can be used.
* Each one can only be beaten **once**, and pays **$100,000**.
* Finding them is up to you!
