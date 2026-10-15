---
description: Turn player-vs-player combat on or off.
---

<!-- Sources: network/_upload/survival/config/pvptoggle/pvptoggle-config.json (default off, 60s toggle cooldown, 30s combat flag, protect_tameables, no combat-log punishment), Downloads/{hub,survival} logs/logs/latest.log (pvptoggle loaded on both), owner (/pvp free for all). -->

# ⚔️ PvP toggle

{% hint style="info" %}
<p align="center">Player-vs-player combat is <strong>off</strong> for everyone by default. You can turn it on with <code>/pvp</code> if you want to fight other players.</p>
{% endhint %}

***

## 🔧 How it works

| | |
| --- | --- |
| ⌨️ **Command** | `/pvp` turns it on or off. `/pvp status` shows your setting. |
| 🤝 **Both players** | You can only hurt another player if you **both** have PvP on |
| ⏱️ **Cooldown** | 60 seconds between switching it on and off |
| 🔥 **In combat** | After you hit or get hit by a player, you're in combat for 30 seconds and can't turn PvP off |
| 🐾 **Your Pokémon** | Other players can't hurt your Pokémon, even with PvP on |

{% hint style="success" %}
💡 This is about hitting each other with swords and bows. Pokémon battles between players don't need PvP on. Use `/challenge <player>` for a friendly battle or `/wager` for a battle with money on it.
{% endhint %}
