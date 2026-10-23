---
description: Every command you can use as a player, grouped by what it's for.
---

<!-- Sources: network/_upload/{hub,survival}/config/commandaliases/*.json and the 1.7.3 mirror alias sets (_archive/network-*-1.7.3-mirror/config/commandaliases), staff permission gates (gated commands left out),
_archive/live-server/mods/luckperms/luckperms-2026-08-21-21-07.json.gz (default group: EC homes/tpa, poketrade, pokeshout, kits.claim.starter),
dev/{wager,champion,towerrules,rankedrewards,nuzlocke,gogyms,shops,quests,combocmd,dexgenrewards,pokehunt,banlist,pokemorph-standalone} command classes (syntax + level-0 nodes),
cobblemonchallenge-fabric-2.5.0.jar, cobblemon-economy-0.0.19.jar, pvptoggle-1.4.0 (default true).
Live mod lists: Downloads/{hub,survival} logs/logs/latest.log (14-15 Oct 2026).
Owner 15 Oct: /pwiki, /hat, /casual free for everyone; /pc Rival and up; /boosters and /back are staff only (left out). -->

# ⌨️ Player commands

{% hint style="info" %}
<p align="center">Everything here works for every player unless it says otherwise. The <strong>Server</strong> column tells you where a command works. Most Hub-only commands will send you to the Hub if you use them on Survival.</p>
{% endhint %}

***

## 🧭 Getting around

| Command | What it does | Server |
| --- | --- | --- |
| `/hub` or `/lobby` | Go to the Hub lobby | Both |
| `/survival` or `/smp` | Go to Survival spawn | Both |
| `/warps` | Open the warp menu with every location | Both |
| `/spawn` | Go to the spawn point of the server you're on | Both |
| `/pokecenter` | Pokémon Center | Both |
| `/pokemart` | PokéMart | Both |
| `/crates` | The crates, where you open your keys | Both |
| `/gacha` | Gacha Machines | Both |
| `/quest_hub` | The quest area | Both |
| `/ev_tower` | EV Training Tower | Both |
| `/hall_of_fame` | Hall of Fame, showing each region's Champion | Both |
| `/safari` | Safari Zone | Both |
| `/underground` | Sinnoh Underground | Both |
| `/market` | Player Market | Both |
| `/gyms` | Gym menu for all four regions | Both |
| `/end` | The End. You need 4 gym badges from one region. | Both |
| `/battle_tower` | Battle Tower (in the End) | Both |
| `/resource` | Resource World | Both |
| `/rtp` | Random teleport into the wild | Both |

***

## 🏡 Homes, teleports & claims

| Command | What it does | Server |
| --- | --- | --- |
| `/home set <name>` | Set a home where you're standing | Survival |
| `/home tp <name>` | Teleport to a home | Survival |
| `/home delete <name>` | Delete a home | Survival |
| `/home list` | List your homes | Survival |
| `/tpa <player>` | Ask to teleport to a player | Both |
| `/tpahere <player>` | Ask a player to teleport to you | Both |
| `/tpaccept` / `/tpdeny` | Accept or deny a teleport request | Both |
| `/flan menu` | Manage the claim you're standing in | Survival |
| `/flan list` | List your claims and their coordinates | Survival |
| `/flan delete` | Delete the claim you're standing in | Survival |
| `/redeem` | Turn claim block vouchers in your inventory into claim blocks | Survival |

{% hint style="info" %}
Your claim tool is the **golden hoe** from the Starter kit. See the [FAQ](getting-started/faq.md) for how to claim land.
{% endhint %}

***

## 🐾 Pokémon

| Command | What it does | Server |
| --- | --- | --- |
| `/poketrade <player>` | Start a trade with a player | Both |
| `/pokeshout <slot>` | Show off a party Pokémon in chat | Both |
| `/wt <slot>` | Wonder Trade a party Pokémon for a random one. Click the message in chat to confirm. | Survival |
| `/combo` | Check your current catch chain | Both |
| `/dexrewards` | Claim Pokédex rewards | Both |
| `/pokehunt` | See this round's Wanted Pokémon | Both |
| `/legendperfume` | Check your active [Legendary or Mythical Perfume](pokemon/legendary-perfumes.md) | Both |
| `/pwiki <pokemon>` | Open the Pokémon wiki: stats, types, spawns, evolutions and moves | Both |

***

## ⚔️ Battles

| Command | What it does | Server |
| --- | --- | --- |
| `/challenge <player>` | Challenge a nearby player to a friendly battle | Both |
| `/wager <player> <singles\|doubles\|triples> <amount>` | Challenge a player to a battle for money | Both |
| `/wager accept` / `deny` / `cancel` | Answer or cancel a wager | Both |
| `/ranked` | Open the [Ranked Battles](battling/ranked.md) menu | Both |
| `/casual` | Queue for casual (unranked) battles | Both |
| `/glory` | Check your Glory balance | Both |
| `/glory history` / `/glory top` | Your Glory history, and the Glory leaderboard | Both |
| `/gloryshop` | Spend Glory in the Glory Shop | Both |
| `/champion` | See who holds each Champion title | Both |
| `/champion challenge <region> [singles\|doubles]` | Challenge a region's Champion | Both |
| `/champion accept` / `decline` / `ready` | Answer a title challenge, or skip the wait between games | Both |
| `/teams` | Join a [GO Gym](battling/go-gyms.md) team | Both |
| `/teams leaderboard` | See how the teams are going | Both |
| `/bp` | Check your Battle Points | Survival |
| `/bp_shop` | Spend Battle Points | Survival |
| `/bt_info` | How the Battle Tower works | Survival |
| `/bt_top [singles\|doubles]` | Battle Tower leaderboard | Survival |
| `/nuzlocke` | The weekly [Nuzlocke Challenge](battling/nuzlocke.md) | Hub |
| `/bans` | See what's banned in gym battles and the Battle Tower | Both |
| `/pvp` | Turn player-vs-player combat on or off (off by default) | Both |

***

## 💰 Money & trading

| Command | What it does | Server |
| --- | --- | --- |
| `/bal` | Check your balance | Both |
| `/pay <player> <amount>` | Send money to another player | Both |
| `/gts` | Open the Global Trade Station | Both |
| `/plot rent <weeks>` | Rent the Market plot you're standing in | Hub |
| `/plot extend <owner> <weeks>` | Pay more weeks on a plot | Hub |
| `/plot info` / `/plot list` | Details about a plot, or a list of plots | Hub |
| `/plot trust <player>` / `untrust <player>` | Let a player build on your plot | Hub |
| `/plot abandon <plot>` | Give up your plot | Hub |
| `/shop create <price> <amount>` | Turn the container you're looking at into a shop | Hub |
| `/market warp <player>` | Visit a player's Market shop | Both |

***

## 🎁 Rewards & progress

| Command | What it does | Server |
| --- | --- | --- |
| `/quest` | Open the quest board | Both |
| `/vote` | Voting links | Both |
| `/votemilestones` | Vote milestone rewards | Both |
| `/kits` | Claim your kits | Hub |
| `/rankbonus` | Claim your one-time rank bonus | Hub |

***

## 💬 Chat & other

| Command | What it does | Server |
| --- | --- | --- |
| `/rules` | Show the server rules | Both |
| `/msg <player> <message>` | Send a private message | Both |
| `/store` | Link to the store | Both |
| `/afk` | Mark yourself as away | Both |
| `/hat` | Wear the item in your hand as a hat | Both |

***

## ⭐ Supporter and rank commands

These need the right rank. See [Ranks / Supporter](getting-started/supporting.md).

| Command | What it does | Who |
| --- | --- | --- |
| `/pokemorph <1-6>` | Turn into a Pokémon from your party | Supporter |
| `/pokemorph clear` | Turn back | Supporter |
| `/supporter` | Go to the Supporter Lounge | Supporter |
| `/pc` | Open your PC from anywhere | Rival and up |
| `/pokeheal` | Heal your whole party anywhere | Some ranks |
