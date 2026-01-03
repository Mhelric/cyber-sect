# 🎯 CyberSect – Official Game Rules

## 1. Core Concept

**CyberSect** is a single-player, turn-based card game. You play as a **Blue Team Operator** (a cybersecurity student) defending your school's network. You battle viruses and hackers using a deck of **Protocols** (Cards) representing real-world security tools.

## 2. The Operational Loop (How to Play)

1. **Monitor:** Select a compromised node (Level) on the Overworld Map.
2. **Engage:** Enter the level and battle waves of malware using your deck.
3. **Remediate:** Reduce the Enemy's HP to 0 while protecting your own.
4. **Analyze:** Winning rewards you with **Cyber Points (CP)** and **Data Logs** (New Cards).
5. **Patch:** Visit the **Repository (Shop)** between levels to buy or upgrade cards using CP.
6. **Certify:** Defeat Chapter Bosses to unlock new **Job Classes**.

## 3. Operator Progression (Classes)

You start as a Rookie. Defeating Bosses unlocks specialized roles. You may **switch your Class** between levels on the Map Screen.

* **Tier 1: Script Kiddie (Rookie):** Balanced starter class.
* **Tier 2: Network Engineer (Defense):** Focuses on Shields and Sustainability.
* **Tier 2: Threat Hunter (Attack):** Focuses on High Damage and Aggression.
* **Tier 3: Pen Tester (Control):** Focuses on Traps and Exploiting Enemy Weakness.

## 4. Deck Architecture

* **Starter Deck:** 15 Cards (Rookie Layout).
* **Class Decks:** 10 Core Cards (Locked) + 5 Flex Slots (Customizable).
* **Hand Size:** Max 10 Cards.

### Card Types

* 🗡️ **Execute (Attack):** Deals damage to Enemy HP.
* 🛡️ **Harden (Defense):** Grants **Shield** to block damage.
* 🔧 **Patch (Utility):** Heals, draws cards, or applies Status Effects.

### The "Signature Match" Mechanic

Some cards are **Specialized**. They have a weaker base effect, but trigger a **Powerful Bonus** if the target matches a specific malware type.

* *Example:* **"Deep Clean"** deals 5 Damage normally, but **25 Damage** if the target is a **Worm**.

### Card Limits & Duplication
We utilize a "Soft Cap" system to balance deck building.

* **Common / Uncommon Cards:** **Unlimited Copies.**
    * You may stack as many copies of these cards as you wish.
    * *Balancing Rule:* Shop prices increase for each duplicate you already own (+50% CP cost per copy).
* **Rare (Ultimate) Cards:** **Unique (Limit 1).**
    * Powerful cards (e.g., *Air Gap*, *System Restore Point*) are limited to **1 copy per deck** to prevent infinite stalling or game-breaking loops.

## 5. Turn Structure

1. **Draw Phase:** Draw 2 cards. (Skip if hand is full at 10 cards).
2. **Energy Phase:** Refill **RAM** (Energy).
* *Rookie/Engineer/Hunter:* 3 RAM.
* *Pen Tester:* 4 RAM.


3. **Action Phase:** Play cards by spending RAM.
4. **Intrusion Phase:** Enemy executes their script (Attack/Buff).
5. **Status Phase:** Start/End of turn effects resolve (Poison, Stun).

## 6. Combat Metrics & Rules

* **Integrity (Health):** Pure numbers. If 0, you lose the level.
* **Firewall (Shield):** Blocks incoming damage. Resets to 0 at the start of your turn.
* **RAM (Energy):** The resource cost to play cards.
* **Reshuffle Rule:** When your draw pile is empty, your discard pile is shuffled into a new deck.
* **⚠️ Boss Fatigue:** In Boss battles, every time you Reshuffle, you take **Overheat Damage** (-5 HP, then -10, -15...). This prevents stalling.

## 7. Status Effects

**🔴 Negative (From Enemies)**

* **Stun:** You lose your next turn.
* **Locked:** A specific card in your hand cannot be played for X turns.
* **Fragile:** You take +50% damage from attacks.

**🟢 Positive (From Player)**

* **Blocking:** Prevents the next X negative status effects.
* **Disabled:** The Enemy cannot use their special ability next turn.

## 8. The Repository (Shop & Economy)

Spend **Cyber Points (CP)** earned from battles to improve your deck.

* **Stock:** 5 Random Cards + Upgrade Station.
* **Costs:**
* Common Card: 50 CP
* Uncommon Card: 120 CP
* Rare Card: 300 CP



## 9. Upgrade System ("Patch Management")

To upgrade a card, you need **Duplicate Copies** of that card plus **CP**.

* **Common Cards:** Upgrade up to Level 3. (Highly customizable).
* **Uncommon Cards:** Upgrade up to Level 2. (Optimized efficiency).
* **Rare Cards:** **Read-Only.** (Cannot be upgraded).

## 10. Loot & Drop Rates

After winning a battle, the enemy drops a **Data Log** (Card Reward).

* **Standard Enemies:** 40% Common, 10% Uncommon, 50% No Card (CP only).
* **Mini-Bosses:** 100% Uncommon Card Choice (Pick 1 of 3).
* **Chapter Bosses:** 100% Rare Card Choice (Pick 1 of 3).

## 11. Victory & Defeat

* **Level Victory:** Defeat all enemies  Get Rewards.
* **Chapter Victory:** Defeat the Boss  Unlock new Class.
* **Defeat:** HP reaches 0  Restart Level.
* **Infinite Retries:** There is no "Game Over." You can retry a level as many times as needed.

## 12. The CyberDex

The in-game encyclopedia. Every card and enemy includes a **Real World Definition** sourced from industry standards (NIST, MITRE, CISA).

* *Example:* **"Phishing"**
* **Game Effect:** Enemy traps you into clicking a fake link.
* **Real World Definition:** "A technique for attempting to acquire sensitive data through a fraudulent solicitation in email or on a web site." [NIST SP 800-83]