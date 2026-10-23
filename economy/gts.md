---
description: The Global Trade Station, the server-wide marketplace for Pokémon and items.
---

<!-- Sources: owner FAQ doc (GTS questions), test-server/config/RGTS/config.json + _archive/network-hub-1.7.3-mirror/config/RGTS/config.json (minimumListingPrice 100, auctions 1h to 3d, bidIncrementPercentage 0.1, impactor:dollars), network/_upload/{hub,survival}/config/RGTS/price_control.json (shiny minimum 50,000, max 5,000,000),
network/_upload/{hub,survival}/config GTS add-on settings (tax 2%, fixed-price expiry 7 days not auctions, anti-snipe: bids in the last 30 s push the end to 90 s, minimum prices: legendary/mythical 150,000, ultra beast 100,000, paradox 75,000, raid shard 60,000, silver caps 35,000). -->

# 🌐 GTS (Global Trade Station)

{% hint style="info" %}
<p align="center">The GTS is the server-wide marketplace where players buy and sell Pokémon and items with each other. Type <code>/gts</code> to open it. It's one marketplace across both servers.</p>
{% endhint %}

***

## 🛒 Buying

Open `/gts`, browse or search the listings, and click one to buy it. Some listings are **auctions**, where you place a bid instead.

* Bids have to beat the current bid by at least **10%**.
* If someone bids in the **last 30 seconds**, the auction is pushed back so there's at least 90 seconds left. No last-second sniping!

***

## 💵 Selling

You can list a Pokémon or an item two ways:

| Type | How it works | How long it lasts |
| --- | --- | --- |
| 🏷️ **Fixed price** | Anyone can buy it straight away for your price | **7 days** |
| 🔨 **Auction** | Players bid, and the highest bid wins | You choose, from 1 hour to 3 days |

* A **2% sales tax** is taken from every sale.
* When a fixed-price listing expires, the Pokémon or item goes back to your **GTS Vault**. You don't need to be online.
* Cancelling a listing is free. It goes back to your Vault.

### 💲 Minimum prices

| Listing | Lowest price allowed |
| --- | --- |
| Anything | $100 |
| Shiny Pokémon | $50,000 |
| Paradox Pokémon | $75,000 |
| Ultra Beasts | $100,000 |
| Legendary and Mythical Pokémon | $150,000 |
| Silver Bottle Caps | $35,000 |
| Raid Shards | $60,000 |

The highest price anything can be listed for is **$5,000,000**.

***

## 🏦 Your GTS Vault

Money from sales doesn't go straight into your balance. It goes into your **GTS Vault**, along with Pokémon from expired listings and items from cancelled ones.

To collect, open `/gts` and **click your player head**. Your Vault keeps everything as long as you like, so there's no rush.

***

{% hint style="warning" %}
⚠️ Renaming Pokémon to advertise on the GTS is against the [rules](../getting-started/rules.md).
{% endhint %}
