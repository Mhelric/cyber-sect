# CyberSect – Game Rules

## 1. Core Concept
**CyberSect** is a single-player, turn-based card game where you play as a **Blue Team Operator** defending a network. You mitigate threats (Malware) using a deck of **Protocols** (Cards).

## 2. The Operational Loop
1.  **Monitor:** Select a compromised node (Level) on the Map.
2.  **Engage:** Battle waves of malware (Standard: 2 Waves | Boss: 3-4 Waves).
3.  **Remediate:** Reduce Enemy Integrity (HP) to 0 while protecting System Stability (Player HP).
4.  **Analyze:** Victory grants **Cyber Points (CP)** and **Data Logs (Card Rewards)**.
5.  **Patch:** Spend CP at the **Repository (Shop)** to buy cards or upgrade existing ones.
6.  **Certify:** Defeating Chapter Bosses unlocks new **Job Specializations**.

## 3. Operator Progression (Classes)
* **Tier 1: Script Kiddie (Rookie):** Balanced starter stats.
* **Tier 2: Firewall Guardian:** Focuses on Defense (Shields).
* **Tier 2: Antivirus Specialist:** Focuses on Offense (Attacks).
* **Tier 2: Ethical Hacker:** Focuses on Utility (Control/Debuffs).

## 4. Card Architecture
All cards cost **RAM** (Energy) to use. Cards are divided by function, but **any card** can have a specialized effect.

### **Functional Types**
* 🗡️ **Execute (Attack):** Deals damage to Enemy Integrity.
* 🛡️ **Harden (Defense):** Grants **Firewall** (Shield) points.
* 🔧 **Patch (Utility):** Heals, draws cards, or applies Status Effects.

### **The "Signature Match" Mechanic**
**Attack, Defense, and Utility** cards can all have a **Condition**.

* **Generic Cards:** Reliable, mid-range effects that work on everyone. (e.g., "Deal 10 Damage").
* **Specialized Cards:** Have a **Weaker Base Effect** but a **Powerful Bonus** if the target matches a specific malware type.
    * *Example Attack:* **"Deep Clean"** (Deal 5 Dmg. **If Worm:** Deal 25 Dmg).
    * *Example Defense:* **"Traffic Shaper"** (Shield 5. **If DDoS:** Shield 25).
    * *Example Utility:* **"Decryption Tool"** (Heal 5 HP. **If Ransomware:** Remove "Lock" Status).

## 5. Runtime (Turn Structure)
1.  **Fetch Phase:** Draw 2 cards (Hand limit: 10).
2.  **Allocation Phase:** Gain **RAM** (Refills to max, usually 3-4).
* *Rookie/Engineer/Hunter:* Refill to 3 RAM.
* *Pen Tester:* Refill to 4 RAM.
3.  **Execute Phase:** Play cards.
4.  **Intrusion Phase:** Enemy attacks/actions occur.
5.  **Garbage Collection:** Start/End of turn effects resolve (Poison/Stun).

## 6. Defense Metrics

* **Integrity (Health):** If 0, System Crash (Restart Level).
* **Firewall (Shield):** Temporary HP. Resets to 0 at start of turn.
* **RAM (Energy):** Resource to play cards.
* **Throttling:** In Boss battles, reshuffling deck causes Overheating (-5 Integrity).

## 7. Loot & Drop Rates

After winning a battle, the enemy drops a **Data Log** (Card Reward). The quality depends on the enemy Tier.

**Standard Enemies:**
* 40% Common Card
* 10% Uncommon Card
* 50% No Card (CP Only)


**Mini-Bosses:**
* 100% Uncommon Card Choice (Pick 1 of 3)


**Chapter Bosses:**
* 100% Rare Card Choice (Pick 1 of 3)



## 8. The Repository (Shop & Economy)

**Stock:**
Sells 5 Random Cards + Upgrade Station.
Inventory quality increases as you reach higher Chapters.

**Purchasability:**

* Common Card: 50 CP
* Uncommon Card: 120 CP
* Rare Card: 300 CP

## 9. Upgrade System ("Patch Management")

To upgrade a card, you must visit the Repository. You need **Duplicate Copies** of that specific card plus **Cyber Points (CP)** to compile the patch.

### **Upgrade Logic by Rarity**

| Rarity | Upgrade Limit | Logic |
| --- | --- | --- |
| **Common** | **Max Level 3** (Upgrade 2 times) | Highly customizable. Starts weak, but has high potential if you farm duplicates. |
| **Uncommon** | **Max Level 2** (Upgrade 1 time) | Specialized tools. Can be optimized once for better efficiency. |
| **Rare** | **Max Level 1** (No Upgrades) | Enterprise-grade/Proprietary. Powerful out of the box, but code is "Read-Only." |

### **Upgrade Costs & Requirements**

**Common Cards**

* **v1.0  v2.0:** Requires **2 Duplicates** + **50 CP**.
* **v2.0  v3.0 (Max):** Requires **3 Duplicates** + **100 CP**.
* *Effect:* Significant stat increase (e.g., Attack 20  30  45).

**Uncommon Cards**

* **v1.0  v2.0 (Max):** Requires **2 Duplicates** + **150 CP**.
* *Effect:* Cost reduction OR added utility (e.g., Cost 2 RAM  Cost 1 RAM).

**Rare Cards**

* **Status:** **Legacy Code / Closed Source**.
* *Effect:* Cannot be upgraded.

## 10. The CyberDex (Source of Definitions)

The in-game encyclopedia.

**Content:**
Every Card and Enemy has an entry explaining its Game Function and Real World Definition.

**Primary Sources:**
All definitions are sourced from:

1. **NIST (National Institute of Standards and Technology)** - CSRC Glossary.
2. **MITRE ATT&CK Framework** - Tactics and Techniques.
3. **CISA (Cybersecurity and Infrastructure Security Agency)** - Common Vulnerabilities.

**Example Entry:**

* **Game Term:** "Phishing"
* **Game Effect:** Enemy masquerades as a friendly card.
* **Definition:** "A technique for attempting to acquire sensitive data, such as bank account numbers, through a fraudulent solicitation in email or on a web site."
* **Source:** [NIST SP 800-83 Rev. 1]