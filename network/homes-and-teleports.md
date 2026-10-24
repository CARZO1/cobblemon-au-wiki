---
description: Set homes and send teleport requests.
---

<!-- Sources: _archive/network-survival-1.7.3-mirror/config/EssentialCommands.properties (home_limit, teleport_request_duration=60, teleport_interrupt_on_damaged=true), _archive/live-server/mods/luckperms export (default: home.set/tp/delete, tpa/tpahere/tpaccept; tpa denied in raid/safari/E4 worlds), network/_upload/hub/config/commandaliases/home(s).json via the 1.7.3 hub mirror (hub redirects to survival), owner FAQ doc. Home counts per rank not printed: only the stale Aug export lists them. -->

# Homes & teleports

{% hint style="info" %}
<p align="center">Homes let you jump straight back to your base. Teleport requests let you visit friends, or bring them to you.</p>
{% endhint %}

***

## 🏡 Homes

Homes are on **Survival**. If you use `/home` on the Hub, you'll be sent over to Survival.

| Command | What it does |
| --- | --- |
| `/home set <name>` | Set a home where you're standing |
| `/home tp <name>` | Go to a home. Just `/home tp` works if you only have one. |
| `/home list` | List your homes |
| `/home delete <name>` | Delete a home |

Ranks get more homes. See [Ranks / Supporter](../getting-started/supporting.md).

{% hint style="success" %}
💡 Set your first home inside your claim as soon as you've built your base. If you lose track of your base, `/flan list` shows the coordinates of all of your claims.
{% endhint %}

***

## 🤝 Teleport requests

| Command | What it does |
| --- | --- |
| `/tpa <player>` | Ask to teleport to a player |
| `/tpahere <player>` | Ask a player to teleport to you |
| `/tpaccept` | Accept a request |
| `/tpdeny` | Turn a request down |

* A request lasts **60 seconds**.
* The teleport is cancelled if you take damage.
* Teleport requests don't work in raids, the Safari Zone, CobbleSafari dungeons or the Elite Four.
