---
description: Catch Boosters double your catch rate for 30 minutes, just for you.
---

<!-- Sources: dev/tools/build_catch_boost.py (14 Nov 2026): item = mega_showdown:booster_energy + custom_data {catch_boost:1b};
/redeem takes one and sets the LuckPerms temp node cobblemonau.catchboost for 30m (accumulate, shared by hub + survival);
cobblemonau_catch_boost.zip callback pokemon_catch_rate_calculated: catch rate x2 (capped 255) for the thrower only.
Sources: raid tier 6 3% (build_raid_loot.py), vote crate weight 110 (~0.5%), Hiker 'large' 4 prism_l + 4 pale_l (2 uses),
Giratina giratina_unique 5%. Owner 14 Nov 2026. -->

# Catch Boosters

{% hint style="info" %}
<p align="center">A <strong>Catch Booster</strong> <strong>doubles your catch rate for 30 minutes</strong>. It only boosts your own throws, and it keeps working on both the Hub and Survival.</p>
{% endhint %}

***

## ✨ Using one

{% stepper %}
{% step %}
### Have it in your inventory

A Catch Booster looks like a glowing pink **Booster Energy** called **Catch Booster**.
{% endstep %}

{% step %}
### Type `/redeem`

One Catch Booster is used up, and your boost starts straight away.
{% endstep %}

{% step %}
### Go catching

For the next **30 minutes**, every Poké Ball you throw has **double the catch rate**. Your boost carries on if you switch servers or log out.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
💡 Using another Catch Booster while one is running adds **30 more minutes** on top.
{% endhint %}

{% hint style="warning" %}
⚠️ The boost only works through `/redeem`. Giving a Catch Booster to a Pokémon to hold just makes it a normal Booster Energy.
{% endhint %}

***

## 🎁 Where to get them

| Source | How |
| --- | --- |
| ⭐⭐⭐⭐⭐⭐ [6 star raids](../network/raid-dens.md) | **3%** chance per Raid Pouch |
| 🗳️ [Vote Crate](../getting-started/voting.md) | A rare prize, about **1 in 200** |
| ⛏️ [Underground Hikers](../network/hoopa-portals.md#hikers-and-rewards) | Some Hikers that want large spheres trade one for **4 Prism + 4 Pale large spheres** |
| 🌌 [Giratina](../network/hoopa-portals.md#the-giratina-boss) | **1 in 20** chance per win |
