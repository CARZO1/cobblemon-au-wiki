---
description: Swap a Pokémon for a random one from other players. Survival only.
---

<!-- Sources: Downloads/survival logs/logs/latest.log (WonderTrade 1.6.0 on survival only), _archive/network-survival-1.7.3-mirror/config/wondertrade/main.json (cooldown 60 min, poolMinLevel 1, poolMaxLevel 70, adjustNewPokemonToLevelRange, empty blacklist) + pool.json (~270 entries),
_archive/network-survival-1.7.3-mirror/config/commandaliases/wt.json + wondertrade.json, hub alias "only on the Survival server", owner (Survival only). Wonder Trade mod stores species/form/level/shiny/gender/nature/ability/IVs/EVs/ball/friendship/nickname; moves and held items are not kept. The CobbleSafari Rotom Phone Wonder Trade app is a different thing and is disabled. -->

# Wonder Trade

{% hint style="info" %}
<p align="center">Send one of your Pokémon into the Wonder Trade pool and get a random Pokémon back that another player traded in. You never know what you'll get!</p>
{% endhint %}

{% hint style="warning" %}
⚠️ Wonder Trade only works on the **Survival** server.
{% endhint %}

***

## 🔄 How to trade

{% stepper %}
{% step %}
### Pick a Pokémon

Put the Pokémon you want to trade away in your party and note which slot it's in (1 to 6).
{% endstep %}

{% step %}
### Start the trade

Type `/wt <slot>`. For example, `/wt 3` trades the Pokémon in your third party slot.
{% endstep %}

{% step %}
### Confirm

Check the message in chat, then click it to confirm. Your Pokémon goes into the pool and you get a random one back straight away.
{% endstep %}
{% endstepper %}

***

## 📏 The rules

| | |
| --- | --- |
| ⏱️ **Cooldown** | One trade every **60 minutes** |
| 📊 **Level** | What you get back is between level 1 and 70 |
| ✨ **Anything goes** | Shinies and Legendaries can go into the pool, so you might get lucky |
| 📢 **Announcements** | Every Pokémon added to the pool is announced in chat, and shinies stand out in yellow |

***

## 🎒 What you keep and what you lose

The Pokémon you get keeps its species, form, level, shiny status, gender, nature, ability, IVs, EVs, Poké Ball, friendship and nickname.

{% hint style="danger" %}
<p align="center"><strong>Take off any held item before you trade.</strong> Held items don't go through Wonder Trade, so you'll lose them. Moves aren't kept either.</p>
{% endhint %}
