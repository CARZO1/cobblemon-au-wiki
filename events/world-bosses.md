---
description: Climb Mt. Coronet, beat Team Galactic, then fight Dialga and Palkia yourself at Spear Pillar.
---

<!-- Sources: network/docs/WORLD-BOSS.md (owner's hand-off: trial order, tickets, lobby, the fight, downed/revive, barriers, rewards, win lock),
worldboss 0.4.4 jar data/worldboss/worldboss/dialga_palkia.json (time limits 1320/1200/1080 s for 2/3/4 fighters, rangedScale 0.4, reward extras and chances, eligibility 1.5% damage or 40% on your feet) and loot_table/rewards/dialga_{participant,mvp}.json,
config/worldboss/config.json (tickets $75,000, 2 to 4 fighters, 60 s lobby, 10 s when full, 3 day wait after a loss, a win locks the boss for good),
config/worldboss/trial.json as uploaded to the hub 18 Nov 2026 (9 tablets, 3 shrines, 5 machines, Mars singles / Jupiter doubles / Saturn triples at level 100 with no bag items, Cyrus doubles with the player's team at 50 and his at 70, hints after 3 and 6 wrong tries, no Sealed Door).
Owner 18 Nov: leave out the Articuno, Zapdos and Moltres fight (not live). The second phase is left out on purpose: it's a surprise. -->

# World Bosses

{% hint style="info" %}
<p align="center">World Bosses are legendary Pokémon you fight <strong>yourself</strong>, with a sword, a bow and quick feet. Climb Mt. Coronet, get past Team Galactic, then take on <strong>Dialga and Palkia at the same time</strong> at Spear Pillar with up to 3 friends.</p>
{% endhint %}

***

## 🗝️ How it works

{% stepper %}
{% step %}
### Climb Mt. Coronet

Finish the Mt. Coronet trial: read the ancient tablets, wake the three lake guardians, shut down Team Galactic's machines and beat its three commanders. You only do this once.
{% endstep %}

{% step %}
### Beat Cyrus

Cyrus waits at Spear Pillar on the summit. Beat him once and you can buy tickets for good.
{% endstep %}

{% step %}
### Buy a ticket

Type `/worldboss ticket buy`. Each ticket costs **$75,000**.
{% endstep %}

{% step %}
### Ready up with your team

Stand on the summit of Mt. Coronet with a ticket and type `/worldboss ready`. Fights take **2 to 4 players**.
{% endstep %}

{% step %}
### Bring them down

Beat Dialga and Palkia before the timer runs out.
{% endstep %}
{% endstepper %}

***

## 🏔️ The Mt. Coronet trial

Mt. Coronet is the great mountain in the middle of Sinnoh, with Oreburgh, Eterna and Hearthome at its foot. Type `/gyms`, flip to Sinnoh and warp to a gym there, then head for the mountain.

| Step | What to do |
| --- | --- |
| 📜 **Ancient tablets** | Nine old inscriptions are hidden on and inside the mountain. Right-click one to copy it into your journal. Tablets you haven't read yet sparkle. |
| ✨ **The lake guardians** | Uxie, Mesprit and Azelf each have a shrine. Read all three of a guardian's tablets and its shrine starts listening. Each guardian wants something different from you and your team, and the tablets are your clues. |
| ⚙️ **Team Galactic's machines** | Five machines are hidden around the mountain. Solve each one's puzzle to shut it down. Do them in any order, whenever you like. |
| ⚔️ **The commanders** | Commander Mars, Jupiter and Saturn guard the way up, in that order. They won't battle you until all three guardians are awake and every machine is shut down. |
| 👑 **Cyrus** | Cyrus only battles players who have beaten all three commanders. |

Right-click a commander or Cyrus to battle them. You need to be standing right next to them.

{% hint style="success" %}
📖 Type `/worldboss trial` to open your journal: every inscription you've read, the hints you've earned, the machines, the commanders and what to do next.
{% endhint %}

{% hint style="info" %}
💡 Stuck at a shrine? After **3 wrong tries** the guardian gives you a hint. After **6**, it tells you exactly what it wants.
{% endhint %}

### Battle rules

| | Commanders | Cyrus |
| --- | --- | --- |
| 🎯 **Format** | Mars: singles. Jupiter: doubles. Saturn: a **triple battle** | Doubles |
| 📈 **Levels** | Everyone at level 100 | Your team at level 50, his at level 70 |
| 🎒 **Bag items** | Not allowed | Not allowed |
| 📏 **Gym rules** | Yes | Yes |

The [gym rules](../battling/gyms.md#gym-rules) apply to every trial battle, so you can bring at most 2 Legendary or Mythical Pokémon. Expect tough teams: every commander has legendaries of their own.

***

## 🎟️ Tickets

* Type `/worldboss ticket buy [amount]` to buy tickets for **$75,000** each. You can buy them once you've beaten Cyrus.
* Your tickets are bound to you, so nobody else can use them.
* A ticket is only used up when a fight actually starts. If the fight is called off, or the server restarts in the middle of it, you get your ticket back.

***

## 🌀 Starting a fight

* Stand on the **summit of Mt. Coronet** with a ticket and type `/worldboss ready`.
* The first player to ready up opens a **60 second** lobby. Anyone else at the summit can ready up to join, and the countdown drops to 10 seconds once all 4 spots are full.
* Changed your mind? `/worldboss unready` before the fight starts.
* Missed the start? For the first 90 seconds of a fight, players with a ticket can still ready up into a free spot.
* **One group at a time.** While a group is fighting, nobody else can get into Spear Pillar. You'll get a message in chat when it's free again.

***

## ⚔️ The fight

Dialga and Palkia come down through portals at Spear Pillar **together**. Each has its own health bar, and a third bar counts down your time.

| Players | Time limit |
| --- | --- |
| 2 | 22 minutes |
| 3 | 20 minutes |
| 4 | 18 minutes |

If the timer runs out, the legends escape.

### Bigger group, tougher fight

The fight scales with how many of you there are. Every extra player makes the legends:

* ❤️ tougher, with **more health**
* ⚡ attack **more often** and hit a little **harder**
* 💥 throw **more hazards** into each attack
* 💎 put up **more crystals** when a barrier goes up

Smaller groups get more time to make up for it. Once a player is out of the fight, the legends ease off a little to match. Their health is set when the fight starts, and anyone who joins late adds to it.

### Hurting them

* ⚔️ **Swords and axes** do the real damage. **Charge your swings**: spam-clicking barely scratches them, while full-charge hits (and falling crits) hit hard.
* 🏹 **Bows** work, but arrows only do 40% damage.
* 🧪 **Balms** from the four dispensers on the platform hit very hard. Each dispenser needs 30 seconds to refill.
* 🚫 **No Pokémon.** You can't send out Pokémon during a World Boss fight.

### Staying alive

* 👀 **Every attack is telegraphed.** Watch for marks on the floor in the boss's colour, listen for the warning sounds, and read the big titles. A skilled player can dodge any single attack.
* 🛡️ **Armour matters a lot.** The attacks are balanced around enchanted netherite. With no armour on, you take nearly 3 times the damage.
* 🎯 **They hunt separately.** Dialga and Palkia go after different players, so nobody gets to hide behind a teammate.
* 🧱 **No hiding.** An invisible wall at the platform's edge keeps everyone on the floor. If you fall off, you're put back on the platform, minus 2 hearts.

### Downed, not out

Nobody dies in a World Boss fight. A hit that would kill you **knocks you down** instead, and you can only crawl.

* A teammate can **crouch next to you for 3 seconds** to revive you.
* If nobody revives you within **30 seconds**, you're out for the rest of the fight and watch in spectator mode. You still count for rewards.
* If **everyone** is down at the same time, the fight is lost.

### Barriers

At certain points, each legend shields itself and starts to heal: Dialga's **Adamant Barrier** and Palkia's **Lustrous Barrier**. Glowing crystals rise around the arena. Smash them all with swords or balms to shatter the barrier. The boss is then stunned for a few seconds and takes **1.5 times damage**, so hit it hard.

The legends keep attacking the whole time, so split your team between dodging and smashing.

### One down, one to go

When one legend falls, it stays down, and the other one is **enraged** and gets faster. Bring down the second one to win.

***

## 🎁 Rewards

To get rewards you need to be online when the fight ends, and either deal at least **1.5% of the damage** or spend **40% of the fight on your feet**. Damage to barrier crystals counts.

Everyone who qualifies on a winning team gets:

| Reward | Chance |
| --- | --- |
| 💵 $150,000 | Always |
| 🍬 8 to 12 Rare Candies | Always |
| 🍬 4 to 8 Exp. Candy XL | Always |
| 🏆 20 Battle Points or 35 Glory | Always (one or the other) |
| 🔑 2 Mega Stone Crate keys | Always |
| 🔑 A Hat, Shiny or Legendary Crate key | Always (Hat 75%, Shiny 20%, Legendary 5%) |
| 🟣 Master Ball | 60% |
| 💎 Adamant Crystal | 35% |
| 🔮 Lustrous Globe | 35% |
| 🧸 Plushie Crate key | 20% |
| 🪙 2 Relic Coin Sacks | 20% |
| 🔑 Paradox Crate key | 15% |
| 🔑 Ultra Beast Crate key | 15% |
| 🔑 Radiant Crate key | 5% |
| 🃏 Shiny Card | 1% |
| 🃏 Alpha Card | 1% |

The **top 3 players by damage** also get **$25,000**, a [Catch Booster](../pokemon/catch-boosters.md) and a 50% chance at an Ability Capsule. On top of that:

| Place | Bonus |
| --- | --- |
| 🥇 1st | Ultra Shiny Incense |
| 🥈 2nd | Great Shiny Incense |
| 🥉 3rd | Shiny Incense |

***

## 🔒 Win once, or wait and try again

* **Win** and you've beaten Dialga and Palkia for good. You can't fight them again for rewards.
* **Lose** (the timer runs out or everyone goes down) and everyone in that fight waits **3 days** before they can try again. Leaving a fight early counts as a loss for you, even if your team goes on to win.
* `/worldboss` shows how long you have left to wait.

***

## ⌨️ Commands

| Command | What it does |
| --- | --- |
| `/worldboss` | Your World Boss status: tickets, Cyrus, bosses you've beaten and any wait |
| `/worldboss trial` | Open your Mt. Coronet journal |
| `/worldboss ticket` | How many tickets you're carrying, and whether you can buy more |
| `/worldboss ticket buy [amount]` | Buy tickets ($75,000 each, up to 8 at a time) |
| `/worldboss ready` | Ready up for the next fight (on the summit) |
| `/worldboss unready` | Leave the lobby before the fight starts |
| `/worldboss join` | Go to the Spear Pillar lobby from the summit, when it's open |
| `/worldboss leave` | Leave a fight you're in |

The commanders and Cyrus don't have a command: right-click them to battle.

{% hint style="info" %}
💡 Before you ready up: put on your best enchanted armour, bring a sharp sword and some food, and agree with your team on who goes for the crystals when a barrier goes up.
{% endhint %}
