---
description: Protect your base on Survival with a land claim.
---

<!-- Sources: network/_upload/survival/config/flan/flan_config.json (startingBlocks 500, ticksForNextBlock 500, maxClaimBlocks 10000, maxClaims -1, minClaimsize 100, golden_hoe / stick, claims expire after 90 days inactive: owner 26 Oct (staged/test-server inactivityTimeDays is still -1), defaultGroups Visitor/Co-Owner), network/_upload/hub/config/flan (hub blacklists overworld + market), network/_upload/survival/config/commandaliases/redeem.json (vouchers), test-server/config/gogyms/config.json (noClaimRadius 16), owner FAQ doc (claiming steps, trust, delete, Pokemon sendout, raid crystal bypass). -->

# Land claims

{% hint style="info" %}
<p align="center">A claim stops other players from breaking, building or opening anything inside it. Claims only work on <strong>Survival</strong>.</p>
{% endhint %}

***

## ⛏️ Making a claim

{% stepper %}
{% step %}
### Get a golden hoe

The golden hoe is the claim tool. You get one in the free **Starter** kit (`/kits` on the Hub), or you can craft one.
{% endstep %}

{% step %}
### Mark the first corner

Hold the golden hoe and left-click one corner of the area you want to protect.
{% endstep %}

{% step %}
### Mark the opposite corner

Walk to the far opposite corner and left-click again. If it worked, gold blocks appear around the edge of your new claim.
{% endstep %}
{% endstepper %}

Hold a **stick** to see the edges of claims around you.

***

## 🧱 Claim blocks

Every block of ground you claim uses one claim block.

| | |
| --- | --- |
| 🎒 **Starting blocks** | 500 |
| ⏱️ **Earning more** | About 144 blocks for every hour you play |
| 📈 **Most you can earn by playing** | 10,000 |
| 📏 **Smallest claim** | 100 blocks |
| 🔢 **Number of claims** | No limit |
| 📅 **Do claims expire?** | **Yes.** Claims expire after **90 days** without logging in |

{% hint style="warning" %}
⚠️ If you don't log in for **90 days**, your claims expire and anyone can build there. Taking a long break? Let us know in our [Discord](https://discord.gg/G48XBcSNk4).
{% endhint %}

You can get extra claim blocks from **claim block vouchers**, which come from vote crates, rank bonuses and the Supporter kit. With a voucher in your inventory, type `/redeem` on Survival to add the blocks.

***

## 🤝 Sharing your claim

Stand in your claim and type `/flan menu`, then click the **book** icon to add a player.

| Role | What they can do |
| --- | --- |
| **Visitor** | Use doors, buttons, levers, trapdoors, gates, beds and the Ender Chest, and trade with villagers |
| **Co-Owner** | Pretty much everything you can: build, break, open chests, send out and battle Pokémon, and edit the claim |

***

## ⚙️ Useful settings

<details>

<summary>Stop other players sending out Pokémon in your claim</summary>

Type `/flan menu`, open **Global Permissions** (the beacon) and find the **Great Ball** on page 3. Set it to false.

</details>

<details>

<summary>Let other players use a Raid Den in your claim</summary>

1. Type `/flan menu`.
2. Click **Configure bypasses for actions**.
3. Click **Allowed block use**, then **Add**.
4. Type `cobblemonraiddens:raid_crystal_block`.
5. Click the **book** to confirm.

</details>

<details>

<summary>Delete a claim</summary>

Stand in it and type `/flan delete`. If it asks you to confirm, type `/flan confirm` or click **\[Confirm]** in chat.

</details>

<details>

<summary>Find a claim you've lost</summary>

Type `/flan list` to see all of your claims and their coordinates.

</details>

***

{% hint style="warning" %}
⚠️ You can't claim land within 16 blocks of a [GO Gym](../battling/go-gyms.md), and building around a GO Gym to hide it is against the [rules](../getting-started/rules.md).
{% endhint %}
