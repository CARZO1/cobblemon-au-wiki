---
description: Warps, shortcuts and switching between servers.
---

<!-- Sources: network/_upload/{hub,survival}/config/skiesguis/guis/warp_menu.json (menu entries), network/_upload/{hub,survival}/config/commandaliases/*.json and the 1.7.3 mirror alias sets (shortcut commands, E4 lock), network/_upload/hub/config/commandaliases/gyms.json, test-server/config/commandaliases/end.json (End requirement), test-server/config/blanketrtp/blanketrtp/config.jsonc (rtp radius, cooldown, glide). -->

# Getting around

{% hint style="info" %}
<p align="center">Type <code>/warps</code> for a menu of every location on the network. If a place is on the other server, the warp switches you over automatically.</p>
{% endhint %}

***

## 📍 Warp shortcuts

| Command | Takes you to | Server it's on |
| --- | --- | --- |
| `/hub` or `/lobby` | The Hub lobby | Hub |
| `/survival` or `/smp` | Survival spawn | Survival |
| `/pokecenter` | Pokémon Center | Hub |
| `/pokemart` | PokéMart | Hub |
| `/quest_hub` | The quest area | Hub |
| `/crates` | Crates | Hub |
| `/gacha` | Gacha Machines | Hub |
| `/ev_tower` | EV Training Tower | Hub |
| `/hall_of_fame` | Hall of Fame | Hub |
| `/safari` | Safari Zone | Hub |
| `/market` | Player Market | Hub |
| `/gyms` | Gym menu (Kanto, Johto, Hoenn and Sinnoh) | Hub |
| `/resource` | The Resource World | Hub |
| `/end` | The End | Survival |
| `/battle_tower` | Battle Tower | Survival |
| `/rtp` | A random spot in the wild | Survival |

***

## 🌌 Getting into the End

You need to beat the first **4 gyms of one region** before you can enter the End. They have to be from the same region, so 2 Kanto badges and 2 Johto badges won't work.

Once you've got them, type `/end`. The Battle Tower is in the End too, so the same requirement applies to `/battle_tower`.

***

## 🎲 Random teleport

`/rtp` drops you somewhere random within 5,000 blocks of spawn. You start high in the air with a temporary elytra so you can glide down and pick a spot.

* On Survival it sends you into the main world. Use it to find a place for your base.
* On the Hub, `/resource` does the same thing in the Resource World.
* There's a cooldown of 2 minutes between uses. Some ranks get a shorter one.

***

## 🔀 Switching servers

Warps that change server take a few seconds while you move over.

{% hint style="info" %}
💡 If you ever arrive at spawn instead of where you were going, just use the command again. It can happen if the switch takes a little longer than usual.
{% endhint %}

{% hint style="warning" %}
⚠️ You can't warp out while you're in the middle of an Elite Four challenge or a Battle Tower run.
{% endhint %}
